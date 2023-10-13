# Hosting a Full Stack Application

## Dependencies

```
- Node v14.15.5 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Environment 
set .env variable

```
- PORT                = 8080
- POSTGRES_HOST       = <DB_IP_Address>
- POSTGRES_PORT       = <DB_Port>
- POSTGRES_DB         = <DB_Name>
- POSTGRES_USERNAME   = <DB_Username>
- POSTGRES_PASSWORD   = <DB_Password>
- URL                 = <Url>
- JWT_SECRET          = <Any_PassPhrase>
- AWS_REGION          = <us-east-1>
- AWS_PROFILE         = <Profile>
- AWS_BUCKET          = <Bucket_Name>

```

## Local Installation
  #### udagram-api
  - install dependencies
    ```
    npm install
    ```
  - run application
    ```
    npm run dev
    ```
#### udagram-frontend
  - install dependencies
    ```
    npm install
    ```
  - run application
    ```
    ng serve
    ```
  - run test
    ```
    ng test
    ```
  - run e2e
    ```
    ng e2e
    ```
        
