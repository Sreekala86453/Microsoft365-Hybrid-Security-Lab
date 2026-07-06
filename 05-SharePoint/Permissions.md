# SharePoint Permissions

## Overview

SharePoint permissions were configured using the default SharePoint permission groups to provide secure collaboration while simplifying administration.

---

## Permission Groups

| Group | Members | Permission |
|---------|----------|------------|
| Owners | Sreekala Sreedharan | Full Control |
| Members | John Smith, Emily Davis, David Wilson, Sarah Lee, Michael Brown | Edit |
| Visitors | None | Read |

---

## Permission Model

The SharePoint Team Site uses the default SharePoint permission groups.

All authenticated site members inherit **Edit** permissions through the **Members** group, allowing them to collaborate on documents and site content.

Unique permissions were not configured for individual folders or document libraries during this phase of the lab. Folder-level security will be implemented in a future advanced SharePoint and Microsoft Purview section.

---

## Business Justification

Using inherited permissions:

- Simplifies administration
- Reduces permission complexity
- Supports collaboration
- Follows Microsoft SharePoint best practices

---

## Validation

Confirmed:

- Members can access the site.
- Members can upload and edit documents.
- Owner retains Full Control.
- Unauthorized users cannot access the site.

---

## Skills Demonstrated

- SharePoint Security
- Role-Based Access Control (RBAC)
- Site Permission Management
- Collaboration Security
- Microsoft 365 Administration
