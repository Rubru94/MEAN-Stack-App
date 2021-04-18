# MEAN-Stack-App
Node.js Restful CRUD API with Node.js, Express, Angular and MongoDB

# Backend
### Path: 
- ./backend
### Run: 
- node server.js

# Frontend
### Path: 
- ./frontend
### Run: 
- ng serve --port `PORT`

***

# Docker reference

## [docker CLI](https://docs.docker.com/engine/reference/commandline/docker/)

- Build an image from a Dockerfile
  - `docker build [OPTIONS] PATH | URL | -`

- Docker runs processes in isolated containers
  - `docker run [OPTIONS] IMAGE[:TAG|@DIGEST] [COMMAND] [ARG...]`

- Stop one or more running containers
  - `docker stop [OPTIONS] CONTAINER [CONTAINER...]`

- Remove one or more containers
  - `docker rm [OPTIONS] CONTAINER [CONTAINER...]`

- Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
  - `docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]`

- Push an image or a repository to a registry
  - `docker push [OPTIONS] NAME[:TAG]`

- Show all images (default hides intermediate images)
  - `docker images -a`

- Remove one or more images
  - `docker rmi [CONTAINER ID / IMAGE ID]`

- Remove all the containers & images
  - `docker system prune -a`

- Fetch the logs of a container
  - `docker logs [CONTAINER ID]`

- Return low-level information on Docker objects
  - `docker inspect [CONTAINER ID]`

## [docker-compose CLI](https://docs.docker.com/compose/reference/)

- Builds, (re)creates, starts, and attaches to containers for a service
  - `docker-compose up --build`

- Stops containers and removes containers, networks, volumes, and images created by up
  - `docker-compose down`

# Bibliography

- [Angular 8 + MongoDB example with Node.js Express: Build CRUD App - BezKoder](https://bezkoder.com/angular-mongodb-node-express/#Implementation)
- [Install MongoDB Community Edition on Ubuntu — MongoDB Manual](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)
- [48 comandos y consultas de MongoDB para conocer como desarrollador y administrador de bases de datos](https://geekflare.com/es/mongodb-queries-examples/)
- [Angular, instala este framework de código abierto en Ubuntu | Ubunlog](https://ubunlog.com/angular-instala-framework-ubuntu/)
- [How to Update Node.js to Latest Version {Linux, Windows, and MacOS}](https://phoenixnap.com/kb/update-node-js-version)
- [How To Dockerize Mean Stack App - DZone DevOps](https://dzone.com/articles/how-to-dockerize-mean-stack-app)
- [Create a MEAN app with Angular and Docker Compose ― Scotch.io](https://scotch.io/tutorials/create-a-mean-app-with-angular-2-and-docker-compose)
- [Git can't commit Angular folder on my project with IntelliJ or SourceTree - Stack Overflow](https://stackoverflow.com/questions/47768267/git-cant-commit-angular-folder-on-my-project-with-intellij-or-sourcetree)
