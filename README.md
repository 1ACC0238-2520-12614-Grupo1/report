# report

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

<h3>2.2.3. Análisis de entrevistas</h3>

<h4><u>SEGMENTO 1: Empresas solicitantes de combustible</u></h4>

<h5>Características objetivas:</h5>
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Variable</th>
      <th>Porcentaje</th>
      <th>Observaciones</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Edad entre 30 y 45 años</td><td>100%</td><td>Todos los entrevistados tienen entre 33 y 45 años.</td></tr>
    <tr><td>Cargo relacionado a logística</td><td>100%</td><td>Los tres pertenecen a áreas de operaciones o logística.</td></tr>
    <tr><td>Usa computadora y celular</td><td>100%</td><td>Todos usan laptop/PC y móvil para sus actividades.</td></tr>
    <tr><td>Utiliza WhatsApp para coordinar</td><td>66%</td><td>2 de 3 lo usan como canal principal con el proveedor.</td></tr>
    <tr><td>Manejo de hojas Excel o Google</td><td>100%</td><td>Todos gestionan sus pedidos manualmente en planillas.</td></tr>
    <tr><td>Nivel medio de familiaridad digital</td><td>100%</td><td>Dominan software básico (Drive, correo, hojas de cálculo).</td></tr>
  </tbody>
</table>

<h5>Características subjetivas:</h5>
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Variable</th>
      <th>Porcentaje</th>
      <th>Observaciones</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Necesita trazabilidad del pedido</td><td>100%</td><td>Todos demandan claridad en el estado y avance del pedido.</td></tr>
    <tr><td>Frustración por depósitos no validados</td><td>66%</td><td>2 de 3 se quejan de retrasos debido a validación manual.</td></tr>
    <tr><td>Deseo de un sistema unificado</td><td>100%</td><td>Los 3 expresaron querer centralizar todo el proceso.</td></tr>
    <tr><td>Receptividad positiva a tecnología</td><td>100%</td><td>Todos están abiertos a soluciones digitales con buena UX.</td></tr>
  </tbody>
</table>

<hr>

<h4><u>SEGMENTO 2: Proveedores de combustible</u></h4>

<h5>Características objetivas:</h5>
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Variable</th>
      <th>Porcentaje</th>
      <th>Observaciones</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Edad entre 39 y 48 años</td><td>100%</td><td>Todos están en ese rango.</td></tr>
    <tr><td>Cargo en operaciones/logística</td><td>100%</td><td>Incluye jefes de planta, despacho o ventas.</td></tr>
    <tr><td>Utiliza laptop/PC y celular</td><td>100%</td><td>Equipamiento estándar en planta o administración.</td></tr>
    <tr><td>Nivel de digitalización medio</td><td>66%</td><td>2 de 3 usan sistemas propios o ERPs básicos.</td></tr>
    <tr><td>Gestión mediante correo y llamadas</td><td>100%</td><td>El proceso actual es altamente manual.</td></tr>
  </tbody>
</table>

<h5>Características subjetivas:</h5>
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Variable</th>
      <th>Porcentaje</th>
      <th>Observaciones</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Problemas con conciliación bancaria</td><td>100%</td><td>Todos mencionan validación lenta de pagos como cuello de botella.</td></tr>
    <tr><td>Necesidad de validar stock antes de liberar</td><td>66%</td><td>2 de 3 destacaron esto como un punto crítico.</td></tr>
    <tr><td>Dificultades en la asignación de vehículos</td><td>66%</td><td>Errores de programación y disponibilidad afectan la entrega.</td></tr>
    <tr><td>Deseo de automatización de procesos</td><td>100%</td><td>Todos visualizan mejoras en eficiencia si se digitalizan etapas clave.</td></tr>
  </tbody>
</table>


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
### 2.4.1. User Stories
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP01</td>
      <td>Gestión de pedidos de combustible de solicitante</td>
      <td>Como usuario solicitante de combustible, quiero poder registrar mis pedidos fácilmente y con la capacidad de establecer parámetros específicos para evitar errores en la comunicación y recibir lo que necesito.</td>
      <td><strong>Escenario 1</strong>: Registro de pedido exitoso. En la plataforma, debería ver una sección en la plataforma para realizar nuevos pedidos, donde encuentre un formulario en el que pueda especificar lo que necesito y posteriormente registrar la orden. <br/> <strong>Escenario 2</strong>: Visualización de historial de pedidos. Debería ser capaz de visualizar una sección que muestre todos mis pedidos anteriores. <br/> <strong>Escenario 3</strong>: Edición antes de la confirmación. Antes de que los pedidos sean confirmados por los proovedores, debería tener la posibilidad de hacer ediciones a este o incluso poder cancelarlo.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Gestión de pedidos recibidos por el proovedoor</td>
      <td>Como usuario proovedor de combustible, quiero poder revisar los pedidos realizados por mis clientes, actualizar el estado de cada uno y dar actualizaciones en tiempo real a mis clientes.</td>
      <td><strong>Escenario 1</strong>: Visualización de pedidos entrantes. Dado que haya pedidos activos, Cuando el proveedor acceda a su panel, Entonces debería poder ver una lista de pedidos con detalles clave (cliente, ubicación, volumen, estado). <br/> <strong>Escenario 2</strong>: Actualización de estado del pedido.Dado que un pedido esté en curso,Cuando el proveedor actualice su estado (confirmado, en ruta, entregado),Entonces el sistema deberá reflejar el cambio en tiempo real. <br/> <strong>Escenario 3</strong>: Notificación a los clientes. Dado que el proveedor realice un cambio o actualización a un pedido, Cuando el cliente esté en la plataforma, entonces deberá ver una notificación con información de los cambios ocurridos.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Gestión de seguridad y acceso</td>
      <td>Como usuario de ambos segmentos de la plataforma, quiero que mis datos estén protegidos y acceder solo mediante autenticación segura, para garantizar la privacidad y evitar accesos no autorizados.</td>
      <td><strong>Escenario 1</strong>: Inicio de sesión seguro. Dado que el usuario tenga una cuenta, Cuando intente iniciar sesión con correo y contraseña, Entonces el sistema debe validar las credenciales y otorgar acceso solo si son correctas, evitando revelar información en caso de error. <br/> <strong>Escenario 2</strong>: Control de accesos según rol. Dado que un usuario (cliente o proveedor) haya iniciado sesión,Cuando intente acceder a secciones específicas de la plataforma, Entonces solo deberá poder ver y operar dentro de las funcionalidades permitidas por su tipo de cuenta. <br/> <strong>Escenario 3</strong>: Autenticación multifactor para operaciones. Dado que un cliente esté realizando un pedido,Cuando intente enviarlo o confirmarlo,Entonces el sistema deberá activar un segundo paso de verificación (código temporal o notificación) antes de procesar la acción..</td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP04</td>
      <td>Landing Page informativa y funcional</td>
      <td>Como parte de la solución, quiero ofrecer una landing page que muestre los beneficios y funcionalidades de FuelTrack, para captar el interés de potenciales usuarios.</td>
      <td><strong>Escenario 1</strong>: Visualización pública. Cuando alguien acceda al dominio principal sin estar autenticado, el sistema debe mostrar la landing page con secciones informativas, beneficios del sistema, segmentos objetivo y llamadas a la acción hacia login/registro. <br/> <strong>Escenario 2</strong>: Redirección según interés. Al hacer clic en 'Quiero registrarme', debe llevar al formulario correspondiente según el segmento.</td>
      <td>-</td>
    </tr>
  </tbody>
</table>


<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Crear nuevo pedido</td>
      <td>Como usuario de una empresa solicitante, quiero poder registrar un pedido directamente desde la plataforma agilizar el proceso y evitar llamadas.</td>
      <td>Dado que el usuario ingrese todos los campos requeridos, Cuando envíe el pedido, Entonces el sistema deberá procesarlo, asignar un ID único y enviarlo a los proovedores para que confirmen la orden.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Consultar historial de pedidos</td>
      <td>Como solicitante, quiero poder consultar mi historial de pedidos anteriores, y poder ver cada uno con información detallada. Además, debo ser capaz de filtrar y ordenar el historial según características específicas de los pedidos.</td>
      <td>Dado que el usuario acceda a la sección de seguimiento,Cuando seleccione un pedido,Entonces podrá ver si fue recibido, confirmado, en ruta o entregado.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Editar pedidos</td>
      <td>Como solicitante, quiero tener la posibilidad de editar parámetros, como el monto o dirección de entrega, de mis pedidos siempre y cuando estos todavía no hayan sido confirmados por el rpoovedor</td>
      <td>Dado que el usuario acceda a la sección de pedidos activo, Cuando seleccione un pedido que se encuentra sin confirmar ,Entonces podrá editar los parámetros del pedido.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Actualización de un pedido</td>
      <td>Como proveedor de combustible, quiero poder actualizar el estado e información de los pedidos en tiempo real, para mantener a mis clientes informados y organizar mejor mis entregas.</td>
      <td>Dado que existan pedidos activos para el proveedor, Cuando el proveedor los seleccione,Entonces el sistema deberá darle la posibilidad de hacerle cambios o darle actualizaciones.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Notificaciones a clientes sobre cambios</td>
      <td>Como proovedor, quiero que mis clientes reciban notificaciones automáticas cuando actualizo un pedido, para que estén al tanto del progreso sin tener que llamarlos.</td>
      <td>Dado que se modifique el estado o datos del pedido, Cuando se actualice a "confirmado", "en ruta" o "entregado", Entonces el sistema debe enviar una notificación push, correo o WhatsApp al cliente.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Cancelación o rechazo de pedidos</td>
      <td>Como proveedor de combustible, quiero poder rechazar o cancelar un pedido y enviar un mensaje al cliente explicando los motivos, para mantener una comunicación clara y evitar confusiones.</td>
      <td>Dado que el proveedor no pueda atender un pedido,Cuando seleccione la opción de cancelar o rechazar,Entonces el sistema deberá solicitarle ingresar un mensaje explicando el motivo y notificar al cliente con dicha información.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Inicio de sesión</td>
      <td>Como usuario registrado, quiero iniciar sesión con mi correo y contraseña, para acceder a mi cuenta de forma segura.</td>
      <td>Dado que el usuario tenga una cuenta, Cuando intente iniciar sesión,Entonces el sistema deberá validar sus credenciales y permitir el acceso solo si son correctas.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Registro de cuenta nueva</td>
      <td>Como visitante, Quiero crear una cuenta con correo, contraseña y rol (cliente o proveedor), Para acceder y comenzar a utilizar la plataforma.</td>
      <td>Dado que el usuario complete todos los campos requeridos, Cuando presione “Crear cuenta”, Entonces la cuenta deberá crearse correctamente y redirigirlo a su panel.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Recuperación de contraseña</td>
      <td>Como usuario, Quiero tener la posibilidad de recuperar mi contraseña mediante correo electrónico, Para no perder el acceso a mi cuenta en caso la olvide.</td>
      <td>Dado que el usuario no recuerde su contraseña, Cuando seleccione “¿Olvidaste tu contraseña?”,Entonces deberá recibir un correo con un enlace para restablecerla.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Acceso restringido por roles</td>
      <td>Como administrador de la plataforma, Quiero que los usuarios solo accedan a las secciones según su tipo de cuenta, Para evitar errores en el sistema</td>
      <td>Dado que un usuario acceda a la plataforma, Cuando vea las secciones que tiene disponible, Entonces verá únicamente las que son correspondientes a su rol.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Autenticación MFA para realizar pedidos</td>
      <td>Como empresa solicitante, Quiero que se me solicite una autenticación multifactor al momento de realizar un pedido, Para asegurar que solo personal autorizado pueda emitir órdenes de compra</td>
      <td>Dado que el cliente quiera registrar un pedido, Cuando complete los datos del formulario de registro, Entonces deberá recibir un código de autenticación y solo podrá finalizar el pedido tras ingresarlo correctamente.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Visualización del landing page</td>
      <td>Como usuario de la plataforma, quiero que el sistema muestre un landing page informativo para que los interesados conozcan los beneficios antes de registrarse.</td>
      <td>Dado que alguien acceda a la URL principal, Cuando no esté autenticado, Entonces deberá visualizar el landing page con secciones informativas y botones hacia login o registro.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>TS01</td>
      <td>Implementar endpoint REST para pedidos</td>
      <td>Como desarrollador, quiero implementar un endpoint RESTful para registrar pedidos, para que la aplicación frontend pueda enviar solicitudes válidas al backend.</td>
      <td>Dado que se realice una solicitud POST con datos válidos, Cuando se procese en el backend, Entonces deberá guardarse el pedido en la base de datos y devolver un código 201 con ID.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS02</td>
      <td>Servicio de autenticación y token</td>
      <td>Como desarrollador, quiero implementar un servicio de autenticación con generación de tokens, para proteger las rutas privadas de la plataforma.</td>
      <td>Dado que un usuario inicie sesión, Cuando las credenciales sean válidas, Entonces el sistema deberá generar un token JWT para acceso a recursos protegidos.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>Envío de notificaciones por cambios de estado</td>
      <td>Como desarrollador, quiero implementar un servicio que envíe notificaciones automáticas cuando un pedido cambie de estado, para mantener informados a los usuarios.</td>
      <td>Dado que el estado de un pedido sea actualizado, Cuando se complete la acción, Entonces deberá enviarse una notificación por correo o WhatsApp al usuario correspondiente.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>Registro y validación de ubicación GPS</td>
      <td>Como desarrollador, quiero permitir que los pedidos en ruta envíen coordenadas GPS, para poder visualizar la trazabilidad del transporte en tiempo real.</td>
      <td>Dado que un conductor envíe su ubicación, Cuando el backend reciba las coordenadas, Entonces deberán almacenarse y estar disponibles para visualización en el frontend.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Ver sección Home</td>
      <td>Como visitante (proveedor), quiero ver una sección de inicio que resuma el valor de FuelTrack para comprender rápidamente el objetivo del sistema.</td>
      <td>
        Escenario 1: Visualización de resumen del sistema.<br/>
        Escenario 2: Acceso a call to action desde Home.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Ver sección About Us</td>
      <td>Como visitante de ambos segmentos, quiero conocer quiénes están detrás de FuelTrack para confiar en el sistema.</td>
      <td>
        Escenario 1: Información visible del equipo.<br/>
        Escenario 2: Ver valores o misión.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Ver sección How it works?</td>
      <td>Como visitante de ambos segmentos, quiero entender cómo funciona FuelTrack paso a paso para evaluar si se ajusta a mis necesidades.</td>
      <td>
        Escenario 1: Comprensión del flujo de pedidos.<br/>
        Escenario 2: Interacción clara entre usuarios.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Enviar mensaje de contacto</td>
      <td>Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información.</td>
      <td>
        Escenario 1: Envío exitoso de mensaje.<br/>
        Escenario 2: Validación de campos obligatorios.<br/>
        Escenario 3: Confirmación visual del envío.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Aprobar pedido</td>
      <td>Como proveedor, quiero aceptar según el stock disponible para evitar conflictos de distribución.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Aprobación de pedido con stock disponible</strong>
            <ul>
              <li>Dado que el proveedor tiene stock suficiente,</li>
              <li>Cuando aprueba el pedido,</li>
              <li>Entonces el estado cambia a “Aprobado”.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Envío de motivo</strong>
            <ul>
              <li>Dado que el proveedor decide no aprobar un pedido por un periodo de tiempo,</li>
              <li>Cuando revise los pedidos,</li>
              <li>Entonces el sistema solicita ingresar una razón.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Marcar pedido como despachado</td>
      <td>Como proveedor, quiero marcar cuándo un pedido sale a entrega para notificar al cliente.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Despacho exitoso de un pedido</strong>
            <ul>
              <li>Dado que el proveedor tiene un pedido aprobado,</li>
              <li>Cuando marca el pedido como despachado,</li>
              <li>Entonces el estado cambia a “Despachado”.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Restricción de despacho sin aprobación previa</strong>
            <ul>
              <li>Dado que el proveedor intenta despachar un pedido sin aprobación,</li>
              <li>Cuando ejecuta la acción,</li>
              <li>Entonces el sistema impide el cambio de estado y muestra un mensaje.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Cerrar pedido</td>
      <td>Como proveedor, quiero cerrar el pedido cuando el cliente confirme la entrega para finalizar el proceso.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Cierre correcto del pedido tras confirmación</strong>
            <ul>
              <li>Dado que el solicitante ya confirmó la entrega,</li>
              <li>Cuando el proveedor cierra el pedido,</li>
              <li>Entonces este no puede modificarse más.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Intento de cierre sin confirmación previa</strong>
            <ul>
              <li>Dado que el proveedor intenta cerrar el pedido,</li>
              <li>Cuando el solicitante aún no ha confirmado la entrega,</li>
              <li>Entonces el sistema impide esta acción.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Generar reporte de ventas</td>
      <td>Como proveedor, quiero generar reportes de ventas para tener registro de operaciones realizadas.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Generación de reporte con datos disponibles</strong>
            <ul>
              <li>Dado que el proveedor selecciona un rango de fechas válido,</li>
              <li>Cuando solicita el reporte,</li>
              <li>Entonces se genera un archivo con los datos de ventas.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Generación sin datos en el rango</strong>
            <ul>
              <li>Dado que el proveedor selecciona un rango sin ventas,</li>
              <li>Cuando solicita el reporte,</li>
              <li>Entonces el sistema informa que no hay resultados.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Descarga del archivo generado</strong>
            <ul>
              <li>Dado que el reporte se genera correctamente,</li>
              <li>Cuando finaliza el proceso,</li>
              <li>Entonces el proveedor puede descargar el archivo.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Ver resumen de pedidos (Solicitante)</td>
      <td>Como solicitante, quiero ver un resumen de mis pedidos para identificar cuántos están en proceso o completados.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Visualización de resumen con datos disponibles</strong>
            <ul>
              <li>Dado que el solicitante tiene pedidos registrados,</li>
              <li>Cuando accede a su dashboard,</li>
              <li>Entonces visualiza los KPIs por estado: pendientes, aprobados, despachados, finalizados y rechazados.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Sin pedidos registrados</strong>
            <ul>
              <li>Dado que el solicitante no tiene pedidos,</li>
              <li>Cuando accede al dashboard,</li>
              <li>Entonces ve un mensaje informando “No hay pedidos registrados”.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Error al cargar datos del resumen</strong>
            <ul>
              <li>Dado que el solicitante accede al dashboard,</li>
              <li>Cuando ocurre un error de carga,</li>
              <li>Entonces el sistema muestra un mensaje e intenta recargar los datos automáticamente.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Ver resumen de pedidos (Proveedor)</td>
      <td>Como proveedor, quiero ver un resumen de pedidos gestionados y pendientes para organizar a los clientes.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Visualización de KPIs con datos</strong>
            <ul>
              <li>Dado que el proveedor tiene pedidos registrados,</li>
              <li>Cuando accede a su dashboard,</li>
              <li>Entonces ve KPIs de pedidos: pendientes, aprobados, rechazados, despachados y finalizados.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Sin datos registrados</strong>
            <ul>
              <li>Dado que no hay pedidos registrados,</li>
              <li>Cuando se carga el dashboard,</li>
              <li>Entonces los KPIs se muestran con valor cero y un mensaje informativo.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Fallo en la carga del resumen</strong>
            <ul>
              <li>Dado que el proveedor accede al dashboard,</li>
              <li>Cuando hay un error de conexión,</li>
              <li>Entonces se muestra una alerta con opción para reintentar.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS05</td>
      <td>Endpoint: Login</td>
      <td>Como developer, quiero un endpoint para autenticar usuarios.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Autenticación exitosa</strong>
            <ul>
              <li>Dado que el developer incluye credenciales válidas en el request,</li>
              <li>Cuando lo envía al endpoint de autenticación,</li>
              <li>Entonces recibe un token JWT y un status 200 como respuesta.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Credenciales inválidas</strong>
            <ul>
              <li>Dado que el developer incluye credenciales incorrectas en el request,</li>
              <li>Cuando se procesa la solicitud,</li>
              <li>Entonces se retorna status 401 con un mensaje de error.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Error interno del servidor</strong>
            <ul>
              <li>Dado que el developer realiza un request y ocurre un problema en el backend,</li>
              <li>Cuando se procesa la autenticación,</li>
              <li>Entonces se retorna status 500 con un mensaje genérico de error.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>TS06</td>
      <td>Endpoint: Recuperar contraseña</td>
      <td>Como developer, quiero un endpoint para que permita enviar correo de recuperación.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Solicitud válida</strong>
            <ul>
              <li>Dado que el developer envía un request con un correo que existe en la base de datos,</li>
              <li>Cuando el request llega al endpoint de recuperación,</li>
              <li>Entonces el sistema genera un token y envía el correo de recuperación.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Correo inexistente</strong>
            <ul>
              <li>Dado que el developer envía un request con un correo no registrado,</li>
              <li>Cuando se procesa la solicitud,</li>
              <li>Entonces se retorna status 404 y no se envía ningún correo.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Error en el envío del correo</strong>
            <ul>
              <li>Dado que el developer ejecuta la acción y ocurre un fallo en el servicio de correo,</li>
              <li>Cuando se intenta enviar el mensaje,</li>
              <li>Entonces se retorna status 500 y se registra el error en los logs del servidor.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>TS07</td>
      <td>Endpoint: Logout</td>
      <td>Como developer, quiero un endpoint para cerrar sesión.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Logout exitoso</strong>
            <ul>
              <li>Dado que el developer envía un token de sesión válido,</li>
              <li>Cuando llama al endpoint de logout,</li>
              <li>Entonces la sesión se invalida y se retorna status 200.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Token inválido o expirado</strong>
            <ul>
              <li>Dado que el developer incluye un token no válido o expirado,</li>
              <li>Cuando se llama al endpoint de logout,</li>
              <li>Entonces se retorna status 401 y no se realiza ninguna acción.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Falla del servidor</strong>
            <ul>
              <li>Dado que el developer realiza un request y ocurre un error interno en el servidor,</li>
              <li>Cuando se procesa el logout,</li>
              <li>Entonces se retorna status 500 con un mensaje genérico.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US24</td>
      <td>Asignar vehículo a pedido</td>
      <td>Como proveedor, quiero asignar un vehículo a un pedido aprobado para organizar la logística.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Asignación válida</strong>
            <ul>
              <li>Dado que el proveedor tiene un pedido aprobado y un vehículo libre disponible,</li>
              <li>Cuando selecciona el vehículo para asignarlo,</li>
              <li>Entonces queda asignado correctamente al pedido.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Vehículo ocupado</strong>
            <ul>
              <li>Dado que el proveedor intenta asignar un vehículo que ya está ocupado,</li>
              <li>Cuando realiza la acción,</li>
              <li>Entonces el sistema muestra un mensaje indicando que el vehículo no está disponible.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Falla durante la asignación</strong>
            <ul>
              <li>Dado que el proveedor intenta asignar un vehículo y ocurre un error en el backend,</li>
              <li>Cuando se ejecuta la asignación,</li>
              <li>Entonces se muestra un mensaje de error y no se vincula ningún vehículo.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Asignar conductor a pedido</td>
      <td>Como proveedor, quiero asignar un conductor para completar la información de despacho.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Conductor disponible</strong>
            <ul>
              <li>Dado que el proveedor tiene un pedido con vehículo asignado y el conductor está libre,</li>
              <li>Cuando selecciona al conductor,</li>
              <li>Entonces este se vincula correctamente al pedido.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Conductor ya asignado en misma franja horaria</strong>
            <ul>
              <li>Dado que el conductor está asignado a otro pedido en el mismo horario,</li>
              <li>Cuando se intenta asignarlo,</li>
              <li>Entonces el sistema bloquea la acción y muestra un mensaje de conflicto.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Error al guardar</strong>
            <ul>
              <li>Dado que el proveedor intenta guardar la asignación y ocurre una falla técnica,</li>
              <li>Cuando realiza la acción,</li>
              <li>Entonces se muestra un mensaje de error y no se realiza el vínculo.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Validar disponibilidad de transporte</td>
      <td>Como proveedor, quiero saber qué vehículos están disponibles antes de asignarlos para vincularlos correctamente.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Vehículo no disponible por superposición</strong>
            <ul>
              <li>Dado que el proveedor visualiza el listado de vehículos,</li>
              <li>Cuando un vehículo está asignado a otro pedido para la misma fecha y hora estimada,</li>
              <li>Entonces el sistema lo muestra como no disponible.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Vehículo disponible</strong>
            <ul>
              <li>Dado que el proveedor visualiza un vehículo sin conflictos de agenda,</li>
              <li>Cuando se carga el listado de vehículos,</li>
              <li>Entonces dicho vehículo se muestra como seleccionable.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Conflicto en tiempo real</strong>
            <ul>
              <li>Dado que el proveedor intenta seleccionar un vehículo que fue asignado recientemente por otro usuario,</li>
              <li>Cuando realiza la acción,</li>
              <li>Entonces el sistema bloquea la selección y muestra un mensaje de actualización.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US27</td>
      <td>Ver perfil de usuario</td>
      <td>Como usuario registrado, quiero ver mis datos de perfil para revisar mi información registrada.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Visualización exitosa del perfil</strong>
            <ul>
              <li>Dado que el usuario tiene sesión activa,</li>
              <li>Cuando accede a su perfil,</li>
              <li>Entonces ve su nombre, correo y rol.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Error en la carga de datos</strong>
            <ul>
              <li>Dado que el usuario accede a su perfil y ocurre un error al obtener los datos,</li>
              <li>Cuando se carga la vista,</li>
              <li>Entonces se muestra un mensaje de error y se sugiere reintentar.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Restricción de datos de otros usuarios</strong>
            <ul>
              <li>Dado que el usuario tiene sesión activa,</li>
              <li>Cuando intenta ver otro perfil,</li>
              <li>Entonces el sistema restringe el acceso y muestra su propia información.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Editar datos de perfil</td>
      <td>Como usuario registrado, quiero editar mis datos para mantener mi información actualizada.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Edición y guardado exitoso</strong>
            <ul>
              <li>Dado que el usuario modifica uno o más campos del formulario,</li>
              <li>Cuando la información ingresada es válida,</li>
              <li>Entonces el sistema guarda los cambios correctamente.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Campo obligatorio vacío</strong>
            <ul>
              <li>Dado que el usuario deja un campo obligatorio vacío,</li>
              <li>Cuando intenta guardar,</li>
              <li>Entonces el sistema muestra un mensaje de validación indicando el campo requerido.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Error del servidor al guardar</strong>
            <ul>
              <li>Dado que el usuario intenta guardar y ocurre un fallo en el servidor,</li>
              <li>Cuando se realiza la acción,</li>
              <li>Entonces se muestra un mensaje de error y los datos ingresados permanecen visibles.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US29</td>
      <td>Buscar pedido por código</td>
      <td>Como usuario de ambos segmentos, quiero buscar un pedido específico por su código para encontrarlo rápidamente.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Ingresar a la búsqueda</strong>
            <ul>
              <li>Dado que el usuario presione el botón de filtrar,</li>
              <li>Cuando ingrese la opción del código en las grillas,</li>
              <li>Entonces podrá buscar su pedido según su código.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Pedido encontrado</strong>
            <ul>
              <li>Dado que el usuario escribe un código válido,</li>
              <li>Cuando existe un pedido con ese código,</li>
              <li>Entonces se muestra el resultado correspondiente.</li>
            </ul>
          </li>
          <li><strong>Escenario 3: Pedido no encontrado</strong>
            <ul>
              <li>Dado que el usuario digita un código no correspondiente a ningún pedido,</li>
              <li>Cuando finaliza la búsqueda,</li>
              <li>Entonces el sistema muestra un mensaje de que no hay coincidencias.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US30</td>
      <td>Filtrar pedidos por estado</td>
      <td>Como usuario de ambos segmentos, quiero filtrar mis pedidos por estado (pendiente, aprobado, entregado) para facilitar la revisión.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Aplicar filtro correctamente</strong>
            <ul>
              <li>Dado que el usuario selecciona un estado,</li>
              <li>Cuando se aplica el filtro,</li>
              <li>Entonces solo se muestran los pedidos con ese estado.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: No hay pedidos en ese estado</strong>
            <ul>
              <li>Dado que el usuario selecciona un estado que no tiene coincidencias,</li>
              <li>Cuando ejecuta el filtro,</li>
              <li>Entonces se muestra un mensaje indicando que no hay pedidos para ese estado.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US31</td>
      <td>Recibir notificación de aprobación</td>
      <td>Como solicitante, quiero recibir una notificación cuando un pedido sea aprobado o rechazado para estar informado.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Visualización de notificación</strong>
            <ul>
              <li>Dado que el proveedor cambia el estado del pedido,</li>
              <li>Cuando el solicitante inicia sesión,</li>
              <li>Entonces recibe la notificación del evento en la página y en las notificaciones.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Pedido actualizado desde otra sesión</strong>
            <ul>
              <li>Dado que el solicitante aún no ha leído la notificación,</li>
              <li>Cuando actualiza la interfaz,</li>
              <li>Entonces la notificación se mantiene visible hasta que sea marcada como leída.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US32</td>
      <td>Notificación de pedido despachado</td>
      <td>Como solicitante, quiero recibir una notificación cuando un pedido haya sido despachado para estar informado.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Pedido marcado como despachado</strong>
            <ul>
              <li>Dado que el proveedor marca el pedido como despachado,</li>
              <li>Cuando el solicitante consulta su cuenta,</li>
              <li>Entonces recibirá la notificación correspondiente en la página como en las notificaciones.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Visualización posterior del evento</strong>
            <ul>
              <li>Dado que el pedido fue despachado anteriormente,</li>
              <li>Cuando el solicitante accede en otro momento,</li>
              <li>Entonces la notificación sigue disponible hasta ser archivada o leída.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US33</td>
      <td>Ver listado de empresas</td>
      <td>Como proveedor, quiero ver una lista de empresas solicitantes para identificar a mis clientes frecuentes.</td>
      <td>
        <ul>
          <li><strong>Escenario 1: Visualización del listado</strong>
            <ul>
              <li>Dado que el proveedor accede al módulo de empresas,</li>
              <li>Cuando se carga el listado,</li>
              <li>Entonces se muestran nombre, pedidos activos y total histórico por empresa.</li>
            </ul>
          </li>
          <li><strong>Escenario 2: Lista vacía o sin datos</strong>
            <ul>
              <li>Dado que el proveedor accede al módulo y no hay empresas registradas,</li>
              <li>Cuando se carga la vista,</li>
              <li>Entonces se muestra un mensaje indicando que no hay empresas disponibles.</li>
            </ul>
          </li>
        </ul>
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US34</td>
      <td>Ver detalles de empresa</td>
      <td>Como proveedor, quiero ver información detallada de una empresa solicitante para analizar su historial de pedidos.</td>
      <td>
        Dado que el proveedor selecciona una empresa, Cuando se carga el detalle, Entonces visualiza pedidos realizados, cantidades solicitadas y fechas. Escenario 2: Dado que el proveedor selecciona una empresa que aún no ha realizado pedidos, Cuando se accede a su perfil, Entonces se muestra un mensaje indicando que no hay historial disponible.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US35</td>
      <td>Ver gráfico de consumo (Solicitante)</td>
      <td>Como solicitante, quiero ver un gráfico de mi consumo mensual para tener control sobre el uso del combustible.</td>
      <td>
        Escenario 1: Dado que el solicitante ha realizado pedidos,Cuando accede al módulo de reportes, Entonces se visualiza un gráfico con galones consumidos por mes. Escenario 2: Dado que el solicitante no ha hecho pedidos aún, Cuando accede al gráfico, Entonces se muestra un mensaje de que no hay datos suficientes.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US36</td>
      <td>Ver gráfico de ventas (Proveedor)</td>
      <td>Como proveedor, quiero ver un gráfico de ventas por mes para monitorear el rendimiento del negocio.</td>
      <td>
        Dado que el proveedor ha despachado pedidos, Cuando accede al módulo de reportes, Entonces se visualiza un gráfico con las ventas mensuales totales. Escenario 2: Dado que el proveedor no ha realizado ventas aún, Cuando accede al gráfico, Entonces se muestra un mensaje de que no hay datos suficientes.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US37</td>
      <td>Descargar reporte PDF</td>
      <td>Como usuario de ambos segmentos, quiero descargar un resumen de pedidos o ventas en formato PDF para archivarlo o compartirlo.</td>
      <td>
        Escenario 1: Dado que el usuario hace clic en "Descargar", Cuando hay datos en el periodo seleccionado, Entonces se genera un archivo PDF descargable. Escenario 2: Dado que el usuario no tiene registros en el periodo seleccionado, Cuando se solicita la descarga, Entonces el sistema notifica que no hay contenido para exportar. Escenario 3: Dado que el usuario intenta descargar el archivo y ocurre un error en el backend al generar el PDF, Cuando hace clic en el botón de descargar, Entonces se muestra un mensaje de error sin afectar la sesión.
      </td>
      <td>-</td>
    </tr>
  </tbody>
</table>

### 2.4.2. Impact Mapping
![IM](img/Impact-Map.png)
### 2.4.3. Product Backlog
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>#Orden</th>
      <th>ID</th>
      <th>User Story</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>01</td><td>US-01</td><td>Crear nuevo pedido</td><td>5</td></tr>
    <tr><td>02</td><td>US-02</td><td>Consultar historial de pedidos</td><td>3</td></tr>
    <tr><td>03</td><td>US-03</td><td>Editar pedidos</td><td>5</td></tr>
    <tr><td>04</td><td>US-04</td><td>Confirmar pedido recibido</td><td>3</td></tr>
    <tr><td>05</td><td>US-05</td><td>Actualización de un pedido</td><td>5</td></tr>
    <tr><td>06</td><td>US-06</td><td>Notificaciones a clientes sobre cambios</td><td>5</td></tr>
    <tr><td>07</td><td>US-07</td><td>Cancelación o rechazo de pedidos</td><td>3</td></tr>
    <tr><td>08</td><td>US-08</td><td>Inicio de sesión</td><td>3</td></tr>
    <tr><td>09</td><td>US-09</td><td>Registro de cuenta nueva</td><td>3</td></tr>
    <tr><td>10</td><td>US-10</td><td>Recuperación de contraseña</td><td>3</td></tr>
    <tr><td>11</td><td>US-11</td><td>Acceso restringido por roles</td><td>2</td></tr>
    <tr><td>12</td><td>US-12</td><td>Autenticación MFA para realizar pedidos</td><td>5</td></tr>
    <tr><td>13</td><td>US-13</td><td>Visualización del landing page</td><td>2</td></tr>
    <tr><td>14</td><td>TS-01</td><td>Implementar endpoint REST para pedidos</td><td>5</td></tr>
    <tr><td>15</td><td>TS-02</td><td>Servicio de autenticación y token</td><td>5</td></tr>
    <tr><td>16</td><td>TS-03</td><td>Envío de notificaciones por cambios de estado</td><td>3</td></tr>
    <tr><td>17</td><td>TS-04</td><td>Registro y validación de ubicación GPS</td><td>5</td></tr>
  </tbody>
</table>


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