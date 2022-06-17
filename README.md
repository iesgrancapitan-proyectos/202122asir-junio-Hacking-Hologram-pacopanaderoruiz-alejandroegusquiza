## 1. Descripción del proyecto
Este proyecto tiene como objetivo el uso de un proyector holograma sin necesidad de su aplicación móvil complementaria. Buscaremos las posibles vulnerabilidades, servicios, puertos, protocolos, etc, que tenga el proyector a través de análisis forenses, tanto de las aplicaciones como del dispositivo mismo. Una vez realizado esto y conociendo como se envían los paquetes del cambio de vídeo, crearemos un script donde podamos elegir el vídeo que queramos reproducir sin necesidad de ninguna aplicación.

## 2. Despliegue

### 2.1 Herramientas hardware para el despliegue

Para llevar a cabo este proyecto, solo necesitaremos el proyector holograma 3D del aula AtecA y un ordenador donde poder descargarnos las herramientas software necesarias.

### 2.2 Herramientas software para el despliegue

Para llevar a cabo este proyecto, necesitaremos varios programas, como Nmap para descubrir los puertos y servicios, Wireshark para los análisis forenses, la aplicación para controlar el holograma, un simulador de android para el ordenador (en nuestro caso Genymotion), etc.
Para usar Genymotion tendremos que registrarnos en su página oficial.

Todas estas herramientas estarán explicadas en la wiki https://github.com/iesgrancapitan-proyectos/202122asir-junio-Hacking-Hologram-pacopanaderoruiz-alejandroegusquiza/wiki#5-recursos

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

Supervisor: José Ramón Albendín Ramírez. Profesor de Informática del IES Gran Capitán (Córdoba)
