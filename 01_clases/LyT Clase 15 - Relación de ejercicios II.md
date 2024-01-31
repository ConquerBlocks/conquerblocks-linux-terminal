# Linux y la Terminal

## Relación de ejercicios II

> Partimos de la base de que nuestro usuario se llama usuario, si no es así, tendremos que sustitutir donde ponga usuario por el nombre que tenga el nuestro

### Ejercicio 1. Operaciones con el contenido de un fichero
- Situarnos en el directorio /home/usuario
- Crear el directorio ejercicio7
- Situarnos en el directorio ejercicio7 mediante direccionamiento relativo
- Crear un fichero de texto con el editor nano con el siguiente contenido:
Nombre;MME;SOM;REDES;APLOF;FOL
Miguel;6;5;7;8;9
Antonio;3;4;2;6;7
Luis;8;8;7;9;9
Sara;2;3;5;6;1
Maria;6;7;5;8;8

Ordenar las lineas del fichero por orden alfabético y redireccionalas a un fichero llamado
orden.txt
- Mostrar las columnas 1, 2 y 3 con el carácter separador " " y redireccionalas a un fichero
llamado "notas_miguel.txt"
- Mostrar las columnas 1 y 5 con el carácter separador " " y redireccionalas a un fichero
llamado "notas_aplof.txt"
- Mostrar las columnas 1 y 4 con el carácter separador " " y redireccionalas a un fichero
llamado "notas_redes.txt"
- Mostrar las columnas 1 y 6 con el carácter separador " " y redireccionalas a un fichero
llamado "notas_fol.txt"
- Mostrar las cadenas que contienen el nombre "Antonio" dentro de todos los ficheros txt
- Contar el número de líneas, palabras y caracteres de todos los ficheros txt


### Ejercicio 2. Información sobre usuarios y grupos de un sistema Linux
- Vamos a comprobar cómo guarda Linux la información sobre los usuarios y grupos del sistema.
- Para ello, realiza los siguiente pasos:
- Entra en el terminal en modo texto.
- Muestra por pantalla el contenido del fichero /etc/passwd de forma paginada (comando
more)
- Realiza un filtro, de forma que muestre, de cada línea del fichero, el nombre de usuario, su UID y su Shell de inicio (Filtro del fichero, y utilizamos el comando cut).
- A continuación, muestra el número de usuarios que hay dados de alta en el sistema
( en /etc/passwd, contar el número de líneas, utilizando filtro y wc).
- Después, indica el número de grupo que tenemos en el sistema.
- Muestra de cada grupo únicamente el nombre del grupo y su GID. (cut)
- Visualiza, del grupo usuario, únicamente la lista de usuarios que lo tienen como secundario.

### Ejercicio 3. Comandos
- Desde un terminal modo texto
- Localiza la ubicación dónde se encuentra el programa ejecutable gedit
- Como superusuario, localiza la ubicación del fichero auth.log
- Ejecuta en segundo plano o background el navegador firefox abriendo la URL de la plataforma automáticamente
- Situarnos en el directorio /home/usuario y nn la misma línea, ejecuta los siguientes comandos:
- Listar el contenido del directorio /etc/init.d mediante acceso relativo (como superusuario)
- Esperar 3 segundos
- Mostrar el árbol de ficheros y directorios del directorio /etc/rc2.d (como superusuario)
- Mediante el uso de un sólo comando y uso de tuberías o pipes (|) y redirecciones (>):
- Contar el número de ficheros del directorio /etc que tienen la extensión .conf
- Crear un fichero llamado volcado.txt que contenga:
- El número de ficheros del directorio /var/log que acaban en .log
