# Instruções

#### Build das imagens docker
(Entre na pasta oracle e execute o seguinte comando)
```
docker build -t santanarscs/oracle-express .
```

(ENtre na pasta postgresql e execute o seguinte comando)
```
docker build -t santanarscs/postgresql .
```

(ENtre na pasta wildfly e execute o seguinte comando)
```
docker build -t santanarscs/wildfly .
```

(ENtre na pasta tomcat e execute o seguinte comando)
```
docker build -t santanarscs/tomcat .
```

(ENtre na pasta nuxeo e execute o seguinte comando)
```
docker build -t santanarscs/nuxeo .
```

(ENtre na pasta swagger e execute o seguinte comando)
```
docker build -t santanarscs/swagger .
```
#### Verificando se as imagens estao disponíveis no docker

```
docker images
```
#### Iniciando os containers

```
docker-compose up
```
