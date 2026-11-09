# Community Engagement Management System

### Microsoft Power Platform | Power Apps | Power Automate | SharePoint | Excel

A Power Platform solution developed to simplify community engagement tracking, centralise activity records and automate weekly KPI reporting.

**Project Status:** Completed - April 2025

**Project Type:** Business Process Automation / Community Operations

---

## Project Overview

Community engagement activities were previously managed manually using spreadsheets, making activity tracking and weekly reporting time-consuming.

This solution was developed based on a real challenge experienced during an internship.

The project brings together a Power Apps Canvas App, SharePoint, Power Automate and an Excel KPI dashboard.

## Business Problem

Manual engagement tracking presented several operational challenges:

- Repetitive spreadsheet data entry
- Disconnected activity records
- Time-consuming weekly reporting
- Difficulty reviewing engagement across platforms

## Solution

The system uses Microsoft Power Platform to support a more structured reporting process.

### 1. Power Apps - Engagement Tracking

A Canvas App provides an interface for recording digital community engagement activities.

### 2. SharePoint - Data Storage

A SharePoint list stores engagement records submitted through the application.

### 3. Power Automate - Weekly Reporting

A scheduled cloud flow automates KPI email reporting every Monday.

### 4. Excel - KPI Dashboard

An Excel dashboard presents engagement reach by platform and activity type.

---

## Solution Architecture

```text
Community Engagement Team
          |
          v
Power Apps Canvas Application
          |
          v
SharePoint List
          |
          +-----------------------+
          |                       |
          v                       v
Power Automate              Excel KPI Dashboard
Scheduled Cloud Flow        Reporting and Analysis
          |
          v
Weekly KPI Email
```

## Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Power Apps | Canvas application for activity entry |
| Microsoft Power Automate | Scheduled weekly KPI email |
| Microsoft SharePoint | Centralised engagement data storage |
| Microsoft Excel | KPI dashboard and reporting |

---

## Application Features

- Digital engagement activity logging
- SharePoint-based data storage
- Scheduled weekly KPI email reporting
- Reach analysis by platform
- Engagement reporting by activity type

---

## Project Screenshots

### Power Apps Canvas Application

![Power Apps](Screenshot%202026-04-15%20211849.png)

### Power Automate Workflow

![Power Automate](Screenshot%202026-04-15%20211853.png)

### SharePoint Data Storage

![SharePoint](Screenshot%202026-04-15%20211859.png)

### Excel KPI Dashboard

![Excel Dashboard](Screenshot%202026-04-15%20211907.png)

---

## Video Demonstration

A walkthrough of the application and its automation workflow is available below.

[Watch the Project Demo](https://www.loom.com/share/23cfe5dc254943c997ab74a8a153a5f0)

---

## Business Value

This project demonstrates how low-code tools can support digital operations by:

- Reducing manual activity logging
- Centralising engagement information
- Automating recurring reporting tasks
- Improving visibility of engagement KPIs
- Supporting data-driven operational decisions

## Technical Skills Demonstrated

- Power Apps Canvas App Development
- SharePoint List Integration
- Power Automate Scheduled Cloud Flows
- Microsoft 365 Workflow Integration
- KPI Reporting and Dashboard Development
- Business Process Improvement

---

## Implementation Notes

The repository includes screenshots and a video demonstration of the project.

Native Power Apps and Power Automate exports have not yet been included.

The separate `power-platform` directory contains learning examples and proposed enhancements. Those examples should not be confused with the completed application.

## Future Enhancements

- Export and document the Canvas App
- Publish a sanitised Power Automate solution export
- Document the SharePoint list schema
- Extend reporting with Power BI
- Explore Dataverse integration
- Add application testing documentation

---

## Project Background

This solution was inspired by a practical operational challenge experienced during an internship.

It demonstrates how Microsoft Power Platform can be used to improve business processes without requiring a traditional full-stack application.

---

## Author

**Pavan Kumar Mukkera**

Microsoft Power Platform | Software Engineering | Data Analytics

[GitHub](https://github.com/pavankumarmukkera)

[LinkedIn](https://www.linkedin.com/in/pavan-kumar-mukkera-b19908188/)