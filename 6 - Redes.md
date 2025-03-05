# Trabajando con redes

La red de contenedores se refiere a la capacidad de los contenedores de conectarse y comunicarse entre sí o con cargas de trabajo que no sean de Docker.

## Principales comandos

Para poder trabajar con las rededs utilizaremos el comando docker de la siguiente forma "docker network [comando]"

#### docker network ls

El siguiente comando mostrará todas las redes

```sh
$ docker network ls
```

#### docker network create

Para crear una red usamos el siguiente comando

```sh
docker network create -d [DRIVER] [NAME]
```

Ejemplo:

```sh
docker network create -d bridge my-network
```

#### docker network rm

Para eliminar una red usamos el siguiente comando

```sh
docker network rm [NAME]
```

Ejemplo: 

```sh
docker network rm my-network
```

#### docker network inspect

Para inspeccionar una red usamos el comando

```sh
docker network inspect [NAME]
```


