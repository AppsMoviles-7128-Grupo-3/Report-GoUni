# COURSE PROJECT - 7128

---

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Aplicaciones para Dispositivos - 7128</strong><br>
    <strong>Profesor: Jorge Luis Mayta Guillermo</strong><br>
    <br>Informe del Trabajo Final</br>
</p>

<p align="center">
    <strong>Startup: (por definir)</strong><br>
    <strong>Producto: GoUni </strong>
</p>

### Team Members:

<div style="display: flex; justify-content: center; align-items: center;">

| **Member**                          | **Code**    |
|-------------------------------------|-------------|
|          |   |
| David Polanco, Alessandro           | u202122232  |
| Chirinos Zúñiga, Rodrigo  | u202217804  |
|      |   |

</div>

<p align="center">
    <strong>Abril 2025</strong>
</p>

---

# Registro de Versiones del Informe

### _TB1_

Para el desarrollo de la entrega **TB1**, se optó por dividir el trabajo de la siguiente forma:

| **Versión**  | **Fecha** | **Autor**                         | **Descripción**                                                                                                   |
|--------------|-----------|-----------------------------------|-------------------------------------------------------------------------------------------------------------------|
| **#01 - TB1**| 19/04/25  |        |  |
|              | 19/04/25  | David Polanco, Alessandro         |  |
|              | 19/04/25  | Chirinos Zúñiga, Rodrigo  |  |
|              | 19/04/25  |     |   |

---

# Project Report Collaboration Insights

**URL del repositorio de GitHub de la organización:** [https://github.com/orgs/AppsMoviles-7128-Grupo](https://github.com/orgs/AppsMoviles-7128-Grupo)

![ProjectReportCollaborationInsigths.png](assets/images/ProjectReportCollaboration/ProjectReportCollaborationInsigths.png)

---

# Contenido

## Tabla de contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
    - [_TB1_](#_tb1_)
    - [_TP_](#_tp_)
    - [_TB2_](#_tb2_)
    - [_TF_](#_tf_)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Studen Outcome](#studen-outcome)
- [**Capítulo I: Presentación.**](#capítulo-i-introducción)
    - [**1.1 Startup Profile.**](#11-startup-profile)
        - [**1.1.1 Descripción del startup.**](#111-descripción-del-startup)
        - [**1.1.2 Perfiles de los integrantes del equipo.**](#112-perfiles-de-los-integrantes-del-equipo)
    - [**1.2 Solution Profile.**](#12-solution-profile)
        - [**1.2.1 Antecedentes y Problemática.**](#121-antecedentes-y-problemática)
        - [**1.2.2 Lean UX Process.**](#122-lean-ux-process)
            - [**1.2.2.1 Lean UX Problem Statements.**](#1221-lean-ux-problem-statements)
            - [**1.2.2.2 Lean UX Assumptions.**](#1222-lean-ux-assumptions)
            - [**1.2.2.3 Lean UX Hypothesis Statements.**](#1223-lean-ux-hypothesis-statements)
            - [**1.2.2.4 Lean UX Canvas.**](#1224-lean-ux-canvas)
    - [**1.3 Segmentos objetivo.**](#13-segmentos-objetivo)

- [**Capítulo II: Requirements Elicitation & Analysis.**](#capítulo-ii-requirements-elicitation--analysis)
    - [**2.1 Competidores.**](#21-competidores)
        - [**2.1.1 Análisis competitivo.**](#211-análisis-competitivo)
        - [**2.1.2 Estrategias y tácticas frente a competidores.**](#212-estrategias-y-tácticas-frente-a-competidores)
    - [**2.2 Entrevistas.**](#22-entrevistas)
        - [**2.2.1 Diseño de entrevistas.**](#221-diseño-de-entrevistas)
        - [**2.2.2 Registro de entrevistas.**](#222-registro-de-entrevistas)
        - [**2.2.3 Análisis de entrevistas.**](#223-análisis-de-entrevistas)
    - [**2.3 Needfinding.**](#23-needfinding)
        - [**2.3.1 User Personas.**](#231-user-personas)
        - [**2.3.2 User Task Matrix.**](#232-user-task-matrix)
        - [**2.3.3 User Journey Mapping.**](#233-user-journey-mapping)
        - [**2.3.4 Empathy Mapping.**](#234-empathy-mapping)
        - [**2.3.5 As-is Scenario Mapping.**](#235-as-is-scenario-mapping)
    - [**2.4 Ubiquitous Language.**](#24-ubiquitous-language)

- [**Capítulo III: Requirements Specification.**](#capítulo-iii-requirements-specification)
    - [**3.1 To-Be Scenario Mapping.**](#31-to-be-scenario-mapping)
    - [**3.2 User Stories.**](#32-user-stories)
    - [**3.3 Impact Mapping.**](#33-impact-mapping)
    - [**3.4 Product Backlog.**](#34-product-backlog)

- [**Capítulo IV: Solution Software Design.**](#capítulo-iv-product-design)
    - [**4.1 Strategic-Level Domain-Driven-Design.**](#41-strategic-level-domain-driven-design)
        - [**4.1.1 Event Storming.**](#411-event-storming)
            - [**4.1.1.1 Candidate Context Discovery.**](#4111-candidate-context-discovery)
            - [**4.1.1.2 Domain Message Flows Modeling.**](#4112-domain-message-flows-modeling)
            - [**4.1.1.3 Bounded Context Canvases.**](#4113-bounded-context-canvases)
        - [**4.1.2 Context Mapping.**](#42-context-mapping)
        - [**4.1.3 Software Architecture.**](#413-software-architetcture)
            - [**4.1.3.1 Software Architecture Context Level Diagrams.**](#4131-software-architecture-context-level-diagrams)
            - [**4.1.3.2 Software Architecture Container Level Diagrams.**](#4132-software-architecture-container-level-diagrams)
            - [**4.1.3.3 Software Architecture Deployment Level Diagrams.**](#4133-software-architecture-deployment-level-diagrams)
    - [**4.2 Tactical-Level Domain-Driven Design.**](#42-tactical-level-domain-driven-design)
        - [**4.2.1 Bounded Context: <Bounded Context Name>.**](#421-bounded-context:-<bounded-context-name>)
          - [**4.2.1.1 Domain Layer.**](#4211-domain-layer)
          - [**4.2.1.2 Interface Layer.**](#4212-interface-layer)
          - [**4.2.1.3 Application Layer.**](#4213-application-layer)
          - [**4.2.1.4 Infrastructure Layer.**](#4214-infrastructure-layer)
          - [**4.2.1.5 Bounded Context Software Architecture Component Level Diagrams.**](#4215-bounded-context-software-architecture-component-level-diagrams)
          - [**4.2.1.6 Bounded Context Software Architecture Code Level Diagrams.**](#4216-bounded-context-software-architecture-code-level-diagram)
            - [**4.2.1.6.1 Bounded Context Domain Layer Class Diagrams.**](#42161-bounded-context-domain-layer-class-diagrams)
            - [**4.2.1.6.2 Bounded Context Database Design Diagram.**](#42162-bounded-context-database-design-diagram)

- [**Capítulo V: Solution UI/UX Design.**](#capítulo-v-solution-uiux-design)
    - [**5.1 Product Design.**](#51-product-design)
        - [**5.1.1 Style Guidelines.**](#511-style-guidelines)
          - [**5.1.1.1 General Style Guidelines.**](#5111-general-style-guidelines)
      - [**5.1.2 Information Architecture.**](#512-information-architecture)
          - [**5.1.2.1 Organization Systems.**](#5121-organization-systems)
          - [**5.1.2.2 Labelling Systems.**](#5122-labelling-systems)
          - [**5.1.2.3 SEO Tags and Meta Tags.**](#5123-seo-tags-and-meta-tags)
          - [**5.1.2.4 Searching Systems.**](#5124-searching-systems)
          - [**5.1.2.5 Navigation Systems.**](#5125-navigation-systems)


- [**Capítulo VI: Product Implementation, Validation & Deployment.**](#capítulo-vi-product-implementation-validation--deployment)
    - [**6.2.1 Sprint 1.**](#621-sprint-1)
        - [**6.2.1.1 Sprint Planning 1.**](#6211-sprint-planning-1)
        - [**6.2.1.2 Sprint Backlog 1.**](#6212-sprint-backlog-1)
        - [**6.2.1.3 Development Evidence for Sprint Review.**](#6213-development-evidence-for-sprint-review)
        - [**6.2.1.4 Testing Suite Evidence for Sprint Review.**](#6214-testing-suite-evidence-for-sprint-review)
        - [**6.2.1.5 Execution Evidence for Sprint Review.**](#6215-execution-evidence-for-sprint-review)
        - [**6.2.1.6 Services Documentation Evidence for Sprint Review.**](#6216-services-documentation-evidence-for-sprint-review)
        - [**6.2.1.7 Software Deployment Evidence for Sprint Review.**](#6217-software-deployment-evidence-for-sprint-review)
        - [**6.2.1.8 Team Collaboration Insights during Sprint.**](#6218-team-collaboration-insights-during-sprint)
    - [**6.3 Validation Interviews.**](63-validation-interviews)
        - [**6.3.1 Diseño de Entrevistas.**](#631-diseño-de-entrevistas)
        - [**6.3.2 Registro de Entrevistas.**](#632-registro-de-entrevistas)
        - [**6.3.3 Evaluaciones según heurísticas.**](#633-evaluaciones-según-heurísticas)
    - [**6.4 Video About-The-Product.**](#64-video-about-the-product)
  
- [**Conclusiones.**](#conclusiones)
    - [**Conclusiones y Recomendaciones.**](#conclusiones-y-recomendaciones)
    - [**Video About-the-Team.**](#about-the-team)

- [**Bibliografía.**](#bibliografia)

- [**Anexos.**](#anexos)

---

# [Student Outcome](#student-outcome)

---
# [**Capítulo I: Introducción.**](#capítulo-i-introducción)

## [**1.1 Startup Profile.**](#11-startup-profile)

### [**1.1.1 Descripción del startup.**](#111-descripción-del-startup)

GoUni es una startup fundada por un grupo de estudiantes de la Facultad de Ingeniería de la Universidad Peruana de Ciencias Aplicadas (UPC) con el objetivo de abordar las preocupaciones y desafíos que enfrentan los estudiantes universitarios al movilizarse. Ante las dificultades para acceder a un transporte cómodo y asequible, estamos desarrollando una plataforma innovadora que permite compartir viajes en vehículos particulares entre compañeros de universidad. Con UniGo, buscamos no solo ofrecer una alternativa económica y social al transporte público, sino también reducir la congestión vehicular y promover un uso más eficiente de los recursos. Nuestro equipo, apasionado por la tecnología y la sostenibilidad, está comprometido en brindar una solución de movilidad segura, conveniente y colaborativa para la comunidad estudiantil.

### Misión:
Nuestra misión es facilitar el transporte universitario a través de una plataforma accesible y colaborativa que permita a los estudiantes compartir viajes de manera segura y económica, mejorando su experiencia de movilidad diaria.

### Visión:
Aspiramos a ser líderes en movilidad estudiantil, reconocidos por nuestro compromiso con la sostenibilidad, la eficiencia y la satisfacción de nuestros usuarios, proporcionando una experiencia de transporte innovadora y socialmente responsable para estudiantes del Perú.

### [**1.1.2 Perfiles de los integrantes del equipo.**](#112-perfiles-de-los-integrantes-del-equipo)

<table>
  <tr>
    <th>Miembros del equipo</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td><img src="assets/images/profiles/" alt="" width="140" height="140"></td>
    <td>//////////////</td>
  </tr>

   <tr>
    <td><img src="assets/images/profiles/AlessandroDavid.png" width="140" height="140"></td>
    <td>Mi nombre es Alessandro David y tengo 21 años. Yo estoy cursando
    la carrera de Ingenieria de Software en la UPC y ando en 7mo ciclo. Me gusto
    demasiado mi eleccion referente a la carrera dado que me interesan mucho todos los temas
    que tenga que ver con la tecnologia y las tendencias de este rubro. Me gusta leer libros de desarrollo
    personal y tambien trenar y montar bicicleta. Me considero una persona empática, comprometida, y siempre atento 
    a resolver cualquier problema que me concierna. Como integrante del grupo de Open Source me comprometo
    a cooperar con todo lo asignado en el trabajo y apoyar a mis compañeros con cualquier duda que quieran absolver.</td>
  </tr>

  <tr>
    <td><img src="https://github.com/user-attachments/assets/9895e794-a88f-4436-a332-8d5c8112f9cb" width="100" height="150"></td>
    <td>Tengo 20 años, soy un estudiante de la carrera de Ingeniería de Software, considero que soy una persona responsable y de escucha activa. Estoy comprometido con mis compañeros en realizar un buen trabajo y así aprender todos en el proceso. También tengo conocimientos en programación en C++, HTML, CSS y JavaScript.</td>
  </tr>

  <tr>
    <td><img src="./assets/images/profiles/" width="140" height="140"></td>
    <td>}}}}}}}}}}}}}}}}}}}}}</td>
  </tr>

</table>

---

## [**1.2. Solution Profile.**](#12-solution-profile)

### [**1.2.1. Antecedentes y Problemática.**](#121-antecedentes-y-problemática)

### Antecedentes:
La movilidad estudiantil en zonas urbanas ha sido un reto constante para los estudiantes universitarios, especialmente en grandes ciudades como Lima, donde la congestión vehicular y la falta de opciones de transporte eficientes afectan directamente la calidad de vida. El transporte público convencional a menudo resulta incómodo, inseguro, y poco fiable, mientras que tener un vehículo propio no es una opción accesible para muchos estudiantes debido a los altos costos de adquisición y mantenimiento.

El auge de la tecnología y las aplicaciones móviles ha abierto nuevas posibilidades para abordar este problema mediante soluciones innovadoras como el carpooling, que no solo promueven un uso más eficiente de los recursos, sino que también ofrecen una alternativa más económica y socialmente integrada al transporte tradicional.

UniGo surge en este contexto con la misión de proporcionar una solución que permita a los estudiantes universitarios compartir viajes en vehículos particulares. Con esta plataforma, buscamos no solo aliviar los problemas de transporte, sino también fomentar la sostenibilidad, reducir el tráfico, y mejorar la seguridad en los desplazamientos diarios hacia las universidades.

### Problemática (5Ws y 2Hs)
##### What (Qué)

###### ¿Cuál es el problema?

La problemática percibida por nuestra startup radica en la falta de opciones de transporte eficiente, seguro y económico para los estudiantes universitarios. Los estudiantes, en su mayoría, dependen de un transporte público lento, incómodo y en muchos casos inseguro, lo que repercute en su bienestar y rendimiento académico.

##### When (Cuando)

###### ¿Cuándo sucede el problema?

Este problema se presenta diariamente cuando los estudiantes necesitan trasladarse a sus universidades. El transporte público suele tener horarios y rutas poco optimizados, lo que se traduce en largas esperas, trayectos prolongados, y una experiencia de viaje incómoda y, en algunos casos, insegura.

##### Where (Donde)

###### ¿A dónde se dirige?
El servicio está diseñado para ser una herramienta de alto impacto para los estudiantes que buscan un equilibrio económico y confortable en sus desplazamientos hacia la universidad.

###### ¿Dónde surge el problema?
El problema se deriva de cuestiones socioculturales, como la inseguridad en Perú durante la espera impredecible de los transportes públicos, que puede resultar tediosa. Asimismo, el costo elevado de utilizar constantemente autos particulares para desplazarse resulta ser una opción poco viable para la economía de los estudiantes que no cuenten con los recursos económicos necesarios.

##### Who (Quién)
###### ¿Quiénes están involucrados? ¿Quién lo utilizará?
Los usuarios del sistema serán principalmente estudiantes universitarios. Por un lado, aquellos que dispongan de un vehículo y busquen generar ganacias  durante su recorrido  hacia la universidad. Por otro lado, se encuentran los estudiantes que utilizarán este servicio y su rol sera el de pasajero.

##### Why (Por qué)
###### ¿Cuál es la causa del problema?
La causa principal del problema es la ineficiencia del transporte público y la falta de alternativas que sean tanto accesibles económicamente como confiables en términos de seguridad y comodidad. Además, el uso de vehículos privados de manera individual contribuye a la congestión vehicular, afectando la calidad de vida en las ciudades.

### ¿Cuáles son las 2H?

##### How (Cómo)
###### ¿Cómo se utilizará el producto?
El producto sera empleado mediante una  plataforma web, donde los estudiantes podrán programar sus viajes, conocer los horarios y rutas disponibles, realizar pagos en línea y recibir actualizaciones en tiempo real sobre el estado del servicio.

###### ¿Cómo lograremos desarrollar la correcta gestión del proceso de carpooling entre estudiantes?
Después de que el estudiante inicia sesión en el sistema y elige su universidad de destino, el sistema presenta los conductores disponibles que viajan por la misma ruta. Si el estudiante está conforme con la hora estimada de llegada y la calificación del conductor, puede reservar un viaje y proceder con el pago. Una vez que el conductor complete todos los asientos, debe indicar que no hay más asientos disponibles. Después de llegar a destino, los usuarios tienen la opción de calificar al conductor.

##### How much (Cuánto)
###### ¿Cuál es la magnitud del problema?
En Lima, se registran numerosos problemas socioculturales, como la delincuencia y el tráfico, que pueden ser especialmente perjudiciales para los estudiantes que suelen llevar consigo sus teléfonos celulares y computadoras portátiles (INEI, 2021). Estudios previos han demostrado que el crimen en Lima afecta negativamente la calidad de vida de los residentes, exacerbando los niveles de estrés y ansiedad (Traverso, 2020). Además, la situación del tráfico en la ciudad ha sido objeto de preocupación constante, ya que los estudiantes corren el riesgo de llegar tarde a clases o exámenes debido a las frecuentes paradas de los autobuses en cada tramo (Municipalidad Metropolitana de Lima, 2023).

###### Quienes seran los beneficiados por el servicio?
Los estudiantes universitarios que deseen una alternativa que sea eficiente, cómoda y económica, así como aquellos que busquen generar ingresos o reducir sus gastos en combustible durante su viaje hacia la universidad.

---

### [**1.2.2. Lean UX Process.**](#122-lean-ux-process)

#### [**1.2.2.1. Lean UX Problem Statements.**](#1221-lean-ux-problem-statements)


Nuestro servicio de carpooling para estudiantes universitarios se diseñó con el fin de mejorar la experiencia de transporte de nuestros usuarios, reducir el estrés, el riesgo de robos, la fatiga por autobuses abarrotados y los costos elevados. Sin embargo, hemos notado que el servicio no está cumpliendo completamente con estos objetivos. Los estudiantes siguen enfrentando problemas de estrés y fatiga, y los costos no se han reducido significativamente. Además, la falta de coincidencia en horarios y rutas entre los usuarios y la baja ocupación de los vehículos están limitando la efectividad del servicio.

¿Cómo podemos mejorar nuestro servicio para asegurar que los estudiantes universitarios encuentren compañeros de viaje compatibles, optimicen el uso de los vehículos y reduzcan significativamente los costos y las dificultades asociadas con el transporte diario?

### Aspectos

#### Domain:
Movilidad y transporte compartido para estudiantes universitarios.

#### Customer Segments:

- ##### Estudiantes Universitarios
Estudiantes que necesitan desplazarse a sus universidades y buscan una alternativa al transporte público o a los vehículos particulares. Estos estudiantes enfrentan desafíos como el estrés, la inseguridad y el costo elevado del transporte.

- ##### Propietarios de Vehículos Privados
Estudiantes que poseen vehículos y desean compartir sus viajes con otros para reducir gastos en combustible y maximizar el uso de sus vehículos.

#### Pain Points:

- ##### Estudiantes

###### Estrés y Fatiga:
La congestión en el transporte público y las largas esperas causan estrés y fatiga, afectando negativamente su experiencia de desplazamiento.

###### Inseguridad:
La inseguridad durante el viaje, especialmente en autobuses abarrotados, es una preocupación constante.

###### Costo Elevado:

Los gastos en transporte son una carga financiera significativa para los estudiantes.

- ##### Propietarios de Vehículos Privados

###### Oportunidades de Rellenar Asientos:
Hay una falta de mecanismos eficientes para asegurar que todos los asientos disponibles en un viaje compartido sean utilizados, reduciendo el potencial de ingresos por compartir el viaje.
#### Gap:
Existe una brecha en el mercado de transporte compartido específico para estudiantes universitarios. Aunque hay aplicaciones de viajes compartidos, no están adaptadas a las necesidades y horarios específicos de los estudiantes, lo que dificulta la formación de compañeros de viaje compatibles y la optimización del uso del vehículo.

#### Vision/Strategy:
Crear una plataforma de carpooling diseñada específicamente para estudiantes universitarios que permita una conexión efectiva entre compañeros de viaje con horarios y rutas compatibles. La plataforma debe abordar el estrés y la inseguridad relacionados con el transporte, al mismo tiempo que ofrece una solución económica y eficiente para los estudiantes que desean compartir sus viajes y reducir costos.

#### [**1.2.2.2. Lean UX Assumptions.**](#1222-lean-ux-assumptions)

Assumptions play a crucial role in identifying project risks and fostering team participation and active engagement.

#### User Assumptions

**Who is the user?**

- The user is any university student interested in a faster, safer, and more efficient way to commute to their university.

**Where does our product fit into their work or life?**

- Our product integrates seamlessly into users' daily lives, providing an efficient and accessible transportation solution. It helps avoid stress, risks of theft, fatigue caused by overcrowded buses, and high transportation costs.

**What problems does our product need to solve?**

- Our product addresses inefficiencies in commuting, scheduling conflicts among travel companions, and low vehicle occupancy that limit carpooling effectiveness. It also aims to reduce transportation costs and enhance the overall experience for students.

**When and how is our product used?**

- The product is used daily by students to coordinate shared rides to and from the university. It matches users with compatible routes and schedules.

**How should our product look and behave?**

- The product should be intuitive and user-friendly, featuring an interface that enables users to efficiently plan and coordinate trips. It must function reliably, ensuring users can quickly find travel companions and complete their trips safely and affordably.

#### Business Assumptions

**We believe that:**

- Our customers need a platform that allows them to coordinate and share rides to the university in a safe, efficient, and economical way. Students are seeking to reduce travel costs and times while minimizing stress associated with daily transportation.

- These needs can be addressed with a mobile application that connects university students, enabling them to share car rides, lower transportation expenses, and improve their daily commuting experience.

**The #1 value my customer wants from my service:**

- **For students offering rides:** A platform that helps fill empty seats in their vehicles, optimizing costs and maximizing the efficiency of their daily commutes.

- **For students seeking rides:** A secure and economical way to reach the university, reducing travel time and the stress of overcrowded public transportation.

- **For universities:** A solution that reduces traffic congestion and environmental impact, promoting a more sustainable mode of transportation for their students.

**Additional benefits for customers:**

- **Student Networking:** Opportunities to connect with fellow university students, building a social and academic network that enriches their university experience.

- **Incentives and Rewards:** Frequent users can access discounts, special promotions, or rewards for participating in the carpooling system.

- **Feedback and Continuous Improvement:** Users can provide and receive feedback on trips, enhancing service quality and ensuring a positive experience for all involved.

#### [**1.2.2.3. Lean UX Hypothesis Statements.**](#1223-lean-ux-hypothesis-statements)

**Creemos que** al simplificar el proceso de registro y la verificación de usuarios en nuestra plataforma, aumentaremos la tasa de conversión de nuevos estudiantes que se inscriben para usar el servicio de carpooling. Sabremos que hemos tenido éxito cuando observemos un aumento significativo en el número de cuentas activas en los primeros 7 días después del lanzamiento.

**Creemos que** al ofrecer una sección destacada para los “Viajes Más Populares de la Semana”, aumentaremos la participación de los estudiantes en la plataforma. Sabremos que hemos tenido éxito cuando observemos un aumento en las visitas a esta sección y una mayor interacción con los viajes destacados.

**Creemos que** al proporcionar métricas claras sobre la eficiencia de los viajes (como ahorro de tiempo y dinero), motivaremos a más estudiantes a utilizar nuestro servicio de manera regular. Sabremos que hemos tenido éxito cuando veamos un aumento en la frecuencia de uso del servicio y una mayor satisfacción de los usuarios.

**Creemos que** al incorporar un sistema de recompensas para conductores y pasajeros frecuentes, aumentaremos la retención de usuarios y generaremos un uso más constante de la plataforma. Sabremos que hemos tenido éxito cuando observemos un aumento en la lealtad de los usuarios y una mayor participación activa en la plataforma.


#### [**1.2.2.4. Lean UX Canvas.**](#1224-lean-ux-canvas)

| **Lean UX Canvas**                                                                                                                                                               | **Fecha:** 19/04/2024                                                                                                              | **Iteración:** 1 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|------------------|
| **1. Business Problem:**                                                                                                                                                         | **5. Solutions:**                                                                                                                  | **2. Business Outcomes:** |
| - La falta de un sistema eficiente y confiable que conecte a los estudiantes universitarios que necesitan compartir transporte hacia la universidad.                              | - **Plataforma de Carpooling:** Sistema que permita a los estudiantes ofrecer y encontrar viajes compartidos hacia la universidad. | - Aumento en el número de usuarios activos y viajes compartidos realizados. |
| - Aunque existen alternativas de transporte público y privado, los estudiantes enfrentan problemas como el tráfico, el costo elevado, la inseguridad y la pérdida de tiempo.      | - **Verificación de Usuarios:** Proceso de verificación para garantizar la seguridad y confianza entre los usuarios.               | - Reducción de costos de transporte para los estudiantes. |
| - Además, la falta de una solución que optimice el uso de vehículos privados entre estudiantes afecta la movilidad y la sostenibilidad.                                           | - **Sistema de Recompensas:** Incentivos para conductores y pasajeros frecuentes.                                                  | - Mejora en la eficiencia y sostenibilidad del transporte universitario. |
|                                                                                                                                                                                  | - **Funcionalidad de Chat:** Herramienta de comunicación directa entre conductores y pasajeros para coordinar detalles del viaje.  | - Reconocimiento y adopción de la plataforma como la opción preferida para el carpooling entre estudiantes universitarios. |
|                                                                                                                                                                                  | - **Integración de Rutas:** Sincronización con aplicaciones de mapas para optimizar las rutas y tiempos de viaje.                  | |
|                                                                                                                                                                                  | - **Notificaciones en Tiempo Real:** Alertas sobre cambios en la ruta o disponibilidad de viajes.                                  | |

| **3. Users:**                                                                                                                                                                   | **6. Hypotheses:**                                                                                                                                       | **4. User Outcomes & Benefits:** |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| - Los usuarios principales serán estudiantes universitarios que buscan una alternativa de transporte más económica, segura y conveniente para llegar a sus campus.              | - Creemos que al simplificar el proceso de registro y la verificación de usuarios en nuestra plataforma, aumentaremos la tasa de conversión de nuevos estudiantes. | - **Estudiantes:** Ahorro de tiempo y dinero, reducción del estrés del transporte público, y mayor seguridad al viajar con compañeros de estudio. |
| - También incluye a los conductores que desean compartir sus vehículos para reducir costos y contribuir a una movilidad más sostenible.                                          | - Creemos que al implementar una función de mensajería entre conductores y pasajeros, mejoraremos la coordinación y la confianza en nuestra plataforma.   | - **Conductores:** Reducción de costos operativos y mayor sostenibilidad en sus desplazamientos. |
| - Las universidades podrían ser clientes interesados en promover el uso de la plataforma entre sus estudiantes.                                                                 | - Creemos que al ofrecer una sección destacada para los “Viajes Más Populares de la Semana,” aumentaremos la participación de los estudiantes en la plataforma. | - **Universidades:** Promoción de una solución eficiente, segura, y ecológica para sus estudiantes, mejorando la calidad de vida en el campus. |
|                                                                                                                                                                                 | - Creemos que al proporcionar métricas claras sobre la eficiencia de los viajes, motivaremos a más estudiantes a utilizar nuestro servicio regularmente.  | |
|                                                                                                                                                                                 | - Creemos que al incorporar un sistema de recompensas para conductores y pasajeros frecuentes, aumentaremos la retención de usuarios.                    | |

| **7. What's the most important thing we need to learn first?**                                                                                                                  | **8. What's the least amount of work we need to do to learn the next most important thing?**                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| - Conocer las necesidades y comportamientos de los estudiantes en relación con sus hábitos de transporte y carpooling.                                                         | - Crear un prototipo funcional que permita a los estudiantes registrarse, verificar su identidad y buscar u ofrecer viajes compartidos.                    |
| - Evaluar la seguridad y confiabilidad del sistema de verificación de usuarios.                                                                                                 | - Realizar pruebas con un grupo pequeño de usuarios para validar la usabilidad y efectividad del sistema de verificación y mensajería.                    |
| - Investigar las preferencias de diseño y funcionalidad de los usuarios potenciales.                                                                                            | - Desarrollar un plan de marketing inicial para generar interés en una universidad piloto.                                                                 |
| - Identificar barreras de adopción y estrategias para superarlas.                                                                                                               | - Establecer soporte básico al usuario para resolver consultas y problemas de manera rápida y efectiva.                                                   |
| - Comprender las mejores prácticas de carpooling y estudiar a la competencia.                                                                                                  |                                                                                                                                                           |

---

## [**1.3. Segmentos objetivo.**](#13-segmentos-objetivo)

Por medio de nuestro enfoque de obtener una solución efectiva a las problemáticas de nuestros futuros usuarios, identificamos los siguientes segmentos para GoUni:

### **Segmento objetivo #1: Estudiantes Universitarios que necesiten movilizarse.**

**Aspectos demográficos:**

- **Sexo:** Masculino y femenino
- **Edades:** Adultos entre 18 - 30 años
- **Nivel socioeconómico:** Clases B, C, D (media-baja, baja)

**Aspectos geográficos:**

- **Nacionalidad:** Peruana
- **Zona geográfica en la que vive:** Urbana
- **Departamento:** Lima Metropolitana

**Aspectos psicográficos:**

- Abiertos a herramientas que les ayuden a simplificar y facilitar su viaje.
- Son hábiles dentro del uso de dispositivos inteligentes.

---

### **Segmento objetivo #2: Estudiantes Universitarios propietarios de un vehículo privado.**

**Aspectos demográficos:**

- **Sexo:** Masculino y femenino
- **Edades:** Adultos entre 18 - 30 años
- **Nivel socioeconómico:** Clases A, B, C (alta, media-alta y media)

**Aspectos geográficos:**

- **Nacionalidad:** Peruana
- **Zona geográfica en la que vive:** Urbana
- **Departamento:** Lima Metropolitana

**Aspectos psicográficos:**

- Son hábiles dentro del uso de dispositivos inteligentes.

---