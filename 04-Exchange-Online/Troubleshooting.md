# Troubleshooting

## Issue 1

### Shared mailbox not appearing in Outlook

Cause

Mailbox delegation had not fully synchronized.

Resolution

- Waited approximately 15 minutes.
- Signed out and back into Outlook.
- Opened the mailbox using **Open another mailbox**.

Status

✅ Resolved

---

## Issue 2

### User unable to send as Helpdesk

Cause

Send As permission had not replicated.

Resolution

- Verified Send As permission in Exchange Admin Center.
- Allowed replication to complete.
- Tested again successfully.

Status

✅ Resolved

---

## Issue 3

### Distribution Group email not received

Cause

Membership changes had not propagated.

Resolution

- Verified group membership.
- Waited for Exchange Online synchronization.
- Resent the email.

Status

✅ Resolved

---

## Issue 4

### Shared mailbox access denied

Cause

User was missing Full Access permission.

Resolution

- Assigned Full Access.
- Waited for permission replication.
- Reopened Outlook.

Status

✅ Resolved

---

## Issue 5

### Mailbox not created after assigning license

Cause

Exchange Online provisioning delay.

Resolution

- Waited for mailbox provisioning.
- Refreshed Exchange Admin Center.
- Verified mailbox creation.

Status

✅ Resolved

---

## Lessons Learned

- Exchange Online changes may require synchronization time.
- Mailbox delegation should be verified after permissions are assigned.
- Distribution Groups should always be validated using real email delivery tests.
- Shared mailboxes do not require a Microsoft 365 license unless their storage exceeds Microsoft's limits or advanced features are needed.
