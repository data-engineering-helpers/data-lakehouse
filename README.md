# Data-lakes, data warehouses and data lake-houses

## Table of Content (ToC)

* [Data\-lakes, data warehouses and data lake\-houses](#data-lakes-data-warehouses-and-data-lake-houses)
  * [Table of Content (ToC)](#table-of-content-toc)
  * [Overview](#overview)
    * [Other repositories of Data Engineering helpers](#other-repositories-of-data-engineering-helpers)
  * [References](#references)
    * [Awesome lakehouse guide](#awesome-lakehouse-guide)
    * [DataBricks blog \- What is a data lakehouse](#databricks-blog---what-is-a-data-lakehouse)
    * [Snowflake guides \- What is a data lakehouse](#snowflake-guides---what-is-a-data-lakehouse)
    * [Google Cloud \- What is a data lakehouse](#google-cloud---what-is-a-data-lakehouse)
    * [What is Apache XTable](#what-is-apache-xtable)
  * [Articles](#articles)
    * [Apache Arraw ecosystem](#apache-arraw-ecosystem)
    * [ACID Transactions in an Open Data Lakehouse](#acid-transactions-in-an-open-data-lakehouse)
    * [Why are companies building a lakehouse](#why-are-companies-building-a-lakehouse)
    * [From Lakehouse architecture to data mesh](#from-lakehouse-architecture-to-data-mesh)
    * [Open Table Formats and the Open Data Lakehouse](#open-table-formats-and-the-open-data-lakehouse)
    * [Understanding Parquet, Iceberg and data lake\-houses at broad](#understanding-parquet-iceberg-and-data-lake-houses-at-broad)
    * [The Data Lakehouse: Data Warehousing and More](#the-data-lakehouse-data-warehousing-and-more)
    * [Understanding Big Data File Formats](#understanding-big-data-file-formats)
  * [Frameworks](#frameworks)
    * [Unity Catalog playground](#unity-catalog-playground)
    * [Lakehouse at home](#lakehouse-at-home)
    * [OpenLakeForge](#openlakeforge)
    * [SoloLakehouse](#sololakehouse)
    * [Local dbt development](#local-dbt-development)
    * [PostgreSQL extensions](#postgresql-extensions)
      * [pg\_lake](#pg_lake)
      * [pg\_incremental](#pg_incremental)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## Overview

[This project](https://github.com/data-engineering-helpers/data-lakehouse)
intends to collect, analyze and synthetize referential material
about data-lakes, data warehouses and data lakehouses.

Even though the members of the GitHub organization may be employed by
some companies, they speak on their personal behalf and do not represent
these companies.

### Other repositories of Data Engineering helpers

* [Data Engineering Helpers - Knowledge Sharing - Modern Data Stack (MDS) in a box](https://github.com/data-engineering-helpers/mds-in-a-box)
* [Data Engineering Helpers - Knowledge Sharing - Declarative pipelines](https://github.com/data-engineering-helpers/declarative-data-pipelines)
* [Data Engineering Helpers - Knowledge Sharing - Data products](https://github.com/data-engineering-helpers/data-products)
* [Data Engineering Helpers - Knowledge Sharing - Data contracts](https://github.com/data-engineering-helpers/data-contracts)
* [Data Engineering Helpers - Knowledge Sharing - Data quality](https://github.com/data-engineering-helpers/data-quality)
* [Data Engineering Helpers - Knowledge Sharing - Architecture principles](https://github.com/data-engineering-helpers/architecture-principles)
* [Data Engineering Helpers - Knowledge Sharing - Data life cycle](https://github.com/data-engineering-helpers/data-life-cycle)
* [Data Engineering Helpers - Knowledge Sharing - Data management](https://github.com/data-engineering-helpers/data-management)
* [Data Engineering Helpers - Knowledge Sharing - Metadata](https://github.com/data-engineering-helpers/metadata)
* [Data Engineering Helpers - Knowledge Sharing - Data pipeline deployment](https://github.com/data-engineering-helpers/data-pipeline-deployment)
* [Data Engineering Helpers - Knowledge Sharing - Semantic layer](https://github.com/data-engineering-helpers/semantic-layer)
* [Data Engineering Helpers - Knowledge Sharing - Data analytics/analysis](https://github.com/data-engineering-helpers/data-analytics)

## References

### Awesome lakehouse guide

* [GitHub - Awesome lakehouse guide](https://github.com/dipankarmazumdar/awesome-lakehouse-guide)
* Author/maintainer:
  [Dipankar Mazumdar](https://www.linkedin.com/in/dipankar-mazumdar/)
* [LinkedIn post](https://www.linkedin.com/posts/dipankar-mazumdar_dataengineering-softwareengineering-activity-7394177118315671552-KwPH)
* Date: Nov. 2025

### DataBricks blog - What is a data lakehouse

* [DataBricks blog - What is a data lakehouse](https://www.databricks.com/blog/2020/01/30/what-is-a-data-lakehouse.html)
* Authors: Ben Lorica, Michael Armbrust, Reynold Xin, Matei Zaharia
  and Ali Ghodsi
* Date: Jan. 2020

### Snowflake guides - What is a data lakehouse

* [Snowflake guides - What is a data lakehouse](https://www.snowflake.com/guides/what-data-lakehouse/)

### Google Cloud - What is a data lakehouse

* [Google Cloud - What is a data lakehouse](https://cloud.google.com/discover/what-is-a-data-lakehouse)

### What is Apache XTable

* Title: What is Apache XTable (formerly OneTable) — Interoperability
  for Apache Hudi, Iceberg & Delta Lake
* Author: Dipankar Mazumdar
  ([Dipankar Mazumdar on LinkedIn](https://www.linkedin.com/in/dipankar-mazumdar/),
  [Dipankar Mazumdar on Medium](https://dipankar-tnt.medium.com/))
* Date: Dec. 2023
* [Medium - Article](https://dipankar-tnt.medium.com/onetable-interoperability-for-apache-hudi-iceberg-delta-lake-bb8b27dd288d)

## Articles

### Apache Arraw ecosystem

* Title: The Apache Arrow Ecosystem
* Date: Apr. 2026
* Author: Hoyt Emerson
  ([Hoyt Emerson on LinkedIn](https://www.linkedin.com/in/hoytemerson/),
  [Hoyt Emerson on Substack](https://substack.com/@hoytemerson))
* [Substack post](https://thefulldatastack.substack.com/p/the-apache-arrow-ecosystem)
* [LinkedIn post](https://www.linkedin.com/posts/hoytemerson_if-you-work-in-data-then-apache-arrow-is-activity-7452374396775821312-05vN/)

### ACID Transactions in an Open Data Lakehouse

* Title: ACID Transactions in an Open Data Lakehouse
* Date: Feb. 2025
* Author: Dipankar Mazumdar
  ([Dipankar Mazumdar on LinkedIn](https://www.linkedin.com/in/dipankar-mazumdar/))
* [OneHouse - ACID transactions in an open data lakehouse](https://www.onehouse.ai/blog/acid-transactions-in-an-open-data-lakehouse)

### Why are companies building a lakehouse

* Title: Why are companies building a lakehouse
* Date: Feb. 2025
* Author: Roy Hasson
  ([Roy Hasson on LinkedIn](https://www.linkedin.com/in/royhasson/))
* [LinkedIn post](https://www.linkedin.com/posts/royhasson_last-week-i-ran-an-enablement-session-for-activity-7297658658773979136-Cr2M/)

> "Why are companies building a Lakehouse"? This is how I responded...
> The why is simple:
>
> 1. Reduce costs
> 2. Eliminate lock-in
> 3. Be more agile and flexible

### From Lakehouse architecture to data mesh

* Title: From Lakehouse architecture to data mesh
* Date: Dec. 2024
* Author: Adevinta
  ([Adevinta on Medium](https://medium.com/@adevinta))
* [Medium - From lakehouse architecture to data mesh](https://medium.com/adevinta-tech-blog/from-lakehouse-architecture-to-data-mesh-c532c91f7b61)

### Open Table Formats and the Open Data Lakehouse

* Title: Open Table Formats and the Open Data Lakehouse, In Perspective
* Date: Oct. 2024
* Author: Dipankar Mazumdar
  ([Dipankar Mazumdar on LinkedIn](https://www.linkedin.com/in/dipankar-mazumdar/))
* [Onehouse - Open table formats](https://www.onehouse.ai/blog/open-table-formats-and-the-open-data-lakehouse-in-perspective)
* Related open source projects:
  * [Apache XTable](https://github.com/apache/incubator-xtable)
  * [Apache Hudi](https://github.com/apache/hudi)

### Understanding Parquet, Iceberg and data lake-houses at broad

* Understanding Parquet, Iceberg and Data Lakehouses at Broad
* Author: David Gomes
  ([David Gomes on LinkedIn](https://www.linkedin.com/in/davidrfgomes/),
  [David Gomes profile page on his own blog](https://davidgomes.com/about-me/))
* Date: December 2023
* [David Gomes' blog post](https://davidgomes.com/understanding-parquet-iceberg-and-data-lakehouses-at-broad/)

### The Data Lakehouse: Data Warehousing and More

* Title: The Data Lakehouse: Data Warehousing and More
* Authors: Dipankar Mazumdar, Jason Hughes, JB Onofré (all working at Dremio
  at the time)
* Date: October 2023
* [Link to the PDF document on Arxiv](https://arxiv.org/pdf/2310.08697.pdf)
* [LinkedIn post](https://www.linkedin.com/posts/dipankar-mazumdar_dataengineering-softwareengineering-activity-7283666426437980160-A33n)

### Understanding Big Data File Formats

* Title: Understanding Big Data File Formats
* Author: Vladimir Sivcevic
  ([Vladimir Sivcevic on LinkeDIn](https://www.linkedin.com/in/vladimirsiv/),
  [Vladimir Sivcevic profile page on his own blog](https://www.vladsiv.com/about/))
* Date: April 2022
* [Vladimir Sivcevic's blog post - Big data file formats](https://www.vladsiv.com/big-data-file-formats/)

## Frameworks

### Unity Catalog playground

* [GitHub - Unity Catalog playground](https://github.com/newfront/unitycatalog-playground)

### Lakehouse at home

* [GitHub - Lakehouse at home](https://github.com/lisancao/lakehouse-at-home)
* Author: Lisa N. Cao
  ([Lisa N. Cao on LinkedIn](https://www.linkedin.com/in/lisancao/),
  [Lisa N. Cao on GitHub](https://github.com/lisancao))
* [Medium - Declarative Pipelining in Apache Spark Part 1](https://medium.com/apache-spark/declarative-pipelining-in-apache-spark-part-1-focus-on-your-data-not-your-dags-553a1056d178),
  March 2026

### OpenLakeForge

* [GitHub - OpenLakeForge](https://github.com/malon64/openlakeforge)
* Main contributor: Alexis Metwalli
  ([Alexis Metwalli on LinkedIn](https://www.linkedin.com/in/alexis-metwalli/),
  [Alexis Metwalli on GitHub](https://github.com/malon64))
* [LinkedIn post](https://www.linkedin.com/feed/update/urn:li:activity:7463121583881138177/)

### SoloLakehouse

* [GitHub - SoloLakehouse](https://github.com/Jiahong-Que-9527/SoloLakehouse)
* [LinkedIn post](https://www.linkedin.com/posts/jiahong-que-215428258_dataengineering-platformengineering-lakehouse-share-7455232883318853632-G-_f)

### Local dbt development

* [Medium post - Local dbt development](https://medium.com/doubleverify-engineering/unlocking-efficient-local-development-with-dbt-2b11fb9ab40f)

### PostgreSQL extensions

#### `pg_lake`

#### `pg_incremental`

* [LinkedIn post](https://www.linkedin.com/posts/marcoslot_why-we-developed-pgincremental-one-of-activity-7392183986577440770-HCZU/)
* Date: Nov. 2025
* Author: [Marco Slot](https://www.linkedin.com/in/marcoslot/)
