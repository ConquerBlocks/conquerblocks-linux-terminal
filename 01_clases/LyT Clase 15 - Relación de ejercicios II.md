# Linux y la Terminal

## Relación de ejercicios II

> Partimos de la base de que nuestro usuario se llama usuario, si no es así, tendremos que sustitutir donde ponga usuario por el nombre que tenga el nuestro

### Ejercicio 1. Operaciones con el contenido de un fichero
- Situarnos en el directorio /home/usuario
- Crear el directorio ejercicio1
- Situarnos en el directorio ejercicio1 mediante direccionamiento relativo
- Crear un fichero de texto con el editor nano con el siguiente contenido:

Nombre;MME;SOM;REDES;APLOF;FOL \
Miguel;6;5;7;8;9 \
Antonio;3;4;2;6;7 \
Luis;8;8;7;9;9 \
Sara;2;3;5;6;1 \
Maria;6;7;5;8;8

- 1.1 Ordenar las lineas del fichero por orden alfabético y redireccionalas a un fichero llamado
orden.txt
- 1.2 Mostrar las columnas 1 y 5 y redireccionalas a un fichero llamado "notas_aplof.txt"
- 1.3 Mostrar las columnas 1 y 4 y redireccionalas a un fichero llamado "notas_redes.txt"
- 1.4 Mostrar las columnas 1 y 6 y redireccionalas a un fichero llamado "notas_fol.txt"
- 1.5 Mostrar las columnas 1, 2 y 3 y redireccionalas a un fichero llamado "notas_miguel.txt" mostrando únicamente las notas de miguel
- 1.6 Mostrar las cadenas que contienen el nombre "Antonio" dentro de todos los ficheros txt
- 1.7 Contar el número de líneas, palabras y caracteres de todos los ficheros txt


### Ejercicio 2. Información sobre usuarios y grupos de un sistema Linux
Vamos a comprobar cómo guarda Linux la información sobre los usuarios y grupos del sistema.
Para ello, realiza los siguiente pasos:
- Entra en el terminal en modo texto.
- 2.1 Muestra por pantalla el contenido del fichero /etc/passwd de forma paginada
- 2.2 Realiza un filtro, de forma que muestre, de cada línea del fichero, el nombre de usuario, su UID y su Shell de inicio.
- 2.3 A continuación, muestra el número de usuarios que hay dados de alta en el sistema (en /etc/passwd, contar el número de líneas, utilizando filtro y wc).
- 2.4 Después, indica el número de grupos que tenemos en el sistema.
- 2.5 Muestra de cada grupo únicamente el nombre del grupo y su GID.
- 2.6 Visualiza, del grupo usuario, únicamente la lista de usuarios que lo tienen como secundario.

### Ejercicio 3. Comandos
- 3.1 Desde un terminal modo texto. Localiza la ubicación dónde se encuentra el programa ejecutable nano
- 3.2 Situarnos en el directorio /home/usuario y en la misma línea, ejecuta los siguientes comandos: Listar el contenido del directorio /etc/init.d mediante acceso relativo (como superusuario), esperar 3 segundos y mostrar el árbol de ficheros y directorios del directorio /etc/rc2.d (como superusuario)
- 3.3 Mediante el uso de un sólo comando y uso de tuberías o pipes (|) y redirecciones (>): Contar el número de ficheros del directorio /etc que tienen la extensión .conf
- 3.4 Crear un fichero llamado volcado.txt que contenga: El número de ficheros del directorio /var/log que acaban en .log
