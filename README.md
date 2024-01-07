## Full stack MERN project - Easy Link App, url shortener


[![Made with Clipchamp](https://clipchamp.com/e.svg)](https://clipchamp.com/watch/Do9UOciGzYv?utm_source=embed&utm_medium=embed&utm_campaign=watch)

# URL Shortener

## Introduction

This project is a URL shortener application that allows users to create shortened versions of long URLs. It provides a user-friendly interface with features such as user authentication, profile management, and short URL management.
## Folder Structure

-**Easy-link-app-master/**
- **client/**
  - **public/**
     - - **assets/**
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
        - - **authToken.ts**
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
      - -  **userServices.ts**
     - **types/**
      - **express/**
        - - **index.ts**
        - -  **urlTypes.ts**
        - - **userTypes.ts.ts**   
     - **util/**
       - - **app.ts**






## Getting Started

**clone the repo using command**
git clone https://github.com/AmanMalviya22/easy-link-app-master/edit/main/

**open teminal and change directory to client**
 cd path_to_client/folder
 **run below command**
 yarn install

**open teminal and change directory to server**
 cd path_to_server/folder
 **run below command**
 yarn install

 **create a .env file and put the following variable**

PORT=''
MONGO_URL=''
JWT_SECRET=''
SESSION_SECRET=''

**RUN COMMAND**
**open teminal and change directory to client**
 cd path_to_client/folder
 **run below command**
 yarn start

**open teminal and change directory to server**
 cd path_to_server/folder
 **run below command**
 yarn start


 **open browser and make request to the following url**
 ## localhost:3000


