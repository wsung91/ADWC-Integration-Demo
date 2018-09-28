# ADWC DEMO
Aug 22, 2018

Author: Sravya Ganugapati
## May be not needed -- Index -- Fix at the end
1. [Introduction](#introduction)
1. [Oracle Cloud Services Used](#oracle-cloud-services-used)
2. [Usecases Overview](#usecases-overview)
1. [Oracle Cloud Services Overview](#oracle-cloud-services-overview )
    1. [Oracle Autonomous Data Warehouse Cloud Service](#oracle-autonomous-data-warehouse-cloud-service)
    1. [Oracle Database Cloud Service](#oracle-database-cloud-service)
    1. [Oracle Data Integration Platform Cloud](#oracle-data-integration-platform-cloud)
    1. [Oracle Big Data Cloud](#oracle-big-data-cloud)
    1. [Oracle Cloud Infrastructure Object Storage](#oracle-cloud-infrastructure-object-storage)
    1. [Oracle Data Visualization Desktop](#oracle-data-visualization-desktop)
3. [Usecase 1: Relational data](#usecase-1---relational-data-to-oracle-autonomous-data-warehouse-cloud-using-oracle-data-integration-platform-cloud)
4. [Usecase 2: Big data](#usecase-2---big-data-to-oracle-autonomous-data-warehouse-cloud-using-oracle-data-lake)
5. [Usecase 3: External Table](#usecase-3---external-table)
6. [Usecase 4: Visualization using Oracle Data Visualization Desktop](#usecase-4---visualization-using-oracle-data-visualization-desktop)
7. [Conclusion](#conclusion)

## Introduction
This workshop will walk you through the different modules that achieve a use case of solving data integration and data management challenges of an enterprise called <Alpha Solutions>. <Talk about data mgmt, integration and migration challenges Alpha is facing> data integration of different data sources, especially big data and relational data in one place - Oracle Autonomous Data Warehouse Cloud - using Oracle cloud products and services. To try Oracle Cloud services, please visit [Oracle Cloud](http://cloud.oracle.com) and sign up for a free trial account worth $300. 

Oracle Autonomous Data Warehouse Cloud (ADWC) provides an easy-to-use, fully autonomous database that scales elastically, delivers fast query performance and requires no database administration.
* **Scalable**: so you can scale down the environments when the resources are not needed, significantly reducing costs or even totally disable the CPU when not in use and just keep the storage up and running.
* **Fast**: delivers high performance data warehousing straight out-of-the-box with unparalleled scalability and reliability. Built on key Oracle Database capabilities: parallelism, columnar processing and compression. All aspects of performance tuning are automatically managed so the service requires no database tuning.
* **Self-driving**: virtually eliminates the need for the manual operational tasks such as backup and patching 
which provides consistently better performing and more secure environments.
* **Automation**: opens opportunities for DBAs to elevate their roles from custodians of databases into more valued data professionals who can deliver more  applications, focus more on the needs of application developers, and extract more value from their current data assets.

## Goals
* Get comfortable with Oracle public cloud services
* Provision a new ADWC service
* Provision other Oracle Cloud services as needed
* Integrate relational data into ADWC using Oracle Data Integration Platform Cloud service (DIPC) from an Oracle database
* Integrate big data into ADWC using Oracle Data Lake
* Create an external table from a file in Oracle Cloud Infrastructure (OCI) Object Storage in ADWC
* Use Oracle Analytics Cloud (OAC) to run reports on the consolidated data in ADWC

## To Learn More About ADWC
* [Oracle ADWC website](https://www.oracle.com/database/data-warehouse.html)
* [Oracle ADWC ipaper](http://www.oracle.com/us/products/database/autonomous-dw-cloud-ipaper-3938921.pdf)
* [Oracle ADWC Documentation](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/index.html)
* [Oracle ADWC Workshop](https://oracle.github.io/learning-library/workshops/journey4-adwc/?page=README.md)


## How to View the Lab Guides
*

# Workshop Details
## Oracle Cloud Services Used
* [Oracle Autonomous Data Warehouse Cloud Service (ADWC)](https://cloud.oracle.com/en_US/datawarehouse)
* [Oracle Database Cloud Service (DBCS)](https://cloud.oracle.com/database)
* [Oracle Data Integration Platform Cloud (DIPC)](https://cloud.oracle.com/en_US/data-integration-platform)
* [Oracle Big Data Cloud (BDC)](https://cloud.oracle.com/bigdata)
* [Oracle Cloud Infrastructure Object Storage](https://cloud.oracle.com/storage/object-storage/features)
* [Oracle Analytics Cloud (OAC)](https://cloud.oracle.com/en_US/oac)


## Introduction - Start Here
**Documentation**: TBDone: "link to md lab"

**Objectives**:

* Introduction to the use case of the entire workshop
* Acquire an Oracle Cloud Account
* Learn how to sign-in to the Oracle Public Cloud
* Learn how to provision a new ADWC database
* Learn how to download the client credentials wallet file
* Learn how to connect to ADWC from Oracle SQL Developer


## Lab 100: Module 1 - Integrate relational data into ADWC
**Documentation**: TBDone: "link to md lab"

**Objectives**:

* Provision an Oracle Database Cloud Service (DBCS) instance
* Connect to the DBCS instance using SQL Developer and import relational data as a table
* Create empty table in ADWC with same structure as that in DBCS
* Provision an Oracle Data Integration Platform Cloud (DIPC) instance
* Configure DIPC to support ADWC as the target and the DBCS as the source
* Use Oracle Data Integrator Studio (ODI Studio) which is part of DIPC to load data from DBCS to ADWC
* Verify if the data is loaded in ADWC


## Lab 200: Module 2 - Integrate big data into ADWC
**Documentation**: TBDone: "link to md lab"

**Objectives**:

* Provision an Oracle Big Data Cloud (BDC) instance
* Upload data into HDFS of the BDC cluster node
* Create an Object Storage bucket in Oracle Cloud Infrastructure (OCI)
* Process and store the data from BDC HDFS to OCI Object Storage bucket
* Create an empty table in ADWC
* Load processed big data file from OCI Object Storage to Oracle ADWC
* Verify if the data is loaded in ADWC


## Lab 300: Module 3 - Create External Table in ADWC
**Documentation**: TBDone: "link to md lab"

**Objectives**:

* Upload data file to the OCI Object Storage bucket created in Lab 300
* Run script to create an external table in ADWC
* Run a sample query to verify if the external table is created in ADWC


## Lab 400: Module 4 - Visualization using Oracle Analytics Cloud (OAC)
**Documentation**: TBDone: "link to md lab"

**Objectives**:

* Create a sample consolidated view on all the tables in ADWC
* Use OAC to visualize and analyze the report

