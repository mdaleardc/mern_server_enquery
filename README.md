# mern_server_enquery

## Server-Side (Backend) Description

Project Title: User Inquiry Management System (Backend)
Tech Stack: Node.js, Express.js, MongoDB, Mongoose

## Description:
The backend is built with Node.js and Express.js, providing a RESTful API for managing user inquiries. It handles Create, Read, Update, and Delete (CRUD) operations, storing data securely in a MongoDB database.

## Key Features:

RESTful API: Structured routes for managing inquiry data (/insert, /view, /update/:id, /delete/:id).

Data Validation: Validates incoming data before saving to the database.

Error Handling: Provides informative error responses for failed operations.

CORS Configuration: Configured to allow cross-origin requests from the frontend.

Environment-Aware Port: Uses process.env.PORT for deployment compatibility.


## API Endpoints:

POST /api/website/enquery/insert → Create a new inquiry

GET /api/website/enquery/view → Retrieve all inquiries

PATCH /api/website/enquery/update/:id → Update an inquiry

DELETE /api/website/enquery/delete/:id → Delete an inquiry
