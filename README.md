# Beevelop's base image (`FROM Ubuntu 16.04`)
----
### Pull from Docker Hub
```
docker pull tairoroberto/base:latest
```

### Build from GitHub
```
docker build -t tairoroberto/base github.com/tairoroberto/docker-base
```

### Run image
```
docker run -it tairoroberto/base bash
```

### Use as base image
```Dockerfile
FROM tairoroberto/base:latest
```