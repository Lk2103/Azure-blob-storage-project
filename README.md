# Azure-Blob-Storage-Project

A project demonstrating the use and functionality of azure blob storage service

**Project Overview**

This project demonstrates the use of Azure Blob Storage to host a static website along with storing of unstructured data. This simulates a real world business scenario. The concept of the website(and the project as whole) is a computer marketplace. Azure Blob service is used to provide the static content such as images and text.

This project includes demonstrations of:

Azure Storage Account

Azure Blob Storage

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/711d93e2-5872-469a-914e-81f9733f6ce5" />

*Screenshot of the Uploading of Text and image files to be used on the static website*

Static Website Hosting

<img width="1919" height="995" alt="image" src="https://github.com/user-attachments/assets/c770bb14-5c88-4dd2-bdbe-5e02ffc684da" />

*Screenshot of the Static Website being enabled(Index.html in Azure Blob Storage*


**Architecture/Design decisions**

Due to the nature of the concept either Azure Tables services or Azure BlobSstorage would be the correct services to use. In some cases it could be ideal to use both Azure Blob(for web images and text defintions) and Azure Table(as an archive) services but, in this case I will only be demonstrating only Azure Blob to avoid confusion and complexity.
Local Redundant Storage was chosen to minimise the cost of the project as a whole. 

**What I learnt**

I learnt how to create a storage account and provide storage solutions for clients.

<img width="1913" height="1011" alt="image" src="https://github.com/user-attachments/assets/dd4d8073-04d7-4adf-9e76-2f6a3aa7e174" />

*Screenshot of storage account being created*

The ideal scenarios in which Azure Blob should be used(when nonstructured images and text are involved) and Azure Table Storage(for unstructure non relational data essentially allowing you to filter groups of data together ideal for archives)

<img width="1915" height="963" alt="image" src="https://github.com/user-attachments/assets/2de6cb1c-5088-47d3-8dcc-0e0a18c775ed" />

*Screenshot of Azure Blob Storage container being created*

How to manage cloud costs effectively

Lifecycle Management rule creation(therefore demonstrating understanding of Hot,cool and archive storage)

<img width="1919" height="845" alt="image" src="https://github.com/user-attachments/assets/d2fc4e36-64c9-4561-9f99-83423cf16572" />

*Screenshot of Lifecycle Management rule being created*

**Cleanup and Cost Management**

After the project was completed I deleted the resources used in this demonstration, avoiding unecessary costs within my subscription and providing an organised workspace.
