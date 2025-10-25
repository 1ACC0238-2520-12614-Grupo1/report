# Capítulo II: Requirements Elicitation & Analysis 
## 2.1. Competidores.

PetroApp es una plataforma digital que facilita la compra y venta de combustible, principalmente orientada a consumidores finales y estaciones de servicio. Permite ubicar estaciones cercanas, gestionar pagos electrónicos y controlar el consumo desde una app. Esta enfocada principalmente en el uso personal, pero también ofrece soluciones para empresas, con funcionalidades que permiten cierta trazabilidad y control, aunque con menos enfoque en el flujo completo del pedido corporativo.

FuelCloud es una solución tecnológica centrada en el control del despacho de combustible mediante una combinación de hardware y software. Este ofrece monitoreo en tiempo real, control de acceso al combustible, reportes detallados de consumo y ubicación, lo que la hace ideal para empresas con tanques propios. Además, se enfoca más en el control físico del combustible que en la gestión administrativa o logística del pedido entre proveedor y cliente.

Wialon es una plataforma global de gestión de flotas que incluye funcionalidades para el control de combustible, seguimiento de vehículos por GPS, y análisis de consumo. Ofrece herramientas de visualización en tiempo real, alertas automatizadas y reportes avanzados. Si bien no gestiona directamente el flujo de pedidos entre proveedores y solicitantes, es altamente utilizada por empresas distribuidoras y logísticas que transportan combustible, lo que la convierte en un competidor indirecto pero funcionalmente cercano a FuelTrack.

### 2.1.1. Análisis competitivo.
<table border="1">
  <tr>
    <th colspan="6" style="text-align:left">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td><strong>¿Por qué llevar a cabo este análisis?</strong></td>
    <td colspan="5">Este análisis se está llevando a cabo porque queremos conocer las ventajas y desventajas de nuestra aplicación frente a la competencia, y cómo nos diferenciamos de ellas.</td>
  </tr>
  <tr>
  <td colspan="2"><strong>(En la cabecera colocar por cada competidor nombre y logo)</strong></td>
  <td><strong>FuelTrack</strong><br><img src="img/logo-fueltrack.jpg" height="120"/></td>
  <td><strong>Zavgar</strong><br><img src="img/logo-zavgar.jpg" height="120"/></td>
  <td><strong>FuelCloud</strong><br><img src="img/logo-fuelcloud.jpg" height="120"/></td>
  <td><strong>Wialon</strong><br><img src="img/logo-wialon.jpg" height="120"/></td>
</tr>

  <tr>
    <th rowspan="3">Perfil</th>
    <td><strong>Visión general</strong></td>
    <td>Plataforma web que digitaliza y estructura el proceso completo de pedido de combustible entre empresas y proveedores.</td>
    <td>SaaS para la gestión de consumo de combustible de flotas, con enfoque en eficiencia, monitoreo y costos.</td>
    <td>Solución con hardware/software para el control físico del despacho de combustible.</td>
    <td>Plataforma de gestión de flotas con control de combustible, GPS y reportes operativos.</td>
  </tr>
  <tr>
    <td><strong>Ventaja competitiva</strong></td>
    <td>Especialización en el flujo completo de pedido, despacho y análisis; integración de pagos y logística; UI intuitiva.</td>
    <td>No requiere hardware; ofrece métricas, control de gastos y reportes sobre consumo.</td>
    <td>Control físico preciso del combustible, monitoreo en tiempo real.</td>
    <td>Seguimiento en tiempo real, visualización de rutas, integración con sensores de combustible.</td>
  </tr>
  <tr>
    <td><strong>¿Qué valor ofrece al cliente?</strong></td>
    <td>Trazabilidad total, eficiencia operativa, reportes de consumo y validación segura de pedidos.</td>
    <td>Optimización de costos y control sobre el uso de combustible en flotas.</td>
    <td>Seguridad y precisión operativa en el control de combustible.</td>
    <td>Trazabilidad de flotas, alertas automáticas, análisis de rutas y consumo de combustible.</td>
  </tr>
  <tr>
    <th rowspan="2">Perfil de Marketing</th>
    <td><strong>Mercado objetivo</strong></td>
    <td>Empresas que solicitan combustible a proveedores.</td>
    <td>Empresas con flotas vehiculares que desean monitorear y reducir el consumo de combustible.</td>
    <td>Empresas con tanques de combustible propios.</td>
    <td>Empresas logísticas, distribuidoras y de transporte de combustible.</td>
  </tr>
  <tr>
    <td><strong>Estrategias de marketing</strong></td>
    <td>Alianzas con proveedores, demostraciones de ahorro, marketing de contenido enfocado en eficiencia.</td>
    <td>Enfoque digital, contenido técnico, integración con proveedores de tarjetas de combustible.</td>
    <td>Ferias industriales, distribuidores, venta consultiva entre empresas.</td>
    <td>Alianzas con distribuidores de GPS, marketing técnico, ferias de transporte.</td>
  </tr>
  <tr>
    <th rowspan="3">Perfil de Producto</th>
    <td><strong>Productos & Servicios</strong></td>
    <td>Plataforma para gestión completa de pedidos, seguimiento, reportes, validación y alertas.</td>
    <td>Plataforma web con módulo de abastecimiento, reportes de consumo, integración GPS y tarjetas.</td>
    <td>Hardware IoT y software para gestión, y control de combustible.</td>
    <td>Plataforma SaaS + app móvil con monitoreo, alertas, mapas y módulos personalizables.</td>
  </tr>
  <tr>
    <td><strong>Precios & Costos</strong></td>
    <td>Modelo SaaS con suscripción escalable según volumen y servicios.</td>
    <td>SaaS con modelos por flota activa o vehículos monitoreados.</td>
    <td>Venta e instalación de hardware + licencias de software.</td>
    <td>Modelo SaaS modular, basado en vehículos activos y funcionalidades activadas.</td>
  </tr>
  <tr>
    <td><strong>Canales de distribución</strong></td>
    <td>Web app responsive, potencial app móvil futura.</td>
    <td>Web app, marketing digital y comunidad de flotas.</td>
    <td>Plataforma web + hardware instalado en sitio.</td>
    <td>Red de partners global, distribuidores locales e integradores de sistemas GPS.</td>
  </tr>
  <tr>
    <th rowspan="4">Análisis SWOT</th>
    <td><strong>Fortalezas</strong></td>
    <td>Enfoque especializado, experiencia de usuario optimizada, integraciones clave, análisis avanzado de consumo.</td>
    <td>Implementación ágil, sin hardware, fácil adopción en empresas medianas.</td>
    <td>Control físico riguroso, solución probada en industrias exigentes.</td>
    <td>Plataforma robusta, cobertura internacional, integración con más de 2,400 dispositivos GPS.</td>
  </tr>
  <tr>
    <td><strong>Debilidades</strong></td>
    <td>Nueva en el mercado, menor reconocimiento de marca, necesita consolidar confianza.</td>
    <td>No gestiona el flujo completo del pedido, enfoque parcial en flotas.</td>
    <td>Alto costo, dependencia de hardware, menor adaptabilidad en mercados emergentes.</td>
    <td>No gestiona pedidos entre proveedor y solicitante, requiere configuración técnica inicial.</td>
  </tr>
  <tr>
    <td><strong>Oportunidades</strong></td>
    <td>Alta informalidad en el sector, digitalización creciente en logística, necesidad de trazabilidad y control.</td>
    <td>Mayor conciencia en eficiencia de flotas y digitalización de costos operativos.</td>
    <td>Nuevos mercados industriales con enfoque en seguridad y control.</td>
    <td>Creciente necesidad de control logístico y monitoreo de distribución en países en desarrollo.</td>
  </tr>
  <tr>
    <td><strong>Amenazas</strong></td>
    <td>Aparición de soluciones similares, resistencia al cambio en empresas tradicionales, competencia ERP.</td>
    <td>SaaS especializados con mayor cobertura funcional (ERP, proveedores, logística).</td>
    <td>SaaS ágiles y sin hardware físico, que ofrecen soluciones más accesibles.</td>
    <td>SaaS más específicos y ligeros, enfocados exclusivamente en la trazabilidad de entregas.</td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores.

#### a. Diferenciación a través de especialización
Una de las principales estrategias de **FuelTrack** es la **especialización en el flujo completo de pedido de combustible**. A diferencia de soluciones como **Zavgar**, que están orientadas principalmente al control y análisis del consumo de combustible en flotas, nuestra plataforma se enfoca en las **interacciones B2B** entre empresas solicitantes y proveedores. Esto nos permite ofrecer un **control dedicado del pedido**, **gestión de la logística**, y **reportes detallados de consumo y entregas**, lo cual no está presente en la mayoría de las plataformas competidoras.

- **Táctica**: Desarrollar funcionalidades para la **validación automática de pagos**, **gestión de stock en tiempo real** y la **optimización del transporte** logrando la automatización de procesos que solo eran logrados de forma manual. Esto crea una ventaja frente a competidores como **FuelCloud**, que se centran más en el control físico del combustible y menos en la administración a nivel operativo.

#### b. Innovación en la interfaz de usuario y experiencia

El sistema de **FuelTrack** está diseñado para ofrecer una **experiencia de usuario optimizada**, algo que **Wialon**, **FuelCloud** y la propia **OSINERGMIN** no abordan en sus plataformas. Al ser una solución especializada y dirigida a una tarea específica, podemos dedicar más recursos en crear una interfaz intuitiva y procesos bien definidos brindando comodidad y seguridad a nuestros usuarios.

- **Táctica**: Diseñar una **interfaz intuitiva y consistente** que permita a los usuarios acceder a reportes de consumo, validar pedidos y coordinar logística con facilidad. Además, ofrecer **soporte y formación continua** para asegurar que los usuarios aprovechen al máximo todas las funcionalidades del sistema.

#### c. Flexibilidad en precios y modelo SaaS escalable
El modelo de precios de **FuelTrack** ofrece **planes escalables basados en suscripción**, lo que hace que sea más accesible para medianas y grandes empresas. Esto es más competitivo frente a **Wialon**, que puede no ser una opción viable para empresas que solo requieren una solución de pedidos de combustible. También es más asequible que **FuelCloud**, que requiere una inversión considerable en hardware, instalación y mantenimiento.

- **Táctica**: Ofrecer un modelo de suscripción flexible y **precios competitivos**, con **múltiples niveles de suscripción** adaptados a las necesidades de diferentes empresas. Esto permitirá que empresas de menor tamaño puedan acceder a la plataforma sin comprometer su presupuesto, a la vez que se asegura el crecimiento a largo plazo a medida que la empresa crece.

#### d. Aprovechamiento de la digitalización en la logística
El sector de la logística está experimentando una transformación digital acelerada. **FuelTrack** se aprovechará de esta tendencia buscando la integración de la plataforma con otras soluciones logísticas (como los sistemas de gestión de vehículos o flotas). De esta forma podemos ofrecer una solución más completa y eficiente.

- **Táctica**: Colaborar con empresas de **gestión de flotas** para optimizar el proceso de asignación de vehículos, cisternas y choferes. También se considerará la posibilidad de integrar **sensores IoT** en los camiones de reparto para un control más preciso sobre el combustible transportado y la entrega.

#### e. Expansión hacia mercados internacionales
Si bien **FuelTrack** está inicialmente orientada a empresas locales, el modelo de negocio y la flexibilidad de la plataforma la hacen ideal para expandirse a **mercados internacionales**. Competidores como **Wialon** ya tienen presencia en mercados globales, pero su enfoque en empresas grandes y sus altos costos de implementación pueden ser una barrera para empresas de menor tamaño, limitando su alcance.

- **Táctica**: Iniciar la expansión en mercados emergentes donde la digitalización en la logística es una necesidad creciente. Esto incluirá la **localización de la plataforma** (idioma, moneda, regulaciones locales) para facilitar la adaptabilidad de los nuevos mercados.

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

Para comprender mejor a nuestros segmentos objetivo, se han definido dos entrevistas diferenciadas según el segmento objetivo: 
- Proveedores de combustible
- Empresas con contratos de suministro (clientes corporativos)

---
#### A. Proveedores de Combustible

**Preguntas:**

1. ¿Cómo gestionan actualmente los pedidos de empresas clientes?
2. ¿Usan algún sistema digital para registrar pedidos o es manual?
3. ¿Qué pasos se siguen desde que un cliente hace un pedido hasta que se entregue?
4. ¿Cómo controlan que lo despachado coincida con lo solicitado?
5. ¿Qué tipo de reportes requieren generar (volúmenes, facturación, entregas, etc.)?
6. ¿Tienen un sistema para validar el stock antes de preparar el despacho de un pedido?
7. ¿Cómo hacen el seguimiento de los pedidos? ¿Informan al cliente en tiempo real?
8. ¿Qué problemas suelen ocurrir en el proceso de atención de pedidos empresariales?
9. ¿Cómo se realiza la conciliación de pagos con los clientes?
10. ¿Estarían dispuestos a integrar su sistema actual con una plataforma SaaS que unifique y centralice estos procesos?


**Preguntas complementarias:**

- ¿Qué edad tiene?
- ¿Cuál es su nivel de experiencia en logística o ventas?
- ¿Qué tipo de dispositivo usa en el trabajo? (PC, tablet, celular)
- ¿Qué aplicaciones o herramientas digitales usa en su día a día?
- ¿Cómo describiría su nivel de habilidad con la tecnología?

---

#### B. Empresas Solicitantes

**Preguntas:**

1. ¿Cómo solicitan actualmente combustible a su proveedor?
2. ¿Utilizan un sistema propio o envían pedidos por correo, WhatsApp, etc.?
3. ¿Cómo verifican que lo entregado coincida con lo solicitado?
4. ¿Tienen problemas con entregas incompletas o fuera de tiempo?
5. ¿Con qué frecuencia necesitan reportes de consumo, entregas o pagos?
6. ¿Qué tan importante es para ustedes tener trazabilidad de cada entrega?
7. ¿Quiénes son los responsables de validar pedidos y autorizar pagos?
8. ¿Cómo gestionan las reprogramaciones o cancelaciones de pedidos?
9. ¿Qué herramientas utilizan para monitorear el consumo mensual?
10. ¿Qué mejoras desearían ver en el proceso actual?

**Preguntas complementarias:**

- ¿Qué edad tiene?
- ¿En qué distrito vive y trabaja?
- ¿Qué nivel de estudios tiene?
- ¿Qué dispositivos utiliza más frecuentemente en el trabajo?
- ¿Qué aplicaciones o plataformas usa para su gestión operativa?
- ¿Cuáles son sus principales frustraciones en el proceso actual?

---

<h3>2.2.2. Registro de entrevistas</h3>

<h4><u>Entrevista 1</u></h4>

<p><strong>Nombres:</strong>
<strong>Apellidos:</strong>
<strong>Edad:</strong>
<strong>Distrito:</strong>

<p><strong>Captura de la entrevista:</strong><br>
<img src="img/entrevista1.png" alt="entrevista_segmento1" /></p>

<p><strong>Inicio / Fin:</strong>
<strong>Duración:</strong>
<strong>URL de Entrevista:</strong> 
<a href="" target="_blank">Ver video</a></p>

<h5><strong>Resumen:</strong></h5>
<p></p>

---
<h4><u>Entrevista 2</u></h4>

<p><strong>Nombres:</strong>
<strong>Apellidos:</strong>
<strong>Edad:</strong>
<strong>Distrito:</strong>

<p><strong>Captura de la entrevista:</strong><br>
<img src="img/entrevista2.png" alt="entrevista_segmento1" /></p>

<p><strong>Inicio / Fin:</strong>
<strong>Duración:</strong>
<strong>URL de Entrevista:</strong> 
<a href="" target="_blank">Ver video</a></p>

<h5><strong>Resumen:</strong></h5>
<p></p>

---
<h4><u>Entrevista 3</u></h4>

<p><strong>Nombres:</strong>
<strong>Apellidos:</strong>
<strong>Edad:</strong>
<strong>Distrito:</strong>

<p><strong>Captura de la entrevista:</strong><br>
<img src="img/entrevista3.png" alt="entrevista_segmento1" /></p>

<p><strong>Inicio / Fin:</strong>
<strong>Duración:</strong>
<strong>URL de Entrevista:</strong> 
<a href="" target="_blank">Ver video</a></p>

<h5><strong>Resumen:</strong></h5>
<p></p>

---
<h4><u>Entrevista 4</u></h4>

<p><strong>Nombres:</strong>
<strong>Apellidos:</strong>
<strong>Edad:</strong>
<strong>Distrito:</strong>

<p><strong>Captura de la entrevista:</strong><br>
<img src="img/entrevista4.png" alt="entrevista_segmento1" /></p>

<p><strong>Inicio / Fin:</strong>
<strong>Duración:</strong>
<strong>URL de Entrevista:</strong> 
<a href="" target="_blank">Ver video</a></p>

<h5><strong>Resumen:</strong></h5>
<p></p>

---
<h4><u>Entrevista 5</u></h4>

<p><strong>Nombres:</strong>
<strong>Apellidos:</strong>
<strong>Edad:</strong>
<strong>Distrito:</strong>

<p><strong>Captura de la entrevista:</strong><br>
<img src="img/entrevista5.png" alt="entrevista_segmento1" /></p>

<p><strong>Inicio / Fin:</strong>
<strong>Duración:</strong>
<strong>URL de Entrevista:</strong> 
<a href="" target="_blank">Ver video</a></p>

<h5><strong>Resumen:</strong></h5>
<p></p>

---
<h4><u>Entrevista 6</u></h4>

<p><strong>Nombres:</strong>
<strong>Apellidos:</strong>
<strong>Edad:</strong>
<strong>Distrito:</strong>

<p><strong>Captura de la entrevista:</strong><br>
<img src="img/entrevista6.png" alt="entrevista_segmento1" /></p>

<p><strong>Inicio / Fin:</strong>
<strong>Duración:</strong>
<strong>URL de Entrevista:</strong> 
<a href="" target="_blank">Ver video</a></p>

<h5><strong>Resumen:</strong></h5>
<p></p>

---

### 2.2.3. Análisis de entrevistas

#### SEGMENTO 1: Empresas solicitantes de combustible

**Características objetivas**
| Variable | Porcentaje | Observaciones |
|-----------|-------------|----------------|
| Edad entre 30 y 45 años | 100% | Todos los entrevistados tienen entre 33 y 45 años. |
| Cargo relacionado a logística | 100% | Los tres pertenecen a áreas de operaciones o logística. |
| Usa computadora y celular | 100% | Todos usan laptop/PC y móvil para sus actividades. |
| Utiliza WhatsApp para coordinar | 66% | 2 de 3 lo usan como canal principal con el proveedor. |
| Manejo de hojas Excel o Google | 100% | Todos gestionan sus pedidos manualmente en planillas. |
| Nivel medio de familiaridad digital | 100% | Dominan software básico (Drive, correo, hojas de cálculo). |

**Características subjetivas**
| Variable | Porcentaje | Observaciones |
|-----------|-------------|----------------|
| Necesita trazabilidad del pedido | 100% | Todos demandan claridad en el estado y avance del pedido. |
| Frustración por depósitos no validados | 66% | 2 de 3 se quejan de retrasos debido a validación manual. |
| Deseo de un sistema unificado | 100% | Los 3 expresaron querer centralizar todo el proceso. |
| Receptividad positiva a tecnología | 100% | Todos están abiertos a soluciones digitales con buena UX. |

**Insights del segmento solicitante**
- La **falta de trazabilidad en tiempo real** genera inseguridad y retrasa la toma de decisiones operativas.  
- La **validación manual de pagos** representa una fuente constante de frustración y pérdida de tiempo.  
- Existe una **disposición clara a migrar hacia sistemas digitales**, siempre que estos sean intuitivos y confiables.  
- Los usuarios perciben valor en **centralizar todas las etapas del pedido en una sola plataforma**, para evitar depender de varios canales (correo, WhatsApp, Excel).  


---

#### SEGMENTO 2: Proveedores de combustible

**Características objetivas**
| Variable | Porcentaje | Observaciones |
|-----------|-------------|----------------|
| Edad entre 39 y 48 años | 100% | Todos están en ese rango. |
| Cargo en operaciones/logística | 100% | Incluye jefes de planta, despacho o ventas. |
| Utiliza laptop/PC y celular | 100% | Equipamiento estándar en planta o administración. |
| Nivel de digitalización medio | 66% | 2 de 3 usan sistemas propios o ERPs básicos. |
| Gestión mediante correo y llamadas | 100% | El proceso actual es altamente manual. |

**Características subjetivas**
| Variable | Porcentaje | Observaciones |
|-----------|-------------|----------------|
| Problemas con conciliación bancaria | 100% | Todos mencionan validación lenta de pagos como cuello de botella. |
| Necesidad de validar stock antes de liberar | 66% | 2 de 3 destacaron esto como un punto crítico. |
| Dificultades en la asignación de vehículos | 66% | Errores de programación y disponibilidad afectan la entrega. |
| Deseo de automatización de procesos | 100% | Todos visualizan mejoras en eficiencia si se digitalizan etapas clave. |

**Insights del segmento proveedor**
- La **falta de sincronización entre pagos y liberación de pedidos** retrasa el flujo de despacho.  
- Los **procesos de stock y asignación de unidades** son críticos y podrían optimizarse mediante automatización.  
- La **digitalización parcial actual** (uso de ERPs básicos) muestra que hay apertura, pero no integración total con clientes.  
- Existe una **necesidad compartida de coordinación en tiempo real** con los solicitantes para evitar errores logísticos.

---

### Síntesis general
Ambos segmentos coinciden en que la gestión actual basada en canales dispersos y tareas manuales genera **ineficiencias, errores y demoras**. Los dos valoran la posibilidad de una **plataforma digital unificada** que mejore la **visibilidad del proceso**, **automatice validaciones** y **agilice la comunicación entre empresas**.



## 2.3. Needfinding.
### 2.3.1. User Personas.

a. User Persona 1: Empresas solicitantes de combustible
![userpersona_segmento1](img/userpersona_segmento1.png)

b. User Persona 2: Proveedores de combustible
![userpersona_segmento2](img/userpersona_segmento2.png)

### 2.3.2. User Task Matrix.

| **Tarea**                                      | **David Miller – Frecuencia** | **David Miller – Importancia** | **Ana Pérez – Frecuencia** | **Ana Pérez – Importancia** |
|------------------------------------------------|-------------------------------|---------------------------------|-----------------------------|------------------------------|
| Revisar nivel de stock de combustible          | Alta | Alta | Baja | Baja |
| Realizar pedido de combustible                 | Media | Alta | Alta | Alta |
| Validar confirmación de pedido                 | Alta | Alta | Alta | Alta |
| Hacer seguimiento a la entrega                 | Alta | Alta | Alta | Alta |
| Supervisar descarga y recepción                | Media | Alta | Media | Media |
| Evaluar proceso post-servicio                  | Baja | Media | Alta | Alta |
| Gestionar atención al cliente                  | Media | Alta | Alta | Alta |
| Revisar encuestas o feedback                   | Baja | Media | Media | Alta |

### 2.3.3. User Journey Mapping.

En el caso del **solicitante**, el recorrido empieza con la generación de un pedido por correo o llamada, seguido por la validación manual del depósito, la espera de aprobación por parte del proveedor, la coordinación del despacho, y finalmente el registro manual de la entrega.

En el caso del **proveedor**, el flujo parte desde la recepción del pedido, luego incluye la verificación del estado de cuenta, la aprobación manual, la asignación de planta y vehículo, y en muchos casos, la reprogramación por problemas de disponibilidad.

a. User Persona 1: Empresas solicitantes de combustible
![userjourneymap_userpersona1](img/userjourneymap_userpersona1.png)

b. User Persona 2: Proveedores de combustible
![userjourneymap_userpersona2](img/userjourneymap_userpersona2.png)

### 2.3.4. Empathy Mapping.

![empathymap_segmento1](img/empathymap_segmento1.png)
![empathymap_segmento1](img/empathymap_segmento2.png)

### 2.3.5. Ubiquitous Language. 

| Término | Definición | Segmentos relacionados |
|---------|------------|------------------------|
| **Requester (Solicitante)** | Usuario representante de una empresa requiere abastecimiento de combustible | Solicitante |
| **Supplier (Proveedor)** | Empresa que ofrece combustibles al por mayor y compite mediante precios, descuentos y promociones. | Proveedor |
| **Fuel (Combustible)** | Recurso energético que es ofertado por los proveedores. Ejemplos: gasohol, diésel, GNV. | Solicitante, Proveedor |
| **Plant (Planta)** | Punto de distribución del combustible perteneciente a al proveedor. | Solicitante, Proveedor |
| **Price per gallon (Precio por galón)** | Valor económico que el proveedor establece por cada galón de combustible. Puede variar según planta, tipo de combustible, etc. | Solicitante, Proveedor |
| **Discount (Descuento)** | Reducción aplicada sobre el precio ofrecido, ya sea por volumen, fidelización u otras condicioens. | Solicitante, Proveedor |
| **Quotation (Cotización)** | Propuesta formal que un proveedor genera detallando precios, productos, entre otras condiciones | Solicitante, Proveedor |
| **Price Table (Tabla de precios)** | Grilla o tabla que muestra los precios ofrecidos por planta, proveedor y tipo de combustible. | Solicitante |
| **Negotiation (Negociación)**   | Intercambio de condiciones entre solicitante y proveedor para alcanzar un acuerdo favorable para ambas partes. | Solicitante, Proveedor |
| **Consumption Volume (Volumen de consumo)** | Cantidad de combustible estimada que una empresa solicita regularmente en un periodo determinado. | Solicitante |
| **Purchase History (Historial de compras)** | Registro de cotizaciones y compras o pedidos previos hechos por el solicitante dentro del sistema. | Solicitante |

## 2.4. Requirements specification
## 2.4.1. User Stories

### Introducción
Este apartado presenta el conjunto de **Epics** y **User Stories** (incluyendo **Technical Stories** y **Spike Stories**) con **criterios de aceptación** en formato **Gherkin**. Las prioridades quedan **TBD** para definición del Product Owner. Los criterios son verificables, en presente y tercera persona, sin referencias a elementos de interfaz.

---

### Cuadro único de Epics & Stories

| Story ID | User/Rol | Priority | Epic | Title (verbo) | Description | Acceptance Criteria |
|---|---|---|---|---|---|---|
| **EP01** | Solicitante | TBD | EP01 | **Gestionar pedidos como solicitante** | Como solicitante, quiere registrar, consultar y ajustar pedidos con trazabilidad para reducir errores. | **Esc 1 – Registrar pedido**: **Given** que el solicitante completa datos válidos, **When** registra el pedido, **Then** el sistema crea el pedido con ID y estado inicial “Pendiente”. **Esc 2 – Consultar historial**: **Given** que existen pedidos, **When** el solicitante solicita su historial, **Then** el sistema retorna la lista con estados actuales. **Esc 3 – Editar antes de confirmación**: **Given** un pedido “Pendiente”, **When** solicita edición, **Then** el sistema permite modificar campos permitidos y registra cambios. |
| **EP02** | Proveedor | TBD | EP02 | **Gestionar pedidos como proveedor** | Como proveedor, quiere revisar y actualizar pedidos, coordinar asignaciones y notificar al cliente para ejecutar la entrega. | **Esc 1 – Ver pedidos entrantes**: **Given** que hay pedidos activos, **When** el proveedor los consulta, **Then** obtiene la lista con datos operativos y estado. **Esc 2 – Actualizar estado**: **Given** un pedido activo, **When** lo cambia a “Confirmado/En ruta/Entregado/Rechazado”, **Then** el nuevo estado queda persistido y trazado. **Esc 3 – Notificar cambios**: **Given** un cambio de estado, **When** se confirma, **Then** el sistema emite notificación al solicitante. |
| **EP03** | Todos | TBD | EP03 | **Asegurar identidad y acceso** | Como usuario del sistema, quiere autenticación, control por roles y MFA en operaciones sensibles para proteger la información. | **Esc 1 – Autenticar**: **Given** credenciales válidas, **When** inicia sesión, **Then** accede a recursos según su rol. **Esc 2 – Restringir por rol**: **Given** sesión activa, **When** intenta acceder a un recurso de otro rol, **Then** el acceso es denegado. **Esc 3 – MFA en operación crítica**: **Given** una acción sensible (p. ej., confirmación de pedido), **When** se ejecuta, **Then** requiere verificación adicional exitosa. |
| **EP04** | Visitante | TBD | EP04 | **Informar la propuesta (Landing)** | Como visitante, quiere entender beneficios y flujo para registrarse según su segmento. | **Esc 1 – Acceso público**: **Given** acceso sin autenticación, **When** solicita información, **Then** el sistema presenta contenido informativo y llamados a registro. **Esc 2 – Derivar registro por segmento**: **Given** interés de registro, **When** el visitante elige su segmento, **Then** el sistema lo redirige al flujo de alta correspondiente. |
| **US01** | Solicitante | TBD | EP01 | **Registrar pedido** | Como solicitante, quiere registrar pedidos para agilizar la solicitud y evitar llamadas. | **Esc 1 – Registro válido**: **Given** datos de pedido válidos, **When** envía la solicitud, **Then** el sistema crea el pedido con ID y estado “Pendiente”. **Esc 2 – Datos inválidos**: **Given** datos incompletos/incorrectos, **When** intenta registrar, **Then** el sistema rechaza y detalla validaciones. |
| **US02** | Solicitante | TBD | EP01 | **Consultar historial de pedidos** | Como solicitante, quiere consultar su historial con estados y detalles. | **Esc 1 – Con registros**: **Given** pedidos existentes, **When** consulta historial, **Then** el sistema retorna pedidos con estado actual (“Pendiente/Confirmado/En ruta/Entregado/Rechazado”). **Esc 2 – Sin registros**: **Given** ausencia de pedidos, **When** consulta, **Then** el sistema retorna lista vacía con causa. |
| **US03** | Solicitante | TBD | EP01 | **Editar pedido no confirmado** | Como solicitante, quiere editar parámetros antes de confirmación del proveedor. | **Esc 1 – Pedido editable**: **Given** pedido “Pendiente”, **When** solicita edición, **Then** el sistema permite modificar campos permitidos. **Esc 2 – Pedido no editable**: **Given** pedido “Confirmado” o superior, **When** solicita edición, **Then** el sistema impide cambios y registra el intento. |
| **US05** | Proveedor | TBD | EP02 | **Actualizar pedido** | Como proveedor, quiere actualizar estado e información operativa del pedido. | **Esc 1 – Cambio de estado**: **Given** un pedido activo, **When** cambia su estado a uno permitido, **Then** el sistema persiste la transición con marca de tiempo. **Esc 2 – Cambio inválido**: **Given** reglas de flujo, **When** intenta transición no permitida, **Then** el sistema rechaza y explica la regla. |
| **US06** | Proveedor | TBD | EP02 | **Notificar cambios al cliente** | Como proveedor, quiere que el cliente reciba notificaciones automáticas ante cambios del pedido. | **Esc 1 – Notificación por estado**: **Given** un cambio a “Confirmado/En ruta/Entregado/Rechazado”, **When** se registra, **Then** el sistema envía la notificación al solicitante. **Esc 2 – Falla de notificación**: **Given** indisponibilidad del servicio de mensajería, **When** se intenta notificar, **Then** el sistema registra el error y reintenta según política. |
| **US07** | Proveedor | TBD | EP02 | **Cancelar o rechazar pedido** | Como proveedor, quiere rechazar/cancelar pedidos con motivo para mantener claridad. | **Esc 1 – Rechazo con motivo**: **Given** imposibilidad de atención, **When** registra rechazo con motivo, **Then** el sistema cambia estado y asocia la justificación. **Esc 2 – Cancelación operativa**: **Given** pedido activo, **When** solicita cancelación con motivo, **Then** el sistema cambia a “Cancelado” y notifica al solicitante. |
| **US08** | Usuario | TBD | EP03 | **Iniciar sesión** | Como usuario, quiere iniciar sesión con credenciales válidas. | **Esc 1 – Éxito**: **Given** credenciales válidas, **When** inicia sesión, **Then** el sistema autentica y emite token de acceso. **Esc 2 – Falla**: **Given** credenciales inválidas, **When** intenta autenticarse, **Then** el sistema niega acceso sin revelar detalles. |
| **US09** | Visitante | TBD | EP03 | **Registrar cuenta** | Como visitante, quiere crear una cuenta con rol (Solicitante/Proveedor). | **Esc 1 – Alta válida**: **Given** datos válidos, **When** confirma el alta, **Then** el sistema crea la cuenta y habilita acceso. **Esc 2 – Alta inválida**: **Given** datos inválidos, **When** solicita alta, **Then** el sistema rechaza y detalla validaciones. |
| **US10** | Usuario | TBD | EP03 | **Recuperar contraseña** | Como usuario, quiere recuperar acceso por correo. | **Esc 1 – Correo registrado**: **Given** un correo válido, **When** solicita recuperación, **Then** el sistema genera token de restablecimiento y lo envía. **Esc 2 – Correo no registrado**: **Given** un correo no existente, **When** solicita recuperación, **Then** el sistema informa que no encuentra el identificador. |
| **US11** | Administrador | TBD | EP03 | **Restringir acceso por rol** | Como administrador, quiere que cada usuario acceda solo a recursos de su rol. | **Esc 1 – Acceso permitido**: **Given** rol y permisos, **When** accede a su recurso, **Then** el sistema permite la operación. **Esc 2 – Acceso denegado**: **Given** recurso de otro rol, **When** intenta acceso, **Then** el sistema deniega y audita. |
| **US12** | Solicitante | TBD | EP03 | **Verificar MFA en pedidos** | Como solicitante, quiere MFA al emitir pedidos para mayor seguridad. | **Esc 1 – Verificación exitosa**: **Given** MFA activo, **When** confirma un pedido, **Then** finaliza solo si la verificación adicional es válida. **Esc 2 – Verificación fallida**: **Given** MFA activo, **When** falla la verificación, **Then** el sistema cancela la acción. |
| **US13** | Visitante | TBD | EP04 | **Explorar landing** | Como usuario no autenticado, quiere visualizar la propuesta y caminos a registro. | **Esc 1 – Información visible**: **Given** acceso público, **When** solicita información, **Then** el sistema expone beneficios y flujo de valor. **Esc 2 – Derivación a registro**: **Given** interés, **When** elige registrarse, **Then** el sistema dirige al alta según segmento. |
| **TS01** | Developer | TBD | EP01 | **Exponer endpoint de pedidos (POST)** | Como developer, quiere un endpoint REST para registrar pedidos. | **Esc 1 – Request válido (201)**: **Given** payload válido, **When** invoca el endpoint, **Then** persiste y retorna 201 con ID. **Esc 2 – Request inválido (400)**: **Given** payload inválido, **When** invoca, **Then** retorna 400 con detalle de validación. |
| **TS02** | Developer | TBD | EP03 | **Emitir token de autenticación (JWT)** | Como developer, quiere servicio de autenticación con JWT. | **Esc 1 – Credenciales válidas (200)**: **Given** credenciales correctas, **When** solicita token, **Then** retorna JWT y vencimiento. **Esc 2 – Credenciales inválidas (401)**: **Given** credenciales incorrectas, **When** solicita, **Then** retorna 401. |
| **TS03** | Developer | TBD | EP02 | **Enviar notificaciones por cambio de estado** | Como developer, quiere servicio que emite notificaciones ante cambios de pedido. | **Esc 1 – Notificación emitida**: **Given** cambio de estado, **When** se confirma, **Then** el servicio envía notificación al destinatario. **Esc 2 – Error de mensajería**: **Given** caída del proveedor de mensajería, **When** intenta enviar, **Then** registra error y gestiona reintentos/backoff. |
| **TS04** | Developer | TBD | EP02 | **Registrar ubicación GPS en ruta** | Como developer, quiere registrar coordenadas para trazabilidad. | **Esc 1 – Registro exitoso**: **Given** coordenadas válidas, **When** se reciben, **Then** el sistema almacena con marca de tiempo y pedido asociado. **Esc 2 – Datos inválidos**: **Given** coordenadas inválidas, **When** se reciben, **Then** el sistema rechaza y audita. |
| **US14** | Visitante (Proveedor) | TBD | EP04 | **Consultar Home pública** | Como visitante proveedor, quiere un resumen del valor de la solución. | **Esc 1 – Resumen visible**: **Given** acceso público, **When** consulta el inicio, **Then** el sistema presenta propósito y propuesta de valor. **Esc 2 – CTA disponible**: **Given** interés del visitante, **When** solicita continuar, **Then** existe un camino a registro o contacto. |
| **US15** | Visitante | TBD | EP04 | **Conocer About Us** | Como visitante, quiere conocer el equipo y propósito para generar confianza. | **Esc 1 – Información del equipo**: **Given** acceso a About, **When** lo solicita, **Then** el sistema presenta información institucional verificable. **Esc 2 – Principios de la solución**: **Given** About, **When** lo consulta, **Then** el sistema presenta visión/valores. |
| **US16** | Visitante | TBD | EP04 | **Entender cómo funciona** | Como visitante, quiere comprender el flujo de operación. | **Esc 1 – Flujo comprensible**: **Given** sección “Cómo funciona”, **When** la revisa, **Then** entiende la interacción solicitante–proveedor a alto nivel. **Esc 2 – Casos de uso**: **Given** la sección, **When** la consulta, **Then** identifica ejemplos típicos del proceso. |
| **US17** | Visitante | TBD | EP04 | **Enviar contacto** | Como visitante, quiere remitir un mensaje de contacto. | **Esc 1 – Envío válido**: **Given** datos válidos, **When** remite el mensaje, **Then** el sistema registra y confirma recepción. **Esc 2 – Datos faltantes**: **Given** datos incompletos, **When** intenta enviar, **Then** el sistema rechaza e indica los campos requeridos. |
| **US18** | Proveedor | TBD | EP02 | **Aprobar pedido** | Como proveedor, quiere aprobar pedidos según stock disponible. | **Esc 1 – Aprobación con stock**: **Given** stock suficiente, **When** aprueba, **Then** el estado cambia a “Confirmado”. **Esc 2 – Rechazo por falta de stock**: **Given** stock insuficiente, **When** decide no aprobar, **Then** registra motivo y cambia a “Rechazado”. |
| **US19** | Proveedor | TBD | EP02 | **Despachar pedido** | Como proveedor, quiere marcar un pedido como despachado para notificar al cliente. | **Esc 1 – Despacho válido**: **Given** pedido “Confirmado”, **When** marca “En ruta/Despachado”, **Then** el sistema actualiza estado y registra hora de salida. **Esc 2 – Restricción sin confirmación**: **Given** pedido sin confirmar, **When** intenta despachar, **Then** el sistema rechaza la transición. |
| **US20** | Proveedor | TBD | EP02 | **Cerrar pedido** | Como proveedor, quiere cerrar el pedido cuando la entrega se confirma. | **Esc 1 – Cierre tras confirmación**: **Given** entrega confirmada por el solicitante, **When** ejecuta cierre, **Then** el pedido pasa a “Entregado/Finalizado” e impide modificaciones. **Esc 2 – Intento sin confirmación**: **Given** sin confirmación, **When** intenta cerrar, **Then** el sistema rechaza la acción. |
| **US21** | Proveedor | TBD | EP02 | **Generar reporte de ventas** | Como proveedor, quiere reportes operativos por rango de fechas. | **Esc 1 – Rango con datos**: **Given** fechas válidas con ventas, **When** solicita el reporte, **Then** el sistema genera el resumen. **Esc 2 – Rango sin datos**: **Given** rango vacío, **When** solicita, **Then** el sistema informa ausencia de resultados. |
| **US22** | Solicitante | TBD | EP01 | **Visualizar KPIs de pedidos (Solicitante)** | Como solicitante, quiere ver un resumen por estado. | **Esc 1 – Con datos**: **Given** pedidos, **When** consulta KPIs, **Then** ve conteos por estado. **Esc 2 – Sin datos**: **Given** sin pedidos, **When** consulta KPIs, **Then** el sistema indica que no hay registros. |
| **US23** | Proveedor | TBD | EP02 | **Visualizar KPIs de pedidos (Proveedor)** | Como proveedor, quiere ver resumen operativo por estado. | **Esc 1 – Con datos**: **Given** pedidos, **When** consulta, **Then** ve KPIs por estado. **Esc 2 – Error de carga**: **Given** falla de fuente, **When** consulta, **Then** el sistema indica error y permite reintentar. |
| **TS05** | Developer | TBD | EP03 | **Autenticar (endpoint login)** | Como developer, quiere endpoint de login. | **Esc 1 – 200 con token**: **Given** credenciales válidas, **When** envía request, **Then** obtiene 200 + JWT. **Esc 2 – 401**: **Given** credenciales inválidas, **When** envía request, **Then** obtiene 401. **Esc 3 – 500**: **Given** error interno, **When** procesa, **Then** retorna 500 y registra en logs. |
| **TS06** | Developer | TBD | EP03 | **Recuperar contraseña (endpoint)** | Como developer, quiere endpoint de recuperación. | **Esc 1 – Correo válido (202)**: **Given** correo existente, **When** solicita, **Then** genera token y envía email. **Esc 2 – 404**: **Given** correo no registrado, **When** solicita, **Then** retorna 404. **Esc 3 – 500**: **Given** fallo de correo, **When** envía, **Then** 500 y traza error. |
| **TS07** | Developer | TBD | EP03 | **Cerrar sesión (endpoint logout)** | Como developer, quiere endpoint para invalidar sesión. | **Esc 1 – 200**: **Given** token válido, **When** solicita logout, **Then** invalida sesión. **Esc 2 – 401**: **Given** token inválido/expirado, **When** solicita, **Then** retorna 401. |
| **US24** | Proveedor | TBD | EP02 | **Asignar vehículo a pedido** | Como proveedor, quiere asignar vehículo a pedido confirmado. | **Esc 1 – Asignación válida**: **Given** vehículo disponible y pedido “Confirmado”, **When** asigna, **Then** queda vinculado. **Esc 2 – Vehículo ocupado**: **Given** vehículo con conflicto, **When** intenta asignar, **Then** el sistema rechaza por superposición. |
| **US25** | Proveedor | TBD | EP02 | **Asignar conductor a pedido** | Como proveedor, quiere asignar conductor disponible. | **Esc 1 – Asignación válida**: **Given** conductor libre y pedido listo, **When** asigna, **Then** queda vinculado. **Esc 2 – Conflicto de horario**: **Given** conductor asignado en el mismo tramo, **When** intenta asignar, **Then** el sistema rechaza y explica conflicto. |
| **US26** | Proveedor | TBD | EP02 | **Validar disponibilidad de transporte** | Como proveedor, quiere verificar disponibilidad de vehículos antes de asignar. | **Esc 1 – No disponible por superposición**: **Given** vehículo con asignación en la misma ventana, **When** se consulta, **Then** se marca no disponible. **Esc 2 – Disponible**: **Given** sin conflictos, **When** se consulta, **Then** es seleccionable. **Esc 3 – Carrera concurrente**: **Given** asignación reciente por otro usuario, **When** intenta seleccionar, **Then** el sistema rechaza y actualiza disponibilidad. |
| **US27** | Usuario | TBD | EP03 | **Consultar perfil** | Como usuario, quiere ver su perfil para revisar datos. | **Esc 1 – Éxito**: **Given** sesión activa, **When** consulta, **Then** el sistema retorna su información de perfil. **Esc 2 – Error de fuente**: **Given** falla al obtener datos, **When** consulta, **Then** el sistema informa el error conservando la sesión. |
| **US28** | Usuario | TBD | EP03 | **Actualizar perfil** | Como usuario, quiere actualizar sus datos vigentes. | **Esc 1 – Guardado válido**: **Given** cambios válidos, **When** confirma, **Then** el sistema persiste cambios. **Esc 2 – Validación**: **Given** campos requeridos faltantes, **When** intenta guardar, **Then** el sistema rechaza la operación con detalle. |
| **US29** | Usuario | TBD | EP01/EP02 | **Buscar pedido por código** | Como usuario, quiere localizar rápidamente un pedido por su código. | **Esc 1 – Encontrado**: **Given** código existente, **When** busca, **Then** el sistema retorna el pedido. **Esc 2 – No encontrado**: **Given** código inexistente, **When** busca, **Then** el sistema informa ausencia de coincidencias. |
| **US30** | Usuario | TBD | EP01/EP02 | **Filtrar pedidos por estado** | Como usuario, quiere filtrar pedidos por estado operativo. | **Esc 1 – Filtro con resultados**: **Given** estado con coincidencias, **When** filtra, **Then** el sistema retorna solo los pedidos de ese estado. **Esc 2 – Sin resultados**: **Given** estado sin coincidencias, **When** filtra, **Then** el sistema informa que no hay resultados. |
| **US31** | Solicitante | TBD | EP01 | **Recibir notificación de aprobación/rechazo** | Como solicitante, quiere ser notificado cuando cambie el estado del pedido. | **Esc 1 – Notificación visible**: **Given** cambio de estado, **When** el solicitante accede, **Then** la notificación está disponible hasta marcar como leída. |
| **US32** | Solicitante | TBD | EP01 | **Recibir notificación de despacho** | Como solicitante, quiere ser notificado cuando el pedido salga a entrega. | **Esc 1 – Despacho confirmado**: **Given** cambio a “En ruta/Despachado”, **When** consulta, **Then** la notificación está disponible y asociada al pedido. |
| **US33** | Proveedor | TBD | EP02 | **Listar empresas solicitantes** | Como proveedor, quiere listar empresas para gestión de clientes. | **Esc 1 – Lista con datos**: **Given** empresas registradas, **When** consulta, **Then** el sistema retorna el listado con métricas operativas. **Esc 2 – Lista vacía**: **Given** sin empresas, **When** consulta, **Then** el sistema informa ausencia de registros. |
| **US34** | Proveedor | TBD | EP02 | **Consultar detalle de empresa** | Como proveedor, quiere ver detalle e historial de una empresa. | **Esc 1 – Con historial**: **Given** empresa con pedidos, **When** consulta, **Then** el sistema retorna pedidos, cantidades y fechas. **Esc 2 – Sin historial**: **Given** empresa sin pedidos, **When** consulta, **Then** el sistema informa que no hay historial. |
| **US35** | Solicitante | TBD | EP01 | **Visualizar gráfico de consumo** | Como solicitante, quiere visualizar consumo mensual. | **Esc 1 – Con datos**: **Given** pedidos históricos, **When** consulta, **Then** el sistema calcula y expone consumo mensual. **Esc 2 – Sin datos**: **Given** sin pedidos, **When** consulta, **Then** el sistema informa falta de datos suficientes. |
| **US36** | Proveedor | TBD | EP02 | **Visualizar gráfico de ventas** | Como proveedor, quiere visualizar ventas por mes. | **Esc 1 – Con datos**: **Given** despachos realizados, **When** consulta, **Then** el sistema expone totales por mes. **Esc 2 – Sin datos**: **Given** sin ventas, **When** consulta, **Then** el sistema informa que no hay datos suficientes. |
| **US37** | Usuario | TBD | EP01/EP02 | **Descargar reporte en PDF** | Como usuario, quiere descargar resúmenes operativos en PDF. | **Esc 1 – Exportación con datos**: **Given** periodo con información, **When** solicita exportar, **Then** el sistema genera el documento. **Esc 2 – Exportación sin datos**: **Given** periodo vacío, **When** solicita, **Then** el sistema informa que no hay contenido exportable. **Esc 3 – Falla de generación**: **Given** error de backend, **When** exporta, **Then** el sistema informa el fallo y conserva sesión. |
| **SP01** | Equipo (Spike) | TBD | EP02/EP03 | **Investigar conciliación de pagos y validación automática** | Como equipo, quiere investigar opciones de integración (e.g., pasarela/conciliación bancaria) para reducir retrasos por validación manual. | **Esc 1 – Documentación revisada**: **Given** proveedores de pago seleccionados, **When** se revisa documentación y webhooks, **Then** se documentan flujos recomendados. **Esc 2 – PoC mínimo**: **Given** entorno de pruebas, **When** se implementa PoC de conciliación, **Then** se registra en repo y se documentan resultados. **Esc 3 – Criterios de decisión**: **Given** hallazgos, **When** se comparan costos/riesgos, **Then** se proponen alternativas y estimaciones. |

---


### 2.4.2. Impact Mapping
![IM](img/Impact-Map.png)

### 2.4.3. Product Backlog

| # Orden | User Story Id | Título | Story Points (1/2/3/5/8) |
|---:|:---:|---|:---:|
| 01 | US01 | Crear nuevo pedido | 5 |
| 02 | US02 | Consultar historial de pedidos | 3 |
| 03 | US03 | Editar pedido no confirmado | 5 |
| 04 | US04 | Confirmar recepción de pedido | 3 |
| 05 | US05 | Actualizar pedido | 5 |
| 06 | US06 | Notificar cambios al cliente | 5 |
| 07 | US07 | Cancelar o rechazar pedido | 3 |
| 08 | US08 | Iniciar sesión | 3 |
| 09 | US09 | Registrar cuenta nueva | 3 |
| 10 | US10 | Recuperar contraseña | 3 |
| 11 | US11 | Restringir acceso por rol | 2 |
| 12 | US12 | Verificar MFA en pedidos | 5 |
| 13 | US13 | Explorar landing (pública) | 2 |
| 14 | TS01 | Exponer endpoint de pedidos (POST) | 5 |
| 15 | TS02 | Emitir token de autenticación (JWT) | 5 |
| 16 | TS03 | Enviar notificaciones por cambio de estado | 3 |
| 17 | TS04 | Registrar ubicación GPS en ruta | 5 |

**URL de evidencia de la gestión del Product Backlog:** https://trello.com/invite/b/68fc3234e665196894efe656/ATTId9f853897aa3fa54b670c6c712d4bf54825FB1B3/fueltrack-product-backlog


## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### Collect Domain Events
![Collect Domain Events](./img/CollectDomainEvents.png)
#### Refine Domain Events
![Refine Domain Events](./img/RefineDomainEvents.png)
#### Track Causes
![Track Causes](./img/TrackCauses.png)
#### Find aggregates & re-sort them
![Find aggregates & re-sort them](./img/Findaggregates&re-sortthem.png)
-------

#### 2.5.1.1. Candidate Context Discovery
| Contexto Candidato             | Descripción                                                        | Actores principales              |
|--------------------------------|--------------------------------------------------------------------|----------------------------------|
| Gestión de pedidos             | Administración y validación inicial de solicitudes de combustible  | - Empresa solicitante <br> - Proveedor |
| Gestión de pagos               | Registro, validación y conciliación de pagos asociados a pedidos.  | - Cliente <br> - Tesorería       |
| Gestión de inventario y despacho | Control del stock de combustible, asignación de vehículos y programación de despacho. | - Proveedor <br> - Área de logística |
| Gestión de entregas y trazabilidad | Monitoreo de la ruta, confirmación de entrega y visibilidad en tiempo real. | - Transportista <br> - Cliente   |

#### 2.5.1.2. Domain Message Flows Modeling

| Origen                          | Evento             | Destino                          | Resultado                 |
|---------------------------------|-------------------|----------------------------------|---------------------------|
| Empresa solicitante              | Realizar pedido   | Gestión de pedidos               | Pedido realizado          |
| Gestión de pedidos               | Pedido realizado  | Gestión de pagos                 | Registrar pago            |
| Gestión de pagos                 | Pago validado     | Gestión de inventario y despacho | Validar stock             |
| Gestión de inventario y despacho | Stock validado    | Gestión de entregas              | Asignar vehículo          |
| Gestión de entregas              | Pedido entregado  | Empresa solicitante              | Confirmación de entrega   |

#### 2.5.1.3. Bounded Context Canvases

### 2.5.2. Context Mapping
### 2.5.3. Software Architecture

#### 2.5.3.1. Software Architecture Context Level Diagrams
![Context Diagram de FuelTrack](./img/fueltrack-context.png)

**Descripción breve:**  
El diagrama de contexto muestra a **FuelTrack** como sistema central y sus interacciones con los **actores** (Cliente y Proveedor) y **sistemas externos** (Pasarela de Pagos, Sistema de Transporte y Servicio de Exportación).  
- **Cliente**: registra pedidos, realiza pagos y descarga facturas.  
- **Proveedor**: administra operadores/vehículos y actualiza estados de entrega.  
- **Pasarela de Pagos**: procesa transacciones con tarjeta.  
- **Sistema de Transporte**: consulta/actualiza el estado logístico.  
- **Servicio de Exportación**: genera reportes PDF/Excel.

---

#### 2.5.3.2. Software Architecture Container Level Diagrams
![Container Diagram de FuelTrack](./img/fueltrack-container.png)

**Descripción breve:**  
Descompone FuelTrack en **contenedores** y su comunicación:  
- **App Móvil (Kotlin + Jetpack Compose)**: interfaz para Cliente y Proveedor.  
- **Backend API**: expone servicios REST, orquesta reglas de negocio y conecta con externos.  
- **Base de Datos (MySQL/PostgreSQL)**: persistencia de pedidos, usuarios, operadores, vehículos y facturas.  
- **Integraciones**: Pasarela de Pagos, Sistema de Transporte y Exportación (PDF/Excel) vía HTTPS.

> La App Móvil se comunica con el Backend API (HTTPS). El Backend API accede a la Base de Datos (ORM/JDBC) y consume las APIs externas.

---

#### 2.5.3.3. Software Architecture Deployment Diagrams
![Deployment Diagram de FuelTrack](./img/fueltrack-deployment.png)

**Descripción breve:**  
Muestra la **distribución física** de los contenedores en el entorno de Producción:  
- **Smartphone Android**: ejecuta la App Móvil (Cliente/Proveedor).  
- **Servidor Backend (Render/AWS/DO)**: despliega la API REST.  
- **Servidor de Base de Datos gestionada**: aloja MySQL/PostgreSQL.  
- **Servicios Externos**: Pasarela de Pagos, Sistema de Transporte y Exportación.

> Flujo principal: App Móvil → Backend (HTTPS) → Base de Datos / Servicios Externos.


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
=======
dw