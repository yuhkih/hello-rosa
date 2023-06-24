# hello-kubernetes
Nginx test container based on UBI8

## How to build
```
docker build . -t hello-rosa:latest 
```

## How to use
```
$ docker run --rm  -p 80:8080 -d hello-rosa:latest
$ curl http://localhost 
Hello ROSA! ROSA is an abbribation for Red Hat OpenShift on AWS! 
$
```

