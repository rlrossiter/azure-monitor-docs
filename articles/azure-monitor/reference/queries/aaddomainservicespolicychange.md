---
title: Example log table queries for AADDomainServicesPolicyChange
description:  Example queries for AADDomainServicesPolicyChange log table
ms.topic: reference
ms.service: azure-monitor
ms.author: edbaynash
author: EdB-MSFT
ms.date: 09/16/2024

# NOTE:  This content is automatically generated using API calls to Azure. Any edits made on these files will be overwritten in the next run of the script. 

---

# Queries for the AADDomainServicesPolicyChange table

For information on using these queries in the Azure portal, see [Log Analytics tutorial](/azure/azure-monitor/logs/log-analytics-tutorial). For the REST API, see [Query](/rest/api/loganalytics/query).


### Show logs from AADDomainServicesPolicyChange table  


Lists the latest logs in AADDomainServicesPolicyChange table, sorted by time (latest first).  

```query
AADDomainServicesPolicyChange
| top 10 by TimeGenerated
```
