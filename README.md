## 1. Descripción del proyecto
Este proyecto tiene como objetivo el uso de un proyector holograma sin necesidad de su aplicación móvil complementaria. Buscaremos las posibles vulnerabilidades, servicios, puertos, protocolos, etc, que tenga el proyector a través de análisis forenses, tanto de las aplicaciones como del dispositivo mismo. Una vez realizado esto y conociendo como se envían los paquetes del cambio de vídeo, crearemos un script donde podamos elegir el vídeo que queramos reproducir sin necesidad de ninguna aplicación.

## 2. Despliegue

El despliegue de este proyecto se llevará a cabo en 4 etapas:

### 2.1 Análisis forense del dispositivo

El primer paso consiste en el descubrimiento de todos los servicios, protocolos, puertos, etc, que tiene el proyector holograma. Para esto usaremos la herramienta 'Nmap', disponible tanto en Windows como en Ubuntu. En Windows nos lo podemos descargar desde el enlace https://nmap.org/download.
Para Ubuntu sería a través del comando sudo apt install nmap -y.
Todo esto se detalla en el entregable de la wiki _**[aquí](https://github.com/iesgrancapitan-proyectos/202122asir-junio-nombreproyecto-pacopanaderoruiz/wiki/An%C3%A1lisis-forense-del-dispositivo.)**_

### 2.2 Análisis forense de la aplicación

En esta etapa descomprimiremos la aplicación móvil para ver su código fuente. Esto nos servirá para entender un poco más como funciona la aplicación en sí, aunque no tenga ninguna función más. Todo esto se detalla en el entregable de la wiki _**[aquí](https://github.com/iesgrancapitan-proyectos/202122asir-junio-nombreproyecto-pacopanaderoruiz/wiki/Análisis-forense-de-la-aplicación)**_

### 2.3 Análisis forense de la red

En esta etapa tendremos como objetivo analizar el envío de paquetes que se produce entre el dispositivo y nuestros equipos. Para ello usaremos la aplicación Wireshark para ver todo el tráfico de la red. Este programa se puede descargar directamente de Internet a través del enlace https://www.wireshark.org/download.html. 
Todo esto se detalla en el entragable de la wiki _**[aquí](https://github.com/iesgrancapitan-proyectos/202122asir-junio-nombreproyecto-pacopanaderoruiz/wiki/An%C3%A1lisis-forense-de-la-red)**_

### 2.4 Prueba de concepto.

Por último, sera crear el script que usemos para cambiar los vídeos sin necesidad de la aplicación móvil.
Todo esto se detalla en el entregable de la wiki _**[aquí](https://github.com/iesgrancapitan-proyectos/202122asir-junio-nombreproyecto-pacopanaderoruiz/wiki/Prueba-de-concepto)**_

## 3. Uso

Una vez creado el script que usemos para cambiar los vídeos sin necesidad de la aplicación móvil, su uso será muy sencillo. Este script será ejecutado usando el comando "bash (nombre del script)", en nuestro caso particular será bash scriptproyecto.sh.
Una vez ejecutado el script, saldrá un menú con varias opciones, la cuál elegirás tú. Cada opción sirve para una cosa diferente:
  
   - Listar los archivos para saber que vídeos hay en el holograma.
    
   - Subir archivos, para poder subir cualquier vídeo o foto que quieras en cualquier momento.
    
   - Descargar archivos, para que te puedes descargar cualquier vídeo que contenga el holograma.
    
   - Borrar archivos, para poder eliminar cualquier vídeo o foto que contenga el holograma.
    
   - Reproducir, que es la opción principal y objetivo de nuestro proyecto. Podremos seleccionar el vídeo que queramos y reproducirlo al momento.
    
   - Fin, se terminará el script.
    
Para todas las opciones, excepto para la de listar y el fin del script, tendremos que escribir el nombre del archivo para que se lleve a cabo el comando.
Esto será explicado más profundamente en el entregable 

## 4. Autores

Autores del proyecto: Francisco Ángel Panadero Ruiz y Alejandro Egusquiza Rey, alumnos de 2º de ASIR del IES Gran Capitán (Córdoba)

Supervisor: José Ramón Albendín Ramírez Profesor de Informática del IES Gran Capitán (Córdoba)
