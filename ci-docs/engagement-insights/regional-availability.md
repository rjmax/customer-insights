---
title: Dynamics 365 Customer Insights availability regions
description: Learn more about the regions and geos the service gets deployed to.
author: mkisel11
ms.reviewer: mhart
ms.author: mkisel
ms.date: 09/01/2021
ms.service: customer-insights
ms.topic: article
ms.manager: shellyha
---

# Regional availability for Dynamics 365 Customer Insights

[!INCLUDE [cc-beta-prerelease-disclaimer](includes/cc-beta-prerelease-disclaimer.md)]

Engagement insights, a capability of Dynamics 365 Customer Insights, gradually introduces more regions where customers can choose to store their data. Admins can choose a region when they [create a new environment](manage-environments-workspaces.md#create-an-environment). 

When you set up engagement insights for the first time, you can choose the region while going through the [guided first-run experience](quickstart.md). Later, every new environment allows you to choose the region that the data will be stored in.

Currently there are two geographies: USA and Europe. Users can choose between the West US region and the North Europe region.

An organization can maintain environments in different regions. For example, Environment A stores data in West US and Environment B in North Europe.

> [!NOTE]
> After choosing a region during environment creation, you won't be able to change that setting. To change the region, an environment admin has to [delete the environment](manage-environments-workspaces.md#delete-an-environment) and create a new environment with the updated region setting.


[!INCLUDE[footer-include](../includes/footer-banner.md)]
