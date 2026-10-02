# Laboratory Operations SPFx Dashboard

> SharePoint Framework portfolio project demonstrating a React and TypeScript operational dashboard for laboratory request visibility in SharePoint Online.

![Laboratory Operations SPFx Dashboard](screenshots/laboratory-operations-spfx-dashboard.png)

## Project Overview

The Laboratory Operations Dashboard provides laboratory staff with a focused SharePoint experience for monitoring request activity. It complements the broader Enterprise Laboratory Request Management solution and demonstrates how a custom SPFx web part can provide a purpose-built operational interface inside SharePoint Online.

## Business Need

The dashboard is designed to provide:

- At-a-glance request indicators
- Request status visibility
- Search and filtering
- A focused SharePoint user experience
- A reusable web part deployable through the Microsoft 365 App Catalog

## Solution Architecture

```text
SharePoint Online
Laboratory Requests Data
        |
        v
SharePoint REST API / SPHttpClient
        |
        v
SPFx Web Part
React + TypeScript
        |
        v
Laboratory Operations Dashboard
KPIs | Search | Filters | Status
```

## Technology Stack

| Technology | Purpose |
|---|---|
| SharePoint Framework (SPFx) | Client-side web part framework |
| React | Dashboard user interface |
| TypeScript | Typed application logic |
| SharePoint Online | Hosting and collaboration platform |
| SharePoint REST API | Request data access |
| SPHttpClient | SharePoint-aware HTTP communication |
| SCSS | Component styling |
| Microsoft 365 App Catalog | SPFx package deployment |

## Dashboard Capabilities

- Total request indicator
- Pending request indicator
- In-progress request indicator
- Completed request indicator
- Searchable and filterable request data
- Request status visibility
- SharePoint-hosted operational experience

## Relationship to the Power Platform Solution

This dashboard is the SharePoint/SPFx component of the larger **Enterprise Laboratory Request Management** portfolio solution. The broader solution uses Power Apps and Dataverse for structured request management and Power Automate for workflow automation.

## Deployment Approach

1. Develop and test the SPFx web part.
2. Build and bundle the solution.
3. Package it as an `.sppkg` application.
4. Upload the package to the Microsoft 365 App Catalog.
5. Deploy/enable the solution.
6. Install it on the Laboratory Operations SharePoint site.
7. Add the dashboard web part to the target page.
8. Validate permissions, data access, filtering, and responsive behavior.

## Repository Structure

```text
laboratory-operations-spfx-dashboard/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── architecture.md
│   └── deployment.md
└── screenshots/
    └── laboratory-operations-spfx-dashboard.png
```

## What This Project Demonstrates

- SharePoint Framework solution design
- React and TypeScript
- SharePoint REST API / SPHttpClient integration
- Operational dashboard design
- Search and filtering concepts
- SharePoint Online integration
- Microsoft 365 App Catalog deployment
- Integration with a broader Power Platform architecture

## Source-Code Note

This repository documents the SPFx solution we built and includes the preserved dashboard screenshot. The complete original local SPFx source tree is not available in the current project files, so this repository does **not** present reconstructed sample code as if it were the original implementation.

## Portfolio Safety

Tenant identifiers, credentials, connection information, production records, and other environment-specific or sensitive information are excluded.

---

**Author:** Netsanet Ayalew  
**Focus:** SharePoint Framework · React · TypeScript · SharePoint Online · Microsoft Power Platform
