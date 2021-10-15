# Examen 15/10/2021  

En este documento explicaremos lo realizado en el examen.  

## Creando una incidencia  

1. Primero hemos creado una incidencia en el repositorio [https://github.com/srlopez/examen0106](https://github.com/srlopez/examen0106). Esto se hace como se puede ver en la Captura 1.  
   ![]({09}-IMG/Captura1.png)
2. Luego hemos realizado un fork del proyecto para tenerlo en nuestro repositorio.  
   ![]({09}-IMG/Captura2.png)  

## De la nube a nuestro ordenador

Hemos clonado el repositorio de github en nuestro ordenador, primero ubicandonos en el directorio donde queremos clonarlo y finalmente clonandolo. Este proceso se puede ver en la Captura 3.  
![]({09}-IMG/Captura3.png)  
Las capturas realizadas durante el proceso, las guardaremos en la carpeta *{09}-IMG* en la carpeta del repositorio. En esta misma carpeta creamos este fichero llamado *{09}-{Martin Fagoaga}.md*.  
![]({09}-IMG/Captura4.png)
Antes de continuar, hemos creado una rama local y nos hemos situado en ella con el siguiente comando:  
![]({09}-IMG/Captura5.png)  

## Edición del contenido

En este apartado simplemente hemos utilizado Visual Studio Code para editar el fichero *.md* como se puede ver en la imagen 6.  
![]({09}-IMG/Captura6.png)  

## Añadiendo los cambios y guardandolos en el repositorio  
1. Añadimos los ficheros que queramos a la rama local con *git add*, como se puede ver en la captura 7.  
   ![]({09}-IMG/Captura7.png)  
2. Una vez los archivos están como deseamos, guardamos el estado de nuestra rama local *rama1* utilizando los siguientes comandos:  
   ![]({09}-IMG/Captura8.png)  

## Subiendolo a github  

Finalmente subimos nuestra rama github utilizando el siguiente comando:  
```console
    git push -u origin rama1
```  

Una vez aquí solicitamos la incorporación de cambios en Github mediante el pull request y luego borrariamos la rama. Este apartado va sin imagenes por falta de tiempo.
