# Ticketing

Ticketing is the core of FyneDesk. Every customer request, internal issue, or service inquiry becomes a ticket that your team can track from creation to resolution.

## Creating Tickets

Tickets can be created in three ways:

1. **Manually** — Any agent or admin can create a ticket from the Tickets page
2. **Email to Ticket** — Customers email your support address and a ticket is created automatically
3. **Client Portal** — Customers submit tickets through your self-service portal

## Ticket Fields

Every ticket includes:

- **Ticket Number** — Auto-generated with your org prefix (e.g., SUP-001)
- **Title** — Short summary of the issue
- **Description** — Full details
- **Status** — New, Active, Pending, Solved, Closed
- **Priority** — Low, Medium, High, Urgent
- **Category** — Configurable categories (e.g., Billing, Technical, General)
- **Ticket Type** — Request, Incident, or Question
- **Assigned To** — The agent or team member responsible
- **Requester** — The contact or profile who submitted the request
- **Created At / Updated At** — Timestamps

## Ticket Lifecycle

Tickets follow this flow:

**New** → **Active** → **Pending** (optional) → **Solved** → **Closed**

- **New**: Just created. No one has started working on it.
- **Active**: An agent is working on the issue.
- **Pending**: Waiting on the requester or a third party.
- **Solved**: A resolution has been provided.
- **Closed**: Confirmed resolved. The ticket is complete.

## Comments

Each ticket has a comment thread where agents and requesters can communicate. Comments create a full audit trail of the conversation.

## Activity Log

Every change to a ticket is automatically logged: status changes, priority changes, assignments, and more. This provides a complete audit trail for accountability and reporting.

## Attachments

Agents and requesters can attach files to tickets (screenshots, documents, logs). Files are stored securely and scoped to your organization.

## Filtering and Search

The ticket list supports:
- Filtering by status, priority, category, assignee, and date range
- Sorting by any column
- Pagination for large ticket volumes

## SLA Tracking

FyneDesk tracks key timestamps for SLA measurement:
- **First Response Time** — How quickly an agent first responds
- **Resolution Time** — How long until the ticket is solved
- **Close Time** — When the ticket is fully closed

Configure SLA targets in Settings to measure your team's performance.
