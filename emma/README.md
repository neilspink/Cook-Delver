# Build and run

```
docker build --no-cache -t emma -f Dockerfile .
docker run -p 80:80 -d --name="emma_server" emma
docker ps
```

Go to command line of running container
```
docker exec -it emma_server bash
```

Delete container using name
```
docker rm -f emma_server
```