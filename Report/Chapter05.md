# **Capítulo V: Product Implementation, Validation & Deployment**

## **5.1. Software Configuration Management**
### **5.1.1. Software Development Environment Configuration**
# Diseño UX/UI del Producto

**Figma**: Herramienta digital utilizada para crear prototipos y diseños de interfaces. En nuestro proyecto, se empleará para desarrollar los Wireframes y el Wireflow en la página de aterrizaje, así como para el diseño tanto de la WebApp como de la MobileApp.  
Ruta referencial: [https://www.figma.com/](https://www.figma.com/)

# Desarrollo de Software

* **Visual Studio Code**: Entorno de desarrollo y compilación de código, elegido por el equipo debido a su familiaridad con la herramienta. Esta IDE es de fácil acceso, ofrece múltiples configuraciones, la opción de añadir extensiones y soporta varios lenguajes de programación.  
  Ruta referencial: [https://code.visualstudio.com/](https://code.visualstudio.com/)

* **HTML5**: Lenguaje de marcado utilizado para desarrollar el código de las etiquetas en páginas web.  
  Ruta referencial: [https://www.w3schools.com/html/html5_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)

* **CSS**: Hojas de estilo en cascada que gestionan el diseño de las páginas web, siempre en conjunto con HTML.  
  Ruta referencial: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)

* **Javascript**: Lenguaje de programación interpretado y orientado a objetos. Se usará para crear la interfaz de usuario de la aplicación.  
  Ruta referencial: [https://developer.mozilla.org/es/docs/Web/JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)

# Despliegue del Software

**Netlify**: Plataforma para la implementación y despliegue de aplicaciones web. Facilita la publicación de sitios web directamente desde el repositorio y permite integrar procesos de CI/CD.  
Ruta referencial: [https://www.netlify.com/](https://www.netlify.com/)

# Documentación del Software y Gestión del Proyecto

**Github**: Plataforma en la nube para alojar los repositorios de código del proyecto. Facilita la colaboración en tiempo real y permite revisar las contribuciones de los miembros del equipo. Accesible a través de navegadores web.  
Ruta referencial: [https://github.com/](https://github.com/)

### **5.1.2. Source Code Management**
Para el desarrollo de nuestro proyecto, adoptaremos el flujo de trabajo propuesto por el modelo GitFlow. Utilizaremos GitHub como plataforma de control de versiones. A continuación, se explicará cómo se implementará GitFlow en el repositorio, y se proporcionarán los enlaces de los repositorios de GitHub para cada componente: Landing Page, Web Services y Frontend Web Applications.

# Repositorio en GitHub

* Repositorio: [Repositorio](https://github.com/orgs/1ASI0729-2520-7344-G3-PowerSense/repositories)
* Landing Page: [Landing Page](https://rococo-sprite-66ce8b.netlify.app/)

# Flujo de trabajo GitFlow

El flujo de trabajo elegido para el desarrollo del proyecto sigue el modelo propuesto por Vincent Driessen en su artículo "A Successful Git Branching Model".

# Estructura de Ramas (Branches)

  1. **Master Branch (Rama Principal):** Esta rama está destinada a la producción de la aplicación. Todos los cambios deben ser aprobados por un miembro del equipo para asegurar que solo se integren modificaciones verificadas.
  2. **HotFix Branch:** Aquí se gestionan las correcciones de errores urgentes. Una vez que se soluciona un problema, los cambios se despliegan nuevamente en la rama principal y también se integran en la rama de desarrollo.
  3. **Develop Branch:** Esta rama es donde se integran de manera continua las nuevas características o mejoras en el proyecto.
  4. **Feature Branch:** Cada nueva funcionalidad es desarrollada en esta rama. Cuando se completa una funcionalidad, se fusiona con la rama de desarrollo para su integración.
  5. **Release Branch:** Esta rama se usa para mantener una versión estable y lista para ser liberada, basada en el código de la rama de desarrollo.

### **5.1.3. Source Code Style Guide & Conventions**
Adoptaremos buenas prácticas en el código para asegurar que sea consistente y sostenible.

**HTML:**

* Se utilizará minúsculas para nombrar etiquetas, IDs, nombres y clases.
* Se debe emplear la codificación UTF-8.
* El contenido debe redactarse en inglés.
* Cada referencia a un archivo debe incluir su extensión (.css, .js).
* Todas las etiquetas deben finalizar con `/>`.

**CSS:**

* El ancho del body debe establecerse al 100%.
* Para las imágenes, se debe definir el ancho (width) en función del elemento contenedor.
* Las etiquetas, nombres y clases deben ser asignadas según el propósito y la categoría del elemento.
* Las palabras deben separarse con un guion "-".
* El margen (margin) y el relleno (padding) de todos los elementos deben establecerse en 0.

### **5.1.4. Software Deployment Configuration**
Para llevar a cabo el despliegue de la landing page, es necesario seguir ciertos pasos específicos. Se requiere una estructura organizada y un repositorio. Una vez que se cuente con estos elementos, se podrá iniciar el proceso de despliegue de la landing page. A continuación, se detallan los pasos a seguir:

1. Conectar GitHub con Netlify
- Lo primero que hicimos fue ir a [Netlify](https://www.netlify.com/) y crear una cuenta (o iniciar sesión si ya teníamos una).
- Luego, en el panel principal, hicimos clic en **"New Site from Git"**.
- Seleccionamos **GitHub** como la opción de repositorio.
- Autoricé a Netlify para que accediera a nuestra cuenta de GitHub y buscara el repositorio donde teníamos nuestro proyecto Angular.
- Encontramos el repositorio y lo seleccionamos para conectar Netlify con él.

2. Configurar el Build en Netlify
- En la sección de **Build Settings**, configuramos lo siguiente:
  - **Branch to deploy**: Elegimos la rama `main` (que es donde teníamos el código).
  - **Build Command**: Escribimos `ng build --prod`, que es el comando de Angular para hacer el build de producción.
  - **Publish Directory**: Especificamos la carpeta `dist/mi-proyecto`, que es donde Angular coloca los archivos listos para producción después del build.

3. Desplegar el Proyecto
- Después de configurar, simplemente hicimos clic en **Deploy Site**.
- Netlify comenzó a construir y desplegar el proyecto. Este proceso tardó unos minutos.
- Cuando terminó, Netlify nos dio un enlace con el sitio desplegado.

4. Verificar el Despliegue
- Abrimos el enlace proporcionado por Netlify y verificamos que nuestra aplicación Angular estaba funcionando perfectamente en línea.
- ¡Todo se veía genial y listo para usarse!

<div style="text-align: center;">
  <img src="https://i.imgur.com/p5ypnj9.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/wx8QMdO.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/5daKrgu.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/H417XHb.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/tubB5I0.png" width="90%" />
</div>

## **5.2. Landing Page, Services & Applications Implementation**
### **5.2.1. Sprint 1**
En la siguiente sección se presentará el sprint #1, que incluye la versión inicial del proyecto, destacando la estructura, el diseño y los resultados obtenidos de la página de aterrizaje.
#### **5.2.1.1. Sprint Planning 1**
En esta sección se detallan los aspectos clave de la reunión de planificación del Sprint 1. El objetivo es garantizar que haya coherencia entre la planificación y la ejecución, alineando el Sprint Goal, las User Stories y los entregables del Sprint Backlog.

| **Sprint #** | Sprint 1 |
|---|---|
| **Sprint Planning Background** |  |
| **Date** | 2025-09-03 |
| **Time** | 10:00 PM |
| **Location** | Reunión mediante Discord |
| **Prepared By** | Sebastian Escobar |
| **Attendees (to planning meeting)** | Juan Pastor /Anderson Gonza/ Irving Allcca / Arturo Nuñez |
| **Sprint 0 Review Summary** |En este sprint se estableció la visión del proyecto, se asignaron los roles del equipo y se llevó a cabo la planificación inicial de la arquitectura y el diseño de la landing page. |
| **Sprint 0 Retrospective Summary** | El equipo reconoció la necesidad de optimizar la comunicación y la asignación de tareas, además de definir criterios claros de aceptación para los entregables. |
| **Sprint Goal & User Stories** |  |
| **Sprint 1 Goal** | Nuestro objetivo es desarrollar una solución tecnológica para optimizar el consumo energético en los hogares y pequeñas empresas de Lima Metropolitana. Para esta entrega, se elaborará la landing page para que los usuarios puedan conocer más sobre la aplicación, creando una página atractiva, clara y fácil de navegar, que resalte las funcionalidades principales, beneficios y cómo la plataforma puede ayudarles a reducir su consumo energético y costos.|
| **Sprint 1 Velocity** | 20 Story Points |
| **Sum of Story Points** | 20 |

#### **5.2.1.2. Aspect Leaders and Collaborators.**
| **Team Member (Last Name, First Name)** | **GitHub Username** | **Capítulo I: Introducción (L/C)** | **Capítulo II: Requirements Elicitation & Analysis (L/C)** | **Capítulo III: Requirements Specification (L/C)** | **Capítulo IV: Product Design (L/C)** | **Capítulo V: Product Implementation, Validation & Deployment (L/C)** |
| --------------------------------------- | ------------------- | ---------------------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------- |
| **Irving Allca**                   | noway-evitern17        | **L**                              | **C**                                                      | **C**                                              | **C**                                 | **C**                                                                 |
| **Juan Pastor Napa**          | ElKiwi1271        | **C**                              | **L**                                                      | **C**                                              | **C**                                 | **C**                                                                 |
| **Andy Arturo Nuñez Soto**          |arturo-ns           | **C**                              | **C**                                                      | **L**                                              | **C**                                 | **C**                                                                 |
| **Anderson Gonza Morales**                        | Ander-U         | **C**                              | **C**                                                      | **C**                                              | **L**                                 | **C**                                                                 |
| **Sebastian Escobar Palomino**                    | sebasepe               | **C**                              | **C**                                                      | **C**                                              | **C**                                 | **L**                                                                 |
#### **5.2.1.3. Sprint Backlog 1**
En el primer sprint, el equipo se enfocó en crear una landing page tanto atractiva como funcional, asignando las tareas mediante el tablero de Sprint según las habilidades de cada miembro.
#### **5.2.1.4. Development Evidence for Sprint Review**

#### **5.2.1.5. Execution Evidence for Sprint Review**
En el Sprint 1 se desarrollaron, diseñaron e implementaron las secciones de la landing page, donde los usuarios pueden obtener información sobre la startup y el producto que se ofrecerá. A continuación, se muestran las evidencias.

<div style="text-align: center;">
  <img src="https://i.imgur.com/D8VAjaU.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/KEk6XLo.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/g0cTqJL.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/DgkdQiF.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/bpD8zHJ.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/PAdL4Bk.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/EwpbPdB.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/JxfaWFt.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/RUGK2nz.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/qwgaMPn.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/nLC9u16.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/ljFAIBC.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/96cZc2a.png" width="90%" />
</div>

#### **5.2.1.6. Services Documentation Evidence for Sprint Review**
#### **5.2.1.7. Software Deployment Evidence for Sprint Review**
#### **5.2.1.8. Team Collaboration Insights during Sprint**
Para este proyecto se usaron herramientas como WebStorm y Git. La landing page se dividió en secciones asignadas a cada miembro del equipo, y al final, un integrante integró todas las contribuciones para consolidar el producto final

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZrAz2Ls.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZlLWjTf.png" width="90%" />
</div>

#### **Bibliografia**

#### **Anexo**
1. **Despliegue del Landing Page:** [Landing Page](https://rococo-sprite-66ce8b.netlify.app/)
2. **Link de la organización :** [Organización](https://github.com/1ASI0729-2520-7344-G3-PowerSense)
5. **Link del repositorio del Reporte :** [Repositorio Reporte](https://github.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report)
6. **Link del repositorio de la Landing Page :** [Repositorio LandingPage](https://github.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page)
9. **Figma con los User Flow Diagrams, wireframes y mockups de la landing page:** [Figma]()
13. **2.2.2. Registro de entrevistas:** [Entrevistas]()
15. **Video de exposición:**[ Video de la exposicion]()
