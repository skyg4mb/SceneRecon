# SceneRecon

Application for document incident response collaboratively

La aplicacion consta de tres partes que puedes ser modificadas en el despliegue, sin embargo en pro de facilitar su despliegue utilizaremos un unico docker desde docker hub.

## Deploy

Para realizar un deploy de la aplicacion podemos seguir las siguientes instrucciones: 

1. Instalar docker https://docs.docker.com/get-docker/

...
$ git clone https://github.com/skyg4mb/SceneRecon

$ cd SceneRecon

$ docker compose up -d
...


## Alert

Los certificados y las configuraciones que se encuentran en este repositorio, son publicos por tanto recomiendo generar sus propias keys y certificados para el uso de la aplicacion.


