# EventGridDemo

* **(A)** Initally starting out a very basic sample of using Event Grids - An image is uploaded in a blob storage and a log is displayed in Azure Fucntions.

1. Create a resource group
2. Create a storage account
3. Create a Event Grid Topic for the Storage Account 
4. Create a Event subscription connectiong to the Azure Fucntion. Here we also try to filter out the imange been uploaded to a spefic container.

    Event Subscription >> Filters >> SUBJECT FILTERS >> /blobServices/default/containers/<i>container name to be used</i>


* **(B)** An image is uploaded in a blob storage - Azure Fucntions the image is compressed and storage in another container and deleted from the intial container
