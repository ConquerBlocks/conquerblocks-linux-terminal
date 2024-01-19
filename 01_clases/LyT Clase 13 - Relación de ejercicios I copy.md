# Linux y la Terminal

## Relación de ejercicios I

> Partimos de la base de que nuestro usuario se llama usuario, si no es así, tendremos que sustitutir donde ponga usuario por el nombre que tenga el nuestro

### Ejercicio 1. Uso básico de comandos de manejo de ficheros y directorios
- Situarnos en el directorio /home/usuario
- Comprobar el directorio de trabajo actual
- Crear un directorio llamado conquer
- Situarnos en el directorio conquer
- Crear el fichero vacío prueba1.txt
- Copiar prueba1.txt como prueba2.txt y prueba3.txt
- Situarnos en el directorio /home/usuario
- Copiar el directorio conquer como conquer_copia
- Comprobar o listar desde /home/usuario el contenido de los directorios en formato largo: /home/usuario/conquer y /home/usuario/conquer_copia

### Ejercicio 2. Ficheros de usuarios y grupos
- Indica los campos (separados por :) que reflejan las siguientes líneas y en que ficheros aparecen estas líneas:
- usuario:x:1000:1000:usuario,,,:/home/usuario:/bin/bash
- adm:x:4:usuario

### Ejercicio 3. Enlaces a ficheros
- Situarnos en el directorio /home/usuario
- Crear el directorio ejercicio3
- Situarnos en ejercicio3 mediante direccionamiento relativo
- El fichero texto.txt debe contener el texto "Este es el ejercicio 4"
- Crear un enlace simbólico en este mismo directorio llamado enlace.lnk que apunte a texto.txt
- Mostrar el listado del directorio ejercicio3 en formato largo
- Mostrar los tipos de ficheros contenidos en el directorio ejercicio3

### Ejercicio 4. Uso básico de comandos de manejo de ficheros y directorios
- Situarnos en el directorio /home/usuario
- Crear un directorio Practica2
- Entrar dentro de Practica y crear los directorios Primera, Segunda y Tercera
- Entrar en Primera y crear los directorios EV1 y EV2
- Con el comando nano crear un documento llamado f1.txt en la carpeta EV1, que contenga un nombre cualquiera.
- Nos cambiamos al directorio Tercera usando direccionamiento relativo
- Copiar fichero f1.txt a la carpeta Tercera con el nombre f2.txt
- Mover f2.txt a la carpeta Segunda
- Mostrar el árbol del directorio /home/usuario

### Ejercicio 5. Manejo de comodines
- Situarnos en el directorio /home/usuario
- Crear el directorio ejercicio7
- Situarnos en el directorio ejercicio7 mediante direccionamiento relativo
- Crear un fichero vacío llamado texto1.txt
- Copiar texto1.txt como texto2.txt
- Copiar texto1.txt como texto3.txt
- Copiar texto1.txt como texto4.txt
- Copiar texto1.txt como texto5.txt
- Crear un directorio llamado ficheros1
- Copiar todos los ficheros terminados en txt en el directorio ficheros1
- Crear un directorio llamado ficheros2
- Copiar todos los ficheros que empiezan por “texto” y acaban por “.txt” en el directorio ficheros2
- Crear un directorio llamado ficheros3
- Copiar todos los ficheros que empiezan por “texto” seguido de un numero de 1 a 3 en el directorio ficheros3
- Mostrar el listado del directorio ejercicio7 y de todos sus subdirectorios en formato largo







### Ejercicio 2. Uso básico de comandos de manejo de ficheros y directorios
- Situarnos en el directorio /home/usuario
- Comprobar el directorio de trabajo
- Crear un directorio llamado ejercicio2
- Situarnos en el directorio ejercicio2
- Crear con el comando echo un fichero cuyo contenido sea la frase "Soy un campeón y me merezco lo mejor", el nombre del fichero será frase.txt
- Crear el fichero listado.txt con el resultado de ejecutar el comando que lista los contenidos del directorio /home/usuario
- Comprobar el contenido del fichero listado.txt
- Crear el fichero discos.txt con el resultado de ejecutar el comando que muestra información del sistema de ficheros de nuestra máquina
- Comprobar el contenido del fichero discos.txt
- Crear el fichero arbol.txt con el resultado de ejecutar el comando que muestra el árbol de contenidos del directorio /home
- Comprobar el contenido del fichero arbol.txt
- Crear el fichero ocupacion.txt con el resultado de ejecutar el comando que muestra la ocupación en formato humano de los directorios y ficheros del directorio /home
- Comprobar el contenido del fichero ocupacion.txt









### Ejercicio 7. Operaciones con el contenido de un fichero
- Situarnos en el directorio /home/usuario
- Crear el directorio ejercicio7
- Situarnos en el directorio ejercicio7 mediante direccionamiento relativo
- Crear un fichero de texto con el editor nano con el siguiente contenido:
◦	Nombre MME SOM REDES APLOF FOL

◦	Miguel 6 5 7 8 9
◦	Antonio 3 4 2 6 7
◦	Luis 8 8 7 9 9
◦	Sara 2 3 5 6 1
◦	Maria 6 7 5 8 8
- Ordenar las lineas del fichero por orden alfabético y redireccionalas a un fichero llamado orden.txt
- Mostrar las columnas 1, 2 y 3 con el carácter separador “ “ y redireccionalas a un fichero llamado “notas_miguel.txt”
- Mostrar las columnas 1 y 5 con el carácter separador “ “ y redireccionalas a un fichero llamado “notas_aplof.txt”
- Mostrar las columnas 1 y 4 con el carácter separador “ “ y redireccionalas a un fichero llamado “notas_redes.txt”
- Mostrar las columnas 1 y 6 con el carácter separador “ “ y redireccionalas a un fichero llamado “notas_fol.txt”
- Mostrar las cadenas que contienen el nombre “Antonio” dentro de todos los ficheros txt
- Contar el número de líneas, palabras y caracteres de todos los ficheros txt

Ejercicio 8. Interfaz gráfico de Ubuntu
- Añade un panel en la zona izquierda o lateral Izquierda de la pantalla cuyo tamaño sea de 65 píxeles y le añadimos los siguientes elementos: salir; nota adhesiva; frecuencia de la CPU; buscar archivos y los ojos. Añadiremos una nota adhesiva recordatoria del examen de SO del Viernes 31 de Enero.


### Ejercicio 10. Información sobre usuarios y grupos de un sistema Linux
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

### Ejercicio 11. Comandos
- Desde un terminal modo texto
- Localiza la ubicación dónde se encuentra el programa ejecutable gedit
- Como superusuario, localiza la ubicación del fichero auth.log
- Ejecuta en segundo plano o background el navegador firefox abriendo la URL de la plataforma automáticamente
- Situarnos en el directorio /home/usuario y nn la misma línea, ejecuta los siguientes comandos:
◦	Listar el contenido del directorio /etc/init.d mediante acceso relativo (como superusuario)
◦	Esperar 3 segundos
◦	Mostrar el árbol de ficheros y directorios del directorio /etc/rc2.d (como superusuario)
- Mediante el uso de un sólo comando y uso de tuberías o pipes (|) y redirecciones (>):
◦	Contar el número de ficheros del directorio /etc que tienen la extensión .conf
◦	Crear un fichero llamado volcado.txt que contenga:
▪	El número de ficheros del directorio /var/log que acaban en .log
