Fandogh Docker Registry
========


This is a simple docker registry stack with basic authentication and dashboard


## How to run project
```bash
docker-compose up
```

registry dashboard is accessible on port 8181 by default.
```bash
open localhost:8181
```

registry address to push docker images is available on port 5000.
```bash
docker tag hello-world localhost:5000/hello-world
docker push localhost:5000/hello-world
```