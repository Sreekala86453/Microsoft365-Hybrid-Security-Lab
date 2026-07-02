# Role-Based Access Control (RBAC)

## Objective

Implement Microsoft Entra ID Role-Based Access Control (RBAC) by assigning built-in administrative roles based on the principle of least privilege. Each role grants only the permissions required for the user's responsibilities, reducing security risks while maintaining effective administration.

---

## Administrative Role Assignments

| Role | Assigned User | Assignment Type |
|------|---------------|-----------------|
| Global Administrator | Sreekala Sreedharan | Active |
| Helpdesk Administrator | Emily Davis | Active |
| User Administrator | David Wilson | Eligible (Microsoft Entra PIM) |
| Intune Administrator | John Smith | Active |

---

# Global Administrator

**Assigned User:** Sreekala Sreedharan

**Assignment Type:** Active

**Purpose**

The Global Administrator role was assigned to the primary tenant administrator responsible for managing all Microsoft 365 services, Microsoft Entra ID, licensing, security, and tenant-wide configurations.

**Responsibilities**

- Manage Microsoft 365 tenant configuration
- Create and manage users and groups
- Assign licenses
- Configure Microsoft Entra ID
- Configure Exchange Online
- Configure Microsoft Intune
- Manage Microsoft Defender
- Configure Conditional Access policies
- Configure Microsoft Sentinel
- Manage Azure integrations
- Delegate administrative roles

**Business Justification**

Assigned as the primary Microsoft 365 administrator responsible for the complete administration and governance of the Microsoft 365 lab environment.

---

# Helpdesk Administrator

**Assigned User:** Emily Davis

**Assignment Type:** Active

**Purpose**

The Helpdesk Administrator role was assigned to the Helpdesk Technician to provide first-line support for user accounts while maintaining the principle of least privilege.

**Responsibilities**

- Reset user passwords
- Unlock user accounts
- Assist users with sign-in issues
- Force password changes
- Manage support requests
- Perform basic identity administration

**Business Justification**

Assigned to provide end-user support and account management without granting unnecessary administrative privileges.

---

# User Administrator

**Assigned User:** David Wilson

**Assignment Type:** Eligible (Microsoft Entra Privileged Identity Management)

**Purpose**

The User Administrator role was assigned using Microsoft Entra Privileged Identity Management (PIM) to demonstrate Just-In-Time (JIT) privileged access for identity management tasks.

**Responsibilities**

- Create users
- Delete users
- Update user properties
- Manage security groups
- Manage Microsoft 365 group memberships
- Assign licenses
- Reset passwords for standard users

**Business Justification**

Assigned as an Eligible role through Microsoft Entra PIM to reduce standing administrative privileges while allowing identity administration when activated.

---

### Microsoft Entra Privileged Identity Management (PIM)

The **User Administrator** role was assigned as an **Eligible** role using Microsoft Entra Privileged Identity Management (PIM). This implements a Just-In-Time (JIT) access model where administrative privileges are activated only when required, reducing standing privileged access and improving the organization's security posture.

This project demonstrates both:
- Traditional active role assignments for operational administration.
- Eligible role assignments through PIM following the principle of least privilege.

---

# Intune Administrator

**Assigned User:** John Smith

**Assignment Type:** Active

**Purpose**

The Intune Administrator role was assigned to manage endpoint administration using Microsoft Intune, including device enrollment, compliance policies, and configuration profiles.

**Responsibilities**

- Manage Microsoft Intune
- Enroll Windows devices
- Create Compliance Policies
- Deploy Configuration Profiles
- Configure Endpoint Security
- Manage Windows Autopilot
- Monitor enrolled devices
- Troubleshoot device management issues

**Business Justification**

Assigned to manage Microsoft Intune endpoint administration and ensure compliant and secure device management across the Microsoft 365 environment.

---

# Security Best Practices Implemented

- Principle of Least Privilege (PoLP)
- Role-Based Access Control (RBAC)
- Delegated Administration
- Microsoft Entra Privileged Identity Management (PIM)
- Just-In-Time (JIT) Administration
- Separation of Duties

---

# Validation

The following administrative roles were successfully configured and verified:

- Global Administrator
- Helpdesk Administrator
- User Administrator
- Intune Administrator

Role assignments were validated through the Microsoft Entra Admin Center under **Identity → Roles & administrators**.

Eligible assignments were verified using **Microsoft Entra Privileged Identity Management (PIM)**.

---

# Skills Demonstrated

- Microsoft Entra ID Administration
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Microsoft Entra Privileged Identity Management (PIM)
- Delegated Administration
- Microsoft Intune Administration
- Microsoft 365 Security Administration
- Principle of Least Privilege
