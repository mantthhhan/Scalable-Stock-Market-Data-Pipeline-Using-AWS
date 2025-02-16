**Scalable Stock Market Data Pipeline Using AWS.**

I designed and implemented a robust and scalable Data Engineering pipeline to ingest, transform, and analyze stock market data from the Yahoo Finance API. My goal was to create a system that gathers real-time stock information for various companies, processes it to generate meaningful insights, and stores it in a data warehouse for further analysis. This pipeline enables businesses and analysts to monitor stock trends, compare company performance, and make data-driven investment decisions. Additionally, I ensured data integrity and reliability while incorporating a failure notification mechanism to monitor the pipeline effectively.

![Architecture](https://github.com/user-attachments/assets/7ac18381-2918-45de-9356-64d3e8776394)

To achieve this, I utilized AWS Batch to orchestrate the ingestion process, running a Python script to fetch stock data from the Yahoo Finance API. I stored the raw data in Amazon S3 in a structured format and implemented a transformation step within the AWS Batch workflow to clean and enrich the data for analytical use. The transformed data was then stored in a designated S3 folder for further processing. To enhance pipeline reliability, I integrated Amazon CloudWatch and SNS for real-time failure notifications, ensuring timely alerts and a resilient data processing system.
