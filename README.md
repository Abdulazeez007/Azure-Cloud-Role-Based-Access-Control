# Implementing Role Based Access Control (RBAC) Using Azure Portal, Azure Cloud Bash Shell and Azure Cloud Powershell

In this article, we’ll explore the implementation of Role-Based Access Control (RBAC) using Azure Cloud Shell, a powerful tool for managing Azure resources directly from your browser. Azure RBAC is essential for ensuring that users and applications have the appropriate level of access to resources, promoting security and compliance within your organization. By leveraging Azure Cloud Shell, we can streamline the process of configuring RBAC settings, making it easier to assign roles, create custom permissions, and maintain governance across our Azure environment. Join me as we dive into practical steps that will empower you to manage access efficiently and securely using Azure Cloud Shell.

## Role-Based Access Control Architectural Diagram

 ![SOC](https://github.com/Virus192/Azure-Cloud-Role-Based-Access-Control/blob/main/Images/RBAC/photo_5827795537615768718_w.jpg)

## KEY OBJECTIVES
- Create a Senior Admins group with the user account ‘John Capenter’ as its member using (Azure portal).
- Create a Junior Admins group with the user account ‘Abel Hook’ as its member using (Azure Portal).
- Create the Service Desk group with the user ‘Abdriane Joseph’ as its member (Azure CLI).
- Assign the Virtual Machine Contributor role to the Service Desk group.
- Assign the Virtual Machine Administrator Login role to the Senior and Junior Admin groups.

## STEP 1: create and configure the Senior Admin Group with Joseph Price as the member

First, Navigate to Azure portal, Search and select Microsoft Entra ID

 ![SOC](https://github.com/Virus192/Azure-Cloud-Role-Based-Access-Control/blob/main/photo_5825543737802081741_w.jpg)

 **Next,** Create New User (***John Capenter***)and Ensure that the Auto-generate password is selected, select the Show password checkbox to identify the automatically generated password. You would need to provide this password, along with the user name to ***Johnie***.

  ![SOC](https://github.com/Virus192/Azure-Cloud-Role-Based-Access-Control/blob/main/Images/RBAC/photo_5825543737802081746_w.jpg)

  
