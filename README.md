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
#### 4.2.1. *Sprint n*  
##### 4.2.1.1. Sprint Planning n  
##### 4.2.1.2. Sprint Backlog n  
##### 4.2.1.3. Development Evidence for Sprint Review  
##### 4.2.1.4. Testing Suite Evidence for Sprint Review  
##### 4.2.1.5. Execution Evidence for Sprint Review  
##### 4.2.1.6. Services Documentation Evidence for Sprint Review  
##### 4.2.1.7. Software Deployment Evidence for Sprint Review  
##### 4.2.1.8. Team Collaboration Insights during Sprint  

### 4.3. Validation Interviews
#### 4.3.1. Diseño de Entrevistas  
#### 4.3.2. Registro de Entrevistas  
#### 4.3.3. Evaluaciones según heurísticas  

---

# Conclusiones
- Conclusiones y recomendaciones.  

# Video App Validation
- Video About the product  
- Video About the team  

# Glosario  
# Bibliografía  
# Anexos  
