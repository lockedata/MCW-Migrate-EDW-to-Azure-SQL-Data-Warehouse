# Migrate EDW to Azure SQL Data Warehouse

Coho, a retail company focusing on consumer electronics, is modernizing their data architecture. Critical to this effort is migrating their existing enterprise data warehouse to the cloud for better integration with their cloud native customer 360 project and self-service business intelligence for their people in the field.

# Target audience

- Database Administrators
- Database Developers 
- Data Architects

# Abstract

## Workshop

In this workshop, you will look at the process of migrating an on-premises data warehouse to Azure SQL Data Warehouse. Throughout the whiteboard design session and hands-on lab, you will look at the planning process for data warehouse migration, identifying schema and data incompatibilities, efficiently migrating data from on-premises databases to the cloud, data distribution in Azure SQL Data Warehouse, migrating ETL jobs to Azure Data Factory, and supporting ad-hoc workloads in an Azure SQL Data Warehouse through Azure Analysis Services. 

At the end of this workshop, you will be better able to plan and implement a migration of your existing on-premises enterprise data warehouse to Azure SQL Data Warehouse and integrating it with both cloud-based and on-premises services and data sources.

## Whiteboard Design Session

This whiteboard design session will look at the process of migrating an on-premises data warehouse to Azure SQL Data Warehouse. The design session will cover planning for a data warehouse migration, data and schema preparation, data loading, optimizing the data distribution, building a solution to support ad-hoc queries, migrating existing ETL packages and visualizing data with Power BI. 

At the end of this whiteboard design session, you will be better able to plan and implement a migration of your existing on-premises enterprise data warehouse to Azure SQL Data Warehouse and integrating it with both cloud-based and on-premises services and data sources.

- [Student notes](Whiteboard design session/WDS student guide - Migrate EDW to Azure SQL Data Warehouse.md)

## Hands-on Lab

In this hands-on lab you will migrate an existing on-premises enterprise data warehouse to the cloud. You will investigate the current data warehouse to identify any incompatibilities, export the data from the on-premises data warehouse, and transfer it to an Azure Blob Storage. You will then load the data into the warehouse using Polybase. Finally, you will integrate the warehouse by migrating ETL to Azure Data Factory and supporting ad-hoc access by implementing Azure Analysis Services. 

At the end of this hands-on lab, you will be better able to plan and implement a migration of your existing on-premises enterprise data warehouse to Azure SQL Data Warehouse and integrating it with both cloud-based and on-premises services and data sources.

- [Setup](Hands-on lab/Before the HOL - Migrate EDW to Azure SQL Data Warehouse.md)
- [Lab - detailed](Hands-on lab/HOL step-by-step - Migrate EDW to Azure SQL Data Warehouse.md)
- [Lab - freeform](Hands-on lab/HOL unguided - Migrate EDW to Azure SQL Data Warehouse.md)

## Azure services and related products 

- Azure SQL Data Warehouse
- Azure Data Factory v2
- Azure Analysis Services
- Azure Storage
- Power BI


## Azure solutions
Cloud Scale Analytics

## Related references
- [MCW](https://github.com/Microsoft/MCW)
