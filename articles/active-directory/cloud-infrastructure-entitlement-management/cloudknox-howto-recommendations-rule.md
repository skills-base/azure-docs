---
title: Generate, view, and apply rule recommendations in the Autopilot dashboard in CloudKnox Permissions Management 
description: How to generate, view, and apply rule recommendations in the Autopilot dashboard in CloudKnox Permissions Management.
services: active-directory
author: Yvonne-deQ
manager: karenh444
ms.service: active-directory
ms.subservice: ciem
ms.workload: identity
ms.topic: how-to
ms.date: 02/23/2022
ms.author: v-ydequadros
---

# Generate, view, and apply rule recommendations in the Autopilot dashboard

> [!IMPORTANT]
> CloudKnox Permissions Management (CloudKnox) is currently in PREVIEW.
> Some information relates to a prerelease product that may be substantially modified before it's released. Microsoft makes no warranties, express or implied, with respect to the information provided here.
 
This article describes how to generate and view rule recommendations in the CloudKnox Permissions Management (CloudKnox) **Autopilot** dashboard.

> [!NOTE]
> Only users with **Administrator** permissions can view and make changes on the Autopilot tab. If you don’t have these permissions, contact your system administrator.

## Generate rule recommendations 

1. In the CloudKnox home page, select the **Autopilot** tab.
1. In the **Autopilot** dashboard, from the **Authorization system types** dropdown, select Amazon Web Services (**AWS**), Microsoft **Azure**, or Google Cloud Platform (**GCP**).
1. From the **Authorization System** dropdown, in the **List** and **Folders** box, select the account and folder names that you want, and then select **Apply**.  
1. In the **Autopilot** dashboard, select a rule.
1. In the far right of the row, select the ellipses **(...)**.
1. To generate recommendations for each user and the authorization system, select **Generate Recommendations**. 

    Only the user who created the selected rule can generate a recommendation.
1. View your recommendations in the **Recommendations** subtab.
1. Select **Close** to close the **Recommendations** subtab.

## View rule recommendations 

1. In the CloudKnox home page, select the **Autopilot** tab.
1. In the **Autopilot** dashboard, from the **Authorization system types** dropdown, select Amazon Web Services (**AWS**), Microsoft **Azure**, or Google Cloud Platform (**GCP**).
1. From the **Authorization System** dropdown, in the **List** and **Folders** box, select the account and folder names that you want, and then select **Apply**.  
1. In the **Autopilot** dashboard, select a rule.
1. In the far right of the row, select the ellipses **(...)**

1. To view recommendations for each user and the authorization system, select **View Recommendations**. 

    CloudKnox displays the recommendations for each user and authorization system in the **Recommendations** subtab.

1. Select **Close** to close the **Recommendations** subtab.

## Apply rule recommendations 

1. In the CloudKnox home page, select the **Autopilot** tab.
1. In the **Autopilot** dashboard, from the **Authorization system types** dropdown, select Amazon Web Services (**AWS**), Microsoft **Azure**, or Google Cloud Platform (**GCP**).
1. From the **Authorization System** dropdown, in the **List** and **Folders** box, select the account and folder names that you want, and then select **Apply**.  
1. In the **Autopilot** dashboard, select a rule.
1. In the far right of the row, select the ellipses **(...)**

1. To view recommendations for each user and the authorization system, select **View Recommendations**. 

    CloudKnox displays the recommendations for each user and authorization system in the **Recommendations** subtab.

1. To apply a recommendation, select the **Apply Recommendations** subtab, and then select a recommendation.
1. Select **Close** to close the **Recommendations** subtab.

## Unapply rule recommendations 

1. In the CloudKnox home page, select the **Autopilot** tab.
1. In the **Autopilot** dashboard, from the **Authorization system types** dropdown, select Amazon Web Services (**AWS**), Microsoft **Azure**, or Google Cloud Platform (**GCP**).
1. From the **Authorization System** dropdown, in the **List** and **Folders** box, select the account and folder names that you want, and then select **Apply**.  
1. In the **Autopilot** dashboard, select a rule.
1. In the far right of the row, select the ellipses **(...)**

1. To view recommendations for each user and the authorization system, select **View Recommendations**. 

    CloudKnox displays the recommendations for each user and authorization system in the **Recommendations** subtab.

1. To remove a recommendation, select the **Unapply Recommendations** subtab, and then select a recommendation.
1. Select **Close** to close the **Recommendations** subtab.


## Next steps

- For more information about viewing rules, see [View roles in the Autopilot dashboard](cloudknox-ui-autopilot.md).
- For information about creating rules, see [Create a rule](cloudknox-howto-create-rule.md).
- For information about notification settings for rules, see [View notification settings for a rule](cloudknox-howto-notifications-rule.md).
