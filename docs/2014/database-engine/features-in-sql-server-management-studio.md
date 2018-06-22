---
title: "Features in SQL Server Management Studio | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dbe-cross-instance"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "SQL Server Management Studio [SQL Server], about SQL Server Management Studio"
  - "scripts [SQL Server], SQL Server Management Studio"
ms.assetid: e75504b9-7968-4e3b-8411-fd79fe09021e
caps.latest.revision: 38
author: "JennieHubbard"
ms.author: "jhubbard"
manager: "jhubbard"
---
# Features in SQL Server Management Studio
  [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] includes the following general features:  
  
-   Supports most administrative tasks for [!INCLUDE[ssNoVersion](../includes/ssnoversion-md.md)].  
  
-   A single, integrated environment for [!INCLUDE[ssDEnoversion](../includes/ssdenoversion-md.md)] management and authoring.  
  
-   Dialogs for managing objects in the [!INCLUDE[ssDEnoversion](../includes/ssdenoversion-md.md)], [!INCLUDE[ssASnoversion](../includes/ssasnoversion-md.md)], and [!INCLUDE[ssRSnoversion](../includes/ssrsnoversion-md.md)], that allows you to execute your actions immediately, send them to a Code Editor, or script them for later execution.  
  
-   Non-modal and resizable dialogs allow access to multiple tools while a dialog is open.  
  
-   A common scheduling dialog that allows you to perform action of the management dialogs at a later time.  
  
-   Exporting and importing [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] server registration from one [!INCLUDE[ssManStudio](../includes/ssmanstudio-md.md)] environment to another.  
  
-   Save or print XML Showplan or Deadlock files generated by SQL Server Profiler, review them later, or send them to administrators for analysis.  
  
-   A new error and informational message box that presents much more information, allows you to send [!INCLUDE[msCoName](../includes/msconame-md.md)] a comment about the messages, allows you to copy messages to the clipboard, and allows you to easily e-mail the messages to your support team.  
  
-   An integrated Web browser for quick browsing of MSDN or online help.  
  
-   Integration of Help from online communities.  
  
-   A tutorial on [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] to help you take advantage of the many new features and become more productive right away.  
  
-   A new activity monitor with filtering and automatic refresh.  
  
-   Integrated Database Mail interfaces.  
  
## New Scripting Capabilities  
 The Code Editor component of [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] contains integrated script editors for authoring [!INCLUDE[tsql](../includes/tsql-md.md)], MDX, DMX, and XML/A. It features:  
  
-   Dynamic Help for immediate access to relevant information while you work.  
  
-   A rich set of templates with the ability to create custom templates.  
  
-   Support for writing and editing queries or scripts without requiring a connection to a server.  
  
-   Scripting support for SQLCMD queries and scripts.  
  
-   A new interface for viewing XML results.  
  
-   Integrated source control for solution and script projects, supporting storing and maintaining copies of scripts as they evolve over time.  
  
-   [!INCLUDE[msCoName](../includes/msconame-md.md)] IntelliSense support for MDX statements.  
  
## Object Explorer Features  
 The Object Explorer component of [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] is an integrated tool for viewing and managing objects in all server types. It features:  
  
-   Filtering by all or part of a name, schema, or date.  
  
-   The asynchronous population of objects, with the ability to filter objects based on their metadata.  
  
-   Access to [!INCLUDE[ssNoVersion](../includes/ssnoversion-md.md)] Agent on replication servers for administration.  
  
 For more information, see [Object Explorer](../ssms/object/object-explorer.md).  
  
## Extensibility  
 [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] is built upon the Visual Studio Isolated Shell, which inherently supports extensibility (add-ins/plug-ins). It is possible to tap into the Visual Studio extensibility services to surface custom capabilities within [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)]; however, such extensibility is not supported.  
  
 There are some users and third parties that have developed extensions to [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)]. While we do not discourage this, keep in mind that such extensibility is not supported, so there may be issues with backward/forward compatibility. Microsoft does not publish documentation for extending [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)]. There are, however, community blogs and sample code that you may be able to leverage.  
  
 Microsoft does not support [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] installations with [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] extensions present, so if you have installed [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] extensions, you may want to remove them before calling Microsoft Customer Support about a [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)] issue.  
  
## See Also  
 [Use SQL Server Management Studio](../database-engine/use-sql-server-management-studio.md)  
  
  