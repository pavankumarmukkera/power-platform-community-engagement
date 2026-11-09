# Weekly Community Engagement KPI Reporting

## Technology
Microsoft Power Automate, SharePoint, Outlook

## Workflow Design

1. Trigger: Scheduled recurrence every Monday.
2. Retrieve community engagement records from SharePoint.
3. Calculate total engagement and reach.
4. Prepare a weekly KPI summary.
5. Send the summary using Outlook.

## Example Workflow

Recurrence Trigger
    |
    v
SharePoint - Get Items
    |
    v
Data Operations - Select
    |
    v
Calculate KPI Totals
    |
    v
Create HTML Table
    |
    v
Outlook - Send Email

## Implementation Status

This document describes a reference workflow based on
the Community Engagement Tracker project.

It is not an exported or deployable Power Automate flow.

## Future Improvements

- Automated error notifications
- Power BI reporting integration
- Reporting history
- Dataverse integration
