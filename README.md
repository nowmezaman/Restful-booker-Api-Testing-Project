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
