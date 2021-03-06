---
title: "Command Routing in VSPackages | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
helpviewer_keywords: 
  - "commands, routing"
  - "command routing, Visual Studio SDK"
ms.assetid: a9c7f9ae-3594-4557-a314-8cf76f5f8772
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# Command routing in VSPackages
A command is routed in [!INCLUDE[vsprvs](../../code-quality/includes/vsprvs_md.md)] based on the context in which it is executed. It is routed from the initial context outward to the global context.  
  
## In this section  
 [Command routing algorithm](../../extensibility/internals/command-routing-algorithm.md)  
 Describes the order of command routing resolution.  
  
 [Command availability](../../extensibility/internals/command-availability.md)  
 Discusses command routing.  
  
 [Commands and menus that use interop assemblies](../../extensibility/internals/commands-and-menus-that-use-interop-assemblies.md)  
 Discusses considerations in routing commands between managed code and COM.  
  
## Related sections  
 [Selection context objects](../../extensibility/internals/selection-context-objects.md)  
 Discusses the model for how you can determine the user's selection context focus on a window.  
  
 [Commands, menus, and toolbars](../../extensibility/internals/commands-menus-and-toolbars.md)  
 Explains how to create a UI that includes menus, toolbars, and command combo boxes.