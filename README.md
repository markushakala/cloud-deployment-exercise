# Simple button

## How to start

Make sure you have java 8 installed

Build the project with `./mvnw package`

Run with `java -jar ./target/docker-example-1.1.3.jar`

The project should open in `8080` and you get a message by pressing the button.

## Cloud deployment

The Docker image of the application is deployed on render.com. The project has 
a GitHub Actions workflow that builds and pushes an image to Docker Hub and triggers 
a redeployment from Docker Hub to render.com when code is pushed to the repository.

Link to the deployed application: https://spring-example-h17w.onrender.com
