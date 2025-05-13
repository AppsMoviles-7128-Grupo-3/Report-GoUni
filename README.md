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
    <strong>Startup: LinkU</strong><br>
    <strong>Producto: GoUni </strong>
</p>

### Team Members:

<div style="display: flex; justify-content: center; align-items: center;">

| **Member**                | **Code**   |
|---------------------------|------------|
| David Polanco, Alessandro | u202122232 |
| Chirinos Zúñiga, Rodrigo  | u202217804 |
| Cruz Ticona, Aaron        | u202213502 |
| Zevallos Linares, Alessandro       | u202216035 |

</div>

<p align="center">
    <strong>Abril 2025</strong>
</p>

---

# Registro de Versiones del Informe

### _TB1_

Para el desarrollo de la entrega **TB1**, se optó por dividir el trabajo de la siguiente forma:

| **Versión**   | **Fecha** | **Autor**                  | **Descripción**                                                                                  |
|---------------|----------|----------------------------|--------------------------------------------------------------------------------------------------|
| **#01 - TB1** | 19/04/25 | David Polanco, Alessandro  | Formateo del Capitulo 1, Capitulo 2, y Capitulo 3, desarrollo de la seccion 4.1.1 del capitulo 4 |
| **#01 - TB1** | 19/04/25 | Chirinos Zúñiga, Rodrigo   | Desarrollo de la seccion 4.2 del capitulo 4                                                      |
| **#01 - TB1** | 19/04/25 | Cruz Ticona, Aaron         | Desarrollo del Capitulo 4.2 Bounded Contexts                                                     |
| **#01 - TB1** | 19/04/25 | Zevallos Linares, Alessandro   | Desarrollo de la seccion 4.2 del capitulo 4                                                      |

---

### _TB2_

Para el desarrollo de la entrega **TB2**, se optó por dividir el trabajo de la siguiente forma:

| **Versión**   | **Fecha** | **Autor**                  | **Descripción**                              |
|---------------|-----------|----------------------------|----------------------------------------------|
| **#01 - TB1** | 4/05/25   | David Polanco, Alessandro  | Formateo del Capitulo 5                      |
| **#01 - TB1** | 4/05/25   | Chirinos Zúñiga, Rodrigo   | Desarrollo de la seccion 4.2 del capitulo 4  |
| **#01 - TB1** | 4/05/25   | Cruz Ticona, Aaron         | Desarrollo del Capitulo 4.2 Bounded Contexts |
| **#01 - TB1** | 4/05/25   | Zevallos Linares, Alessandro   | Desarrollo de la seccion 4.2 del capitulo 4  |

---

# Project Report Collaboration Insights

**URL del repositorio de GitHub de la organización:** [https://github.com/orgs/AppsMoviles-7128-Grupo-3/repositories](https://github.com/orgs/AppsMoviles-7128-Grupo-3/repositories)

![ProjectReportCollaborationInsigths.png](./assets/cap-1/collab-insight.png)

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
- [Student Outcome](#student-outcome)
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

- [**Capítulo IV: Solution Software Design.**](#capítulo-iv-solution-software-design)
    - [**4.1 Strategic-Level Domain-Driven-Design.**](#41-strategic-level-domain-driven-design)
        - [**4.1.1 Event Storming.**](#411-event-storming)
            - [**4.1.1.1 Candidate Context Discovery.**](#4111-candidate-context-discovery)
            - [**4.1.1.2 Domain Message Flows Modeling.**](#4112-domain-message-flows-modeling)
            - [**4.1.1.3 Bounded Context Canvases.**](#4113-bounded-context-canvases)
        - [**4.1.2 Context Mapping.**](#412-context-mapping)
        - [**4.1.3 Software Architecture.**](#413-software-architecture)
            - [**4.1.3.1 Software Architecture Context Level Diagrams.**](#4131-software-architecture-context-level-diagrams)
            - [**4.1.3.2 Software Architecture Container Level Diagrams.**](#4132-software-architecture-container-level-diagrams)
            - [**4.1.3.3 Software Architecture Deployment Level Diagrams.**](#4133-software-architecture-deployment-level-diagrams)
    - [**4.2 Tactical-Level Domain-Driven Design.**](#42-tactical-level-domain-driven-design)
        - [**4.2.1 Bounded Context: <Bounded Context Name>.**](#421-bounded-context-gestión-de-viajes-compartidos)
            - [**4.2.1.1 Domain Layer.**](#4211-domain-layer)
            - [**4.2.1.2 Interface Layer.**](#4212-interface-layer)
            - [**4.2.1.3 Application Layer.**](#4213-application-layer)
            - [**4.2.1.4 Infrastructure Layer.**](#4214-infrastructure-layer)
            - [**4.2.1.5 Bounded Context Software Architecture Component Level Diagrams.**](#4215-bounded-context-software-architecture-component-level-diagrams)
            - [**4.2.1.6 Bounded Context Software Architecture Code Level Diagrams.**](#4216-bounded-context-software-architecture-code-level-diagrams)
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
    - [**6.1 Software Configuration Management**](#61-software-configuration-management)
        - [**6.1.1 Software Development Environment Configuration**](#611-software-development-environment-configuration)
        - [**6.1.2 Source Code Management.**](#612-source-code-management)
        - [**6.1.3 Source Code Style Guide & Conventions**](#613-source-code-style-guide--conventions)
        - [**6.1.4 Software Deployment Configuration.**](#614-software-deployment-configuration)
    - [**6.2 Landing Page, Services & Applications Implementation**](#62-landing-page-services--applications-implementation)
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

| Criterio Específico                                                                                                                         | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Conclusiones                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **David Polanco, Alessandro Alonso**, <br><br>**TB1**: Se actualizaron y aplicaron conocimientos clave sobre metodologías ágiles, análisis de usuarios y diseño centrado en la experiencia. A través de herramientas como el Lean UX Canvas, entrevistas, mapeos de viaje del usuario y empatía, logramos identificar con mayor precisión los problemas y necesidades de los estudiantes universitarios respecto a su movilidad. Este proceso no sólo consolidó nuestras capacidades técnicas, sino que fortaleció nuestra competencia para enfrentar desafíos reales en el desarrollo de soluciones digitales, combinando teoría y práctica con enfoque en el usuario. <br><br>**Chirinos Zúñiga, Rodrigo Manuel**, <br><br>**TB1**: Se identificaron necesidades del usuario, especificando requisitos y diseñando soluciones mediante metodologías como Lean UX y Domain-Driven Design. <br><br>**Cruz Ticona, Aaron Alejandro**, <br><br>**TB1**: Participé activamente en el diseño e implementación de los bounded context, aplicando principios de Domain-Driven Design. Además, colaboré en la definición de los segmentos objetivos de usuarios.                                                                                                     | **General**: El desarrollo de TB1 permitió fortalecer la capacidad del equipo para analizar, documentar y comprender la problemática desde una perspectiva técnica y humana. Se adquirieron conocimientos clave en diseño UX, análisis de requerimientos y herramientas colaborativas como Miro, fundamentales para afrontar proyectos reales de software. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.**  | **David Polanco, Alessandro Alonso**, <br><br>**TB1**: El desarrollo de TB1 nos hizo conscientes de que el aprendizaje constante es fundamental en el campo de la ingeniería de software. Enfrentar una problemática real como la movilidad estudiantil nos impulsó a investigar nuevas metodologías, comprender mejor el entorno y mejorar nuestras habilidades de comunicación, análisis y documentación. Además, trabajar en equipo, estructurar entrevistas y utilizar plataformas colaborativas como GitHub nos permitió fortalecer nuestra capacidad de adaptación y crecimiento continuo, reconociendo que la evolución profesional está directamente ligada a la disposición de aprender en cada etapa del proceso. <br><br>**Chirinos Zúñiga, Rodrigo Manuel**, <br><br>**TB1**: Se reconoció la importancia del aprendizaje continuo y se aplicó en el desarrollo de soluciones de software, integrando nuevos conocimientos y metodologías en la entrega de este primer avance del proyecto. <br><br>**Cruz Ticona, Aaron Alejandro**, <br><br>**TB1**: La necesidad de estructurar correctamente los bounded contexts y representar fielmente los procesos del dominio me llevó a investigar y aplicar patrones avanzados de diseño de software.  | **General**: Durante TB1 se evidenció la importancia de estar en constante aprendizaje, no solo en tecnologías, sino también en metodologías de investigación y comunicación con usuarios reales. Esta experiencia nos hizo conscientes de que el software no se trata solo de código, sino de entender profundamente al usuario para ofrecer soluciones relevantes y sostenibles.  |

---

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
    <td><img src="assets/images/profiles/perfil_alessandro.jpg" alt="" width="700" height="140"></td>
    <td>Soy Alessandro Zevallos,estudiante de Ingeniería de Software con un fuerte interés en el desarrollo de productos digitales y la tecnología. En mi tiempo libre, me gusta jugar videojuegos. También tengo un interés especial en la música, lo que me ayuda a equilibrar mi vida académica y personal.</td>
  </tr>

   <tr>
    <td><img src="assets/images/profiles/alessandro-profile.jpeg" width="700" height="160"></td>
    <td>Mi nombre es Alessandro David y tengo 21 años. Yo estoy cursando
    la carrera de Ingenieria de Software en la UPC y ando en 7mo ciclo. Me gusto
    demasiado mi eleccion referente a la carrera dado que me interesan mucho todos los temas
    que tenga que ver con la tecnologia y las tendencias de este rubro. Me gusta leer libros de desarrollo
    personal y tambien entrenar y montar bicicleta. Me considero una persona empática, comprometida, y siempre atento 
    a resolver cualquier problema que me concierna. Como integrante del grupo de Apps Moviles me comprometo
    a cooperar con todo lo asignado en el trabajo y apoyar a mis compañeros con cualquier duda que quieran absolver.</td>
  </tr>

  <tr>
    <td><img src="https://github.com/user-attachments/assets/9895e794-a88f-4436-a332-8d5c8112f9cb" width="700" height="150"></td>
    <td>Tengo 20 años, soy un estudiante de la carrera de Ingeniería de Software, considero que soy una persona responsable y de escucha activa. Estoy comprometido con mis compañeros en realizar un buen trabajo y así aprender todos en el proceso. También tengo conocimientos en programación en C++, HTML, CSS y JavaScript.</td>
  </tr>

  <tr>
    <td><img src="assets/images/profiles/aaron_profile.jpg" width="700" height="140"></td>
    <td>Actualmente, me encuentro cursando la carrera de Ingeniería de Software, una disciplina que despierta mi 
        constante curiosidad y deseo de aprendizaje. Mi motivación por adquirir nuevos conocimientos es una de mis 
        principales fortalezas, y espero seguir nutriéndola a lo largo del curso. Me considero una persona adaptable, 
        especialmente cuando se trata de trabajar en equipo, por lo que confío en mi capacidad para contribuir de 
        manera efectiva en proyectos colaborativos. Además, valoro un entorno laboral positivo y colaborativo, y me 
        esfuerzo por fomentar este ambiente dentro de mi grupo, ya que considero que el trabajo en equipo es esencial para alcanzar el éxito.</td>
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

Link del Lean UX Canvas: https://miro.com/app/board/uXjVI25Wgp8=/?share_link_id=201297055499

![Lean UX Canvas](assets/cap-1/lean-ux-canvas.jpg)

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

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

**BlaBlaCar**

Es una plataforma global de ride-sharing que conecta conductores y pasajeros para compartir viajes de media y larga distancia. Los usuarios pueden dividir los costos del viaje, lo que hace que el transporte sea más económico y sostenible. BlaBlaCar fomenta la colaboración y la optimización de recursos al reducir la cantidad de vehículos en la carretera.

**Urbvan**

Es una plataforma de transporte privado en van que opera en rutas predefinidas, generalmente en áreas metropolitanas. Se enfoca en ofrecer una alternativa más eficiente y cómoda al transporte público, brindando un servicio seguro y puntual a través de vehículos compartidos, pero con un enfoque de calidad y confort para los usuarios.

**Yango**

Es una aplicación internacional de ride-hailing que ofrece transporte bajo demanda con tarifas competitivas y un enfoque en la facilidad de uso. Opera en diversas ciudades del mundo, brindando a los usuarios una experiencia de transporte rápida, segura y accesible, con la opción de reservar y pagar viajes directamente a través de la aplicación.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se esta llevando a cabo para connotar las diferencias con las empresas competidoras y tomar sus amenazas
    como nuevas oportunidades en nuestro producto para poder innovar.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        GoUni
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/cap-1/gounilogo.jfif" alt="StartUp" width="100px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    BlaBlaCar
    <div style="text-align: center; margin-top: 20px;">
                <img src="assets/cap-1/blablacar.png" alt="blablacar" width="100px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      Urbvan
      <div style="text-align: center; margin-top: 40px;">
                <img src="assets/cap-1/urbvan.png" alt="urbvan" width="200px">
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Yango
      <div style="text-align: center; margin-top: 20px;">
                <img src="assets/cap-1/yango.png" alt="yango" width="610px">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Plataforma de ride-sharing entre estudiantes universitarios en Perú, centrada en la 
    colaboración, sostenibilidad y reducción de costos de transporte.</td>
    <td colspan="1" valign="top">Plataforma global de ride-sharing para viajes interurbanos, 
    donde conductores y pasajeros comparten viajes y gastos.</td>
    <td colspan="1" valign="top">Plataforma de transporte privado en van con rutas predefinidas, 
    enfocada en eficiencia y comodidad.</td>
    <td colspan="1" valign="top">Aplicación internacional de ride-hailing que se enfoca en 
    ofrecer tarifas competitivas y una experiencia sencilla de uso.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Focalización en estudiantes universitarios, fomentando una comunidad cerrada y 
    segura con intereses comunes; enfoque en sostenibilidad.</td>
    <td colspan="1" valign="top">Operación a nivel global con una amplia base de usuarios; 
    experiencia consolidada en viajes largos.</td>
    <td colspan="1" valign="top">Ofrece transporte cómodo y seguro en rutas fijas; 
    ideal para desplazamientos largos dentro de la ciudad.</td>
    <td colspan="1" valign="top">Tarifas competitivas y experiencia de usuario sencilla, 
    rápida expansión en diversas ciudades.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Estudiantes universitarios en Perú que buscan compartir viajes seguros, 
    económicos y sostenibles con sus compañeros.</td>
    <td colspan="1" valign="top">Viajeros interurbanos que buscan reducir costos y socializar en viajes largos.</td>
    <td colspan="1" valign="top">Profesionales y estudiantes que requieren transporte cómodo y 
    eficiente en rutas fijas dentro de la ciudad.</td>
    <td colspan="1" valign="top">Usuarios urbanos que buscan transporte asequible y 
    rápido en varias ciudades de América Latina.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Enfoque en el marketing digital y redes sociales en entornos estudiantiles; 
    colaboraciones con universidades para promociones.</td>
    <td colspan="1" valign="top">Campañas de marketing enfocadas en la experiencia compartida, 
    la comunidad y la reducción de costos de viaje.	</td>
    <td colspan="1" valign="top">Enfoque en la eficiencia, seguridad y confort en el transporte urbano; 
    promociones y descuentos para usurios frecuentes.</td>
    <td colspan="1" valign="top">Enfoque en tarifas competitivas, promociones frecuentes y facilidad de uso; 
    expansión rápida y adquisición de nuevos usuarios.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Plataforma de ride-sharing exclusiva para estudiantes 
    universitarios, con opciones para compartir viajes cortos y largos dentro de la ciudad.</td>
    <td colspan="1" valign="top">Ride-sharing interurbano, conectando conductores 
    y pasajeros en viajes de larga distancia.</td>
    <td colspan="1" valign="top">Servicios de transporte en vans con rutas fijas; 
    asientos reservados y viajes cómodos.</td>
    <td colspan="1" valign="top">Ride-hailing en tiempo real con diferentes tipos de vehículos; 
precios competitivos y una plataforma fácil de usar.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">Precios asequibles con base en compartir costos de 
    viaje; enfoque en la economía colaborativa.</td>
    <td colspan="1" valign="top">Compartir costos de viaje entre conductores y pasajeros; 
    enfoque en la reducción de costos de viaje.</td>
    <td colspan="1" valign="top">Tarifas fijas según las rutas y horarios predefinidos; enfoque en la comodidad.</td>
    <td colspan="1" valign="top">Tarifas accesibles con promociones frecuentes; 
    modelo basado en precios competitivos y flexibles.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Aplicación móvil enfocada en estudiantes universitarios, 
    con soporte web para registros y gestión de viajes.</td>
    <td colspan="1" valign="top">Aplicación móvil y web con acceso a reservas 
    de viajes compartidos en toda la región.</td>
    <td colspan="1" valign="top">Aplicación móvil y reservas web para la gestión de rutas y viajes en vans.</td>
    <td colspan="1" valign="top">Aplicación móvil fácil de usar disponible en múltiples ciudades de América Latina.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Enfoque en la comunidad estudiantil; servicio exclusivo y seguro; sostenibilidad.</td>
    <td colspan="1" valign="top">Amplia red global de usuarios; enfoque en viajes largos; reputación consolidada.</td>
    <td colspan="1" valign="top">Comodidad y eficiencia en rutas predefinidas; seguridad y confort en transporte urbano.</td>
    <td colspan="1" valign="top">Tarifas competitivas y fácil de usar; expansión rápida en diversas ciudades.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Mercado limitado a estudiantes universitarios; competencia con transporte público económico.</td>
    <td colspan="1" valign="top">Dependencia de viajes largos; limitado a rutas interurbanas.</td>
    <td colspan="1" valign="top">Restricción de rutas fijas y horarios; costos más altos comparados con el transporte público tradicional.</td>
    <td colspan="1" valign="top">Competencia feroz en mercados urbanos; problemas con la regulación local.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Expansión a otras universidades y ciudades; colaboraciones con instituciones educativas.</td>
    <td colspan="1" valign="top">Expansión a mercados nuevos y emergentes; desarrollo de más servicios complementarios.</td>
    <td colspan="1" valign="top">Expansión a más rutas y ciudades; enfoque en ofrecer servicios corporativos.</td>
    <td colspan="1" valign="top">Crecimiento acelerado en más ciudades; enfoque en la mejora continua del servicio y tarifas.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia de aplicaciones de ride-hailing y transporte público; regulación gubernamental.</td>
    <td colspan="1" valign="top">Aparición de competidores más locales en áreas específicas; cambios en la regulación.</td>
    <td colspan="1" valign="top">Competencia con aplicaciones de ride-hailing y transporte público tradicional.</td>
    <td colspan="1" valign="top">Regulación gubernamental y competencia feroz en el mercado urbano de transporte.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

- **Diferenciación de la plataforma:**
  GoUni se diferencia por ser una plataforma exclusiva para estudiantes universitarios. El enfoque en la comunidad académica y la seguridad brinda un entorno más cerrado y confiable en comparación con otras plataformas abiertas al público general. Además, su misión de promover la sostenibilidad y la economía colaborativa refuerza su atractivo para jóvenes conscientes del medio ambiente.
-----
- **Comunidad activa:**
  Con GoUni queremos fomentar una comunidad de estudiantes comprometidos, creando un entorno en el que los usuarios se sientan seguros viajando con personas de su misma universidad. La cercanía entre los miembros de la comunidad facilita la interacción y genera confianza entre los usuarios.
-----
- **Marketing dirigido:**
  El marketing en GoUni se enfocará en captar a estudiantes universitarios mediante colaboraciones con universidades, eventos estudiantiles y promociones a través de redes sociales específicas para jóvenes. Esta comunicación apela a la sostenibilidad, la seguridad y la economía colaborativa, factores importantes para la comunidad estudiantil.
-----
- **Monetización creativa:**
  La monetización de GoUni se basará en la compartición de costos entre estudiantes, pero puede explorar modelos adicionales como suscripciones premium que ofrezcan beneficios exclusivos, como rutas garantizadas o mayor seguridad. También podría implementar alianzas con marcas enfocadas en estudiantes, generando ingresos adicionales a través de publicidad contextual o colaboraciones.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se han definido todas las preguntas que se plantearán en el momento de realizar las entrevistas a los diferentes segmentos objetivos.

**Preguntas Generales**

1. ¿Cuál es tu nombre?
1. ¿Qué edad tienes?
1. ¿Dónde vives actualmente?
1. ¿A qué te dedicas?
-----
**Preguntas Segmento 1: Estudiantes universitarios**

1. ¿Con qué frecuencia utilizas transporte para llegar a la universidad?
1. ¿Cuáles son las mayores dificultades que enfrentas al desplazarte a la universidad?
1. ¿Cuánto tiempo sueles tardar en llegar a la universidad desde tu casa?
1. ¿Estarías dispuesto/a a compartir tu trayecto con otros estudiantes? ¿Por qué?
1. ¿Qué factores te harían sentir más cómodo/a utilizando un servicio de ride-sharing para estudiantes?
1. ¿Cómo crees que un servicio de transporte compartido podría mejorar tu experiencia diaria?
-----
**Preguntas Segmento 2: Estudiantes universitarios propietarios de vehículos privados**

1. ¿Con qué frecuencia conduces hacia tu universidad o trabajo?
1. ¿Te gustaría compartir tu vehículo con otros estudiantes en tus trayectos?
1. ¿Cuáles son tus mayores preocupaciones al compartir tu vehículo con otras personas?
1. ¿Qué aspectos te motivarían a ofrecer tu vehículo en un servicio de ride-sharing?
1. ¿Qué tipo de incentivos te harían más propenso/a a unirte a una plataforma de ride-sharing para estudiantes?
1. ¿Cómo manejas los costos de mantenimiento y gasolina? ¿Crees que compartir tu vehículo podría ayudar a reducir esos costos?
1. ¿Cuáles son tus expectativas en cuanto a seguridad y comodidad al ofrecer tu vehículo para transportar a otros?

### 2.2.2 Registro de entrevistas

**Segmento 1: Estudiantes Universitarios**

**Entrevista 1:**

- **Nombres:** Diego
- **Apellidos:** Chirinos
- **Edad:** 22
- **Lugar de residencia:** Puente Piedra


**Evidencia de la entrevista:**
<img src="assets/cap-1/entrevista_Rodrigo.png">

**Enlace de la entrevista:** <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202217804_upc_edu_pe/EafDNXFPq2BIhYC_e8DyVvsB2SDioSgRJ8liZa5-P_5M-Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1zOkep"> Clic aquí </a>

**Resumen de la entrevista:**
Diego usa el transporte público de 4 a 5 días a la semana. El trayecto le toma máximo 1:30:00 de ida, nos comenta que depende del tráfico y también cuando tiene algunos contratiempos. Le parece una buena idea hacer uso del servicio de ride-sharing porque hace el trayecto más ameno y sería un solo viaje sin paradas o cambio de bus. Le gustaría que el sistema sea seguro, bien organizado y que validen las identidades de los usuarios, también en caso de alguna emergencia poder contactar a alguien.


-----

**Entrevista 2:**

- **Nombres:** Maria Gracia
- **Apellidos:** Rojas Montenegro
- **Edad:** 19
- **Lugar de residencia:** Lima, Perú

**Evidencia de la entrevista:**  
<img src="assets/cap-1/EvidenciaEntrevistaAlessandro.png">

**Enlace de la entrevista:**<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202122232_upc_edu_pe/EdkBJ6BiIApNmPjECvCbqpYBZLdRyR5IUQ6hbW72k0wSNw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&e=yEaifN"> Clic aquí </a>

**Resumen de la entrevista:**
Maria Gracia es una estudiante universitaria de la UPC que no tiene muchas dificultades al momento de transportarse desde su casa hacia la universidad. Ella comenta que le gustaría mucho una alternativa de transporte como el carpooling, ya que podría conocer nuevas personas de la misma universidad, ahorrar dinero en transporte, y utilizar un método más rápido en casos de urgencia.

-----
**Segmento 2: Estudiantes universitarios propietarios de vehículos privados**

**Entrevista 1:**

- **Nombres:** Andre
- **Apellidos:** Zagaceta
- **Edad:** 21
- **Lugar de residencia:** San MIguel


**Evidencia de la entrevista:**
<img src="assets/cap-1/entrevista_alessandro.PNG">

**Enlace de la entrevista:**<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216035_upc_edu_pe/EaTEgOo5uhpPqhKfrRocsVUBLLwVeB6TOUh-V59LvfrsmQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=aregO1"> Clic aquí </a>



**Resumen de la entrevista:**
Andre Zagaceta es un estudiante universitario que conduce de manera regular a la universidad, el esta dispuesto a compartir su viaje con otros alumnos ya que cree que esto puede ayudar con la gasolina y reducir los costos de mantenimiento, y buscaria que sean personas resptuosas y que este controlado por la apliacion.



-----
**Entrevista 2:**

- **Nombres:** Francisco
- **Apellidos:** Soto
- **Edad:** 22
- **Lugar de residencia:** Lima, Perú


**Evidencia de la entrevista:**
<img src="assets/cap-1/entrevista_aaron.png">

**Enlace de la entrevista:** <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213502_upc_edu_pe/EbhcYmyn-y1JlD7N3pR5cwoBN9sSJpjLNJq1wA_k8zbvuQ?e=o36q7H&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D"> Clic aquí </a>

**Resumen de la entrevista:**
El entrevistado indica que posee un vehículo de uso familiar que utiliza principalmente para movilizarse a la u.
Aunque no tiene experiencia previa compartiendo su vehículo, está dispuesto a hacerlo siempre que exista un nivel
adecuado de confianza con la persona interesada. Actualmente no conoce ninguna plataforma que le permita hacer lo que
nuestro producto busca abarcar.



## 2.2.3 Análisis de entrevistas.

<TABLE BORDER>
	<TR>
		<TD COLSPAN = 2 align=center>

*Características*</TD>

<TD align=center>

*Segmento1*
<br>
*Estudiantes universitarios*
</TD>

<TD align=center>

*Segmento2*
<br>
*Estudiantes universitarios propietarios de vehiculos privados*
</TD>

   </TR>
	<TR>
		<TD ROWSPAN = 4>

*Objetivas*
</TD>
<TD>Tráfico</TD>
<TD>Costos</TD>
<TD>Seguridad</TD>
</TR>
<TR>
<TD>Problemas con el tráfico diario</TD>
<TD>Potencial de ahorro en transporte </TD>
<TD>Preocupación por la seguridad en transporte público</TD>
</TR>
<TR>
<TD>Menos relevante, pero buscan reducir tiempo y costo</TD>
<TD>Reducir costos de transporte es clave </TD>
<TD>Seguridad personal y verificación de identidad son cruciales</TD>
</TR>
<TR>
<TD >Mejoraría tiempos de viaje y eficiencia</TD>
<TD>N/A</TD>
<TD>Reducir tiempos también es valorado</TD>
</TR>

   <TR>
		<TD ROWSPAN = 4>

*Subjetivas*
</TD>
<TD>Conexiones sociales</TD>
<TD>Comodidad</TD>
<TD>Reglas claras</TD>
<TR>
<TD>Oportunidad de hacer networking con otros estudiantes</TD>
<TD>Preferirían más comodidad que en transporte público</TD>
<TD>N/A</TD>
</TR>
<TR>
<TD>Hacer nuevas amistades mientras reducen costos</TD>
<TD>Preocupación por la comodidad de los pasajeros</TD>
<TD>Necesidad de reglas claras y sistemas de calificación</TD>
</TR>
<TR>

</TR>
</TABLE>

## 2.3. Needfinding

### 2.3.1. User Personas
***Estudiantes universitarios:***

Link del User Persona: https://miro.com/app/board/uXjVI2QHm_0=/?share_link_id=179785171278

<img src="assets/cap-2/user-persona-1.png" width="800px">

***Estudiantes Universitarios propietarios de vehículos privados:***

Link del User Persona: https://miro.com/app/board/uXjVI2QHm_0=/?share_link_id=179785171278

<img src="assets/cap-2/user-persona-2.png" width="800px">

-----
### 2.3.2. User Task Matrix

A continuación se pueden apreciar los User Task Matrix de los segmentos objetivos.

***Segmento Objetivo: Estudiantes Universitarios***

|**Task**|**Frequency**|**Importance**|
| :- | :- | :- |
|Buscar compañeros disponibles en la app|High|High|
|Coordinar el punto de encuentro|Medium|Medium|
|Realizar pagos a través de la app|Medium|High|
|Verificar la seguridad del conductor/compañeros|High|High|
|Calificar al conductor y el viaje|Low|Medium|
|Planificar viajes recurrentes|Medium|High|
|Ser partícipe de promociones o descuentos|Low|Medium|

-----
***Segmento Objetivo: Estudiantes universitarios propietarios de vehículos privados***

|**Task**|**Frequency**|**Importance**|
| :- | :- | :- |
|Publicar la disponibilidad del vehículo|High|High|
|Aceptar solicitudes de pasajero|High|High|
|Coordinar horarios y puntos de recogida|Medium|Medium|
|Recibir pago de los pasajeros|High|High|
|Revisar la seguridad y confiabilidad del pasajero|Medium|High|
|Calificar a los pasajeros|Low|Medium|
|Optimizar rutas para ahorrar tiempo y combustible|Medium|High|

### 2.3.3. User Journey Mapping

A continuación se pueden apreciar los User Journey Mapping de los segmentos objetivos.

***Estudiantes Universitarios***

<img src="assets/cap-2/journey-map-1.png" width="900px">


***Estudiantes universitarios propietarios de vehículos privados***

<img src="assets/cap-2/journey-map-2.png" width="900px">

-----
### 2.3.4. Empathy Mapping

A continuación se pueden apreciar los Empathy Mapping de los segmentos objetivos.

***Estudiantes Universitarios***

<img src="assets/cap-2/empathy-mapping-1.png" width="900px">

***Estudiantes universitarios propietarios de vehículos privados***

<img src="assets/cap-2/empathy-mapping-2.png" width="900px">

-----
### 2.3.5. As-is Scenario Mapping

A continuación se pueden apreciar los As-Is Scenario de los segmentos objetivos.

***Estudiantes Universitarios***

<img src="assets/cap-2/as-is-scenario-1.png" width="900px">

***Estudiantes universitarios propietarios de vehículos privados***

<img src="assets/cap-2/as-is-scenario-2.png" width="900px">

**Enlace de Miro:** 

-----
## 2.4. Ubiquitous Language

- **Usuario**: Estudiante universitario registrado en la plataforma, ya sea como conductor o pasajero.
- **Conductor**: Estudiante universitario que posee un vehículo y está dispuesto a compartir su viaje hacia la universidad con otros estudiantes a cambio de una compensación económica.
- **Pasajero**: Estudiante universitario que utiliza la plataforma para buscar conductores con rutas compatibles y compartir un viaje hacia su universidad a cambio de una tarifa.
- **Viaje Compartido**: Desplazamiento en un vehículo particular en el que participan un conductor y uno o más pasajeros que comparten una ruta similar hacia la universidad.
- **Ruta**: Trayectoria específica que sigue un conductor desde su punto de origen hasta la universidad, la cual es compartida con los pasajeros a través de la plataforma.
- **Carpooling**: El acto de compartir un viaje entre varias personas para optimizar el uso de un vehículo particular, reducir costos y disminuir la congestión vehicular.
- **Reserva de Viaje**: Proceso mediante el cual un pasajero asegura un asiento en el vehículo de un conductor para un viaje específico, siguiendo una ruta y horario predeterminado.
- **Tarifa**: Costo que un pasajero paga al conductor por compartir el viaje. Esta tarifa cubre una parte de los gastos del conductor, como el combustible.
- **Perfil del Usuario**: Información detallada que cada usuario (conductor o pasajero) proporciona a la plataforma, incluyendo su nombre, universidad, calificaciones previas, y preferencias de viaje.
- **Calificación**: Sistema de puntuación que los pasajeros y conductores otorgan mutuamente después de cada viaje, basado en aspectos como puntualidad, seguridad y comportamiento durante el trayecto.
- **Notificación**: Comunicación enviada a los usuarios a través de la plataforma, informándoles sobre el estado de su reserva, cambios en la ruta, o recordatorios de viaje.
- **Punto de Encuentro**: Lugar acordado donde el conductor y los pasajeros se reúnen para iniciar el viaje compartido.
- **Destino**: La universidad u otro lugar predeterminado donde el viaje compartido finaliza.
-----

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección se resume la información recopilada. Se presentan dos tablas que detallan la situación a mejorar de cada segmento objetivo, analizando los pasos que se realizarán y cómo se sienten los usuarios en cada etapa.

### *Segmento: Estudiantes Universitarios que necesiten movilizarse*
[![to-be-primer-segmento.png](https://i.postimg.cc/50YFpZh0/to-be-primer-segmento.png)](https://postimg.cc/r0TmwYFX)

---

### *Segmento: Estudiantes Universitarios propietarios de vehículo privado*

[![to-be-segundo-segmento.png](https://i.postimg.cc/2jWZWNd9/to-be-segundo-segmento.png)](https://postimg.cc/mhbkxq57)


## 3.2. User Stories
<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 21%" />
<col style="width: 39%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>
<tr class="even">
<td>E1-US01</td>
<td>Compartir viajes con compañeros de universidad</td>
<td>
<p><strong>Como</strong> estudiante universitario sin vehículo,</p>
<p><strong>Quiero</strong> compartir viajes con compañeros que se dirijan a la universidad</p>
<p><strong>Para</strong> reducir costos y llegar de manera más eficiente</p>
</td>
<td>
<p>Escenario 1: Búsqueda de viajes disponibles</p>
<p><strong>Dado</strong> que el usuario necesita transporte hacia la universidad,</p>
<p><strong>Cuando</strong> accede a la plataforma</p>
<p><strong>Entonces</strong> podrá buscar y ver una lista de conductores disponibles que se dirijan a su universidad en un horario compatible</p>
<p>Escenario 2: Reserva de un viaje</p>
<p><strong>Dado</strong> que el usuario ha encontrado un viaje disponible,</p>
<p><strong>Cuando</strong> selecciona al conductor y realiza la reserva,</p>
<p><strong>Entonces</strong> podrá confirmar su lugar en el vehículo y recibir detalles sobre el viaje</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E1-US02</td>
<td>Generar ingresos compartiendo mi vehículo</td>
<td>
<p><strong>Como</strong> estudiante universitario con vehículo propio,</p>
<p><strong>Quiero</strong> ofrecer lugares en mi auto a otros estudiantes que van hacia la unviersidad</p>
<p><strong>Para</strong> reducir mis gastos de transporte y generar ingresos adicionales</p>
</td>
<td>
<p>Escenario 1: Publicación de disponibilidad de asientos</p>
<p><strong>Dado</strong> que el usuario tiene un vehículo con lugares disponibles,</p>
<p><strong>Cuando</strong> accede a la plataforma</p>
<p><strong>Entonces</strong> podrá publicar su ruta y disponibilidad de asientos para que otros estudiantes puedan reservar</p>
<p>Escenario 2: Gestión de reservas</p>
<p><strong>Dado</strong> que el usuario ha publicado su disponibilidad,</p>
<p><strong>Cuando</strong> los pasajeros reservan lugares en su vehículo,</p>
<p><strong>Entonces</strong> podrá ver y gestionar todas las reservas en su aplicación, confirmando los pasajeros y horarios</p>
</td>
<td>1</td>
</tr>

<tr class="even">
<td>E1-US03</td>
<td>Evaluar la seguridad del viaje</td>
<td>
<p><strong>Como</strong> estudiante,</p>
<p><strong>Quiero</strong> evaluar a los conductores y recibir calificaciones de otros usuarios</p>
<p><strong>Para</strong> asegurarme de que el viaje sea seguro y confiable</p>
</td>
<td>
<p>Escenario 1: Ver calificaciones de conductores</p>
<p><strong>Dado</strong> que el usuario está reservando un viaje,</p>
<p><strong>Cuando</strong> selecciona un conductor,</p>
<p><strong>Entonces</strong> podrá ver la calificación y los comentarios de otros pasajeros sobre la experiencia previa a ese conductor</p>
<p>Escenario 2: Dejar una calificación</p>
<p><strong>Dado</strong> que el usuario ha completado un viaje,</p>
<p><strong>Cuando</strong> finalice el trayecto,</p>
<p><strong>Entonces</strong> podrá dejar una calificación y comentarios sobre la experiencia con el conductor</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E2-US01</td>
<td>Recibir notificaciones en tiempo real</td>
<td>
<p><strong>Como</strong> estudiante pasajero,</p>
<p><strong>Quiero</strong> recibir notificaciones en tiempo real sobre mi viaje </p>
<p><strong>Para</strong> estar al tanto de cualquier cambio en la ruta o el horario</p>
</td>
<td>
<p>Escenario 1: Actualización de la hora de llegada</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> haya un cambio en la ruta o el horario,</p>
<p><strong>Entonces</strong> el usuario recibirá una notificación en tiempo real indicando el neuvo tiempo estimado de llegada</p>
<p>Escenario 2: Notificación de recogida</p>
<p><strong>Dado</strong> que el conductor está llegando a recoger a un pasajero,</p>
<p><strong>Cuando</strong> esté cerca al punto de encuentro,</p>
<p><strong>Entonces</strong> el usuario recibirá una notificación informándole que el conductor está próximo</p>
</td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US02</td>
<td>Verificación de identidades</td>
<td>
<p><strong>Como</strong> usuario de la plataforma,</p>
<p><strong>Quiero</strong> que tanto los conductores como los pasajeros verifiquen sus identidades </p>
<p><strong>Para</strong> asegurarme de que mi viaje será con persona confiables</p>
</td>
<td>
<p>Escenario 1: Verificación de conductores</p>
<p><strong>Dado</strong> que el usuario va realizar un viaje,</p>
<p><strong>Cuando</strong> seleccione un conductor,</p>
<p><strong>Entonces</strong> podrá ver si el conductor ha verificado su identidad y sus documentos</p>
<p>Escenario 2: Verificación de pasajeros</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> los pasajeros confirmen su reserva,</p>
<p><strong>Entonces</strong> el conductor podrá ver si los pasajeros han verificado su identidad a través de la plataforma</p>
</td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US03</td>
<td>Realizar pagos de manera segura</td>
<td>
<p><strong>Como</strong> pasajero,</p>
<p><strong>Quiero</strong> realizar el pago del viaje a través de la paltaforma de forma segura </p>
<p><strong>Para</strong> no tener que manejar efectivo durante el trayecto</p>
</td>
<td>
<p>Escenario 1: Pago en línea</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> confirme su reserva,</p>
<p><strong>Entonces</strong> podrá realizar el apgo del viaje a través de la plataforma utilizando métodos de pago seguros como tarjeta de crédito, débito o bileteras digitales</p>
<p>Escenario 2: Confirmación de pago</p>
<p><strong>Dado</strong> que el usuario ha realizado el pago,</p>
<p><strong>Cuando</strong> se complete la transacción,</p>
<p><strong>Entonces</strong> recibirá una confirmación del pago en su correo electrónico o dentro de la aplicación</p>
</td>
<td>2</td>
</tr>

 <tr class="even">
        <td>E3-US01</td>
        <td>Registro de usuario</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder crear mi usuario</p>
            <p><strong>Para</strong> acceder al servicio de carpooling</p>
        </td>
        <td>
            <p>Escenario 1: Registro del usuario</p>
            <p><strong>Dado</strong> que el usuario quiere unirse a la plataforma,</p>
            <p><strong>Cuando</strong> complete el formulario de registro,</p>
            <p><strong>Entonces</strong> recibirá un correo electrónico de confirmación después del registro.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US02</td>
        <td>Búsqueda de Viaje Disponibles</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> buscar viajes disponibles</p>
            <p><strong>Para</strong> poder planificar mis desplazamientos</p>
        </td>
        <td>
            <p>Escenario 1: Filtrado de viajes</p>
            <p><strong>Dado</strong> que el usuario necesita un viaje,</p>
            <p><strong>Cuando</strong> ingrese sus criterios de búsqueda,</p>
            <p><strong>Entonces</strong> podrá ver una lista de viajes disponibles con información detallada.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US03</td>
        <td>Reserva de Viaje</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder reservar un asiento en el viaje disponible</p>
            <p><strong>Para</strong> garantizar mi lugar.</p>
        </td>
        <td>
            <p>Escenario 1: Confirmación de reserva</p>
            <p><strong>Dado</strong> que el usuario ha seleccionado un viaje,</p>
            <p><strong>Cuando</strong> acceda a la página de detalles del viaje,</p>
            <p><strong>Entonces</strong> podrá encontrar la opción para reservar un asiento y confirmar la reserva.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US04</td>
        <td>Comunicación con el Conductor</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder comunicarme con el conductor de mi viaje</p>
            <p><strong>Para</strong> coordinar detalles y obtener información adicional.</p>
        </td>
        <td>
            <p>Escenario 1: Mensajería dentro de la plataforma</p>
            <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
            <p><strong>Cuando</strong> quiera comunicarse con el conductor,</p>
            <p><strong>Entonces</strong> podrá hacerlo a través de la plataforma UniRider.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US05</td>
        <td>Cancelación de Reserva</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder cancelar una reserva de viaje</p>
            <p><strong>Para</strong> los casos de que surjan imprevistos</p>
        </td>
        <td>
            <p>Escenario 1: Cancelación de reserva</p>
            <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
            <p><strong>Cuando</strong> acceda a la página de detalles de su reserva,</p>
            <p><strong>Entonces</strong> podrá encontrar la opción para cancelar su reserva y confirmar la cancelación.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US06</td>
        <td>Calificación y Comentario del Conductor</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder calificar y dejar comentarios sobre la experiencia de viaje con el conductor</p>
            <p><strong>Para</strong> ayudar a otros usuarios en su elección</p>
        </td>
        <td>
            <p>Escenario 1: Calificación del conductor</p>
            <p><strong>Dado</strong> que el usuario ha completado un viaje,</p>
            <p><strong>Cuando</strong> quiera dejar una opinión,</p>
            <p><strong>Entonces</strong> podrá calificar al conductor con una puntuación y un comentario opcional.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US07</td>
        <td>Publicación de disponibilidad de asientos</td>
        <td>
            <p><strong>Como</strong> Usuario con vehículo,</p>
            <p><strong>Quiero</strong> publicar la disponibilidad de asientos</p>
            <p><strong>Para</strong> que otros estudiantes puedan reservar</p>
        </td>
        <td>
            <p>Escenario 1: Publicación de disponibilidad</p>
            <p><strong>Dado</strong> que el usuario tiene un vehículo con lugares disponibles,</p>
            <p><strong>Cuando</strong> acceda a la plataforma,</p>
            <p><strong>Entonces</strong> podrá publicar su ruta y disponibilidad de asientos para que otros estudiantes puedan reservar.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US08</td>
        <td>Gestión de reservas</td>
        <td>
            <p><strong>Como</strong> Usuario con vehículo,</p>
            <p><strong>Quiero</strong> gestionar las reservas de los pasajeros</p>
            <p><strong>Para</strong> confirmar los pasajeros y horarios</p>
        </td>
        <td>
            <p>Escenario 1: Gestión de reservas</p>
            <p><strong>Dado</strong> que el usuario ha publicado su disponibilidad,</p>
            <p><strong>Cuando</strong> los pasajeros reservan lugares en su vehículo,</p>
            <p><strong>Entonces</strong> podrá ver y gestionar todas las reservas en su aplicación, confirmando los pasajeros y horarios.</p>
        </td>
        <td>3</td>
    </tr>
<tr class="even">
        <td>E4-US01</td>
        <td>Visualizar planes de servicio</td>
        <td>
            <p><strong>Como</strong> usuario que visita la plataforma del restaurante,</p>
            <p><strong>Quiero</strong> visualizar los planes de servicio disponibles</p>
            <p><strong>Para</strong> evaluar las opciones y elegir el que mejor se adapte a mis necesidades</p>
        </td>
        <td>
            <p>Escenario 1: Visualización inicial de los planes de servicio</p>
            <p><strong>Dado</strong> que el usuario ha accedido a la plataforma,</p>
            <p><strong>Cuando</strong> el usuario navega a la sección de planes de servicio,</p>
            <p><strong>Entonces</strong> se muestran todos los planes disponibles en una lista, incluyendo el nombre del plan, precio y beneficios principales.</p>
        </td>
        <td>
            <p>Escenario 2: Ver detalles de un plan específico</p>
            <p><strong>Dado</strong> que el usuario está visualizando los planes de servicio,</p>
            <p><strong>Cuando</strong> el usuario selecciona un plan específico de la lista,</p>
            <p><strong>Entonces</strong> se muestra con los detalles completos del plan, incluyendo una descripción más detallada de los beneficios y cualquier condición asociada.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E4-US02</td>
        <td>Seleccionar un plan de servicio</td>
        <td>
            <p><strong>Como</strong>usuario registrado en la plataforma,</p>
            <p><strong>Quiero</strong> seleccionar un plan de servicio</p>
            <p><strong>Para</strong> adquirir los beneficios específicos que ofrece el plan</p>
        </td>
        <td>
            <p>Escenario 1: Selección de un plan desde la lista</p>
            <p><strong>Dado</strong> que el usuario ha visualizado los planes de servicio disponibles,</p>
            <p><strong>Cuando</strong> el usuario selecciona un plan de la lista,</p>
            <p><strong>Entonces</strong> se redirige al usuario a una página de confirmación, mostrando un resumen del plan seleccionado.</p>
        </td>
        <td>
            <p>Escenario 2: Confirmación de selección del plan</p>
            <p><strong>Dado</strong> que el usuario ha seleccionado un plan,</p>
            <p><strong>Cuando</strong> el usuario revisa el resumen del plan en la página de confirmación,,</p>
            <p><strong>Entonces</strong> tiene la opción de confirmar la selección o regresar a la lista de planes para elegir otro.</p>
        </td>
        <td>3</td>
    </tr>

<tr class="even">
        <td>E4-US03</td>
        <td>Realizar el pago del plan seleccionado</td>
        <td>
            <p><strong>Como</strong> usuario que ha seleccionado un plan,</p>
            <p><strong>Quiero</strong> realizar el pago del plan seleccionado</p>
            <p><strong>Para</strong> activar los beneficios del plan y comenzar a utilizarlos</p>
        </td>
        <td>
            <p>Escenario 1: Ingreso de detalles de pago</p>
            <p><strong>Dado</strong>  que el usuario ha confirmado la selección de un plan y ha sido redirigido a la página de pago,
            <p><strong>Cuando</strong> el usuario introduce los detalles de pago (tarjeta de crédito, PayPal, etc.),</p>
            <p><strong>Entonces</strong> el sistema verifica la validez de los detalles ingresados y muestra un resumen de la transacción.</p>
        </td>
        <td>
            <p>Escenario 2: Confirmación del pago</p>
            <p><strong>Dado</strong> que el usuario ha ingresado detalles de pago válidos,</p>
            <p><strong>Cuando</strong> el usuario confirma la transacción,</p>
            <p><strong>Entonces</strong> el sistema procesa el pago y muestra una confirmación en pantalla, indicando que el plan ha sido activado con éxito.</p>
        </td>
        <td>
            <p>Escenario 3: Notificación de pago exitoso</p>
            <p><strong>Dado</strong> que el pago ha sido procesado con éxito,</p>
            <p><strong>Cuando</strong> la transacción se completa,</p>
            <p><strong>Entonces</strong> el usuario recibe una notificación de confirmación por correo electrónico, detallando el plan adquirido y los beneficios activados.</p>
        </td>
        <td>5</td>
    </tr>

<tr class="odd">
        <td>E4-US04</td>
        <td>Cancelar suscripción o plan</td>
        <td>
            <p><strong>Como</strong>usuario que ha adquirido un plan,</p>
            <p><strong>Quiero</strong> cancelar mi suscripción o plan</p>
            <p><strong>Para</strong> dejar de recibir los beneficios y evitar cargos futuros</p>
        </td>
        <td>
            <p>Escenario 1: Acceso a la opción de cancelación</p>
            <p><strong>Dado</strong> que el usuario tiene un plan activo en su cuenta,</p>
            <p><strong>Cuando</strong> el usuario accede a la sección de “Mis planes” o “Mi cuenta”,</p>
            <p><strong>Entonces</strong> se le muestra la opción de cancelar su suscripción o plan actual.</p>
        </td>
        <td>
            <p>Escenario 2: Coonfirmación de la cancelación</p>
            <p><strong>Dado</strong> que el usuario ha solicitado cancelar su plan,</p>
            <p><strong>Cuando</strong> el usuario hace clic en “Cancelar plan” y se le solicita confirmar la acción,</p>
            <p><strong>Entonces</strong> el sistema muestra un mensaje de confirmación que explica las consecuencias de la cancelación.</p>
        </td>
        <td>3</td>
    </tr>
<tr class="even">
<td>E5-US01</td>
<td>Barra de navegación en la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> una barra de navegación en la landing page,</p>
<p><strong>Para</strong> tener acceso directo a la aplicación.</p>
</td>
<td>
<p>Escenario 1: El cliente o conducto se encuentra en el navbar de navegación</p>
<p><strong>Dado</strong> que el usuario se encuentra en la landing page,</p>
<p><strong>Cuando</strong> se encuentre en la sección del navbar,</p>
<p><strong>Entonces</strong> visualiza enlaces de las secciones, botón de idiomas y el botón para redirigir a la aplicación.</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E5-US02</td>
<td>Dirigirse a la aplicación mediante la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> dirigirme a la aplicación mediante el botón “Open App”,</p>
<p><strong>Para</strong> poder usarla.</p>
</td>
<td>
<p>Escenario 1: Enlace directo a la aplicación a través de un botón</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> este se dirige al navbar,</p>
<p><strong>Cuando</strong> presione el botón “Open app”,</p>
<p><strong>Entonces</strong> es dirigido a la aplicación donde se podrá loguear.</p>
</td>
<td>2</td>
</tr>

<tr class="even">
<td>E5-US03</td>
<td>Sección hero del landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> observar la sección hero de la landing,</p>
<p><strong>Para</strong> poder tener información de lo que es y ofrece la aplicación.</p>
</td>
<td>
<p>Escenario 1: El cliente o conductor se encuentra en la sección de hero</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Cuando</strong> se encuentra en la sección hero,</p>
<p><strong>Entonces</strong> observa una presentación de la aplicación.</p>
<p>Escenario 2: El cliente o conductor accede a la aplicación por el botón de Sign Up</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> presiona el botón “Sign up”,</p>
<p><strong>Entonces</strong> es redirigido al formulario de registro de cuentas.</p>
</td>
<td>3</td>
</tr>

<tr class="odd">
<td>E5-US04</td>
<td>Versión en español de la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> tener al alcance una versión en español del landing page,</p>
<p><strong>Para</strong> tener accesibilidad en cuanto a opciones de idioma.</p>
</td>
<td>
<p>Escenario 1: El cliente entra a la landing page</p>
<p><strong>Dado</strong> que el usuario se encuentra en el landing page,</p>
<p><strong>Cuando</strong> sea su primera vez,</p>
<p><strong>Entonces</strong> el idioma predeterminado de la landing page será inglés.</p>
<p>Escenario 2: El cliente quiere cambiar de idioma</p>
<p><strong>Dado</strong> que el usuario se encuentra en la landing page,</p>
<p><strong>Y</strong> desea cambiar de idioma a español,</p>
<p><strong>Cuando</strong> presiona el botón para cambiar de inglés a español,</p>
<p><strong>Entonces</strong> la landing page se muestra en el idioma de preferencia seleccionado.</p>
</td>
<td>4</td>
</tr>

<tr class="even">
<td>E5-US05</td>
<td>Sección about the product y about the team</td>
<td>
<p><strong>Como</strong> cliente o staff,</p>
<p><strong>Quiero</strong> ver la sección del about the product y about the team,</p>
<p><strong>Para</strong> conocer las características de la aplicación y del grupo de desarrolladores.</p>
</td>
<td>
<p>Escenario 1: Enlace directo a la sección about the product y the team</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> este se dirige al navbar,</p>
<p><strong>Entonces</strong> puede acceder directamente a la sección correspondiente.</p>
</td>
<td>5</td>
</tr>

<tr class="odd">
  <td>E1-US01</td>
  <td>Agendar notificaciones de recordatorio de viajes</td>
  <td>
    <p><strong>Como</strong> pasajero,</p>
    <p><strong>Quiero</strong> recibir notificaciones de recordatorio antes del inicio de mi viaje</p>
    <p><strong>Para</strong> asegurarme de estar listo a tiempo</p>
  </td>
  <td>
    <p>Escenario 1: Recordatorio antes del viaje</p>
    <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
    <p><strong>Cuando</strong> queden 30 minutos para que comience el viaje,</p>
    <p><strong>Entonces</strong> recibirá una notificación recordándole el inicio próximo del viaje</p>
    <p>Escenario 2: Ubicación del conductor</p>
    <p><strong>Dado</strong> que el usuario ha recibido la notificación de recordatorio,</p>
    <p><strong>Cuando</strong> abra la aplicación,</p>
    <p><strong>Entonces</strong> podrá ver la ubicación y el tiempo estimado de llegada del conductor</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US02</td>
  <td>Filtrar viajes por tipos de vehículos</td>
  <td>
    <p><strong>Como</strong> pasajero,</p>
    <p><strong>Quiero</strong> poder filtrar los viajes según el tipo de vehículo</p>
    <p><strong>Para</strong> seleccionar el que más se ajuste a mis necesidades</p>
  </td>
  <td>
    <p>Escenario 1: Aplicar filtros</p>
    <p><strong>Dado</strong> que el usuario está buscando un viaje,</p>
    <p><strong>Cuando</strong> acceda a los filtros,</p>
    <p><strong>Entonces</strong> podrá seleccionar el tipo de vehículo, como sedan, SUV, o camioneta</p>
    <p>Escenario 2: Búsqueda de vehículos filtrados</p>
    <p><strong>Dado</strong> que el usuario ha aplicado el filtro,</p>
    <p><strong>Cuando</strong> seleccione "Buscar",</p>
    <p><strong>Entonces</strong> verá solo los viajes disponibles con el tipo de vehículo seleccionado</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US03</td>
  <td>Establecer destinos secundarios</td>
  <td>
    <p><strong>Como</strong> conductor,</p>
    <p><strong>Quiero</strong> poder establecer destinos secundarios durante mi ruta</p>
    <p><strong>Para</strong> recoger a más estudiantes en puntos intermedios</p>
  </td>
  <td>
    <p>Escenario 1: Añadir destinos secundarios</p>
    <p><strong>Dado</strong> que el usuario ha publicado un viaje,</p>
    <p><strong>Cuando</strong> esté configurando su ruta,</p>
    <p><strong>Entonces</strong> podrá agregar puntos de parada adicionales en el trayecto</p>
    <p>Escenario 2: Verificación de paradas</p>
    <p><strong>Dado</strong> que el conductor ha agregado un destino secundario,</p>
    <p><strong>Cuando</strong> un pasajero busque viajes,</p>
    <p><strong>Entonces</strong> podrá ver si hay paradas adicionales en la ruta del conductor</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US04</td>
  <td>Opciones de seguridad adicionales para conductores</td>
  <td>
    <p><strong>Como</strong> conductor,</p>
    <p><strong>Quiero</strong> poder acceder a opciones adicionales de seguridad, como compartir mi ubicación en tiempo real</p>
    <p><strong>Para</strong> garantizar un viaje seguro</p>
  </td>
  <td>
    <p>Escenario 1: Activar seguimiento de ubicación</p>
    <p><strong>Dado</strong> que el conductor ha iniciado un viaje,</p>
    <p><strong>Cuando</strong> comience el recorrido,</p>
    <p><strong>Entonces</strong> podrá activar la opción de compartir su ubicación en tiempo real con un contacto de confianza</p>
    <p>Escenario 2: Desactivar el seguimiento</p>
    <p><strong>Dado</strong> que el conductor ha compartido su ubicación,</p>
    <p><strong>Cuando</strong> termine el viaje,</p>
    <p><strong>Entonces</strong> podrá desactivar el seguimiento de la ubicación</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US05</td>
  <td>Identificación de usuarios frecuentes</td>
  <td>
    <p><strong>Como</strong> pasajero frecuente,</p>
    <p><strong>Quiero</strong> poder marcar ciertos conductores como favoritos</p>
    <p><strong>Para</strong> facilitar la reserva de futuros viajes con ellos</p>
  </td>
  <td>
    <p>Escenario 1: Marcar un conductor como favorito</p>
    <p><strong>Dado</strong> que el pasajero ha completado varios viajes con un conductor,</p>
    <p><strong>Cuando</strong> acceda a su perfil,</p>
    <p><strong>Entonces</strong> podrá marcarlo como "Favorito" para futuros viajes</p>
    <p>Escenario 2: Recibir notificaciones de conductores favoritos</p>
    <p><strong>Dado</strong> que el pasajero ha marcado a un conductor como favorito,</p>
    <p><strong>Cuando</strong> busque viajes,</p>
    <p><strong>Entonces</strong> recibirá notificaciones cuando ese conductor tenga disponibilidad</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US06</td>
  <td>Programar viajes recurrentes</td>
  <td>
    <p><strong>Como</strong> usuario,</p>
    <p><strong>Quiero</strong> poder programar viajes recurrentes</p>
    <p><strong>Para</strong> no tener que hacer reservas diarias cada vez que necesite transporte</p>
  </td>
  <td>
    <p>Escenario 1: Programar viaje recurrente</p>
    <p><strong>Dado</strong> que el usuario necesita transporte diario,</p>
    <p><strong>Cuando</strong> acceda a la opción de "Viajes recurrentes",</p>
    <p><strong>Entonces</strong> podrá establecer un horario y ruta fijos para repetir el viaje automáticamente</p>
    <p>Escenario 2: Confirmación de viajes recurrentes</p>
    <p><strong>Dado</strong> que el usuario ha programado un viaje recurrente,</p>
    <p><strong>Cuando</strong> se aproxime la fecha del viaje,</p>
    <p><strong>Entonces</strong> recibirá una confirmación automática del viaje y detalles del conductor</p>
  </td>
  <td>1</td>
</tr>

</tbody>
</table>
<hr>

## 3.3. Impact Mapping.

<img src="assets/cap-3/impact-mapping.png" alt="Impact Mapping" style="width: 100%; height: auto;">

## 3.4. Product Backlog.
<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 28%" />
<col style="width: 14%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th>#Orden</th>
<th>User Story ID</th>
<th>Titulo</th>
<th>Descripcion</th>
<th>Prioridad</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>US01</td>
<td>Compartir viajes con compañeros de universidad</td>
<td><p><strong>Como</strong> estudiante universitario sin vehículo,</p>
<p><strong>quiero</strong> compartir viajes con compañeros que se dirijan a la universidad</p>
<p><strong>para</strong> reducir costos y llegar de manera más eficiente</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>2</td>
<td>US02</td>
<td>Generar ingresos compartiendo mi vehículo</td>
<td><p><strong>Como</strong> estudiante universitario con vehículo propio,</p>
<p><strong>quiero</strong> ofrecer lugares en mi auto a otros estudiantes que van hacia la universidad</p>
<p><strong>para</strong> reducir mis gastos de transporte y generar ingresos adicionales</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>3</td>
<td>US03</td>
<td>Evaluar la seguridad del viaje</td>
<td><p><strong>Como</strong> estudiante,</p>
<p><strong>quiero</strong> evaluar a los conductores y recibir calificaciones de otros usuarios</p>
<p><strong>para</strong> asegurarme de que el viaje sea seguro y confiable</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>4</td>
<td>US04</td>
<td>Recibir notificaciones en tiempo real</td>
<td><p><strong>Como</strong> estudiante pasajero,</p>
<p><strong>quiero</strong> recibir notificaciones en tiempo real sobre mi viaje</p>
<p><strong>para</strong> estar al tanto de cualquier cambio en la ruta o el horario</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>5</td>
<td>US05</td>
<td>Verificación de identidades</td>
<td><p><strong>Como</strong> usuario de la plataforma,</p>
<p><strong>quiero</strong> que tanto los conductores como los pasajeros verifiquen sus identidades</p>
<p><strong>para</strong> asegurarme de que mi viaje será con personas confiables</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>6</td>
<td>US06</td>
<td>Realizar pagos de manera segura</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> realizar el pago del viaje a través de la plataforma de forma segura</p>
<p><strong>para</strong> no tener que manejar efectivo durante el trayecto</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>7</td>
<td>US07</td>
<td>Registro de usuario</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder crear mi usuario</p>
<p><strong>para</strong> acceder al servicio de carpooling</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>8</td>
<td>US08</td>
<td>Búsqueda de viajes disponibles</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> buscar viajes disponibles</p>
<p><strong>para</strong> poder planificar mis desplazamientos</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>9</td>
<td>US09</td>
<td>Reserva de viaje</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder reservar un asiento en el viaje disponible</p>
<p><strong>para</strong> garantizar mi lugar</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>10</td>
<td>US10</td>
<td>Comunicación con el conductor</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder comunicarme con el conductor de mi viaje</p>
<p><strong>para</strong> coordinar detalles y obtener información adicional</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>11</td>
<td>US11</td>
<td>Cancelación de reserva</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder cancelar una reserva de viaje</p>
<p><strong>para</strong> los casos de que surjan imprevistos</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="even">
<td>12</td>
<td>US12</td>
<td>Calificación y comentario del conductor</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder calificar y dejar comentarios sobre la experiencia de viaje con el conductor</p>
<p><strong>para</strong> ayudar a otros usuarios en su elección</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>13</td>
<td>US13</td>
<td>Publicación de disponibilidad de asientos</td>
<td><p><strong>Como</strong> Usuario con vehículo,</p>
<p><strong>quiero</strong> publicar la disponibilidad de asientos</p>
<p><strong>para</strong> que otros estudiantes puedan reservar</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>14</td>
<td>US14</td>
<td>Gestión de reservas</td>
<td><p><strong>Como</strong> Usuario con vehículo,</p>
<p><strong>quiero</strong> gestionar las reservas de los pasajeros</p>
<p><strong>para</strong> confirmar los pasajeros y horarios</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>15</td>
<td>US15</td>
<td>Visualizar planes de servicio</td>
<td><p><strong>Como</strong> usuario que visita la plataforma del restaurante,</p>
<p><strong>quiero</strong> visualizar los planes de servicio disponibles</p>
<p><strong>para</strong> evaluar las opciones y elegir el que mejor se adapte a mis necesidades</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>16</td>
<td>US16</td>
<td>Seleccionar un plan de servicio</td>
<td><p><strong>Como</strong> usuario registrado en la plataforma,</p>
<p><strong>quiero</strong> seleccionar un plan de servicio</p>
<p><strong>para</strong> adquirir los beneficios específicos que ofrece el plan</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>17</td>
<td>US17</td>
<td>Realizar el pago del plan seleccionado</td>
<td><p><strong>Como</strong> usuario que ha seleccionado un plan,</p>
<p><strong>quiero</strong> realizar el pago del plan seleccionado</p>
<p><strong>para</strong> activar los beneficios del plan y comenzar a utilizarlos</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>18</td>
<td>US18</td>
<td>Cancelar suscripción o plan</td>
<td><p><strong>Como</strong> usuario que ha adquirido un plan,</p>
<p><strong>quiero</strong> cancelar mi suscripción o plan</p>
<p><strong>para</strong> dejar de recibir los beneficios y evitar cargos futuros</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>19</td>
<td>US19</td>
<td>Barra de navegación en la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> una barra de navegación en la landing page,</p>
<p><strong>para</strong> tener acceso directo a la aplicación</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="even">
<td>20</td>
<td>US20</td>
<td>Dirigirse a la aplicación mediante la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> dirigirme a la aplicación mediante el botón “Open App”,</p>
<p><strong>para</strong> poder usarla</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>21</td>
<td>US21</td>
<td>Sección hero del landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> observar la sección hero de la landing,</p>
<p><strong>para</strong> poder tener información de lo que es y ofrece la aplicación</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>22</td>
<td>US22</td>
<td>Versión en español de la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> tener al alcance una versión en español del landing page,</p>
<p><strong>para</strong> tener accesibilidad en cuanto a opciones de idioma</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>23</td>
<td>US23</td>
<td>Sección about the product y about the team</td>
<td><p><strong>Como</strong> cliente o staff,</p>
<p><strong>quiero</strong> ver la sección del about the product y about the team,</p>
<p><strong>para</strong> conocer las características de la aplicación y del grupo de desarrolladores</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>24</td>
<td>US24</td>
<td>Agendar notificaciones de recordatorio de viajes</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> recibir notificaciones de recordatorio antes del inicio de mi viaje,</p>
<p><strong>para</strong> asegurarme de estar listo a tiempo</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>25</td>
<td>US25</td>
<td>Filtrar viajes por tipos de vehículos</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> poder filtrar los viajes según el tipo de vehículo,</p>
<p><strong>para</strong> seleccionar el que más se ajuste a mis necesidades</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>26</td>
<td>US26</td>
<td>Establecer destinos secundarios</td>
<td><p><strong>Como</strong> conductor,</p>
<p><strong>quiero</strong> poder establecer destinos secundarios durante mi ruta,</p>
<p><strong>para</strong> recoger a más estudiantes en puntos intermedios</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>27</td>
<td>US27</td>
<td>Opciones de seguridad adicionales para conductores</td>
<td><p><strong>Como</strong> conductor,</p>
<p><strong>quiero</strong> poder acceder a opciones adicionales de seguridad, como compartir mi ubicación en tiempo real,</p>
<p><strong>para</strong> garantizar un viaje seguro</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>28</td>
<td>US28</td>
<td>Identificación de usuarios frecuentes</td>
<td><p><strong>Como</strong> pasajero frecuente,</p>
<p><strong>quiero</strong> poder marcar ciertos conductores como favoritos,</p>
<p><strong>para</strong> facilitar la reserva de futuros viajes con ellos</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>29</td>
<td>US29</td>
<td>Programar viajes recurrentes</td>
<td><p><strong>Como</strong> usuario,</p>
<p><strong>quiero</strong> poder programar viajes recurrentes,</p>
<p><strong>para</strong> no tener que hacer reservas diarias cada vez que necesite transporte</p></td>
<td>Alta</td>
<td>8</td>
</tr>
</tbody>
</table>

---

# Capítulo IV: Solution Software Design

## 4.1.  Strategic-Level Domain-Driven-Design
### 4.1.1 Event Storming
#### 4.1.1.1 Candidate Context Discovery
<img src="assets/cap-4/domain-events.png" alt="domain-events" width="450px">
<br>  - Gestión de Viajes Compartidos
<br>   Se encarga de la creación, reserva y seguimiento de viajes compartidos.
<br>
<br>  - Verificación de Usuario
<br>   Administra la validación de identidad de conductores y pasajeros para garantizar seguridad.
<br>
<br>  - Sistema de Pagos
<br>    Procesa los pagos de los viajes mediante tarjetas y billeteras digitales.
<br>
<br>  - Sistema de Calificaciones y Feedback
<br>    Permite que los usuarios califiquen su experiencia después de cada viaje.
<br>
<br>  - Notificaciones y Alertas
<br>    Gestiona el envío de notificaciones en tiempo real para cambios de ruta, estado de reserva, etc.

#### 4.1.1.2 Domain Message Flows Modeling
<img src="assets/cap-4/domain-message-flow-modeling.png" alt="domain-events" width="600px">

#### 4.1.1.3 Bounded Context Canvases
<img src="assets/cap-4/bounded-context-canvas-1.png" alt="domain-events" width="600px">
<img src="assets/cap-4/bounded-context-canvas-2.png" alt="domain-events" width="600px">
<img src="assets/cap-4/bounded-context-canvas-3.png" alt="domain-events" width="600px">
<img src="assets/cap-4/bounded-context-canvas-4.png" alt="domain-events" width="600px">
<img src="assets/cap-4/bounded-context-canvas-5.png" alt="domain-events" width="600px">

### 4.1.2 Context Mapping
<img src="assets/cap-4/context-mapping.png" alt="domain-events" width="600px">

### 4.1.3 Software Architecture
- La arquitectura de software de la solución GoUni se basa en el modelo C4 (Context, Container, Component y Deployment), el cual permite una representación progresiva y estructurada del sistema desde su visión más general hasta sus detalles técnicos.
  Esta arquitectura está orientada al dominio (DDD), sigue principios de separación de responsabilidades, bajo acoplamiento y alta cohesión, y está pensada para ser implementada como una app Android nativa en Kotlin, conectada a una backend ligera desplegada en la nube.

#### 4.1.3.1 Software Architecture Context Level Diagrams
<img src="assets/cap-4/context-diagram.png" alt="domain-events" width="600px">


#### 4.1.3.2 Software Architecture Container Level Diagrams
<img src="assets/cap-4/container-diagram.png" alt="domain-events" width="600px">

#### 4.1.3.3 Software Architecture Deployment Level Diagrams

<img src="assets/cap-4/deployment-diagram.png" alt="domain-events" width="600px">

## 4.2.  Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Gestión de Viajes Compartidos
### 4.2.1.1 Domain Layer
#### Entities

**Viaje**

Atributos:
- id: UUID
- origen: string
- destino: string
- horario: datetime
- capacidad: int
- asientos_disponibles: int
- conductor_id: UUID
- estado: enum {CREADO, RESERVADO, COMPLETADO, CANCELADO}

Métodos:
- publicar_viaje()
- reservar_asiento(usuario_id)
- actualizar_estado(nuevo_estado)

---

**Reserva**

Atributos:
- id: UUID
- viaje_id: UUID
- pasajero_id: UUID
- asiento_reservado: string
- estado: enum {PENDIENTE_PAGO, CONFIRMADA, CANCELADA}
- fecha_reserva: datetime

Métodos:
- confirmar_reserva()
- cancelar_reserva()

---

**Vehiculo**

Atributos:
- id: UUID
- tipo: string
- matricula: string
- capacidad: int
- conductor_id: UUID

Métodos:
- registrar_vehiculo()
- actualizar_detalles()

---

**Conductor**

Atributos heredados:
- id: UUID
- nombre: string
- email: string
- rol: Rol
- verificado: boolean

Métodos:
- publicar_viaje()
- gestionar_reservas()

---

**Pasajero**

Atributos heredados:
- id: UUID
- nombre: string
- email: stirng
- rol: Rol
- verificado: boolean

Métodos:
- buscar_viaje()
- reservar_viaje()

---

#### Value Objects

- Ubicacion: Encapsula origen y destino.
- Horario: Agrupa fecha y hora del viaje.

---

#### Aggregates

- Viaje es el agregado raíz.
- Incluye a Reserva como entidad interna del agregado.
- Las operaciones sobre Reserva se hacen a través de Viaje.

---

#### Factories

ViajeFactory  
Método:
- crear(datos: dict)  Viaje

---

#### Domain Services

**ServicioDeReserva**

Lógica para reservar asiento considerando:
- Disponibilidad de asientos
- Estado del viaje
- Validación del conductor y pasajero
- Integración con sistema de pagos

---

#### Repositories (Interfaces)

IViajeRepository
- obtener_por_id(id: UUID)  Viaje
- guardar(viaje: Viaje)
- buscar(origen: string, destino: string, fecha: date)  List[Viaje]

IReservaRepository
- obtener_por_id(id: UUID)  Reserva
- guardar(reserva: Reserva)

---

#### 4.2.1.2. Interface Layer

Command Handlers

- CrearViajeHandler: Usa la factory para crear un viaje.
- ReservarViajeHandler: Orquesta validaciones, disponibilidad y reserva.
- FinalizarViajeHandler: Marca viaje como COMPLETADO y emite evento.

---

Event Handlers

- EventoPagoConfirmadoHandler: Escucha evento del sistema de pagos y actualiza la reserva a CONFIRMADA.
- EventoViajeFinalizadoHandler: Emite evento hacia el sistema de Calificaciones y Feedback.

---

#### 4.2.1.3. Application Layer

Controllers (API REST via API Gateway)

- POST /viajes: Crear un nuevo viaje.
- GET /viajes: Buscar viajes por origen, destino y fecha.
- POST /viajes/{id}/reservar: Reservar asiento.
- POST /viajes/{id}/finalizar: Finalizar viaje.

---

#### 4.2.1.4. Infrastructure Layer

Servicios Externos

- Auth Service: Autenticación del conductor/pasajero antes de realizar acciones.
- Payment Service: Validación de pago de la reserva.
- Notification Service: Envío de alertas al reservar o cambiar el estado del viaje.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
<img src="assets/cap-4/bounded-context-component-diagram-1.png">

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
<img src="assets/cap-4/bounded-context-class-diagram-1.png">

##### 4.2.1.6.2. Bounded Context Database Design Diagram
<img src="assets/cap-4/bounded-context-database-diagram-1.png">

### 4.2.2. Bounded Context: Verificación de Usuarios

### 4.2.2.1 Domain Layer

#### Entities

**Usuario**

Atributos:
- id: UUID
- nombre: string
- email: string
- contraseña: string
- rol: enum {CONDUCTOR, PASAJERO}
- verificado: boolean

Métodos:
- registrarse()
- iniciarSesion()
- verificarIdentidad()

---

**Conductor** (hereda de Usuario)
**Pasajero** (hereda de Usuario)

---

#### Value Objects

- DocumentoDeIdentidad:
    - tipo: enum {DNI, CARNET_EXTRANJERIA, LICENCIA}
    - numero: string

---

#### Aggregates

- Usuario es el agregado raíz.

---

#### Factories

UsuarioFactory  
Método:
- crear(datos: dict) → Usuario

---

#### Domain Services

**ServicioDeVerificacion**

Método:
- verificar_documento(documento: DocumentoDeIdentidad) → bool

Lógica:
- Valida los datos ingresados por el usuario, posiblemente consulta con fuentes externas.

---

#### Repositories (Interfaces)

IUsuarioRepository
- obtener_por_id(id: UUID) → Usuario
- guardar(usuario: Usuario)
- buscar_por_email(email: string) → Usuario

---

### 4.2.2.2 Interface Layer

#### Command Handlers

- RegistrarUsuarioHandler: orquesta el registro mediante la factory.
- VerificarUsuarioHandler: aplica la verificación de identidad.
- IniciarSesionHandler: maneja login y autenticación.

---

#### Event Handlers

- EventoDocumentoVerificadoHandler: actualiza estado verificado = true si el documento es válido.
- EventoUsuarioVerificadoHandler: emite evento a "Gestión de Viajes" si se completó verificación.

---

### 4.2.2.3 Application Layer

#### Controllers (API REST via API Gateway)

- POST /usuarios: Crear usuario nuevo
- POST /usuarios/login: Inicia sesión
- POST /usuarios/{id}/verificar: Envía documentos y verifica
- GET /usuarios/{id}: Ver detalle de usuario

---

### 4.2.2.4 Infrastructure Layer

#### Servicios Externos

- Servicio de Verificación de Documentos.
- Auth Service.

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
<img src="assets/cap-4/bounded-context-component-diagram-2.png">

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
<img src="assets/cap-4/bounded-context-class-diagram-2.png">

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
<img src="assets/cap-4/bounded-context-database-diagram-2.png">

##### 4.2.2.6.2. Bounded Context Database Design Diagram

### 4.2.3. Bounded Context: Sistema de Pagos

### 4.2.3.1 Domain Layer

#### Entities

**Pago**

Atributos:
- id: UUID
- monto: float
- metodoDePago: enum {TARJETA, BILLETERA}
- estado: enum {PENDIENTE, CONFIRMADO, FALLIDO}
- reservaId: UUID

Métodos:
- realizarPago()
- confirmarPago()

---

#### Value Objects

- MetodoDePago:
    - tipo: enum {TARJETA, BILLETERA}
    - detalles: string (tokenizado o ID del proveedor)

---

#### Aggregates

- Pago es el agregado raíz.

---

#### Factories

PagoFactory  
Método:
- crear(monto, metodo, reservaId) → Pago

---

#### Domain Services

**ProcesadorDePagos**

Lógica para procesar el pago con:
- Interacción con proveedores externos como Stripe, PayPal o Yape/Plin.

Método:
- procesar(pago: Pago) → estado

---

#### Repositories (Interfaces)

IPagoRepository
- guardar(pago)
- obtener_por_id(id)
- obtener_por_reserva(reservaId)

---

### 4.2.3.2 Interface Layer

#### Command Handlers

- RealizarPagoHandler: Inicia un nuevo pago.
- ConfirmarPagoHandler: Recibe confirmación del proveedor.
- CancelarPagoHandler: Marca el pago como fallido o cancelado.

---

#### Event Handlers

- EventoPagoConfirmadoHandler: Notifica al sistema de reservas.
- EventoPagoFallidoHandler: Informa al usuario y actualiza estado.

---

### 4.2.3.3 Application Layer

#### Controllers (API REST via API Gateway)

- POST /pagos: Realiza un nuevo pago
- GET /pagos/{id}: Ver detalles del pago
- POST /pagos/{id}/confirmar: Confirma el pago
- POST /pagos/{id}/cancelar: Cancela el pago

---

### 4.2.3.4 Infrastructure Layer

#### Servicios Externos

- Proveedor de Pagos (Stripe/PayPal/Yape): Procesamiento real del pago.
- Servicio de Tokenización: Para guardar datos de tarjetas de forma segura.

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
<img src="assets/cap-4/bounded-context-component-diagram-3.png">

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
<img src="assets/cap-4/bounded-context-class-diagram-3.png">

##### 4.2.3.6.2. Bounded Context Database Design Diagram
<img src="assets/cap-4/bounded-context-database-diagram-3.png">

### 4.2.4. Bounded Context: Gestión de Evaluaciones

### 4.2.4.1 Domain Layer
#### Entities

**Evaluacion**

Atributos:
- id: UUID
- calificacion: int (1-5)
- comentario: string
- evaluadorId: UUID
- viajeId: UUID
- fecha: Date

Métodos:
- calificar()
- dejarComentario()

---

#### Value Objects

**CalificacionValor**

- valor: int (1-5)

Validaciones:
- valor debe estar entre 1 y 5

---

#### Aggregates

- Evaluacion es la raíz del agregado.

---

#### Factories

EvaluacionFactory  
Método:
- crear(calificacion, comentario, evaluadorId, viajeId) → Evaluacion

---

#### Domain Services

**ValidadorEvaluacionService**

Lógica para validar evaluaciones considerando:
- verificarUsuarioViaje(evaluadorId, viajeId): boolean

Valida que el evaluador haya participado en el viaje que quiere calificar.

---

#### Repositories (Interfaces)

IEvaluacionRepository
- guardar(evaluacion)
- obtenerPorViaje(viajeId)
- obtenerPorUsuario(usuarioId)

---

### 4.2.4.2 Interface Layer

Command Handlers

- CrearEvaluacionHandler: Valida y crea una evaluación.

---

Event Handlers

- EvaluacionRegistradaHandler: Dispara actualizaciones de reputación del conductor o pasajero.

---

### 4.2.4.3 Application Layer

Controllers (API REST via API Gateway)

- POST /evaluaciones: Crea una nueva evaluación
- GET /evaluaciones/usuario/{id}: Obtiene evaluaciones por usuario
- GET /evaluaciones/viaje/{id}: Obtiene evaluaciones por viaje

---

### 4.2.4.4 Infrastructure Layer

Servicios Externos

- Sistema de Gestión de Usuarios: Validar que el usuario haya participado en el viaje.

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams
<img src="assets/cap-4/bounded-context-component-diagram-4.png">

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
<img src="assets/cap-4/bounded-context-class-diagram-4.png">

##### 4.2.4.6.2. Bounded Context Database Design Diagram
<img src="assets/cap-4/bounded-context-database-diagram-4.png">

### 4.2.5. Bounded Context: Gestión de Notificaciones

### 4.2.5.1 Domain Layer
#### Entities

**Notificacion**

Atributos:
- id: UUID
- mensaje: String
- tipo: TipoNotificacion (enum)
- receptorId: UUID
- fechaEnvio: Date
- estado: String (pendiente, enviada, fallida)

Métodos:
- enviarNotificacion()

---

#### Value Objects

**TipoNotificacion**

Enum:
- VERIFICACION_APROBADA
- VERIFICACION_RECHAZADA
- PAGO_CONFIRMADO
- VIAJE_PUBLICADO
- RESERVA_CONFIRMADA
- VIAJE_CANCELADO

---

#### Aggregates

- Notificacion es la raíz del agregado.

---

#### Factories

NotificacionFactory  
Método:
- crearDesdeEvento(evento): Notificacion

---

#### Domain Services

**EnvioNotificacionService**

Lógica para el envío de notificaciones:
- enviar(notificacion): ResultadoEnvio

---

### 4.2.5.2 Application Layer

Event Handlers

- onVerificacionAprobada(event)
- onVerificacionRechazada(event)
- onPagoConfirmado(event)
- onViajePublicado(event)
- onReservaConfirmada(event)
- onViajeCancelado(event)

Estos métodos son listeners suscritos a los canales de eventos de los demás bounded contexts.

---

### 4.2.5.3 Infrastructure Layer

Servicios Externos

- Servicio de Email o Push Notifications (ej: Firebase, Twilio, etc.)
- Bus de eventos (RabbitMQ, Kafka, etc.)

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams
<img src="assets/cap-4/bounded-context-component-diagram-5.png">

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams
<img src="assets/cap-4/bounded-context-class-diagram-5.png">

##### 4.2.5.6.2. Bounded Context Database Design Diagram
<img src="assets/cap-4/bounded-context-database-diagram-5.png">

# Capítulo V: Solution UI/UX Design
## 5.1. Product Design
### 5.1.1. Style Guidelines
En esta sección se describen las pautas generales de estilo que guían la apariencia visual del producto, incluyendo el uso de colores, tipografía y espaciado.

#### 5.1.1.1 General Style Guidelines

Las directrices generales aseguran una estética que refuerza la marca y proporciona claridad visual para los usuarios.

#### Historia de la marca
La marca busca transmitir modernidad y profesionalismo, reflejando estos valores en cada elemento visual del diseño.

#### Misión
Proporcionar a los usuarios una experiencia fluida y atractiva, con interfaces claras y consistentes.

#### Visión
Ser reconocidos como una marca que combina funcionalidad y estilo en el diseño de productos digitales.

#### Brand Name
El nombre de la marca es un elemento clave de nuestra identidad, representando los valores fundamentales de la empresa.

#### Colores
La paleta de colores está diseñada para proporcionar un equilibrio visual. Utilizamos una combinación de tonos brillantes y neutros para transmitir profesionalismo y modernidad.

![Paleta de Colores](assets/cap-5/colors.png)

#### Tipografía
Usamos la tipografía **Roboto** en diferentes pesos para establecer jerarquía visual y garantizar una legibilidad óptima. El color de la letra principal es `#404040`.

![Guía de Tipografía](assets/cap-5/guidelines.png)

#### Espaciado
El espaciado entre elementos visuales asegura una estructura clara y organizada, ayudando a los usuarios a navegar por el contenido de forma fluida.

- **Tamaño de letra**: Las fuentes varían desde 12px hasta 98px según la jerarquía del texto.
- **Interlineado**: Mantenemos un interlineado proporcional para mejorar la legibilidad.

### 5.1.2 Information Architecture.
En esta sección, se describe cómo se organizará el contenido en la plataforma **GoUni**, tanto en la web como en las aplicaciones móviles. Se busca que la estructura sea intuitiva para los estudiantes universitarios, permitiendo una navegación fluida y el acceso rápido a las principales funcionalidades de la plataforma.

<hr>

#### 5.1.2.1 Organization Systems.

El Sistema de Organización de **GoUni** está diseñado para facilitar la interacción entre el usuario y la plataforma, asegurando que los estudiantes puedan encontrar y utilizar los servicios clave, como la búsqueda de viajes o la oferta de plazas en vehículos.

- **Jerarquía Visual**: La página principal destacará las acciones más importantes para el usuario, como “Buscar viaje” y “Publicar viaje”, con énfasis en botones de llamada a la acción que lleven a estas secciones.
- **Organización Secuencial**: Se aplicará a procesos clave como el registro de usuario, reserva de un viaje y configuración de perfil. Estos procesos se guiarán paso a paso, asegurando que los usuarios completen cada tarea sin problemas.
- **Organización Matricial**: Los filtros de búsqueda permitirán a los usuarios seleccionar viajes según el tipo de vehículo, horario y calificaciones del conductor, haciendo que sea más fácil encontrar un viaje que se ajuste a sus necesidades.
- **Esquemas de Categorización**: La categorización de la información podrá hacerse por orden alfabético (al buscar conductores por nombre), cronológico (al organizar las reservas según la fecha), o por audiencia (al segmentar entre conductores y pasajeros).

<br>

#### 5.1.2.2 Labelling Systems.

En **GoUni**, las etiquetas se diseñarán para ser claras, directas y comprensibles para los estudiantes, priorizando una navegación simple y una experiencia de usuario intuitiva.

### Etiquetas:
- **Inicio**: Al hacer clic en el logo de GoUni, los usuarios serán redirigidos a la página principal.
- **Buscar Viaje**: Opción en el menú principal que permite a los estudiantes buscar viajes disponibles en su universidad.
- **Publicar Viaje**: Los usuarios con vehículo propio podrán acceder a esta opción para publicar su ruta y disponibilidad de asientos.
- **Reservas Actuales**: Sección donde los usuarios pueden ver y gestionar sus reservas actuales.
- **Perfil**: Permite a los usuarios gestionar sus datos personales, verificar su identidad y ver su historial de viajes.

Una vez que los usuarios se registren y accedan a su cuenta, aparecerán nuevas etiquetas como:
- **Mis Viajes**: Un lugar donde los usuarios pueden revisar sus reservas activas y pasadas.
- **Calificar Conductores**: Opción que aparece tras la finalización de un viaje, permitiendo dejar comentarios y puntuaciones.

<br>

#### 5.1.2.3 SEO Tags and Meta Tags.

Los SEO Tags y Meta Tags son esenciales para mejorar la visibilidad de **GoUni** en los motores de búsqueda.

### Para la Landing Page:
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GoUni - Carpooling para Estudiantes Universitarios</title>
<meta name="description" content="GoUni es la plataforma de carpooling exclusiva para estudiantes universitarios, enfocada en la seguridad, sostenibilidad y economía colaborativa.">
<meta name="keywords" content="carpooling universitario, compartir autos estudiantes, movilidad sostenible, transporte colaborativo">
<meta name="author" content="GoUni Team">
```
### Para la App Movil:
```xml
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
          package="com.gouni.app">

    <application
            android:label="GoUni"
            android:icon="@mipmap/ic_launcher"
            android:theme="@style/Theme.GoUni">

        <meta-data
                android:name="description"
                android:value="Con GoUni, comparte tu auto con otros estudiantes universitarios y ahorra en transporte mientras ayudas al medio ambiente." />

        <meta-data
                android:name="keywords"
                android:value="carpooling estudiantes, compartir auto universidad, transporte sostenible, viaje colaborativo" />

        <meta-data
                android:name="author"
                android:value="GoUni Team" />

        <!-- Activity principal -->
        <activity
                android:name=".MainActivity"
                android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />
                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>

    </application>

</manifest>
```

<br>

#### 5.1.2.4 Searching Systems.

El sistema de búsqueda en GoUni facilitará a los usuarios encontrar viajes disponibles de forma rápida y efectiva. La funcionalidad de búsqueda incluirá:

Búsqueda por Universidad: Los estudiantes podrán buscar viajes que conecten con su universidad específica.
Filtros de Búsqueda: Los usuarios podrán filtrar los resultados por tipo de vehículo, horario de salida, calificación del conductor y disponibilidad de plazas.
Organización de Resultados: Los resultados se podrán ordenar de manera alfabética, por hora de salida o por la proximidad del conductor al punto de recogida.

![Searching.png](assets/cap-5/search.png)

#### 5.1.2.5 Navigation Systems.

El sistema de navegación de GoUni estará diseñado para que los usuarios puedan encontrar la información y realizar las acciones deseadas con el mínimo esfuerzo.

Navegación Principal: El menú superior incluirá accesos rápidos a las funciones clave: "Buscar Viaje", "Publicar Viaje", "Reservas Actuales" y "Perfil".
Navegación Móvil: En la versión móvil, el menú será desplegable para ahorrar espacio y mostrar solo las opciones más importantes de manera compacta. Los usuarios podrán regresar a la página de inicio pulsando el logo de GoUni.
Navegación Secundaria: En secciones como el perfil, habrá opciones adicionales para gestionar la cuenta, verificar la identidad o ajustar preferencias de notificaciones.

![Navigation.png](assets/cap-5/navigation.png)

# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1 Software Configuration Management

En la sección siguiente, se describirán las herramientas, convenciones, referencias y configuraciones utilizadas durante el desarrollo del proyecto, las cuales ayudaron a mantener la coherencia en el trabajo realizado.

### 6.1.1 Software Development Environment Configuration

En esta parte, se mencionarán los distintos programas de software que el equipo de desarrollo utilizó para llevar a cabo las tareas relacionadas con la creación del proyecto.

<br>

**Project Management**

- **Trello**: <https://trello.com/>  
  La plataforma de Trello se empleó para la gestión de las tareas y la organización del flujo del trabajo en el proyecto. Las tareas se presentaron dentro de tarjetas en listas con el integrante encargado de realizarlas. Además, utilizamos funcionalidades como agregar etiquetas de colores y marcar el proceso de las tareas. De esta manera, pudimos hacer seguimiento a nuestros avances en el proyecto.


- **Notion**: <https://www.notion.so/>  
  Notion fue utilizado para la colaboración del equipo en el proyecto. Se crearon calendarios y listas con las fechas de las reuniones del equipo. Además, se usaron herramientas como comentarios y menciones para fomentar el trabajo y la colaboración en equipo.

**Requirements Management**

- **Trello**: <https://trello.com/>  
  Trello se empleó para organizar los requisitos de la aplicación. En él se gestionó el product backlog, ordenado según la prioridad aplicando Fibonacci para enumerar las historias de usuario, y en otra sección organizándolas según las épicas.

**Product UX/UI Design**

- **Figma**: <https://www.figma.com/>  
  Figma nos ayudó a desarrollar los wireframes, mockups y prototipos de la aplicación móvil.


- **Miro**: <https://miro.com/es/>  
  Miro fue de utilidad para realizar los As-Is Scenario Mapping y To-Be Scenario Mapping para cada uno de los segmentos objetivos.


- **LucidChart**: <https://www.lucidchart.com/>

  LucidChart se utilizó para la creación de los diagramas de flujo y los diagramas de arquitectura de software.


- **UXPressia**: <https://uxpressia.com/>  
  UXPressia se empleó para la creación de User Personas, Empathy Maps, Journey Maps e Impact Maps. Usamos plantillas de UXPressia para elaborar cada una de estas herramientas, permitiendo exportar el trabajo realizado para incluirlo en el proyecto.

**Software Development**

- **Landing Page**  
  La landing page fue desarrollada utilizando **Angular** y **TypeScript (TS)**, lo que permitió un desarrollo más estructurado y escalable. Además, se utilizaron estilos personalizados con **CSS**. El diseño y desarrollo fueron optimizados para su despliegue en **Vercel**.


- **Frontend Web Application**  
  Para la aplicación web frontend, se utilizó **Angular** junto con **TypeScript (TS)**, empleando **Angular Material** para la creación de componentes UI consistentes y responsivos. En algunas partes del diseño también se integraron estilos de **Bootstrap** para complementar la interfaz. La arquitectura fue diseñada para ser modular, escalable y responsiva, optimizada para su despliegue en **Vercel**.


- **Backend**  
  El backend fue desarrollado utilizando **Java** con el framework **Spring Boot**, proporcionando APIs RESTful que interactúan con una base de datos **MySQL**. Este servicio fue desplegado en **Railway**, garantizando escalabilidad y un manejo eficiente de las integraciones con el frontend y la landing page.

**Software Testing**

Para las pruebas funcionales de la Landing Page y la aplicación web, se utilizaron herramientas de desarrollo de navegadores web como Google Chrome (<https://www.google.com/chrome/>), Microsoft Edge (<https://www.microsoft.com/en-us/edge>) y Mozilla Firefox (<https://www.mozilla.org/en-US/firefox/browsers/>).

**Software Deployment**

- **Vercel**: [https://vercel.com/](https://vercel.com/)  
  Para el despliegue de la Landing Page y la Web Application, se conectó el repositorio de GitHub con Vercel. Esto permitió que Vercel gestionara automáticamente las implementaciones cada vez que se realizaron actualizaciones en el repositorio.  
  Además, Vercel ofreció vistas previas de las ramas para facilitar la revisión de los cambios antes de publicarlos en producción.


- **Railway**: [https://railway.app/](https://railway.app/)  
  Para el despliegue del backend, se utilizó Railway, conectando el repositorio de GitHub al servicio. Esto permitió implementar automáticamente los cambios realizados en el código.  
  Railway proporcionó un entorno escalable y simplificado para manejar las configuraciones del servidor y las bases de datos, facilitando el proceso de desarrollo y despliegue.

**Software Documentation**


- **Google Drive**: [https://www.google.com/intl/es-419_pe/drive/](https://www.google.com/intl/es-419_pe/drive/)  
  Google Drive se utilizó para crear y gestionar documentos mediante **Google Docs**, permitiendo trabajar de manera colaborativa en los informes de las entregas. Además, se utilizó para almacenar archivos relevantes del proyecto y facilitar el acceso compartido.


- **Structurizr**: [https://structurizr.com/](https://structurizr.com/)  
  Se empleó **Structurizr** para la creación de diagramas C4, cubriendo los niveles de contexto, contenedor y componentes. Esta herramienta facilitó la visualización de la arquitectura del sistema utilizando una sintaxis basada en texto, ideal para mantener la documentación actualizada y consistente.


- **GitHub**: [https://github.com/](https://github.com/)  
  GitHub se utilizó tanto para la creación de la documentación como para el versionado y despliegue de la **Landing Page** y la **Web Application**. Su sistema de control de versiones y las herramientas para trabajo colaborativo permitieron gestionar cambios de manera eficiente.

### 6.1.2 Source Code Management.
### 6.1.3 Source Code Style Guide & Conventions

- Utilizaremos el lenguaje de etiquetas **HTML** para el desarrollo principal de nuestra Landing Page.
- Utilizaremos el lenguaje **CSS** para aplicar los estilos a la estructura de nuestra Landing Page.
- Implementaremos el lenguaje **JavaScript** para añadir funcionalidades a nuestra Landing Page.
- Utilizaremos el lenguaje **Gherkin** para diseñar pruebas de cada historia de usuario, siguiendo su estructura básica.

---

#### **Convenciones de Commits**

Nuestro equipo sigue las **Conventional Commits** en su versión 1.0.0 (disponible en [conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)) para garantizar claridad y coherencia en los registros. La estructura es la siguiente:

**Formato:**  
`<type>[scope opcional]: <description>`

- **type:** Indica el tipo de modificación realizada, con opciones como `feat` (nueva funcionalidad), `fix` (corrección de errores), `docs` (documentación), etc.
- **scope (opcional):** Define el alcance del cambio realizado en el código (e.g., un módulo o componente específico).
- **description:** Ofrece un resumen conciso de los cambios implementados.

---

#### **Convenciones de Versionado de Lanzamientos**

Seguimos el estándar **Semantic Versioning 2.0.0**, en el cual las versiones se presentan como `X.Y.Z`, con las siguientes interpretaciones:

- **X (Major):**  
  Incrementa con cambios incompatibles con versiones anteriores. Comienza en `0` durante el desarrollo inicial y pasa a `1` cuando el proyecto está listo para su lanzamiento público.  
  _Nota:_ Al aumentar `X`, los valores de `Y` y `Z` se reinician a `0`.

- **Y (Minor):**  
  Incrementa con cambios compatibles que agregan nuevas funcionalidades, generalmente provenientes de ramas `release`.  
  _Nota:_ Al aumentar `Y`, el valor de `Z` se reinicia a `0`.

- **Z (Patch):**  
  Incrementa con correcciones de errores menores, integrando commits realizados en ramas de corrección (`hotfix`) que se fusionan con la rama principal.

Este enfoque asegura que las versiones del proyecto sean claras y fácilmente interpretables por todos los miembros del equipo y usuarios finales.

### 6.1.4 Software Deployment Configuration.

Para configurar el despliegue del proyecto, seguimos los pasos detallados a continuación utilizando **Vercel** como plataforma:

1. **Entrar a Vercel y seleccionar la opción "Import an existing project"**  
   ![importAnExistingProject.001.png](assets/cap-6/import-image.png)


2. **Seleccionar la opción "Deploy with GitHub"**  
   ![deployGithub.002.png](assets/cap-6/deployGithub.002.png)


3. **Seleccionar la organización y el repositorio del proyecto**  
   Dentro de la organización, buscar y seleccionar el repositorio del proyecto que se desea desplegar en producción.


4. **Agregar la información necesaria para el despliegue**  
   Proporcionar los datos requeridos por la plataforma, como configuraciones específicas o variables de entorno si es necesario.


5. **Presionar el botón de despliegue**  
   Finalmente, hacer clic en el botón correspondiente al nombre del proyecto para iniciar el proceso de despliegue.

---

#### **Enlace de la Landing Page:**

Este enlace redirige a la landing page desarrollada con **Angular** y desplegada en **Vercel**. La página ofrece una introducción al proyecto, destacando sus características principales y facilitando el acceso a la aplicación web. Está diseñada para ser completamente responsiva y optimizada para dispositivos móviles, tabletas y computadoras de escritorio.

[**https://landing-page-with-angular-sigma.vercel.app/home**](https://landing-page-with-angular-sigma.vercel.app/home)

---

## 6.2 Landing Page, Services & Applications Implementation
### 6.2.1 Sprint 1.

En esta sección se registra y explica el avance en términos de producto y trabajo colaborativo para el **Sprint 1**, enfocado en el desarrollo de la landing page. Se detalla el progreso tangible y funcional, incluyendo su diseño, desarrollo y funcionalidades implementadas, así como la colaboración del equipo, los métodos de comunicación utilizados y las herramientas empleadas para garantizar una cooperación efectiva. Además, se incluye información sobre la planificación del sprint, el backlog de tareas, evidencia del desarrollo, documentación de servicios utilizados y reflexiones sobre la colaboración del equipo, proporcionando una visión completa del progreso alcanzado.

---

#### 6.2.1.1 Sprint Planning 1.

En el **Sprint Planning 1**, se presenta evidencia de la planificación e implementación de la landing page, incluyendo avances del proyecto y aprendizajes de colaboración en equipo registrados en **GitHub**.

| **Sprint #**                 | Sprint 1                                                                                                                                                                                                                                                                                                                                     |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                                                                                                                                                                              |
| **Date**                     | 30 de abril de 2025                                                                                                                                                                                                                                                                                                                          |
| **Time**                     | 22:00 horas (GMT-5)                                                                                                                                                                                                                                                                                                                          |
| **Location**                 | Modalidad remota                                                                                                                                                                                                                                                                                                                             |
| **Prepared By**              | LinkU                                                                                                                                                                                                                                                                                                                                        |
| **Attendees (to planning meeting)** | Todos los miembros de LinkU                                                                                                                                                                                                                                                                                                                  |
| **Sprint 0 Review Summary**  | Debido a que es el primer sprint, no hay review summary de un sprint anterior.                                                                                                                                                                                                                                                               |
| **Sprint 1 Retrospective Summary** | En este Sprint se planea desarrollar el landing page con HTML y CSS3. Previamente, el landing page se diseñó en Figma. El grupo discutió cómo diseñar el landing, implementar imágenes y todo lo referente a la interfaz. Al finalizar este sprint, el landing page estará desplegado en Netlify, permitiendo el acceso público al proyecto. |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                                                                                                                              |
| **Sprint Goal 1**            | El objetivo de este sprint es el desarrollo y despliegue de la landing page.                                                                                                                                                                                                                                                                 |
| **Sprint Velocity 1**        | 8                                                                                                                                                                                                                                                                                                                                            |
| **Sum of Story Points**      | 36                                                                                                                                                                                                                                                                                                                                           |

---
#### 6.2.1.2 Sprint Backlog 1.

En esta parte mostramos las tareas que se realizaron en este sprint.

**Link del Trello:**  
<https://trello.com/b/46pAPLAt/linku-sprint-1>

**Vista del Sprint Backlog en Trello:**  
![trelloSprint1.png](assets/cap-6/trello-sprint1.png)

---

| **Sprint #**   | **Sprint 1**                                                                                                                                                                                                                  |     |     |                                                                                             |           |                    |     |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|-----|---------------------------------------------------------------------------------------------|-----------|--------------------|-----|
| **User Story**  | **Work-item / Task**                                                                                                                                                                                                         |     |     |                                                                                             |           |                    |     |
| **ID**         | **Title**                        | **Id** | **Title**                        | **Description**                                                                             | **Estimation (hours)** | **Assigned To**    | **Status (To-do / In-Process / To-Review / Done)** |
| **E5-US01**     | Barra de navegación en la landing page | **T1** | Navbar section                  | Implementar navbar con botón (redirige a la aplicación) y responsive design          | 1h        | Alessandro David   | Done    |
| **E5-US02**     | Dirigirse a la aplicación mediante el landing page | **T2** | Button Call to Action         | Implementar el button Call to Action del navbar                          | 0.1h      | Rodrigo Chirinos   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T3** | Navbar section responsive       | Aplicar diseño responsive a las opciones del navbar                                         | 1h        | Rodrigo Chirinos   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T4** | Hero section                    | Implementar un hero section                                                                 | 1h        | Aaron Cruz         | Done    |
| **E5-US03**     | Sección hero del landing page   | **T5** | Responsive design hero section  | Aplicar design responsive al hero section                                                   | 1h        | Aaron Cruz         | Done    |
| **E5-US03**     | Sección hero del landing page   | **T6** | Product section and items       | Implementar Product section y los ítems característicos en orden grid                       | 1h        | Alessandro David   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T7** | Responsive design Product section | Implementar diseño responsive a Product section                                             | 1h        | Alessandro David   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T8** | Customers section and items     | Implementar Customers section y los ítems característicos en orden grid y aplicar animaciones | 1.5h      | Rodrigo Chirinos   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T9** | Responsive design Customers section | Implementar diseño responsive a Customers section                                         | 1h        | Rodrigo Chirinos   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T10** | Pricing section                | Implementar Pricing section y los ítems característicos en orden grid                       | 1h        | Alessandro Zevallos | Done    |
| **E5-US03**     | Sección hero del landing page   | **T11** | Responsive design Pricing section | Implementar diseño responsive a Pricing section                                         | 1h        | Alessandro Zevallos      | Done    |
| **E5-US03**     | Sección hero del landing page   | **T12** | Contact section                | Implementar Contact section y los ítems característicos en orden grid                       | 1h        | Alessandro Zevallos      | Done    |
| **E5-US03**     | Sección hero del landing page   | **T13** | Responsive design Contact section | Implementar diseño responsive a Contact section                                         | 1h        | Alessandro Zevallos      | Done    |
| **E5-US03**     | Sección hero del landing page   | **T14** | Footer section                 | Implementar footer section                                                                  | 1h        | Alessandro David   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T15** | Social media section            | Implementar icons para las redes sociales y también links                                   | 0.5h      | Alessandro David   | Done    |
| **E5-US03**     | Sección hero del landing page   | **T16** | Responsive design footer section | Aplicar diseño responsive                                                                   | 1h        | Aaron Cruz        | Done    |
| **E5-US04**     | Versión en español de landing page | **T17** | Switch que activa I18n         | Button de tipo switch que permite cambiar de idioma a la landing                            | 0.5h      | Alessandro David       | Done    |


#### 6.2.1.3 Development Evidence for Sprint Review.

En esta sección, se presentan los commits realizados en el repositorio de la landing page en GitHub. Estos commits reflejan el progreso y las mejoras implementadas durante el Sprint 1, proporcionando una visión detallada de las actividades de desarrollo y las contribuciones del equipo.

**Repositorio de la Landing Page:**  
[https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page)

---

| **Repository**                                                                 | **Branch** | **Commit Id**                              | **Commit Message**                                                                                                                                                                                                                                                                        | **Commit Message Body** | **Committed on (Date)** |
|--------------------------------------------------------------------------------|------------|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|-------------------------|
| [Landing Page](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page) | `main`     | `7a88b0b55f9bd3155b0e22080df5aac77c8b7755` | [feat: add feature for contact us](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/7a88b0b55f9bd3155b0e22080df5aac77c8b7755 "feat: add feature for contact us")                                                                                                     | -                       | 13 Mayo, 2025           |
|                                                                                |            | `7e94335dce635a9c98f89f15e03a79830b55b4db` | [feat: Add section header and footer](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/7e94335dce635a9c98f89f15e03a79830b55b4db "feat: Add section header and footer")                                                                                               | -                       | 13 Mayo, 2025          |
|                                                                                |            | `51b9b25bb58a16837e911c25c2a02ca84d9c2aff` | [Added Security & Plans sections](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/51b9b25bb58a16837e911c25c2a02ca84d9c2aff "Added Security & Plans sections")                                                                                                       | -                       | 13 Mayo, 2025           |
|                                                                                |            | `dd203f623004f4fa2f43249ac7b4e8661c98f5c9` | [feat: add feature for Sponsors](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/dd203f623004f4fa2f43249ac7b4e8661c98f5c9 "feat: add feature for Sponsors")                                                                                                         | -                       | 13 Mayo, 2025           |
|                                                                                |            | `bc7b0af06fcfe8467618e501d12d8bb3e32d89ff` | [added the GoUni benefits section from the landing page](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/bc7b0af06fcfe8467618e501d12d8bb3e32d89ff "added the GoUni benefits section from the landing page")                                                         | -                       | 13 Mayo, 2025           |
|                                                                                |            | `d0b74c90e865527a4f0aa2891f706776ad46a669` | [feat: add feature for ourApp & Portals](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/d0b74c90e865527a4f0aa2891f706776ad46a669 "feat: add feature for ourApp & Portals")                                                                                         | -                       | 13 Mayo, 2025           |
|                                                                                |            | `8c7655adfdf12f7cd62901e58a971ab1b3fea6a3` | [added ourTeam section](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/8c7655adfdf12f7cd62901e58a971ab1b3fea6a3 "added ourTeam section")                                                                                                                           | -                       | 13 Mayo, 2025           |
|                                                                                |            | `cc4951ff0a373a041ff98ad8657649fea466399f` | [Add "Who We Are" and "Why GoUni?" sections with corresponding content and styles](https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page/commit/cc4951ff0a373a041ff98ad8657649fea466399f "Add \"Who We Are\" and \"Why GoUni?\" sections with corresponding content and styles") | -                       | 13 Mayo, 2025           |

---

#### 6.2.1.4 Testing Suite Evidence for Sprint Review.

En este sprint, se han incorporado pruebas de aceptación escritas en **Gherkin**, asegurando que los requisitos del usuario se validen de manera efectiva. A continuación, se proporciona el enlace al repositorio de las pruebas de aceptación, donde se encuentra una descripción detallada de los escenarios de prueba y su implementación:

**Repositorio de pruebas de aceptación:**  
[https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test)

---

| **Repository**                                                                             | **Branch** | **Commit Id**                          | **Commit Message**                                                                                                                                                         | **Commit Message Body** | **Committed on (Date)** |
|--------------------------------------------------------------------------------------------|------------|----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|-------------------------|
| [LinkU Acceptance Test](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test) | `main`     | `491a119fae331fa5f96133e23a331898a2f8624c` | [feat: Add acceptance test](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test/commit/491a119fae331fa5f96133e23a331898a2f8624c "feat: Add acceptance test") | -                       | 13 Mayo, 2025           |
|                                                                                            |            | `51d4606a823313a47d14b04cd36c12b3dde0db63` | [chore: add AT02.feature file](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test/commit/51d4606a823313a47d14b04cd36c12b3dde0db63)                          | -                       | 13 Mayo, 2025           |
|                                                                                            |            | `744f6af82c0a2f70b912280d5d628fb800e01aed` | [chore: add AT03.feature file](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test/commit/744f6af82c0a2f70b912280d5d628fb800e01aed)                          | -                       | 13 Mayo, 2025           |
|                                                                                            |            | `96a6385da82f092f8896c9d232b781291f829788` | [chore: add AT04.feature file](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test/commit/96a6385da82f092f8896c9d232b781291f829788)                          | -                       | 13 Mayo, 2025           |
|                                                                                            |            | `1352e75921e965469d9662da5c9e8c2cfac9e0fc` | [chore: add AT05.feature file](https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test/commit/1352e75921e965469d9662da5c9e8c2cfac9e0fc)                          | -                       | 13 Mayo, 2025           |

---

#### 6.2.1.5 Execution Evidence for Sprint Review.

En este sprint logramos, como primera fase de nuestro producto final, desarrollar nuestra landing page usando HTML y CSS. También se implementó un diseño responsive para dispositivos Android e iOS, y su respectivo despliegue se realizó en **Netlify**.

![executionEvidence.png](assets/cap-6/gouni-main.png)

---

#### 6.2.1.6 Services Documentation Evidence for Sprint Review.

En el alcance del Sprint 1 se logró desarrollar la landing page, por lo que no se evidencia el empleo de web services.

---

#### 6.2.1.7 Software Deployment Evidence for Sprint Review.

Durante el primer sprint, desarrollamos y desplegamos la landing page del proyecto. El despliegue lo llevó a cabo uno de nuestros integrantes (Abraham), ya que el proceso no tomaba más de cinco minutos. Utilizamos **Netlify** como plataforma de despliegue, realizando varias pruebas en la rama "develop" antes de proceder con la rama "main".

**Pasos para el despliegue:**

1. Creación de cuenta en **Netlify**.
2. Selección de la opción "Add new website" para elegir el proyecto a desplegar.

   ![addNewWebsite.jpeg](assets/cap-6/vercel-deploying.png)

3. Selección de la rama "main" y clic en el botón "Deploy".

   ![deploy.jpeg](assets/cap-6/main-choosing.png)

---

#### 6.2.1.8 Team Collaboration Insights during Sprint.

**Distribución de aportes en el informe:**  
El desarrollo del informe se organizó dividiendo el repositorio por capítulos. Cada integrante realizó aportes específicos, distribuidos como se muestra en la siguiente tabla y las capturas incluidas.

**URL del repositorio para el Project Report:**  
<https://github.com/AppsMoviles-7128-Grupo-3/Report-GoUni>

| **Integrante**          | **Aporte en el informe**                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Alessandro Zevallos** | Competidores, Análisis competitivo, Estrategias frente a competidores, Product backlog, Style guidelines, Web style guidelines, Information architecture, Landing page UI design, Landing page mockup, Web applications mockup, Software deployment configuration, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review. ![chapter2.png](assets/cap-6/cap-2.png) |
| **Rodrigo Chirinos**    | User task matrix, User journey mapping, As-is scenario mapping, To-be scenario mapping, Wireflow diagrams, Diseño de entrevistas, Análisis de entrevistas, DDD architecture. ![userTaskMatrix.png](assets/cap-6/user-task-matrix.png)                                                                                                                                                                                                                                                       |
| **Aaron Cruz**             | Registro de entrevistas, Análisis de entrevistas, Software deployment configuration, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review. ![ubiquitusLanguage.png](assets/cap-6/ubiq-language.png)                                                                                                                                                              |
| **Alessandro David**    | Lean UX Hypothesis Statements, Lean UX Canvas, Diseño de entrevistas, User Personas, Empathy Mapping, Impact Mapping, Domain-Driven Software Architecture, Software Development Environment Configuration, Source Code Management, Source Code Style Guide & Conventions. ![hypothesisStatements.png](assets/cap-6/lean-ux.png)                                                                                                                                                             |

**Evidencia de los commits:**

![commitEvidence.png](assets/cap-6/commits.png)

Durante este sprint, para proteger la rama "main", creamos una rama "develop". Cada integrante creó una sub-rama "feature" para subir un capítulo del informe siguiendo las convenciones establecidas (**Conventional Commits** y **GitFlow**).

**GitHub Analytics del Sprint 1:**

![githubAnalyticsSprint.png](assets/cap-6/analytics.png)

---


## Conclusiones
- Este primer avance permitió definir claramente la problemática de movilidad estudiantil y establecer una propuesta de solución basada en el análisis del usuario, competencia y contexto. Se construyó una base sólida para el diseño centrado en el usuario y el desarrollo técnico del sistema.
- A través de herramientas como Lean UX y Domain-Driven Design, se logró alinear la solución con las necesidades reales de los estudiantes. El trabajo realizado sienta las bases para una plataforma colaborativa, sostenible y técnicamente viable.


## Bibliografia

1. NEI. (2021). *Encuesta Nacional de Hogares: Módulo de Victimización*. Lima, Perú: INEI.
2. Traverso, J. L. (2020). *Impacto del crimen en la calidad de vida de los habitantes de Lima Metropolitana*. *Revista Peruana de Criminología*, 3(1), 45-58.
3. Municipalidad Metropolitana de Lima. (2023). *Informe anual sobre el estado del transporte público en Lima*. Lima, Perú: Autor.
4. Flores Martos, C. Y., & Gonzales Otiniano, J. E. (2018). Efecto de la implementación del aplicativo Carpooling, bajo la norma ISO 9126, en la economía de estudiantes universitarios de Cajamarca.
5. Amaro Meza, R. D. (2019). Aplicación carpooling para el transporte de personas que trabajan en el Centro Empresarial de San Isidro.
6. Flores Martos, C. Y., & Gonzales Otiniano, J. E. (2018). Efecto de la implementación del aplicativo Carpooling, bajo la norma ISO 9126, en la economía de estudiantes universitarios de Cajamarca.
7. Valdez Fabian, I. K. (2023). Gestión de comunicación del proyecto de responsabilidad social Facilito de Osinergmin en Lima Metropolitana.
8. Jáuregui Mena, G. M. ¿La culpa es solo del conductor?: Un análisis de la responsabilidad de las plataformas digitales frente al consumidor de taxi por aplicativo en el Perú.
9. Hofer, S., & Schwentner, H. (2021). *Domain Storytelling: A Collaborative, Visual, and Agile Way to Build Domain-Driven Software*. Addison-Wesley Professional.
10. Vural, H., & Koyuncu, M. (2021). Does domain-driven design lead to finding the optimal modularity of a microservice?. *IEEE Access*, 9, 32721-32733.
11. Tramullas Ortiz, C. (2023). *Diseño y aplicación de autómatas programables basados en open source*.
12. Casado, P. E. F. (2020). *Domine JavaScript* (4ª Edición). Ra-Ma Editorial.
13. Casado, P. E. F. (2023). *Creación de componentes en JavaScript Curso practico*. Ra-Ma Editorial.
14. Fernández, P. (2023). *Construcción y diseño de páginas web con HTML, CSS y JavaScript*. Ediciones de la U.
15. García-Holgado, A., & García-Peñalvo, F. J. (2014). *Patrón arquitectónico para la definición de ecosistemas de eLearning basados en desarrollos open source*.
16. Molina Araque, F. A., & Espitia Pineda, A. A. (2016). *Propuesta de diseño e implementación de una aplicación móvil (App) como plataforma para compartir el uso del carro particular (carpooling) entre empleados de las sucursales en Bogotá de la empresa Claro Colombia sa, para teléfonos inteligentes cuyo sistema operativo sea Android 5.1*.
17. Villena Romero, C. L. (2023). *Estudio de prefactibilidad para la instalación de una empresa de transporte compartido (carpooling) en una universidad privada de la ciudad de Lima*.
18. Miranda de La Espriella, D., & Ramón García, N. (2016). *Fuímonos-Carpooling estudio y análisis para el desarrollo de la estrategia de mercadeo: plataforma web y móvil monografía de investigación*.
19. Díaz Domínguez, G. M. (2015). *Carpooling GT, aplicación para compartir vehículo* (Doctoral dissertation, Universidad de San Carlos de Guatemala).
20. Melo Domínguez, A. I. (2018). *Mejoramiento del problema de la congestión vehicular para la comunidad universitaria UDEC hacia una solución TI para carpooling*.
21. Mendizábal, E. L. (2015). *Los nuevos sistemas de utilización compartida de vehículos de transporte ("carpooling" y "car sharing"): entre la economía colaborativa y la competencia desleal*. *Revista de derecho mercantil*, (296), 283-334.
22. Cárdenas Peralta, N. F., Navarrete Cruzate, E. A., Jiménez Valdivia, K. M., & Arias Chilet, P. M. *CampusRoad*.
23. Murillo Paredes, A. (2021). *Diseño de software aplicando el patrón Domain-Driven Design*.

## Anexos


| Descripción                  | Link                                                       |
|------------------------------|------------------------------------------------------------|
| Repositorio General de LinkU | https://github.com/AppsMoviles-7128-Grupo-3                |
| Repositorio Reporte          | https://github.com/AppsMoviles-7128-Grupo-3/Report-GoUni   |
| Repositorio Landing Page     | https://github.com/AppsMoviles-7128-Grupo-3/GoUni-Landing-Page   |
| Repositorio Acceptance Tests | https://github.com/AppsMoviles-7128-Grupo-3/linku-acceptance-test    |
| Link landing page            | https://landing-page-with-angular-sigma.vercel.app/home    |
