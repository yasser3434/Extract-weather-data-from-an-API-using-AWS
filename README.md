## Overview
## The pipeline:

Extracts real-time weather data from OpenWeatherMap API.
Transforms and processes raw weather data using Spark in AWS Glue.
Loads the transformed data into Amazon Redshift for analytics and reporting.
Uses Apache Airflow to orchestrate the entire pipeline.

## Technologies Used
AWS CloudFormation: Automates resource provisioning.
AWS Glue: Data cataloging and transformation.
Amazon Redshift: Data warehouse for analytics.
Apache Airflow: Workflow orchestration.
OpenWeatherMap API: Source of real-time weather data.
Python: ETL scripting and orchestration logic.
