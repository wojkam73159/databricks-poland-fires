# databricks-poland-fires
# Fire Data Ingestion and Processing
## Overview

This project automates the process of downloading, storing, and analyzing satellite fire detection data from the NASA FIRMS API for Poland. Using Databricks and PySpark, it fetches daily data, loads it into a DataFrame, and merges it with an existing Delta table. The processed data is then saved to Azure Data Lake (ADLS) for storage and further analysis. The project is designed to be scalable and easy to maintain, enabling efficient fire data processing and storage.
## Tech Stack

    Databricks: Platform for running scalable data pipelines.
    PySpark: Framework for processing large datasets in a distributed manner.
    NASA FIRMS API: Provides real-time satellite fire detection data.
    Azure Data Lake (ADLS): Stores the processed fire data.
    Delta Lake: Data storage layer enabling ACID transactions and scalable processing.
    JDBC: Used for exporting processed data to a database.
