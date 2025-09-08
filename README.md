<!--* Carátula -->

<div align="center">

# Informe de Trabajo Final 📙

<img src="./resources/Banner-UPC.png" alt="Banner UPC">

### Universidad Peruana de Ciencias Aplicadas ♨️

🧑‍💻 **Carrera:** Ingeniería de Software – 2025-02  

**Código y nombre del curso:** [1ASI0729] - [Desarrollo de Aplicaciones Open Source]  

**Sección:** 7414  

**Docente:** Rafael Oswaldo Castro Veramendi  

**Startup:** ProtectX

**Producto:** Sentinel  

<div align='left'>  

~~~C#
static string[] Integrantes() {
    return new string[] {
        "🧑‍💻 Ruiz Huisa, Daniel Elias - 202210764",
        "🧑‍💻 Villugas Jeronimo , Liam Anderson - 202211634",
        "👨‍💻 Quiroz Zambrano, Fabrizio Javier - 202213406",
        "👩‍💻 Hermoza Quispe, Jude Alessandro - 202318220",       
        "👩‍💻 Apellidos, Nombres - Código", 
    };
}
~~~

</div>

Agosto del 2025 🗓️  

</div>

---

## Registro de Versiones del Informe
| Versión | Fecha | Descripción | Responsable |
|---------|-------|-------------|-------------|
| 1.0     | 01/09/2025 | Versión inicial | Daniel Ruiz |
| 1.1     | dd/mm/yyyy | Ajustes sección II | Integrante Y |

---

## Project Report Collaboration Insights
> Aquí se registran observaciones del trabajo colaborativo, contribuciones por sprint y aprendizajes.

---

## Contenido del Informe

- [Informe de Trabajo Final 📙](#informe-de-trabajo-final-)
    - [Universidad Peruana de Ciencias Aplicadas ♨️](#universidad-peruana-de-ciencias-aplicadas-️)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido del Informe](#contenido-del-informe)
  - [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile 📌](#11-startup-profile-)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [5W’s + 2H’s](#5ws--2hs)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas 💼](#22-entrevistas-)
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
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.X. Sprint n](#52x-sprint-n)
      - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
      - [5.2.X.2. Aspect Leaders and Collaborators](#52x2-aspect-leaders-and-collaborators)
      - [5.2.X.3. Sprint Backlog n](#52x3-sprint-backlog-n)
      - [5.2.X.4. Development Evidence for Sprint Review](#52x4-development-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

## Student Outcome
> Describir los resultados de aprendizaje y cómo se alinean con el curso.

---

# Capítulo I: Introducción  



## 1.1. Startup Profile 📌
### 1.1.1. Descripción de la Startup
ProtectX es una startup del sector seguridad que busca responder al problema de la creciente inseguridad ciudadana en Lima y sus alrededores. Ofrece un servicio innovador basado en IoT que, ante cualquier irregularidad, envía una alerta inmediata a la entidad policial más cercana. Su propuesta combina sensores, alarmas y cámaras inteligentes, gestionadas desde una aplicación móvil que centraliza la información. El modelo de negocio se sustenta en un sistema de suscripción por niveles, que permite a los usuarios acceder a mayor cantidad de sensores según sus necesidades. Dirigida a personas que viven solas o que sienten temor por la inseguridad, ProtectX busca proporcionar un ambiente más seguro y fortalecer la protección de cada vivienda.
### 1.1.2. Perfiles de integrantes del equipo  
<div align='center'>
   <!--TODO: integrante 1 -->
  > 🧑‍💻 <strong>Daniel Elias Ruiz Huisa</strong> 
   

   <div align='center'>
     
   <img src="resources/Cap-1/Members/daniel.png" alt="imagen Daniel" width="100" align='right'>

   ~~~txt
   Soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente cursando el 6to ciclo de la carrera.
   
   Durante mi formación he adquirido conocimientos en diversas tecnologías y buenas prácticas de desarrollo. Mis principales fortalezas se encuentran lenguajes con orientados fuertemente a la POO como C++ y Java. 

   Adicionalmente, he trabajado con PGAdmin, MongoAtlas, MySQLlite como gestores de bases de datos, y con tecnologías web que me permiten tener una visión integral del desarrollo de software.

   ~~~

   </div>


   <div align='center'>
   <!--TODO: integrante 2 -->
  > 🧑‍💻 <strong>Jude Alessandro Hermoza Quispe</strong> 
   

   <div align='center'>
     
   <img src="resources/Cap-1/Members/jude.png" alt="imagen Jude" width="100" align='right'>

   ~~~txt
   Soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente cursando el 5to ciclo de la carrera.

   Me apasiona el desarrollo fullstack y tengo experiencia trabajando con tecnologías como Python, SQL Server, MongoDB y TypeScript. Disfruto aprender nuevas herramientas y lenguajes que me permitan aportar soluciones innovadoras en los proyectos en los que participo.

   Me considero una persona responsable, proactiva y con facilidad para adaptarme a los retos del trabajo en equipo. Aspiro a seguir creciendo profesionalmente y contribuir al desarrollo de software útil y de impacto social.
   ~~~

   </div>


    <div align='center'>
   <!--TODO: integrante 3 -->
  > 🧑‍💻 <strong>[Complete Name]</strong> 
   

   <div align='center'>
     
   <img src="resources/Cap-1/Members/.png" alt="imagen [name]" width="100" align='right'>

   ~~~txt
[descripcion]

   ~~~

   </div>

      <div align='center'>
   <!--TODO: integrante 4 -->
  > 🧑‍💻 <strong>[Complete Name]</strong> 
   

   <div align='center'>
     
   <img src="resources/Cap-1/Members/[name].png" alt="imagen [name]" width="100" align='right'>

   ~~~txt
[descripcion]

   ~~~

   </div>

      <div align='center'>
   <!--TODO: integrante 5 -->
**> 🧑‍💻 Fabrizio Javier Quiroz Zambrano (U202213406)**
   <div align='center'>

   <img src="resources/Cap-1/Members/Fabrizio1.jpg" alt="imagen Fabrizio" width="100" align='right'>

   ~~~txt
    Actualmente curso el sexto ciclo de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), donde he venido desarrollando una sólida base técnica y una visión crítica
    sobre el desarrollo de soluciones digitales. Mi formación me ha permitido explorar distintos lenguajes y herramientas, desde la lógica estructurada de C++ hasta el dinamismo de frameworks
    modernos como Angular, con los que he trabajado principalmente en el frontend. También tengo experiencia en Python y SQL, lo que me ha ayudado a comprender mejor la gestión de datos y la
    construcción de aplicaciones más completas.

    Más allá de lo técnico, me considero una persona comprometida con el aprendizaje constante, con facilidad para adaptarme a nuevos entornos y colaborar en equipo. Me gusta enfrentar desafíos
    que me obliguen a pensar fuera de lo convencional y a buscar soluciones eficientes y sostenibles.

    Tengo grandes expectativas para el curso de Desarrollo de Aplicaciones Open Source, ya que representa una oportunidad para fortalecer mis habilidades en el desarrollo fullstack y familiarizarme con nuevas tecnologías
    como Vue. Estoy convencido de que este tipo de experiencias me acercan cada vez más al perfil profesional que quiero construir: uno capaz de crear software útil, escalable y centrado en las personas.
   ~~~

   </div>

---
<div align='left'>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática  

<b>Problemática general</b>
En Lima y sus alrededores, la inseguridad ciudadana se ha convertido en una de las principales preocupaciones de la población. El aumento de robos, asaltos y delitos contra la propiedad ha superado la efectividad de los métodos tradicionales de protección, como rejas o rondas vecinales, generando una creciente sensación de vulnerabilidad. Este escenario plantea la necesidad de soluciones más eficientes que respondan a la magnitud del problema.

<b>Dimensión social</b>
La inseguridad no solo afecta el patrimonio de los ciudadanos, sino también su bienestar emocional. Muchas personas viven con miedo constante, lo que reduce su calidad de vida y limita su libertad de movimiento, especialmente en sectores donde los índices delictivos son más altos. Este clima de temor generalizado genera desconfianza en la comunidad, debilitando los lazos sociales y reforzando la percepción de que los hogares no son espacios plenamente seguros.

<b>Dimensión económica</b>
El impacto económico de la inseguridad se refleja en pérdidas materiales por robos, daños en las viviendas y el gasto recurrente en medidas de protección tradicionales que resultan insuficientes. Además, obliga a las familias a destinar recursos adicionales a reforzar la seguridad, lo que representa una carga financiera significativa. En conjunto, estos costos reducen la capacidad de ahorro y afectan la economía doméstica, evidenciando que la inseguridad es también un problema que compromete la estabilidad financiera de los hogares.

#### 5W’s + 2H’s
 🟢 **WHAT (Qué)**  
  Creciente ola de inseguridad ciudadana caracterizada por robos, asaltos y delitos contra la propiedad.  

 🟢 **WHEN (Cuándo)**  
  Actualmente, con mayor incidencia en los últimos años debido al incremento sostenido de la criminalidad.  

 🟢 **WHERE (Dónde)**  
  Principalmente en Lima Metropolitana y zonas aledañas con altos índices delictivos.  

 🟢 **WHO (Quién)**  
  Ciudadanos en general, con especial impacto en personas que viven solas o con temor frente a la inseguridad.  

 🟢 **WHY (Por qué)**  
  Falta de respuestas rápidas y efectivas ante emergencias, limitada capacidad de cobertura policial y deficiencia en las medidas tradicionales de seguridad.  

 🟢 **HOW (Cómo)**  
  Las personas recurren a rejas, cerraduras, cámaras convencionales o rondas vecinales, pero estas acciones resultan insuficientes frente a la magnitud del problema.  

 🟢 **HOW MUCH (Cuánto)**   
 El costo se refleja en pérdidas materiales por robos, daños en viviendas y una carga financiera extra para las familias, además del impacto social derivado del miedo y la desconfianza.

#### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
Los ciudadanos preocupados por la inseguridad en Lima y los profesionales encargados de la protección vecinal enfrentan dificultades para acceder a soluciones de seguridad que sean realmente efectivas, rápidas y adaptadas a sus necesidades particulares.

Hemos observado que muchos usuarios sienten que los sistemas tradicionales (rejas, alarmas convencionales, rondas vecinales) no ofrecen una respuesta inmediata ni una integración tecnológica suficiente, lo que genera desconfianza y baja percepción de seguridad en sus hogares.

¿Cómo podríamos diseñar un sistema de alerta y monitoreo inteligente que incremente la sensación de seguridad y permita una respuesta más rápida ante incidentes?

#### 1.2.2.2. Lean UX Assumptions

**Assumptions Worksheet**

### Supuestos del Negocio – Sentinel

1. **Creo que mis clientes tienen la necesidad de:**  
   Contar con un sistema de seguridad inteligente que brinde alertas inmediatas y centralice la información de sensores, cámaras y alarmas, permitiendo una respuesta rápida ante emergencias.

2. **Estas necesidades pueden resolverse con:**  
   Sentinel, una solución IoT que integra sensores, cámaras y alarmas inteligentes, gestionadas desde una aplicación móvil, conectada directamente con entidades policiales y vecinos.

3. **Mis clientes iniciales son (o serán):**  
   - Personas que viven solas o en zonas de alta inseguridad.
   - Familias preocupadas por la protección de su vivienda.
   - Juntas vecinales y administradores de edificios residenciales.

4. **El principal valor que un cliente quiere obtener de mi servicio es:**  
   Seguridad y tranquilidad, gracias a la capacidad de recibir alertas inmediatas y monitorear su hogar en tiempo real.  
   **También pueden obtener estos beneficios adicionales:**  
   Facilidad de uso, integración con autoridades, historial de eventos y personalización de niveles de protección.

5. **Adquiriré la mayoría de mis clientes a través de:**  
   - Recomendaciones de boca a boca en comunidades y vecindarios.
   - Alianzas con inmobiliarias y juntas vecinales.
   - Campañas digitales enfocadas en zonas de alta incidencia delictiva.

6. **Ganaré dinero mediante:**  
   - Suscripciones mensuales por niveles de servicio.
   - Venta de kits de sensores y cámaras inteligentes.
   - Servicios premium de monitoreo y soporte técnico.

7. **Mi principal competencia en el mercado será:**  
   Empresas de alarmas tradicionales y sistemas de cámaras convencionales.  
   **Superaremos a la competencia debido a:**  
   Nuestra integración IoT, respuesta automatizada y conexión directa con autoridades.

8. **El mayor riesgo de mi producto es:**  
   Que los usuarios no confíen en la efectividad del sistema o no perciban una mejora real en la seguridad.  
   **Lo resolveremos mediante:**  
   Pilotos en comunidades, testimonios de usuarios y mejoras continuas basadas en feedback.

9. **Otras suposiciones que, si se demuestran falsas, harán que nuestro negocio fracase:**  
   - Que los usuarios estén dispuestos a pagar por un sistema de seguridad inteligente.
   - Que las autoridades colaboren en la integración de alertas.
   - Que la tecnología funcione de manera confiable en diferentes entornos urbanos.

### Supuestos del Cliente – NutriSmart

1. **¿Quién es el cliente?**  
   Personas y familias que buscan mejorar la seguridad de su vivienda, especialmente quienes viven en zonas de alta incidencia delictiva, así como juntas vecinales y administradores de edificios.

2. **¿Dónde encaja nuestro producto en su vida?**  
   En la rutina diaria: al salir o llegar a casa, al monitorear la vivienda desde el móvil, o ante cualquier evento sospechoso detectado por los sensores.

3. **¿Qué problemas soluciona nuestro producto?**  
   - Falta de respuesta inmediata ante emergencias.
   - Dificultad para monitorear el hogar en tiempo real.
   - Limitada integración entre vecinos y autoridades.
   - Ineficiencia de sistemas tradicionales de seguridad.

4. **¿Cuándo y cómo se utiliza nuestro producto?**  
   - Uso diario: monitoreo desde la app, recepción de alertas.
   - En situaciones de emergencia: activación automática de alarmas y notificaciones.
   - Acceso desde dispositivos móviles y web.

5. **¿Qué características son importantes?**  
   - Alertas inmediatas y automáticas.
   - Integración de sensores, cámaras y alarmas.
   - Facilidad de uso y configuración.
   - Historial de eventos y personalización de notificaciones.

6. **¿Cómo debe verse y comportarse nuestro producto?**  
   - Interfaz intuitiva y moderna.
   - Acceso rápido a información crítica.
   - Notificaciones claras y en tiempo real.
   - Adaptable a distintos perfiles de usuario.

**Lean & Hypothesis - Driven Development**

#### 1.2.2.3. Lean UX Hypothesis Statements

<!-- Segmento 1: Personas que viven solas o familias preocupadas por la seguridad -->
**1ra Hipótesis**  
**Creemos que** ofrecer alertas automáticas e inmediatas a través de la app Sentinel aumentará la percepción de seguridad de los usuarios.  
**Sabremos que estamos bien cuando** los usuarios reporten sentirse más seguros y se reduzca el tiempo de respuesta ante incidentes en al menos un 30% durante pruebas piloto.

---

**2da Hipótesis**  
**Creemos que** permitir la personalización de niveles de protección y notificaciones incrementará la satisfacción y el uso continuo del sistema.  
**Sabremos que esto es cierto cuando** más del 60% de los usuarios ajusten sus configuraciones y mantengan el servicio activo después del primer mes.

---

**3ra Hipótesis**  
**Creemos que** integrar un historial de eventos accesible desde la app aumentará la confianza y el sentido de control de los usuarios.  
**Sabremos que esto es cierto cuando** al menos el 70% de los usuarios consulten el historial al menos una vez por semana.

---

<!-- Segmento 2: Juntas vecinales y administradores de edificios residenciales -->
**4ta Hipótesis**  
**Creemos que** la función de alertas comunitarias permitirá una mejor coordinación entre vecinos ante emergencias.  
**Sabremos que esto es cierto cuando** al menos el 50% de las alertas sean respondidas por más de un usuario de la comunidad.

---

**5ta Hipótesis**  
**Creemos que** ofrecer reportes de seguridad y estadísticas mensuales facilitará la toma de decisiones en la gestión vecinal.  
**Sabremos que esto es cierto cuando** los administradores descarguen o consulten los reportes al menos una vez al mes.

---

**6ta Hipótesis**  
**Creemos que** la integración de chat o foros internos fortalecerá la colaboración y comunicación entre vecinos.  
**Sabremos que esto es cierto cuando** se registre un aumento del 40% en la interacción entre usuarios dentro de la plataforma.

---

<!-- Segmento 3: Autoridades locales y serenazgo -->
**7ma Hipótesis**  
**Creemos que** la recepción de alertas en tiempo real permitirá a las autoridades responder más rápido a incidentes reportados por Sentinel.  
**Sabremos que esto es cierto cuando** el tiempo promedio de respuesta disminuya en al menos un 25% en zonas piloto.

---

**8va Hipótesis**  
**Creemos que** el acceso a mapas de calor y reportes de incidentes ayudará a las autoridades a optimizar la vigilancia y patrullaje.  
**Sabremos que esto es cierto cuando** las rutas de patrullaje se ajusten en función de los datos proporcionados por Sentinel.

---

**9na Hipótesis**  
**Creemos que** la posibilidad de enviar mensajes o recomendaciones directas a los usuarios desde la plataforma mejorará la percepción de cercanía y apoyo de las autoridades.  
**Sabremos que esto es cierto cuando** al menos el 60% de los usuarios valore positivamente la comunicación recibida en encuestas de satisfacción.

---
#### 1.2.2.4. Lean UX Canvas  
---
### 1.3. Segmentos Objetivos

#### Segmento Objetivo 1: Personas que viven solas o familias preocupadas por la seguridad

**Aspectos Demográficos:**
- **Sexo:** Masculino y femenino
- **Edades:** 25 a 65 años
- **Nivel Socioeconómico:** Clases B, C y D (media, media-baja y baja)
- **Ocupación:** Trabajadores dependientes, independientes, amas de casa, adultos mayores
- **Ingresos:** Ingresos medios o bajos, con preocupación por proteger su patrimonio

**Aspectos Geográficos:**
- **Ubicación:** Lima Metropolitana y zonas urbanas/periurbanas con alta incidencia delictiva
- **Acceso a tecnología:** Uso frecuente de smartphones y acceso a internet móvil

**Aspectos Psicográficos:**
- **Motivaciones:** Proteger a su familia y bienes, reducir el miedo y la ansiedad por la inseguridad
- **Estilo de vida:** Hogareño, con preocupación constante por la seguridad del entorno
- **Preocupaciones:** Robos, asaltos, respuesta lenta de autoridades, falta de soluciones tecnológicas accesibles
- **Adaptación a la tecnología:** Disposición a usar apps móviles si son fáciles y útiles

---

#### Segmento Objetivo 2: Juntas vecinales y administradores de edificios residenciales

**Aspectos Demográficos:**
- **Sexo:** Masculino y femenino
- **Edades:** 30 a 65 años
- **Nivel Socioeconómico:** Clases B y C (media y media-baja)
- **Ocupación:** Líderes vecinales, administradores de edificios, representantes comunales

**Aspectos Geográficos:**
- **Ubicación:** Urbanizaciones, condominios y edificios en zonas con problemas de seguridad
- **Acceso a tecnología:** Uso de computadoras y smartphones para gestión y comunicación

**Aspectos Psicográficos:**
- **Motivaciones:** Mejorar la seguridad colectiva, fortalecer la colaboración entre vecinos y con autoridades
- **Estilo de vida:** Proactivos en la gestión comunitaria, buscan soluciones integrales y tecnológicas
- **Preocupaciones:** Coordinación eficiente ante emergencias, falta de herramientas para monitoreo y alerta comunitaria
- **Adaptación a la tecnología:** Alta disposición a implementar soluciones digitales que faciliten la gestión y comunicación

---

#### Segmento Objetivo 3: Autoridades locales y serenazgo

**Aspectos Demográficos:**
- **Sexo:** Masculino y femenino
- **Edades:** 25 a 60 años
- **Ocupación:** Personal de serenazgo, policías municipales, funcionarios de seguridad ciudadana

**Aspectos Geográficos:**
- **Ubicación:** Municipios y distritos de Lima y alrededores

**Aspectos Psicográficos:**
- **Motivaciones:** Mejorar la capacidad de respuesta y monitoreo, optimizar recursos y coordinación con la comunidad
- **Preocupaciones:** Falta de información en tiempo real, dificultad para priorizar emergencias, baja colaboración vecinal
- **Adaptación a la tecnología:** Interés en herramientas que automaticen alertas y centralicen información para la toma de decisiones

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

> Criterios de comparación: público objetivo principal, complejidad de uso, costo aproximado, foco geográfico, y capacidades clave (presupuestos, reportes, proyecciones, colaboración, educación financiera).

| Competidor | Enfoque | Fortalezas | Debilidades | Ventaja de ProtectX |
|------------|---------|------------|-------------|----------------------|
| **YNAB (You Need a Budget)** | Presupuesto personal con metodología “zero-based”. | Disciplina presupuestaria, comunidad activa, formación financiera. | Precio elevado, curva de aprendizaje, interfaz solo en inglés. | ProtectX ofrece ruta de aprendizaje integrada y planes más accesibles para LATAM, con onboarding guiado en español. |
| **Simplifi by Quicken** | Presupuesto personal y flujo de caja futuro. | Plan de gasto personalizable, proyección de cashflow, fácil para principiantes. | Enfoque B2C; funciones empresariales limitadas. | ProtectX integra vistas personales y de microempresa en un mismo panel, con progresión de funcionalidades. |
| **Monarch Money** | Gestión integral personal (presupuesto + inversiones). | Consolidación de cuentas, colaboración con asesores/familia, interfaz moderna. | Precio medio/alto; foco en EE. UU./Canadá. | ProtectX prioriza LATAM (monedas locales, categorías locales) y un plan de entrada económico. |
| **Wallet (BudgetBakers)** | Control de gastos con IA de categorización. | Amplios reportes, sincronización bancaria, análisis guiado. | Límite de cuentas en plan gratis; menos foco educativo. | ProtectX combina registro sencillo con micro-lecciones y alertas educativas contextuales. |
| **PocketGuard** | Presupuesto personal “safe-to-spend”. | Seguimiento de suscripciones, payoff de deudas, análisis de gasto. | Menor profundidad en metas/proyecciones avanzadas. | ProtectX añade metas con hitos, proyecciones y recomendaciones accionables para LATAM. |
| **QuickBooks Online** | Contabilidad para pymes. | Suite robusta, estándar de mercado, ecosistema amplio. | Costo y complejidad altos para microempresas sin contable. | ProtectX ofrece “lo esencial” para pymes sin contable: flujo de caja, presupuestos y reportes simplificados. |
| **Xero** | Contabilidad en la nube pymes. | Automatizaciones, integraciones, UX limpia. | Planes en USD; puede requerir asesor externo. | ProtectX prioriza simplicidad operativa y educación financiera para dueños no contables. |
| **Zoho Books** | Contabilidad pymes y freelancers. | Plan gratuito limitado, buena relación precio/valor, integraciones Zoho. | Funciones avanzadas en planes superiores; configuración inicial. | ProtectX reduce fricción inicial (plantillas locales, categorías pre-cargadas) y guía paso a paso. |
| **Alegra (LATAM)** | Contabilidad y facturación electrónica para pymes. | Cumplimiento local, factura electrónica, soporte 24/7. | Orientado a procesos contables/fiscales; curva de adopción. | ProtectX se enfoca en gestión financiera diaria (presupuestos, metas, flujo de caja) con menor complejidad y costo. |

**Resumen de ventaja competitiva de ProtectX**  
- **Localización LATAM** (monedas, categorías y realidades de gasto locales).  
- **Simplicidad + educación**: onboarding guiado, micro-lecciones y alertas educativas sin sobrecargar al usuario.  
- **Escalabilidad**: un solo producto que crece desde uso personal hasta microempresa sin “cambio de plataforma”.  
- **Costo accesible** con plan gratuito funcional y premium de bajo costo.  

---

### 2.1.2. Estrategias y tácticas frente a competidores

- **Posicionamiento**: “La forma más sencilla y en español para tomar control de tus finanzas personales y de tu microempresa”.  
- **Go-to-market LATAM**: campañas con casos reales de estudiantes/emprendedores y pricing local.  
- **Producto**:  
  - Onboarding por objetivos (ahorro, control de gastos, flujo de caja de negocio).  
  - Módulo de **metas** con hitos, recordatorios y proyecciones mensuales.  
  - **Reportes claros**: salud financiera, cashflow, desviaciones vs. presupuesto y alertas.  
  - **Importación fácil** (CSV/WhatsApp/Excel) para usuarios sin conexión bancaria abierta.  
- **Educación integrada**: micro-contenidos dentro del flujo (p. ej., si el gasto en “delivery” excede 20%, se muestra tip y acción sugerida).  
- **Alianzas**: con contadores/mentores locales y, a futuro, con fintechs de open finance y facturación para ampliar capacidades.  
- **Experimentos de pricing**: plan gratis (básico), plan personal (metas/alertas) y plan negocio (reportes y multi-usuario).  

---

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmentos objetivo**

1. **Estudiantes y jóvenes profesionales** (18–30): buscan control de gastos, hábitos de ahorro y educación financiera.  
2. **Emprendedores y microempresas** (1–10 colaboradores): requieren visibilidad del flujo de caja, presupuestos y reportes simples.

**Preguntas por Segmento Objetivo**

**A. Estudiantes y jóvenes profesionales**  
1. ¿Cómo registras hoy tus gastos e ingresos y con qué frecuencia lo haces?  
2. ¿Qué momento del mes se te hace más difícil para mantener tu presupuesto y por qué?  
3. Si una app te enviara **solo dos** alertas útiles al día, ¿cuáles deberían ser?  
4. ¿Qué te impediría usar una app de finanzas todos los días durante 30 días seguidos?  
5. ¿Qué nivel de detalle necesitas en reportes/visualizaciones para sentir control real de tus finanzas?

**B. Emprendedores y microempresas**  
1. ¿Cómo controlas hoy el flujo de caja semanal y qué decisiones tomas a partir de él?  
2. ¿Qué errores o retrabajos te genera el registro de gastos/ingresos (personas, procesos o herramientas)?  
3. ¿Qué reporte mensual te gustaría ver en **una sola pantalla** para decidir compras, deudas o inversiones?  
4. ¿Qué automatizarías primero: conciliación, facturas, alertas de sobre-gasto, o proyecciones? ¿Por qué?  
5. ¿Cuál sería el “momento wow” que te haría pagar por una app como ProtectX?

---

### 2.2.2. Registro de entrevistas

| Entrevistado | Segmento | Fecha | Hallazgos clave |
|--------------|----------|-------|-----------------|
| E-01 | Estudiante/Profesional joven | AAAA-MM-DD | [datos relevantes] |
| E-02 | Emprendedor/Microempresario | AAAA-MM-DD | [datos relevantes] |
| ... | ... | ... | ... |

---

### 2.2.3. Análisis de entrevistas

- **Patrones comunes:** [Identificar temas que aparezcan de manera recurrente en diferentes perfiles].  
- **Diferencias por segmento:** [Señalar necesidades distintas entre estudiantes y emprendedores].  
- **Conclusiones:** [Indicar las funcionalidades más prioritarias para cada segmento].  

---


## 2.3. Needfinding
### 2.3.1. User Personas  
### 2.3.2. User Task Matrix  
### 2.3.3. User Journey Mapping  
### 2.3.4. Empathy Mapping  
### 2.3.5. As-is Scenario Mapping  
---
## 2.4. Ubiquitous Language  

---

# Capítulo III: Requirements Specification  

## 3.1. To-Be Scenario Mapping  
## 3.2. User Stories  
## 3.3. Impact Mapping  
## 3.4. Product Backlog  

---

# Capítulo IV: Product Design  

## 4.1. Style Guidelines  
### 4.1.1. General Style Guidelines  
### 4.1.2. Web Style Guidelines  
---
## 4.2. Information Architecture  
### 4.2.1. Organization Systems  
### 4.2.2. Labeling Systems  
### 4.2.3. SEO Tags and Meta Tags  
### 4.2.4. Searching Systems  
### 4.2.5. Navigation Systems  
---
## 4.3. Landing Page UI Design  
### 4.3.1. Landing Page Wireframe  
### 4.3.2. Landing Page Mock-up  
---
## 4.4. Web Applications UX/UI Design  
### 4.4.1. Web Applications Wireframes  
### 4.4.2. Web Applications Wireflow Diagrams  
### 4.4.3. Web Applications Mock-ups  
### 4.4.4. Web Applications User Flow Diagrams  
---
## 4.5. Web Applications Prototyping  
---
## 4.6. Domain-Driven Software Architecture  
### 4.6.1. Software Architecture Context Diagram  
### 4.6.2. Software Architecture Container Diagrams  
### 4.6.3. Software Architecture Components Diagrams  
---
## 4.7. Software Object-Oriented Design  
### 4.7.1. Class Diagrams  
### 4.7.2. Class Dictionary  
---
## 4.8. Database Design  
### 4.8.1. Database Diagram  

---

# Capítulo V: Product Implementation, Validation & Deployment  

## 5.1. Software Configuration Management  
### 5.1.1. Software Development Environment Configuration  
### 5.1.2. Source Code Management  
### 5.1.3. Source Code Style Guide & Conventions  
### 5.1.4. Software Deployment Configuration  
---
## 5.2. Landing Page, Services & Applications Implementation  
### 5.2.X. Sprint n  
#### 5.2.X.1. Sprint Planning n  
#### 5.2.X.2. Aspect Leaders and Collaborators  
#### 5.2.X.3. Sprint Backlog n  
#### 5.2.X.4. Development Evidence for Sprint Review  
#### 5.2.X.5. Execution Evidence for Sprint Review  
#### 5.2.X.6. Services Documentation Evidence for Sprint Review  
#### 5.2.X.7. Software Deployment Evidence for Sprint Review  
#### 5.2.X.8. Team Collaboration Insights during Sprint  
---
## 5.3. Validation Interviews  
### 5.3.1. Diseño de entrevistas  
### 5.3.2. Registro de entrevistas  
### 5.3.3. Evaluaciones según heurísticas  
---
## 5.4. Video About-the-Product  

---

# Conclusiones  

## Conclusiones y recomendaciones  

## Video About-the-Team  

---

# Bibliografía  
> Referencias en formato APA.  

---

# Anexos  
> Evidencias, capturas, diagramas adicionales.  
</div>
