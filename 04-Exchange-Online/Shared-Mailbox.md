# Shared Mailbox

## Overview

A shared mailbox named **Helpdesk** was created to provide centralized email management for the IT support team.

Shared mailboxes enable multiple users to read and respond to emails using a common identity without requiring a separate Microsoft 365 license.

---

## Mailbox Configuration

| Property | Value |
|----------|-------|
| Mailbox Name | Helpdesk |
| Email Address | helpdesk@examlabpractice820.onmicrosoft.com |
| Mailbox Type | Shared Mailbox |
| License | Not Required |

The Helpdesk shared mailbox does **not** require a separate Microsoft 365 license because it is accessed by licensed users through delegated permissions.

---

## Mailbox Delegation

The Helpdesk shared mailbox was configured to allow multiple IT support staff to access and manage support emails.

### Delegated Permissions

| User | Full Access | Send As |
|------|-------------|---------|
| Emily Davis | ✅ | ✅ |
| John Smith | ✅ | ✅ |

### Permission Summary

**Full Access**
- Open the shared mailbox
- Read emails
- Manage mailbox folders
- Delete or move messages

**Send As**
- Send emails that appear to come directly from the Helpdesk mailbox
- Respond to support requests using the shared mailbox identity

### Business Justification

Delegating Full Access and Send As permissions enables multiple Helpdesk technicians to collaborate on customer support requests using a single organizational mailbox while maintaining consistent communication.

---

## Business Scenario

The Helpdesk mailbox provides a single communication channel for IT support requests.

Support technicians can:

- Read incoming support requests
- Reply as Helpdesk
- Manage customer communications
- Maintain a centralized support history

---

## Validation

The following validation steps were completed:

- Shared mailbox created successfully.
- Members added.
- Full Access permission verified.
- Send As permission verified.
- Emily Davis successfully opened the mailbox in Outlook.
- Email successfully sent from the Helpdesk mailbox.
- Recipient successfully received the message.

---

## Skills Demonstrated

- Shared Mailbox Administration
- Mailbox Delegation
- Exchange Online

