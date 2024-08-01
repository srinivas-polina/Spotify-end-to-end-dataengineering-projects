# Spotify End-to-End Data engineering Project

### Description:
In this project, I created an ETL pipeline that efficiently extracts, transforms, and loads data from the Spotify API.

### Architecture
![Architecture diagram](https://github.com/srinivas-polina/Spotify-end-to-end-dataengineering-projects/blob/main/architecture%20diagram.png)


### API Information:
The Spotify API is a tool that allows developers to access and interact with Spotify's music data. With it, you can retrieve information about songs, albums, artists, playlists, and even control playback on Spotify. It helps integrate Spotify’s features into apps and websites. - [Spotify-Api](https://developer.spotify.com/)



### Services uesd
1. **S3 (Simple Storage Service)** : Amazon S3 is a highly scalable object storage service that can store and retrieve any amount of data from anywhere on the web. It is commonly used to store and distribute large media files , data backups, and static website files.
   
2. **AWS Lambda** : AWS lambda is a serverless computing service that lets us run our code without managing servers. We can use LAmbda to run code in response to events like changes in S3, DynamoDB, or other AWS services.

3. **Cloud Watch** : Aws cloudwatch is a monitoring service for AWS resources and the applications we run on them. We can use cloudwatch to collect and track metrics, collect and monitor log files, and set alarms.

4. **Aws glue crawler** : Aws glue crawler is a fully managed service that automatically crawls our data sources, identifies data formats, and infer schemas to create an AWS glue data catalog.

5. **AWS Glue Data Catalog** : Basically it means we can store information about our data , how many columns we have , what are the different names of other columns, what is the data type, so all of the metadata about the data will be stored inside the aws data catalog.

6. **Amazon Athena** : Amazon athena is an interactive query service that makes it easy to analyze data in amazon S3 using standard SQl. we can use athena to analyze data in our glue catalog or in our S3 buckets.
