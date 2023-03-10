

## Table of Contents

- [My Tech Stack](#my-tech-stack-mern)
  - [Front-end](#front-end)
  - [Back-end](#back-end)
  - [Original Tech Stack](#original-tech-stack)
- [Guidelines to setup](#guidelines-to-setup)
- [API Endpoints](#api-endpoints)
  - [Base Url](#base-url---httplocalhost5000api)
  - [Users](#users)
  - [Posts](#posts)
  - [Answers](#answers)
  - [Comments](#comments)
  - [Tags](#tags)
- [Demo](#demo)
  - [Video](#video---watch-the-video)
  - [Images](#images)

## My Tech Stack (MERN)

#### Front-end
* Front-end Framework: `React.js (with Redux)`
* Styling: `SASS` and `BOOTSTRAP`

#### Back-end
* For handling server requests: `Node.js with Express.js Framework`
* As Database: `MySQL`
* API tested using: `POSTMAN`

### Original Tech Stack
* For handling server requests: `C#`
* As Database: `Microsoft SQL Server`
* `.NET` as well

## Guidelines to setup
1. Create a `.env` file and the format should be as given in `.env.example`.
2. Run these commands then - 
    ```
    npm run installDep (To install all the dependencies)
    
    npm run auditDep (Run this to audit fix all the vulnerabilities)
    ```
3. Run `databaseConfig.sql` file in the mysql client
    ```
    source <file path>/databaseConfig.sql
    ```
4. Start the servers
    ```
    Option 1 (for running both the servers simultaneously):
    
    npm run dev
    
    Option 2 (for running both the servers individually):
    
    npm run server (for backend server only)
    
    npm run client (for frontend server only)
    ```
_NOTE: Might take sometime to start as there will be 2 servers running._

## API Endpoints

#### Base Url - `http://localhost:5000/api`

#### Users
* `GET /auth`
* `POST /auth`
* `POST /users/:id`
* `GET /users`
* `GET /users/:id`

#### Posts
* `GET /posts`
* `GET /posts/top`
* `GET /posts/tag/:tagname`
* `GET /posts/:id`
* `POST /posts/`
* `DELETE /posts/:id`

#### Answers
* `GET /posts/answers/:id`
* `POST /posts/answers/:id`
* `DELETE /posts/answers/:id`

#### Comments
* `GET /posts/comments/:id`
* `POST /posts/comments/:id`
* `DELETE /posts/comments/:id`

#### Tags
* `GET /tags`

## DEMO

#### VIDEO - [Watch the video](https://drive.google.com/file/d/1A0B3JPUUY2snG8MLZpyz2LWhvThG2epn/view?usp=sharing)
