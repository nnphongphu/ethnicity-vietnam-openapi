# Ethnicity Vietnam Openapi 3.0 Specification
This is the Ethnicity Vietnam server based on the OpenAPI 3.0 specification. 
The server is used to serve content for the main website as well as provide a fully operational CRUD API for our content management system. 

_The API implemetation of the server MUST strictly comply to all the specifications in this document._

This repository is automatically deployed using Github Pages, click [here](https://nnphongphu.github.io/ethnicity-vietnam-openapi/) to be redirected to the interactive version of this specification.
    
Useful links:
- [Ethnicity Vietnam's core client](https://github.com/nnphongphu/ethnicity-vietnam-core-client)
- [Ethnicity Vietnam's core server](https://github.com/nnphongphu/ethnicity-vietnam-core-server)
- [OpenAPI specifications for Ethnicity Vietnam Restful API](https://nnphongphu.github.io/ethnicity-vietnam-openapi/)

## Steps to make changes to this repository

1. Install the package `swagger-cli` globally
```
npm install -g swagger-cli
```

2. Mofidy the `.yaml` files inside the source folder
    
3. Compile the source folder into one single openapi file using the command
```
swagger-cli bundle ./source/openapi.yaml --outfile openapi.yaml --type yaml
```

4. Git push to master branch and it will automatically be deployed to Github page