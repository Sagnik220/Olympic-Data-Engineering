# Olympic-Data-Engineering
Introduction

The Olympic Games are one of the world’s most celebrated events, bringing together athletes from diverse backgrounds to compete on a global stage. Inspired by Darshil Parmar’s insightful YouTube video on Olympic Data Engineering, this article explores the fascinating world of data engineering in the context of the Olympics and how it fuels this iconic event with data-driven insights.


Architecture
Data Source:

CSV files stored in a GitHub repository as a data source.


Data Source
Data Integration: Unveiling the Data Pipeline

In the world of data-driven projects, a seamless data integration process is the cornerstone of success. In this blog post, we’ll delve deeper into a specific data integration scenario that encapsulates the essence of efficient data management and processing: ingesting data from a GitHub repository and effortlessly depositing it into Azure Storage.

The Players in Action

GitHub Repository: At the source of this data journey lies a GitHub repository, a familiar hub for open data, code, and collaborative projects. It’s here that our data adventure begins, where CSV files hold the keys to valuable insights.
Azure Data Factory: Stepping onto the stage next is Azure Data Factory, a cloud-based service that seamlessly orchestrates data workflows. Think of it as the conductor of an orchestra, ensuring that every instrument (data) plays its part harmoniously.
Azure Data Lake Gen2 Storage’s “Raw Data” Folder: This is the designated destination for our data. It’s where the untouched, unprocessed data finds its temporary home, awaiting further analysis and utilization.



Raw & Transformed Layer Directory

Raw Data
Data Pipeline:

Creating a data pipeline is the next pivotal step in our data journey. This pipeline will serve as the task of orchestrating the data ingestion and transformation processes seamlessly.

Azure Databricks offers a powerful and collaborative environment for data engineering making it the ideal stage for refining the raw data. In this stage, the data is refined, cleansed, transformed, and prepared for analysis.


Data Pipeline in Azure Databricks

Transformed Data
Creating Interactive Dashboards with Power BI

Power BI serves as an exceptional tool for transforming the final transformed Olympic data into visually engaging and interactive dashboards.

Here we have built a basic Olympic Medal Distribution dashboard

