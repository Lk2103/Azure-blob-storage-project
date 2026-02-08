# Azure-Blob-Storage-Project

A project demonstrating the use and functionality of azure blob storage service

**Project Overview**

This project demonstrates the use of Azure Blob Storage to host a static website along with storing of unstructured data. This simulates a real world business scenario. The concept of the website (and the project as whole) is a computer marketplace. Azure Blob service is used to provide the static content such as images and text.

This project includes demonstrations of:

Azure Storage Account

Azure Blob Storage

<img width="1919" height="905" alt="Uploading text and images" src="https://github.com/user-attachments/assets/98994e18-4099-4a12-8758-cac152e2c199" />

*Screenshot of the Uploading of Text and image files to be used on the static website*

Static Website Hosting

<img width="1919" height="841" alt="Static website enabling" src="https://github.com/user-attachments/assets/2dddaf32-80e7-4cb9-a4f4-0cc3e87e701b" />

*Screenshot of the Static Website being enabled(Index.html in Azure Blob Storage)*


**Architecture/Design decisions**

Due to the nature of the concept either Azure Tables services or Azure Blob Storage would be the correct services to use. In some cases it could be ideal to use both Azure Blob(for web images and text defintions) and Azure Table(as an archive) services but, in this case I will only be demonstrating only Azure Blob to avoid confusion and complexity.
Local Redundant Storage was chosen to minimise the cost of the project as a whole. 

**What I learnt**

I learnt how to create a storage account and provide storage solutions for clients.

<img width="1913" height="833" alt="Storage account" src="https://github.com/user-attachments/assets/2d2c468e-9402-491b-bd5e-a1675a0d6145" />

*Screenshot of storage account being created*

The ideal scenarios in which Azure Blob should be used(when nonstructured images and text are involved) and Azure Table Storage(for unstructure non relational data essentially allowing you to filter groups of data together ideal for archives)

<img width="1915" height="827" alt="Storage blob container" src="https://github.com/user-attachments/assets/d7e156e4-d65b-4232-a92e-93f86e99455a" />

*Screenshot of Azure Blob Storage container being created*

How to manage cloud costs effectively

Lifecycle Management rule creation(therefore demonstrating understanding of Hot,cool and archive storage)

<img width="1919" height="845" alt="image" src="https://github.com/user-attachments/assets/d2fc4e36-64c9-4561-9f99-83423cf16572" />

*Screenshot of Lifecycle Management rule being created*

**Cleanup and Cost Management**

After the project was completed I deleted the resources used in this demonstration, avoiding unecessary costs within my subscription and providing an organised workspace.
