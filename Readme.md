## curso Git desde cero 
Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos

### zonas de  Git 
1. Directorio de trabajo 
2. Area de preparación
3. Directorio Git 

### Flujo de trabajo básico en Git
1. Modificar una serie de archivos en tu directorio  de trabajo.
2. Prepara los archivos, añadiéndolos en tu área de preparación. 
2. Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantánea de manera permanente en tu directorio de Git.

##comandos
1. Git init inicializa git en en el proyecto o carpeta que estamos trabajando.
2. git Status muestra el status del archivo.
3. Git commit -m "añade un comentario al archivo que estas subiendo o los cambios que hiciste/con comillas".
4. git log dice quien hizo el commit, la hora y el comentario del commit (muestra el historial)
5. git add  "archivo a subir al repositorio sin comillas" zona de preparacion 
6. git diff muestra la ultima referencia del archivo es decir lo que se le añade al archivo y aparece en color verde 
7. git diff --staged vemos la diferencia entre un archivo ya preparado y el que no hemos preparado 
8. git add . añade todos los archivos esten en seguimiento con git o no, la zona de preparacion.
9. git reset HEAD "nombre del archivo" saca los archivos de la zona de preparación a la zona de trabajo 
10. git add -A agrega al area de preparación todos los archivos preparacion que estaomos siguiendo con Git
11. git commit --amend para cambiar el commit mas reciente que hicimos por otro comentario 
12. git mv file_from file_to  para renombar archivos 
13. git rm  para elimar el archivo con git 
14. git log --graph 
15. git log --oneline
16. git log --oneline --graph
17. git log --3 para ver los ultimos tres o el numero que le metamos es lo que nos mostrara
18. git log --pretty=format: "%h - %an(autor del commit),  %ar : %s"
                   7be4c0e - Joel Celaya,  2 days ago : notas de git
19.  git commit -a -m git prepara automaticamente todos los archivos rastreados antes de confirmarlos.                  
20. git checkout -- (nombre del archivo) recupera el archivo eliminado


## Git por primera vez 
1. git config --global user.name "JoelCLuna" 
2. git config --global user.email joelcluna@gmail.com
3. git config --global core. editor nano 
3. git config --list 

## 

##

##