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

| Sprint # | User Story ID | Título                       | Descripción                                                                                                                                          | Estimación (Horas) | Asignado a                        | Estado (To-do/InProcess/To-Review/Done) |
|----------|---------------|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|----------------------------------|---------------------------------------|
| Sprint 1 | HU1           | Información general del producto | Implementar la sección que proporciona información clara sobre la plataforma de optimización energética y sus beneficios.                              | 4                  | Irving Allcca Guerrero           | Done                                  |
| Sprint 1 | HU1           | Visualización de funcionalidades | Desarrollar la interfaz que muestre las funcionalidades del sistema como monitoreo de consumo, reportes y alertas.                                    | 4                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU1           | Recomendaciones para ahorrar energía | Implementar sección de recomendaciones simples sobre cómo reducir el consumo energético.                                                           | 3                  | Irving Allcca Guerrero           | Done                                  |
| Sprint 1 | HU1           | Llamada a la acción           | Crear botones destacados para registrar, iniciar sesión o solicitar más información.                                                                 | 2                  | Anderson Gonza Morales          | Done                                  |
| Sprint 1 | HU2           | Casos de éxito                | Desarrollar la sección de testimonios con casos de éxito sobre ahorro energético en hogares.                                                        | 4                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU2           | Filtrado por tipo de usuario  | Implementar la funcionalidad de filtrado para mostrar solo casos de éxito relevantes para el tipo de usuario hogar.                                  | 3                  | Juan Pastor Napa                | Done                                  |
| Sprint 1 | HU2           | Llamada a la acción           | Añadir botones destacados para registrarse o solicitar más información al final de la página de casos de éxito.                                      | 2                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU3           | Planes y precios              | Desarrollar la sección con una tabla comparativa de planes: Básico, Pro, Empresarial.                                                                | 4                  | Irving Allcca Guerrero           | Done                                  |
| Sprint 1 | HU3           | Visualización de características | Crear la visualización detallada de las características de cada plan en la tabla comparativa.                                                         | 4                  | Anderson Gonza Morales          | Done                                  |
| Sprint 1 | HU3           | Plan destacado                | Resaltar el plan más popular o recomendado visualmente en la tabla de planes.                                                                        | 2                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU3           | Selección de plan             | Implementar los botones para seleccionar un plan y redirigir al formulario de registro.                                                             | 3                  | Juan Pastor Napa                | Done                                  |
| Sprint 1 | HU3           | Responsividad                 | Asegurar que la tabla comparativa se vea correctamente en dispositivos móviles, tabletas y PC.                                                       | 3                  | Irving Allcca Guerrero           | Done                                  |
| Sprint 1 | HU4           | Cómo Funciona                 | Desarrollar la sección "Cómo funciona" con el desglose del proceso, incluyendo monitoreo de consumo y dispositivos inteligentes.                       | 4                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU4           | Explicación de las funcionalidades | Crear una explicación paso a paso sobre el uso de la plataforma: creación de perfil, conexión de dispositivos, etc.                                   | 4                  | Andy Arturo Nuñez Soto          | Done                                  |
| Sprint 1 | HU4           | Visualización de resultados   | Implementar ejemplos visuales de reportes generados, alertas y recomendaciones de optimización.                                                     | 3                  | Anderson Gonza Morales          | Done                                  |
| Sprint 1 | HU4           | Llamada a la acción           | Añadir botones de acción como "Ver planes" o "Comienza ahora".                                                                                       | 2                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU5           | Contacto                      | Implementar un formulario de contacto para que los usuarios puedan obtener más información o hacer preguntas.                                         | 4                  | Juan Pastor Napa                | Done                                  |
| Sprint 1 | HU5           | Validación de campos obligatorios | Implementar validación para asegurar que los campos obligatorios (nombre y correo electrónico) sean completados.                                      | 3                  | Irving Allcca Guerrero           | Done                                  |
| Sprint 1 | HU5           | Envío exitoso del formulario   | Crear el flujo para enviar el formulario y mostrar un mensaje de confirmación.                                                                       | 2                  | Sebastián Escobar Palomino      | Done                                  |
| Sprint 1 | HU5           | Notificación interna          | Implementar el sistema de notificación interna al equipo de soporte o ventas para dar seguimiento.                                                  | 3                  | Andy Arturo Nuñez Soto          | Done                                  |
| Sprint 1 | HU5           | Redirección a la página principal | Añadir la opción de regresar a la página principal o a la sección de "Planes" después de enviar el formulario.                                         | 2                  | Anderson Gonza Morales          | Done                                  |

#### **5.2.1.4. Development Evidence for Sprint Review**

| Repository                                                      | Branch  | Commit Id | Commit Message                                                                                                  | Commit Message Body | Committed on (Date) |
| --------------------------------------------------------------- | ------- | --------- | ---------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------- |
|1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page | develop | arturo-ns | feat: Update Footer                                                                                                | -                   | Sep 13, 2025        |
|1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page  | develop | arturo-ns | feat: Update Footer                                                                                                | -                   | Sep 13, 2025        |
| 1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page | develop | arturo-ns | feat: Update Footer                                                                                                | -                   | Sep 13, 2025        |
|1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page  | develop | arturo-ns | feat: Update Footer                                                                                                | -                   | Sep 13, 2025        |
| 1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page | develop | sebasepe  | feat(landing-page): add components for landing page                                                                | -                   | Sep 4, 2025         |
| 1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page | develop | sebasepe  | chore: remove unnecessary folders                                                                                  | -                   | Sep 4, 2025         |
| 1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page| develop | sebasepe  | chore: remove README                                                                                                | -                   | Sep 4, 2025         |
| 1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page | develop | sebasepe  | Add files via upload                                                                                              | -                   | Sep 4, 2025         |
| 1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page | develop | sebasepe  | Create README.md                                                                                                  | -                   | Aug 28, 2025        |


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
 **Pasos para realizar la Landing Page de la Plataforma de Optimización Energética:**

1. **Acceder a la sección “Información general del producto”**: 
   - Como visitante, navega hacia la sección de “Información del producto” para entender cómo la plataforma puede ayudarte a reducir el consumo energético y ahorrar en tus facturas.

2. **Mostrar funcionalidades principales de la plataforma**: 
   - Presenta de manera clara las funcionalidades clave como el monitoreo en tiempo real, reportes energéticos y alertas para optimizar el consumo energético en el hogar.

3. **Ofrecer recomendaciones de ahorro energético**: 
   - Agrega una sección con consejos prácticos para ahorrar energía, como la optimización de dispositivos y el ajuste de hábitos de consumo.

4. **Agregar testimonios y casos de éxito**: 
   - Incluye testimonios visuales de marcas e influencers que hayan tenido éxito utilizando la plataforma, como ejemplos de ahorro energético real.

5. **Destacar los planes y precios de la plataforma**: 
   - Asegúrate de que la sección de “Planes y precios” muestre de manera clara los diferentes planes disponibles (Básico, Pro y Empresarial), con información sobre características y precios.

6. **Incluir una sección de “¿Cómo funciona?”**: 
   - Desglosa de forma simple y visual cómo funciona la plataforma, incluyendo los pasos para crear una cuenta, conectar dispositivos y obtener reportes de consumo energético.

7. **Habilitar contacto directo con el equipo de soporte**: 
   - Implementa un formulario de contacto para que los usuarios puedan enviar preguntas o comentarios, conectando con el equipo de soporte de la plataforma.

8. **Verificación de funcionalidades**: 
   - Realiza pruebas para asegurarte de que todos los botones, enlaces y formularios funcionen correctamente. Verifica que la información se muestre correctamente en todos los dispositivos.

9. **Responsividad y adaptación a dispositivos móviles**: 
   - Asegúrate de que la página sea completamente responsiva y se vea correctamente tanto en PC como en dispositivos móviles (smartphones y tablets).

10. **Llamada a la acción**: 
    - Asegúrate de que las llamadas a la acción estén bien visibles en cada sección, con botones de “Registrarse”, “Ver cómo funciona” o “Ver planes”.


#### **5.2.1.7. Software Deployment Evidence for Sprint Review**
Se empleó Netlify para publicar la landing page, lo que facilitó el despliegue del sitio. A continuación, se proporciona el enlace a la landing page: [Landing Page](https://rococo-sprite-66ce8b.netlify.app/)

<div style="text-align: center;">
  <img src="https://i.imgur.com/krnAWFe.png" width="90%" />
</div>

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
9. **Figma con los User Flow Diagrams, wireframes y mockups de la landing page:** [Figma](https://www.figma.com/design/6zsotpbkoOZH0xcz69YyCU/Mock-Upc?node-id=0-1&t=svzqcosOPQg0VdcE-1)
13. **2.2.2. Registro de entrevistas:** [Entrevistas](https://www.youtube.com/watch?v=mx5nMZDKNeg)
15. **Video de exposición:**[ Video de la exposicion]()
