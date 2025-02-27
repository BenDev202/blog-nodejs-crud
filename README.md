# RESTful API for News Management  

This project is a **RESTful API** built with **Node.js** and **Express.js**, using **MySQL** as the database. The API enables CRUD operations for managing news posts.  

## Features  

- Retrieve all news posts  
- Retrieve a single post by ID  
- Create a new news post  
- Update an existing post  
- Delete a news post  

## Tech Stack  

- **Backend:** Node.js, Express.js  
- **Database:** MySQL  
- **API Testing:** Postman  

## Endpoints  

| Method | Endpoint       | Description                         |
|--------|---------------|-------------------------------------|
| GET    | `/`           | Home page for blog                 |
| GET    | `/posts`      | Get all news posts                 |
| GET    | `/posts/:id`  | Get a single post by ID            |
| POST   | `/posts`      | Create a new post                  |
| PUT    | `/posts/:id`  | Update an existing post by ID      |
| DELETE | `/posts/:id`  | Delete a post by ID                |

## Installation  

1. Clone the repository  
   ```sh  
   git clone https://github.com/BenDev202/blog-nodejs-crud.git 
   cd blog-nodejs-crud ```
