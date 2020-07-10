"COVID-19 - Analytics in Minutes"
=================================

Workshop 1: COVID-19 Analytics in Minutes (full data refresh)
=============================================================

Workshop Summary
----------------

Extract, via an HTTP request, a publically available COVID-19 dataset utilising Azure Data Factory
(ADF). Land this file to Azure Data Lake - within a date driven hierarchy. Then ingest this file to
Azure Data Explorer (ADX). Once loaded, using KQL, perform "what if" analysis combined with in-situ visualisations.

The final stage is to, using the new [ADX Dashboards](https://docs.microsoft.com/en-us/azure/data-explorer/azure-data-explorer-dashboards)
feature, create an enriched analytical dashboard permitting data wrangling. 

This **README.MD** file explains how the lab is structured, what you
will learn, and the technologies you will use in this solution.


Activities
----------
The workshop is broken down into several logical units, as follows:

-   Activity 1: Azure Data Lake (ADLS)

    -   Create this Azure services

-   Activity 2: Azure Data Explorer (ADX)

    -   Create this Azure services

-   Activity 3: Data Factory (ADF)

    -   Build this Azure services

-   Activity 4: Security & Access

    -   Configure Managed Identities, ADLS, ADX and Dashboard access

-   Activity 5: ADF Pipeline

    -   Build an ADF pipeline

-   Activity 6: Analytics via KQL

    -   Query the resulting ADX database with KQL

-   Activity 7: Analytics via ADX Dashboards

    -   Query the ADX database with new Dashboard feature

-	Activity 8: Wrap-up


Artifacts
---------
This diagram shows the architecture that will be built [Architecture HLD](media/image1.png).

This diagram shows the Azure ADX Dashboard that will be built [ADX Dashboard](media/image2.png).


Method
------
Open the lab document ""COVID-19 - Analytics in Minutes - Workshop 1.pdf" and work through each activity to complete the lab.