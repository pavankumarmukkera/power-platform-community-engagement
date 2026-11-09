# Community Engagement Tracker - Power Fx Examples

## Microsoft Power Apps Canvas Application

Technology: Power Apps, SharePoint, Power Fx

Status: Sample formulas for learning and demonstration.
These formulas have not been tested in a deployed app.

## 1. Submit Engagement Record

Example OnSelect formula:

```powerfx
If(
    IsBlank(txtActivity.Text),
    Notify("Please enter an activity", NotificationType.Error),
    Patch(
        EngagementRecords,
        Defaults(EngagementRecords),
        {
            Title: txtActivity.Text,
            Platform: txtPlatform.Text,
            Reach: Value(txtReach.Text)
        }
    );
    Notify("Activity recorded", NotificationType.Success)
)
```

## 2. Search Engagement Records

Example gallery Items formula:

```powerfx
Filter(
    EngagementRecords,
    StartsWith(Title, txtSearch.Text)
)
```

## 3. Navigate Between Screens

```powerfx
Navigate(scrDashboard, ScreenTransition.Fade)
```

## 4. Display Total Reach

```powerfx
Sum(EngagementRecords, Reach)
```

## Configuration Notes

Create a SharePoint list named EngagementRecords with:

- Title: Single line of text
- Platform: Single line of text
- Reach: Number

Add the list as a Power Apps data source.

Create the referenced input controls and screens.
Test and adapt these examples in your own environment.
