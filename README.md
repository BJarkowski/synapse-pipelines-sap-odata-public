# SAP OData Services with Synapse Pipelines

This repository supplements blog series available on SAP Community about data extraction from SAP systems using OData services. Each directory contains target solution described in a blog.
You can find all posts here:
https://blogs.sap.com/tag/summer-with-odata-extraction-using-synapse-pipelines/

Every week, as I publish another episode of the blog series, I will add a directory with the source code of the pipeline and all resources.

# How to use it
I strongly suggest to create your own pipelines by following my blog posts. Use this repository if anything is unclear and when you'd like to compare your solution with the reference.
1) Create a copy of this repository
2) Open Synapse Studio. Go to Manage and choose Git Configuration. Click Configure.
3) Set Repository type to GitHub and provide your account name
4) Choose Repository
5) Change the Root Folder to selected episode, for example /e1 for Episode 1
6) Leave Import existing resources to repository checked
7) Synapse will be now linked with your repository. 
8) All resources should be available in Synapse, however they are not configured. You still need to install and define a Self-Hosted Integration Runtime and edit Linked Services.

I hope above (short) instructions allow you to fast start with Synapse Pipelines and the blog series. I will enhance them in near future.
