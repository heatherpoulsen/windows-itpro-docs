---
title: How to Enable Only Administrators to Publish Packages by Using an ESD (Windows 10)
description: How to Enable Only Administrators to Publish Packages by Using an ESD
author: MaggiePucciEvans
ms.pagetype: mdop, appcompat, virtualization
ms.mktglfcycl: deploy
ms.sitesec: library
ms.prod: w10
---


# How to Enable Only Administrators to Publish Packages by Using an ESD

**Applies to**
-   Windows 10, version 1607

Starting in App-V 5.0 SP3, you can configure the App-V client so that only administrators (not end users) can publish or unpublish packages. In earlier versions of App-V, you could not prevent end users from performing these tasks.

**To enable only administrators to publish or unpublish packages**

1.  Navigate to the following Group Policy Object node:

    **Computer Configuration &gt; Administrative Templates &gt; System &gt; App-V &gt; Publishing**.

2.  Enable the **Require publish as administrator** Group Policy setting.

    To instead use Windows PowerShell to set this item, see [How to Manage App-V Packages Running on a Stand-Alone Computer by Using Windows PowerShell](appv-manage-appv-packages-running-on-a-stand-alone-computer-with-powershell.md#bkmk-admins-pub-pkgs).

## Have a suggestion for App-V?

Add or vote on suggestions on the [Application Virtualization feedback site](http://appv.uservoice.com/forums/280448-microsoft-application-virtualization).<br>For App-V issues, use the [App-V TechNet Forum](https://social.technet.microsoft.com/Forums/en-US/home?forum=mdopappv).
