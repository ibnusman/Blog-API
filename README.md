# Blog-API

A simple blog application that provides a -> RESTful API for managing blog posts and a frontend interface to interact with the data. This project demonstrates the separation of backend and frontend logic for modular and scalable application development.

---

## Features

### Backend API
- **Endpoints**:
  - `GET /posts`: Retrieve all blog posts.
  - `GET /posts/:id`: Retrieve a single post by its ID.
  - `POST /posts`: Create a new post.
  - `PATCH /posts/:id`: Update specific fields of an existing post.
  - `DELETE /posts/:id`: Delete a post by its ID.
- **In-Memory Data Store**: Temporary storage for blog posts during runtime.

### Frontend
- **Dynamic Blog List**: Displays all posts with options to edit or delete.
- **Create and Edit Forms**: Provides forms for creating and updating posts.
- **EJS Templates**: Used for rendering dynamic content on the server-side.
