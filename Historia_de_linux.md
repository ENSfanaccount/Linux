# Linux: El Sistema Operativo de Código Abierto
## Historia de Linux 
La historia de Linux comienza con un estudiante finlandés llamado Linus Torvalds. En 1991, mientras estudiaba en la Universidad de Helsinki, Linus comenzó a trabajar en un nuevo núcleo de sistema operativo como pasatiempo.

Linus se inspiró en el sistema operativo Unix y deseaba crear un sistema similar a Unix que estuviera disponible de forma gratuita y que pudiera ejecutarse en computadoras personales.

![Alt Text](https://imgs.search.brave.com/RY-VrYJC6uNYM-bMCS1-42HxoRlSeMTB9FJQeTXKSDk/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvNTMy/NTAyNDE0L3Bob3Rv/L2xpbnVzLXRvcnZh/bGRzLmpwZz9zPTYx/Mng2MTImdz0wJms9/MjAmYz0zdE1pMGlv/bzFiaHgzSVc3WXQ1/VEI0VWRnN2VFdFVF/OHNuWDlwT1NQRXNn/PQ)

## Crecimiento y collaboraciones
Linus continuo desarrollando el kernel (intermediario entre el hardware y el software.) haciendolo open-source, haciendo así posible para otros desarrolladores formar parte del proyecto.

![Alt Text](https://imgs.search.brave.com/73_o4iluUxQDnP5ar2i_daEoUdhtvefBeRA5BPkV0e8/rs:fit:860:0:0/g:ce/aHR0cHM6Ly93d3cu/YWRzbHpvbmUubmV0/L2FwcC91cGxvYWRz/LWFkc2x6b25lLm5l/dC8yMDIwLzAzL2xp/bnV4Mi5qcGc)

## Distribuciones del Linux
Se estima que existen aproximadamente mas de 600 distribuciones de Linux, pero las mas conocidas son las siguientes:
### Ubuntu: 
Ubuntu es conocida por su facilidad de uso y su enfoque en la experiencia del usuario.
### Debian:
Debian es conocida por su estabilidad y es la base de muchas otras distribuciones, incluyendo Ubuntu. Es una elección popular en entornos de servidor y desarrollo.
### Fedora
 Se utiliza ampliamente en entornos de desarrollo y escritorios Linux.
 ### Kali linux
 Kali es una distribución especializada en seguridad informática y pruebas de penetración. Es ampliamente utilizada por profesionales de ciberseguridad.
![Alt Text](https://imgs.search.brave.com/mJJlAmCH6tDRJaktPjuLeqqdoqbGEeU4gsHrbF9C8Kc/rs:fit:860:0:0/g:ce/aHR0cHM6Ly93YWxs/cGFwZXJhY2Nlc3Mu/Y29tL2Z1bGwvMzUz/ODYwNi5wbmc)
## Instalación de Paquetes y Programas
### Install from source
Se instala el programa, se extrae y se coloca en el directorio deseado.

Para utilizarlo se utilizan los comandos:

./configure

make

make install

#### Ubuntu 16.10

En el caso de esta distribución de Linux es necesario instalar el paquete de autoconf con el comando:

sudo apt-get install autoconf

Dependiendo de la versión y paquete, también existe la posibilidad de que se requieran instalar los paquetes build-dep y build-essential
![Alt Text](https://lcom.static.linuxfound.org/sites/lcom/files/source_a.jpg)

### Ubuntu
Ubuntu utiliza un administrador de paquetes derivado de Devian.

Generalmente para instalar un programa o paquete se accede a la terminal y se utiliza el comando siguiente:

sudo apt install "Nombre del paquete"

Para borrar ese paquete se utilizaría el comando:

sudo apt remove "Nombre del paquete"

### Apt

Apt es corto para aptitude.
Línea de código:

sudo aptitude

Nos brinda otra forma de acceder a los paquetes, además de brindarnos un status de los mismos.

Los repositorios pueden ser accedidos en /etc/apt/sources.list

### Dpkg
Dpkg es otro administrador de paquetes que se encuentra en Ubuntu pero generalmente no se utiliza ya que Apt brinda más herramientas.

### Repositorios Extra
Además podemos acceder a repositorios que se encuentran fuera de los oficiales del sistema siguiendo la dirección de /etc/apt/sources.list y comentando algunas líneas.

### Actualizaciones automaticas
Es posible configurar las actualizaciones automaticas utilizando:

sudo apt install unnattended-upgrades

## Historia de Git

Git fue creada por Linus Torvals en 2005. Durante el desarrollo de Linux se utilizó un DVCS llamado Bitkeeper. Al tener problemas con el mismo la comunidad creadora de Linux decide crear Git.

![Alt Text](https://nodd3r.com/media/blog/Portadas_blog_21.png)
