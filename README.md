# cat_flask_docker-
A simple flask application with necessary configuration to run in docker.

Build the docker image :
    docker build -t cat_flask_app .
   
Run the container :
    docker run -p 8888:5000 --name cat_flask_app cat_flask_app
 
By default flask runs on port 5000. Hence 5000 is exposed from the docker. 

The app can be opened in localhost:8888 as port 8888 of local host is mapped to 5000 port where the app is run on container.
