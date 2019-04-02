# React boilerplate for ServiceNow apps
Simple and lightweight boilerplate to build React applications for ServiceNow. 

Based on [Create-React-App](https://github.com/facebook/create-react-app).

## How to set up your development environment
You need to complete 3 steps so you can start bulding a React applicaiton for ServiceNow:
1. Copy this repo to your local machine and run `npm install` to install all dependencies.
2. Update `package.json` (line #5) with a link to your ServiceNow instance
```json
    "proxy":"https://dev38444.service-now.com"
```
3. updated `.env` file with user credentials you want to use for communications with ServiceNow
```bash
    REACT_APP_USER=servicenow.account
    REACT_APP_PASSWORD=12345
```
This completes development environment setup and you can run the application by `npm start`.
> User name and password required for development environment only, while you're building the application locally. You don't need to provide credentials when deploying the app into ServiceNow.
