Overview:

This is a BI project based on ELT, developed using dbt (Data Build Tool), from another project I created. The data source was extracted from Mavin Analytics, which provides a specific page for downloading it.
I downloaded the data sources and saved them in a Postgres database schema named STAGING, then connected to my dbt environment to transform the data for consumption.

- 1° DBT (Data Build Tool) enviroment: 
        The first step I took was creating the environment for dbt, adding it to GitHub, and installing the libraries dbt-core, dbt-postgres, and other dependencies required to run it. After that, using the dbt init command, I created the Data Warehouse where all the transformations have been performed. I separated the project into two paths: Staging and Marts. In Staging, you will find the raw data sources, and in Marts, the data has already been transformed.


- ![image](https://github.com/user-attachments/assets/4831f2c9-9fe3-443f-b527-69c324d6e3ea)
