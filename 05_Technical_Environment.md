# Technical Environment Reference

## Purpose

This document gives the Project Manager Agent enough technical context
to understand web development discussions and identify
project-management impacts.

The agent should not assume that every project uses every technology
listed here.

## Common Backend Technologies

-   Laravel
-   PHP

## Common Frontend Technologies

-   Blade
-   Bootstrap
-   JavaScript
-   DataTables

## Database

-   MySQL
-   SQL views
-   Multiple database connections where applicable

## Development and Source Control

-   Git
-   GitHub
-   GitHub Actions

## Hosting / Deployment

Possible environments include:

-   Local development
-   Staging
-   cPanel
-   Apache
-   Proxmox
-   Production servers

## Notifications / Real-Time Features

Possible technologies include:

-   Pusher
-   Laravel Reverb

Use only the technology confirmed by the specific project.

## Authentication

Projects may use:

-   Standard application authentication
-   Microsoft Entra / Microsoft Graph
-   Single Sign-On
-   Project-specific authentication

Do not assume an authentication method without project information.

## Legacy System Considerations

Some existing systems may have:

-   Database structures created directly without migrations
-   Inconsistent primary-key naming
-   Legacy SQL views
-   Raw DB queries
-   Multiple database connections
-   Business logic inside controllers
-   Inconsistent controller naming
-   Existing modules that do not follow current Laravel conventions

When managing work in a legacy system:

1.  Understand the existing architecture.
2.  Avoid assuming a clean-slate architecture.
3.  Identify technical debt only when it affects delivery, security,
    maintainability, or scope.
4.  Avoid proposing large refactoring projects unless they are
    explicitly required.
5.  Consider backward compatibility and impact on existing modules.

## Technical Discussion Rule

The PM Agent should understand enough technical detail to answer:

-   What is blocking development?
-   What dependency is missing?
-   What environment is affected?
-   What component may be impacted?
-   What is the likely project impact?
-   What needs clarification from the developer?

It should not automatically turn every PM question into a coding
solution.
