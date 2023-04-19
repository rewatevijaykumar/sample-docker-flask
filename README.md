# sample-docker-flask
This is a sample flask app deployed using docker

<!-- ![Docker](/assets/Docker.jpg "Docker") -->
<img width="50%" alt="Docker" src="/assets/Docker.jpg">

<!-- ![Flask](/assets/Flask.png "Flask") -->
<img width="50%" alt="Flask" src="/assets/Flask.png">

## 1. Build -> 
```
docker -t <docker-image-name> . 
docker -t welcome-app .
```

## 2. Check docker images -> 
```
docker images
```

## 3. Run docker image -> 
```
docker run -p <host-port>:<container-port> <docker-image>
docker run -p 5000:5000 welcome-app
```

## 4. Run docker image in detached mode - Container will run in background, without being attahced to any input or output stream
```
docker run -d -p 5000:5000 welcome-app
```

## 5. Check running docker containers ->
```
docker ps
```

## 6. Stop container ->
```
docker stop <container-id>
```

## 7. Check running docker containers
```
docker ps
```

## 8. Stop container
```
docker stop <container-id>
```

## 9. Remove docker image
```
docker image rm -f <docker-image-name>
docker image rm -f welcome-app
```

## 10. Rename docker image
```
docker tag <existing-name> <new-name>
```

## 11. Docker Login
```
docker login
-username
-password
```

## 12. docker push image to docker hub
```
docker push <docker-image-name>:<version>
```

## 13. pull image from docker hub
```
docker pull <docker-image-name>:<version>
```