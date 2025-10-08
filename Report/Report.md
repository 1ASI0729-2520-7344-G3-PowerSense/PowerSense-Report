
## <p align="center">Informe de Trabajo Final</p>

<p align="center">Universidad Peruana de Ciencias Aplicadas, Ingeniería de Software, 5to Ciclo</p>

<div align="center">
  <img src="https://i.imgur.com/37GXtIL.png" alt="Logo de UPC" />
</div>

<p align="center">Desarrollo de Aplicaciones Open Source - 1ASI0729</p>
<p align="center">Sección: 7344</p>
<p align="center"><strong>Nombre del profesor: Ivan Robles Fernández</strong></p>
<p align="center"><strong>Nombre del startup:</strong> SODA </p>
<p align="center"><strong>Nombre del producto:</strong> Powersense<p>
<p align="center"><strong>Team members:</strong></p>

<div align="center">

|            Nombre             |    Código    |
|:-----------------------------:|:------------:|
| Allcca Guerrero, Irving       | U202213241   |
| Escobar Palomino, Sebastian   | U202125968   |
| Gonza Morales, Anderson       | U202120836   |
| Nuñez Soto, Andy Arturo       | U999999999   |
| Pastor Napa, Juan             | U202217288   |

</div>

<p align="center">Septiembre - 2025</p>

# Registro de versiones del informe
| Versión | Fecha      | Autor             | Descripción de modificación                                                                                                                                                                                                                                                                                       |
| ------- | ---------- | ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TB1    | 19/09/2025 | Powersense | En esta primera entrega se han incluido los capítulos:<br>• **Capítulo I:** Introducción<br>• **Capítulo II:** Requirements Elicitation & Analysis<br>• **Capítulo III:** Requirements Specification<br>• **Capítulo IV:** Product Design<br>• **Capítulo V:** Product Implementation, Validation & Deployment |
# Project Report Collaboration Insights
Enlace al repositorio para el informe del proyecto (Github): [PowerSense](hhttps://github.com/orgs/1ASI0729-2520-7344-G3-PowerSense/repositories)

## TB1 
Los contenidos se asignaron en formato Markdown, utilizando "Conventional Commits" para registrar el progreso. Se subieron recursos e imágenes a la carpeta "assets" de cada rama, y se realizaron reuniones para coordinar el avance del Sprint 1, centrado en el desarrollo de la Landing Page.

<div style="text-align: center;">
  <img src="https://i.imgur.com/c6GkfYx.png" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/WvbQ6sF.png" width="100%" />
</div>

# Contenido
## Tabla de contenidos
- [**Project Report Collaboration Insights**](#project-report-collaboration-insights)
- [**Contenido**](#contenido)
  - [**Tabla de contenidos**](#tabla-de-contenidos)
- [**Student Outcome**](#student-outcome)
- [**Capítulo I: Introducción**](#capítulo-i-introducción)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [**1.2.1. Antecedentes y problemática**](#121-antecedentes-y-problemática)
  - [**1.2.2. Lean UX Process**](#122-lean-ux-process)
    - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
    - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
    - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
      - [**Hypothesis Statement 01**](#hypothesis-statement-01)
      - [**Hypothesis Statement 02**](#hypothesis-statement-02)
      - [**Hypothesis Statement 03**](#hypothesis-statement-03)
      - [**Hypothesis Statement 04**](#hypothesis-statement-04)
      - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivos**](#13-segmentos-objetivos)
- [**Capítulo II: Requirements Elicitation \& Analysis**](#capítulo-ii-requirements-elicitation--analysis)
  - [**2.1. Competidores**](#21-competidores)
  - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
  - [**Diseño de entrevista – Primer segmento objetivo: Empresas**](#diseño-de-entrevista--primer-segmento-objetivo-empresas)
  - [**Diseño de entrevista – Segundo segmento objetivo: Influencers**](#diseño-de-entrevista--segundo-segmento-objetivo-influencers)
    - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
  - [**Entrevista para el Segmento Objetivo 1 - Empresas :**](#entrevista-para-el-segmento-objetivo-1---empresas-)
  - [**Entrevista para el Segmento Objetivo 2 - Influencer:**](#entrevista-para-el-segmento-objetivo-2---influencer)
    - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding**](#23-needfinding)
    - [**2.3.1. User Personas**](#231-user-personas)
    - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
  - [**Perfil 1: Trabaja en una startup o agencia**](#perfil-1-trabaja-en-una-startup-o-agencia)
  - [**Perfil 2: Creador de contenido independiente**](#perfil-2-creador-de-contenido-independiente)
    - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
    - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
  - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
- [**Capítulo III: Requirements Specification**](#capítulo-iii-requirements-specification)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
    - [**Epic 1: Búsqueda y Selección de Influencers**](#epic-1-búsqueda-y-selección-de-influencers)
    - [**Epic 2: Dashboard Personalizado y Reputación**](#epic-2-dashboard-personalizado-y-reputación)
    - [**Epic 3: Visualización de Perfiles de Usuario**](#epic-3-visualización-de-perfiles-de-usuario)
    - [**Epic 4: Landing page**](#epic-4-landing-page)
    - [**Epic 5: Autenticación**](#epic-5-autenticación)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
  - [**4.1. Style Guidelines**](#41-style-guidelines)
    - [**4.1.1. General Style Guidelines**](#411-general-style-guidelines)
    - [**4.1.2. Web Style Guidelines**](#412-web-style-guidelines)
      - [**Imágenes**](#imágenes)
      - [**Botones**](#botones)
  - [**4.2. Information Architecture**](#42-information-architecture)
    - [**4.2.1. Organization Systems**](#421-organization-systems)
    - [**4.2.2. Labeling Systems**](#422-labeling-systems)
    - [**4.2.3. SEO Tags and Meta Tags**](#423-seo-tags-and-meta-tags)
    - [**4.2.4. Searching Systems**](#424-searching-systems)
    - [**4.2.5. Navigation Systems**](#425-navigation-systems)
  - [**4.3. Landing Page UI Design**](#43-landing-page-ui-design)
    - [**4.3.1. Landing Page Wireframe**](#431-landing-page-wireframe)
    - [**4.3.2. Landing Page Mock-up**](#432-landing-page-mock-up)
  - [**4.4. Diseño UX/UI de Aplicaciones Web**](#44-diseño-uxui-de-aplicaciones-web)
    - [**4.4.1. Wireframes de Aplicaciones Web**](#441-wireframes-de-aplicaciones-web)
    - [**4.4.2. Web Applications Wireflow Diagrams**](#442-web-applications-wireflow-diagrams)
  - [**4.4. Diseño UX/UI de Aplicaciones Web**](#44-diseño-uxui-de-aplicaciones-web-1)
    - [**4.4.1. Mockups de Aplicaciones Web**](#441-mockups-de-aplicaciones-web)
    - [**4.4.4. Web Applications User Flow Diagrams**](#444-web-applications-user-flow-diagrams)
  - [**4.5. Web Applications Prototyping**](#45-web-applications-prototyping)
  - [**4.6. Domain-Driven Software Architecture**](#46-domain-driven-software-architecture)
    - [**4.6.1. Software Architecture Context Diagram**](#461-software-architecture-context-diagram)
    - [**4.6.2. Software Architecture Container Diagrams**](#462-software-architecture-container-diagrams)
    - [**4.6.3. Software Architecture Components Diagram**](#463-software-architecture-components-diagrams)
  - [**4.7. Software Object-Oriented Design**](#47-software-object-oriented-design)
    - [**4.7.1. Class Diagrams**](#471-class-diagrams)
    - [**4.7.2. Class Dictionary**](#472-class-dictionary)
  - [**4.8. Database Design**](#48-database-design)
    - [**4.8.1. Database Diagra**](#481-database-diagram)
- [**Capítulo V: Product Implementation, Validation \& Deployment**](#capítulo-v-product-implementation-validation--deployment)
  - [**5.1. Software Configuration Management**](#51-software-configuration-management)
    - [**5.1.1. Software Development Environment Configuration**](#511-software-development-environment-configuration)
    - [**5.1.2. Source Code Management**](#512-source-code-management)
    - [**5.1.3. Source Code Style Guide \& Conventions**](#513-source-code-style-guide--conventions)
    - [**5.1.4. Software Deployment Configuration**](#514-software-deployment-configuration)
  - [**5.2. Landing Page, Services \& Applications Implementation**](#52-landing-page-services--applications-implementation)
    - [**5.2.1. Sprint 1**](#521-sprint-1)
      - [**5.2.1.1. Sprint Planning 1**](#5211-sprint-planning-1)
      - [**5.2.1.2. Aspect Leaders and Collaborators.**](#5212-aspect-leaders-and-collaborators)
      - [**5.2.1.3. Sprint Backlog 1**](#5213-sprint-backlog-1)
      - [**5.2.1.4. Development Evidence for Sprint Review**](#5214-development-evidence-for-sprint-review)
      - [**5.2.1.5. Execution Evidence for Sprint Review**](#5215-execution-evidence-for-sprint-review)
      - [**5.2.1.6. Services Documentation Evidence for Sprint Review**](#5216-services-documentation-evidence-for-sprint-review)
      - [**5.2.1.7. Software Deployment Evidence for Sprint Review**](#5217-software-deployment-evidence-for-sprint-review)
      - [**5.2.1.8. Team Collaboration Insights during Sprint**](#5218-team-collaboration-insights-during-sprint)
    - [**5.2.2. Sprint 2**]()
      - [**5.2.2.1. Sprint Planning 2**]()
      - [**5.2.2.2. Aspect Leaders and Collaborators.**]()
      - [**5.2.2.3. Sprint Backlog 2**]()
      - [**5.2.2.4. Development Evidence for Sprint Review**]()
      - [**5.2.2.5. Execution Evidence for Sprint Review**]()
      - [**5.2.2.6. Services Documentation Evidence for Sprint Review**]()
      - [**5.2.2.7. Software Deployment Evidence for Sprint Review**]()
      - [**5.2.2.8. Team Collaboration Insights during Sprint**]()
      - [**Conclusiones**](#conclusiones)
      - [**Bibliografia**](#bibliografia)
      - [**Anexo**](#anexo)
## Student Outcome

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Nuestra startup nace en el Perú con el propósito de ofrecer una solución tecnológica que ayude a los hogares y pequeñas empresas a reducir su consumo energético y su huella de carbono. A través de un sistema basado en Internet de las Cosas (IoT), integramos sensores inteligentes y actuadores que permiten monitorear en tiempo real el gasto de energía y controlar de forma remota los dispositivos eléctricos. La plataforma incorpora funciones de Inteligencia Artificial (IA) que analizan los patrones de uso, detectan ineficiencias y brindan recomendaciones prácticas para optimizar el consumo, fomentando así un estilo de vida más sostenible y consciente con el medio ambiente.

Nuestra visión es convertirnos en un referente en toda Sudamérica en el desarrollo de soluciones de eficiencia energética inteligente, contribuyendo a la transformación de las ciudades en espacios más sostenibles y resilientes. Nuestra misión es empoderar a los usuarios, ofreciéndoles herramientas accesibles y fáciles de usar que les permitan visualizar su consumo en tiempo real, programar el encendido y apagado de dispositivos, y adoptar hábitos responsables que reduzcan costos y emisiones. De esta manera, buscamos impactar positivamente en la economía de los hogares, el crecimiento empresarial y la preservación del entorno natural, ampliando nuestro alcance desde el Perú hacia la región.

**Logotipo del servicio** 
<div style="text-align: center;">
  <img src="https://i.imgur.com/u79m2Ce.jpeg"  width="70%" />
</div>

### 1.1.2. Perfiles de integrantes del equipo

|  **Allcca Guerrero, Irving** | Foto |
|------------------------------------------|-------------------------------|
| **Ingeniería de Software – U20213241**<br><br>**Habilidades:** Soy estudiante de Ingeniería de Software cursando el 5to ciclo de mi carrera en la UPC y tengo 20 años. Soy una persona empática e intuitiva. Me gusta desarrollar los proyectos de manera secuencial y eficiente. En equipo, me esfuerzo por colaborar. Tengo experiencia en programación con C ++, c#, Python, así como en el diseño web con html, CSS y JavaScript. |![Foto_Irving](https://imgur.com/ZDr5MfF.png)|
|  **Andy Arturo Nuñez Soto** | Foto |
| **Ingeniería de Software – U20231E795**<br><br>**Habilidades:** Mi nombre es Andy Arturo Nuñez Soto, Actualmente curso el quinto ciclo de la carrera de Ingeniería de Software. Soy una persona creativa y comprometida, lo que me permite enfrentar desafíos con determinación y encontrar soluciones efectivas. Voy a aportar mis habilidades al proyecto con el objetivo de alcanzar resultados exitosos. | ![Foto_Arturo](https://i.imgur.com/umVtyUB.png)|
|  **Juan Carlos Pastor Napa** | Foto |
| **Ingeniería de Software – u202217288**<br><br>**Habilidades:** Mi nombre es Juan Carlos Pastor Napa, tengo 20 años y actualmente estudio ingeniería de software en la UPC, poseo conocimientos en Python y c ++, experiencia con Hardware como tecnico, así como experiencia a servicio en una empresa y varios trabajos de la misma naturaleza, soy apasionado por el deporte, la naturaleza y por el software.  |![Foto_Juan](https://i.imgur.com/M2mvNZD.png)|
|  **Sebastian Matias Escobar Palomino** | Foto |
| **Ingeniería de Software – u202125968**<br><br>**Habilidades:** Mi nombre es Sebastián Matías Escobar Palomino, soy estudiante de Ingeniería de Software. Mi objetivo es contribuir de manera activa al trabajo en equipo, cumplir con los plazos establecidos y mantener una comunicación fluida y clara con mis compañeros, aplicando mis conocimientos para cumplir con las responsabilidades asignadas en el proyecto.  |![Foto_Sebastian](https://i.imgur.com/tqL3DCm.png)|
|  **Anderson Gonza Morales** | Foto |
| **Ingeniería de Software – u202120836**<br><br>**Habilidades:** Actualmente soy estudiante de Ingeniería de Software. Soy muy curioso, empatico y creativo. Tengo conocimientos en python, un poco de java y base de datos.  |![Foto_Anderson](https://i.imgur.com/gGQHZBG.jpeg)|


## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

En el Perú, y especialmente en Lima Metropolitana, los hogares muestran un consumo energético elevado que supera el promedio nacional. Según un informe reciente, el consumo promedio mensual en una vivienda limeña alcanza los 172 kWh, mientras que a nivel nacional apenas bordea los 93 kWh (Autosolar, 2025). Esta diferencia refleja no solo un mayor gasto en las facturas familiares, sino también una presión creciente sobre el sistema eléctrico nacional. La concentración urbana de Lima, junto con el uso intensivo de aparatos eléctricos y la falta de prácticas de eficiencia, ha convertido a la capital en un punto crítico de sobreconsumo energético.

A este panorama se suma el hecho de que el país aún enfrenta grandes retos en su transición energética. Pese al potencial de fuentes renovables, no existen planes claros ni progresos consistentes para impulsar un cambio hacia un modelo más sostenible (Mongabay Latam, 2024). Esto significa que el alto consumo eléctrico en los hogares limeños no solo impacta la economía familiar, sino que además incrementa la huella de carbono y retrasa la modernización del sistema energético nacional. Frente a esta situación, resulta urgente diseñar soluciones accesibles y tecnológicamente viables que permitan a los usuarios monitorear y optimizar su consumo, reduciendo tanto sus costos como su impacto ambiental.

#### Problemática

Who (¿Quién?)

Los principales actores afectados son los hogares de Lima Metropolitana y las pequeñas y medianas empresas (PYMEs). Ambos segmentos enfrentan altos costos de electricidad debido a un consumo por encima del promedio nacional. En los hogares, esto se traduce en un impacto directo en la economía familiar; en las PYMEs, en una disminución de la rentabilidad operativa, ya que los gastos fijos en energía se convierten en un obstáculo para su crecimiento.

What (¿Qué?)

El problema central radica en el excesivo consumo de energía eléctrica sin mecanismos eficientes de monitoreo ni control. Actualmente, la mayoría de usuarios paga mensualmente por la energía utilizada sin conocer en detalle qué dispositivos consumen más, cuándo se generan picos de consumo, ni cómo reducirlos. Esto genera derroche de recursos y una huella ambiental innecesariamente elevada.

Where (¿Dónde?)

El epicentro de este problema es Lima Metropolitana, donde el consumo energético promedio mensual en un hogar alcanza los 172 kWh, superando ampliamente el promedio nacional de 93 kWh (Autosolar, 2025). Esta diferencia convierte a Lima en un caso crítico, donde se concentra gran parte de la demanda energética residencial del país, y por lo tanto, en el lugar ideal para implementar soluciones de optimización.

When (¿Cuándo?)

La urgencia de atender este problema se enmarca en el contexto actual. Según Mongabay Latam (2024), el Perú carece de planes claros y avances consistentes en su transición energética hacia fuentes renovables. En consecuencia, los altos niveles de consumo en los hogares limeños no solo elevan las facturas eléctricas, sino que también retrasan los esfuerzos nacionales de sostenibilidad. Esto convierte al momento presente en una ventana crítica para implementar soluciones innovadoras que ayuden a cerrar la brecha.

Why (¿Por qué?)

La causa del problema es doble: por un lado, económica, ya que el consumo excesivo genera gastos adicionales considerables en electricidad para familias y negocios; por otro, ambiental, debido a que gran parte de la electricidad en Perú proviene de fuentes no renovables, lo que incrementa la emisión de gases de efecto invernadero. Resolver este problema no solo alivia la carga financiera de los usuarios, sino que también contribuye a reducir la huella de carbono y a fomentar una cultura de eficiencia energética.

How (¿Cómo?)

La solución se plantea mediante la implementación de una plataforma de Internet de las Cosas (IoT) “Verde”, que integre sensores y actuadores inteligentes para monitorear y controlar en tiempo real el consumo energético. El sistema incorporaría algoritmos de Inteligencia Artificial (IA) capaces de identificar patrones de uso, detectar ineficiencias y emitir recomendaciones prácticas al usuario, como apagar dispositivos en horarios de baja ocupación o programar encendidos automáticos. Así, se habilitaría un control remoto, programable y optimizado del consumo eléctrico.

How Much (¿Cuánto?)

En términos monetarios, el sobreconsumo energético en Lima es significativo. Los 79 kWh adicionales que consume un hogar limeño al mes respecto al promedio nacional equivalen a un gasto de aproximadamente S/ 49,77 adicionales mensuales, es decir, cerca de S/ 600 al año, considerando un costo promedio de S/ 0,63 por kWh en tarifa residencial (OSINERGMIN, 2025). Este monto representa un ahorro potencial tangible que la plataforma IoT podría ofrecer a los usuarios al optimizar su consumo.


### 1.2.2. Lean UX Process

Para asegurar que nuestra solución tecnológica responda a necesidades reales y no a simples suposiciones, aplicamos el Lean UX Process. Esta metodología nos permite entender el problema, reconocer lo que asumimos como cierto y      transformarlo en hipótesis comprobables. Con ello buscamos alinear el desarrollo de nuestro software con los objetivos de los usuarios y con la visión de sostenibilidad que guía nuestra startup.

#### 1.2.2.1. Lean UX Problem Statements

Nuestro proyecto se encuentra en el dominio de la eficiencia energética y las tecnologías IoT.
Los segmentos de clientes principales son los hogares limeños y las pequeñas y medianas empresas (PYMEs) que enfrentan un consumo eléctrico elevado y poco controlado.
El dolor (pain point) que encontramos es que estos usuarios pagan facturas elevadas sin contar con información clara sobre qué dispositivos consumen más ni cómo reducir su gasto.
La brecha (gap) está en la falta de herramientas accesibles en el mercado local que permitan monitorear el consumo en tiempo real y ofrecer recomendaciones prácticas.
Nuestra visión y estrategia es acercar una solución IoT “verde” y sencilla de usar, que combine sensores inteligentes, control remoto de dispositivos y recomendaciones automáticas.

#### 1.2.2.2. Lean UX Assumptions

Al iniciar este proyecto, reconocemos varias suposiciones que debemos validar:

. Creemos que los usuarios limeños valoran poder visualizar en tiempo real su consumo eléctrico.

. Suponemos que estarán dispuestos a invertir en dispositivos IoT accesibles si estos les generan ahorros tangibles en sus facturas.

. Asumimos que las PYMEs priorizan la reducción de costos energéticos como parte de su sostenibilidad operativa.

. Creemos que los usuarios prefieren una aplicación simple y fácil de usar, por encima de una plataforma con demasiadas funciones complejas.

Estas suposiciones nos ayudan a guiar el diseño inicial, pero solo se confirmarán a través de pruebas con usuarios y despliegues piloto.

#### 1.2.2.3. Lean UX Hypothesis Statements

A partir de nuestras suposiciones, formulamos hipótesis comprobables que guiarán los experimentos y pruebas:

Creemos que los hogares limeños reducirán su consumo mensual en un 10% si utilizan un sistema de monitoreo en tiempo real. Sabremos que esto es cierto cuando al menos el 70% de los usuarios piloto reporten un ahorro en sus facturas después de tres meses de uso.

Creemos que las PYMEs usarán regularmente los reportes de consumo si el sistema incluye recomendaciones automáticas de ahorro. Sabremos que esto es cierto cuando al menos el 50% de las empresas piloto consulten el dashboard semanalmente.

Creemos que los usuarios residenciales interactuarán de forma constante con la plataforma si se incluyen funcionalidades simples como encendido/apagado remoto y programación de horarios. Sabremos que esto es cierto cuando más del 60% de los usuarios activos usen estas funciones al menos una vez por semana.

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas nos permite sintetizar en un solo marco los elementos clave de nuestro proyecto. A través de esta herramienta identificamos el problema central, los usuarios a quienes está dirigida la solución, los beneficios que esperan, así como las suposiciones e hipótesis que guiarán la validación de nuestro producto.

![Foto_leanUXcanvas](https://imgur.com/ooqIITR.png)

## 1.3. Segmentos objetivo

### Hogares limeños con recibo de luz

En Lima Metropolitana, casi la totalidad de hogares cuenta con acceso a electricidad (97.6%), lo que los convierte en un segmento consolidado que paga recibo de luz regularmente (INEI, 2021). El jefe de hogar suele ser adulto de mediana edad (~50 años), con un nivel educativo mayor al promedio nacional: cerca del 49% de la población de 18 a 64 años alcanzó educación superior (INEI, 2022). La estructura socioeconómica limeña muestra predominio de la clase media (NSE C: 48% de los hogares), mientras que los hogares promedian 3.5 miembros (APEIM, 2022). En cuanto al consumo energético, Lima registra una mediana de 190 kWh/mes, casi el doble del promedio nacional, lo que se traduce en recibos entre S/60 y S/120 mensuales, dependiendo del equipamiento eléctrico del hogar (Osinergmin, 2023).

### PYMEs limeñas

Lima concentra cerca del 42% de todas las empresas del país, es decir, alrededor de 1.4 millones de unidades económicas, de las cuales más del 99% son micro y pequeñas (SUNAT, 2024). Estas empresas emplean en promedio de 2 a 3 trabajadores y se concentran principalmente en comercio minorista (45%) y servicios (42%), siendo menos frecuente la manufactura (9%) (INEI, 2022). El consumo eléctrico representa un costo fijo relevante: un pequeño negocio limeño puede gastar entre 200 y 300 kWh/mes, lo que equivale a recibos de S/150 a S/250. Estos costos impactan directamente en la rentabilidad, ya que las tarifas comerciales (BT5) no reciben subsidio, lo que hace más crítica la gestión eficiente de la energía en este segmento (Osinergmin, 2023).
# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

A continuación se presenta una tabla con los competidores más relevantes en Perú para la propuesta _IoS_ (IoT + Software/IA para monitoreo y optimización del consumo eléctrico). El campo `logo_url` queda en blanco para que pegues el enlace de la imagen correspondiente.
| id | nombre | descripcion | caracteristicas | canal_distribucion | logo_url |  
|---:|--------|-------------|-----------------|--------------------|----------|  
| 1 | Smelpro | Soluciones IoT e Inteligencia Artificial para Industria 4.0. Aplicaciones energéticas: monitoreo en tiempo real, detección de fallas, mantenimiento predictivo y optimización de costos operativos. Sectores: energía, agua, minería, manufactura, logística. | - Monitoreo en tiempo real del consumo eléctrico<br>- Detección de fallas y mantenimiento predictivo con IA<br>- Optimización de costos operativos<br>- Soporte para LoRaWAN, Sigfox y redes celulares; dashboards personalizados | - Ventas B2B directas<br>- Integradores y proyectos llave en mano | ![](https://media.licdn.com/dms/image/v2/D4E0BAQEE408hz04ogQ/company-logo_200_200/company-logo_200_200/0/1707159503649/smelpro_logo?e=2147483647&v=beta&t=A1pA5y-dyGfbO1CuZyANrh2e1NJTgr3bE7_aVm2YyqY) |  
| 2 | LoraTech | Empresa líder en soluciones IoT con tecnología LoRaWAN para monitoreo energético. Aplicaciones eléctricas: redes de sensores para consumo eléctrico en tiempo real, control remoto de cargas, alertas y reportes para optimización. Ventajas: bajo consumo, alta penetración en interiores y seguridad de datos. Sectores: industria, agroindustria, edificios inteligentes. | - Redes de sensores LoRaWAN para consumo en tiempo real<br>- Control remoto de cargas y automatización<br>- Alertas y reportes de consumo y anomalías<br>- Dispositivos de bajo consumo y larga autonomía | - Ventas B2B y partners integradores<br>- Proyectos llave‑en‑mano y proveedores de gateways/servicios de red | ![](https://media.licdn.com/dms/image/v2/C4E0BAQGkwW0mBTLwow/company-logo_200_200/company-logo_200_200/0/1649220243203/loratech_latam_logo?e=2147483647&v=beta&t=0U4NE8EbMbBMejS4uPCyBF58EkctrZYjj3phCiwJOT8) |  
| 3 | Teca Perú | Soluciones “llave‑en‑mano” en telemetría y telecontrol con fuerte uso de LoRaWAN. Aplicaciones energéticas: medición en tiempo real de servicios (agua, energía, gas) y despliegues industriales. Casos: edificios inteligentes, minería, agricultura, piscicultura. | - Telemetría y telecontrol llave‑en‑mano<br>- Redes LoRaWAN privadas y gateways<br>- Medición en tiempo real y dashboards industriales<br>- Integración con sistemas SCADA/ERP | - Ventas B2B directas<br>- Integradores de proyectos y contratos con empresas/municipios | ![](https://teca.pe/web/image/website/1/logo/Teca%20%7C%20Soluciones%20IoT?unique=cbd5366) |  


---

## 2.1.2. Estrategias y tácticas frente a competidores
<table class="tg"> <thead> <tr> <th class="tg-0pky" colspan="6">Competitive Analysis Landscape</th> </tr> </thead> <tbody> <tr> <td class="tg-0pky" colspan="6"><strong>Propósito del análisis:</strong> Evaluar la posición de PowerSense frente a tres competidores clave del ecosistema IoT/energía (Smelpro, LoraTech y Teca Perú) para identificar ventajas competitivas, riesgos y tácticas prioritarias que permitan ganar cuota en hogares urbanos y PYMEs.</td> </tr> <tr> <td class="tg-0pky" colspan="6"><strong>Pregunta guía:</strong> ¿Cómo se compara PowerSense en oferta, producto, mercado y potencial estratégico frente a Smelpro, LoraTech y Teca Perú, y qué acciones tácticas deben priorizarse para diferenciarse y crecer?</td> </tr> <tr> <td class="tg-0pky" colspan="2"></td> <td class="tg-0lax">PowerSense (objetivo)</td> <td class="tg-0pky">Smelpro</td> <td class="tg-0pky">LoraTech</td> <td class="tg-0pky">Teca Perú</td> </tr> <!-- Perfil - Overview / Ventaja Competitiva --> <tr> <td class="tg-0pky" rowspan="2">Perfil</td> <td class="tg-0pky">Overview</td> <td class="tg-0lax"><em>Plataforma IoT + IA</em> orientada a hogares y PYMEs: kits plug‑and‑play por circuito, app móvil/panel web, analítica que traduce consumo a ahorro en S/; modelo freemium + suscripción.</td> <td class="tg-0pky"><em>Proveedor de soluciones industriales</em> IoT/IA centrado en monitoreo, mantenimiento predictivo y optimización operativa en entornos críticos.</td> <td class="tg-0pky"><em>Proveedor e integrador LoRaWAN</em> especializado en despliegues de red, sensores y gestión para sensorización masiva y baja potencia.</td> <td class="tg-0pky"><em>Integrador local</em> de telemetría y telecontrol que entrega proyectos llave‑en‑mano, con experiencia en integración SCADA/ERP y contratos sectoriales.</td> </tr> <tr> <td class="tg-0pky">Ventaja Competitiva ¿Qué valor ofrece a los clientes?</td> <td class="tg-0lax">Ahorro económico claro (S/), IA explicable que sugiere acciones prácticas y UX sencilla para usuarios no técnicos; rápida adopción mediante freemium.</td> <td class="tg-0pky">Analítica avanzada y experiencia en entornos industriales críticos; soluciones robustas para uptime y eficiencia operativa.</td> <td class="tg-0pky">Cobertura LoRaWAN, eficiencia en consumo energético de sensores y escalabilidad para despliegues masivos.</td> <td class="tg-0pky">Entrega integral: hardware, instalación, integración y operación; conocimiento del mercado local y normativas.</td> </tr> <!-- Perfil de marketing --> <tr> <td class="tg-0pky" rowspan="2">Perfil de marketing</td> <td class="tg-0pky">Mercado objetivo</td> <td class="tg-0lax">Hogares urbanos (nivel medio‑alto) y pequeñas/medianas empresas (PYMEs) que buscan reducir su recibo eléctrico y mejorar eficiencia sin complejidad técnica.</td> <td class="tg-0pky">Grandes industrias: minería, manufactura, plantas con requerimientos críticos.</td> <td class="tg-0pky">Operadores de red, edificios inteligentes, agricultura, municipalidades y empresas que requieren sensorización masiva.</td> <td class="tg-0pky">Empresas locales, municipalidades y proyectos sectoriales (energía, agua, minería) que requieren soluciones integradas.</td> </tr> <tr> <td class="tg-0pky">Estrategias de marketing</td> <td class="tg-0lax">Marketing digital orientado a ahorro (casos en S/), pilotos locales, partnerships con instaladores y campañas de conversión freemium→pago.</td> <td class="tg-0pky">Relaciones B2B, participación en ferias industriales, estudios de caso técnicos y ventas consultivas.</td> <td class="tg-0pky">Alianzas con operadores LoRaWAN, demostraciones de cobertura y campañas sectoriales (agro, smart cities).</td> <td class="tg-0pky">Licitaciones, relaciones comerciales locales, propuestas llave‑en‑mano y presencia en contratos públicos/privados.</td> </tr> <!-- Perfil de producto --> <tr> <td class="tg-0pky" rowspan="3">Perfil de producto</td> <td class="tg-0pky">Productos o servicios</td> <td class="tg-0lax">Kits de medición por circuito (pinzas/medidores), gateway Wi‑Fi/LoRa, app móvil/panel web, analítica IA, reportes de ahorro y alertas.</td> <td class="tg-0pky">Sensores industriales, gateways, plataforma analítica, mantenimiento predictivo y servicios de integración a sistemas de control.</td> <td class="tg-0pky">Gateways LoRaWAN, nodos/sensores, gestión de red, integraciones y servicios gestionados para despliegues.</td> <td class="tg-0pky">Sensores, gateways, integración SCADA/ERP, servicios de instalación, puesta en marcha y operación.</td> </tr> <tr> <td class="tg-0pky">Precios y costos</td> <td class="tg-0lax">Estimado: hardware S/200–S/600 por kit; suscripción S/9–S/49/mes según plan. Instalación opcional con cargo único.</td> <td class="tg-0pky">Modelos de proyecto: contratos de alto valor (decenas de miles S/); soporte/servicios bajo contrato anual.</td> <td class="tg-0pky">Venta de hardware + tarifas por gestión/servicio; precio variable según escala y cobertura.</td> <td class="tg-0pky">Precios por proyecto (CAPEX) y contratos de servicio; altos montos según alcance e integración requerida.</td> </tr> <tr> <td class="tg-0pky">Canales de distribución (web y/o móvil)</td> <td class="tg-0lax">E‑commerce para kits, app móvil y web para servicio; red de instaladores certificados y partnerships B2B.</td> <td class="tg-0pky">Ventas B2B directas, integradores, licitaciones y servicios profesionales.</td> <td class="tg-0pky">Partners/operadores LoRaWAN, integradores y distribuidores; portales B2B para gestión de red.</td> <td class="tg-0pky">Ventas B2B, integradores locales, canales de licitación pública y contratos corporativos.</td> </tr> <!-- Análisis SWOT --> <tr> <td class="tg-0pky" rowspan="4">Análisis SWOT</td> <td class="tg-0pky">Fortalezas</td> <td class="tg-0lax">- Enfoque en usuario final y PYMEs<br>- IA explicable con métricas en S/<br>- Modelo freemium que facilita adopción rápida</td> <td class="tg-0pky">- Analítica y capacidades probadas en entornos críticos<br>- Credibilidad en industria<br>- Soluciones robustas y escalables</td> <td class="tg-0pky">- Experiencia y know‑how en LoRaWAN<br>- Bajo consumo y buena penetración para sensores<br>- Capacidad de despliegue masivo</td> <td class="tg-0pky">- Capacidad de entrega integral (instalación + integración)<br>- Conocimiento del mercado local y normativas<br>- Relaciones con clientes públicos/privados</td> </tr> <tr> <td class="tg-0pky">Debilidades</td> <td class="tg-0lax">- Marca nueva: menor confianza inicial<br>- Recursos limitados frente a incumbentes<br>- Dependencia inicial de partners para instalación/soporte</td> <td class="tg-0pky">- Enfoque industrial puede limitar atractivo para consumidores residenciales<br>- Costos y complejidad altos</td> <td class="tg-0pky">- Depende de cobertura y planificación de red<br>- No siempre óptimo para soluciones plug‑and‑play residenciales</td> <td class="tg-0pky">- Ciclos de venta largos<br>- Dependencia en contratos/licitaciones que generan variabilidad</td> </tr> <tr> <td class="tg-0pky">Oportunidades</td> <td class="tg-0lax">- Creciente preocupación por ahorro energético doméstico<br>- Alianzas con instaladores, municipalidades y utilities<br>- Pilotos que prueben ROI local en S/</td> <td class="tg-0pky">- Digitalización industrial y demanda de mantenimiento predictivo</td> <td class="tg-0pky">- Expansión de redes LoRaWAN gestionadas y demanda de sensorización masiva</td> <td class="tg-0pky">- Proyectos públicos/privados en modernización y telemetría regional</td> </tr> <tr> <td class="tg-0pky">Amenazas</td> <td class="tg-0lax">- Entrada de ESCOs o utilities con ofertas financiadas<br>- Competidores con soluciones ya integradas en PYMEs<br>- Cambios regulatorios que afecten despliegues</td> <td class="tg-0pky">- Competencia con soluciones más accesibles para PYMEs/residenciales<br>- Proveedores globales con mayor escala</td> <td class="tg-0pky">- Proveedores que usan Wi‑Fi o redes celulares para mercados residenciales<br>- Competencia de integradores locales</td> <td class="tg-0pky">- Presión de precio en licitaciones y entrada de integradores internacionales</td> </tr> </tbody> </table>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Para evaluar el atractivo y la practicidad de el servicio y producto PowerSense , estamos realizando entrevistas para entender a fondo lo que nuestros futuros usuarios necesitan, cómo se comportan y qué esperan.


## Diseño de entrevista – Primer segmento objetivo: 

¿En qué momentos del día suele usar más electricidad?

¿Qué dispositivos eléctricos son indispensables en su hogar y por qué?

¿Ha sentido que paga más luz de lo que debería? ¿Cómo lo percibe?

¿Suele comparar el monto de su recibo actual con el de meses anteriores? ¿Qué observa en esas comparaciones?

¿En su hogar suelen hablar o discutir sobre el gasto en electricidad?

¿Ha tenido que limitar el uso de algún aparato eléctrico por el costo de la electricidad?

¿Qué estrategias usa actualmente para intentar reducir el gasto en electricidad?

¿Cómo se informa (si es que lo hace) sobre su consumo eléctrico?

¿Qué impacto tiene el gasto en electricidad dentro del presupuesto familiar?

## Diseño de entrevista – Segundo segmento objetivo: 

¿Cuál es su nombre y cargo dentro de la empresa?

¿Cómo se llama su negocio y a qué rubro se dedica (ej. comercio, gastronomía, servicios, manufactura, etc.)?

¿En qué distrito o zona se encuentra ubicada su empresa?

¿Cuántos años tiene funcionando su negocio?

¿Cuál es el horario de funcionamiento habitual de su negocio?

¿En qué meses del año siente que gasta más electricidad? ¿Por qué cree que ocurre eso?

¿Qué equipos o procesos consumen más energía en su operación diaria?

¿Qué equipos, maquinarias o procesos son más indispensables para su negocio?

¿Qué equipos cree que consumen más energía?

¿Han tenido fallas en los equipos o servicios debido a picos de consumo eléctrico?

¿Qué estrategias o medidas ha probado para reducir el gasto en electricidad?

¿Cómo afecta el pago de la electricidad en su rentabilidad mensual o anual?

¿Considera que sus clientes valoran si su empresa adopta prácticas sostenibles?

¿Qué impacto tendría en su negocio poder optimizar los recursos energéticos sin sacrificar productividad?

### 2.2.2. Registro de entrevistas

[![YouTube video player](https://img.youtube.com/vi/mx5nMZDKNeg/0.jpg)](https://www.youtube.com/watch?v=mx5nMZDKNeg)

 ___-Segmento Objetivo 1___

__Entrevista 1 (Cameron Bustamante)__
Inicio: 00:00 -
Fin: 02:37 -
Duración: 2:37

+ Nombre: Cameron Bustamente
+ Edad: 22 años
+ Distrito de residencia: Surco

**Resumen de Entrevista :**
A partir de la entrevista realizada al usuario Cameron Bustamante, de 22 años y residente de Surco, se identificó que el entrevistado describe su rutina diaria y cómo ésta se refleja en el consumo eléctrico del hogar. Indica que por las mañanas utiliza la cocina y la terma y por las noches enciende la televisión y varios dispositivos electrónicos, generando picos marcados en esos horarios. Señala que la nevera permanece siempre encendida y constituye un consumo base, pero que la boleta ha aumentado con el tiempo sin una explicación aparente; comenta que no ha incorporado nuevos electrodomésticos ni cambiado hábitos de forma relevante. Manifiesta frustración por la falta de desagregación en la factura y por no poder identificar qué aparatos o qué franjas horarias generan los picos. Expone que sus medidas de ahorro son básicas (desenchufar equipos en desuso, duchas más cortas) y reconoce no conocer el impacto real de estas acciones en el monto final. Finaliza expresando interés en una solución que muestre consumo por toma y envíe alertas ante picos inusuales para recuperar control y tranquilidad.

__Entrevista 2 (Paolo Padilla)__
Inicio: 02:38 -
Fin: 06:23 -
Duración: 3:45

+ Nombre: Paolo Padilla Oliveira
+ Edad: 20 años
+ Distrito de residencia: Surquillo

**Resumen de Entrevista :**
A partir de la entrevista realizada al usuario Paolo Padilla Oliveira, de 20 años y residente de Surquillo, se identificó que vive en una vivienda compartida donde la convivencia complica la relación con la factura eléctrica. Relata que varias personas usan el mismo medidor y que surgen discusiones sobre cómo repartir el costo, porque no existe una medición individualizada. Indica que su jornada de trabajo y estudio desde casa concentra el uso de dispositivos en las tardes y noches, lo que coincide con los picos de consumo observados. Muestra desconfianza hacia la boleta por su falta de detalle y preferencia por soluciones económicas y fáciles de instalar que permitan atribuir consumo por toma o por usuario y así facilitar acuerdos internos.

__Entrevista 3 (Sebastián Valdivia)__
Inicio: 06:34 -
Fin: 10:10 -
Duración: 3:36

+ Nombre: Sebastián Valdivia
+ Edad: 22 años
+ Distrito de residencia: Miraflores

**Resumen de Entrevista :**
A partir de la entrevista realizada al usuario Sebastián Valdivia, de 22 años y residente de Miraflores, se identificó que percibe un consumo base constante por electrodomésticos esenciales y observa picos y variaciones mensuales en la factura que no logra vincular con cambios en su rutina. Reconoce falta de formación técnica para interpretar lecturas y conceptos presentes en la boleta, por lo que sus intentos de ahorro son a veces inconsistentes y sin métricas que confirmen impacto. Valora herramientas que permitan visualizar consumo por hora y por dispositivo para priorizar cambios y justificar medidas ante otros miembros del hogar.

___-Segmento Objetivo 2___

__Entrevista 4 (Juan Carlos Urdanivia Abad — Premium Cultural Institute)__
Inicio: 10:13 -
Fin: 16:18 -
Duración: 6:05

+ Nombre: Juan Carlos Urdanivia Abad
+ Edad: 55 años
+ Distrito de residencia: Surco
+ Sector: Enseñanza

**Resumen de Entrevista :**
A partir de la entrevista realizada al usuario Juan Carlos Urdanivia Abad, de 55 años y residente de Surco, se identificó que desde la perspectiva institucional los equipos de climatización y los sistemas audiovisuales generan picos significativos, especialmente durante actividades y temporadas altas. Indica que las vitrinas o equipos que requieren funcionamiento continuo representan la carga base más relevante y que la falta de datos en tiempo real impide identificar con precisión horarios o procesos causantes de incrementos en la factura. Manifiesta interés en monitoreo por circuito, reportes estacionales y en justificar inversiones en eficiencia ante la dirección, pero también subraya la necesidad de garantizar continuidad de servicio y comodidad en el espacio educativo.

__Entrevista 5 (Franco Matías Tico Flores — Minimarket Paco)__
Inicio: 16:23 -
Fin: 20:29 -
Duración: 4:06


+ Nombre: Sebastián Valdivia
+ Edad: 20 años
+ Distrito de residencia: Surco
+ Sector: Tienda de conveniencia.

**Resumen de Entrevista :**
A partir de la entrevista realizada al usuario Franco Matías Tico Flores, de 20 años y residente de Surco, se identificó que el entrevistado, representante del minimarket, atribuye la mayor parte del consumo a equipos de refrigeración y señala picos en días de mayor afluencia. Comenta que no cuentan con métricas en tiempo real para relacionar ventas y consumo y que les preocupa proteger inventario perecible. Muestra interés en soluciones con monitoreo continuo, alarmas por desviaciones y opciones de control remoto de cargas no críticas, aunque destaca la necesidad de que la inversión tenga un retorno claro.

__Entrevista 6 (Tomas Dextre Sanchez — Beeschurguer Hamburguesa)__
Inicio: 20:33 -
Fin: 24:31 -
Duración: 3:58
+ Nombre: Tomas Tobias Teodoro Dextre Sanchez
+ Edad: 22 años
+ Distrito de residencia: Surco
+ Sector: Comida rapida.

**Resumen de Entrevista :**
A partir de la entrevista realizada al usuario Tomas Tobias Teodoro Dextre Sanchez, de 22 años y residente de Surco, se identificó que el entrevistado, vinculado a un negocio de comida rápida, señala que la principal carga proviene de equipos de frío y de cocina y que existen picos en días de mayor demanda. Expresa que carecen de datos granulares y métricas en tiempo real para relacionar ventas, horarios y consumo, y que valorarían una solución con monitoreo continuo, alarmas tempranas y capacidad para gestionar cargas no críticas en momentos de tensión. Recalca que cualquier inversión debe estar alineada a un retorno razonable y que la protección del inventario es prioritaria.

Link de las Entrevistas : [ENTREVISTAS](https://www.youtube.com/watch?v=mx5nMZDKNeg)

### 2.2.3. Análisis de entrevistas

**Segmento 01 (hogares y usuarios domésticos) :** Observamos que los entrevistados reportan incrementos periódicos en el gasto energético sin que se identifique una causa clara y verificable que explique dichas variaciones. Los datos que reciben, como la boleta y las lecturas del medidor, no son suficientemente detallados ni intuitivos para relacionarlos con el uso real de los equipos, lo que genera desconfianza y sensación de opacidad. Además, existe escasa formación en gestión energética: muchos participantes reconocen no tener conocimientos técnicos para interpretar consumos eléctricos ni para evaluar estrategias de ahorro más sofisticadas. Las medidas que aplican suelen ser reactivas y de bajo impacto.

Por ejemplo, desenchufar equipos o reducir tiempos de ducha y carecen de herramientas que permitan medir su efecto a mediano o largo plazo. En viviendas compartidas aparece un problema recurrente en la distribución del costo: la ausencia de mediciones por toma o por usuario provoca incertidumbre y conflictos al momento de repartir la boleta.

**Segmento 02 (negocios e instituciones) :** Los entrevistados reconocen que el consumo es elevado y que existen picos asociados a equipos concretos, como refrigeradores y aires acondicionados, pero coinciden en que no siempre es posible identificar con precisión qué operación o qué horario provoca los incrementos en la factura. La información disponible no facilita la toma de decisiones operativas porque falta métricas en tiempo real y reportes que permitan optimizar horarios y equipos. 

Aunque hay interés en implementar medidas de eficiencia o generación propia, la principal barrera es el costo inicial y la necesidad de justificar retornos financieros claros, lo que impide muchas veces la adopción. La prioridad de estos negocios es garantizar la continuidad operativa: en rubros con equipos críticos (congeladores, vitrinas, equipos de ventilacion), la posibilidad de aplicar medidas agresivas de reducción de carga queda limitada por el riesgo de pérdidas, por lo que requieren soluciones que les permitan monitorear y proteger esos activos. Las prácticas actuales de gestión energética son en general manuales y poco automatizadas, lo que reduce la capacidad de respuesta eficiente ante variaciones de demanda.
## 2.3. Needfinding
### 2.3.1. User Personas
-Segmento 1: Hogares

![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/User_persona-Maria-seg1.png)

-Segmento 2: Negocios

![User persona Julio - Segmento 2](https://github.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/blob/feature/chapter02/img/User_persona_Julio_seg2.png?raw=true)


### 2.3.2. User Task Matrix

  __Segmento 1: Hogares__ 
| Tarea principal                                                     | Frecuencia | Importancia |
|---------------------------------------------------------------------|------------|-------------|
| Instalar el kit PowerSense de forma rápida y segura (sin obras)     | Una vez    | Alta        |
| Conectar la app y ver consumo por circuito en S/ y tiempo real      | Frecuente  | Alta        |
| Recibir alertas de picos/anomalías y entender qué hacer             | Frecuente  | Alta        |
| Seguir recomendaciones simples para ahorrar (horarios/hábitos)      | Frecuente  | Alta        |
| Ver el “ahorro logrado” y el estimado de ROI                        | Frecuente  | Alta        |

---

 __Segmento 2: PYME__ 

| Tarea principal                                                             | Frecuencia | Importancia |
|-----------------------------------------------------------------------------|------------|-------------|
| Desplegar PowerSense fuera de horario sin parar operación                   | Una vez    | Alta        |
| Monitorear circuitos/equipos críticos en tiempo real (en S/ por hora)       | Frecuente  | Alta        |
| Recibir alertas operativas (frío, compresor, picos) y actuar                 | Frecuente  | Alta        |
| Programar/automatizar cargas no críticas fuera de punta                     | Frecuente  | Alta        |
| Revisar reporte mensual con ahorro y payback para socios                    | Frecuente  | Alta        |

---
### 2.3.3. User Journey Mapping

Journey Map - Segmento 1 (Hogares):

![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/Seg1_journeymap.png)

Journey Map - Segmento 2 (Negocios):

![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/Seg2_journeymap.png)


### 2.3.4. Empathy Mapping

Empathy Map - Segmento 1 (Hogares)
![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/seg1_empathy_mapping.png)


Empathy Map - Segmento 2 (Negocios)
![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/seg2_empathy_mapping.png)

### 2.3.5. As-is Scenario Mapping

As-Is Scneario Map - Segmento 1:
![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/Seg1_AsIs_scenariomap.png)

As-Is Scneario Map - Segmento 2:
![](https://raw.githubusercontent.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report/refs/heads/feature/chapter02/img/Seg2_AsIs_scenariomap.png)

## 2.4. Ubiquitous Language

En esta sección se presentara un glosario de términos y conceptos utilizados en el dominio de negocio de PowerSense.

| Término (Inglés) | Definición breve |  
|---|---|  
| **Cuenta (Account)** | Identidad del usuario en PowerSense: acceso, estado y datos básicos. |  
| **Usuario (User)** | Persona con cuenta; puede ser cliente o trabajador. |  
| **Cliente (Customer)** | Usuario que contrata servicios o compra productos. |  
| **Trabajador Técnico (Worker)** | Profesional que ofrece servicios a través de la plataforma. |  
| **Experiencia (Experience)** | Historial laboral o de proyectos que muestra la trayectoria del trabajador. |  
| **Reseña (Review)** | Evaluación y calificación dejada por un cliente tras un servicio. |  
| **Propuesta (Proposal)** | Oferta formal del trabajador que especifica alcance, tiempo y costo. |  
| **Chat / Mensaje (Chat / Message)** | Canal y unidad de comunicación entre cliente y trabajador. |  
| **Orden de Servicio (Service Order)** | Documento que detalla el trabajo a realizar: dirección, fecha, materiales y estado. |  
| **Orden de Pago / Pago (Sales Order / Payment)** | Registro del cobro por un servicio; incluye monto y estado (pendiente/pagado). |  
| **Reclamo / Ticket (Ticket)** | Registro de un problema o disputa que requiere atención y resolución. |  
| **Tarifa por Hora (Hourly Rate)** | Precio que cobra el trabajador por hora de trabajo. |  
| **Campo de Especialidad (Field)** | Área técnica en la que se especializa el trabajador (ej. paneles solares, eficiencia). |  
| **Habilidades (Skills)** | Competencias relevantes del trabajador (ej. diagnóstico de consumo). |  
| **Disponibilidad (Availability)** | Horarios en que el trabajador puede agendar servicios. |  
| **Presupuesto (Quote)** | Estimación del costo ofrecida al cliente; puede convertirse en una orden de servicio. |  
| **Factura (Invoice)** | Documento fiscal final que detalla el servicio y el monto a pagar. |  
| **Depósito en garantía (Escrow)** | Mecanismo opcional que retiene el pago hasta la confirmación del servicio. |  
| **SLA** | Compromisos de tiempo y calidad (ej. tiempo de respuesta). |  
| **Telemetría (Telemetry)** | Datos medidos por dispositivos (consumo, voltaje) usados para análisis. |  
| **Desagregación (Disaggregation)** | Separar el consumo total en partes por circuito o aparato, para identificar usos y ahorrar. |  
| **Freemium** | Modelo: funciones básicas gratis, funciones avanzadas por suscripción. |  
| **Suscripción (Subscription)** | Pago recurrente para acceso a funciones premium y soporte. |  
| **Prueba (Trial)** | Periodo gratuito para evaluar funciones premium. |  
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
### Segmento 1: Hogares y Consumidores Individuales
![Diagrama To-Be Segmento 1](https://i.imgur.com/6Q58946.png[/img])
### Segmento 2: Pequeñas y Medianas Empresas (PYMEs)
![Diagrama To-Be Segmento 2](https://i.imgur.com/z1WVtbs.png[/img])
## 3.2. User Stories
### Epic 1 – Landing Page
| #HU  | HU ID | Tipo Usuario    | Nombre HU               | Descripción                                                                                                                                                   | Criterios de Aceptación    |
|------|-------|-----------------|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HU1 | HU1  | Visitante Hogar | Información general del producto | Como visitante interesado en reducir el consumo energético en mi hogar, quiero acceder a información clara sobre la plataforma de optimización energética para entender cómo me beneficia y cómo puede ayudarme a ahorrar en mis facturas. | **Scenario 1: Acceso a información pública**<br>Dado que el visitante ingresa a la página web de la plataforma de optimización energética<br>Cuando selecciona la sección “Información del producto”<br>Entonces el sistema muestra una descripción general de la plataforma, sus objetivos (ahorro de energía y optimización de consumo) y los beneficios principales como monitoreo en tiempo real y dispositivos inteligentes.<br><br>**Scenario 2: Visualización de funcionalidades**<br>Dado que el visitante se encuentra en la sección “Información del producto”<br>Cuando navega por la interfaz<br>Entonces el sistema presenta de manera clara las funcionalidades, como el monitoreo de consumo, los reportes de energía y las alertas para optimizar el uso de energía en el hogar.<br><br>**Scenario 3: Recomendaciones para ahorrar energía**<br>Dado que el visitante revisa la información sobre el producto<br>Cuando llega a la sección de consejos o recomendaciones de ahorro energético<br>Entonces el sistema muestra sugerencias simples, como la optimización del uso de dispositivos y consejos para reducir el consumo sin necesidad de personalización.<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante explora la información general<br>Cuando visualiza botones o enlaces destacados como “Ver cómo funciona” o “Ver planes”<br>Entonces el sistema muestra opciones para registrarse, iniciar sesión o solicitar más información sobre los planes y servicios de optimización energética. |
| HU2 | HU2  | Visitante Hogar | Casos de éxito            | Como visitante, quiero consultar casos de éxito reales sobre ahorro energético en hogares para confiar en la efectividad de la solución antes de registrarme. | **Scenario 1: Acceso público**<br>Dado que el visitante ingresa a la plataforma sin necesidad de estar registrado<br>Cuando selecciona la sección “Casos de éxito”<br>Entonces el sistema muestra una lista de testimonios e implementaciones exitosas en hogares.<br><br>**Scenario 2: Visualización detallada**<br>Dado que el visitante se encuentra en la lista de casos de éxito<br>Cuando selecciona un caso específico<br>Entonces el sistema muestra información detallada sobre el consumo energético antes y después de utilizar la plataforma, así como los resultados obtenidos, como reducción de costos y optimización de consumo.<br><br>**Scenario 3: Filtrado por tipo de usuario**<br>Dado que el visitante accede a la sección de casos de éxito<br>Cuando utiliza el filtro “Hogar”<br>Entonces el sistema muestra únicamente los casos correspondientes a usuarios de tipo hogar.<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante ha revisado uno o más casos de éxito<br>Cuando llega al final de la página<br>Entonces el sistema muestra un botón destacado para registrarse o solicitar más información sobre la plataforma. |
| HU3 | HU3  | Visitante Hogar | Planes y precios           | Como visitante interesado en optimizar el consumo energético de mi hogar, quiero visualizar los planes y precios para elegir la opción que se ajuste a mis necesidades. | **Scenario 1: Acceso a la sección de planes**<br>Dado que el visitante se encuentra en la página principal<br>Cuando selecciona la opción “Planes y precios” en el menú de navegación<br>Entonces el sistema muestra una tabla comparativa con los diferentes planes disponibles: Básico (Gratis), Pro ($29/mes), y Empresarial ($79/mes).<br><br>**Scenario 2: Visualización de características**<br>Dado que el visitante accede a la tabla de planes<br>Cuando revisa la comparativa<br>Entonces el sistema muestra de manera clara las características de cada plan, como el monitoreo básico de consumo, análisis avanzado de consumo, y soporte prioritario.<br><br>**Scenario 3: Plan destacado**<br>Dado que la plataforma ofrece un plan recomendado<br>Cuando el visitante observa la comparativa<br>Entonces el sistema resalta visualmente el plan más popular o recomendado (Ejemplo: con un borde o etiqueta “Más Popular”).<br><br>**Scenario 4: Selección de plan**<br>Dado que el visitante identifica un plan de su interés<br>Cuando hace clic en el botón “Seleccionar” o “Más información” dentro de dicho plan<br>Entonces el sistema redirige al formulario de registro, demo gratuita o pago según corresponda.<br><br>**Scenario 5: Responsividad**<br>Dado que el visitante accede desde distintos dispositivos (PC, tablet o móvil)<br>Cuando visualiza la tabla comparativa<br>Entonces el sistema adapta el diseño para que la información sea clara y fácil de leer en cualquier dispositivo. |
| HU4 | HU4  | Visitante Hogar | Cómo Funciona               | Como visitante interesado en optimizar el consumo energético en mi hogar, quiero entender cómo funciona la plataforma para asegurarme de que es una solución efectiva para reducir mis costos de energía. | **Scenario 1: Acceso a la sección “Cómo funciona”**<br>Dado que el visitante ingresa a la página web<br>Cuando selecciona la opción “Cómo funciona” en el menú de navegación<br>Entonces el sistema muestra un desglose claro de cómo funciona la plataforma, incluyendo el monitoreo de consumo en tiempo real, los dispositivos inteligentes integrados y el análisis avanzado de consumo.<br><br>**Scenario 2: Explicación de las funcionalidades**<br>Dado que el visitante está en la sección “Cómo funciona”<br>Cuando lee la información presentada<br>Entonces el sistema describe paso a paso el proceso: creación de perfil, conexión de dispositivos inteligentes, monitoreo en tiempo real y generación de reportes de consumo energético.<br><br>**Scenario 3: Visualización de resultados**<br>Dado que el visitante ha revisado la explicación del proceso<br>Cuando navega por la interfaz<br>Entonces el sistema muestra ejemplos visuales de los reportes generados, alertas de consumo elevado y recomendaciones de optimización.<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante entiende cómo funciona el sistema<br>Cuando visualiza botones de acción como “Ver planes” o “Comienza ahora”<br>Entonces el sistema ofrece opciones para registrarse, iniciar sesión o solicitar más información sobre cómo empezar a utilizar la plataforma. |
| HU5 | HU5  | Visitante Hogar | Contacto                   | Como visitante, quiero poder acceder a un formulario de contacto para obtener más información o realizar preguntas sobre la plataforma de optimización energética. | **Scenario 1: Acceso al formulario de contacto**<br>Dado que el visitante se encuentra en la página principal<br>Cuando selecciona la opción “Contacto” en el menú de navegación<br>Entonces el sistema muestra un formulario con los campos: nombre, correo electrónico, mensaje y un botón para enviar.<br><br>**Scenario 2: Validación de campos obligatorios**<br>Dado que el visitante está en el formulario de contacto<br>Cuando intenta enviarlo sin completar los campos obligatorios (nombre y correo electrónico)<br>Entonces el sistema muestra un mensaje de error indicando los campos que deben completarse.<br><br>**Scenario 3: Envío exitoso del formulario**<br>Dado que el visitante ha completado correctamente el formulario<br>Cuando hace clic en el botón “Enviar”<br>Entonces el sistema muestra un mensaje de confirmación que indica “Tu solicitud fue enviada con éxito, pronto nos pondremos en contacto contigo”.<br><br>**Scenario 4: Notificación interna**<br>Dado que un visitante ha completado y enviado el formulario de contacto<br>Cuando el sistema procesa la solicitud<br>Entonces la plataforma envía una notificación interna al equipo de soporte o ventas con los datos registrados para dar seguimiento.<br><br>**Scenario 5: Redirección a la página principal**<br>Dado que el visitante ha enviado el formulario de contacto<br>Cuando se muestra el mensaje de confirmación<br>Entonces el sistema ofrece la opción de volver a la página principal o a la sección de "Planes" para explorar más sobre la plataforma. |
| HU6 | HU6  | Visitante Hogar | Sobre Nosotros     | Como visitante, quiero saber más sobre el equipo detrás de la plataforma y sobre el producto para comprender mejor la misión, visión y las ventajas que ofrece la solución. | **Scenario 1: Acceso a la sección "Sobre Nosotros"**<br>Dado que el visitante ingresa a la página web<br>Cuando selecciona la opción “Sobre Nosotros” en el menú de navegación<br>Entonces el sistema muestra una introducción sobre la plataforma, su misión, visión y objetivos.<br><br>**Scenario 2: Información sobre el equipo**<br>Dado que el visitante está en la sección "Sobre Nosotros"<br>Cuando selecciona el apartado “Nuestro equipo”<br>Entonces el sistema muestra una breve descripción de los miembros clave del equipo, sus roles y experiencia.<br><br>**Scenario 3: Información sobre el producto**<br>Dado que el visitante está en la sección "Sobre Nosotros"<br>Cuando selecciona el apartado “Sobre el producto”<br>Entonces el sistema proporciona detalles sobre las características, beneficios y diferenciadores del producto (optimización energética, reducción de costos, monitoreo inteligente, etc.).<br><br>**Scenario 4: Llamada a la acción**<br>Dado que el visitante ha revisado la información sobre el equipo y el producto<br>Cuando llega al final de la sección<br>Entonces el sistema muestra opciones para registrarse, obtener más información o navegar a las secciones de "Planes" y "Cómo Funciona". |
### Epic 2 – Gestión de Usuarios
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU7 | HU7 | Hogar | Registro de cuenta | Como usuario de hogar, quiero registrarme en la plataforma para comenzar a gestionar mi consumo energético. | **Scenario 1: Registro exitoso**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha completado los campos obligatorios (nombre, correo electrónico válido y contraseña que cumple con los requisitos)<br>Cuando el visitante hace clic en el botón “Registrar”<br>Entonces el sistema crea la nueva cuenta en la base de datos<br>Y redirige al visitante a la página de inicio de sesión mostrando el mensaje “Registro exitoso, por favor inicie sesión”.<br><br>**Scenario 2: Correo electrónico ya registrado**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha completado los campos con un correo electrónico ya existente en la base de datos<br>Cuando el visitante hace clic en el botón “Registrar”<br>Entonces el sistema muestra un mensaje de error: “El correo ya está registrado, por favor intente con otro o inicie sesión”.<br><br>**Scenario 3: Contraseña no cumple requisitos**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha ingresado una contraseña con menos de 8 caracteres o sin los requisitos mínimos<br>Cuando intenta hacer clic en el botón “Registrar”<br>Entonces el sistema muestra el mensaje de validación: “La contraseña debe tener al menos 8 caracteres, incluir mayúsculas, minúsculas y un número”.<br><br>**Scenario 4: Campos obligatorios vacíos**<br>Dado que el visitante se encuentra en la página de “Registro”<br>Y ha dejado uno o más campos obligatorios en blanco<br>Cuando intenta hacer clic en el botón “Registrar”<br>Entonces el sistema resalta los campos vacíos en rojo<br>Y muestra el mensaje: “Complete todos los campos obligatorios para continuar”.<br><br>**Scenario 5: Error técnico inesperado**<br>Dado que el visitante ha completado todos los campos de forma válida<br>Y el sistema presenta un fallo en la comunicación con el servidor<br>Cuando el visitante hace clic en “Registrar”<br>Entonces el sistema muestra un mensaje de error: “Ha ocurrido un problema, por favor intente más tarde”<br>Y registra el error en los logs del backend. |
| HU8 | HU8 | PYME | Registro empresarial | Como administrador de PYME, quiero registrar mi empresa en la plataforma para gestionar el consumo energético de mis instalaciones. | **Scenario 1: Registro exitoso de empresa**<br>Dado que el administrador se encuentra en la página de “Registro empresarial”<br>Y ha completado los campos obligatorios (nombre de la empresa, RUC/NIF, correo corporativo y contraseña válida)<br>Cuando hace clic en el botón “Registrar empresa”<br>Entonces el sistema crea el perfil de la empresa en la base de datos<br>Y muestra el mensaje: “Registro exitoso, por favor inicie sesión con su cuenta empresarial”.<br><br>**Scenario 2: RUC/NIF ya registrado**<br>Dado que el administrador se encuentra en la página de “Registro empresarial”<br>Y ha ingresado un RUC/NIF que ya existe en la base de datos<br>Cuando hace clic en el botón “Registrar empresa”<br>Entonces el sistema muestra un mensaje de error: “El número de RUC/NIF ya está registrado, intente con otro o recupere acceso”.<br><br>**Scenario 3: Correo corporativo ya registrado**<br>Dado que el administrador completa el formulario de registro empresarial<br>Y ingresa un correo corporativo que ya está en uso en otra cuenta<br>Cuando intenta registrarse<br>Entonces el sistema muestra un mensaje de error: “El correo corporativo ya está vinculado a otra empresa”.<br><br>**Scenario 4: Contraseña no cumple requisitos**<br>Dado que el administrador ingresa una contraseña de menos de 8 caracteres o sin mayúsculas/números<br>Cuando hace clic en el botón “Registrar empresa”<br>Entonces el sistema muestra el mensaje: “La contraseña debe tener al menos 8 caracteres, incluir mayúsculas, minúsculas y un número”.<br><br>**Scenario 5: Campos obligatorios vacíos**<br>Dado que el administrador ha dejado uno o más campos obligatorios sin llenar<br>Cuando intenta registrarse<br>Entonces el sistema resalta los campos vacíos en rojo<br>Y muestra el mensaje: “Complete todos los campos obligatorios para continuar”.<br><br>**Scenario 6: Error técnico inesperado**<br>Dado que el administrador ha completado todos los campos correctamente<br>Y ocurre un error en la comunicación con el servidor<br>Cuando hace clic en “Registrar empresa”<br>Entonces el sistema muestra el mensaje: “Ha ocurrido un problema, por favor intente más tarde”<br>Y el error se guarda en los logs del backend. |
| HU9 | HU9 | Hogar | Inicio de sesión | Como usuario de hogar, quiero iniciar sesión de forma segura para acceder a mis datos de consumo. | **Scenario 1: Usuario inicia sesión correctamente**<br>Dado que el usuario está registrado en la plataforma<br>Y el usuario se encuentra en la pantalla de inicio de sesión<br>Cuando el usuario introduce su correo electrónico y contraseña correctos<br>Entonces el sistema autentica las credenciales<br>Y muestra el panel principal con los datos de consumo del usuario.<br><br>**Scenario 2: Usuario ingresa credenciales inválidas**<br>Dado que el usuario está en la pantalla de inicio de sesión<br>Cuando el usuario introduce un correo electrónico y/o contraseña incorrectos<br>Entonces el sistema rechaza la autenticación<br>Y muestra el mensaje: “Credenciales inválidas, verifique sus datos”.<br><br>**Scenario 3: Cierre automático de sesión por seguridad**<br>Dado que el usuario ha iniciado sesión en la plataforma<br>Cuando el usuario cierra el navegador o permanece inactivo por más de 10 minutos<br>Entonces el sistema cierra la sesión automáticamente<br>Y redirige al usuario nuevamente a la pantalla de inicio de sesión.<br><br>**Scenario 4: Usuario usa la opción “Recordar sesión”**<br>Dado que el usuario está en la pantalla de inicio de sesión<br>Y marca la casilla “Recordarme”<br>Cuando introduce credenciales correctas<br>Entonces el sistema autentica al usuario<br>Y mantiene la sesión activa en ese dispositivo hasta que el usuario cierre sesión manualmente. |
| HU10 | HU10 | PYME | Inicio de sesión corporativo | Como administrador de PYME, quiero iniciar sesión corporativa para acceder a las métricas de mi organización. | **Scenario 1: Inicio de sesión exitoso**<br>Dado que el administrador de PYME está registrado en la plataforma<br>Y el administrador se encuentra en la pantalla de inicio de sesión corporativa<br>Cuando introduce su correo corporativo y contraseña correctos<br>Entonces el sistema autentica las credenciales<br>Y muestra el panel principal con las métricas y consumo energético de la empresa.<br><br>**Scenario 2: Credenciales incorrectas**<br>Dado que el administrador de PYME está en la pantalla de inicio de sesión corporativa<br>Cuando introduce un correo corporativo y/o contraseña incorrectos<br>Entonces el sistema rechaza la autenticación<br>Y muestra el mensaje: “Credenciales inválidas, verifique sus datos”.<br><br>**Scenario 3: Cierre automático de sesión por inactividad**<br>Dado que el administrador de PYME ha iniciado sesión<br>Cuando permanece inactivo por más de X minutos o cierra el navegador<br>Entonces el sistema cierra la sesión automáticamente<br>Y redirige al administrador nuevamente a la pantalla de inicio de sesión corporativa.<br><br>**Scenario 4: Uso de opción “Recordar sesión”**<br>Dado que el administrador de PYME se encuentra en la pantalla de inicio de sesión corporativa<br>Y marca la casilla “Recordarme”<br>Cuando introduce credenciales correctas<br>Entonces el sistema autentica al administrador<br>Y mantiene la sesión activa en ese dispositivo hasta que el administrador cierre sesión manualmente. |
| HU11 | HU11 | PYME | Gestión de múltiples usuarios | Como administrador de PYME, quiero dar acceso a distintos roles (empleados, supervisores) para distribuir responsabilidades. | **Scenario 1: Agregar un nuevo usuario con rol específico**<br>Dado que el administrador de PYME ha iniciado sesión correctamente<br>Y se encuentra en la sección de gestión de usuarios<br>Cuando el administrador ingresa los datos del nuevo usuario y asigna un rol (empleado o supervisor)<br>Entonces el sistema crea el usuario en la base de datos<br>Y asigna el rol correspondiente<br>Y muestra un mensaje de confirmación: “Usuario agregado exitosamente”.<br><br>**Scenario 2: Intento de agregar usuario con correo existente**<br>Dado que el administrador intenta registrar un usuario con un correo electrónico ya registrado<br>Cuando hace clic en “Agregar usuario”<br>Entonces el sistema muestra un mensaje de error: “El correo electrónico ya está en uso, utilice otro”.<br><br>**Scenario 3: Modificar rol de un usuario existente**<br>Dado que el administrador está en la sección de gestión de usuarios<br>Y el usuario ya existe en la lista<br>Cuando el administrador cambia el rol del usuario y guarda los cambios<br>Entonces el sistema actualiza el rol del usuario en la base de datos<br>Y muestra un mensaje de confirmación: “Rol actualizado exitosamente”.<br><br>**Scenario 4: Eliminación de un usuario**<br>Dado que el administrador se encuentra en la lista de usuarios<br>Y selecciona un usuario para eliminar<br>Cuando confirma la acción de eliminación<br>Entonces el sistema elimina al usuario de la base de datos<br>Y muestra un mensaje: “Usuario eliminado correctamente”.<br><br>**Scenario 5: Error técnico al gestionar usuarios**<br>Dado que el administrador intenta agregar, modificar o eliminar un usuario<br>Cuando ocurre un fallo en la comunicación con el servidor<br>Entonces el sistema muestra el mensaje: “Ha ocurrido un error, por favor intente más tarde”<br>Y registra el error en los logs del backend. |
| HU12 | HU12 | Hogar | Personalización de perfil | Como usuario de hogar, quiero personalizar mi perfil con mis hábitos para recibir recomendaciones más relevantes. | **Scenario 1: Actualización exitosa de perfil**<br>Dado que el usuario de hogar ha iniciado sesión correctamente<br>Y se encuentra en la sección de “Perfil”<br>Cuando el usuario ingresa sus hábitos de consumo (horarios, dispositivos frecuentes, preferencias)<br>Y hace clic en “Guardar cambios”<br>Entonces el sistema actualiza la información en la base de datos<br>Y muestra un mensaje de confirmación: “Perfil actualizado correctamente”.<br><br>**Scenario 2: Campos obligatorios incompletos**<br>Dado que el usuario está en la sección de “Perfil”<br>Cuando deja uno o más campos obligatorios vacíos y hace clic en “Guardar cambios”<br>Entonces el sistema resalta los campos vacíos<br>Y muestra el mensaje: “Complete todos los campos obligatorios para actualizar su perfil”.<br><br>**Scenario 3: Datos inválidos**<br>Dado que el usuario introduce información en un formato incorrecto (por ejemplo, texto en un campo numérico)<br>Cuando hace clic en “Guardar cambios”<br>Entonces el sistema muestra un mensaje de validación: “Ingrese datos válidos en todos los campos”.<br><br>**Scenario 4: Error técnico al actualizar perfil**<br>Dado que el usuario ha completado todos los campos correctamente<br>Cuando ocurre un fallo en la comunicación con el servidor al guardar los cambios<br>Entonces el sistema muestra el mensaje: “Ha ocurrido un error, por favor intente más tarde”<br>Y registra el error en los logs del backend.<br><br>**Scenario 5: Visualización de perfil actualizado**<br>Dado que el usuario ha guardado cambios exitosamente<br>Cuando vuelve a acceder a la sección de “Perfil”<br>Entonces el sistema muestra la información actualizada correctamente en todos los campos. |
### Epic 3 – Monitoreo y Control Energético
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU13 | HU13 | Hogar | Dashboard en tiempo real | Como usuario de hogar, quiero visualizar el consumo energético en un dashboard para monitorear mi gasto en tiempo real. | **Scenario 1: Visualización del consumo en tiempo real**<br>Dado que el usuario ha iniciado sesión correctamente<br>Cuando abre la sección “Dashboard”<br>Entonces el sistema muestra el consumo energético actual en tiempo real<br>Y el sistema actualiza los datos cada minuto sin necesidad de recargar la página<br><br>**Scenario 2: Visualización de gráficos de consumo por dispositivo**<br>Dado que el usuario tiene varios dispositivos registrados<br>Cuando abre la sección “Dashboard”<br>Entonces el sistema muestra un gráfico por cada dispositivo mostrando su consumo actual<br>Y cada gráfico incluye etiquetas con nombre de dispositivo y valor de consumo<br><br>**Scenario 3: Indicadores de consumo total y comparativa diaria**<br>Dado que el usuario accede al dashboard<br>Cuando visualiza la información general<br>Entonces el sistema muestra el consumo total del hogar hasta el momento<br>Y compara el consumo con el promedio diario del usuario mostrando una alerta si supera el promedio |
| HU14 | HU14 | PYME | Dashboard empresarial | Como administrador de PYME, quiero ver un panel de consumo por áreas/departamentos para identificar ineficiencias. | **Scenario 1: Visualización del consumo por área**<br>Dado que el administrador ha iniciado sesión correctamente<br>Cuando abre la sección “Dashboard Empresarial”<br>Entonces el sistema muestra el consumo energético total de cada área/departamento<br>Y cada área incluye un gráfico indicando su consumo en tiempo real<br><br>**Scenario 2: Identificación de áreas con consumo elevado**<br>Dado que el sistema tiene datos históricos de consumo<br>Cuando se visualiza el dashboard<br>Entonces las áreas que superen los umbrales definidos se resaltan en rojo<br>Y se muestra una alerta indicando posibles ineficiencias<br><br>**Scenario 3: Comparativa entre áreas/departamentos**<br>Dado que existen múltiples áreas registradas<br>Cuando el administrador selecciona la opción “Comparativa de áreas”<br>Entonces el sistema genera un gráfico comparativo mostrando el consumo de todas las áreas<br>Y se indican porcentajes de consumo relativo entre cada departamento<br><br>**Scenario 4: Actualización automática de datos**<br>Dado que el administrador mantiene abierto el dashboard<br>Cuando pasan nuevos registros de consumo<br>Entonces el sistema actualiza automáticamente los gráficos y valores sin necesidad de recargar la página |
| HU15 | HU15 | Hogar | Control remoto de dispositivos | Como usuario de hogar, quiero encender/apagar mis dispositivos desde la app para ahorrar energía. | **Scenario 1: Encender un dispositivo desde la app**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos registrados en su hogar<br>Cuando selecciona un dispositivo y pulsa “Encender”<br>Entonces el sistema envía la señal al dispositivo<br>Y el dispositivo se enciende, actualizando su estado en la app a “Encendido”<br><br>**Scenario 2: Apagar un dispositivo desde la app**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos encendidos<br>Cuando selecciona un dispositivo y pulsa “Apagar”<br>Entonces el sistema envía la señal al dispositivo<br>Y el dispositivo se apaga, actualizando su estado en la app a “Apagado”<br><br>**Scenario 3: Visualización del estado de todos los dispositivos**<br>Dado que el usuario abre la sección “Mis dispositivos”<br>Cuando la app carga los datos<br>Entonces se muestran todos los dispositivos con su estado actual (Encendido / Apagado)<br>Y el usuario puede identificar rápidamente cuáles están activos y cuáles apagados<br><br>**Scenario 4: Notificación de fallo de control**<br>Dado que un dispositivo no responde a la señal de encendido/apagado<br>Cuando el usuario intenta controlarlo desde la app<br>Entonces el sistema muestra un mensaje de error indicando “No se pudo controlar el dispositivo. Intente nuevamente.” |
| HU16 | HU16 | PYME | Control remoto empresarial | Como administrador de PYME, quiero gestionar remotamente dispositivos de mi oficina para reducir gastos energéticos. | **Scenario 1: Encender dispositivos por área/departamento**<br>Dado que el administrador ha iniciado sesión correctamente<br>Y tiene áreas/departamentos con dispositivos registrados<br>Cuando selecciona un área y pulsa “Encender todos”<br>Entonces el sistema envía la señal a todos los dispositivos del área<br>Y cada dispositivo se enciende mostrando su estado actualizado en el dashboard<br><br>**Scenario 2: Apagar dispositivos por área/departamento**<br>Dado que el administrador ha iniciado sesión correctamente<br>Y algunos dispositivos están encendidos<br>Cuando selecciona un área y pulsa “Apagar todos”<br>Entonces el sistema envía la señal a todos los dispositivos del área<br>Y cada dispositivo se apaga mostrando su estado actualizado en el dashboard<br><br>**Scenario 3: Visualización del estado de los dispositivos corporativos**<br>Dado que el administrador abre la sección “Gestión de dispositivos”<br>Cuando la app carga los datos<br>Entonces se muestran todos los dispositivos con su estado actual (Encendido / Apagado)<br>Y se pueden filtrar por área, departamento o tipo de dispositivo<br><br>**Scenario 4: Notificación de fallo en dispositivos**<br>Dado que algún dispositivo no responde a la señal de control<br>Cuando el administrador intenta encender/apagar desde la app<br>Entonces el sistema muestra un mensaje de error indicando “No se pudo controlar el dispositivo. Verifique la conexión.” |
| HU17 | HU17 | Hogar | Programar horarios | Como usuario de hogar, quiero programar horarios de encendido/apagado de mis electrodomésticos para optimizar el consumo. | **Scenario 1: Programar un horario de encendido**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos registrados<br>Cuando selecciona un dispositivo y establece un horario de encendido<br>Entonces el sistema guarda la programación<br>Y el dispositivo se enciende automáticamente a la hora establecida<br><br>**Scenario 2: Programar un horario de apagado**<br>Dado que el usuario ha iniciado sesión correctamente<br>Y tiene dispositivos encendidos<br>Cuando selecciona un dispositivo y establece un horario de apagado<br>Entonces el sistema guarda la programación<br>Y el dispositivo se apaga automáticamente a la hora establecida<br><br>**Scenario 3: Visualizar horarios programados**<br>Dado que el usuario abre la sección “Programaciones”<br>Cuando la app carga los datos<br>Entonces se muestran todos los horarios activos por dispositivo<br>Y se puede editar o eliminar cada programación<br><br>**Scenario 4: Notificación de conflicto de horarios**<br>Dado que el usuario intenta establecer un horario que entra en conflicto con otra programación<br>Cuando guarda el nuevo horario<br>Entonces el sistema muestra un mensaje de advertencia indicando “Conflicto de programación. Ajuste la hora para continuar.” |
| HU18 | HU18 | PYME | Programación grupal | Como administrador de PYME, quiero establecer horarios automáticos de apagado en áreas comunes para evitar consumos innecesarios. | **Scenario 1: Establecer horario de apagado por área**<br>Dado que el administrador ha iniciado sesión correctamente<br>Y existen áreas comunes con dispositivos registrados<br>Cuando selecciona un área y configura un horario de apagado automático<br>Entonces el sistema guarda la programación<br>Y todos los dispositivos del área se apagan automáticamente a la hora establecida<br><br>**Scenario 2: Visualizar horarios programados por área**<br>Dado que el administrador abre la sección “Programaciones corporativas”<br>Cuando la app carga los datos<br>Entonces se muestran todos los horarios activos por área<br>Y se puede editar o eliminar cada programación según sea necesario<br><br>**Scenario 3: Notificación de conflicto de horarios**<br>Dado que el administrador intenta establecer un horario que entra en conflicto con otra programación existente<br>Cuando guarda la nueva programación<br>Entonces el sistema muestra un mensaje de advertencia indicando “Conflicto de programación. Ajuste la hora para continuar.”<br><br>**Scenario 4: Confirmación de ejecución**<br>Dado que la hora programada de apagado ha llegado<br>Cuando los dispositivos se apagan automáticamente<br>Entonces el sistema actualiza el dashboard mostrando el estado “Apagado”<br>Y envía una notificación al administrador confirmando la ejecución del horario |
| HU19 | HU19 | Hogar | Gestión de dispositivos | Como usuario de hogar, quiero registrar y administrar mis dispositivos conectados para organizarlos en la app. | **Scenario 1: Registrar un nuevo dispositivo**<br>Dado que el usuario ha iniciado sesión correctamente<br>Cuando selecciona la opción “Agregar dispositivo”<br>Y completa los datos requeridos (nombre, tipo, ubicación)<br>Entonces el sistema guarda el dispositivo en su perfil<br>Y el dispositivo aparece listado en la sección “Mis dispositivos”<br><br>**Scenario 2: Editar información de un dispositivo registrado**<br>Dado que el usuario tiene dispositivos registrados<br>Cuando selecciona un dispositivo y elige la opción “Editar”<br>Y modifica los datos (nombre, tipo, ubicación)<br>Entonces el sistema actualiza la información<br>Y los cambios se reflejan inmediatamente en la lista de dispositivos<br><br>**Scenario 3: Eliminar un dispositivo registrado**<br>Dado que el usuario tiene dispositivos registrados<br>Cuando selecciona un dispositivo y pulsa “Eliminar”<br>Entonces el sistema solicita confirmación de eliminación<br>Y al confirmar, el dispositivo se elimina de la lista y del perfil del usuario<br><br>**Scenario 4: Visualizar dispositivos organizados por ubicación o tipo**<br>Dado que el usuario abre la sección “Mis dispositivos”<br>Cuando el sistema carga los datos<br>Entonces los dispositivos se muestran organizados por ubicación o tipo<br>Y el usuario puede filtrar o buscar dispositivos fácilmente |
| HU20 | HU20 | PYME | Gestión masiva de dispositivos | Como administrador de PYME, quiero dar de alta y controlar múltiples dispositivos de manera centralizada para optimizar su uso. | **Scenario 1: Dar de alta múltiples dispositivos**<br>Dado que el administrador ha iniciado sesión correctamente<br>Cuando selecciona la opción “Agregar dispositivos masivamente”<br>Y carga un archivo con la información de varios dispositivos (nombre, tipo, ubicación)<br>Entonces el sistema registra todos los dispositivos correctamente<br>Y los dispositivos aparecen listados en la sección “Gestión de dispositivos”<br><br>**Scenario 2: Controlar dispositivos de manera centralizada**<br>Dado que el administrador tiene múltiples dispositivos registrados<br>Cuando selecciona un grupo de dispositivos y elige “Encender” o “Apagar”<br>Entonces el sistema envía la señal a todos los dispositivos seleccionados<br>Y actualiza su estado en el dashboard mostrando “Encendido” o “Apagado”<br><br>**Scenario 3: Editar información de dispositivos masivos**<br>Dado que el administrador desea actualizar información de varios dispositivos<br>Cuando selecciona un grupo de dispositivos y aplica cambios (ubicación, tipo, área)<br>Entonces el sistema actualiza la información de todos los dispositivos seleccionados<br>Y los cambios se reflejan inmediatamente en la lista<br><br>**Scenario 4: Eliminación masiva de dispositivos**<br>Dado que el administrador desea eliminar varios dispositivos<br>Cuando selecciona un grupo de dispositivos y pulsa “Eliminar”<br>Entonces el sistema solicita confirmación<br>Y al confirmar, todos los dispositivos seleccionados se eliminan de manera centralizada |
### Epic 4 – Reportes y Alertas
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU21 | HU21 | Hogar | Reporte diario | Como usuario de hogar, quiero recibir un reporte diario de mi consumo para tener visibilidad de mis hábitos. | **Scenario 1: Generación automática del reporte diario**<br>Dado que el usuario tiene dispositivos registrados en la plataforma<br>Cuando el sistema procesa la información de consumo al final del día<br>Entonces genera un reporte con el detalle del consumo energético diario<br>Y el reporte queda disponible en la sección “Historial de consumo” de la app<br><br>**Scenario 2: Envío de reporte por notificación**<br>Dado que el usuario tiene configuradas notificaciones en la aplicación<br>Cuando el reporte diario es generado<br>Entonces el sistema envía una notificación push al dispositivo móvil<br>Y al abrir la notificación, el usuario accede directamente al reporte<br><br>**Scenario 3: Contenido del reporte**<br>Dado que el usuario consulta su reporte diario<br>Cuando el reporte es mostrado en la app<br>Entonces el sistema presenta los datos de consumo total en kWh, costo estimado y dispositivos de mayor consumo<br>Y muestra comparaciones con el día anterior para identificar variaciones<br><br>**Scenario 4: Acceso a reportes pasados**<br>Dado que el usuario quiere revisar reportes de días anteriores<br>Cuando selecciona una fecha en el calendario dentro de “Historial de consumo”<br>Entonces el sistema muestra el reporte correspondiente a ese día con el mismo formato |
| HU22 | HU22 | PYME | Reporte semanal corporativo | Como administrador de PYME, quiero recibir reportes semanales consolidados para analizar patrones de consumo en mi empresa. | **Scenario 1: Generación automática del reporte semanal**<br>Dado que el administrador tiene múltiples dispositivos registrados en la plataforma<br>Cuando el sistema procesa la información de consumo al finalizar la semana<br>Entonces genera un reporte consolidado con el detalle del consumo energético semanal de la empresa<br>Y el reporte queda disponible en la sección “Historial corporativo” de la app<br><br>**Scenario 2: Envío del reporte por correo electrónico**<br>Dado que el administrador tiene configurado su correo en la aplicación<br>Cuando el reporte semanal es generado<br>Entonces el sistema envía automáticamente el reporte en formato PDF y Excel al correo registrado<br>Y el administrador recibe una notificación de confirmación en la app<br><br>**Scenario 3: Contenido del reporte**<br>Dado que el administrador consulta su reporte semanal<br>Cuando el reporte es mostrado en la app<br>Entonces el sistema presenta los datos de consumo total en kWh, costo estimado y desglose por áreas o dispositivos<br>Y muestra comparaciones con semanas anteriores para identificar patrones de consumo<br><br>**Scenario 4: Acceso a reportes pasados**<br>Dado que el administrador quiere revisar reportes de semanas anteriores<br>Cuando selecciona una semana en el calendario dentro de “Historial corporativo”<br>Entonces el sistema muestra el reporte correspondiente a esa semana con el mismo formato |
| HU23 | HU23 | Hogar | Alertas de exceso | Como usuario de hogar, quiero recibir alertas cuando supere un umbral de consumo para reaccionar a tiempo. | **Scenario 1: Configuración de umbral de consumo**<br>Dado que el usuario se encuentra en la sección "Configuración de alertas"<br>Cuando el usuario establece un valor límite de consumo diario o mensual en kWh<br>Entonces el sistema guarda ese umbral como referencia para generar alertas<br><br>**Scenario 2: Generación de alerta por exceso de consumo**<br>Dado que el sistema monitorea el consumo energético en tiempo real<br>Y el usuario configuró un umbral de consumo<br>Cuando el consumo acumulado supera el umbral definido<br>Entonces el sistema genera automáticamente una alerta<br>Y muestra el mensaje “Has superado tu límite de consumo” en la sección de notificaciones<br><br>**Scenario 3: Envío de notificación push**<br>Dado que el usuario tiene habilitadas las notificaciones en su dispositivo<br>Cuando el sistema genera una alerta por exceso de consumo<br>Entonces el sistema envía una notificación push con el detalle del exceso detectado<br>Y el usuario puede acceder desde la notificación al detalle de consumo<br><br>**Scenario 4: Consulta de historial de alertas**<br>Dado que el usuario ingresa al historial de alertas en la aplicación<br>Cuando el sistema muestra las alertas pasadas<br>Entonces se presentan la fecha, hora y nivel de exceso de cada alerta registrada |
| HU24 | HU24 | PYME | Alertas de picos energéticos | Como administrador de PYME, quiero recibir alertas automáticas en picos de consumo para identificar anomalías. | **Scenario 1: Configuración de umbral de pico energético**<br>Dado que el administrador accede a la sección "Configuración de alertas"<br>Cuando define un umbral de consumo máximo en kWh por hora o por área<br>Entonces el sistema guarda este umbral para detectar futuros picos energéticos<br><br>**Scenario 2: Generación de alerta por pico energético**<br>Dado que el sistema monitorea el consumo energético en tiempo real por áreas/departamentos<br>Y existe un umbral de pico configurado<br>Cuando se detecta que el consumo supera ese umbral en un periodo corto de tiempo<br>Entonces el sistema genera automáticamente una alerta de pico energético<br>Y muestra un mensaje en la sección de notificaciones<br><br>**Scenario 3: Envío de notificación corporativa**<br>Dado que el administrador tiene habilitadas las notificaciones en la plataforma<br>Cuando ocurre un pico energético y el sistema genera una alerta<br>Entonces se envía una notificación al administrador con los detalles (área, hora, nivel de consumo)<br><br>**Scenario 4: Consulta de historial de alertas de picos**<br>Dado que el administrador accede al historial de alertas en la plataforma<br>Cuando el sistema lista las alertas anteriores<br>Entonces se muestran los registros con fecha, hora, área afectada y nivel del pico detectado |
| HU25 | HU25 | Hogar | Historial de consumo | Como usuario de hogar, quiero ver un historial gráfico de mi consumo energético para analizar mis tendencias. | **Scenario 1: Acceso al historial de consumo**<br>Dado que el usuario de hogar inicia sesión en la plataforma<br>Cuando accede a la sección "Historial de consumo"<br>Entonces el sistema muestra un gráfico con el consumo energético registrado en los últimos días<br><br>**Scenario 2: Visualización por periodos de tiempo**<br>Dado que el sistema muestra el historial de consumo en un gráfico<br>Cuando el usuario selecciona un rango de tiempo (diario, semanal, mensual)<br>Entonces el gráfico se actualiza mostrando los datos correspondientes a ese periodo<br><br>**Scenario 3: Detalle de consumo en puntos del gráfico**<br>Dado que el gráfico de historial de consumo está visible<br>Cuando el usuario pasa el cursor o toca un punto específico del gráfico<br>Entonces el sistema muestra el valor exacto del consumo correspondiente a esa fecha y hora<br><br>**Scenario 4: Exportación del historial de consumo**<br>Dado que el usuario desea conservar un registro fuera de la plataforma<br>Cuando selecciona la opción "Exportar historial"<br>Entonces el sistema genera un archivo descargable (CSV o PDF) con los datos del consumo energético en el rango seleccionado |
| HU26 | HU26 | PYME | Historial corporativo avanzado | Como administrador de PYME, quiero generar reportes históricos avanzados para evaluar el impacto de medidas de ahorro. | **Scenario 1: Acceso al historial corporativo**<br>Dado que el administrador de PYME inicia sesión en la plataforma<br>Cuando accede a la sección "Historial corporativo avanzado"<br>Entonces el sistema muestra un panel con las métricas históricas de consumo energético de la empresa<br><br>**Scenario 2: Selección de periodos personalizados**<br>Dado que el administrador visualiza el historial corporativo<br>Cuando selecciona un rango de fechas personalizado (ejemplo: últimos 6 meses o un año específico)<br>Entonces el sistema actualiza los gráficos y tablas con los datos correspondientes a ese rango<br><br>**Scenario 3: Comparación entre periodos**<br>Dado que el sistema muestra el historial de consumo corporativo<br>Cuando el administrador selecciona dos periodos distintos (ejemplo: 2023 vs 2024)<br>Entonces el sistema presenta un reporte comparativo que muestra diferencias de consumo y tendencias<br><br>**Scenario 4: Evaluación de impacto de medidas de ahorro**<br>Dado que el sistema tiene datos históricos registrados<br>Cuando el administrador activa la opción "Evaluar impacto" sobre periodos donde se aplicaron medidas de ahorro<br>Entonces el sistema genera un reporte resaltando reducciones o incrementos en el consumo energético y calcula el porcentaje de variación<br><br>**Scenario 5: Exportación de reportes históricos**<br>Dado que el administrador requiere almacenar los datos fuera de la plataforma<br>Cuando selecciona la opción "Exportar historial avanzado"<br>Entonces el sistema genera un archivo descargable (CSV o PDF) con los gráficos, métricas y comparaciones seleccionadas |
| HU27 | HU27 | Hogar | Comparativa mensual | Como usuario de hogar, quiero comparar mi consumo mensual con meses anteriores para evaluar mi progreso. | **Scenario 1: Acceso a la comparativa mensual**<br>Dado que el usuario de hogar inicia sesión en la plataforma<br>Cuando accede a la sección "Comparativa mensual"<br>Entonces el sistema muestra un gráfico con el consumo del mes actual y de los últimos meses<br><br>**Scenario 2: Selección de meses anteriores**<br>Dado que el usuario está visualizando la comparativa mensual<br>Cuando selecciona uno o más meses anteriores en el filtro<br>Entonces el sistema actualiza el gráfico mostrando el consumo de los meses seleccionados junto al consumo actual<br><br>**Scenario 3: Indicador de progreso**<br>Dado que el sistema presenta los datos de consumo mensual<br>Cuando el usuario visualiza la comparativa<br>Entonces el sistema muestra un indicador visual (ejemplo: porcentaje de aumento o reducción) para señalar la evolución frente a meses anteriores<br><br>**Scenario 4: Descarga de reporte mensual**<br>Dado que el usuario quiere guardar los resultados de la comparativa<br>Cuando selecciona la opción "Descargar comparativa mensual"<br>Entonces el sistema genera un archivo en formato PDF o CSV con la información de consumo comparativo<br><br>**Scenario 5: Consumo superior al promedio**<br>Dado que el sistema detecta que el consumo del mes actual es mayor al promedio de los meses anteriores<br>Cuando se actualiza la comparativa mensual<br>Entonces el sistema muestra una alerta informativa recomendando revisar hábitos de consumo |
| HU28 | HU28 | PYME | Comparativa entre sedes | Como administrador de PYME, quiero comparar el consumo energético entre distintas sedes para detectar ineficiencias. | **Scenario 1: Acceso a la comparativa entre sedes**<br>Dado que el administrador de PYME inicia sesión en la plataforma<br>Cuando accede a la sección "Comparativa entre sedes"<br>Entonces el sistema muestra una tabla y/o gráfico con el consumo energético de cada sede registrada en la cuenta<br><br>**Scenario 2: Selección de rango de fechas**<br>Dado que el administrador se encuentra en la sección de comparativa entre sedes<br>Cuando selecciona un rango de fechas específico<br>Entonces el sistema actualiza los datos de consumo para mostrar solo el consumo de las sedes en ese rango de fechas<br><br>**Scenario 3: Identificación de sede con mayor consumo**<br>Dado que el sistema presenta los datos de todas las sedes en un gráfico comparativo<br>Cuando se actualizan los valores<br>Entonces el sistema resalta la sede con mayor consumo con un indicador visual (ejemplo: color resaltado o ícono de advertencia)<br><br>**Scenario 4: Exportación de comparativa**<br>Dado que el administrador necesita registrar los datos para análisis externo<br>Cuando selecciona la opción "Exportar comparativa"<br>Entonces el sistema genera un archivo en formato PDF o Excel con el detalle de consumo energético de cada sede<br><br>**Scenario 5: Generación de alertas automáticas**<br>Dado que la comparativa entre sedes identifica una diferencia significativa en el consumo (ejemplo: una sede con un 30% más de consumo que el promedio)<br>Cuando se guarda la comparativa<br>Entonces el sistema genera una alerta automática notificando al administrador sobre la anomalía detectada |
| HU29 | HU29 | Hogar | Notificaciones push | Como usuario de hogar, quiero recibir notificaciones push sobre mi consumo para estar informado en tiempo real. | **Scenario 1: Activación de notificaciones**<br>Dado que el usuario de hogar ha iniciado sesión en la aplicación<br>Cuando accede a la sección de configuración de notificaciones y activa la opción de "Notificaciones push"<br>Entonces el sistema guarda la preferencia y habilita el envío de notificaciones en tiempo real<br><br>**Scenario 2: Recepción de notificación por consumo excesivo**<br>Dado que el usuario tiene activadas las notificaciones push<br>Cuando su consumo energético diario supera el umbral configurado en su perfil<br>Entonces el sistema envía una notificación push con el mensaje de advertencia y el detalle del consumo<br><br>**Scenario 3: Notificación de reporte diario disponible**<br>Dado que el sistema genera automáticamente el reporte diario de consumo<br>Cuando el reporte está listo para visualizarse<br>Entonces el usuario recibe una notificación push indicando que puede revisar su reporte en la aplicación<br><br>**Scenario 4: Sincronización de notificaciones en múltiples dispositivos**<br>Dado que el usuario de hogar tiene la aplicación instalada en más de un dispositivo (ejemplo: móvil y tablet)<br>Cuando se genera una notificación push<br>Entonces el sistema envía la notificación a todos los dispositivos vinculados con la misma cuenta<br><br>**Scenario 5: Desactivación de notificaciones**<br>Dado que el usuario ya no desea recibir notificaciones en tiempo real<br>Cuando desactiva la opción de "Notificaciones push" en la configuración<br>Entonces el sistema detiene el envío de notificaciones hasta que el usuario las active nuevamente |
| HU30 | HU30 | PYME | Notificaciones por correo | Como administrador de PYME, quiero recibir alertas por correo sobre consumos inusuales para actuar oportunamente. | **Scenario 1: Configuración de alertas por correo**<br>Dado que el administrador de PYME ha iniciado sesión en la plataforma<br>Cuando accede a la sección de notificaciones y activa la opción "Alertas por correo"<br>Entonces el sistema guarda la preferencia y habilita el envío de correos ante consumos inusuales<br><br>**Scenario 2: Envío de alerta por consumo inusual**<br>Dado que el administrador tiene activadas las alertas por correo<br>Cuando el sistema detecta un consumo que supera el umbral definido en la configuración de la empresa<br>Entonces se envía un correo automático al administrador con el detalle del evento de consumo<br><br>**Scenario 3: Recepción en múltiples destinatarios**<br>Dado que el administrador ha registrado varios correos de responsables de área<br>Cuando ocurre un evento de consumo inusual<br>Entonces el sistema envía la notificación a todos los correos registrados en la configuración<br><br>**Scenario 4: Confirmación de envío exitoso**<br>Dado que el sistema genera una alerta por correo<br>Cuando el mensaje es enviado<br>Entonces el sistema registra en el historial de notificaciones que el correo fue entregado exitosamente<br><br>**Scenario 5: Desactivación de alertas por correo**<br>Dado que el administrador ya no desea recibir alertas por correo<br>Cuando desactiva la opción en la configuración de notificaciones<br>Entonces el sistema detiene el envío de correos hasta que se reactive nuevamente |
### Epic 5 – Inteligencia Artificial (IA Verde)
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU31 | HU31 | Hogar | Recomendaciones básicas IA | Como usuario de hogar, quiero recibir recomendaciones simples para ahorrar energía en base a mis datos. | **Scenario 1: Generación de recomendaciones iniciales**<br>Dado que el usuario de hogar ha registrado sus dispositivos y hábitos en la plataforma<br>Cuando la IA analiza los primeros datos de consumo<br>Entonces el sistema muestra recomendaciones básicas personalizadas en la sección de “Consejos de ahorro”<br><br>**Scenario 2: Actualización automática de recomendaciones**<br>Dado que el usuario tiene un historial de consumo activo<br>Cuando se detectan cambios en sus patrones de uso<br>Entonces la IA actualiza las recomendaciones y las muestra en el panel principal<br><br>**Scenario 3: Visualización en el dashboard**<br>Dado que el usuario inicia sesión en la plataforma<br>Cuando accede al dashboard de consumo<br>Entonces el sistema despliega un bloque con las recomendaciones actuales generadas por la IA<br><br>**Scenario 4: Diferenciación según tipo de dispositivo**<br>Dado que la IA identifica distintos dispositivos conectados (ejemplo: refrigerador, luces, aire acondicionado)<br>Cuando genera las recomendaciones<br>Entonces el sistema especifica consejos vinculados a cada tipo de dispositivo<br><br>**Scenario 5: Registro de interacción del usuario**<br>Dado que el usuario lee una recomendación<br>Cuando marca la opción “Aplicado” o “No relevante”<br>Entonces el sistema registra la respuesta y ajusta las recomendaciones futuras de acuerdo con las elecciones del usuario |
| HU32 | HU32 | PYME | Recomendaciones IA corporativas | Como administrador de PYME, quiero obtener sugerencias de IA sobre cómo reducir costos energéticos en mis operaciones. | **Scenario 1: Visualización inicial de recomendaciones de IA**<br>Dado que el administrador ha iniciado sesión en el sistema<br>Y el sistema tiene acceso a datos históricos de consumo energético de la empresa<br>Cuando el administrador abre la sección “Recomendaciones de IA”<br>Entonces el sistema muestra un panel con sugerencias personalizadas de ahorro energético<br>Y cada sugerencia incluye una breve explicación comprensible para el usuario.<br><br>**Scenario 2: Actualización periódica de recomendaciones**<br>Dado que el sistema ya generó recomendaciones previas<br>Cuando el sistema detecta nueva información de consumo energético o llega la fecha de actualización programada (ej. semanal)<br>Entonces el sistema recalcula las recomendaciones<br>Y el administrador visualiza un mensaje indicando que hay sugerencias actualizadas.<br><br>**Scenario 3: Exportar recomendaciones**<br>Dado que el administrador visualiza el panel de recomendaciones de IA<br>Cuando el administrador selecciona la opción “Exportar reporte”<br>Entonces el sistema genera un archivo descargable con las recomendaciones y explicaciones en formato PDF o Excel<br>Y el archivo incluye la fecha de generación del reporte. |
| HU33 | HU33 | Hogar | Optimización automática IA | Como usuario de hogar, quiero que la IA configure mis dispositivos automáticamente para optimizar mi consumo sin esfuerzo. | **Scenario 1: Activación de optimización automática**<br>Dado que el usuario de hogar ha iniciado sesión en el sistema<br>Y tiene dispositivos inteligentes vinculados a su cuenta<br>Cuando el usuario activa la opción “Optimización automática con IA” en la configuración<br>Entonces el sistema ajusta automáticamente los dispositivos (ej. aire acondicionado, luces, electrodomésticos) según patrones de uso eficientes<br>Y muestra una notificación confirmando que la optimización está activa.<br><br>**Scenario 2: Ajustes en tiempo real por la IA**<br>Dado que la opción de “Optimización automática con IA” está activa<br>Cuando el sistema detecta un consumo elevado en un dispositivo fuera de lo normal<br>Entonces la IA ajusta la configuración de dicho dispositivo para reducir el consumo<br>Y envía una notificación al usuario indicando la acción tomada.<br><br>**Scenario 3: Desactivación de optimización automática**<br>Dado que la IA está gestionando automáticamente los dispositivos del hogar<br>Cuando el usuario desactiva la opción de “Optimización automática con IA”<br>Entonces el sistema detiene cualquier ajuste automático<br>Y los dispositivos mantienen su última configuración manual. |
| HU34 | HU34 | PYME | Estrategias automáticas IA corporativas | Como administrador de PYME, quiero que la IA ajuste automáticamente el consumo de mi empresa para reducir costos y huella de carbono. | **Scenario 1: Activación de estrategias automáticas IA**<br>Dado que el administrador de la PYME tiene acceso al panel de control energético<br>Y existen dispositivos y medidores vinculados a la empresa<br>Cuando el administrador activa la opción “Estrategias automáticas con IA” en el sistema<br>Entonces la IA analiza los patrones de consumo corporativo<br>Y ajusta automáticamente los dispositivos y horarios de operación para optimizar el uso energético.<br><br>**Scenario 2: Ajustes en tiempo real para reducción de costos**<br>Dado que la opción “Estrategias automáticas con IA” está activa<br>Cuando el sistema detecta un pico de consumo en horas de alta demanda energética<br>Entonces la IA redistribuye las cargas de trabajo y pospone procesos no críticos<br>Y envía una alerta al administrador informando las acciones tomadas y el ahorro estimado.<br><br>**Scenario 3: Ajustes en tiempo real para reducir huella de carbono**<br>Dado que el sistema está optimizando automáticamente el consumo<br>Cuando la IA identifica oportunidades de reducción de emisiones (ej. priorizar energía renovable disponible)<br>Entonces ajusta los dispositivos y procesos corporativos para maximizar el uso de energía limpia<br>Y genera un reporte con el impacto ambiental reducido.<br><br>**Scenario 4: Desactivación de estrategias automáticas IA**<br>Dado que la IA está gestionando automáticamente el consumo corporativo<br>Cuando el administrador desactiva la opción de “Estrategias automáticas con IA”<br>Entonces el sistema detiene los ajustes automáticos<br>Y los dispositivos vuelven a su configuración estándar de operación. |
### Epic 6 – Accesibilidad y Compatibilidad
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU35 | HU35 | Hogar | Compatibilidad multiplataforma | Como usuario de hogar, quiero que la aplicación esté disponible en iOS y Android para acceder desde cualquier dispositivo. | **Scenario 1: Instalación en iOS**<br>Dado que el usuario tiene un dispositivo con sistema operativo iOS<br>Cuando el usuario accede a la App Store y busca la aplicación<br>Entonces el sistema permite descargar e instalar la aplicación correctamente<br>Y la aplicación se ejecuta sin errores en iOS.<br><br>**Scenario 2: Instalación en Android**<br>Dado que el usuario tiene un dispositivo con sistema operativo Android<br>Cuando el usuario accede a Google Play Store y busca la aplicación<br>Entonces el sistema permite descargar e instalar la aplicación correctamente<br>Y la aplicación se ejecuta sin errores en Android.<br><br>**Scenario 3: Sincronización entre dispositivos**<br>Dado que el usuario tiene la aplicación instalada en un dispositivo iOS y en un dispositivo Android con la misma cuenta<br>Cuando inicia sesión en ambos dispositivos<br>Entonces el sistema sincroniza los datos de consumo, reportes y configuraciones<br>Y el usuario puede acceder a la misma información en ambos dispositivos.<br><br>**Scenario 4: Interfaz adaptativa**<br>Dado que la aplicación está instalada en un dispositivo iOS o Android<br>Cuando el usuario abre la aplicación<br>Entonces la interfaz se adapta correctamente a las dimensiones y resoluciones de la pantalla del dispositivo<br>Y mantiene la misma experiencia de uso en ambas plataformas. |
| HU36 | HU36 | PYME | Acceso web empresarial | Como administrador de PYME, quiero poder acceder a la plataforma vía web para gestionarla desde mi oficina. | **Scenario 1: Acceso desde navegador**<br>Dado que el administrador cuenta con un navegador actualizado en su equipo de oficina<br>Cuando ingresa la URL de la plataforma en la barra de direcciones<br>Entonces el sistema muestra la pantalla de inicio de sesión<br>Y permite al administrador autenticarse correctamente.<br><br>**Scenario 2: Inicio de sesión seguro**<br>Dado que el administrador ingresa su usuario y contraseña válidos<br>Cuando presiona el botón “Iniciar sesión”<br>Entonces el sistema valida las credenciales<br>Y muestra el panel de control empresarial.<br><br>**Scenario 3: Gestión completa desde web**<br>Dado que el administrador accedió al panel de control empresarial vía web<br>Cuando navega por las diferentes secciones de la plataforma<br>Entonces el sistema le permite visualizar reportes, configurar dispositivos y recibir alertas<br>Y todas las funcionalidades disponibles en la aplicación móvil están también habilitadas en la versión web.<br><br>**Scenario 4: Compatibilidad de navegadores**<br>Dado que el administrador utiliza navegadores como Google Chrome, Microsoft Edge o Mozilla Firefox<br>Cuando accede a la plataforma web<br>Entonces el sistema muestra la interfaz correctamente<br>Y todas las funcionalidades responden sin errores en los navegadores soportados. |
### Epic 7 – Desarrollo Técnico (RESTful API)
| #HU | HU ID | Tipo Usuario | Nombre HU | Descripción | Criterios de Aceptación |
|-----|-------|--------------|-----------|------------|------------------------|
| HU37 | HU37 | Developer | Endpoint de autenticación | Como desarrollador, quiero un endpoint de autenticación basado en JWT para gestionar de forma segura el acceso a la aplicación. | **Scenario 1: Solicitud de autenticación exitosa**<br>Dado que el desarrollador envía una solicitud POST al endpoint de autenticación con credenciales válidas (usuario y contraseña)<br>Cuando el sistema valida dichas credenciales en la base de datos<br>Entonces el sistema responde con un token JWT válido que incluye el identificador del usuario y tiempo de expiración.<br><br>**Scenario 2: Solicitud de autenticación fallida**<br>Dado que el desarrollador envía credenciales incorrectas al endpoint de autenticación<br>Cuando el sistema intenta validar los datos<br>Entonces el sistema responde con un código de error HTTP 401 (Unauthorized) y un mensaje indicando “Credenciales inválidas”.<br><br>**Scenario 3: Expiración del token**<br>Dado que el desarrollador utiliza un token JWT previamente generado<br>Cuando el tiempo de validez del token ha expirado<br>Entonces el sistema rechaza la solicitud y devuelve un error 401 (Unauthorized) con el mensaje “Token expirado”.<br><br>**Scenario 4: Verificación del token en peticiones**<br>Dado que el desarrollador realiza una solicitud a un endpoint protegido<br>Cuando incluye un token JWT válido en la cabecera de autorización<br>Entonces el sistema valida el token y concede acceso a los recursos solicitados.<br><br>**Scenario 5: Token inválido o manipulado**<br>Dado que el desarrollador envía un token JWT alterado o inválido en la cabecera de autorización<br>Cuando el sistema intenta validar el token<br>Entonces rechaza la solicitud y responde con un error 403 (Forbidden) indicando que el token no es válido. |
| HU38 | HU38 | Developer | Endpoint de consumo energético | Como desarrollador, quiero exponer un endpoint que devuelva el consumo energético en tiempo real para mostrarlo en la app Angular. | **Scenario 1: Consulta de consumo en tiempo real exitosa**<br>Dado que el desarrollador envía una solicitud GET al endpoint /api/consumo/realtime con un token JWT válido<br>Cuando el sistema obtiene los datos de consumo de los dispositivos asociados al usuario<br>Entonces responde con un objeto JSON que contiene el valor de consumo actual, la fecha y hora de la medición.<br><br>**Scenario 2: Usuario sin dispositivos registrados**<br>Dado que el usuario autenticado no tiene dispositivos asociados en la base de datos<br>Cuando se solicita el consumo en tiempo real<br>Entonces el sistema responde con un objeto JSON vacío o con valores en cero, junto con un mensaje “No se encontraron dispositivos registrados”.<br><br>**Scenario 3: Token no válido**<br>Dado que el desarrollador realiza la solicitud al endpoint sin incluir un token JWT válido en la cabecera<br>Cuando el sistema intenta validar la autenticación<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 4: Error en la obtención de datos**<br>Dado que el desarrollador envía una solicitud correcta al endpoint<br>Cuando ocurre un error en la consulta a la base de datos o al servicio de monitoreo<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al obtener datos de consumo energético”. |
| HU39 | HU39 | Developer | Endpoint de control de dispositivos | Como desarrollador, quiero un endpoint para encender/apagar dispositivos conectados a los actuadores para que el frontend gestione el control remoto. | **Scenario 1: Encendido exitoso de dispositivo**<br>Dado que el desarrollador envía una solicitud POST al endpoint /api/dispositivos/control con un token JWT válido y un cuerpo JSON con {“deviceId": "123", "action": "on”}<br>Cuando el sistema procesa la solicitud y actualiza el estado del dispositivo en la base de datos<br>Entonces responde con un código 200 y un mensaje “Dispositivo encendido correctamente”.<br><br>**Scenario 2: Apagado exitoso de dispositivo**<br>Dado que el desarrollador envía una solicitud POST al endpoint /api/dispositivos/control con un token JWT válido y un cuerpo JSON con {“deviceId": "123", "action": "off”}<br>Cuando el sistema procesa la solicitud y actualiza el estado del dispositivo en la base de datos<br>Entonces responde con un código 200 y un mensaje “Dispositivo apagado correctamente”.<br><br>**Scenario 3: Token no válido**<br>Dado que el desarrollador realiza la solicitud al endpoint sin incluir un token JWT válido<br>Cuando el sistema intenta autenticar la solicitud<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 4: Dispositivo no encontrado**<br>Dado que el desarrollador envía una solicitud con un deviceId inexistente en la base de datos<br>Cuando el sistema intenta ejecutar la acción<br>Entonces responde con un código 404 (Not Found) y un mensaje “Dispositivo no encontrado”.<br><br>**Scenario 5: Error en la ejecución de la acción**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando ocurre un error en la comunicación con el actuador o en la base de datos<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al ejecutar la acción sobre el dispositivo”. |
| HU40 | HU40 | Developer | Endpoint de reportes históricos | Como desarrollador, quiero un endpoint para obtener el historial de consumo energético por rango de fechas para alimentar los reportes de la app. | **Scenario 1: Consulta exitosa de historial por rango de fechas**<br>Dado que el desarrollador envía una solicitud GET al endpoint /api/reportes/historicos?fechaInicio=2025-01-01&fechaFin=2025-01-31 con un token JWT válido<br>Cuando el sistema valida el token y procesa la solicitud<br>Entonces responde con un código 200 y un cuerpo JSON que contiene la lista de registros de consumo energético dentro del rango de fechas solicitado.<br><br>**Scenario 2: Falta de parámetros de fechas**<br>Dado que el desarrollador envía una solicitud al endpoint sin incluir fechaInicio o fechaFin<br>Cuando el sistema intenta procesar la solicitud<br>Entonces responde con un código 400 (Bad Request) y un mensaje “Parámetros de fecha requeridos”.<br><br>**Scenario 3: Rango de fechas inválido**<br>Dado que el desarrollador envía un rango en el que fechaFin es anterior a fechaInicio<br>Cuando el sistema valida los parámetros<br>Entonces responde con un código 400 (Bad Request) y un mensaje “Rango de fechas inválido”.<br><br>**Scenario 4: Token no válido o ausente**<br>Dado que el desarrollador realiza la solicitud sin un token JWT válido<br>Cuando el sistema intenta autenticar la solicitud<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 5: Sin datos en el rango solicitado**<br>Dado que el desarrollador solicita un rango de fechas válido<br>Cuando no existen registros de consumo energético en ese periodo<br>Entonces el sistema responde con un código 200 y un cuerpo JSON con una lista vacía.<br><br>**Scenario 6: Error interno del servidor**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando ocurre un error inesperado en la base de datos o el backend<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al generar el reporte histórico”. |
| HU41 | HU41 | Developer | Endpoint de recomendaciones IA | Como desarrollador, quiero un endpoint que entregue recomendaciones de ahorro energético para que el frontend las muestre de manera personalizada. | **Scenario 1: Solicitud exitosa de recomendaciones personalizadas**<br>Dado que el desarrollador envía una solicitud GET al endpoint /api/recomendaciones/ia con un token JWT válido y un parámetro userId=123<br>Cuando el sistema procesa la solicitud y consulta el motor de IA con los datos de consumo del usuario<br>Entonces responde con un código 200 y un cuerpo JSON que contiene una lista de recomendaciones personalizadas.<br><br>**Scenario 2: Token no válido o ausente**<br>Dado que el desarrollador realiza la solicitud sin incluir un token JWT válido<br>Cuando el sistema intenta autenticar la solicitud<br>Entonces responde con un código 401 (Unauthorized) y un mensaje “Acceso no autorizado”.<br><br>**Scenario 3: Falta de parámetros requeridos**<br>Dado que el desarrollador envía la solicitud sin incluir el parámetro userId<br>Cuando el sistema valida los parámetros de entrada<br>Entonces responde con un código 400 (Bad Request) y un mensaje “El parámetro userId es requerido”.<br><br>**Scenario 4: Recomendaciones no disponibles**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando el sistema no encuentra recomendaciones generadas para el usuario en ese momento<br>Entonces responde con un código 200 y un cuerpo JSON vacío o con un mensaje “No hay recomendaciones disponibles actualmente”.<br><br>**Scenario 5: Error interno del servidor**<br>Dado que el desarrollador envía una solicitud válida<br>Cuando ocurre un fallo inesperado en el motor de IA o en la base de datos<br>Entonces el sistema responde con un código 500 (Internal Server Error) y un mensaje “Error al generar recomendaciones de IA”. |
## 3.3. Impact Mapping
### Segmento 1: Hogares y Consumidores Individuales
![Impact Mapping Segmento 1](https://i.imgur.com/2WjWAmp.png[/img])
## Segmento 2: Pequeñas y Medianas Empresas (PYMEs)
![Impact Mapping Segmento 2](https://i.imgur.com/c15tMV5.png[/img]g)
## 3.4. Product Backlog
### 3.4. Product Backlog

| Orden | User Story Id | Título | Descripción | Story Points |
| --- | --- | --- | --- | --- |
| 1 | HU1 | Información general del producto | Como visitante interesado en mejorar el consumo energético en mi hogar, quiero acceder a información clara sobre la plataforma para entender cómo me beneficia. | 2 |
| 2 | HU2 | Casos de éxito | Como visitante, quiero consultar casos de éxito reales para confiar en la efectividad de la solución antes de registrarme. | 2 |
| 3 | HU3 | Comparativa de planes | Como visitante, quiero ver la comparativa de planes y precios para elegir la opción que se ajuste mejor a mis necesidades. | 3 |
| 4 | HU4 | Contacto | Como visitante, quiero disponer de un formulario de contacto. | 2 |
| 5 | HU5 | Registro de cuenta | Como usuario de hogar, quiero registrarme en la plataforma para comenzar a gestionar mi consumo energético. | 3 |
| 6 | HU6 | Registro empresarial | Como administrador de PYME, quiero registrar mi empresa en la plataforma para gestionar el consumo energético de mis instalaciones. | 5 |
| 7 | HU7 | Inicio de sesión | Como usuario de hogar, quiero iniciar sesión de forma segura para acceder a mis datos de consumo. | 3 |
| 8 | HU8 | Inicio de sesión corporativo | Como administrador de PYME, quiero iniciar sesión corporativa para acceder a las métricas de mi organización. | 5 |
| 9 | HU9 | Gestión de múltiples usuarios | Como administrador de PYME, quiero dar acceso a distintos roles (empleados, supervisores) para distribuir responsabilidades. | 5 |
| 10 | HU10 | Personalización de perfil | Como usuario de hogar, quiero personalizar mi perfil con mis hábitos para recibir recomendaciones más relevantes. | 3 |
| 11 | HU11 | Dashboard en tiempo real | Como usuario de hogar, quiero visualizar el consumo energético en un dashboard para monitorear mi gasto en tiempo real. | 5 |
| 12 | HU12 | Dashboard empresarial | Como administrador de PYME, quiero ver un panel de consumo por áreas/departamentos para identificar ineficiencias. | 8 |
| 13 | HU13 | Control remoto de dispositivos | Como usuario de hogar, quiero encender/apagar mis dispositivos desde la app para ahorrar energía. | 2 |
| 14 | HU14 | Control remoto empresarial | Como administrador de PYME, quiero gestionar remotamente dispositivos de mi oficina para reducir gastos energéticos. | 5 |
| 15 | HU15 | Programar horarios | Como usuario de hogar, quiero programar horarios de encendido/apagado de mis electrodomésticos para optimizar el consumo. | 4 |
| 16 | HU16 | Programación grupal | Como administrador de PYME, quiero establecer horarios automáticos de apagado en áreas comunes para evitar consumos innecesarios. | 5 |
| 17 | HU17 | Gestión de dispositivos | Como usuario de hogar, quiero registrar y administrar mis dispositivos conectados para organizarlos en la app. | 3 |
| 18 | HU18 | Gestión masiva de dispositivos | Como administrador de PYME, quiero dar de alta y controlar múltiples dispositivos de manera centralizada para optimizar su uso. | 5 |
| 19 | HU19 | Reporte diario | Como usuario de hogar, quiero recibir un reporte diario de mi consumo para tener visibilidad de mis hábitos. | 3 |
| 20 | HU20 | Reporte semanal corporativo | Como administrador de PYME, quiero recibir reportes semanales consolidados para analizar patrones de consumo en mi empresa. | 5 |
| 21 | HU21 | Alertas de exceso | Como usuario de hogar, quiero recibir alertas cuando supere un umbral de consumo para reaccionar a tiempo. | 2 |
| 22 | HU22 | Alertas de picos energéticos | Como administrador de PYME, quiero recibir alertas automáticas en picos de consumo para identificar anomalías. | 3 |
| 23 | HU23 | Historial de consumo | Como usuario de hogar, quiero ver un historial gráfico de mi consumo energético para analizar mis tendencias. | 3 |
| 24 | HU24 | Historial corporativo avanzado | Como administrador de PYME, quiero generar reportes históricos avanzados para evaluar el impacto de medidas de ahorro. | 5 |
| 25 | HU25 | Comparativa mensual | Como usuario de hogar, quiero comparar mi consumo mensual con meses anteriores para evaluar mi progreso. | 2 |
| 26 | HU26 | Comparativa entre sedes | Como administrador de PYME, quiero comparar el consumo energético entre distintas sedes para detectar ineficiencias. | 3 |
| 27 | HU27 | Notificaciones push | Como usuario de hogar, quiero recibir notificaciones push sobre mi consumo para estar informado en tiempo real. | 2 |
| 28 | HU28 | Notificaciones por correo | Como administrador de PYME, quiero recibir alertas por correo sobre consumos inusuales para actuar oportunamente. | 3 |
| 29 | HU29 | Recomendaciones básicas IA | Como usuario de hogar, quiero recibir recomendaciones simples para ahorrar energía en base a mis datos. | 3 |
| 30 | HU30 | Recomendaciones IA corporativas | Como administrador de PYME, quiero obtener sugerencias de IA sobre cómo reducir costos energéticos en mis operaciones. | 5 |
| 31 | HU31 | Optimización automática IA | Como usuario de hogar, quiero que la IA configure mis dispositivos automáticamente para optimizar mi consumo sin esfuerzo. | 8 |
| 32 | HU32 | Estrategias automáticas IA corporativas | Como administrador de PYME, quiero que la IA ajuste automáticamente el consumo de mi empresa para reducir costos y huella de carbono. | 5 |
| 33 | HU33 | Compatibilidad multiplataforma | Como usuario de hogar, quiero que la aplicación esté disponible en iOS y Android para acceder desde cualquier dispositivo. | 3 |
| 34 | HU34 | Acceso web empresarial | Como administrador de PYME, quiero poder acceder a la plataforma vía web para gestionarla desde mi oficina. | 3 |
| 35 | HU35 | Endpoint de autenticación | Como desarrollador, quiero un endpoint de autenticación basado en JWT para gestionar de forma segura el acceso a la aplicación. | 5 |
| 36 | HU36 | Endpoint de consumo energético | Como desarrollador, quiero exponer un endpoint que devuelva el consumo energético en tiempo real para mostrarlo en la app Angular. | 3 |
| 37 | HU37 | Endpoint de control de dispositivos | Como desarrollador, quiero un endpoint para encender/apagar dispositivos conectados a los actuadores para que el frontend gestione el control remoto. | 5 |
| 38 | HU38 | Endpoint de reportes históricos | Como desarrollador, quiero un endpoint para obtener el historial de consumo energético por rango de fechas para alimentar los reportes de la app. | 3 |
| 39 | HU39 | Endpoint de recomendaciones IA | Como desarrollador, quiero un endpoint que entregue recomendaciones de ahorro energético para que el frontend las muestre de manera personalizada. | 5 |
| 40 | HU40 | Endpoint de optimización automática IA | Como desarrollador, quiero un endpoint que optimice el consumo energético de los dispositivos basándose en los datos analizados por la IA. | 3 |
| 41 | HU41 | Endpoint de alertas | Como desarrollador, quiero un endpoint que envíe alertas a los usuarios cuando superen los umbrales de consumo. | 5 |

# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
#### Branding – PowerSense

#### Brand Overview
**PowerSense** es una plataforma **IoT “verde”** para **hogares y PYMEs** que permite **monitorear y optimizar** el consumo eléctrico en tiempo real. Integra **sensores y actuadores inteligentes** con **IA** para detectar ineficiencias, recomendar acciones y automatizar encendidos/apagados, reduciendo **costos** y **huella de carbono**. Se posiciona como una solución **confiable, moderna y accesible** para Lima y, progresivamente, Sudamérica.

#### Misión
Empoderar a hogares y PYMEs para **gastar menos energía** sin perder confort ni productividad, ofreciendo herramientas simples, basadas en **datos reales**, que conviertan el consumo eléctrico en **ahorros medibles**.

#### Visión
Ser la **plataforma líder en Sudamérica** en **eficiencia energética inteligente**, impulsando ciudades más sostenibles mediante tecnología IoT y analítica clara y accionable.

#### Brand Name
**PowerSense** combina *Power* (energía) y *Sense* (sensar/entender): **medir, comprender y optimizar** el uso de la energía de forma simple y automatizada.

#### Logotipo
![Logo de PowerSense](https://imgur.com/oWeUQ6Y.png)



#### Colores (HEX)

> Paleta orientada a sostenibilidad y claridad de lectura; acentos verdes para acciones clave y **violeta muy claro** para superficies suaves.

![Colores de PowerSense](https://imgur.com/zgbTEmS.png)

### Principales
- **Primary / Verde Power:** `#48AF6A`  
- **CTA / Verde Acción:** `#46AE09`  
- **Base / Blanco:** `#FFFFFF`

### Secundarios & Superficies
- **Superficie Suave (violeta muy claro):** `#E6E9F7`  
- **Verde Suave Acento:** `#DCEED4`  
- **Verde Pastel Acento:** `#C1E4AD`

### Interacción & Links
- **Link / Menú Verde:** `#60B92B`

### Texto
- **Heading / Verde Muy Oscuro:** `#112310` (alt. `#1E301F`)  
- **Copy / Gris Párrafo:** `#616E67` (alt. `#6E7672`)  
- **Texto invertido (sobre CTA/oscuro):** `#FFFFFF`

#### Tipografía

![Tipografía de PowerSense](https://imgur.com/j8Ye9hI.png)

**Familia:** **Inter** (sans-serif), por su legibilidad y neutralidad en interfaces.

### Jerarquías

| Jerarquía             | Tamaño | Altura de línea | Peso     | Uso sugerido |
|-----------------------|:------:|:---------------:|----------|--------------|
| Heading 1             | 48 px  | 60 px           | Bold     | Héroe, métricas clave |
| Heading 2             | 32 px  | 42 px           | Semibold | Secciones |
| Heading 3             | 20 px  | 30 px           | Medium   | Subsecciones, cards |
| Heading 4             | 16 px  | 24 px           | Medium   | Etiquetas, mini-títulos |
| Large Text Bold       | 20 px  | 30 px           | Bold     | KPIs/llamadas |
| Medium Text Regular   | 18 px  | 28 px           | Regular  | Párrafos destacados |
| Normal Text Regular   | 16 px  | 24 px           | Regular  | Párrafo base |
| Small Text Regular    | 14 px  | 20 px           | Regular  | Ayudas, disclaimers |

**Aplicación de color tipográfico**
- Títulos: `#112310`  
- Párrafos: `#616E67`  
- Enlaces: `#60B92B`  
- Texto en CTA/superficies oscuras: `#FFFFFF`



#### Spacing & Layout

Sistema modular **8 px**:
- **Secciones:** 32 px  
- **Padding contenedores:** 24 px  
- **Gap entre controles:** 16 px  
- **Padding interno de tarjetas:** 12 px  

**Superficies recomendadas**
- Fondo principal: `#FFFFFF`  
- Tarjetas / bloques destacados: `#E6E9F7`  
- Secciones alternas: `#DCEED4`, `#C1E4AD`



#### Tono de comunicación
- **Personalidad:** Profesional, cercana y orientada a impacto.  
- **Tono emocional:** Optimista y responsable (ahorro + sostenibilidad).  
- **Lenguaje:** Claro, directo.  
- **Relación con el usuario:** Didáctica y empática, enfatizando **ahorro** y reducción de emisiones.



#### Uso rápido (componentes)

- **Botón primario (CTA):** fondo `#46AE09`, texto `#FFFFFF` (hover: oscurecer 8–12%).  
- **Botón secundario:** borde `#48AF6A`, texto `#48AF6A`, fondo `transparent` (hover: `#DCEED4`).  
- **Card:** fondo `#E6E9F7`, títulos `#112310`, texto `#616E67`.  
- **Links / Nav:** `#60B92B` con subrayado al hover.  
- **Badges / Chips:** fondo `#C1E4AD`, texto `#112310`.


### 4.1.2. Web Style Guidelines.

Para el estilo principal en el cual se va a enfocar la aplicación web y la landing page son:

- Diseño minimalista y colorido La aplicación tendrá un tono minimalista para evitar llenar de información al usuario como excesiva cantidad de elementos en pantalla.

- Imágenes ilustrativas Para mostrar el uso de las imágenes optamos por usar ilustraciones en cambio de las imágenes estilo fotografía, ya que estas encajan perfecto con el estilo minimalista y además de una mayor personalización.

- Elementos intuitivos de interacción Los elementos de nuestra aplicación son intuitivos para brindar una mayor experiencia de usuario. Cabe recalcar que la mayoría de estos elementos estarán resaltados con los colores primarios y secundarios.

- Contraste de colores Para una mayor redacción de la aplicación, tomamos en cuenta el nivel de contraste entre dos o más elementos.

## 4.2. Information Architecture.

### 4.2.1. Organization Systems.

En cuanto al sistema de organización del contenido, se optó el patrón jerárquico (visal hierarchy) para organizar la información de las secciones. El tamaño de las fuentes es crucial para el usuario, donde la información más importante serán desde los textos más grandes hasta los más pequeños.

Por otro lado, se utiliza categorización por audiencia para dirigirnos a postulantes y profesionales de recursos humanos, con secciones específicas para cada uno. Además, se implementa orden cronológico descendente en las entradas de la base de datos, priorizando las más recientes al principio para facilitar la consulta de los usuarios.

### 4.2.2. Labeling Systems.

Para el contenido, se prioriza la reducción de textos para brindar una mejor redacción y legibilidad de estos para los usuarios.

Para el uso de botones se ha optado por un estilo minimalista, donde se usarán los colores primarios como fondo y bordes redondeados.

En el tema de iconos, se emplean los colores creados del sistema de diseño del equipo.

### 4.2.3. SEO Tags and Meta Tags

```html
<head>
    <meta charset="utf-8" />
    <title>PowerSense-LandingPage</title>
    <base href="/" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#4051b5" />
    <link rel="icon" type="image/x-icon" href="favicon.ico" />
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
</head>
```

### 4.2.4. Searching Systems.

#### Estructura de Navegación Principal

La navegación de PowerSense está diseñada para guiar al usuario de forma clara e intuitiva por la landing page, facilitando el acceso a la información más relevante.

##### 1. Navegación de la Landing page 
Sección principal de la página, ubicada en la parte superior. Incluye el logotipo y el menú de navegación que permite moverse rápidamente a las secciones clave.
- **Logo PowerSense** → Enlace a inicio  
- **Menú Principal:**  
  - Inicio → Scroll a sección *Hero*  
  - Cómo Funciona → Scroll a sección *Proceso 4 pasos*  
  - Casos de Éxito → Scroll a *Testimonios y casos*  
  - Planes → Scroll a *Precios y suscripciones*  
  - Contacto → Scroll a *Formulario de contacto*  
  - Sobre Nosotros → Scroll a *Información de empresa*  

##### 2. Navegación de la Web Application

**Aplicación Web:**
- **Menú lateral (sidebar):** Incluye accesos a secciones principales como Dashboard, Explorar, etc.
- **Barra superior:** Muestra íconos de notificaciones, ayuda y perfil de usuario.
- **Breadcrumbs:** Presentes en vistas secundarias para mantener contexto.
- **Componentes interactivos:** Botones, tarjetas, chips y enlaces mantienen consistencia en color y comportamiento.

#### Técnicas de Navegación Implementadas

En esta sección se describen las técnicas que mejoran la experiencia de desplazamiento del usuario dentro de la landing page.

##### 1. Scroll Suave (*Smooth Scrolling*)
Permite que el movimiento entre secciones sea fluido y agradable para el usuario.  
- Transiciones fluidas entre secciones  
- Duración: **300ms** con *easing* personalizado  
- Comportamiento: `scroll-behavior: smooth`  

##### 2. Navegación por Anclas
Cada enlace del menú se conecta con una sección específica de la página mediante identificadores únicos.  
- Cada sección tiene un **ID único** (`#home`, `#how-it-works`, etc.)  
- Los enlaces del header apuntan a secciones específicas  
- Scroll automático al hacer clic en enlaces  

### 4.2.5. Navigation Systems.

#### Searching Systems

PowerSense implementa un sistema de búsqueda sencillo que organiza la información por secciones y categorías, ayudando al usuario a encontrar rápidamente lo que necesita.

##### Sistema de Búsqueda en Landing Page
Describe cómo se facilita la exploración del contenido principal a través de la estructura de la página.  
- **Búsqueda de contenido por secciones**  
  - Navegación por anclas: búsqueda directa de secciones específicas  
  - Scroll automático: lleva al usuario exactamente donde necesita  
  - Filtros visuales: cada sección tiene un propósito específico  

##### Búsqueda de Información
Explica cómo se organiza el acceso a información más detallada, como soporte, precios o políticas.  
- **FAQ** integrado en la sección de contacto  
- **Búsqueda por categorías:**  
  - Precios y Planes  
  - Características Técnicas  
  - Soporte y Ayuda  
  - Información Legal  


## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.

<div style="text-align: center;">
  <img src="https://imgur.com/8uDUf0C.png" width="90%" />
  <img src="https://imgur.com/XA0Gv6i.png" width="90%" />
  <img src="https://imgur.com/rN837sx.png" width="90%" />
  <img src="https://imgur.com/F3JaQ9N.png" width="90%" />
  <img src="https://imgur.com/8i6IjWm.png" width="90%" />
  <img src="https://imgur.com/Ui0y2un.png" width="90%" />

</div>

### 4.3.2. Landing Page Mock-up.
A continuación los Mock ups, estos son los modelos de diseño que se utilizarán en la elaboración del landing page y servirá de modelo y base para la elaboración del landing page. 

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


## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.

Enlace para acceder a los Mockups en Figma: [FIGMA](https://www.figma.com/design/6zsotpbkoOZH0xcz69YyCU/Mock-Upc?node-id=0-1&p=f&t=cClrOXvLgaL6N2Nu-0)

<img src="https://i.imgur.com/kngYX75.png">
<img src="https://i.imgur.com/MnjlvQg.png[/img]">
<img src="https://i.imgur.com/t6p3fhh.png[/img]">
<img src="https://i.imgur.com/wsJ0cxd.png[/img]">
<img src="https://i.imgur.com/QOmePg2.png[/img]">

### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.

<img src="https://i.imgur.com/DdYe8li.png">

### 4.6.2. Software Architecture Container Diagrams.

<img src="https://i.imgur.com/C5K7mpv.png">

### 4.6.3. Software Architecture Components Diagrams.

<img src="https://i.imgur.com/spAmpFw.png">

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

<img src="https://imgur.com/TxJQgtp.png">

### 4.7.2. Class Dictionary.

# Contextos delimitados (Bounded Contexts) – Visión DDD

> Sistema: Plataforma de Optimización Energética / IoT Verde  
> Nota: Se listan **Aggregates**, **Entities**, **Value Objects**, **Servicios de Dominio**, comandos expuestos y restricciones/invariantes clave.


## 1) IdentityContext (Identity & Access)

**Propósito**  
Gestión de identidad, autenticación y perfil del usuario; dueño lógico de `UserId`.

**Aggregate Root**
- **User**
  - Campos: `UserId id`, `Email email`, `Password password`, `UserType type`, `UserProfile profile`, `List<Device> devices`
  - Comandos: `register()`, `login()`, `updateProfile()`, `addDevice()`
  - Invariantes:
    - `Email` debe ser válido/único.
    - `Password` almacenado solo como `hashedValue`.
    - Un `Device` añadido debe pertenecer al `ownerId = User.id`.

**Entities**
- *(No adicionales dentro del aggregate `User`, los dispositivos pertenecen al MonitoringContext; aquí solo se referencia la colección para ownership lógico.)*

**Value Objects**
- **UserProfile**: `name`, `List<ConsumptionHabit> habits`, `NotificationPreferences preferences`
- **Email**: `value` (+ `validate()`)
- **Password**: `hashedValue` (+ `encrypt()`, `verify()`)

**Integraciones / Colaboraciones**
- Publica `UserId` a otros contextos (Monitoring, Reporting, Alert, AI, Enterprise).
- Usa `AuthenticationService` (servicio de dominio compartido).


## 2) MonitoringContext (Energy Monitoring)

**Propósito**  
Registro de consumo energético por usuario y por dispositivo; control operativo de dispositivos y sus horarios.

**Aggregate Root**
- **EnergyConsumption**
  - Campos: `ConsumptionId id`, `UserId userId`, `DateTime timestamp`, `Energy value`, `List<DeviceConsumption> deviceConsumptions`
  - Comandos: `recordConsumption()`, `getTotal()`
  - Invariantes:
    - `timestamp` es monotónico por `ConsumptionId`.
    - `value.kWh` ≥ 0.
    - Cada `DeviceConsumption.measuredAt` ∈ [periodo válido] y `deviceId` pertenece al `userId`.

**Entities**
- **Device**
  - Campos: `DeviceId id`, `UserId ownerId`, `name`, `DeviceType type`, `Location location`, `DeviceStatus status`, `Schedule schedule`
  - Comandos: `turnOn()`, `turnOff()`, `setSchedule()`
  - Invariantes: `ownerId` ≡ `UserId` existente; `Schedule` no solapa tramos inválidos.
- **Schedule** *(modelado como VO en el diagrama, se maneja como objeto inmutable dentro de Device)*

**Value Objects**
- **DeviceConsumption**: `deviceId`, `Energy consumption`, `DateTime measuredAt`
- **Energy**: `double kWh`, `Currency estimatedCost` (+ `add()`, `compareTo()`)
- **Schedule**: `startTime`, `endTime`, `List<DayOfWeek> days` (+ `isActive()`)

**Integraciones / Colaboraciones**
- Consume `UserId` del IdentityContext.
- Colabora con `ConsumptionCalculationService` para agregaciones por dispositivo y periodo.

## 3) ReportingContext (Reporting)

**Propósito**  
Generación de reportes, historiales y comparaciones de consumo/costo por periodo.

**Aggregate Root**
- **Report**
  - Campos: `ReportId id`, `UserId userId`, `ReportType type`, `DateRange period`, `ReportData data`, `DateTime generatedAt`
  - Comandos: `generate()`, `export()`
  - Invariantes: `period` válido (`start ≤ end`); `data` coherente con fuentes de Monitoring.

**Entities**
- **ConsumptionHistory**
  - Campos: `HistoryId id`, `UserId userId`, `List<ConsumptionRecord> records`
  - Comandos: `getByDateRange()`, `compare()`

**Value Objects**
- **ConsumptionRecord**: `DateTime date`, `Energy consumption`, `Currency cost`
- **Comparison**: `Energy previousPeriod`, `Energy currentPeriod`, `Percentage variance` (+ `calculate()`)

**Integraciones / Colaboraciones**
- Lee consumos consolidados del MonitoringContext.
- Expone datos para AlertContext (tendencias) y AIContext (features para recomendaciones).


## 4) AlertContext (Alerts & Notifications)

**Propósito**  
Definir umbrales, evaluar excedentes y notificar al usuario por canales configurados.

**Aggregate Root**
- **Alert**
  - Campos: `AlertId id`, `UserId userId`, `AlertType type`, `message`, `AlertSeverity severity`, `DateTime triggeredAt`, `bool isRead`
  - Comandos: `trigger()`, `markAsRead()`
  - Invariantes: cada `Alert` referencia un `Threshold` o condición válida.

**Entities**
- **Threshold**
  - Campos: `ThresholdId id`, `UserId userId`, `Energy limit`, `ThresholdType type`
  - Comandos: `isExceeded()`
- **Notification**
  - Campos: `NotificationId id`, `AlertId alertId`, `NotificationChannel channel`, `NotificationStatus status`
  - Comandos: `send()`

**Value Objects**
- *(Usa `Energy` desde MonitoringContext como VO compartido conceptual — se recomienda anticorrupción si difieren unidades/formato.)*

**Integraciones / Colaboraciones**
- Llama a `AlertService` para `checkThresholds()`, `triggerAlert()`, `sendNotification()`.
- Consume métricas del MonitoringContext y preferencias de `UserProfile` (IdentityContext).


## 5) AIContext (AI Recommendations)

**Propósito**  
Extracción de patrones de consumo y emisión de recomendaciones y automatizaciones de ahorro.

**Aggregate Root**
- **Recommendation**
  - Campos: `RecommendationId id`, `UserId userId`, `description`, `RecommendationType type`, `Energy potentialSaving`, `DateTime createdAt`, `RecommendationStatus status`
  - Comandos: `apply()`, `dismiss()`
  - Invariantes: `potentialSaving.kWh` ≥ 0; `status` ∈ {Proposed, Applied, Dismissed}.

**Entities**
- **AIStrategy**
  - Campos: `StrategyId id`, `UserId userId`, `List<OptimizationRule> rules`, `bool isActive`
  - Comandos: `activate()`, `deactivate()`, `optimize()`

**Value Objects**
- **OptimizationRule**: `Condition condition`, `Action action`, `Priority priority`

**Integraciones / Colaboraciones**
- Usa `RecommendationEngine` para `analyzePatterns()` y `generateRecommendations()`.
- Lee histórico/series de Reporting y eventos/estados de Monitoring.
- Puede coordinar con `Device.setSchedule()` (Monitoring) al aplicar acciones.


## 6) EnterpriseContext (Empresa / Multisede)

**Propósito**  
Modelo organizacional para clientes corporativos: empresas, sedes, áreas y su consumo agregado.

**Aggregate Root**
- **Company**
  - Campos: `CompanyId id`, `name`, `TaxId taxId`, `List<Branch> branches`, `List<Employee> employees`
  - Comandos: `addBranch()`, `addEmployee()`
  - Invariantes: `TaxId` válido/único; cada `Branch.companyId` = `Company.id`.

**Entities**
- **Branch**
  - Campos: `BranchId id`, `CompanyId companyId`, `name`, `Location location`, `List<Area> areas`
  - Comandos: `compareConsumption()` (consolidación por sedes)
- **Area**
  - Campos: `AreaId id`, `BranchId branchId`, `name`, `List<Device> devices`
  - Comandos: `getConsumption()` (consulta/agregación)
- **Employee**
  - Campos: `EmployeeId id`, `CompanyId companyId`, `name`, `Role role`, `List<Permission> permissions`

**Value Objects**
- *(Reutiliza `Location`; permisos/roles pueden modelarse como VO según políticas.)*

**Integraciones / Colaboraciones**
- Se apoya en Monitoring para consumo por `Device` y agregaciones por `Area/Branch/Company`.
- Puede usar Reporting para reportes corporativos y comparativas entre áreas/sedes.


## 7) Servicios de Dominio (Cross-Context)

> No constituyen bounded contexts por sí mismos; implementan lógica de dominio reusable/orquestación.

- **AuthenticationService**
  - `authenticate(email, password)`, `generateToken()`, `validateToken()`
  - Colabora con IdentityContext; expone tokenización al resto.
- **ConsumptionCalculationService**
  - `calculateTotal()`, `calculateByDevice()`, `calculateByPeriod()`
  - Sirve a Monitoring/Reporting para agregaciones consistentes.
- **RecommendationEngine**
  - `analyzePatterns()`, `generateRecommendations()`, `optimizeAutomatically()`
  - Propio del AIContext; puede aplicar acciones en Monitoring (schedules).
- **AlertService**
  - `checkThresholds()`, `triggerAlert()`, `sendNotification()`
  - Orquesta reglas de Threshold + canales de `Notification`.


## Relaciones clave entre Contextos

- **Identity → todos**: `UserId` como identidad transversal.
- **Monitoring → Reporting**: fuente de series/consumos para reportes e históricos.
- **Monitoring → Alert**: métricas en tiempo real para evaluar `Threshold`.
- **Reporting → AI**: features (tendencias, variance) para recomendaciones.
- **AI → Monitoring**: aplicación de `OptimizationRule` en `Device/Schedule`.
- **Enterprise → Monitoring/Reporting**: agregaciones por `Area/Branch/Company`.


## Decisiones / Recomendaciones de diseño

- **VO compartidos**: `Energy`, `Location`, `DateRange` deben tener contratos estables; usar **anticorruption layer** si cambian por contexto.
- **Consistencia**: comandos que afectan múltiples contextos (p.ej., `apply()` en AI que programa dispositivos) deberían emitirse como **eventos de dominio** y consumirse asincrónicamente.
- **Seguridad**: `NotificationPreferences` y `permissions` deben consultarse antes de `sendNotification()` o exportaciones en Reporting.
- **Escalabilidad**: `EnergyConsumption` puede particionarse por `userId` y `timestamp`; `DeviceConsumption` como stream append-only.



## 4.8. Database Design.
### 4.8.1. Database Diagram.
![Database Diagram](https://imgur.com/PhPuPGs.png)
# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### Diseño UX/UI del Producto

**Figma**: Herramienta digital utilizada para crear prototipos y diseños de interfaces. En nuestro proyecto, se empleará para desarrollar los Wireframes y el Wireflow en la página de aterrizaje, así como para el diseño tanto de la WebApp como de la MobileApp.  
Ruta referencial: [https://www.figma.com/](https://www.figma.com/)

## Desarrollo de Software

* **Visual Studio Code**: Entorno de desarrollo y compilación de código, elegido por el equipo debido a su familiaridad con la herramienta. Esta IDE es de fácil acceso, ofrece múltiples configuraciones, la opción de añadir extensiones y soporta varios lenguajes de programación.  
  Ruta referencial: [https://code.visualstudio.com/](https://code.visualstudio.com/)

* **HTML5**: Lenguaje de marcado utilizado para desarrollar el código de las etiquetas en páginas web.  
  Ruta referencial: [https://www.w3schools.com/html/html5_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)

* **CSS**: Hojas de estilo en cascada que gestionan el diseño de las páginas web, siempre en conjunto con HTML.  
  Ruta referencial: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)

* **Javascript**: Lenguaje de programación interpretado y orientado a objetos. Se usará para crear la interfaz de usuario de la aplicación.  
  Ruta referencial: [https://developer.mozilla.org/es/docs/Web/JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)

## Despliegue del Software

**Netlify**: Plataforma para la implementación y despliegue de aplicaciones web. Facilita la publicación de sitios web directamente desde el repositorio y permite integrar procesos de CI/CD.  
Ruta referencial: [https://www.netlify.com/](https://www.netlify.com/)

## Documentación del Software y Gestión del Proyecto

**Github**: Plataforma en la nube para alojar los repositorios de código del proyecto. Facilita la colaboración en tiempo real y permite revisar las contribuciones de los miembros del equipo. Accesible a través de navegadores web.  
Ruta referencial: [https://github.com/](https://github.com/)

### 5.1.2. Source Code Management
Para el desarrollo de nuestro proyecto, adoptaremos el flujo de trabajo propuesto por el modelo GitFlow. Utilizaremos GitHub como plataforma de control de versiones. A continuación, se explicará cómo se implementará GitFlow en el repositorio, y se proporcionarán los enlaces de los repositorios de GitHub para cada componente: Landing Page, Web Services y Frontend Web Applications.

## Repositorio en GitHub

* Repositorio: [Repositorio](https://github.com/orgs/1ASI0729-2520-7344-G3-PowerSense/repositories)
* Landing Page: [Landing Page](https://rococo-sprite-66ce8b.netlify.app/)

## Flujo de trabajo GitFlow

El flujo de trabajo elegido para el desarrollo del proyecto sigue el modelo propuesto por Vincent Driessen en su artículo "A Successful Git Branching Model".

## Estructura de Ramas (Branches)

  1. **Master Branch (Rama Principal):** Esta rama está destinada a la producción de la aplicación. Todos los cambios deben ser aprobados por un miembro del equipo para asegurar que solo se integren modificaciones verificadas.
  2. **HotFix Branch:** Aquí se gestionan las correcciones de errores urgentes. Una vez que se soluciona un problema, los cambios se despliegan nuevamente en la rama principal y también se integran en la rama de desarrollo.
  3. **Develop Branch:** Esta rama es donde se integran de manera continua las nuevas características o mejoras en el proyecto.
  4. **Feature Branch:** Cada nueva funcionalidad es desarrollada en esta rama. Cuando se completa una funcionalidad, se fusiona con la rama de desarrollo para su integración.
  5. **Release Branch:** Esta rama se usa para mantener una versión estable y lista para ser liberada, basada en el código de la rama de desarrollo.

### 5.1.3. Source Code Style Guide & Conventions
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

### 5.1.4. Software Deployment Configuration
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

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
En la siguiente sección se presentará el sprint #1, que incluye la versión inicial del proyecto, destacando la estructura, el diseño y los resultados obtenidos de la página de aterrizaje.
#### 5.2.1.1. Sprint Planning 1
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

#### 5.2.1.2. Aspect Leaders and Collaborators.
| **Team Member (Last Name, First Name)** | **GitHub Username** | **Capítulo I: Introducción (L/C)** | **Capítulo II: Requirements Elicitation & Analysis (L/C)** | **Capítulo III: Requirements Specification (L/C)** | **Capítulo IV: Product Design (L/C)** | **Capítulo V: Product Implementation, Validation & Deployment (L/C)** |
| --------------------------------------- | ------------------- | ---------------------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------- |
| **Irving Allca**                   | noway-evitern17        | **L**                              | **C**                                                      | **C**                                              | **C**                                 | **C**                                                                 |
| **Juan Pastor Napa**          | ElKiwi1271        | **C**                              | **L**                                                      | **C**                                              | **C**                                 | **C**                                                                 |
| **Andy Arturo Nuñez Soto**          |arturo-ns           | **C**                              | **C**                                                      | **L**                                              | **C**                                 | **C**                                                                 |
| **Anderson Gonza Morales**                        | Ander-U         | **C**                              | **C**                                                      | **C**                                              | **L**                                 | **C**                                                                 |
| **Sebastian Escobar Palomino**                    | sebasepe               | **C**                              | **C**                                                      | **C**                                              | **C**                                 | **L**                                                                 |
#### 5.2.1.3. Sprint Backlog 1
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

#### 5.2.1.4. Development Evidence for Sprint Review

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
#### 5.2.1.5. Execution Evidence for Sprint Review
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

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
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


#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Se empleó Netlify para publicar la landing page, lo que facilitó el despliegue del sitio. A continuación, se proporciona el enlace a la landing page: [Landing Page](https://rococo-sprite-66ce8b.netlify.app/)

<div style="text-align: center;">
  <img src="https://i.imgur.com/krnAWFe.png" width="90%" />
</div>

#### 5.2.1.8. Team Collaboration Insights during Sprint
Para este proyecto se usaron herramientas como WebStorm y Git. La landing page se dividió en secciones asignadas a cada miembro del equipo, y al final, un integrante integró todas las contribuciones para consolidar el producto final

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZrAz2Ls.png" width="90%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZlLWjTf.png" width="90%" />
</div>

### 5.2.2. Sprint 2
En la siguiente sección se presentará el sprint #2, que incluye la versión inicial del proyecto, destacando la estructura, el diseño y los resultados obtenidos de la página de aterrizaje.

#### 5.2.2.1. Sprint Planning 2

#### 5.2.2.2. Aspect Leaders and Collaborators.

#### 5.2.2.3. Sprint Backlog 2

#### 5.2.2.4. Development Evidence for Sprint Review

#### 5.2.2.5. Execution Evidence for Sprint Review

#### 5.2.2.6. Services Documentation Evidence for Sprint Review


#### 5.2.2.7. Software Deployment Evidence for Sprint Review

#### 5.2.2.8. Team Collaboration Insights during Sprint


#### Bibliografia


#### Anexo
1. **Despliegue del Landing Page:** [Landing Page](https://rococo-sprite-66ce8b.netlify.app/)
2. **Link de la organización :** [Organización](https://github.com/1ASI0729-2520-7344-G3-PowerSense)
5. **Link del repositorio del Reporte :** [Repositorio Reporte](https://github.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Report)
6. **Link del repositorio de la Landing Page :** [Repositorio LandingPage](https://github.com/1ASI0729-2520-7344-G3-PowerSense/PowerSense-Landing-Page)
9. **Figma con los User Flow Diagrams, wireframes y mockups de la landing page:** [Figma](https://www.figma.com/design/6zsotpbkoOZH0xcz69YyCU/Mock-Upc?node-id=0-1&t=svzqcosOPQg0VdcE-1)
13. **2.2.2. Registro de entrevistas:** [Entrevistas](https://www.youtube.com/watch?v=mx5nMZDKNeg)
15. **Video de exposición:**[ Video de la exposicion]()
