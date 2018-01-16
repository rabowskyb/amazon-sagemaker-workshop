# Amazon SageMaker Workshop

Amazon SageMaker is a fully-managed service that enables developers and data scientists to quickly and easily build, train, and deploy machine learning models at any scale. In this workshop, you'll create a SageMaker notebook instance and work through sample Jupyter notebooks that demonstrate some of the many features of SageMaker.  Along the way you'll see how machine learning can be applied to both structured and unstructured data.  Please complete Module 1, Creating a Notebook Instance, right away when the workshop begins before the introduction presentation, so your notebook instance will be ready when the presentation ends and the hands on portion of the workshop starts.  

## Prerequisites

### AWS Account

In order to complete this workshop you'll need an AWS Account with access to create AWS IAM, S3 and SageMaker resources. The code and instructions in this workshop assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. You can work around these by appending a unique suffix to the resources that fail to create due to conflicts, but the instructions do not provide details on the changes required to make this work.

Some of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the [AWS Free Tier page](https://aws.amazon.com/free/) for more details.  We are also providing a credit for the workshop.

### Browser

We recommend you use the latest version of Chrome to complete this workshop.

## Modules

This workshop is broken up into multiple modules. Module 1 must be completed first.  We recommend you complete the other modules in order, however, you are welcome to skip ahead.  

1. Creating a Notebook Instance
2. Notebook 1:  Video Game Sales
2. NOTEBOOK 2
3. NOTEBOOK 3

After you have completed the workshop you can delete all of the resources that were created by following the instructions at the end of each notebook ( NOTE:  SHOULD WE PROVIDE A CLEANUP GUIDE INSTEAD? ). 

### Module 1:  Creating a Notebook Instance

### Module 2:  Video Game Sales Notebook

In this module, we'll work our way through an example Jupyter notebook that demonstrates how to use an Amazon-provided algorithm in SageMaker. More specifically, we'll use SageMaker's version of XGBoost, a popular algorithm that often is useful in working with structured data that might be found in relational databases and flat files. To begin, follow these steps:
- Download this repository to your computer by clicking 'Clone or download' then 'Download ZIP'.
- In your notebook instance, click the 'New' button on the right and select 'Folder'.  
- Click the checkbox next to your new folder, click the 'Rename' button above in the menu bar, and give the folder a name.
- Click the folder to enter it.
- To upload the notebook, click the 'Upload' button on the right, then in the file selection popup, select the file 'video-game-sales.ipynb' from the folder on your computer where you downloaded this GitHub repository. Then click the blue 'Upload' button that appears in the notebook next to the file name.
- You are now ready to begin the notebook:  click the notebook's file name to open it, then follow the directions in the notebook.







