How to Setup
Dependency Installation: Execute npm install to pull all required packages.

Database Provisioning: Open MySQL and create a schema named typescript_crud_api.

Execution: Run npm start to initialize the database models and host the server on http://localhost:4000.

==========================================

API Testing
POST /users : Registers a new user account into the system.

GET /users : Lists all currently registered users in the database.

PUT /users/:id : Modifies existing user information based on their Unique ID.

DELETE /users/:id : Permanently removes a user record from the persistence layer.
