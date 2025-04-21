<div align="center">
  
## Universidad Peruana de Ciencias Aplicadas

![Image](images/upc-logo.png)

## TB1 "StayMap"


**1ASI0729 - DESARROLLO DE APLICACIONES OPEN SOURCE**

Carrera de Ingeniería de Software


**NRC:** 2510-4334

**Profesor:** Hugo Allan Mori Paiva

**Integrantes:**

Collantes Carrillo, Diego Mateo (u202311823)

Lizarbe Alvarez, Ariana Nickole (u202311704)

Ortiz Cardenas, Johanna Antuanete (u202310358)

Zegarra Lopez, Renato Sebastian Rubber (u202311558)

Zúñiga Murillo, Diego Sebastian (u202310636)


**2025**
</div>

## Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TP</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TB2</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TF</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Contents

- [STUDENT OUTCOME](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [CAPÍTULO I: INTRODUCCIÓN](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## STUDENT OUTCOME
ABET - EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
<tbody>
    <tr>
      <td>Comunica oralmente con efectividad a diferentes rangos de audiencia</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Comunica por escrito con efectividad a diferentes rangos de audiencia</td>
      <td></td>
      <td></td>
    </tr>
    </tbody>
</table>

# CAPÍTULO I: INTRODUCCIÓN

# 1.1. Startup Profile

## 1.1.1. Descripción de la Startup
MIROH es una startup creativa y tecnológica comprometida con transformar la manera en que las personas descubren, conectan y viven la música en vivo. Creemos que cada concierto, sin importar su tamaño, tiene el poder de generar emociones únicas y crear vínculos duraderos entre artistas y fans. Por ello, trabajamos en soluciones digitales innovadoras que conectan al público con experiencias musicales auténticas y accesibles.
Nos enfocamos en el desarrollo de StayMap, una aplicación web interactiva que actúa como un puente entre los amantes de la música y los escenarios de su ciudad. A través de un mapa dinámico con geolocalización, los usuarios pueden explorar eventos en tiempo real, seguir a sus artistas favoritos, conocer las fechas de sus giras, hacer check-in en conciertos y compartir momentos con otros fans. Además, brindamos herramientas de promoción y visibilidad para bandas emergentes, contribuyendo activamente al crecimiento de la escena musical independiente.
En MIROH, apostamos por el poder de la comunidad, el descubrimiento espontáneo y la tecnología como medio para enriquecer las experiencias culturales. Nuestra visión es construir una red global donde cada presentación en vivo —desde un bar local hasta un festival internacional— pueda ser descubierta, compartida y vivida al máximo, celebrando la diversidad y el dinamismo del mundo musical.
Con pasión, creatividad y enfoque social, desde el corazón de MIROH impulsamos proyectos como StayMap, que reimaginan el futuro de la música en vivo y lo acercan a quienes más lo disfrutan.

## 1.1.2. Perfiles de integrantes del equipo

# 1.2 Solution Profile
## 1.2.1. Antecedentes y problemática
**What**:

Las personas tienen dificultades para descubrir y conectarse con conciertos en vivo, especialmente los de pequeña o mediana escala. Esto limita la visibilidad de artistas emergentes, dificulta el acceso a experiencias musicales auténticas y reduce el impacto de la música local en la vida diaria de los fans.

De acuerdo con Chartmetric (2023) en su informe “Year in music 2023: Part 1”, de los aproximadamente 710,000 nuevos artistas agregados a su plataforma en dicho año, solo el 0.1% logró ubicarse entre los 35,000 artistas más exitosos. Mientras tanto, el 99.9% se mantuvo en la categoría de "sin descubrir" o "en desarrollo". Estas cifras subrayan la abrumadora dificultad que enfrentan los nuevos talentos para destacarse en un mar de competencia feroz.

**When**:

Esta problemática suele presentarse en momentos en los que las personas están motivadas a vivir experiencias musicales, pero no cuentan con la información necesaria para hacerlo. Por ejemplo, puede ocurrir cuando alguien decide salir de forma espontánea a un concierto una noche de fin de semana, pero no sabe dónde buscar eventos cercanos ni cuáles están activos en ese momento. También se da cuando un fan sigue a un artista emergente, pero no se entera de que este se presentará en su ciudad debido a la falta de difusión o herramientas para recibir notificaciones personalizadas. Otro escenario común es el de un turista que visita una nueva ciudad con ganas de explorar su vida cultural, pero al no conocer medios locales o redes de promoción independientes, termina perdiéndose eventos interesantes. Además, muchos conciertos organizados por bandas nuevas o independientes pasan desapercibidos porque no cuentan con canales efectivos para llegar a su público ideal, lo que limita tanto la asistencia como el crecimiento de la escena musical local. En todos estos casos, la desconexión entre el público y la música en vivo se traduce en oportunidades perdidas tanto para los fans como para los artistas.

**Where**:

Los problemas relacionados con el descubrimiento y la conexión con conciertos en vivo pueden surgir en diferentes espacios y contextos. Esto sucede tanto en el entorno cotidiano de las personas como en situaciones más específicas, como cuando visitan una nueva ciudad o buscan actividades culturales fuera de su rutina habitual. La desconexión entre los eventos musicales y el público puede ocurrir en calles con alta oferta artística pero poca visibilidad digital, en barrios donde se organizan conciertos independientes sin una estrategia de difusión clara, o incluso en ciudades donde los medios de promoción tradicionales no alcanzan a públicos más jóvenes o digitales.

StayMap se utiliza en diversos contextos urbanos y culturales para facilitar el acceso a experiencias musicales auténticas:

- En la ciudad de origen del usuario: Los usuarios acceden a la aplicación para descubrir conciertos cercanos en tiempo real, ya sea para planificar su fin de semana o salir de manera espontánea en busca de música en vivo.
- Durante viajes o turismo cultural: Al llegar a una nueva ciudad, los usuarios pueden explorar la agenda musical local sin depender de medios tradicionales o recomendaciones limitadas.
- En espacios donde la escena independiente tiene poca visibilidad: StayMap permite a los usuarios acceder a eventos organizados por artistas emergentes o colectivos culturales que normalmente no figuran en los canales de difusión masiva.


StayMap está diseñada para personas amantes de la música en vivo que desean explorar y disfrutar de conciertos con mayor facilidad, especialmente en escenarios donde la información no es fácilmente accesible o centralizada.

**Why**:

Porque la música en vivo tiene un valor emocional, social y cultural que va más allá del entretenimiento. Asistir a conciertos fortalece el sentido de comunidad, apoya directamente a los artistas y permite descubrir nuevas propuestas que muchas veces no llegan a los circuitos comerciales. Sin embargo, esta experiencia se ve limitada cuando no existe una herramienta efectiva que conecte al público con los eventos musicales a su alrededor, especialmente en el caso de conciertos independientes o espontáneos. La falta de difusión adecuada no solo perjudica a los músicos emergentes, sino también a los fans que anhelan vivir momentos auténticos y significativos a través de la música. En un mundo hiperconectado, resulta paradójico que aún sea tan difícil descubrir qué está ocurriendo musicalmente a nivel local, justo cuando las personas tienen la disposición, el tiempo o el ánimo de salir a explorar.

**Who**:

Esta problemática afecta principalmente a dos grupos:
- Fans de la música en vivo, tanto jóvenes como adultos, que desean descubrir conciertos interesantes cerca de ellos pero carecen de información actualizada, personalizada o centralizada.
- Artistas emergentes y bandas independientes, que enfrentan grandes barreras para visibilizar sus presentaciones en un entorno saturado y competitivo, sin contar con recursos o redes de difusión eficientes.



**How**:

StayMap aborda esta problemática mediante una aplicación móvil que centraliza, personaliza y geolocaliza la información sobre conciertos en vivo. Utilizando tecnología basada en ubicación y preferencias del usuario, StayMap permite:
- Descubrir eventos en tiempo real cerca de su ubicación.
- Filtrar por géneros, fechas y tipo de eventos.
- Recibir notificaciones personalizadas sobre conciertos de artistas favoritos o nuevos talentos similares.
- Acceder a eventos independientes que usualmente no aparecen en medios tradicionales.
- Compartir y recomendar eventos con amigos, generando una comunidad activa.

Esta solución integra datos de distintas fuentes, incluyendo registros de eventos, publicaciones de artistas y recomendaciones sociales, facilitando una experiencia fluida, espontánea y enriquecedora.

**How much:**

Las consecuencias de no atender esta problemática incluyen:
- Pérdida de oportunidades para artistas de darse a conocer, generar ingresos y construir una base de fans sólida.
- Reducción en la asistencia a conciertos, afectando la economía de espacios culturales, bares y promotores locales.
- Empobrecimiento de la vida cultural urbana, donde eventos valiosos pasan desapercibidos y la diversidad musical queda eclipsada.
- Frustración del público, que quiere vivir experiencias auténticas pero no encuentra cómo hacerlo fácilmente.

Al mismo tiempo, existe un alto potencial de impacto positivo: al facilitar la conexión entre público y música en vivo, se promueve la cultura local, se fomenta el descubrimiento musical y se apoya directamente al ecosistema artístico independiente.

