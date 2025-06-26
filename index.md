---
title: "Oracle Mbank Lab"
keywords: homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you to understand the problem and how it was solved.
---


## Introduction

This data pipeline project on Oracle Cloud implements a complete architecture for ingesting, processing, storing, and analyzing data from various sources such as MongoDB, MySQL, Oracle databases, APIs, and flat files (CSV, JSON). All ingested data is first landed in the Raw Zone using Oracle Object Storage in Parquet format, which ensures efficient storage and schema flexibility. From there, the data is transformed, cleaned, and enriched in the Silver & Gold layer using Oracle Autonomous Database and Data Flow, following business logic and modeling standards. The processed data is then made available for analytics and reporting in Oracle Analytics Cloud, supporting both business intelligence and data science use cases. This architecture allows for high scalability, performance, and governance, leveraging native Oracle tools in a cloud-native, secure, and cost-effective environment.
