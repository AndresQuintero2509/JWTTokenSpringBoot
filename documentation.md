# JWT Authentication on Spring Boot

This example shows how to use Spring Security for using JWT as the default security for REST.

## MongoDB

We use a Docker container for the MongoDB here's the command from [Code4IT](https://www.code4it.dev/blog/run-mongodb-on-docker) you can run:

` docker run -d --name mongo-on-docker -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongoadmin -e MONGO_INITDB_ROOT_PASSWORD=secret mongo `

