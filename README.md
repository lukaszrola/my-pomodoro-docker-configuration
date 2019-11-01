# my-pomodoro-docker-configuration

Purpose of this project is to integrate my-pomodoro components:

- my-pomodoro-client: https://github.com/lukaszrola/my-pomodoro-client
- my-pomodoro-words: https://github.com/lukaszrola/my-pomodoro-words

Additionaly `my-pomodoro-words` use `PostgeSQL` as a data storage

Docker images of this projects are available on dockerhub:

- my-pomodoro-client: https://hub.docker.com/r/rolalukasz1992/my-pomodoro-client
- my-pomodoro-words: https://hub.docker.com/r/rolalukasz1992/my-pomodoro-words
- postgresql: https://hub.docker.com/r/bitnami/postgresql

## Run application with docker-compose

1. Checkout file `docker-compose.yml`
2. Call `docker-compose up` from directiory where file `docker-compose.yml` is.
3. After start application should be available on `http://localhost:3000`
