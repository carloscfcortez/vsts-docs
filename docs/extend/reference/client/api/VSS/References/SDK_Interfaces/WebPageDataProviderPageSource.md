---
title: VSS/References/SDK.Interfaces WebPageDataProviderPageSource API | Extensions for Visual Studio Team Services
description: Contextual data for web-page-related data providers about the originating (host/source) page
ms.assetid: 851f3787-a045-eca0-354f-5de943261595
ms.prod: vs-devops-alm
ms.technology: vs-devops-extensions-api
generated: true
ms.manager: douge
ms.author: elbatk
ms.date: 08/04/2016
---

# WebPageDataProviderPageSource

Defined in vss.d.ts


Contextual data for web-page-related data providers about the originating (host/source) page 

### Members

* `navigation`: [NavigationContext](../../../VSS/References/SDK_Interfaces/NavigationContext.md). The navigation context for the host page that is loading the data provider

* `project`: [ContextIdentifier](../../../VSS/References/SDK_Interfaces/ContextIdentifier.md). The project context for the host page that is loading the data provider

* `team`: [TeamContext](../../../VSS/References/SDK_Interfaces/TeamContext.md). The team context for the host page that is loading the data provider

* `url`: string. The url of the host page that is loading the data provider

