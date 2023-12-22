# Azure administration and Azure Data Engineering course

## Course Outline

<details>
 <summary> <b> Module-01: Microsoft Azure Administration :computer: </b>  </summary>
  
-  Deploy & Manage Azure Compute Service: Azure Virtual Machines (VM)
    - Overview of Azure Virtual Machines
    - Azure VM: Images | Instances (Linux & Windows) | VM Sizes
    - Azure VM Storage: Disks (for persistent storage)
    - Azure VM Management and Automation using Azure VM Extensions
    - Azure VM: HA and Autoscaling services – Scale-sets, Zone, AS
    - Azure Load Balancing services – Load Balancer, AG, Traffic Manager

- Configure and Manage Virtual Networking in Azure

  - Introduction to Azure Virtual Network – Subnets
  - Azure Network Security services - Network Security Group, Firewall
  - IP Address - Public IP, Private IP
  - Azure Virtual Network connectivity use-cases and mechanisms

- Implement and Manage Storage in Azure
  - Overview of Azure Storage
  - Azure Storage Services: Blob, Files, Table, Queue
  - Azure Storage Account: Authorization Techniques
  - Azure Storage Account: Data Redundancy (HA) - LRS, ZRS, GRS, RGRS, GZRS
  - Azure Storage Account: Lifecycle Policies
  - Azure Storage Account: Firewall & Network settings

</details>
<details>
 <summary> <b> Module-02: Microsoft Azure DevOps Services and Jenkins :gear: </b>  </summary>
  
- Introduction to DevOps 
  - Configure processes and communications
    - Agile Development
    - Azure Boards
- Design and implement source control
  - Git Primer
  - Github
  - Azure Repos/AWS CodeCommit
  - Git Branch & Actions

- Plan and Configure CICD Pipeline with Azure Pipelines

  - Continuous Integration process (CI) Primer
  - Understanding Build and Release process
  - YAML Primer
  - Understanding Azure Pipeline configuration file (build, tasks, jobs)
  - Triggering Azure Pipeline
  - Create end-to-end Production grade CICD Azure Pipeline
  - Integrating Azure Pipeline with Azure Repos and Github

- Plan and Configure CICD Pipeline with **Jenkins**

</details>
<details>
 <summary> <b> Module-03: Docker and Kubernetes </b>  </summary>
  
- **Docker**: Package, Ship and Deploy Container Applications
  - Introduction to Containerization | Docker Primer
  - Docker Architecture | Installation | Container Lifecycle | Registry
  - Working with Docker Images – Dockerfile | Custom Images | Container Registries
  - Explore Azure Container Instance and Azure Container App services
  - Lab – Create custom Docker Image and push it to Docker Hub/ACR/ECR

- **Kubernetes**: Orchestrating containerized applications
  - Kubernetes Overview - Architecture | Control Plane components
  - K8s Installation and Configure (One node cluster with minikube)
  - Explore various K8s objects
    - Pod
    - ReplicaSet
    - ReplicationController
    - Deployments
    - Secrets
    - PVC, PV
  - Automating custom application packaging, shipping and deployment to K8s cluster using CI CD Pipeline
  </details>

<details>
  <summary> <b> Module-04: Data Engineering with Azure Services </b>  </summary>

- Plan and Implement Storage in Azure - Azure Storage, Azure SQL DB, Cosmos DB
- **T-SQL** Primer
  - Installation | Configure
  - DDL Queries - Create, Alter and Drop Tables
  - DML Queries - Insret, Update and Delete Records
  - SQL Constraints
  - Normalization of Relational data
- Azure SQL Database
- Azure NoSQL Database - **Cosmos DB**
- Data Processing with **Azure Data Factory** (ADF)

  - ETL Primer
  - Azure Data Factory (ADF) Overview
  - Pipelines and Activities
  - Working with Linked services and Datasets
  - Lab: Create Data Pipeline using ADF
  - Understand how to Trigger and Debug a Pipeline
  - ADF Triggers - Schedule | Storage
  - ADF Connectors
  - ADF Control Flow Activities
  - ADF Data Transformations
  - Lab: Creating Transformation Notebooks

- Develop and Process Data with **Azure Databricks**

  - Azure Databricks Overview - Architecture | Workspace
  - Plan and Create Azure Databricks Workspace
  - Azure Databricks Clusters - Setup | Types | Pricing
  - _Apache Spark Primer_ - Cluster Architecture | Dataframe and Data source APIs
  - Data Ingestion - CSV | JSON | Bulk files
  - Working with _PySpark_ - Python API for Apache Spark
  - Lab: Performing various operations on Data - Load, Groupby, Filtering on NULL
  - Analyzing Data using Spark - Filters | Joins | Aggregations
  - Azure Databricks Notebooks
  - Delta Lake and Data Warehousing in Databricks
    - Create SQL Warehouse in Azure Databricks
    - Run Notebook from Azure Data Factory
  - Azure Databricks Workflows

- Case Studies
  - Data migration from Hadoop to Azure Databricks
  - Setting up Data Pipeline using Azure Synapse Analytics
</details>
