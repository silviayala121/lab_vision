# Warmup Questions

1.  What is the clone url of this repository?
    >   answer
https://github.com/silviayala121/lab_vision.git

2.  What is the output of the ``cal`` command?

        multi
        line
        answer
        Cal muestra un calendario simple. Si no se especifican argumentos, se muestra el mes actual.
        
    Ejemplo:
    ubuntu-gnome@ubuntu-gnome:~$ cal
   February 2015      
Su Mo Tu We Th Fr Sa  
 1  2  3  4  5  6  7  
 8  9 10 11 12 13 14  
15 16 17 18 19 20 21  
22 23 24 25 26 27 28

        Las opciones son las siguientes:
-1 Mostrar la salida solo mes. (Este es el valor predeterminado.)
-3 Pantalla prev / salida de corriente / mes que viene.
-s Mostrar el domingo como el primer día de la semana. (Este es el valor predeterminado.)
-m Mostrar el lunes como el primer día de la semana.
-j Pantalla fechas julianas (día uno basado en, contados a partir del 1 de enero).
-y Mostrar un calendario para el año en curso.



# Homework Questions

1.  What is the ``grep``command?
    >   answer
grep es un comando usado para buscar texto o busca en el archivo dado por las líneas que contengan una coincidencia con las cadenas o palabras dadas

2.  What is a *makefile*?
    >   answer
Un makefile es un archivo que contiene instrucciones para el programa 'make'

3.  What is *git*?
    >   answer
es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. 

4.  What does the ``-prune`` option of ``find`` do? Give an example
    >   answer
Encuentra todos los archivos y directorios presentes sólo en el directorio actual 
Ejemplo:
[vision@guitaca ~]$ find -prune
.
[vision@guitaca ~]$ 

5.  Where is the file ``xxxxxx``
    >   answer
No se encontró el archivo 

6.  How many files with ``gnu`` in its name are in ``dir``
    >   answer
[vision@guitaca home]$ cd /usr/src
[vision@guitaca src]$ find / -name '*gnu*' 2>/dev/null | wc -l  
656
[vision@guitaca src]$ 

7.  How many files contain ``gpl`` inside in ``dir``
    >   answer
[vision@guitaca src]$ find / -name '*gpl*' 2>/dev/null | wc -l
324
[vision@guitaca src]$ 

8.  What does the ``cut`` command do?
    >   answer
Remueve secciones de cada línea de archivos

9.  What does the ``wget`` command do?
    >   answer
Descarga ficheros desde Internet en modo consola

10.  What does the ``diff`` command do?
    >   answer
se utiliza para encontrar diferencias entre dos archivos

11.  How many users exist in *Guitaca*?
    >   answer
[vision@guitaca etc] cd /etc
[vision@guitaca etc] ls
[vision@guitaca etc] cat passwd
[vision@guitaca etc]$ cat passwd | wc -l
48
[vision@guitaca etc]$ 

12. What command will produce a table of Users and Shells sorted by shell (tip: using ``cut`` and ``sort``)
    >   answer

13. What command will produce the number of users with shell ``/sbin/nologin`` (tip: using ``grep`` and ``wc``)
    >   answer

14.  What is the name of the linux distribution running on *Guitaca*?
    >   answer

15. Create a script for finding duplicate images based on their content (tip: hash or checksum)
    You may look in the internet for ideas, but please indicate the source of any code you use
    Save this script as ``find_duplicates.sh`` in this directory and commit your changes to github

16. What is the meaning of ``#! /bin/bash`` at the start of scripts?
    >   answer
Esta linea indica donde se encuentra el interprete de comandos en nuestro sistema. Por defecto todos los sistemas que tengan Bash instalado, lo tendran en el directorio /bin. 

17. How many unique images are in the ``sipi_images`` folder?
    >   answer
    
