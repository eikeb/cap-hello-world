# Hello World using SAP CAP
This is a Hello World application using the SAP Cloud Application Programming model.

## Prerequisites
- Install the latest LTS version of [NodeJS](https://nodejs.org/)
- Install [SQLite](https://sqlite.org/download.html) (only required on Windows)
- Install ``@sap/cds-dk`` globally with:
  ```bash
  npm i -g @sap/cds-dk
  cds # test it
  ``` 

## Installation

Run the following command to install all dependencies and start the application locally.
```bash
yarn install
yarn start
```

After that, open http://localhost:4004/say/hello(to='World') to test the service.