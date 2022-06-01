# Azure Setup

## Infrastructure as Code (IaC)

Establish an Infrastructure as Code (`IaC`) pipeline for Azure
1. Identify the necessary Azure Infrastructure/Platform items.
    1. Azure `administrator` account (with email address) for portal access
    2. Azure Subscription for Azure hosting needs
    3. Azure Resource Group
    4. Azure DNS Zone \
       Used to host DNS records, naked/www/sub domains
    5. Azure Storage Account \
       Basic storage account for blobs, files, queues, tables, etc.
    6. Azure Content Delivery Network
2. Group/order them by prerequisites, dependencies.
3. Additional items to be added as necessary...

## Application Repository and CICD pipeline(s)

2. Establish a Development CICD pipeline for simple Web page
    1. Prepare a simple Web page using HTML, CSS and JavaScript.
    2. Setup development repos/branches in `github` ~~Azure DevOps~~, using VSCode as the editor.
    3. Setup CICD triggers in  `github` ~~Azure DevOps~~ for a CI pipeline and a CD pipeline