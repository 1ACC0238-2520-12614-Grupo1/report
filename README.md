<div align="center">
<img src="img/logo.jpg" alt="Logo de la Universidad" width="150"/>

# **Universidad Peruana de Ciencias Aplicadas**
## **Ingeniería de Software**

**Periodo:** 2025-20  
**Curso:** 1ACC0238 – Aplicaciones para Dispositivos Móviles  
**NRC:** 1827  
**Docente:** David Gerardo Quevedo Velasco  

---

## **Informe del Trabajo Final**

**Startup:** FuelTrack  
**Producto:** FuelTrack Pro  

---
### **Integrantes (orden alfabético):**

U20211584 – Angulo Abad, Juan Carlos

U20211837 – Choque, Oliver Jonseck

U20213278 – Durand Vega, Gianfranco

U20213322 – Mio Mejía, Andy Alejandro

U20214011 – Murillo, Mathias Javier

**Octubre 2025**
</div>





## Registro de Versiones del Informe

| **Versión** | **Fecha** | **Autores** | **Descripción de Modificación** |
|-------------|-----------|-------------|----------------------------------|
| **TB1** | 26/04/2025 | - Juan Carlos Alvarado De La Cruz <br> - Gianfranco Jared Durand Vega <br> - **Bryan Ronald Espejo Gamarra** <br> - Jhon Danny Guerrero Vasquez <br> - Renzo Andres Luque Minaya | Se incluyeron los siguientes capítulos y artefactos:<br>• Estructura del informe<br>• Capítulo I: Presentación<br>• Capítulo II: Requirements Development & Software Solution Design<br>• Capítulo III: Solution UI/UX Design<br>• Capítulo IV: Product Implementation & Validation (borrador)<br>• Configuración inicial del repositorio y del Landing Page<br>• Aplicación de GitFlow y convenciones de commits |
| **TP1** | Semana 7 (2025) | - Juan Carlos Alvarado De La Cruz <br> - Gianfranco Jared Durand Vega <br> - **Bryan Ronald Espejo Gamarra** <br> - Jhon Danny Guerrero Vasquez <br> - Renzo Andres Luque Minaya | Actualizaciones y entregables del Stage Review:<br>• Registro de Versiones, Collaboration Insights y Student Outcome actualizados<br>• Corrección y mejora de artefactos previos (diagramas, prototipos y especificaciones)<br>• **Landing Page desplegada (v0.1)**<br>• **Backend v0.1**: estructura base, endpoints iniciales y pipeline de despliegue<br>• **App móvil nativa v0.1 (Android)**: login, dashboard y listado de pedidos (demo)<br>• Cap. V: Solution UI/UX Design (prototipos validados); Cap. VI: Product Implementation, Validation & Deployment (secciones 6.1 y 6.2.1 Sprint 1)<br>• Evidencias de Sprint 1: Planning, Backlog, Development/Execution/Services Docs, Deployment y Team Collaboration<br>• Avance de Conclusiones, Bibliografía y Anexos |
| **TB2** | Semana 12 (2025) | - Juan Carlos Alvarado De La Cruz <br> - Gianfranco Jared Durand Vega <br> - **Bryan Ronald Espejo Gamarra** <br> - Jhon Danny Guerrero Vasquez <br> - Renzo Andres Luque Minaya | Actualizaciones del Sprint Review 2 y ampliaciones:<br>• Registro de Versiones, Collaboration Insights y Student Outcome actualizados<br>• Refactor y mejora de artefactos previos (DDD, UI flows, casos de uso)<br>• **Landing Page v0.2** (mejoras de contenido y métricas)<br>• **Backend v0.2**: autenticación **JWT**, servicios de órdenes/proveedores y ajustes de despliegue CI/CD<br>• **App nativa v0.2**: mejoras en UX, creación/seguimiento de pedidos y manejo de estados<br>• **Primera versión cross-platform (Flutter) v0.1**: estructura, navegación base y vistas iniciales<br>• Videos (primer corte): **Validación de la aplicación**, **About-the-Product**, **About-the-Team**<br>• Cap. 6.2.2 Sprint 2: Planning, Backlog, Development, Testing Suite, Execution, Services Docs, Deployment y Team Collaboration<br>• Sección 6.3 Validación: diseño de entrevistas, registro de hallazgos y evaluación heurística<br>• Avance de Conclusiones, Bibliografía y Anexos |
| **TF1** | --/--/2025 | - Juan Carlos Alvarado De La Cruz <br> - Gianfranco Jared Durand Vega <br> - **Bryan Ronald Espejo Gamarra** <br> - Jhon Danny Guerrero Vasquez <br> - Renzo Andres Luque Minaya | *(Pendiente de completar)* |



<br><br><br><br><br>
<p>&nbsp;</p>
<p>&nbsp;</p>
<br><br>
<br><br><br><br><br>
<p>&nbsp;</p>
<p>&nbsp;</p>
<br><br>
<br><br><br><br><br>
<p>&nbsp;</p>
<p>&nbsp;</p>







## Project Report Collaboration Insights

Este informe ha sido desarrollado de forma colaborativa mediante GitHub, aplicando GitFlow y Conventional Commits. Cada integrante del equipo ha contribuido mediante ramas independientes, commits individuales y revisiones de Pull Requests.

---

###  Participación por miembro (commits realizados)

A continuación, se muestra un gráfico de barras con la cantidad de commits realizados por cada integrante del equipo:


---

### Evolución temporal de commits

El siguiente gráfico muestra una línea de tiempo con la evolución de los commits realizados por todos los miembros:


<br><br><br><br><br>
<p>&nbsp;</p>
<p>&nbsp;</p>
<br><br>
<br><br><br><br><br>
<p>&nbsp;</p>


---


## Contenido

- [Carátula](#carátula)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Impact Mapping](#33-impact-mapping)
  - [3.4 Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1 EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2 Context Mapping](#412-context-mapping)
    - [4.1.3 Software Architecture](#413-software-architecture)
      - [4.1.3.1 Context Level Diagrams](#4131-context-level-diagrams)
      - [4.1.3.2 Container Level Diagrams](#4132-container-level-diagrams)
      - [4.1.3.3 Deployment Diagrams](#4133-deployment-diagrams)
  - [4.2 Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X Bounded Context: \<Bounded Context Name\>](#42x-bounded-context-bounded-context-name)
      - [4.2.X.1 Domain Layer](#42x1-domain-layer)
      - [4.2.X.2 Interface Layer](#42x2-interface-layer)
      - [4.2.X.3 Application Layer](#42x3-application-layer)
      - [4.2.X.4 Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5 Component Level Diagrams](#42x5-component-level-diagrams)
      - [4.2.X.6 Code Level Diagrams](#42x6-code-level-diagrams)
      - [4.2.X.6.1 Domain Layer Class Diagrams](#42x61-domain-layer-class-diagrams)
      - [4.2.X.6.2 Database Design Diagram](#42x62-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  - [5.1 Product Design](#51-product-design)
    - [5.1.1 Style Guidelines](#511-style-guidelines)
      - [5.1.1.1 General Style Guidelines](#5111-general-style-guidelines)
    - [5.1.2 Information Architecture](#512-information-architecture)
      - [5.1.2.1 Organization Systems](#5121-organization-systems)
      - [5.1.2.2 Labelling Systems](#5122-labelling-systems)
      - [5.1.2.3 SEO Tags and Meta Tags](#5123-seo-tags-and-meta-tags)
      - [5.1.2.4 Searching Systems](#5124-searching-systems)
      - [5.1.2.5 Navigation Systems](#5125-navigation-systems)
    - [5.1.3 Landing Page UI Design](#513-landing-page-ui-design)
      - [5.1.3.1 Landing Page Wireframe](#5131-landing-page-wireframe)
      - [5.1.3.2 Landing Page Mock-up](#5132-landing-page-mock-up)
    - [5.1.4 Mobile Applications UX/UI Design](#514-mobile-applications-uxui-design)
      - [5.1.4.1 Mobile Applications Wireframes](#5141-mobile-applications-wireframes)
      - [5.1.4.2 Mobile Applications Wireflow Diagrams](#5142-mobile-applications-wireflow-diagrams)
      - [5.1.4.3 Mobile Applications Mock-ups](#5143-mobile-applications-mock-ups)
      - [5.1.4.4 Mobile Applications User Flow Diagrams](#5144-mobile-applications-user-flow-diagrams)
      - [5.1.4.5 Mobile Applications Prototyping](#5145-mobile-applications-prototyping)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1 Software Configuration Management](#61-software-configuration-management)
    - [6.1.1 Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2 Source Code Management](#612-source-code-management)
    - [6.1.3 Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
    - [6.1.4 Software Deployment Configuration](#614-software-deployment-configuration)
  - [6.2 Landing Page & Mobile Application Implementation](#62-landing-page--mobile-application-implementation)
    - [6.2.X Sprint n](#62x-sprint-n)
      - [6.2.X.1 Sprint Planning n](#62x1-sprint-planning-n)
      - [6.2.X.2 Sprint Backlog n](#62x2-sprint-backlog-n)
      - [6.2.X.3 Development Evidence for Sprint Review](#62x3-development-evidence-for-sprint-review)
      - [6.2.X.4 Testing Suite Evidence for Sprint Review](#62x4-testing-suite-evidence-for-sprint-review)
      - [6.2.X.5 Execution Evidence for Sprint Review](#62x5-execution-evidence-for-sprint-review)
      - [6.2.X.6 Services Documentation Evidence for Sprint Review](#62x6-services-documentation-evidence-for-sprint-review)
      - [6.2.X.7 Software Deployment Evidence for Sprint Review](#62x7-software-deployment-evidence-for-sprint-review)
      - [6.2.X.8 Team Collaboration Insights during Sprint](#62x8-team-collaboration-insights-during-sprint)
  - [6.3 Validation Interviews](#63-validation-interviews)
    - [6.3.1 Diseño de Entrevistas](#631-diseño-de-entrevistas)
    - [6.3.2 Registro de Entrevistas](#632-registro-de-entrevistas)
    - [6.3.3 Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
  - [6.4 Video About-the-Product](#64-video-about-the-product)
- [Conclusiones](#conclusiones)
  - Conclusiones y recomendaciones.
- [Video About-the-team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
<br><br>
<br><br><br><br><br>


## Student Outcome

> *Cada participante del equipo debe colaborar a fin de que se redacte como grupo los sustentos y evidencias de las actividades realizadas en el trabajo final que han ayudado a desarrollar cómo las dimensiones del student outcome. Por ello en esta sección debe quedar descrito por escrito, la relación entre el outcome, sus dimensiones y el trabajo que han realizado.*

| **Criterio Específico** | **Acciones Realizadas** | **Conclusiones**  |
|---|---|---|
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software** | **Juan Carlos Alvarado De La Cruz**<br>TB1: Coordinó la organización inicial del informe, asegurando que se incluyeran las secciones obligatorias y revisó la estructura base del documento.<br><br>**Gianfranco Jared Durand Vega**<br>TB1: Colaboró en la elaboración de la sección de entrevistas y análisis de la problemática inicial, aplicando conceptos revisados en clase.<br><br>**Bryan Ronald Espejo Gamarra**<br>TB1: Coordinó el desarrollo del Landing Page, implementando GitFlow y convenciones de commits en el repositorio.<br><br>**Jhon Danny Guerrero Vasquez**<br>TB1: Apoyó en la construcción del capítulo de presentación, redactando perfiles de los integrantes y la descripción de la startup.<br><br>**Renzo Andres Luque Minaya**<br>TB1: Participó en el diseño de User Personas y en el análisis de los requerimientos iniciales, reforzando los conceptos de UX y Needfinding. <br><br>TP1: *(Pendiente de completar)*<br>TB2: *(Pendiente de completar)*<br>TF1: *(Pendiente de completar)* | La aplicación de conceptos vistos en clase permitió establecer una base sólida en la estructuración del informe y el desarrollo del proyecto. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software** | **Juan Carlos Alvarado De La Cruz**<br>TB1: Investigó y propuso referencias adicionales para reforzar la parte de antecedentes y problemática.<br><br>**Gianfranco Jared Durand Vega**<br>TB1: Complementó la redacción del Lean UX Process con ejemplos investigados de soluciones similares.<br><br>**Bryan Ronald Espejo Gamarra**<br>TB1: Aplicó conocimientos previos de control de versiones y metodologías ágiles para estructurar el repositorio y coordinar al equipo.<br><br>**Jhon Danny Guerrero Vasquez**<br>TB1: Investigó sobre experiencias de usuario y aportó mejoras en la sección de Empathy Mapping.<br><br>**Renzo Andres Luque Minaya**<br>TB1: Se capacitó en herramientas de diseño (Figma/Lucidchart) y aplicó lo aprendido en la construcción de los primeros artefactos visuales. <br><br>TP1: *(Pendiente de completar)*<br>TB2: *(Pendiente de completar)*<br>TF1: *(Pendiente de completar)* | El aprendizaje autónomo y continuo de cada miembro permitió enriquecer la propuesta inicial y mejorar la calidad del entregable. |

---

## Capítulo I: Introducción

### 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

**FuelTrack** es una startup innovadora dedicada a la optimización de la gestión de pedidos de combustible entre empresas solicitantes y proveedores. Fundada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), nuestra propuesta se centra en la digitalización de un sector tradicionalmente dependiente de procesos manuales, brindando una solución tecnológica que garantiza eficiencia, transparencia y un control más riguroso de las operaciones.

**Misión**: Nuestra misión es desarrollar soluciones tecnológicas avanzadas que transformen la gestión de pedidos de combustible, eliminando los métodos informales y reduciendo el margen de error, mediante una plataforma web intuitiva y accesible.

**Visión**: Nuestra visión es posicionarnos como líderes en la digitalización del sector energético, ofreciendo a las empresas una herramienta que facilite una gestión más eficiente, segura y sostenible, contribuyendo al progreso tecnológico y a la mejora de la competitividad del sector.

---
#### 1.1.2 Perfiles de integrantes del equipo

| Foto                                          | Nombre completo               | Código     | Carrera                | Habilidades técnicas y rol                                   |
|-----------------------------------------------|-------------------------------|------------|------------------------|--------------------------------------------------------------|
| ![Juan Carlos](img/foto_juan.png)             | Juan Carlos Alvarado De La Cruz | U202300101 | Ingeniería de Software | Desarrollo Backend, Gestión de APIs RESTful, Arquitectura DDD |
| ![Gianfranco Durand](img/foto_gianfranco.png) | Gianfranco Jared Durand Vega    | U202300102 | Ingeniería de Software | Desarrollo Frontend (Vue/React), UI/UX, Integración de servicios externos |
| ![Bryan Espejo](img/foto_bryan.png)           | Bryan Ronald Espejo Gamarra     | U202213278 | Ingeniería de Software | Backend, Base de Datos, DevOps, Coordinación técnica del proyecto |
| ![Jhon Guerrero](img/foto_jhon.png)           | Jhon Danny Guerrero Vasquez     | U202300103 | Ingeniería de Software | Desarrollo Móvil Nativo (Kotlin/Swift), Testing y QA          |
| ![Renzo Luque](img/foto_renzo.png)            | Renzo Andres Luque Minaya       | U20221C275 | Ingeniería de Software | Desarrollo Frontend, Cloud Deployment, Seguridad y Autenticación |


### 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

**Descripción del problema**  
El sector de distribución de combustibles enfrenta serias ineficiencias debido a la dependencia de métodos informales como llamadas telefónicas, correos electrónicos y aplicaciones de mensajería para gestionar los pedidos de combustible. Estos métodos generan desorganización, errores y falta de visibilidad en tiempo real, lo que afecta la eficiencia operativa y la relación con los clientes.

**Técnica 5W+2H**

- **What? (¿Qué?)**  
  La problemática principal es la falta de un sistema centralizado y digital para gestionar los pedidos de combustible, lo que genera errores humanos, duplicación de esfuerzos y retrasos en las entregas.

- **When? (¿Cuándo?)**  
  El problema se presenta constantemente en el proceso de gestión de pedidos, especialmente cuando hay un alto volumen de solicitudes o múltiples pedidos a coordinar.

- **Where? (¿Dónde?)**  
  El problema ocurre en empresas solicitantes de combustible y proveedores, tanto en áreas urbanas como rurales, donde la infraestructura digital aún no está optimizada.

- **Who? (¿Quién?)**  
  Los principales afectados son las empresas solicitantes (medianas y grandes), los proveedores de combustible y los encargados de la logística y gestión de pedidos.

- **Why? (¿Por qué?)**  
  El problema radica en la falta de integración entre los métodos actuales de gestión (como correos y aplicaciones de mensajería), que dificultan un control centralizado y preciso de los pedidos.

- **How? (¿Cómo?)**  
  Los procesos actuales son desorganizados, utilizando diversas plataformas desconectadas, lo que impide tener un flujo de trabajo eficiente y controlado.

- **How Much? (¿Cuánto?)**  
  La magnitud del problema es considerable, pues cada día se pierden horas valiosas debido a la ineficiencia y los errores, lo que incrementa los costos operativos y puede generar pérdidas económicas significativas.

---


#### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

FuelTrack es una plataforma que digitaliza y centraliza la gestión de pedidos de combustible entre empresas solicitantes y proveedores, reemplazando prácticas informales (llamadas, correos y mensajería) por un flujo único con trazabilidad en tiempo real.

En el mercado de combustibles predominan canales desorganizados y no integrados, lo que genera errores en los pedidos, retrasos en las entregas y retrabajo. La ausencia de un sistema centralizado disminuye la eficiencia operativa de los proveedores y deteriora la satisfacción del cliente.

Ante una demanda creciente por logística ágil y confiable, se requiere una plataforma que estandarice, automatice y compacte la gestión de pedidos para reducir pérdidas operativas y mejorar la experiencia del cliente.

¿Cómo podríamos diseñar una solución digital que centralice y automatice la gestión de pedidos de combustible, integrando a proveedores y solicitantes en una misma plataforma, para disminuir errores y elevar la eficiencia operativa?

#### 1.2.2.2 Lean UX Assumptions

Business Assumptions

- Las empresas proveedoras tienen en la adopción de nuevas tecnologías para automatizar multiples procesos de gestión con el fin de tener un servicio más eficiente y reducir el número de operadores comerciales que necesitan.   
- Las empresas están buscando formas de reducir errores y retrasos logísticos para optimizar sus costos operativos.  
- Los proveedores estan dispuestos a invertir para mejorar su nivel de servicio y aumentar su competitividad en el mercado.  
- Las empresas usuarias apreciarán tener un mayor control de sus órdenes y ser capaces de seguirlas en una plataforma centralizada.  
- La dificil trazabilidad de los pedidos y la posibilidad de fallas en la comunicación hace que dejar los métodos informales sea una necesidad crítica para el sector en general.

---

User Assumptions

**¿Quién es el usuario?**  
Los usuarios principales serían los encargados logísticos de los proovedores y las empresas compradoras de combustible.

**¿Dónde encaja nuestro producto en su trabajo o vida?**  
FuelTracks encajaría en el día a día de los usuarios como una plataforma de gestión centralizada, que ayudaría a coordinar, rastrear y organizar pedidos de combustible de forma confiable. Reemplazando así los sistemas dispersos que se utilizan hoy en día.

**¿Qué problemas tiene nuestro producto que resolver?**  
FuelTracks debe resolver la desorganización causada por métodos informales de venta, reducir errores humanos y mejorar la experiencia del cliente.

**¿Cuándo y cómo es nuestro producto usado?**  
Será utilizado diariamente por solicitantes y los proveedores por igual. Por el lado de los usuarios solicitantes, usarán la plataforma para registrar y monitorear pedidos de combustible, y por el lado de proveedores para gestionar la recepción, programación y entrega de dichos pedidos.

**¿Qué características son importantes?**  
El seguimiento de pedidos en tiempo real, actualizaciones de estado mediante notificiaciones, historial de entregas, paneles de control y una interfaz clara y rápida.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**  
El producto debe presentar una interfaz limpia y profesional. Adaptada al perfil corporativo de los clientes objetivos. Debe ser eficiente, permitiendo la creación, modificación y seguimiento de pedidos en pocos clics. También debe ser altamente confiable, debido al alto valor y magnitud de las órdenes que se realizarán en la plataforma

---

Feature Assumptions

- Creemos que al proporcionar una plataforma centralizada con trazabilidad en tiempo real, ayudaremos a las empresas a reducir errores y mejorar la eficiencia logística.  
- Creemos que al ofrecer una interfaz clara y rápida con funciones de seguimiento, aumentaremos la adopción entre proveedores y solicitantes.  
- Creemos que al automatizar la gestión de pedidos, los usuarios reducirán su dependencia de métodos informales y ganarán en control y visibilidad.  
- Creemos que al integrar notificaciones en tiempo real sobre estados de pedido, mejoraremos la coordinación entre actores y reduciremos los retrasos.  
- Creemos que al incluir visualización de métricas, facilitaremos la toma de decisiones y la optimización operativa de los proveedores.

##### 1.2.2.3 Lean UX Hypothesis Statements

Hypothesis Statement 01  
**Creemos que** la centralización de los pedidos en nuestra plataforma reducirá el ratio de errores causados por problemas de coordinación entre las empresas solicitantes y los proveedores.  
**Sabremos que hemos tenido éxito**  
**Cuando** luego de los primeros tres meses de uso se reporte que más de un 70% de los pedidos realizados fueron confirmados sin necesidad de correcciones posteriores.

---

Hypothesis Statement 02  
**Creemos que** ofrecer más herramientas para el control y seguimiento de pedidos mejorará la satisfacción de los clientes solicitantes.  
**Sabremos que hemos tenido éxito**  
**Cuando** se observe una reducción del 30% en llamadas de seguimiento.

---

Hypothesis Statement 03  
**Creemos que** la plataforma permitirá a los proveedores optimizar el proceso de gestión de los pedidos y reducir el tiempo que toma cumplir con cada uno.  
**Sabremos que hemos tenido éxito**  
**Cuando** los proveedores logren reducir en un 20% el tiempo promedio entre confirmación y entrega de pedidos.

---

Hypothesis Statement 04  
**Creemos que** las notificaciones automáticas sobre el estado de los pedidos reducirán la necesidad de una gran cantidad de operadores comerciales de alta disponibilidad.  
**Sabremos que hemos tenido éxito**  
**Cuando** las solicitudes de información por parte de clientes disminuyan en un 40% y el tiempo promedio de atención se reduzca en un 60% tras el primer trimestre de uso.


##### 1.2.2.4 Lean UX Canvas
<!-- Imagen o tabla del Lean UX Canvas -->

---

### 1.3 Segmentos objetivo

#### A. Empresas solicitantes de combustible

Empresas medianas y grandes que requieren de combustible de forma constante para el desarrollo de sus operaciones. Utilizan este recurso para alimentar maquinaria, vehículos o equipos, y buscan procesos más ágiles, ordenados y confiables para su gestión de pedidos. Además, mantienen un contrato de exclusividad con un proveedor de combustible, lo que les permite tener un flujo constante de pedidos y una relación comercial estable.

**Necesidades:**
- Asegurar el abastecimiento oportuno de combustible.
- Reducir errores derivados de la informalidad en los procesos.
- Mantener constante comunicación con proveedores.

---

#### B. Proveedores de combustible
Son empresas dedicadas a la distribución de combustibles, atendiendo principalmente a clientes corporativos o industriales. Buscan herramientas que les permitan, optimizar sus operaciones y diferenciarse en un mercado cada vez más competitivo.

**Motivaciones:**
- Mejorar la experiencia del cliente mediante canales digitales.
- Reducir errores en la entrega por información incompleta o mal gestionada.
- Optimizar la planificación logística y distribución.

