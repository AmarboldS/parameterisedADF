#WELCOME TO parameterisedADF#

Looking for information? here is it "written by Amarbold Sodnomdorj"

Overview

Microsft has announced that we can now create more dynamic data pipelines using Azure Data Facotry (ADF) v2 by passing parameters between:
Pipelines, Activities, Datasets and Linked Services.

I have used key vault to store connection strings for source and destination Azure SQL Databases which makes the data pipeline clean without any secret information. 

This parameterised pipeline extracts all tables in the source Azure SQL Database to Azure Data Lake Store then loads into the destination Azure SQL Database using a generic dataset and a generic linked service

Hope this example helps you a lot.

If you have any questions, shoot me an email @ amarbold.s@gmail.com

Goodluck!
