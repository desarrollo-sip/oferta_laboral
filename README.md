# Oferta Laboral

**Oferta Laboral:** Desarrollador Python Full Stack

**Empresa:** Sip Ingeniería

### Conocimientos requeridos:

- Python y el framework Web2py. 
- HTML 
- JavaScript 
- TypeScript
- React
-  CSS 
- PostgreSQL 
- Docker

**Salario:** Entre **$2,500,000** y **$4,500,000**, dependiendo de habilidades y experiencia.

**Descripción del trabajo:** Buscamos un desarrollador Python Full Stack apasionado y con experiencia para unirse a nuestro equipo. El candidato ideal debe tener experiencia en desarrollo web utilizando Python con el framework web2py, HTML, JavaScript, TypeScript, React, CSS, y manejo de bases de datos con PostgreSQL. También es crucial la experiencia con Docker.

**Aplicación a la Oferta:** Para aplicar, los interesados deben primero completar la prueba de conocimiento y después aplicar a la oferta.

### **Prueba de Conocimiento - Proyecto:** Sistema de Gestión Escolar

El proyecto consiste en desarrollar una aplicación web para gestionar operaciones clave de una institución educativa. Esta aplicación deberá incluir los módulos:

- para el registro de estudiantes, 
- salones, materias 
- y el seguimiento de la asistencia.

#### Módulos y Requisitos Específicos:

##### Registro de Estudiantes (Python, TypeScript, Clases Repository, de Modelo, Factory, Renderer, Controller):

Desarrollar un formulario de registro de estudiantes utilizando completamente TypeScript.   
Implementar la validación de datos y la comunicación con el backend. Desarrollar una API que maneje las solicitudes para el registro de los estudiantes usando un controlador en web2py. En python: Implementa y usa las Clases Repository que permitan interactuar con cada tabla donde se requiera agregar o actualizar datos a la base de datos. En Typescript: Debes implementar las clases de Repository las cuales llaman al api para el registro de estudiantes, Clase de Modelo para modelar el formulario, Clase de renderer para generar el html del modelo de formulario creado, Clase Factory para crear instancias del modelo de formulario, Clase de controller para atender los eventos del formulario y ejecutar las acciones necesarias.

##### Gestión de Salones y Materias (sqlform.grid):

Utilizar sqlform.grid para crear vistas CRUD para la administración de las tablas como: Salon, Materia.

##### Registro de Asistencia (Python, Javascript, Clases de Modelo, Factory, Singleton y Renderer):


Crear clases de modelo separadas para Estudiante, Salón y Materia.
Utilizar el patrón de diseño Factory para crear instancias de los modelos Estudiante, Salón y Materia.
Aplica en patron de diseño Singleton y Cache en las clases Factory de Salon y Materia.
Desarrollar una clase Renderer en la carpeta /renderer para el control de asistencia.
La clase Renderer debe encargarse de generar la visualización de estos modelos utilizando objetos HTML de Web2py, asegurando que cada elemento se muestre correctamente en la interfaz.
La visualización debe incluir listas o tablas que muestren los estudiantes, salones y materias, con la opción de marcar asistencia.
Cada fila correspondiente a un estudiante debe incluir un control select con opciones como "Asistió" y "Ausente".
Integrar funciones de JavaScript que se activen cuando se cambie el estado en el control select.
Estas funciones deben estar diseñadas para hacer llamadas a una API que registre los cambios de asistencia en la base de datos
Desarrollar una API que maneje las solicitudes para actualizar el estado de asistencia de los estudiantes.
Esta API debe interactuar con la base de datos usando sus clases Repository para registrar los cambios efectuados desde la interfaz de usuario.

###### Gestión de Base de Datos y Migraciones (Postgres, Alembic):

Utilizar Alembic para la creación y gestión de tablas de base de datos. Incluir scripts de migración para la estructura inicial, carga de datos para pruebas y cualquier cambio posterior.

###### Pruebas Unitarias y de Integración (unittest, Jest, mockups):

Implementar tests unitarios para cada módulo o clase creada en Python. Implementar tests unitarios para cada módulo o clase creada en Typescript. Uso de mockups para simular interacciones por ejemplo: de base de datos, servicios api, etc.

###### Dockerización y Despliegue:

Crear un Dockerfile para construir una imagen del proyecto. Desarrollar un archivo docker-compose para facilitar el despliegue y la ejecución del proyecto.

###### Control de Calidad de Código:

Agrega tipado de datos en todos los agumentos y retornos de funciones python y typescript.
Utilizar herramientas como black, flake8, pylint, bandit para Python, y ESLint para TypeScript. Asegurar que todo el código cumple con los estándares de calidad y seguridad establecidos.

###### Documentación:

Agregar archivo README.md. El Código, los comentarios y docstrings deben estar en inglés y seguir las convenciones de Python y Typescript.

###### Estructura del proyecto:

Para python dentro de una aplicación web2py:

```

controllers
cron
...
modules/
modules/factory
modules/libs
modules/models
modules/processes
modules/renderer
modules/repository
modules/services/api_services
modules/services/business_logic
modules/system
modules/templates
modules/utils
...
```

Para typescript dentro de una aplicación web2py, lo mismo pero reemplazar "modules" por "src".

###### Otros:

Editor de Código: Utilizar Visual Studio Code.
Herramientas de Asistencia: Se permite el uso de GitHub Copilot y/o GPT-3/GPT-4.
Uso de git para registrar los cambios durante todo el desarrollo.

###### Entrega del proyecto:


Crear un video demostrativo del funcionamiento de la aplicación, incluyendo los tests, y compartir el link.
Subir el proyecto completo a GitHub, con código fuente, documentación e instrucciones de ejecución.
Se evaluará la calidad del código, cumplimiento de requerimientos y creatividad en la resolución de problemas. 

El objetivo es valorar habilidades en desarrollo Full Stack con Python y TypeScript, y la integración de diversas tecnologías en un proyecto unificado.
