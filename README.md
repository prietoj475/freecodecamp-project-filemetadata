# FCC API Project: File Metadata Microservice

## About
This is my project of the [File Metadata Microservice challenge](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/file-metadata-microservice) for the freeCodeCamp Back End Development and APIs certification. It was built based on the boilerplate available [here](https://github.com/freeCodeCamp/boilerplate-project-filemetadata/).

## Technologies
- **Node.js** and **Express** to create the server and handle routes, requests and responses.

## Endpoints:

Endpoints | Description | Params
----------|-------------|-------------
POST `/api/fileanalyse` | return file name, type, and size | files (via body)

#### Example output:
* `{"name":"test.txt","type":"text/plain","size":0}`

## How to use:
```
npm install
npm start
```
