# Web-app-v-3
Docker Hub Deployment
Create a Dockerfile in the "version3" folder with the following contents: Dockerfiles are what tell docker how it should build your image (environments)  
Build the Docker image using the following command:  
docker build -t your-dockerhub-username/docker-web-app:3.0 .  
This will build a Docker image with the name "your-dockerhub-username/docker-web-app" and the tag "3.0".  
Push the Docker image to DockerHub using the following command:  
docker push your-dockerhub-username/docker-web-app:3 
