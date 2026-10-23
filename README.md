
# Sitio Web de Presentación Profesional

##  Objetivo del Proyecto
Desarrollar y desplegar un sitio web de presentación profesional interactivo y de alta fidelidad, aplicando buenas prácticas de estructuración frontend y empaquetándolo en un contenedor mediante Nginx para garantizar su portabilidad y correcta ejecución.

##  Tecnologías Utilizadas
* **HTML5**: Estructuración semántica y contenido del sitio web.
* **CSS Externo**: Diseño visual, estilos y adaptabilidad del diseño basado en el mockup de alta fidelidad.
* **Nginx**: Servidor web de alto rendimiento utilizado para servir los archivos estáticos dentro del contenedor Docker.
* **Docker**: Plataforma de contenedorización para empaquetar la aplicación y sus dependencias.
* **Docker Hub**: Repositorio en la nube para la distribución y almacenamiento de la imagen Docker.

##  Estructura del Proyecto
```text
.
├── index.html          # Página principal del sitio web
├── css/
│   └── styles.css      # Hoja de estilos externa
├── assets/             # Recursos gráficos, iconos e imágenes
├── Dockerfile          # Configuración para la creación de la imagen Docker
└── README.md           # Documentación del proyecto
```
## Instrucciones para Construir y Subir a Docker Hub
Sigue los siguientes pasos para compilar la imagen localmente y publicarla en tu cuenta de Docker Hub:


Debes de tener cuenta de Docker


1. Construir la imagen de Docker (debe tener el nombre del usuario seguido de una /):

docker build -t tu-usuario/nombre-de-la-imagen .


2. Loguear la cuenta del Docker para poder enviar al Docker Hub


docker login

Puede pedirte el usuario y clave si no estas logueado antes


3. Subir la imagen al repositorio remoto:

docker push tu-usuario/sitio-profesional


## Enlace a Docker Hub
Puedes acceder a la imagen del proyecto publicada en Docker Hub mediante el siguiente enlace:

https://hub.docker.com/r/lacalderon7/perfil-profesional-luis-calderon

Para descargar la imagen usa este comando:

docker pull lacalderon7/perfil-profesional-luis-calderon

## Enlace al Mockup
Puedes ingresar al Mockup mediante el siguiente enlace:

https://share.gemini.google/lSo6WRKKgBOb 
