# Oferta Laboral

**Oferta Laboral:** Desarrollador Python Full Stack trabajando en remoto.

**Empresa:** Sip Ingeniería

### Conocimientos requeridos:

- Python y el framework Web2py. 
- HTML 
- JavaScript 
- TypeScript
- React
- CSS 
- PostgreSQL 
- Docker

**Salario:** Entre **$1,600,000** y **$4,500,000**, dependiendo de habilidades y experiencia.

**Descripción del trabajo:** Buscamos varios desarrolladores Python Full Stack apasionados y con experiencia para unirse a nuestro equipo. El candidato ideal debe tener experiencia en desarrollo web utilizando Python con el **framework web2py**, HTML, JavaScript, TypeScript, React, CSS, y manejo de bases de datos con PostgreSQL. También es crucial la experiencia con Docker.

- Trabajamos en remoto 44 horas a la semana, el horario de trabajo es: Lunes a viernes, de 8:00 am - 1:00pm, y de 2:00 pm a 6:00 pm
- Necesitas solo una conexión estable a internet y un explorador web, se recomienda tener una conexión de internet auxiliar por ejemplo en el celular en caso de que la principal tenga cortes.

###### Modalidades de Contratación
- **Fase Inicial:** Inicio con un contrato de prueba de 3 meses, permitiendo una evaluación mutua de compatibilidad y desempeño.
- **Contratación a Largo Plazo:** Según los resultados y el desempeño observado, se procederá a ofrecer un contrato de 4, 8 o 12 meses con posibilidad de extensión a término indefinido, afianzando así una relación laboral duradera y estable.

**Convocatoria a la Oferta Laboral:** Para aquellos interesados en sumarse a nuestro equipo, es requisito indispensable completar una evaluación de competencias. Esta evaluación está diseñada no solo para medir tus habilidades y conocimientos previos, sino también para brindarte una preparación integral, familiarizándote con las herramientas, frameworks y metodologías que constituyen la base de nuestro trabajo diario. Considera esta evaluación como una oportunidad de aprendizaje autónomo que te equipará con todo lo necesario para desempeñarte de manera eficaz y productiva en tu posible futuro rol dentro de nuestra empresa.

### **Prueba de Conocimiento - Proyecto:** Sistema de Gestión Escolar

El proyecto consiste en desarrollar una aplicación web para gestionar operaciones clave de una institución educativa. Esta aplicación deberá incluir los módulos:

- para el registro de estudiantes, 
- salones, materias 
- y el seguimiento de la asistencia.

#### Módulos y Requisitos Específicos:

##### Registro de Estudiantes (Python Web2py, TypeScript, Clases Repository, de Modelo, Factory, Renderer, Controller):

- Desarrollar un formulario de registro de estudiantes utilizando completamente TypeScript.   
- Implementar la validación de datos y la comunicación con el backend. Desarrollar una API que maneje las solicitudes para el registro de los estudiantes usando un controlador en web2py.
- En python: Implementa y usa las Clases Repository que permitan interactuar con cada tabla donde se requiera agregar o actualizar datos a la base de datos.
- En Typescript: Debes implementar las clases de Repository las cuales llaman al api para el registro de estudiantes, Clase de Modelo para modelar el formulario, Clase de renderer para generar el html del modelo de formulario creado, Clase Factory para crear instancias del modelo de formulario, Clase de controller para atender los eventos del formulario y ejecutar las acciones necesarias.

##### Gestión de Salones y Materias (Web2py sqlform.grid):

- Utilizar sqlform.grid para crear vistas CRUD para la administración de las tablas como: Salon, Materia. 
- Aplicar ordenamiento en las tablas por: nombre de salon, nombre de la materia.

##### Registro de Asistencia (Python Web2py, Javascript, Clases de Modelo, Factory, Singleton y Renderer):

- Crear clases de modelo separadas para Estudiante, Salón y Materia.
- Utilizar el patrón de diseño Factory para crear instancias de los modelos Estudiante, Salón y Materia.
- Aplica en patron de diseño Singleton y Cache en las clases Factory de Salon y Materia.
- Desarrollar una clase Renderer en la carpeta /renderer para el control de asistencia.
- La clase Renderer debe encargarse de generar la visualización de estos modelos utilizando objetos HTML de Web2py, asegurando que cada elemento se muestre correctamente en la interfaz.
- La visualización debe incluir listas o tablas que muestren los estudiantes, salones y materias, con la opción de marcar asistencia.
- Cada fila correspondiente a un estudiante debe incluir un control select con opciones como "Asistió" y "Ausente".
- Integrar funciones de JavaScript que se activen cuando se cambie el estado en el control select.
- Estas funciones deben estar diseñadas para hacer llamadas a una API que registre los cambios de asistencia en la base de datos
- Desarrollar una API que maneje las solicitudes para actualizar el estado de asistencia de los estudiantes.
- Esta API debe interactuar con la base de datos usando sus clases Repository para registrar los cambios efectuados desde la interfaz de usuario.

###### Gestión de Base de Datos y Migraciones (Postgres, Alembic):

- Utilizar Alembic para la creación y gestión de tablas de base de datos.
- Incluir scripts de migración para la estructura inicial, carga de datos para pruebas y cualquier cambio posterior.

###### Pruebas Unitarias y de Integración (unittest, Jest, mockups):

- Implementar tests unitarios para cada módulo o clase creada en Python.
- Implementar tests unitarios para cada módulo o clase creada en Typescript.
- Uso de mockups para simular interacciones por ejemplo: de base de datos, servicios api, etc.

###### Dockerización y Despliegue:

- Crear un Dockerfile para construir una imagen del proyecto.
- Desarrollar un archivo docker-compose para facilitar el despliegue y la ejecución del proyecto.

###### Control de Calidad de Código:

- Agrega tipado de datos en todos los argumentos y retornos de funciones python y typescript.
- Utilizar herramientas como black, flake8, pylint, bandit para Python, y ESLint para TypeScript.
- Asegurar que todo el código cumple con los estándares de calidad y seguridad establecidos.

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

- Editor de Código: Utilizar Visual Studio Code.
- Herramientas de Asistencia: Se permite el uso de GitHub Copilot y/o GPT-3/GPT-4, Gemini, Bard, entre otros.
- Uso de git para registrar los cambios durante todo el desarrollo.

###### Entrega del proyecto:

- Demostración Visual: Desarrollar y compartir un video demostrativo que ilustre de manera clara el funcionamiento de la aplicación. Este debe incluir una visión general de los tests realizados para asegurar su correcto funcionamiento. Por favor, comparte el enlace del video en una plataforma accesible.
- Compartir el Proyecto: Publicar el proyecto completo en GitHub, incluyendo el código fuente, la documentación pertinente y las instrucciones detalladas para su ejecución. Esto facilitará la revisión y evaluación de tu trabajo.
- Criterios de Evaluación: Se valorará especialmente la calidad del código, el cumplimiento efectivo de los requerimientos establecidos y la creatividad demostrada en la solución de problemas.

El propósito de esta evaluación es apreciar tus competencias en el desarrollo Full Stack, utilizando Python y TypeScript. Se valorará especialmente la habilidad para integrar una variedad de tecnologías en un solo proyecto cohesivo, así como la capacidad de adaptación y aprendizaje de nuevas herramientas, tales como web2py y Docker, demostrando versatilidad y proactividad en el manejo de nuevos desafíos tecnológicos.
