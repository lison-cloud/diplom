# Данный проект является практической частью диплома
## Для его запуска необходимо собрать три Docker image:
### Директория frontend, выполнив следующую команду:
`docker build -t frontend .`
### Директория backend, выполнив следующую команду:
`docker build -t backend .`
### Директория keycloak, выполнив следующую команду:
`docker build -t customkeycloak .`

## Запускается проект путем выполнения комманды
`docker-compose up`