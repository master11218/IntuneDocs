---
# required metadata

title: Create a group in Microsoft Intune
titleSuffix: 
description: Organize users into groups to make it easier to manage the policies and apps that they can access.
keywords:
author: ErikjeMS
ms.author: erikje
manager: dougeby
ms.date: 02/26/2018
ms.topic: conceptual
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 39a93fb5-d318-4997-a409-b64549a00e7a

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer:
ms.suite: ems
search.appverid: MET150
#ms.tgt_pltfrm:
ms.custom: intune-azure
ms.collection: M365-identity-device-management
---

# Create a group to manage your users and data access

Groups are used to manage your users and control your employees' access to your company resources. These resources can be part of your directory or can be external resources, like SaaS apps or SharePoint sites.

Microsoft Intune uses Azure Active Directory (Azure AD) to manage access to company resources. This access is controlled using roles in the directory. Intune then manages this access for mobile devices, which allows members of that group to access resources.

## How do I create a group?

1. Sign in to the [Azure portal](https://portal.azure.com).
2. Choose **All services** > **Intune**. Intune is located in the **Monitoring + Management** section.
3. Once you've opened the **Microsoft Intune** pane, select **Groups**.
4. On the **Users and groups – All groups** pane, select the **New group** command.
5. On the **Group** pane, choose a **Group type**.
5. Add a **Name** and **Description** for the group.
6. Set the **Membership type** as **Assigned**. Do not **Enable Office features** for the test group.
7. Select **Members** for the group.
7. Click **Create**.

If you've successfully created a group, it should appear in the list of **All groups**. If it doesn't appear there, try to create another group.

## Next steps

[Get started with policies](get-started-policies.md) - Create policies to prevent users from doing unauthorized things with their devices.

## Learn more

* [Set enrollment restrictions using groups in Intune](groups-add.md)
* [Manage access to company resources using groups in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/active-directory-manage-groups)
