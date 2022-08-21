---
layout: default
title: APIs General
parent: API and Other Connections
nav_order: 5
---

# API Connection Notes

## Azure DevOps

[AzureDevOps_R](https://github.com/AMNakamura/API/blob/main/AzureDevOps_R.md) describes the enablement and use of Azure (
and other APIs) in the RStudio Connect environment while protecting the confidentiality of API tokens needed for authentication. Covers getting  the API "key", using the token locally to query the Azure analytics API (securely) while you perfect your document in RStudio, and using the token in production (e.g., for automation). 

[Azure API - WIQLs](https://github.com/AMNakamura/API/blob/main/Azure_WIQL_Example.md) describes the process and provides examples on how to extract work items in Azure DevOps Services REST API using Work Item Query Language (WIQL). Work item text can be used not only to track work, but to identify unexplored relationships between system functionality (e.g., through topic modeling of user story text).  

## Google Analytics

[Setting Up a Simple Google API Call](https://github.com/AMNakamura/API/blob/main/GoogleAnalyticsBasic0.md) describes the necessary pieces of information (credentials) needed for a GoogleAnalytics query and how to use them, with R, to generate tokens, pass URL requests to get page views and other information, and how to perform some basic visualizations. 