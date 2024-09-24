This is an attempt to create most basic blob trigger serverless (function app in azure)

Overview
This project shows a basic Azure Function App that triggers on the creation of new blobs in Azure Blob Storage. The application is designed to demonstrate the power of serverless computing which enables you to efficiently process data with minimal infrastructure management.


Features:

1.Blob Trigger: Automatically executes a function whenever a new blob is uploaded to the specified container, allowing for real-time data processing.

2.Serverless Architecture: Utilizes Azure Functions, which automatically scales based on demand. 

3.Cost Efficiency: The serverless model, this project minimizes operational costs. You are charged only for the execution time of your functions and the number of executions i:e you'll be charged by azure only for the time when your server query is running the scripts, making it an ideal solution for nonfrequent usage 


Getting Started

Prerequisites
--An active Azure subscription

--Azure Functions Core Tools

--Azure Storage Account (The code already consist of variables which commands the azure to create a storage a/c and resource group)


--Setup Instructions

1.Clone this repository to your local machine.

2.Deploy the function app to your Azure account.

3.Set up your Blob Storage container and configure the function's trigger settings (I've uploaded a png file for trigerring the function app, you can use any file can be yout basic html file also).

Usage:

Upload a blob to the specified container to trigger the function. Monitor the Azure portal for execution logs and outputs (Logs will take upto 3-4mins or more than that to show the invocations)
