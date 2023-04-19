# sample-docker-flask
This is a sample flask app deployed using docker

## 1. Build -> 
```
docker -t <docker-image-name> . 
docker -t welcome-app .
```

## 2. check dokcer images -> 
```
docker images
```

## 3. Run docker image -> 
```
docker run -p <host-port>:<container-port> <docker-image>
docker run -p 5000:5000 welcome-app
```

## 4. Check running docker containers ->
```
docker ps
```

## 5. Stop container ->
```
docker stop <container-id>
```