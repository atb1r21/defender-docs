---
title: Prerequisites and support in Microsoft Security Exposure Management
description: Review the prerequisites for Microsoft Security Exposure Management.
ms.author: v-mjosephy
author: mjosephym
manager: rayne-wiselman
ms.topic: overview
ms.service: exposure-management
ms.date: 03/11/2024
---

# Prerequisites and support

This article describes the requirements and prerequisites for using Microsoft Security Exposure Management.

Security Exposure Management is currently in public preview.

[!INCLUDE [prerelease](../includes/prerelease.md)]

## Permissions

Permissions are based on [Microsoft Entra ID RBAC](/entra/identity/role-based-access-control/custom-overview). You need a tenant with at least one Global Admin or Security Admin to create a Security Exposure Management workspace.

- For full Security Exposure Management access, user roles need access to all Defender for Endpoint  [device groups](/microsoft-365/security//defender-endpoint/machine-groups).
- Users with scope restrictions to access, such as limits to a specific device group or multiple device groups, can view global exposure insight information, but not specific device information.
- Users with a defined scope don't have access to attack paths and Security Exposure Management advanced hunting tables.

### Permissions for Security Exposure Management tasks

For full access, users need one of the following Microsoft Entra ID roles:

- **Global Admin** (read and write permissions)
- **Global Reader** (read permissions)
- **Security Admin** (read and write permissions)
- **Security Operator** (read and limited write permissions)
- **Security Reader** (read permissions)

Permission levels are summarized in the table.

| Action| Global Admin |Global Reader | Security Admin  | Security Operator | Security Reader |
|---------|---------|---------|---------|---------|---------|
| **Grant permissions to others** | ✔       |  -       |   -      | - | -|
|  **Onboard your organization to the Microsoft Defender External Attack Surface Management (EASM) initiative**   | ✔       |  ✔       |   ✔      | ✔ | ✔ |
|  **Mark initiative as a favorite**   | ✔       |  ✔       |   ✔      | ✔ | ✔ |
| **Set initiative target score** | ✔       |  -       |   -      | - | - |
|  **View general initiatives**  | ✔       |  ✔       |   ✔      | ✔ | ✔ |
|  **Share metric/Recommendations**   | ✔       |  ✔       |   ✔      | ✔ | ✔ |
| **Edit metric weight** | ✔       |  -       |   -      | - | - |
| **Export metric (PDF)** | ✔       |  ✔       |   ✔      | ✔ | ✔ |
|  **View metrics**  | ✔       |  ✔       |   ✔      | ✔ | ✔ |
| **Export assets (metric/recommendation)**  | ✔       |  ✔       |   ✔      | ✔ | ✔ |
|  **Manage recommendations**  |    ✔    | -  |  ✔  |   -      | - |
|  **View recommendations**  | ✔       |  ✔       |   ✔      | ✔ | ✔ |
|  **Export events**  | ✔       |  ✔       |   ✔      | ✔ | ✔ |
|  **Change criticality level**  | ✔       |  ✔       |   ✔      | ✔ | ✔ |
| **Set critical asset rule** | ✔       |  -       |   -      | - | - |
|  **Create criticality rule**  | ✔       |    -    |   ✔      | - | - |
|  **Turn criticality rule on/off**  | ✔       |    -    |   ✔      | ✔ | - |
|  **Run a query on exposure graph data**  |    ✔    |   ✔     |  ✔       | ✔ | ✔ |

## Browser requirements

You can access Security Exposure Management in the Microsoft Defender portal using Microsoft Edge, Internet Explorer 11, or any HTML 5 compliant web browser.

## Getting support

To get support, select the Help question mark icon in the Microsoft Security toolbar.

:::image type="content" source="./media/microsoft-defender-portal-header.png" alt-text="Screenshot of the Microsoft Defender security portal Help button in the portal header bar.":::

You can also engage with the [Microsoft Tech community](https://techcommunity.microsoft.com/).  

## Next steps

[Start using Microsoft Security Exposure Management](get-started-exposure-management.md).