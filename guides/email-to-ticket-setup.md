---
title: How to Set Up Email-to-Ticket in FyneDesk
description: Step-by-step guide to setting up email-to-ticket in FyneDesk. Customers email your support address and tickets are created automatically with subject, body, and sender captured.
keywords: email to ticket setup, how to set up email ticketing, automatic email to ticket, email support setup, helpdesk email configuration
---

# How to Set Up Email-to-Ticket

Email-to-ticket lets your customers send an email to a support address and have it automatically created as a ticket in FyneDesk. No manual data entry, no copy-pasting. This guide walks through how it works and how to get the most out of it.

## How It Works

1. Your organization gets a dedicated support email address in the format: **support-yourslug@fynedesk.io**
2. Share this address with your customers (on your website, in email signatures, on business cards)
3. When a customer sends an email to that address, FyneDesk automatically creates a ticket
4. The ticket includes the email subject as the title, the email body as the description, and the sender as the requester
5. If the sender's email matches an existing contact, the ticket is linked to that contact's record
6. If the sender is new, a contact record is created automatically

## Finding Your Support Email

Go to **Settings > Organization** to see your organization's support email address. This address is created automatically when your organization is set up.

## What Gets Captured

- **Subject line** becomes the ticket title
- **Email body** becomes the ticket description
- **Sender email** is matched to an existing contact or creates a new one
- **Attachments** are captured (on plans that support attachments)

## Configuring Your Public-Facing Email

You have two options for how customers reach you:

### Option 1: Share the FyneDesk address directly
Give customers your support-yourslug@fynedesk.io address. Simple, works immediately.

### Option 2: Forward from your own domain
Set up email forwarding from your own address (e.g., support@yourcompany.com) to your FyneDesk support address. This way customers see your brand, and emails still arrive as tickets. Check your email provider's documentation for forwarding setup.

## Tips

- **Set expectations:** Let customers know they'll receive a confirmation when their ticket is created
- **Use a clear subject line policy:** Encourage customers to use descriptive subject lines, since these become ticket titles
- **Monitor the queue:** Email-to-ticket creates tickets with "New" status. Assign or triage them promptly
- **Check contact matching:** If a customer emails from multiple addresses, they may create duplicate contacts. Merge them from the Contacts page

## Troubleshooting

- **Emails not creating tickets?** Verify the email address is correct (check for typos in the slug). Check Settings > Organization for the exact address.
- **Duplicate tickets?** This can happen if the same email is forwarded multiple times. FyneDesk tracks message IDs to prevent duplicates where possible.
- **Missing attachments?** Attachment support depends on your plan. Check your plan features.
