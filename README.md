# Exercise: Feature Toggle

## Description

Imagine the following: a large hypothetical system is suffering from a lot of bugs. As such a need as arisen to be able to disable some features on the platform.
Your team has chosen you to create a rapid prototype API for enabling and disabling features at runtime. Below are user stories for the prototype.
Feel free to alter the user stories, as they mainly serve as inspiration - the Deployment step is also evaluated and can be priortized over some of the requirements
if needed.

## User Stories


With the language and tools of your choice; develop a prototype application that partially or fully encapsulates the features below:

**1. Firstly, the team needs a prototype API, that can be used to demonstrate the Feature Toggle functionality**
  - An **Employee** wants to be able to store information about invoices (for the prototype, the following data will suffice; an ID, customer name and $ amount)
  - An **Employee** wants to be able to update the $ amount of an invoice
  - An **Employee** wants to be able to get the total $ amount for a given customer

(Note: If you already have a similar project, feel free to use that as foundation for demonstrating the feature toggle capability - If so, please remember to make it clear which functionality is new, as older projects will not be reviewed)


**2. John is one of the administrators, and he wants an API that can be used to manage Feature Toggles**
  - The **admin** wants to be able to create and remove feature toggles
  - The **admin** wants the toggles to reliably enable/disable any of the features you created earlier
  - The **admin** needs a way to see which Feature Toggles exist and their status

**4. The hypothetical client has several features, that are only being used part of the week/month/year, and would like a way to be able to schedule Feature Toggles.


## Deploying the application
As mentioned the client is running a large monolithic system, and would like to explore cloud and microservices architecture. As such, it would be a huge plus if the prototype could incorporate some of these elements.

## Notes
- The Deployment step is also evaluated and can be priortized over some of the requirements if needed.
- You do not have to priortize implementing any kind of user authorization or login functionality
- You do not need to create any kind of frontend application for this task

## Resource
The concepts of a feature toggle can be viewed here:  
https://martinfowler.com/articles/feature-toggles.html  
https://en.wikipedia.org/wiki/Feature_toggle
