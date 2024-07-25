<!DOCTYPE html>
<html>
<body>
<h1>About the Project</h1>
<p>This project focuses on building a robust batch ETL pipeline to efficiently extract, transform, and load IPL data for in-depth analysis. By leveraging AWS, PySpark, and Databricks, I have created a scalable and reliable solution to process large volumes of IPL data and generate valuable insights.</p>

<h2>Tech Stack</h2>
<ul>
<li>AWS: Provides cloud infrastructure for data storage (S3).</li>
<li>PySpark: Used for data processing and transformation.</li>
<li>Databricks: Serves as the platform for running PySpark jobs and managing Delta tables.</li>
</ul>

<h2>Architecture</h2>

![IPL_dataAnalysis_Architecture](https://github.com/user-attachments/assets/f0ee8d7d-d11a-4150-8147-ea4f601a780e)
<h2>Working of the Project</h2>
<p>The ETL pipeline operates in the following steps:</p>
<ol>
<li><strong>Extraction:</strong> IPL data is extracted from AWS S3 buckets.</li>
<li><strong>Transformation:</strong> Extracted data undergoes cleaning, normalization, and enrichment using PySpark on Databricks.</li>
<li><strong>Loading:</strong> Transformed data is loaded into a Databricks Delta table for efficient querying and analysis.</li>
</ol>

<h2>Impact of the Project</h2>
<p>This project delivers the following benefits:</p>
<ul>
<li><strong>Improved data accessibility:</strong> Clean and structured IPL data is readily available for analysis.</li>
<li><strong>Enhanced data quality:</strong> Data transformation ensures data consistency and accuracy.</li>
<li><strong>Scalability:</strong> The PySpark and Databricks-based solution can handle large datasets efficiently.</li>
<li><strong>Data-driven insights:</strong> The processed data enables in-depth analysis and data-driven decision-making.</li>
</ul>
</body>
</html>
