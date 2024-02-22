# Comando para conectar mi git local con el git en la nube
- git remote add nombre-conexion(origin) url-conexion (cuando ya tengo algo en el git local de esto)

## Comando para clonar o traer repositorio de git remoto
- git clone url-conexion(para cuando voy a comenzar a codear y no tengo nada en el archivo)

## Comando para listar las conexiones remotas
- git remote -v

## Comando para eliminar una conexion remota
- git remote remove nombre_conexion

## Comando para enviar informacion del git remoto
- git push
- git push nombre_conexion nombre_rama
- git push -u nombre_conexion nombre _rama
- git push --all

## Comando para obtener cambios o la informacion que hay en el git remoto
- git pull
- git pull nombre_conexion nombre_rama