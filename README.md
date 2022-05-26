## [Get this title for $10 on Packt's Spring Sale](https://www.packt.com/B06896?utm_source=github&utm_medium=packt-github-repo&utm_campaign=spring_10_dollar_2022)
-----
For a limited period, all eBooks and Videos are only $10. All the practical content you need \- by developers, for developers

# Learning Azure Functions
This is the code repository for [Learning Azure Functions](https://www.packtpub.com/virtualization-and-cloud/learning-azure-functions?utm_source=github&utm_medium=repository&utm_campaign=9781787122932), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Functions help you easily run small pieces of code in cloud with Azure functions without worrying about a whole application or the infrastructure to run it. With Azure functions, you can use triggers to execute your code and bindings to simplify the input and output of your code.

This book will start with the basics of Azure Functions. You will learn the steps to set up the environment and the tools that we will be using in the further chapters. Once you have a better understanding of this, we will be creating our first hello world function app. Later you will be introduced to triggers, how they are used to activate a function, and how binding can be used to output results of a function.You will also explore the steps to create an assembly with complex functionality that can be used by functions. Next, this book will teach you to scale your functions and use them to process data, integrate systems, and build simple APIs and microservices. Finally, this book will cover some diagnostic techniques with Azure App services and best practices of working with Azure Functions.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
{
"bindings": [
{
"name": "myBlob",
"type": "blobTrigger",
"direction": "in",
"path": "photographs/{name}",
"connection": "origphotography2017_STORAGE",
"dataType": "binary"
},
```

This book is for beginners. This book assumes that you are familiar with at least JavaScript,
Python, PHP, and other programming languages. Knowledge of these programming
languages is essential considering this book to gain better insight. Having a strong
understanding of program logic will provide you with the background to be productive
with Azure Functions while creating serverless architecture.
As we are going to use Microsoft Azure Functions, you need to have an Azure subscription
or free trail to utilize Azure Functions. For basic functions, Azure Functions can be used
freely without using a Microsoft Azure Account.
In this book, we cover Continuous Integration and Continuous Delivery for Azure
Functions, so it is essential to have a Visual Team Studio Services (VSTS) account and some
basic knowledge of it. You can utilize the Implementing DevOps with Microsoft Azure book
available at https://www.amazon.com/Implementing-DevOps-Microsoft-Azure-Miteshebook/dp/B01MSQWO4W for DevOps, Microsoft Azure, and VSTS-related basic knowledge. It
is good to have some knowledge of repositories such as svn and Git as in Continuous
Integration and Continuous Delivery. For Azure Functions, we are going to use a VSTS
repository to store the code for the functions.
Additionally, you will need access to the internet to access Azure Portal. Any normal
hardware configuration is good enough, such as 4 GB RAM and 500 GB hard disk, to access
Microsoft Azure Portal and work with different functions.

## Related Products
* [Learning Microsoft Azure Storage](https://www.packtpub.com/big-data-and-business-intelligence/learning-microsoft-azure-storage?utm_source=github&utm_medium=repository&utm_campaign=9781785884917)

* [Learning Functional Programming in Go](https://www.packtpub.com/application-development/learning-functional-programming-go?utm_source=github&utm_medium=repository&utm_campaign=9781787281394)

* [Learning Functional Data Structures and Algorithms](https://www.packtpub.com/application-development/learning-functional-data-structures-and-algorithms?utm_source=github&utm_medium=repository&utm_campaign=9781785888731)

