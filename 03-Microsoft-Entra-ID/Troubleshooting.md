# Possible issues might be encountered & Troubleshooting Steps

## Issue 1 – Unable to create a user

### Symptoms

User creation fails.

### Possible Causes

- Duplicate User Principal Name (UPN)
- Missing required fields
- Insufficient administrative permissions

### Resolution

- Verify the UPN is unique.
- Complete all required fields.
- Ensure the account has Global Administrator or User Administrator permissions.

---

## Issue 2 – Unable to assign Microsoft 365 license

### Symptoms

License assignment fails.

### Possible Causes

- Usage location not configured
- No available licenses
- License provisioning delay

### Resolution

- Set the user's Usage Location (Canada).
- Verify available Microsoft 365 E5 licenses.
- Refresh the portal after a few minutes.

---

## Issue 3 – Administrative role appears as Eligible instead of Active

### Symptoms

The assigned administrator role is listed under Eligible Assignments.

### Cause

Microsoft Entra Privileged Identity Management (PIM) is enabled, resulting in Just-In-Time (JIT) role assignments.

### Resolution

- Activate the role through Microsoft Entra PIM when required.
- Alternatively, assign the role as Active if permanent administrative access is appropriate for the lab scenario.

---

## Issue 4 – Unable to assign administrative role

### Symptoms

Assignment wizard displays validation errors.

### Possible Causes

- Missing business justification
- Required fields incomplete
- Insufficient permissions

### Resolution

- Enter a business justification.
- Verify assignment type and dates.
- Confirm Global Administrator privileges.

---

## Issue 5 – Group membership not updating

### Symptoms

Users do not appear in the expected security group.

### Resolution

- Refresh the Microsoft Entra Admin Center.
- Verify the correct group membership type.
- Confirm that changes have been saved successfully.
