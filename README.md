# Insurance_Dashboard
Built interactive Power BI dashboards in the vehicle insurance domain, comparing company performance, analyzing vehicle claim trends, and assessing policy risk. Designed to make insurance data easy to explore and highlight insights for smarter decisions.

# Vehicle Insurance Dashboard – Power BI
  # Project Overview
I built this project to make sense of the vehicle insurance domain using Power BI. The dashboards compare different insurance companies and bring clarity to areas like Company Performance, Vehicle Claims, and Policy Risk. The idea was simple: turn complex insurance data into visuals that anyone can explore and use to spot trends or risks quickly.
# How the Data Flows
Behind the dashboards is a data pipeline I designed to keep everything fresh and reliable:
- Data starts in an Amazon S3 bucket, acting as the data lake.
- It’s then loaded into Snowflake for scalable storage and querying.
- dbt models handle the transformations, cleaning, and structuring the data.
- dbt jobs run every hour, so the dashboards always reflect the latest updates.
- The transformed data in Snowflake feeds directly into Power BI, where the dashboards come alive.
  # Why It Matters
Insurance data can be messy and overwhelming. By automating the pipeline and visualizing the results, this project makes it easier to compare companies, understand claim patterns, and assess policy risks—all in one place.

