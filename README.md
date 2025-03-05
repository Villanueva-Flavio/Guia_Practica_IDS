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



# **Guía 1: Bash - Conceptos básicos**

## Introducción
Esta guía proporciona ejercicios prácticos para mejorar el manejo de Bash, enfatizando la modificación de archivos y directorios. Se recomienda trabajar dentro de una carpeta de prueba para evitar la pérdida de datos importantes. Los ejercicios pueden ejecutarse en WSL, una máquina virtual, un entorno nativo de Linux o en AWS o en una Raspberry Pi Zero.

En esta guía se presentarán muchas acciones que se pueden hacer con el mouse como borrar o cambiar nombre, pero se pide que se haga todo con Bash, porque esa es la idea.

### Comandos cubiertos
- `mkdir`, `sed`, `cat`, `cd`, `ls`, `rm`, `mv`, `cp`, `chgrp`, `chown`, `chmod`, `man`, `tree`
- Se recomienda el uso de `man` para consultar detalles de cada comando: `man <comando>`
- Navegación en `man`: Salir (`q`), Moverse (`↑ ↓`)

---

## Ejercicios

### Ejercicio 1: Creación de directorio de trabajo
Cree una carpeta de trabajo evitando el uso de espacios en el nombre. Se recomienda utilizar `sudo` para garantizar permisos adecuados.
![1 1](https://github.com/user-attachments/assets/d7207dbd-676e-41ff-9c91-4783392088a3)

### Ejercicio 2: Acceder a la carpeta creada
Ingrese a la carpeta creada en el ejercicio 1.
![1 2](https://github.com/user-attachments/assets/6e3e51bc-9e23-4ca4-aa2d-48c273af07b5)

### Ejercicio 3: Creación de un archivo y asignación de permisos
Genere un archivo de texto con el siguiente texto como contenido: `Hello world`, y concédale permisos de lectura, escritura y ejecución para todos los usuarios. Luego, asigne su usuario como propietario y grupo.
![1 3](https://github.com/user-attachments/assets/20c22ae2-3d65-4196-a599-5170399bcd93)

### Ejercicio 4: Visualización de permisos y propietario del archivo
Muestre en pantalla el archivo con sus permisos y detalles de propiedad.
![1 4](https://github.com/user-attachments/assets/e4296c44-b1c4-4462-a74f-4b84d5b4f2cc)

### Ejercicio 5: Copia de archivos
Cree un directorio llamado `copia` al mismo nivel que el archivo existente y copie el archivo creado en él.
![1 5](https://github.com/user-attachments/assets/d897e3a1-e298-482e-95c9-fe72a3db795e)

### Ejercicio 6: Edición y restauración de archivos
Elimine el archivo original, y edite la copia con Bash haciendo que esta diga: `Hello IDS`, después muévala a su ubicación original, y elimine el directorio `copia`, y finalmente, muestre el contenido del archivo.
![1 6](https://github.com/user-attachments/assets/22deb3b1-65aa-4ec2-82c3-5bfbd9e69f26)

### Ejercicio 7: Visualización de estructura de archivos
Diríjase a un directorio por encima del raíz de este proyecto e imprima su contenido de forma jerárquica utilizando `tree`.
![1 7](https://github.com/user-attachments/assets/55b02cad-aadf-4355-9535-17082032c471)

### Ejercicio 8: Creación de estructuras de directorios
Vuelva al directorio y cree dos directorios, `A` y `B`. Dentro de `A`, genere un archivo `test.txt` con contenido de prueba.
![1 8](https://github.com/user-attachments/assets/e1c41abd-e8e5-4ee8-beb3-e99dab793253)

### Ejercicio 9: Visualización de un archivo desde otro directorio
Desde `B`, liste el contenido de `test.txt` ubicado en `A`.
![1 9](https://github.com/user-attachments/assets/f24fed58-26ee-4b7c-ae2c-2940418fe023)

### Ejercicio 10: Mover archivos entre directorios
Desde `B`, mueva `test.txt` desde `A` a `B`.
![1 10](https://github.com/user-attachments/assets/7bf3ecab-a2c8-4f58-ade8-4ab0939d161b)

### Ejercicio 11: Restauración del archivo a su ubicación original
Desde `B`, regrese `test.txt` a `A`.
![1 11](https://github.com/user-attachments/assets/f4c55b96-db65-4662-8d0e-61207fd08981)

### Ejercicio 12: Eliminación de directorios
Desde `B`, elimine los directorios `A` y `B` simultáneamente.
![1 12](https://github.com/user-attachments/assets/dd59b8b5-e136-46fe-bab7-cfb077e572db)

---

## Soluciones sugeridas

1. ```bash
   sudo mkdir directorio
   ``` 

2. ```bash
   cd directorio
   ``` 

3. ```bash
    echo "Hola mundo" > archivo.txt
    sudo chmod 777 archivo.txt
    sudo chown tu_usuario archivo.txt
    sudo chgrp tu_usuario archivo.txt
    ```

4. ```bash
   ls -l
   ```

5. ```bash
    mkdir copia
    cp archivo.txt copia/
    ```

6. ```bash
    rm archivo.txt
    echo "Hello IDS" > copia/archivo.txt
    mv copia/archivo.txt .
    rm -r copia
    cat archivo.txt
    ```

7. ```bash
    cd ..
    tree
    ```

8. ```bash
    mkdir A B
    echo "Test" > A/test.txt
    cd B
    ```

9. ```bash
   cat ../A/test.txt
   ```

10. ```bash
    mv ../A/test.txt .
    ```

11. ```bash
    mv test.txt ../A/
    ```

12. ```bash
    rm -r ../A ../B
    ```

---
