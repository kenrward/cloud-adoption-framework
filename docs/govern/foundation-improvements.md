---
title: "Improve your initial cloud governance foundation"
titleSuffix: Microsoft Cloud Adoption Framework for Azure
description: Learn how to incrementally improve your initial cloud governance foundation.
author: BrianBlanchard
ms.author: brblanch
ms.date: 09/13/2019
ms.topic: landing-page
ms.service: cloud-adoption-framework
ms.subservice: govern
ms.custom: governance
layout: LandingPage
---

# Improve your initial cloud governance foundation

This article assumes that you have established an [initial cloud governance foundation](./initial-foundation.md). As your cloud adoption plan is implemented, tangible risks will emerge from the proposed approaches by which teams want to adopt the cloud. As these risks surface in release planning conversations, use the following grid to quickly identify a few best practices for getting ahead of the adoption plan to prevent risks from becoming real threats.

## Maturity vectors

At any time, the following best practices can be applied to the initial governance foundation to address the risk or need mentioned in the table below.

> [!IMPORTANT]
> Resource organization can affect how these best practices are applied. It is important to start with the recommendations that best align with the initial cloud governance foundation you implemented in the previous step.

|Risk/Need | Standard Enterprise | Complex Enterprise |
|---|---|---|
|Sensitive data in the cloud|[Discipline improvement](./guides/standard/security-baseline-improvement.md)|[Discipline improvement](./guides/complex/security-baseline-improvement.md)|
|Mission critical apps in the cloud|[Discipline improvement](./guides/standard/resource-consistency-improvement.md)|[Discipline improvement](./guides/complex/resource-consistency-improvement.md)|
|Cloud cost management|[Discipline improvement](./guides/standard/cost-management-improvement.md)|[Discipline improvement](./guides/complex/cost-management-improvement.md)|
|Multicloud|[Discipline improvement](./guides/standard/multicloud-improvement.md)|[Discipline improvement](./guides/complex/multicloud-improvement.md)|
|Complex/legacy identity management|N/A|[Discipline improvement](./guides/complex/identity-baseline-improvement.md)|
|Multiple layers of governance|N/A|[Discipline improvement](./guides/complex/multiple-layers-of-governance.md)|

## Next steps

In addition to the application of best practices, the governance methodology in the Cloud Adoption Framework can be customized to fit unique business constraints. After following the applicable recommendations, [evaluate corporate policy to understand additional customization requirements](./corporate-policy.md).

> [!div class="nextstepaction"]
> [Evaluate corporate policy](./corporate-policy.md)
