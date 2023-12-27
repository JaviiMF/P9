Para llevar a cabo la parte de bisect, he creado los siguientes 4 commits:
1) He añadido el archivo main.py con el programa funcionando correctamente
2) He añadido una operación extra al programa que muestro por pantalla
3) He modificado la función suma y he introducido el error
4) He añadido otra operacion extra para mostrar por pantalla

A continuación he ejecutado los siguientes comandos:
1) git bisect start
2) git bisect bad (indico que el commit actual es incorrecto)
3) git bisect good <commit_donde_el_programa_funcionaba>

De manera casi instantánea, ha detectado que commit ha introducido el error
