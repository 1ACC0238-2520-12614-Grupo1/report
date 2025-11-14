
---

# Conclusiones
- Conclusiones y recomendaciones.  

# Video App Validation
## Video About The Product
![General Style Guidelines - Color](img/video-about-the-product.png)
Enlace permanente de visualizacion: https://drive.google.com/file/d/1ueirgDoL4SoTTfIo0AIdukoxICfuU2G5/view?usp=sharing

Se presenta un resumen breve consolidando las partes más esenciales de la aplicación FuelTrack, desde el Log In al inicio del video, entrando luego en las características centrales que definen el modelo de negocio. Se presenta el proceso de cotización desde la cuenta del Cliente, para luego mostrar la contraparte en la vista del Proveedor, donde este administra la orden entrante. Se destaca el ciclo de vida completo del pedido, mostrando la actualización de sus estados (en ruta, en sitio, etc.) y la flexibilidad que tiene el proveedor para configurar sus tarifas, cerrando así el círculo comercial de la aplicación.

## Video About the team  
Enlace permanente de visualizacion:

# Glosario
## Glosario de terminos usados en el proyecto
### Metodologías y Prácticas

- **C4 Model (Modelo C4):** Metodología utilizada para visualizar la arquitectura de software en diferentes niveles de abstracción. En este proyecto, se aplica para crear los diagramas de Contexto, Contenedores y Despliegue.
- **Conventional Commits (Commits Convencionales):** Estándar adoptado por el equipo para escribir los mensajes de commit en Git (ej. `feat:`, `fix:`). Se utiliza para mantener un historial limpio y automatizar el versionado.
- **Domain-Driven Design (DDD):** Enfoque de diseño de software (utilizado en el Capítulo 4) centrado en modelar el software según el dominio de negocio. Se divide en `Strategic-Level` (EventStorming, Context Mapping) y `Tactical-Level` (diseño de capas).
- **EventStorming:** Taller colaborativo utilizado en la fase de diseño (DDD) para explorar el dominio de negocio mediante la identificación de eventos (ej. "Pedido realizado", "Pago validado").
- **GitFlow:** Modelo de ramificación (branching) para Git utilizado por el equipo, que define roles para las ramas `main`, `develop` y `feature` para gestionar el código fuente de forma ordenada.
- **Lean UX:** Metodología de diseño ágil utilizada para definir el producto. Incluye artefactos como `Lean UX Problem Statements`, `Assumptions`, `Hypothesis Statements` y el `Lean UX Canvas`.
- **Needfinding:** Proceso de investigación (utilizado en el Capítulo 2) para entender las necesidades reales de los usuarios. Incluye técnicas como `User Personas` y `Empathy Mapping`.
- **Sprint:** Un ciclo de trabajo corto y con tiempo fijo (ej. Sprint 1, Sprint 2) en el que el equipo desarrolla un incremento funcional del producto, como la Landing Page o las funciones de pedido.

### Artefactos y Entregables del Proyecto

- **Acceptance Criteria (Criterios de Aceptación):** Las condiciones específicas, escritas en formato Gherkin (Dado, Cuando, Entonces), que una `User Story` debe cumplir para ser considerada "terminada".
- **Context Mapping (Mapeo de Contextos):** Un diagrama de DDD que muestra las relaciones entre los diferentes `Bounded Contexts` (ej. Gestión de pedidos, Gestión de pagos).
- **Empathy Mapping (Mapa de Empatía):** Herramienta de UX utilizada para obtener una comprensión profunda del usuario, visualizando lo que dice, piensa, siente y hace.
- **Gherkin:** El lenguaje de texto plano (Dado, Cuando, Entonces) utilizado para escribir los `Acceptance Criteria` de las Historias de Usuario.
- **Landing Page:** La página web de presentación de FuelTrack, diseñada para informar a los visitantes sobre el producto y sus beneficios.
- **Mock-up:** Un modelo visual estático de alta fidelidad que representa cómo se verá el diseño final de la aplicación, incluyendo colores y tipografía.
- **Product Backlog:** El listado maestro y priorizado de todo el trabajo (User Stories, Tareas Técnicas) necesario para el producto, gestionado por el equipo en Trello.
- **Sprint Backlog:** El conjunto de `User Stories` (ítems del Product Backlog) seleccionadas para ser completadas durante un `Sprint` específico.
- **Ubiquitous Language (Lenguaje Ubicuo):** Un lenguaje común y compartido por el equipo y los expertos del dominio (Capítulo 2.3.5) para describir el negocio sin ambigüedad (ej. `Requester`, `Supplier`, `Plant`).
- **User Journey Mapping:** Una visualización del proceso (pasos, acciones, emociones) que un usuario sigue para lograr un objetivo con el producto.
- **User Persona:** Un personaje ficticio (arquetipo) creado para representar a un segmento de usuarios objetivo (ej. "Empresas solicitantes de combustible", "Proveedores de combustible").
- **User Story (Historia de Usuario):** Una descripción corta e informal de una funcionalidad desde la perspectiva del usuario (Como... quiero... para...).
- **Wireframe:** Un boceto de baja fidelidad que define la estructura y jerarquía de una pantalla, sin colores ni estilos.

### Términos del Dominio (FuelTrack)

- **Plant (Planta):** Término del `Ubiquitous Language` que se refiere al punto de distribución físico del combustible que pertenece a un `Supplier`.
- **Quotation (Cotización):** Propuesta formal que un `Supplier` genera, detallando precios y productos.
- **Requester (Solicitante):** Término del `Ubiquitous Language` para el usuario (empresa) que requiere abastecimiento de combustible.
- **Supplier (Proveedor):** Término del `Ubiquitous Language` para la empresa que ofrece y distribuye el combustible.

### Tecnologías y Herramientas

- **Android Studio:** El Entorno de Desarrollo Integrado (IDE) utilizado por el equipo para construir la aplicación móvil nativa de FuelTrack.
- **API (Application Programming Interface):** Se refiere al `Backend API` del sistema, que expone los servicios REST para que la App Móvil y otros contenedores se comuniquen.
- **Flutter:** Framework de desarrollo cross-platform (mencionado en el TB2) utilizado para crear una versión de la aplicación.
- **Jetpack Compose:** El toolkit de UI moderno utilizado junto con `Kotlin` para construir la interfaz de usuario de la aplicación nativa de Android.
- **Kotlin:** El lenguaje de programación principal utilizado para el desarrollo de la aplicación móvil nativa (FuelTrack Pro).
- **SaaS (Software as a Service):** El modelo de negocio de FuelTrack, donde la plataforma se ofrece como un servicio por suscripción, en lugar de un software que se instala.
- **Structurizr:** Herramienta utilizada por el equipo para modelar y generar los diagramas de arquitectura basados en el `C4 Model`.



# Bibliografía  
# Anexos  
## 2.6. Tactical-Level Domain-Driven Design
### 2.6.x. Bounded Context: <Bounded Context Name>
#### 2.6.x.1. Domain Layer
#### 2.6.x.2. Interface Layer
#### 2.6.x.3. Application Layer
#### 2.6.x.4. Infrastructure Layer
#### 2.6.x.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.x.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.x.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.x.6.2. Bounded Context Database Design Diagram
  
# Capítulo III: Solution UI/UX Design

## 3.1. Product Design
En la realización de este capítulo, abordaremos el diseño integral de la startup, cubriendo aspectos clave como el estilo visual, los diagramas C4 para la arquitectura del sistema, los diagramas de clases y los modelos de base de datos, proporcionando una visión clara y estructurada de la infraestructura y el funcionamiento del proyecto.

---

### 3.1.1. Style Guidelines
En esta sección se presentan los estándares que definen el formato y el diseño de la solución, asegurando la calidad en su implementación.

#### 3.1.1.1. General Style Guidelines
Con estas decisiones en el diseño visual buscamos reflejar innovación que incentive a la formalidad en los procesos de comercialización. Es así como demostramos modernidad y calidad, valores que van alineados a nuestro proyecto.

**Color**  
Seleccionamos esta gama de colores porque armoniza con el diseño del logo y refleja la temática de nuestra aplicación, asegurando la identidad de la marca.

![General Style Guidelines - Color](img/Imagen3.png)

**Tipografía**  
Seleccionamos esta tipografía por su excelente legibilidad en diversos entornos, lo que nos permite diferenciarnos frente a la competencia y aportar una identidad única a nuestra marca.

![General Style Guidelines - Tipografia](img/Imagen2.png)

**Branding**  
El nombre de nuestro producto es *FuelTrack*. Contamos con un logo que representa claramente nuestro rubro, dándole un toque moderno y simple. Además, usamos colores que serán característicos en nuestra empresa y amigables a la vista de nuestros clientes.

![General Style Guidelines - Branding](img/Imagen1.png)

---

### 3.1.2. Information Architecture
La arquitectura de información se diseñó para guiar al usuario de forma lógica a través de las funciones esenciales de FuelTrack, facilitando la navegación y reduciendo la curva de aprendizaje.

#### 3.1.2.1. Organization Systems
El sistema de organización de FuelTrack tiene como objetivo facilitar la interacción fluida entre los usuarios (compradores y proveedores) y la plataforma mediante una jerarquía visual clara. Esta jerarquía destaca las funciones clave —como la gestión de pedidos de combustible, el registro de depósitos y la carga de documentos— permitiendo que los usuarios accedan rápidamente a las acciones más importantes desde la pantalla principal.

- **Agrupación lógica de funciones:** Las funcionalidades están organizadas por bloques temáticos (*Record Deposits*, *Upload Documents*, *Track Orders*), lo que permite a los usuarios identificar rápidamente las opciones disponibles y su propósito.  
- **Accesibilidad inmediata:** La interfaz principal resalta las opciones más utilizadas mediante una disposición vertical y centrada, optimizada tanto para escritorio como para dispositivos móviles.  
- **Menú de navegación:** Se mantiene fijo en la parte superior para facilitar el acceso constante a secciones clave como *How it Works*, *Pricing* y *Sign Up*.  
- **Reducción de fricción:** Al minimizar la cantidad de clics necesarios para ejecutar acciones comunes, el sistema organiza la información de forma que prioriza la eficiencia y la experiencia del usuario.  

Este sistema organizativo asegura que tanto usuarios nuevos como recurrentes puedan navegar por FuelTrack con facilidad, incrementando la productividad y reduciendo los errores de operación.

---

#### 3.1.2.2. Labelling Systems
Las etiquetas que utilizaremos para la página serán diseñadas para ser claras, directas y fáciles de entender, enfocándose en la eficiencia y simplicidad para usuarios con distintos niveles de experiencia tecnológica.

---

**Principios generales**
- Se limita el uso de 2-3 palabras por ítem.  
- Se mantiene la consistencia terminológica en todas las pantallas.  
- Las etiquetas son descriptivas y responden a acciones directas, estados o categorías claras.  

---

**Algunas de las etiquetas principales de nuestras secciones serán las siguientes:**

**Gestión de Pedidos**
- Nuevo Pedido  
- Estado de Pedido  
- Historial de Pedidos  
- Ver Detalles  
- Confirmar Entrega  

**Pagos y Facturación**
- Métodos de Pago  
- Mis Facturas  
- Resumen de Pagos  
- Confirmar Pago  

**Reportes**
- Reporte de Pedidos  
- Reporte de Pagos  
- Resumen de Actividad  
- Generar Informe  

**Navegación general**
- Inicio  
- Mi Cuenta  
- Soporte  
- Cerrar Sesión  

---

**Asociaciones y agrupaciones**
- Las etiquetas se agrupan en módulos lógicos (por ejemplo: pedidos, pagos, reportes) con un menú lateral y dashboard central de fácil acceso.  
- Las acciones están asociadas a sus contextos inmediatos: por ejemplo, *Nuevo Pedido* solo aparece cuando se selecciona la opción *Gestión de Pedidos*.  
- Los mensajes del sistema son claros y directos: *Pedido Confirmado*, *Pago Realizado*, *Entrega Programada*.  

Estas etiquetas están diseñadas para que los usuarios puedan navegar de manera sencilla y sin confusiones, optimizando la experiencia para empresas que desean una solución eficiente y fácil de usar.

---

#### 3.1.2.3. SEO Tags and Meta Tags

**Landing Page**
- **Title (SEO Tag):** FuelTrack | Simplify Fuel Order Management  
- **Description (Meta Tag):** Optimize your fuel ordering process with FuelTrack — a centralized platform for buyers and suppliers to record deposits, upload documents, and track orders.  
- **Keywords (Meta Tag):** Fuel, Track, Ordering, Fuel management, Supplier platform, Track fuel orders, Fuel deposits, Order management software  
- **Author (Meta Tag):** FuelTrack Team  

**Web Application**
- **Title (SEO Tag):** FuelTrack | Manage Fuel Orders and Deposits  
- **Description (Meta Tag):** Access your dashboard to record deposits, manage documents, and monitor fuel order status in real time.  
- **Keywords (Meta Tag):** Fuel order tracking, Deposit management, Supplier dashboard, Fuel logistics, FuelTrack Web App  
- **Author (Meta Tag):** FuelTrack Team  

---

#### 3.1.2.4. Searching Systems
Para garantizar una navegación fluida y centrada de nuestra plataforma, vamos a implementar las siguientes acciones y técnicas tanto para la página como la aplicación web:

- **Menú de navegación:** En la página utilizaremos un *Navigation Bar* que contendrá enlaces visibles a las secciones más importantes de la plataforma, principalmente sus características y el registro o ingreso de la cuenta.  
- **Navegación visual guiada:** El contenido está organizado en bloques visuales de las secciones determinadas en la barra principal, permitiendo al usuario desplazarse verticalmente para descubrir las funcionalidades de manera fluida.  
- **Responsive design:** Esta será construida para adaptarse al tipo de dispositivo del usuario. Por ejemplo, la resolución de la página estará optimizada según cómo sea redimensionada, con compatibilidad tanto en escritorio como en portátiles. De esta forma, los usuarios podrán realizar sus tareas sin que el cambio de máquina sea un problema.

---

#### 3.1.2.5. Navigation Systems
Para la plataforma implementamos un sistema de búsqueda por texto y por categorías para que los usuarios, especialmente los proveedores, puedan localizar los pedidos que se han realizado o se están llevando a cabo. Se incluirán filtros de la siguiente manera:

- **Búsqueda por texto:**  
  El usuario tendrá una tabla de pedidos donde en cada categoría (razón social, número de pedido, nombre de banco, etc.) dispondrá de un mini buscador estándar para encontrar sus pedidos registrados o pendientes. Este entregará los resultados según el tipo de información que detecte automáticamente.  
  Además, habrá un botón llamado **“Búsqueda avanzada”**, donde se realizará una búsqueda más específica siempre y cuando se completen todas las categorías.

- **Búsqueda por categorías:**  
  El usuario dispondrá de un sistema automático de filtrado de datos basado en las categorías existentes para optimizar su tiempo en tareas de mayor importancia.  
  Por ejemplo, el sistema se encargará de filtrar todas las ubicaciones detectadas de los pedidos registrados o pendientes, y se podrán seleccionar las que se deseen aplicar.


### 3.1.3. Landing Page UI Design
La propuesta de diseño de la Landing Page para FuelTrack parte de una arquitectura de información clara y orientada a los segmentos objetivo definidos: empresas proveedoras de combustible y empresas solicitantes de combustible.

El diseño organiza el contenido en bloques visuales jerárquicos que guían al usuario de manera natural hacia los principales call-to-action (CTA), alineando cada sección con una necesidad identificada: informar, atraer y convertir.

Decisiones principales de diseño tomadas:

- **Navegación simple y consistente:** El menú principal permite acceso rápido a las secciones clave (Features, Pricing y Contact).
- **Call to Action diferenciados:** Hay botones específicos tanto para proveedores como para solicitantes, siguiendo un enfoque de segmentación clara.
- **Diseño inclusivo:** La paleta de colores cumple estándares de contraste para accesibilidad, y los botones tienen tamaños adecuados para pantallas táctiles.
- **Adaptabilidad:** El diseño es responsive, garantizando experiencia de usuario adecuada tanto en desktop como en dispositivos móviles.
- **Consistencia visual:** Se mantiene un diseño limpio y moderno, utilizando colores corporativos azul y verde para reforzar la identidad de FuelTrack.
#### 3.1.3.1. Landing Page Wireframe  
![Landing Page - Wireframe 1](img/landing_wireframe_1.png)
![Landing Page - Wireframe 2](img/landing_wireframe_2.png)
![Landing Page - Wireframe 3](img/landing_wireframe_3.png)
![Landing Page - Wireframe 4](img/landing_wireframe_4.png)
![Landing Page - Wireframe 5](img/landing_wireframe_5.png)
![Landing Page - Wireframe 6](img/landing_wireframe_6.png)
![Landing Page - Wireframe 7](img/landing_wireframe_7.png)
#### 3.1.3.2. Landing Page Mock-up
![Landing Page - Mockup 1](img/landing_mockup_1.png) 
![Landing Page - Mockup 2](img/landing_mockup_2.png) 
![Landing Page - Mockup 3](img/landing_mockup_3.png)
![Landing Page - Mockup 4](img/landing_mockup_4.png)
![Landing Page - Mockup 5](img/landing_mockup_5.png)
![Landing Page - Mockup 6](img/landing_mockup_6.png)
![Landing Page - Mockup 7](img/landing_mockup_7.png)
### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes  
#### 3.1.4.2. Mobile Applications Wireflow Diagrams  
#### 3.1.4.3. Mobile Applications Mock-ups  
#### 3.1.4.4. Mobile Applications User Flow Diagrams  
#### 3.1.4.5. Mobile Applications Prototyping

# Capítulo IV: Product Implementation & Validation

# 4. Product Implementation & Validation

## 4.1. Software Configuration Management

### 4.1.1. Software Development Environment Configuration

| **Producto** | **Propósito en el proyecto** | **Categoría** | **Ruta de descarga/acceso** | **Descripción** |
|---|---|---|---|---|
| **Android Studio**<br><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Android_Studio_icon_%282023%29.svg/1200px-Android_Studio_icon_%282023%29.svg.png" alt="Android Studio logo" width="56"> | IDE principal para desarrollo de la app Android (Kotlin/Java), emuladores y profiling. | Desarrollo de software | https://developer.android.com/studio | Entorno completo para construir, depurar y empaquetar APK/AAB; integra Gradle, SDK Manager y AVD. |
| **Postman**<br><img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/Postman_%28software%29.png" alt="Postman logo" width="120"> | Pruebas funcionales de APIs (REST), documentación y colecciones de requests. | Testing de API / Desarrollo | https://www.postman.com/ | Permite validar endpoints, usar variables de entorno, tests automáticos y compartir colecciones. |
| **Lucidchart**<br><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Lucidchart-logo.svg/512px-Lucidchart-logo.svg.png" alt="Lucidchart logo" width="140"> | Diagramas de procesos, casos de uso, flujos y arquitectura. | Arquitectura & Documentación | https://www.lucidchart.com/ | Herramienta visual para documentar flujos UI, BPMN, ERD y vistas de arquitectura de alto nivel. |
| **Structurizr**<br><img src="https://static.structurizr.com/img/structurizr-banner.png" alt="Structurizr logo" width="160"> | Modelado de arquitectura con el **modelo C4** (Context, Container, Component, Code). | Arquitectura & Documentación | https://structurizr.com/ | Genera diagramas C4 consistentes desde código/DSL; útil para el Deployment Diagram requerido. |
| **Miro**<br><img src="https://logo.svgcdn.com/l/miro-8x.png" alt="Miro logo" width="144"> | Ideación colaborativa, mapas de experiencia/journey y wireframes rápidos. | UX/UI & Colaboración | https://miro.com/ | Pizarra online para co-crear flujos, priorizar features y registrar decisiones de diseño. |
| **GitHub Pages**<br><img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub logo" width="40"> | Hosting estático para la **Landing Page** del proyecto. | Deployment / Hosting | https://pages.github.com/ | Publica sitios estáticos directamente desde el repositorio; integra con CI y dominios personalizados. |

#### 4.1.2. Source Code Management  

FuelTrack es una solución B2B orientada a ordenar el ciclo completo de un pedido de combustible (solicitud, validación, despacho, seguimiento y cierre). Por esa naturaleza operativa —donde la trazabilidad y la auditoría son críticas— la gestión del código se diseñó para privilegiar la separación clara de responsabilidades, la estandarización del trabajo en equipo y la automatización repetible de entregas. Adoptamos vistas C4 para comunicar arquitectura (Context, Container, Component y Deployment) y principios de Clean Architecture para mantener límites nítidos entre dominio, aplicación e infraestructura sin amarrar el modelo de negocio a frameworks específicos.

Para mantener la uniformidad del entorno, el equipo desarrolla la app móvil en Android Studio y usa Postman para validar contratos de la API a partir del artefacto OpenAPI generado en cada build del backend. La documentación de arquitectura se versiona como código (archivos DSL de Structurizr y diagramas exportados) dentro de los repos, de modo que cualquier cambio estructural quede ligado a un commit y pueda revisarse igual que el resto del código.

Todo el código vive en nuestra organización de GitHub: https://github.com/orgs/1ACC0238-2520-12614-Grupo1/repositories, con tres repos: fueltrack-landing, fueltrack-report y fueltrack-mobile.
Usamos GitFlow (main/develop + feature/release/hotfix) y Conventional Commits. Todo cambio va por Pull Request con checks (build, tests, lint) y la documentación (C4/Structurizr y OpenAPI) se versiona en los mismos repositorios.

<img src="https://i.imgur.com/W9WWwOQ.png" alt="GitHub logo" width="740">

#### 4.1.3. Source Code Style Guide & Conventions  

Para FuelTrack, la estandarización del código no es solo estética: es el mecanismo que garantiza trazabilidad, mantenibilidad y velocidad de entrega en un producto B2B donde “pedido-→validación-→despacho-→seguimiento-→cierre” debe auditarse sin ambigüedades. Por eso adoptamos vistas C4 para comunicar arquitectura (Context, Container, Component y Deployment) y principios de Clean Architecture para separar presentación / aplicación / dominio / infraestructura, evitando dependencias innecesarias del dominio con frameworks.

Lenguaje y nomenclatura (transversal). Todos los identificadores del código (clases, métodos, variables, paquetes, rutas de API, nombres de archivos) se escriben en inglés; el español se reserva a contenido visible para el usuario o documentación funcional. Se prohíben abreviaturas crípticas y términos con acentos. Convenciones: PascalCase para clases y tipos; camelCase para métodos, variables y propiedades; UPPER_SNAKE_CASE para constantes; nombres de archivos en kebab-case cuando aplique (p. ej., front estático). Comentarios solo cuando aporten intención o contratos; preferimos autoexpresividad del código y KDoc/Javadoc en APIs públicas.

Landing (estático). HTML5 semántico (header, nav, main, section, footer), atributos alt y ARIA donde corresponda, CSS utilitario o BEM de forma consistente, breakpoints responsivos definidos a nivel de tema y Prettier para formateo. JS moderno (ES Modules), sin lógica de negocio en el cliente; todo texto en inglés en código fuente.

Mobile: Kotlin & Flutter. Escribimos en inglés y organizamos por features (orders, auth, tracking); nombres claros: clases en PascalCase, funciones/variables en camelCase y archivos Flutter.
Textos, colores y tipografías salen de un tema central y archivos de localización. Pantallas como Composables/Widgets pequeños y reutilizables, con estados consistentes (loading/empty/error/success) y navegación simple pasando solo lo necesario.
Commits con Conventional Commits y PRs obligatorios; priorizamos código legible y sin complejidad innecesaria.

Trabajamos con GitFlow (ramas main y develop, más feature/, release/ y hotfix/), mensajes de commit con Conventional Commits (p. ej., feat(mobile): create order page), y Pull Requests obligatorios con revisión. Esto mantiene trazabilidad directa entre historias del backlog y los cambios en código, sin fricción para el equipo.

#### 4.1.4. Software Deployment Configuration  

### 4.2. Landing Page & Mobile Application Implementation
#### 4.2.1. *Sprint 1*  

En la etapa inicial de nuestro proyecto, decidimos llevar a cabo la implementación del diseño de nuestra Landing Page utilizando AndroidStudio como el entorno de desarrollo.

##### 4.2.1.1. Sprint Planning 1  

Para el primer sprint, el equipo establecio que el desarrollo de las tareas tomaría al rededor de 12 horas.

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"><b>Sprint  Background</b></td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2025/10/10</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>10:30 PM</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>Discordt</td>
        </tr>
        <tr>
            <td>Prepared by</td>
            <td>Renzo Luque</td>
        </tr>
        <tr>
            <td>Atendees (to  meeting)</td>
            <td>
                <li>Juan Carlos Alvarado De La Cruzn</li>
                <li>Bryan Ronald Espejo Gamarra</li>
                <li>Gianfranco Jared Durand Vega</li>
                <li>Jhon Danny Guerrero Vasquez</li>
              <li>Renzo Andres Luque Minaya</li>
            </td>
        </tr>
        <tr>
            <td>Sprint 1 Retrospective Summary</td>
            <td>
                Acuerdo de la implementación de una primera versión del Landing Page  
            </td>
        </tr>
        <tr>
            <td colspan="2"><b>Sprint Goal & User Stories</b></td>
        </tr>
        <tr>
            <td>Sprint 1 Goal</td>
            <td style="text-align: justify">
                <p>
                Nuestro objetivo en este sprint es desarrollar la primera versión de la Landing Page de FuelTrack, enfocándonos en una estructura que sea visualmente atractiva y fácil de navegar. Utilizando AndroidStudio, crearemos una interfaz responsive que se adapte de manera óptima a dispositivos móviles.
                </p>
                <p>
                Creemos que esta Landing Page ofrecerá una introducción profesional y accesible a Tallerazo, mejorando la experiencia de usuario y estableciendo una base sólida para la intecon el sistema. El éxito de este sprint se confirmará cuando los usuarios puedan explorar la Landing Page de manera fluida en distintos dispositivos, logrando una primera impresión positiva y una navegación sencilla que los motive a explorar más sobre el sistema.
                </p>
            </td>
        </tr>
        <tr>
            <td>Sprint 1 Velocity</td>
            <td>
                8
            </td>
        </tr>
        <tr>
            <td>Sum of story points</td>
            <td>
                8
            </td>
        </tr>
    </tbody>
</table>

##### 4.2.1.2. Sprint Backlog 1  

| User Story | Work-Item / Task | Title | Description | Estimation (Hours) | Assigned To |
|-------------|------------------|--------|--------------|--------------------|--------------|
| US01 | T01 | Diseñar Pantalla de Login | Crear la interfaz principal de inicio de sesión con campos de correo, contraseña y botones de acceso demo. | 3 | Gianfranco Jared Durand Vega |
| US02 | T02 | Implementar Lógica de Autenticación | Desarrollar la funcionalidad de login con validación básica y conexión al servicio de datos. | 3 | Juan Carlos Alvarado De La Cruz |
| US03 | T03 | Configurar Repositorio y Documentación | Crear el repositorio en GitHub y agregar documentación inicial del proyecto (README, estructura, objetivos). | 2 | Renzo Andres Luque Minaya |
| US04 | T04 | Desarrollar Pantalla de Dashboard | Implementar una vista inicial del panel principal con resumen de datos de consumo. | 2 | Bryan Ronald Espejo Gamarra |
| US05 | T05 | Pruebas y Ajustes Finales | Realizar pruebas funcionales del login y dashboard, corrigiendo errores visuales o de navegación. | 2 | Jhon Danny Guerrero Vasquez |


##### 4.2.1.3. Development Evidence for Sprint Review 

| Historia de Usuario | Elemento de trabajo / Tarea | Descripción | Estimación (Horas) | Asignado a | Estado |
|----------------------|-----------------------------|--------------|--------------------|-------------|---------|
| US13 | Implementar visualización del Landing Page | Mostrar una landing page informativa para que los interesados conozcan la plataforma antes de registrarse. | 5 | Bryan Ronald Espejo Gamarra | Finalizado |
| EP04 | Landing Page informativa y funcional | Landing page con secciones informativas, beneficios, segmentos y botones que dirigen a login o registro. | 6 | Jhon Danny Guerrero Vasquez | Finalizado |

##### 4.2.1.4. Testing Suite Evidence for Sprint Review 


##### 4.2.1.5. Execution Evidence for Sprint Review 

**Resumen:**
Las principales secciones de la Landing Page de FuelTrack fueron desarrolladas y desplegadas exitosamente. A continuación se presentan capturas de pantalla de las secciones implementadas.

Evidencia de Capturas:

<img width="263" height="483" alt="login" src="https://github.com/user-attachments/assets/6d781f4e-d290-4085-9b62-6480ddb6ad98" />

##### 4.2.1.6. Services Documentation Evidence for Sprint Review  

En el primer sprint, hemos realizado el diseño, la programación y el despligue de la Landing Page que presentará nuesta apliación móvil "FuelTrack"

##### 4.2.1.7. Software Deployment Evidence for Sprint Review  

Para el despliegue de nuestra Landing Page hemos utilizado AndroidStudio. Para hacer esto, hemos trabajado en el compilador AndroidStudio dondse se compilará el código trabajado.

<img width="263" height="483" alt="login" src="https://github.com/user-attachments/assets/b7f49d41-1562-4e70-80ca-9d0651c883cd" />

##### 4.2.1.8. Team Collaboration Insights during Sprint  

**Resumen:**
El equipo colaboró mediante GitHub, WhatsApp y Discord durante el Sprint. Las actividades principales se centraron en el desarrollo y despliegue de la Landing Page.

**Evidencia de Colaboración:**

* Conversaciones de WhatsApp sobre coordinación de secciones y ajustes de diseño.
  
* Principales Herramientas de Comunicación:
  
* GitHub (control de versiones y manejo de issues)
  
* WhatsApp (comunicación diaria y aclaraciones rápidas)
  
* Discord (reuniones de planificación de sprint)

               
</table>

### 4.3. Validation Interviews
#### 4.3.1. Diseño de Entrevistas  
#### 4.3.2. Registro de Entrevistas  
#### 4.3.3. Evaluaciones según heurísticas  


#### 4.2.2. *Sprint 2*  
En esta etapa, el equipo se centró en desarrollar la funcionalidad principal de FuelTrack: la creación y visualización de pedidos desde el rol Solicitante. El esfuerzo estimado para este sprint fue de 30 horas.

##### 4.2.2.1. Sprint Planning 2  
<table> <thead> <tr> <th>Sprint #</th> <th>Sprint 2</th> </tr> </thead> <tbody> <tr> <td colspan="2"><b>Sprint Background</b></td> </tr> <tr> <td>Date</td> <td>2025/10/24</td> </tr> <tr> <td>Time</td> <td>10:30 PM</td> </tr> <tr> <td>Location</td> <td>Discord</td> </tr> <tr> <td>Prepared by</td> <td>Renzo Luque</td> </tr> <tr> <td>Attendees (to meeting)</td> <td> <li>Juan Carlos Alvarado De La Cruz</li> <li>Bryan Ronald Espejo Gamarra</li> <li>Gianfranco Jared Durand Vega</li> <li>Jhon Danny Guerrero Vasquez</li> <li>Renzo Andres Luque Minaya</li> </td> </tr> <tr> <td>Sprint 1 Retrospective Summary</td> <td> El equipo completó el Login y Dashboard del Sprint 1. Se identificó que las tareas de integración API-app requerían mayor estimación, por lo que se aplicó para este Sprint 2. </td> </tr> <tr> <td colspan="2"><b>Sprint Goal & User Stories</b></td> </tr> <tr> <td>Sprint 2 Goal</td> <td style="text-align: justify"> <p> Este sprint tiene como objetivo implementar la funcionalidad core de FuelTrack: permitir que el usuario “Solicitante” cree nuevos pedidos de combustible y pueda visualizar su historial. </p> <p> El sprint será exitoso cuando un usuario autenticado logre registrar un pedido desde la pantalla “Nuevo Pedido” (US01) y pueda visualizarlo correctamente en el “Historial de Pedidos” (US02), con datos obtenidos desde el backend a través de los endpoints implementados. </p> </td> </tr> <tr> <td>Sprint 2 Velocity</td> <td>15</td> </tr> <tr> <td>Sum of Story Points</td> <td>15</td> </tr> </tbody> </table>

##### 4.2.2.2 Sprint Backlog 2  

<table> <thead> <tr> <th>User Story</th> <th>Work-Item / Task</th> <th>Title</th> <th>Description</th> <th>Estimation (Hours)</th> <th>Assigned To</th> </tr> </thead> <tbody> <tr> <td>US06</td> <td>T06</td> <td>Diseñar Interfaz de Registro</td> <td>Crear la pantalla de registro con campos validados y diseño responsivo.</td> <td>3</td> <td>Juan Carlos Alvarado De La Cruz</td> </tr> <tr> <td>US07</td> <td>T07</td> <td>Implementar API de Registro</td> <td>Desarrollar la lógica para registrar nuevos usuarios y enviarlos al backend.</td> <td>4</td> <td>Jhon Danny Guerrero Vasquez</td> </tr> <tr> <td>US08</td> <td>T08</td> <td>Optimizar Diseño del Dashboard</td> <td>Ajustar visualmente el dashboard para mejorar su navegación y accesibilidad.</td> <td>2</td> <td>Bryan Ronald Espejo Gamarra</td> </tr> <tr> <td>US09</td> <td>T09</td> <td>Configurar Navegación entre Pantallas</td> <td>Permitir la navegación fluida entre login, registro y dashboard.</td> <td>3</td> <td>Gianfranco Jared Durand Vega</td> </tr> <tr> <td>US10</td> <td>T10</td> <td>Pruebas Funcionales Generales</td> <td>Realizar pruebas básicas en las nuevas pantallas implementadas.</td> <td>2</td> <td>Renzo Andres Luque Minaya</td> </tr> </tbody> </table>

##### 4.2.2.3. Development Evidence for Sprint Review 

<table> <thead> <tr> <th>Historia de Usuario</th> <th>Elemento de trabajo / Tarea</th> <th>Descripción</th> <th>Estimación (Horas)</th> <th>Asignado a</th> <th>Estado</th> </tr> </thead> <tbody> <tr> <td>US06</td> <td>Diseñar Interfaz de Registro</td> <td>Se desarrolló una pantalla de registro responsiva con validaciones básicas.</td> <td>3</td> <td>Juan Carlos Alvarado De La Cruz</td> <td>Finalizado</td> </tr> <tr> <td>US07</td> <td>Implementar API de Registro</td> <td>Se creó la conexión al backend y el flujo de creación de nuevos usuarios.</td> <td>4</td> <td>Jhon Danny Guerrero Vasquez</td> <td>Finalizado</td> </tr> <tr> <td>US08</td> <td>Optimización del Dashboard</td> <td>Se mejoró la experiencia visual del dashboard mediante ajustes en diseño.</td> <td>2</td> <td>Bryan Ronald Espejo Gamarra</td> <td>Finalizado</td> </tr> <tr> <td>US09</td> <td>Navegación entre pantallas</td> <td>Se configuró la navegación fluida entre login, registro y dashboard.</td> <td>3</td> <td>Gianfranco Jared Durand Vega</td> <td>Finalizado</td> </tr> <tr> <td>US10</td> <td>Pruebas funcionales</td> <td>Se probaron todas las nuevas funcionalidades y se corrigieron errores menores.</td> <td>2</td> <td>Renzo Andres Luque Minaya</td> <td>Finalizado</td> </tr> </tbody> </table>

##### 4.2.2.4. Testing Suite Evidence for Sprint Review 

### Resumen de Pruebas del Sprint 2

#### PRUEBAS MANUALES DOCUMENTADAS

• Prueba de navegación entre pantallas:
  - Login → Registro → Dashboard.
  - Resultado: Correcto.

• Validaciones en pantalla de Registro:
  - Campos vacíos, correo inválido, contraseña débil.
  - Resultado: Correcto.

• Integración con API de Registro:
  - Se envían datos y se recibe respuesta del backend.
  - Resultado: Correcto.

• Diseño responsive:
  - Se probó en diferentes tamaños de pantalla.
  - Resultado: Aprobado.

• Pruebas del Dashboard:
  - Carga de datos y botones principales funcionando.
  - Resultado: Aprobado.

#### PRUEBAS EN GHERKIN

```gherkin
Feature: Gestión de Pedidos del Solicitante
  Como Solicitante, quiero crear y ver mis pedidos
  para gestionar mis compras de combustible.

  Scenario: Creación exitosa de un nuevo pedido
    Given que estoy autenticado como "Solicitante" en la app
    When navego a la pantalla "Nuevo Pedido"
    And lleno el formulario con "Diesel B5", "1000 galones" y "Planta Arequipa"
    And presiono el botón "Confirmar Pedido"
    Then el sistema crea el pedido en estado "Por confirmar"
    And soy redirigido a mi "Historial de Pedidos"
    And veo el pedido de "1000 galones de Diesel B5" en la lista.
```

##### 4.2.2.5. Execution Evidence for Sprint Review 

Resumen:
Las pantallas “Nuevo Pedido” y “Historial de Pedidos” han sido implementadas correctamente, permitiendo al Solicitante gestionar sus pedidos desde la app móvil.


<!--->
Evidencia de capturas:
Pantallas desarrolladas y funcionando en entorno móvil.
(Insertar imágenes según tu repositorio)
<---->

##### 4.2.2.6. Services Documentation Evidence for Sprint Review  

<table> <thead> <tr> <th>Servicio</th> <th>Descripción</th> <th>Responsable</th> <th>Estado</th> </tr> </thead> <tbody> <tr> <td>API de Registro</td> <td>Servicio encargado de recibir la información del usuario nuevo y almacenarla en el backend.</td> <td>Jhon Danny Guerrero Vasquez</td> <td>Documentado</td> </tr> <tr> <td>Servicio de Autenticación</td> <td>Proceso que valida credenciales desde la app y permite acceso al Dashboard.</td> <td>Juan Carlos Alvarado De La Cruz</td> <td>Actualizado</td> </tr> <tr> <td>Servicio de Navegación</td> <td>Módulo que permite el flujo entre pantallas dentro de la aplicación móvil.</td> <td>Gianfranco Jared Durand Vega</td> <td>Documentado</td> </tr> <tr> <td>Servicio de Dashboard</td> <td>Recopila y muestra información relevante del usuario respecto a su actividad.</td> <td>Bryan Ronald Espejo Gamarra</td> <td>Documentado</td> </tr> </tbody> </table>

Swagger disponible en entorno de pruebas.

##### 4.2.2.7. Software Deployment Evidence for Sprint Review  

La nueva versión del backend con endpoints /orders fue desplegada en ambiente de pruebas.
La app móvil fue recompilada e instalada en dispositivos del equipo para testing interno.

##### 4.2.2.8. Team Collaboration Insights during Sprint  
Resumen:
La colaboración fue constante entre equipos mobile y backend mediante:

GitHub (PRs y versionamiento)

Discord (reuniones de coordinación)
![Discord - Evidence](img/Discord%20-%20Evidence.png)

Trello (gestión del Sprint)
![Trello - Evidence](img/Trello%20-%20sprint2.png)

### 4.3. Validation Interviews
#### 4.3.1. Diseño de Entrevistas  
#### 4.3.2. Registro de Entrevistas  
#### 4.3.3. Evaluaciones según heurísticas  

  
