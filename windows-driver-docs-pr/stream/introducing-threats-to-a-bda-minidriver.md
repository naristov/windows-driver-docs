---
title: Introducing Threats to a BDA Minidriver
author: windows-driver-content
description: Introducing Threats to a BDA Minidriver
ms.assetid: 5dabf93a-9a85-4791-958c-59c8e0a99cf4
keywords:
- Broadcast Driver Architecture WDK AVStream , security
- BDA WDK AVStream , security
- security WDK BDA
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Introducing Threats to a BDA Minidriver


## <a href="" id="ddk-introducing-threats-to-a-bda-minidriver-ksg"></a>


The following paths can possibly introduce BDA minidriver threats:

1.  Signal transport stream.

2.  Special-purpose IOCTLs.

3.  Direct WDM dispatch routines.

The following diagram shows how BDA minidriver threats can be introduced:

![diagram illustrating how bda minidriver threats can be introduced](images/bdathret.png)

 

 




