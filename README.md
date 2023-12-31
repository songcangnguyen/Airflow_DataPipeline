# Twitter Data Pipeline using Airflow and AWS
## Architecture 
![Pipeline](https://github.com/songcangnguyen/Airflow_DataPipeline/assets/109171837/a3d4651c-a1b6-45e8-9c8b-fca35e370340)

## Overview 
Build an end-to-end data pipeline using **Airflow** and **Python**. I extract data using Twitter API, and use **Python** to transform data, deploy the code on **Airflow/EC2** and save the final result on **Amazon S3**
## Environment: 
* Python: 3.11.3
* Pipeline: Airflow
* AWS EC2, S3
## Progress:
1. Get access to the Twitter API, create an application to get API Key, API Key Secret, Authentication Tokens, and Authentication Tokens Secret.
2. Access data from Twitter to perform extract, transform, load using **Python** in Visual Studio Code.
3. Install pandas, tweepy, s3fs packages to your computer by using **Command Prompt**
```
pip3 install pandas 
pip3 install tweepy 
pip3 install s3fs #To read and write data from the s3 bucket
```
5. Create Twitter authentication and API object 
6. Create the EC2 instance to connect and deploy Airflow
7. Create Twitter DAG function with **Python** to connect **EC2** and **S3**
8. Create **IAM** role to grant access to the **S3** bucket. 
