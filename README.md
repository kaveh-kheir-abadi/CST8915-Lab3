# CST8915 Lab 3 - Deploying the Algonquin Pet Store on Azure

**Student Name:** Kaveh Kheir Abadi  
**Student ID:** 041297932  
**Course:** CST8915 Full-stack Cloud-native Development  
**Semester:** Fall 2026

## Demo Video

https://youtu.be/bWy5ROEUbFg

## Service Repositories

- Order Service: https://github.com/kaveh-kheir-abadi/CST8915-Lab2-Order-Service
- Product Service: https://github.com/kaveh-kheir-abadi/CST8915-Lab2-Product-Service
- Store Front: https://github.com/kaveh-kheir-abadi/CST8915-Lab2-Store-Front

## Reflection Questions

### 1. What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?

I tried several times to create a Static Web App in Azure, but unfortunately, I could not create it because of the Azure policy restriction. Because of this, I could not practice configuring the environment variables in the GitHub Actions workflow. I used an Azure VM for the Store Front instead. I will try to learn and practice this more in the next labs.

### 2. How does deploying microservices on Azure Web App Service differ from running them locally?

Yes, there is a little difference, but based on my experience, I think deploying on Azure is easier than running the services locally. We can deploy the code from GitHub easily, and Azure also helps manage the dependencies. Environment variables are also easy to define in Azure. Overall, I found deploying the microservices on Azure easier than running and configuring everything locally.

### 3. Why is it important to use environment variables for configurations in a cloud environment?

Using environment variables allows us to define configuration values in a secure place instead of putting them directly inside the code, so it provides better security. Also, we can deploy the same code several times on different machines or environments without needing to change the code.
