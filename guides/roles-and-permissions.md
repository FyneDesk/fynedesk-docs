---
title: FyneDesk Roles and Permissions - Admin, Agent, and End User Access
description: FyneDesk uses role-based access control with three roles. Admins manage everything, Agents handle tickets, End Users submit requests via the customer portal. Permissions enforced at database level.
keywords: helpdesk roles, user permissions, role-based access control, admin agent roles, helpdesk permissions, RBAC helpdesk
---

# Roles and Permissions

FyneDesk uses role-based access control (RBAC) to determine what each person in your organization can see and do. There are three roles: Admin, Agent, and End User. Permissions are enforced at the database level, not just the interface.

## Role Overview

| Capability | Admin | Agent | End User |
|-----------|-------|-------|----------|
| View and manage tickets | Yes | Yes | Own tickets only |
| Create tickets | Yes | Yes | Yes (via portal) |
| Assign tickets | Yes | Yes | No |
| Comment on tickets | Yes | Yes | Own tickets only |
| View all contacts | Yes | Yes | No |
| Create and edit contacts | Yes | Yes | No |
| Access knowledge base (internal) | Yes | Yes | No |
| Access knowledge base (published) | Yes | Yes | Yes (via portal) |
| View reporting dashboards | Yes | Yes | No |
| Manage team members (invite, deactivate, change roles) | Yes | No | No |
| Manage settings (org, categories, SLA, themes) | Yes | No | No |
| Manage teams | Yes | No | No |
| Manage asset types | Yes | No | No |
| Create announcements | Yes | No | No |
| View announcements | Yes | Yes | No |
| Access customer portal | No (agent dashboard) | No (agent dashboard) | Yes |

## Admin

Admins have full access to everything in the organization. They can manage settings, invite and deactivate users, change roles, configure SLAs, manage categories and asset types, and access all tickets, contacts, and reports.

Every organization needs at least one Admin. The system prevents the last Admin from being demoted or deactivated to avoid lockout.

## Agent

Agents handle day-to-day support work. They can view, create, update, and comment on tickets. They can manage contacts and use the knowledge base. They can view reports to track their own performance. They cannot access organization settings or manage other users.

## End User

End Users are external people (customers, clients) who access the customer portal. They can submit tickets, view their own ticket history, search the published knowledge base, and add comments to their own tickets. They cannot see other people's tickets or access any internal tools.

## Changing Roles

Admins can change any team member's role from **Settings > Team Members**. Role changes take effect immediately.

## Security

Roles are enforced at the database level, not just in the interface. Hiding a button in the UI does not remove access. FyneDesk enforces permissions through database-level policies, so even if someone tried to access a restricted API endpoint directly, they would be blocked.

The system also prevents role escalation: a non-Admin cannot make themselves an Admin by manipulating requests.
