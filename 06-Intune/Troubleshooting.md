# Possible issues and troubleshooting steps

## Issue 1

### Unable to locate specific Settings Catalog options

**Cause**

Microsoft frequently updates the Intune Settings Catalog, and available settings may differ between tenants and service versions.

**Resolution**

Configured equivalent Microsoft Defender and Windows security settings available within the current tenant.

**Status**

✅ Resolved

---

## Issue 2

### No devices displayed in Intune

**Cause**

No Windows devices had been enrolled.

**Resolution**

Confirmed that this is expected for the current phase of the lab. Device enrollment is planned for a later stage.

**Status**

✅ Resolved

---

## Issue 3

### Unable to assign policies to devices

**Cause**

No managed devices existed within the tenant.

**Resolution**

Created the **Windows Managed Devices** security group and assigned policies to this group in preparation for future device enrollment.

**Status**

✅ Resolved

---

## Lessons Learned

- Intune policies can be configured before devices are enrolled.
- Settings Catalog options may vary between tenants and Microsoft service updates.
- Preparing policy assignments in advance streamlines future endpoint onboarding.

---

## Skills Demonstrated

- Microsoft Intune Troubleshooting
- Endpoint Management
- Policy Administration
- Enterprise Problem Solving
