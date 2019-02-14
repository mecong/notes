Login to docker container as a root
```
docker exec -u root -it 61632a04e982 bash
```

Find process on port 8082
```
lsof -i :8082
```
