# azure-blob-storage-project

A project demonstrating the use and functionality of azure blob storage service

**Project Overview**

This project has been formulaited to demonstrate the use of azure blob storage and potentially other azure storage services in a real world business context. I have chosen to carry on a previous conecpt idea of a Computer marketplace. 

This project includes demonstrations of:

Production of a storage account

Creation of blob storage containers

The enabling of static website intergation into azure blob service(static website paired with storage)


This could be useful within this sort of business because it means that the company can keep a log of the devices sold within a given period.

**Architecture/Design decisions**

Due to the nature of the concept either azure tables services or azure blob storage would be the correct services to use. In some cases it could be ideal to use both blob(for web images and text defintions) and azure table(as an archive) services but, in this case I will only be demonstrating blob to avoid confusion and complexity.
Local Redundant Storage was chosen to minimise the cost of the project as a whole. 

**What I learnt**

I learnt how to create a storage account and provide storage solutions for clients.

The ideal scenarios in which Azure blob should be used(when nonstructured images and text are involved) and azure tables(for unstructure non sql data essentially allowing you to filter to bigger groups of data together ideal for big archives)

how to manage cloud costs effectively

I also learnt how to include lifecycle managment rules which allow me to auotmate the movement of data to cool or achrive storage(essentially telling azure that this data will not be needed for a prelonged period of time)

**Cleanup and Cost Managment**

After the project was completed I deleted the resources used in this demonstration, this was to avoid any unecessary costs within my subscription and to remain organised.
