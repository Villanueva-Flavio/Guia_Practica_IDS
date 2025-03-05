# Guía Práctica - Introducción al Desarrollo de Software
> Cátedra: 02 Lanzillotta

> Autores: Flavio Villanueva, Nestor Palavecino

> Actualizado: 1C2025

## Introducción

Esta guía contempla ejercicios prácticos que abarcan todo el plan de estudio de la materia, y un poco más (Ver más adelante). Se recomienda trabajar dentro de una nueva carpeta con permisos de administrador y usar `sudo` cuando sea necesario.

Esta guía práctica se divide en capítulos, existen diversos temas que se vuelven a ver ya que se integran con otros conceptos, como `Shell + Python` o `Shell + Docker`, por lo que se recomienda seguir el orden de los capítulos.

## Requisitos

- Sistema operativo Linux (preferentemente: [Mint](https://www.linuxmint.com/download.php) / [Ubuntu](https://ubuntu.com/download) / [Debian](https://www.debian.org/devel/debian-installer/)) o cualquiera que use APT y Bash.
- Una computadora que prenda (Opcional)
- El sistema operativo debe estar instalado ya sea [nativamente](https://ubuntu.com/download), en una [máquina virtual](https://www.virtualbox.org/wiki/Downloads) o en [WSL](https://apps.microsoft.com/detail/9pn20msr04dw?hl=es-ES&gl=ES).
- Python 3.8 o superior
- MySQL 8.0 o superior
- Flask 2.0 o superior
- Docker y Docker Compose

## Índice

### **Capítulo 1: Bash - Conceptos básicos**
- Introducción a Bash: Ejercicios de comandos básicos para el uso general de Linux, manejo de archivos y carpetas
- Automatización de tareas: Ejercicios de scripts en Bash para automatizar tareas comunes
- Automatización de herramientas útiles

### **Capítulo 2: Regex en Bash**
- Introducción a Regex: Ejercicios de comandos básicos para el uso general de Regex, manejo de archivos y carpetas
- Regex en bash y python
- Ejemplos de uso para verificar la validez de datos
- Modificación de datos específicos de archivos

### **Capítulo 3: Python**
- Introducción a Python: Ejercicios de comandos básicos para el uso general de Python, manejo de archivos y carpetas
- Ejecución de comandos de bash y uso de regex dentro de Python.
- Uso del entorno virtual y PIP

### **Capítulo 4: Regex en Python**
 - Uso de comandos generales de Regex en Python
 - Validacion de variables de Python con Regex

### **Capítulo 5: Flask y el desarrollo web**
- Introducción a Flask: Ejercicios de comandos básicos para el uso general de Flask, manejo de archivos y carpetas
- Creación de una aplicación web con Flask
- Carga de datos como JSON, CSV y otros formatos
- Creacion de APIs

### **Capítulo 6: HTML y CSS**
- Introducción a HTML y CSS: Ejercicios de comandos básicos para el uso general de HTML y CSS, manejo de archivos y carpetas
- Creación de páginas web con HTML y CSS
- Creación de plantillas con Jinja

### **Capítulo 7: Bash para el desarrollo web**
- Automatización de la creación de páginas web con Bash
- Automatización de levantamiento de proyectos de Flask con entornos Virtuales
- Instalación de paquetes de Python con PIP automaticamente

### **Capítulo 8: JavaScript**
- Creación de Scripts y modularización
- Conceptos básicos del DOM
- Manejo del DOM con eventos
- API Fetch
- Comunicación FrontEnd con Flask en tiempo real

### **Capítulo 9: MySQL**
- Introducción a MySQL: Ejercicios de comandos básicos para el uso general de MySQL, manejo de bases de datos y tablas
- Diseño de bases de datos
- Claves primarias y foráneas
- Condicionales, Joins y Subconsultas
- Integración de MySQL al uso general en Flask

### **Capítulo 10: Docker**
- Creación, eliminación y manejo de contenedores y volumenes
- Uso de docker-compose para la creación de contenedores completos
- Creación de contenedores con Flask, MySQL, y otros servicios
- Automatización de contenedores descargados desde GitHub u obtenidos por wget

### **Capítulo 11: Bash para contenedores**
- Automatización de la creación de contenedores con Bash
- Automatización de descarga despliegue y ejecución de contenedores en Bash
- Descarga y Configuración de proyectos completos en docker-compose con Bash


## Glosario

Durante la guía se utilizarán términos específicos que se detallan a continuación para comprender mejor la clase de ejercicios a los que te enfrentarías:

> [🎩] Sombrero de mago  -> Este ejercicio cuenta con un truco, no es dificil su comprensión, solo que a veces requiere verlo desde otra perspectiva. (¬‿¬)

> [💀] Calavera -> Este ejercicio es dificil. (╯°□°）╯︵ ┻━┻

> [📌] Pin -> El resultado de este ejercicio te servirá para reutilizarlo en el futuro en algún código propio. (★‿★)

> [🕵️‍♂️] Detective -> Este ejercicio es siempre opcional, cuenta con temas que no están incluidos en el plan de estudios, por lo que tendrás que investigar por tu cuenta, pero aportan pistas útiles para el desarrollo profesional personal. (>_>)🔎 

> [🌐] Red -> Este ejercicio requiere que descargues algo en particular. 🌍───📡───💻

## Recursos

### Sobre la cátedra
- [Página de la cátedra](https://introds-web.vercel.app/)
- [Drive de la cátedra](https://drive.google.com/drive/folders/1EaowjueNp7y7_b0Qj_PyDmSJaaZOescM?usp=sharing)
- [Youtube de la cátedra](https://www.youtube.com/@Intro.Desa.Soft-Lanzillotta)

### Sobre los temas

- [FetchAPI](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [MySQL](https://www.mysql.com/)
- [Python](https://www.python.org/)
- [Regex](https://regex101.com/)
- [Bash](https://www.gnu.org/software/bash/)
- [JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Jinja](https://jinja.palletsprojects.com/en/3.0.x/)
- [PIP](https://pypi.org/project/pip/)
- [Entornos Virtuales](https://docs.python.org/3/library/venv.html)

## Contacto

### Links

- [Whatsapp de la cátedra](https://chat.whatsapp.com/LWHJN7BCCed0FbeIGOEUkp)
- [Slack de la cátedra](https://introduccinal.slack.com/join/shared_invite/zt-2oyza3902-Z0OB8B9toYkckl3O8ssKhA#/shared-invite/email)
- [Clases Virtuales (Teams)](https://teams.microsoft.com/l/meetup-join/19:0NZNrUQO3GGN51dmSQ68i6jTVt2hmgua3lkeqbD_qKQ1@thread.tacv2/1724120723048?context=%7B%22Tid%22:%22b41ac89a-6984-4110-853b-f6f558dee7d4%22,%22Oid%22:%2229ed7c2a-a6cb-4c35-a37a-bce4395f4902%22%7D)

### Emails

- Bruno Lanzillotta: blanzillotta@fi.uba.ar
- Flavio Villanueva: fvillanueva@fi.uba.ar
- Nestor Palavecino: npalavecino@fi.uba.ar
- Departamento de computación: computacion@fi.uba.ar
