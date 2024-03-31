# Restful-booker-Api-Testing-Project
API testing project on Restful-booker Api which is a CRUD Web API that comes with authentication features. Utilizing Postman for testing Api and Newman, a Command-line collection runner for Postman, for generating reports.

# Testing Tools used:
Postman
Newman

# Prerequisite:
Node Js
Newman
Html Report Library

# Newman Installation Process:
Install Command:
npm install -g newman

Run Command: 
newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
newman run “Collection Link” -e “Path”/EnvironmentName.json

# Report Configure
Install Command:
npm install -g newman-reporter-html
npm install -g newman-reporter-htmlextra

Run Command: 
newman run CollectionName.json -e EnvironmentName.json -r cli,html
newman run CollectionName.json -e EnvironmentName.json -r cli,htmlextra


# API Documentation:
https://restful-booker.herokuapp.com/apidoc/index.html

# Steps to perform Testing in Postman using Newman CLI
Create a collection and create the API requests inside the collection. Add your tests to the API request.

# Newman CLI
Newman CLI is a powerful tool that can automate API testing and perform data-driven testing. With Newman CLI, you can easily perform testing and catch bugs and issues early in the development cycle

![booking env](https://github.com/nowmezaman/Restful-booker-Api-Testing-Project/assets/17945810/f750c296-7e87-4f64-88d5-c445cffaa545)


# Newman Summary Report

![image](https://github.com/nowmezaman/Restful-booker-Api-Testing-Project/assets/17945810/bd9aba61-3ffc-40b3-bdc9-3cce16e0f492)





