clase Cómo se manejan los permisos 13/23
# bash
Linea de Comandos

# mkdir (make directory)
  Crea directorios
# touch
  Crea archivos
# cd
  cambia de directorio
# cp (copy)
  copia archivos o directorios
# mv (move)
  mueve archivos o directorios
# rm (remove)
  elimina un archivo
  * -i : interactive - Pregunta si estas seguro
  * -r : recursive - elimina todo lo que esta dentro del directorio
  * -f : force - fuerza a borrar todo

# head
muestra el contenido de las 10 primeras lineas del archivo
* n : permite elegir la cantidad de lineas a visualizar
# tail
muestra el contenido de las ultimas 10 filas del archivo
* n : permite elegir la cantidad de lineas del archivo

# less
    Muestra el contenido del archivo de manera interactiva
* para salir de less se utiliza la letra q

# xdg-open
    abre el archivo con el editor predeterminado

# nautilus
    abre la interfaz de ventanas de la carpeta que selecciones

# wildcards

# > Redirecciona la salida. Por defecto redirecciona el Standar Output

# > Concatena la salida con lo que ya tenga el archivo a donde se está redirigiendo la salida

# 2> Redirecciona el file descriptor 2 (En este caso Standar Error)

# 2>&1 Redirecciona el file descriptor 2 y 1