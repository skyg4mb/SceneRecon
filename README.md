# SceneRecon

Application for document incident response collaboratively

La aplicacion consta de tres partes que puedes ser modificadas en el despliegue, sin embargo en pro de facilitar su despliegue utilizaremos un unico docker desde docker hub.

## Deploy

El deploy de la aplicacion es bastante sencillo: 

1. Instalar docker https://docs.docker.com/get-docker/

...
$ git clone https://github.com/skyg4mb/SceneRecon
...

...
$ cd SceneRecon
...

...
$ docker compose up -d
...
