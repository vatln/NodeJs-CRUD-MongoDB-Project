# CRUD sample Application Mongo DB express

This is a simple Node.js CRUD application using MongoDB.

### How to run

    npm install
    node app.js

### Configuration

MongoDB: `mongodb://mongodb`

Express: `app.listen(process.env.PORT || 3000);`

Wercker environment properties:

- DOCKER_USERNAME = username for Docker account
- DOCKER_PASSWORD = password for Docker account
- DOCKER_TAG = tag of the docker image
- DOCKER_REPOSITORY = name of the new repository (includes image name)

# NodeJs-CRUD-MongoDB-Project
