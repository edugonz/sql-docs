---
title: Updated - SSMS for SQL Server docs | Microsoft Docs
description: Display snippets of updated content for recently changed in documentation, for SQL Server Management Studio (SSMS) for Microsoft SQL Server.

manager: craigg
author: MightyPen
ms.author: genemi
ms.topic: article
ms.custom: UpdArt.exe
ms.suite: sql
ms.prod_service: sql-non-specified

ms.component: ssms
ms.date: 02/03/2018
---
# New and Recently Updated: SQL Server Management Studio (SSMS) for SQL Server



Nearly every day Microsoft updates some of its existing articles on its [Docs.Microsoft.com](http://docs.microsoft.com/) documentation website. This article displays excerpts from recently updated articles. Links to new articles might also be listed.

This article is generated by a program that is rerun periodically. Occasionally an excerpt can appear with imperfect formatting, or as markdown from the source article. Images are never displayed here.

Recent updates are reported for the following date range and subject:



- *Date range of updates:* &nbsp; **2017-12-03** &nbsp; -to- &nbsp; **2018-02-03**
- *Subject area:* &nbsp; **SQL Server Management Studio (SSMS)**.




&nbsp;

## New Articles Created Recently

The following links jump to new articles that have been added recently.


1. [Install non-English language versions of SQL Server Management Studio (SSMS)](install-other-languages.md)



&nbsp;

## Updated Articles with Excerpts

This section displays the excerpts of updates gathered from articles that have recently experienced a large update.

The excerpts displayed here appear separated from their proper semantic context. Also, sometimes an excerpt is separated from important markdown syntax that surrounds it in the actual article. Therefore these excerpts are for general guidance only. The excerpts only enable you to know whether your interests warrant taking the time to click and visit the actual article.

For these and other reasons, do not copy code from these excerpts, and do not take as exact truth any text excerpt. Instead, visit the actual article.





&nbsp;

<a name="compactupdatedlist"/>

### Compact List of Articles Updated Recently

This compact list provides links to all the updated articles that are listed in the Excerpts section.

1. [Download SQL Server Management Studio (SSMS)](#TitleNum_1)
2. [SQL Server Management Studio - Changelog (SSMS)](#TitleNum_2)




&nbsp;

&nbsp;

<a name="TitleNum_1"/>

### 1. &nbsp; [Download SQL Server Management Studio (SSMS)](download-sql-server-management-studio-ssms.md)

*Updated: 2018-01-18* &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  ([Next](#TitleNum_2))

<!-- Source markdown line 83.  ms.author= "sstein".  -->

&nbsp;


<!-- git diff --ignore-all-space --unified=0 0e123e7bdf04f02fcd26ac31fa30ed5f31b19c7d 924246b55d3cad6a5d068da8a41f4be23dcfeb2b  (PR=4652  ,  Filename=download-sql-server-management-studio-ssms.md  ,  Dirpath=docs\ssms\  ,  MergeCommitSha40=6b4aae3706247ce9b311682774b13ac067f60a79) -->



SSMS 17.4 is the latest version of SQL Server Management Studio. The 17.x generation of SSMS provides support for almost all feature areas on SQL Server 2008 through SQL Server 2017. Version 17.x also supports SQL Analysis Service PaaS.

Version 17.4 includes:

Vulnerability Assessment:
- Added a new SQL Vulnerability Assessment service to scan your databases for potential vulnerabilities and deviations from best practices, such as misconfigurations, excessive permissions, and exposed sensitive data.
- Results of the assessment include actionable steps to resolve each issue and customized remediation scripts where applicable. The assessment report can be customized for each environment and tailored to specific requirements. Learn more at [SQL Vulnerability Assessment](https://docs.microsoft.com/sql/relational-databases/security/sql-vulnerability-assessment).

SMO:
- Fixed issue where *HasMemoryOptimizedObjects* was throwing exception on Azure.
- Added support for new CATALOG_COLLATION feature.

Always On Dashboard:
- Improvements for latency analysis in Availability Groups.
- Added two new reports: *AlwaysOn\_Latency\_Primary* and *AlwaysOn\_Latency\_Secondary*.

Showplan:
- Updated links to point to correct documentation.
- Allow single plan analysis directly from actual plan produced.
- New set of icons.
- Added support for recognize "Apply logical operators" like GbApply, InnerApply.

XE Profiler:
- Renamed to XEvent Profiler.
- Stop/Start menu commands now stop/start the session by default.
- Enabled keyboard shortcuts (for example, CTRL-F to search).
- Added database\_name and client\_hostname actions to appropriate events in XEvent Profiler sessions. For the change to take effect, you may need to delete existing QuickSessionStandard or QuickSessionTSQL session instances on the servers - [Connect 3142981](https://connect.microsoft.com/SQLServer/feedback/details/3142981)



&nbsp;

&nbsp;

---

<a name="TitleNum_2"/>

### 2. &nbsp; [SQL Server Management Studio - Changelog (SSMS)](sql-server-management-studio-changelog-ssms.md)

*Updated: 2018-01-29* &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  ([Previous](#TitleNum_1))

<!-- Source markdown line 27.  ms.author= "sstein".  -->

&nbsp;


<!-- git diff --ignore-all-space --unified=0 b5096fa8f1ae3f2e4bc040f43cb8810d96f2c69c eb641ac39386a26a76dc303f5bd55eb3f9f4c78d  (PR=0  ,  Filename=sql-server-management-studio-changelog-ssms.md  ,  Dirpath=docs\ssms\  ,  MergeCommitSha40=ba4b1c2e5200f2f78786b710da18fd38fedde6c9) -->



**[SSMS 17.4](download-sql-server-management-studio-ssms.md)**

Generally available | Build number: 14.0.17213.0

**What's new**


**General SSMS**

Vulnerability Assessment:
- Added a new SQL Vulnerability Assessment service to scan your databases for potential vulnerabilities and deviations from best practices, such as misconfigurations, excessive permissions, and exposed sensitive data.
- Results of the assessment include actionable steps to resolve each issue and customized remediation scripts where applicable. The assessment report can be customized for each environment and tailored to specific requirements. Learn more at [SQL Vulnerability Assessment](https://docs.microsoft.com/sql/relational-databases/security/sql-vulnerability-assessment).

SMO:
- Fixed issue where *HasMemoryOptimizedObjects* was throwing exception on Azure.
- Added support for new CATALOG_COLLATION feature.

Always On Dashboard:
- Improvements for latency analysis in Availability Groups.
- Added two new reports: *AlwaysOn\_Latency\_Primary* and *AlwaysOn\_Latency\_Secondary*.

Showplan:
- Updated links to point to correct documentation.
- Allow single plan analysis directly from actual plan produced.
- New set of icons.
- Added support for recognize "Apply logical operators" like GbApply, InnerApply.

XE Profiler:
- Renamed to XEvent Profiler.
- Stop/Start menu commands now stop/start the session by default.
- Enabled keyboard shortcuts (for example, CTRL-F to search).
- Added database\_name and client\_hostname actions to appropriate events in XEvent Profiler sessions. For the change to take effect, you may need to delete existing QuickSessionStandard or QuickSessionTSQL session instances on the servers - [Connect 3142981](https://connect.microsoft.com/SQLServer/feedback/details/3142981)

Command line:
- Added a new command line option ("-G") that can be used to automatically have SSMS connect to a server/database using Active Directory Authentication (either 'Integrated' or 'Password'). For details, see [Ssms utility](ssms-utility.md).







## Similar articles about new or updated articles

This section lists very similar articles for recently updated articles in other subject areas, within our public GitHub.com repository: [MicrosoftDocs/sql-docs](https://github.com/MicrosoftDocs/sql-docs/).


#### Subject areas that *do* have new or recently updated articles


- [New + Updated (1+3):&nbsp; **Advanced Analytics for SQL** docs](../advanced-analytics/new-updated-advanced-analytics.md)
- [New + Updated (0+1):&nbsp; **Analytics Platform System for SQL** docs](../analytics-platform-system/new-updated-analytics-platform-system.md)
- [New + Updated (0+1):&nbsp; **Connect to SQL** docs](../connect/new-updated-connect.md)
- [New + Updated (0+1):&nbsp; **Database Engine for SQL** docs](../database-engine/new-updated-database-engine.md)
- [New + Updated (12+1): **Integration Services for SQL** docs](../integration-services/new-updated-integration-services.md)
- [New + Updated (6+2):&nbsp; **Linux for SQL** docs](../linux/new-updated-linux.md)
- [New + Updated (15+0): **PowerShell for SQL** docs](../powershell/new-updated-powershell.md)
- [New + Updated (2+9):&nbsp; **Relational Databases for SQL** docs](../relational-databases/new-updated-relational-databases.md)
- [New + Updated (1+0):&nbsp; **Reporting Services for SQL** docs](../reporting-services/new-updated-reporting-services.md)
- [New + Updated (1+1):&nbsp; **SQL Operations Studio** docs](../sql-operations-studio/new-updated-sql-operations-studio.md)
- [New + Updated (1+1):&nbsp; **Microsoft SQL Server** docs](../sql-server/new-updated-sql-server.md)
- [New + Updated (0+1):&nbsp; **SQL Server Data Tools (SSDT)** docs](../ssdt/new-updated-ssdt.md)
- [New + Updated (1+2):&nbsp; **SQL Server Management Studio (SSMS)** docs](../ssms/new-updated-ssms.md)
- [New + Updated (0+2):&nbsp; **Transact-SQL** docs](../t-sql/new-updated-t-sql.md)



#### Subject areas that do *not* have any new or recently updated articles


- [New + Updated (0+0): **Data Migration Assistant (DMA) for SQL** docs](../dma/new-updated-dma.md)
- [New + Updated (0+0): **ActiveX Data Objects (ADO) for SQL** docs](../ado/new-updated-ado.md)
- [New + Updated (0+0): **Analysis Services for SQL** docs](../analysis-services/new-updated-analysis-services.md)
- [New + Updated (0+0): **Data Quality Services for SQL** docs](../data-quality-services/new-updated-data-quality-services.md)
- [New + Updated (0+0): **Data Mining Extensions (DMX) for SQL** docs](../dmx/new-updated-dmx.md)
- [New + Updated (0+0): **Master Data Services (MDS) for SQL** docs](../master-data-services/new-updated-master-data-services.md)
- [New + Updated (0+0): **Multidimensional Expressions (MDX) for SQL** docs](../mdx/new-updated-mdx.md)
- [New + Updated (0+0): **ODBC (Open Database Connectivity) for SQL** docs](../odbc/new-updated-odbc.md)
- [New + Updated (0+0): **Samples for SQL** docs](../samples/new-updated-samples.md)
- [New + Updated (0+0): **SQL Server Migration Assistant (SSMA)** docs](../ssma/new-updated-ssma.md)
- [New + Updated (0+0): **Tools for SQL** docs](../tools/new-updated-tools.md)
- [New + Updated (0+0): **XQuery for SQL** docs](../xquery/new-updated-xquery.md)


