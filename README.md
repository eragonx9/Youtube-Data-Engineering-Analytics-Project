# Youtube-Data-Engineering-Analytics-Project
Designed to streamline the processing and analysis of YouTube datasets, this project handles diverse data formats to uncover insights into video categories and trending behavior.


Project Objectives:

Automated Data Ingestion: Establish a robust pipeline to aggregate data from disparate external sources.

Scalable ETL Pipeline: Develop a system to transform raw, unstructured data into a cleaned, schema-optimized format for analysis.

Centralized Data Lake: Implement a unified repository to store and manage high-volume datasets originating from multiple streams.

System Scalability: Ensure the architecture remains performant and responsive as data throughput and storage requirements grow.

Cloud-Native Processing: Leverage AWS infrastructure to handle large-scale data processing that exceeds local hardware capabilities.

Interactive Reporting: Deploy a centralized dashboard to visualize key metrics and derive data-driven insights.


Tech Stack & AWS Services:

Amazon S3: Serves as the primary object storage layer, providing high durability, security, and the foundation for our Data Lake.

AWS IAM: Manages fine-grained permissions and secure access control across all AWS resources.

AWS Glue: A serverless integration service used to crawl, discover, and prepare data for analysis via automated ETL jobs.

AWS Lambda: Provides event-driven, serverless computing to execute code in response to data triggers without infrastructure management.

AWS Athena: Enables high-speed, interactive SQL querying directly against data stored in Amazon S3.

Apache Superset: An enterprise-grade, open-source data exploration and visualization platform used to build the project's analytical dashboards.


Utilized Dataset:

Statistics (CSV files) on daily popular YouTube videos over several months are included in this Kaggle dataset. Every day, up to 200 popular videos are released for various areas. Each region's data is contained in a separate file. The data includes, among other things, the video title, channel title, publishing time, tags, views, likes and dislikes, description, and number of comments. The JSON file associated with the region also contains a category_id field that varies each area.

https://www.kaggle.com/datasets/datasnaek/youtube-new

Data Architecture:

<img width="1344" height="768" alt="data architecture" src="https://github.com/user-attachments/assets/0c17851e-69bd-4a28-9f50-07333185cddd" />


Dashboard pdf and link:
<img width="3200" height="2560" alt="youtube-data-analytics" src="https://github.com/user-attachments/assets/07815615-c0da-4225-a9ec-0c54db44acf0" />

https://59ff25e3.us2a.app.preset.io/superset/dashboard/9/?native_filters_key=QC5ajFFincREcVdcvla-FGS9Sf5XJPmG2lKUie7dT9m5Rd4jv5Nbhm3EN6jTInag
