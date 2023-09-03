# Core categories for Azure documentation

## Storage

**Service:** Archive storage

This feature with various access tiers affords users the ability to efficiently store and organize blob data in a cost effective manner based on how it is being used.

**Python usage:** You can install required libraries by having the Azure SDK for python installed using pip.You can also import necessary libraries in your python script.

**Service:** Azure backup

This service allows for simple, safe, and cost-effective solutions to back up your data and recover it from the Microsoft Azure cloud.

**Python usage:** Azure Backup can be managed with the Azure Command-Line Interface (CLI), which you can use in Python scripts by invoking CLI commands using the “subprocess” module.

## Compute

**Service:** API apps
This enables users to build and host web apps, mobile back ends, and RESTful APIs in the programming language of their choice without managing infrastructure. It offers auto-scaling and high availability, supports both Windows and Linux, and enables automated deployments from GitHub, Azure DevOps, or any Git repo.

**Python usage:** You can use python to make API requests. This can be done by using the requests library or any other HTTP library  to send HTTP requests to the Azure API App's endpoints.

**Service:** Azure CycleCloud

Azure CycleCloud’s automated configuration enables IT to focus on providing service to the business users. It is designed to enable enterprise IT organizations to provide secure and flexible cloud HPC and Big Compute environments to their end users. It has dynamic scaling of clusters which allows businesses to get the resources they needs at the right time and the right price. 

**Python usage:** You can use python to interact with CycleCloud. This can be done by using the the “cyclecloud_client” object to manage your CycleCloud resources. You can create, start, stop, and manage HPC clusters, and also retrieve information about your CycleCloud configuration.

## Database services

**Service:** Azure Database for MariaDB

This service is a relational database service based on the open-source MariaDB Server engine. It is a fully managed database as a service offering that can handle mission-critical workloads with predictable performance and dynamic scalability.

**Python usage:** You can use libraries like “pymysql” or “mysql-connector-python” to connect to and interact with the MariaDB database.

**Service:** Azure database for migration services

This service enables seamless migrations from multiple database sources to Azure Data platforms with minimal downtime. It uses the Data Migration Assistant to generate assessment reports that provide recommendations to guide users through the changes required before performing a migration.

**Python usage:** You can install required libraries for database connectivity. For example, “pymysql” or “mysql-connector-python” and potentially the Azure SDK for Python “azure-mgmt-database- migration”.
