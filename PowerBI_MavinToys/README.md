Overview:

This is a BI project based on ELT, developed using dbt (Data Build Tool), from another project I created. The data source was extracted from Mavin Analytics, which provides a specific page for downloading it.
I downloaded the data sources and saved them in a Postgres database schema named STAGING, then connected to my dbt environment to transform the data for consumption.

- 1° DBT (Data Build Tool) enviroment: 

  The first step I took was creating the environment for dbt, adding it to GitHub, and installing the libraries dbt-core, dbt-postgres, and other dependencies required to run it. After that, using the dbt init command, I created the Data Warehouse where all the transformations have been performed. I separated the project into two paths: Staging and Marts. In Staging, you will find the raw data sources, and in Marts, the data has already been transformed.


 ![image](https://github.com/user-attachments/assets/4831f2c9-9fe3-443f-b527-69c324d6e3ea)

- 2° Recommendation analyses :
  The Maven Analytics suggests some question are been solved:
  -- 2.1° Which product categories drive the biggest profits? Is this the same across store locations?
  -- 2.2° Can you find any seasonal trends or patterns in the sales data?
  -- 2.3° Are sales being lost with out-of-stock products at certain locations?
  -- 2.4° How much money is tied up in inventory at the toy stores? How long will it last?

- 3° BI Template:
  The project are divide in four visions:

  - 3.1°  Overview :
        The overview viusal, shown the information about  
          ![image](https://github.com/user-attachments/assets/72336c96-782d-430d-b608-10f77340e06b)
          ![image](https://github.com/user-attachments/assets/45045d65-2b0a-45e8-b9a9-9cda93954cbf)

                
  - 3.2°  Financials :
          ![image](https://github.com/user-attachments/assets/d659682f-78b3-4640-aa75-c60e8c959a6b)

  - 3.3°  Storage :
          ![image](https://github.com/user-attachments/assets/d8836cdd-f965-4d49-89ed-8ed47c4b3509)

  - 3.4°  Data Extraction :
          ![image](https://github.com/user-attachments/assets/ba3b7494-59f8-4fef-b52f-362df54f48ba)


  - Menu :
  

- 4° DAX Formulas:
  Following the dax formulas are used belong the projects
