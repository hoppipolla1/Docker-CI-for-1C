# Docker-CI-for-1C

Установка производится с помощью docker-compose, выполнять на linux контейнерах

В docker engine установить параметр "experimental": true

В настройках General установить параметр "Use the WSL 2 based engine"

По желанию можно установить Postgre (если планируется БД в контейнере Docker) и Traefik

Если не устанавливается SonarQube, то создать или отредактировать файл .wslconfig в папке своей учетной записи

![image](https://user-images.githubusercontent.com/110767375/224983178-06cf0b61-fb04-4b23-84b1-33fffa6acbd1.png)

