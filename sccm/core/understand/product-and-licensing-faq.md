---
title: Product and Licensing FAQ
titleSuffix: Configuration Manager
description: Find answers for common product and license questions for System Center Configuration Manager.
ms.date: 07/30/2018
ms.prod: configuration-manager
ms.technology: configmgr-other
ms.topic: conceptual
ms.assetid: ee8d611f-aa0c-4efd-b0ad-dbd14d0a0623
author: aczechowski
ms.author: aaroncz
manager: dougeby
ms.collection: M365-identity-device-management
---
# Frequently asked questions for Configuration Manager branches and licensing

 *Applies to: System Center Configuration Manager (Current Branch), System Center Configuration Manager (Long-Term Servicing Branch)*

## Summary
This FAQ addresses common licensing questions about System Center Configuration Manager Current Branch and Long-Term Servicing Branch (LTSB) versions, available through Microsoft Volume Licensing programs. This article is for informational purposes. It does not supersede or replace any documentation covering System Center Configuration Manager licensing. For more information, see the product licensing for [System Center 2016](https://www.microsoft.com/en-us/licensing/product-licensing/system-center-2016.aspx)<!-- this link doesn't work without some language code --> and the [Product Terms](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=53). The Product Terms describe the use terms for all Microsoft products in Volume Licensing.

For more information about Configuration Manager features, see the [product page](https://www.microsoft.com/cloud-platform/system-center-configuration-manager).




## Product and licensing FAQ

### <a name="bkmk_cb"></a> What is Current Branch?  
The Current Branch is the production ready build of System Center Configuration Manager that provides an active servicing model. This servicing model is like the experience with Windows 10 or the Windows Server 2016 Nano Server installation option. This approach supports customers who are moving at a "cloud cadence" and wish to innovate more quickly. With the Current Branch servicing model, System Center Configuration Manager customers continue to receive new features and functionality. For this reason, only customers with active Software Assurance on System Center Configuration Manager licenses, or with equivalent subscription rights, may install and use the Current Branch of System Center Configuration Manager.


### <a name="bkmk_ltsb"></a> What is Long Term Servicing Branch (LTSB)?  
The Long-Term Servicing Branch is a production ready build of System Center Configuration Manager. It is intended for customers who allow Software Assurance or equivalent subscription rights to expire. When compared to the Current Branch, the LTSB has [reduced functionality](/sccm/core/understand/introduction-to-the-ltsb#features-that-are-not-available-in-the-ltsb-of-configuration-manager). Customers who allow Software Assurance or equivalent subscription rights to expire must uninstall the Current Branch of System Center Configuration Manager. Customers who have perpetual license rights to System Center Configuration Manager may then install and use the LTSB build of the version of System Center Configuration Manager that is current at the time of expiration.


### <a name="bkmk_licensing-acronyms"></a> I've seen SA and L&SA used in licensing content. What do these acronyms mean in regard to System Center Configuration Manager?    
Both SA (Software Assurance) and L&SA (License and Software Assurance) are license options that grant rights to use System Center Configuration Manager. SA is an option for a customer that is renewing SA coverage from a prior agreement. L&SA is an option for a customer buying a new license and SA coverage.
  - **Software Assurance (SA)**: Customers must have active SA on System Center Configuration Manager licenses, or equivalent subscription rights, in order to install and use the Current Branch option of System Center Configuration Manager.    

    - While SA is optional for some Microsoft products, the only way to get rights to use System Center Configuration Manager Current Branch is with SA *(or equivalent subscription rights)*. For more information, see the [Software Assurance FAQ](https://www.microsoft.com/en-us/licensing/licensing-programs/FAQ-Software-Assurance.aspx).<!--this link doesn't work without some language code-->

  - **Microsoft License and Software Assurance (L&SA)**: Customers buying new licenses for System Center Configuration Manager must acquire L&SA (the license and SA coverage).   

    - The SA grants rights to use the Current Branch.

    - If your SA expires, and you still have a license for System Center Configuration Manager, you can no longer use the Current Branch. For more information, see the FAQ [If my SA expires and I had L&SA, what do I get?](#bkmk_sa-expires)

For more information about license offerings, see [Ways to buy](https://www.microsoft.com/en-us/licensing/licensing-programs)<!--this link doesn't work without some language code--> and [Licensing Product Terms](http://www.microsoftvolumelicensing.com/ProductResults.aspx?doc=Product%20Terms,OST&fid=64).  


### <a name="bkmk_equiv-sub"></a> I read the term "equivalent subscription", what programs does that refer to?   
Equivalent subscriptions refer to programs like [Enterprise Mobility + Security](http://www.microsoftvolumelicensing.com/ProductResults.aspx?doc=Product%20Terms,OST&fid=51) (EMS) or [Microsoft 365 Enterprise](https://www.microsoft.com/microsoft-365/enterprise). There can be others, but these programs are the most common. The Microsoft Volume Licensing Product Terms refers to these programs as Management License Equivalent Licenses.


### <a name="bkmk_ems-expires"></a> I have Enterprise Mobility + Security and it expired, what must I do now?  
EMS grants rights to use System Center Configuration Manager (Current Branch and Long-Term Service Branch). When these rights expire, you no longer have rights to use either branch and must uninstall.  


### <a name="bkmk_sa-expires"></a> If my SA expires, and I had L&SA, what do I get?   
If your SA expired after October 1, 2016, depending on what program you acquired L&SA under, you could retain a perpetual license to use the Long-Term Servicing Branch (LTSB). If you currently use the Current Branch, you must uninstall it and then install the LTSB. There is no support to migrate to, or convert to the LTSB from the Current Branch.

If your SA expired before October 1, 2016, and you retained a perpetual license to System Center Configuration Manager, then your only option for ongoing use is to install and use System Center 2012 R2 Configuration Manager and its available service packs. You were required to uninstall the Current Branch when your SA expired, and reinstall that earlier version of the product. There is no support to migrate to or downgrade from System Center Configuration Manager Current Branch to prior versions of Configuration Manager.   

If you use System Center Endpoint Protection, you must uninstall it if your SA expires. System Center Endpoint Protection offers no *L (License)* rights, and no perpetual rights.<!--506238--> 


### <a name="bkmk_owncb"></a> Do I "own" the Current Branch?   
No. You are licensed to use the Current Branch while you have active SA. For example, via *L&SA*, when *SA* expires, you then have only *L (License)* rights, which do not include rights to use the Current Branch. If your L provides perpetual rights, you can use the Long-Term Servicing Branch of System Center Configuration Manager (or System Center 2012 R2 Configuration Manager if your SA expired prior to October 1, 2016) in place of the Current Branch.


### <a name="bkmk_standalone"></a> Can I purchase System Center Configuration Manager Standalone without SA?      
No. The only way to get rights to use System Center Configuration Manager is to acquire a license with SA or through an equivalent subscription. There are developer programs (like MSDN) where System Center Configuration Manager is offered for development and test purposes, but not production usage.


### <a name="bkmk_update-rights"></a> I see updates for System Center Configuration Manager offered from within my console, like version 1610. Do I have rights to install it?   
If you have active *SA*, you do. If you do not have active SA, you must uninstall the Current Branch and can then install the LTSB of System Center Configuration Manager. The LTSB does not receive updates for incremental versions of System Center Configuration Manager, but does receive security updates based on the Support Lifecycle.


### <a name="bkmk_csp"></a> I have purchased EMS or Microsoft 365 through a Cloud Solution Provider (CSP), do I have rights to use System Center Configuration Manager? 
Yes, you have rights to use System Center Configuration Manager to manage clients covered by the EMS license. First download and install the [evaluation software](https://www.microsoft.com/evalcenter/evaluate-system-center-configuration-manager-and-endpoint-protection). Then contact Microsoft Support to obtain the license key.<!--issue472-->  


### <a name="bkmk_expiration-date"></a> Is my subscription end-date the same as an SA expiration date?    
If *SA* or your subscription is active, you have use rights for System Center Configuration Manager Current Branch. An active subscription is equivalent of having active *SA*, but no perpetual *"L" (license)*. Once your subscription is over, you must uninstall the Current Branch, and you do not have rights to use the LTSB.  

  
### <a name="bkmk_sql"></a> What are the use rights associated with the SQL technology provided with System Center Configuration Manager?    
All of the System Center products include SQL Server technology. Microsoft's licensing terms for these products allow customer use of SQL Server technology only to support System Center components. SQL Server client access licenses are not required for that use. 
 
Approved use rights for the SQL capabilities with System Center Configuration Manager include:
 - Site database role
 - Windows Server Update Services (WSUS) for software update point role
 - SQL Server Reporting Services (SSRS) for reporting point role
 - Data warehouse service point role
 - Database replicas for management point roles
 - SQL Server Always On 

The SQL Server license that is included with System Center Configuration Manager supports each instance of SQL Server that you install to host a database for Configuration Manager. However, only databases for Configuration Manager in the preceding list can run on that SQL Server when you use this license. If a database for any additional Microsoft or third-party product shares the SQL Server, you must have a separate license for that SQL Server instance. 
 <!-- sms500967 -->
