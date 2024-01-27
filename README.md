README.md

Develop and Deploy on Azure a single sign on application that allows users to 
1. Upload Videos to Azure Data Lake Storage 
2. List the videos they have uploaded
3. Delete a Video from the list they have uploaded
4. Users do not need to create folders (a requirement that will be needed later on but think about how you would do this in your design and implementation)

The SSO site should be an Azure Web App and should use the recommended Azure practicies to ensure securtiy regarding the single sign on and Azure lake
You can assume the Azure lake storage and the web app are on the same Tenancy for now (but look into what would be required to change for the app to be on one tenancy and the storage to be on another)

Have a look at the following
https://learn.microsoft.com/en-us/azure/app-service/scripts/terraform-secure-backend-frontend
and use 
Chat GPT for ideas eg  
https://sl.bing.net/kRuk796SNqK

after which ask Bing the following:
"How do I develop the code and write the terraform for a single sign on application that is running as an azure web app that allows users to upload and access video stored in an azure data lake?"
