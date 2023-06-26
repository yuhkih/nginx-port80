# Nginx container that listens to TCP80
Nginx test container based on UBI8

## How to build
```
docker build . -t nginx-port80:latest 
```

## How to use
```
$ docker run --rm --name test -p 80:80 nginx-port80:latest 
$ curl http://localhost 

$ docker stop test
```

