##git log 
muestra todo el historial de commits del proyecto

7be4c0e - Joel Celaya,  2 days ago : notas de git


git log --pretty=format:"%h - %an, %ar : %s" 
 muestra el historial con el formato que indicamos. 
 
 ## limitar la salida del historial 
 git log -n  cambiamos la n por cualquier numero entero, por ejemplo:
 git log -2 nos mostrara los 2 commits mas recientes. 
 
 git log --after="2018-03-30"  : muestra los commits realizados despues de la fecha especificada
 git log --before="2018-03-30" : muestra los commits realizados antes de la fecha especificada
 
 las banderas del comando git log se pueden usar juntas segun convenga por ejemplo :
 git log --after="2018-03-30" --before="2018-04-03" 
 git log --after="2018-03-30 12:00:00" --before="2018-04-03 21:30:50" 
