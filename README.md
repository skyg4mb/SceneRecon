# SceneRecon

Application for document incident response collaboratively

La aplicacion consta de tres partes que puedes ser modificadas en el despliegue, sin embargo en pro de facilitar su despliegue utilizarems un unico docker desde docker hub.

## Proceso de creacion de dockers 

En caso de que se tenga el codigo fuente de la aplicacion podemos compilar el docker con la instruccion:

docker build -t skyg4mb/rois .

para efectos practicos utilizaremos tanto certificados como llaves privadas por defecto, sin embargo, se recomienda fuertemente cambiarlos (proximamente documentare el metodo para su modificacion)

La forma de ejecutarlo es la siguiente:

docker run -t -v config/default.ts:/app/config/default.ts skyg4mb/rois

En caso de querer detener su ejecucion podemos hacerlo con la instruccion 

docker container stop <containder id>
  
para visualizar el container id lo puede hacer con la instruccion docker container ls
  
