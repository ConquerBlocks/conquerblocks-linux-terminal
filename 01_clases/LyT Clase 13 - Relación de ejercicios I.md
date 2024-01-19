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
- Copiar todos los ficheros que empiezan por "texto" y acaban por ".txt" en el directorio ficheros2
- Crear un directorio llamado ficheros3
- Copiar todos los ficheros que empiezan por "texto" seguido de un numero de 1 a 3 en el directorio ficheros3
- Mostrar el listado del directorio ejercicio7 y de todos sus subdirectorios en formato largo
