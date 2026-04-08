# IAC-lab01-martes

Tenemos codigo de una aplicacion web, 
Se compone por un archivo HTML que tiene como contenido: WEB01

Publicar esta web, especificamente una sola copia como primera instancia

TAREA DESPLEGAR DOS WEB, MOSTRAR WEB01, Y WEB 02 como contenido
Los puertos deben estar configurados en 4000 y 4001
Gestuonar Carpetas para ordenar
Hacer uso de Gitflow/Conventional Commits

Se uso: docker run -d --name web02 -p 4001:80 web02-image
        docker run -d --name web01 -p 4001:80 web01-image