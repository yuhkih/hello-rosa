# hello-kubernetes
Nginx test container based on UBI8

## How to build
```
docker build . -t hello-rosa:latest 
```

## How to use
```
$ docker run --rm --name hello-test -p 80:8080 -d hello-rosa:latest
$ curl http://localhost 
Hello ROSA! 
ROSA is an  abbreviation for Red Hat OpenShift on AWS. It's a managed OpenShift service on AWS.
$ docker stop hello-test
```

