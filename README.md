## Full stack MERN project - Easy Link App, url shortener
## HERE I ADDING VIDEO OF URL SHORTNER WHICH I CREATED

[![Made with Clipchamp](https://clipchamp.com/e.svg)](https://clipchamp.com/watch/Do9UOciGzYv?utm_source=embed&utm_medium=embed&utm_campaign=watch)

https://clipchamp.com/watch/Do9UOciGzYv?utm_source=share&utm_medium=social&utm_campaign=watch

# URL Shortener

## Introduction

This project is a URL shortener application that allows users to create shortened versions of long URLs. It provides a user-friendly interface with features such as user authentication, profile management, and short URL management.
## Folder Structure

-**Easy-link-app-master/**
- **client/**
  - **public/**
     - -**assets/**
     - -**images/**
  - **src/**
    - **components/**
    - **pages/**
    - **services/**   
    - **stores/** 
    - **types/**   
    - **util/**
- **server/**
  - **src/**    
    - **config/**
     - - **db.ts**
    - **middlewares/**
        - **authToken.ts**
    - **models/**
      - - **userModel.ts**
      - - **urlModel.ts**
     - **routes/**
     - -  **authRouter.ts**
     - -  **index.ts**
     - -  **urlRoute.ts**
     - -  **userRouter.ts**
     - **services/**
      - - **urlServices.ts**
      - - **userServices.ts**
     - **types/**
      - **express/**
        - - **index.ts**
        - - **urlTypes.ts**
        - - **userTypes.ts.ts**   
     - **util/**
       - - **app.ts**






## Getting Started

# Easy Link App

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/AmanMalviya22/easy-link-app-master/edit/main/


## set up client
# Change directory to the client folder
cd path_to_client/folder

# Install dependencies
yarn install


## set up server

# Change directory to the server folder
cd path_to_server/folder

# Install dependencies
yarn install

### Create Environment Variables
***Create a .env file in the server directory and add the following variables:***

PORT=''
MONGO_URL=''
JWT_SECRET=''
SESSION_SECRET=''



Run the Application
Start the Client

# Change directory to the client folder
cd path_to_client/folder

# Run the client
yarn start

### start the server
# Change directory to the server folder
cd path_to_server/folder

# Run the server
yarn start


Access the Application
Open your browser and make a request to the following URL:


http://localhost:3000






