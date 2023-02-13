# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Grace True
- Caraline Baker

## Lab Question Answers

Question 1: Why are RESTful APIs scalable? 

REST (Representational State Transfer) APIs scale efficently because REST optimizes client-server interactions by taking away the need to get old information preventing communication errors and overload

Sources: https://aws.amazon.com/what-is/restful-api/

Question 2: According to the definition of “resources” provided in the AWS article above,
What are the resources the mail server is providing to clients?

Resources: information that different applications provide to their clients

Images, videos, text, numbers, etc. are all information that can be provided to the client as resources. 

Sources: https://aws.amazon.com/what-is/restful-api/

Question 3: What is one common REST Method not used in our mail server? How could
we extend our mail server to use this method?

The common REST methods are: Get, Post, Put and Delete. 

In our mail server we implement an add, delete, get mail route, get inbox route, and get sent route. 

We do not implement any Post methods which could be used to update existing emails. We could add this to our mail server by implementing a way to change the route of an email. Or, if we add functionality to the code to have different folders for mail (ie. read, unread etc. 

Question 4:Why are API keys used for many RESTful APIs? What purpose do they
serve? Make sure to cite any online resources you use to answer this question!

API keys are used to authorize a client to interact with a server. It can be used to verity that you are calling an API and that you have a right to call the API. APIs can be used to track API calls and usage patterns while still allowing for individuals to anonomously call the API. 

Sources: https://cloud.google.com/endpoints/docs/openapi/when-why-api-key#:~:text=API%20keys%20provide%20project%20authorization,-To%20decide%20which&text=By%20identifying%20the%20calling%20project,or%20enabled%20in%20the%20API. 
