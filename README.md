# screenfetch
Instalación de Screenfetch 
Para Instalar screenfetch en las diferentes distribuciones de GNU/Linux escribimos lo siguiente en nuestra terminal (modo superusuario).

Derivados de Debian (Ubuntu,PureOs,antiX,SolydXK,MXLinux,Parrot OS,Kali linux, linux mint etc)

sudo apt-get install screenfetch
--------------------------------------------------------------
Archlinux o de distribuciones derivadas de Archlinux:

sudo pacman -S screenfetch
-----------------------------------------------------
usuarios de Fedora o distribuciones derivadas de Fedora:

sudo dnf install screenfetch
-----------------------------------------------------
Por lo tanto después de ejecutar el software disponemos de la siguiente información:

El logo de nuestra distribución.
Nuestro nombre de usuario y el nombre del equipo.
La versión del Kernel que estamos usando.
El tiempo que lleva abierto nuestro ordenador.
El número de paquetes que tenemos instalado en nuestro sistema operativo.
La versión de Bash que estamos usando.
La resolución de nuestra pantalla.
El entorno de escritorio que estamos utilizando.
El tema que estamos usando en nuestro sistema operativo.
El tema de iconos que estamos usando.
El tipo de fuente que tenemos configurada.
El procesador que tiene nuestro ordenador.
La tarjeta gráfica que tiene nuestro ordenador.
La memoria RAM usada y disponible de nuestro ordenador.
Toda la información que se muestra es autodetectada por el mismo programa y nosotros no tenemos que realizar absolutamente nada.

CONFIGURAR LA INFORMACIÓN QUE SE MUESTRA
Screenfetch permite configurar el modo en el que queremos que se muestre la información. De este modo podemos modificar el contenido que aparece en pantalla siguiendo las siguientes instrucciones.

---------------------------

Si queremos que se muestre la totalidad de la información que hemos visto con anterioridad a excepción del logo, deberemos usar el siguiente comando:

screenfetch -n
----------------
Si queremos se muestre la totalidad de información pero únicamente usando el color de texto que tenemos definido en la terminal, tenemos que ejecutar el siguiente comando:

screenfetch -N
-------------------------
Si alguno de los parámetros que tiene que proporcionar el programa da error porqué el programa no es capaz de autodetectar los valores, podemos hacer que no salga en pantalla usando el siguiente comando:

screenfetch -E
------------------------
Si queremos que únicamente se imprima el logo de nuestra distro tenemos que usar el siguiente comando:

screenfetch -L
--------------------------
Si queremos que únicamente se imprima el logo de nuestra distro, y que además el logo sea en color rojo, tenemos que usar el siguiente comando:

screenfetch -c 9 -L
------------------------------
Nota: Si reemplazamos el número 9 por cualquier otro número contenido entre el 0 y el 9, conseguiremos variar el color del logo de nuestra distro.
Si queremos visualizar el resultado de la salida en el hipotético caso que tuviéramos instalada la distro Deppin, podemos ejecutar el siguiente comando en la terminal:

screenfetch -D 'Debian'
-----------------------------
Nota: Podemos sustituir la palabra Debian por el nombre de la distribución que nosotros queramos. Los nombres de las distribuciones disponibles las podéis encontrar en la sección Supported GNU/Linux Distributions de las manpages de screenfetch.
Para más información sobre las opciones de configuración de este programa, pueden consultar las manpages ejecutando el siguiente comando en la terminal:

man screenfetch
---------------------

