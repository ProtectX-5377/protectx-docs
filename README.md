<!--* Carátula -->

<div align="center">

# Informe de Trabajo Final 📙

<img src="./resources/Cap-1/Banner-UPC.png" alt="Banner UPC">

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
    - [Supuestos del Negocio – Sentinel](#supuestos-del-negocio--sentinel)
    - [Supuestos del Cliente – NutriSmart](#supuestos-del-cliente--nutrismart)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos Objetivos](#13-segmentos-objetivos)
      - [Segmento Objetivo 1: Personas que viven solas o familias preocupadas por la seguridad](#segmento-objetivo-1-personas-que-viven-solas-o-familias-preocupadas-por-la-seguridad)
      - [Segmento Objetivo 2: Juntas vecinales y administradores de edificios residenciales](#segmento-objetivo-2-juntas-vecinales-y-administradores-de-edificios-residenciales)
      - [Segmento Objetivo 3: Autoridades locales y serenazgo](#segmento-objetivo-3-autoridades-locales-y-serenazgo)
- [Capítulo II: Requirements Elicitation \& Analysis — ProtectX](#capítulo-ii-requirements-elicitation--analysis--protectx)
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
    - [4.7.2. Class Dictionary](#472-class-dictionary-1)
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
     
   <img src="resources/Cap-1/Members/Daniel.jpg" alt="imagen Daniel" width="100" align='right'>

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
  > 🧑‍💻 <strong>[Liam Anderson Villugas Jeronimo]</strong> 
   

   <div align='center'>
     
   <img src="resources/Cap-1/Members/.png" alt="imagen Liam" width="100" align='right'>

   ~~~txt
   Soy Estudiante de Ingienieria de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), Estoy cursando actualmente el 6to ciclo de la carrera.

   Me atrae mucho el desarrollo de aplicaciones y el uso de las bases de datos tanto SQL como NoSQL. Cuento con conocimientos en lenguajes en python, Aprendiendo C# y en cuanto a las bases de datos tengo conocimientos de SQLite, SQLserver Y MongoDB.

   Me considero una persona en Aprendizaje constante e intento mantener la tranquilidad bajo prension al trabajar.
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

# Capítulo II: Requirements Elicitation & Analysis — ProtectX

## 2.1. Competidores

### 2.1.1. Análisis competitivo

> Criterios de comparación: público objetivo principal, complejidad de instalación/uso, costo aproximado, foco geográfico, y capacidades clave (detección, monitoreo, evidencia, colaboración comunitaria, escalamiento a autoridades).

| Competidor | Enfoque | Fortalezas | Debilidades | Ventaja de ProtectX |
|------------|---------|------------|-------------|----------------------|
| **Verisure (Securitas Direct)** | Alarmas con monitoreo 24/7 para hogares y negocios. | Marca reconocida, instalación profesional, coordinación con serenazgo/PNP. | Contratos largos y costosos, poco flexible para juntas vecinales. | ProtectX es modular, con auto-instalación guiada, alertas inmediatas y funciones de comunidad. |
| **ADT** | Sistemas de alarma y sensores para el hogar. | Experiencia global, soporte confiable, ecosistema robusto. | Menor integración comunitaria y adaptación local limitada. | ProtectX integra comunidad + hogares con costos escalables y protocolos de respuesta locales. |
| **Securitas Perú (B2B)** | Seguridad corporativa (monitoreo, CCTV, control de acceso). | Portafolio amplio, servicios gestionados, SOC 24/7. | Costos elevados, pensado para empresas, no hogares. | ProtectX empaqueta lo esencial en una solución accesible para familias, juntas y autoridades locales. |
| **Ring (Amazon)** | Cámaras/timbres inteligentes con app móvil. | Interfaz simple, ecosistema smart home, fácil adopción. | Sin vínculo con autoridades locales; soporte LATAM limitado. | ProtectX conecta sensores/cámaras a serenazgo/PNP y fomenta coordinación vecinal. |
| **Hikvision / Dahua (kits IoT)** | Cámaras y alarmas con analítica perimetral. | Amplia oferta, disponibilidad en Perú, hardware sólido. | Requiere configuración técnica, apps dispersas, sin monitoreo nativo. | ProtectX centraliza sensores + cámaras en una sola app con escalamiento automático de alertas. |
| **SimpliSafe** | Alarmas con autoservicio. | Instalación sencilla, app clara. | No disponible oficialmente en LATAM; sin coordinación comunitaria. | ProtectX es local-first, con comunidad y autoridades integradas en el flujo de respuesta. |
| **Aseguradoras con servicios de alarma** | Paquetes de seguro + monitoreo. | Credibilidad, soporte integral. | Planes caros, poco flexibles, sin comunidad. | ProtectX es más accesible, escalable y diseñado para Lima Metropolitana. |

**Resumen de ventaja competitiva de ProtectX**  
- **Localización en Lima/Perú**: rutas de alerta a serenazgo/PNP configuradas por distrito.  
- **Modelo IoT modular**: escalable por sensores y niveles de suscripción (hogar → edificio → comunidad).  
- **Colaboración comunitaria**: mapa de incidentes, chat vecinal, evidencia compartida en tiempo real.  
- **Accesibilidad**: auto-instalación, costos escalables, interfaz simple y multisegmento.  

---

### 2.1.2. Estrategias y tácticas frente a competidores

- **Posicionamiento**: “La seguridad inteligente y comunitaria de Lima: detección, evidencia y coordinación con vecinos y autoridades en una sola app”.  
- **Go-to-market**:  
  - Pilotos en distritos con alta incidencia delictiva.  
  - Alianzas con juntas vecinales, inmobiliarias y municipalidades.  
  - Testimonios y campañas digitales segmentadas por zona.  
- **Producto**:  
  - **Hogares**: botón de pánico, alertas inmediatas, 2–4 sensores básicos.  
  - **Juntas vecinales**: tablero comunitario, permisos por roles, reportes mensuales.  
  - **Autoridades locales**: mapas de calor, evidencias en un clic, comunicación directa.  
- **Educación y confianza**: protocolos de privacidad, cifrado de datos, SLA de notificaciones.  
- **Modelo de ingresos**:  
  - Suscripciones mensuales por niveles.  
  - Kits iniciales de sensores/cámaras.  
  - Servicios premium de monitoreo y soporte técnico.  

---

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmentos objetivo**

1. **Personas/familias que viven solas o con temor por la inseguridad (hogares).**  
2. **Juntas vecinales y administradores de edificios residenciales.**  
3. **Autoridades locales y serenazgo.**

**Preguntas por Segmento Objetivo**

**A. Hogares**  
1. ¿Qué incidentes de seguridad has experimentado en tu vivienda en los últimos 12 meses?  
2. ¿Qué métodos de seguridad utilizas actualmente y qué limitaciones encuentras en ellos?  
3. ¿Qué características te darían confianza para pagar por un sistema de seguridad inteligente?  
4. ¿Qué tipo de alertas en el celular considerarías más útiles en caso de emergencia?  
5. ¿Cuál sería un precio justo por un servicio que combine sensores, cámaras y alertas inmediatas?

**B. Juntas vecinales / Administradores**  
1. ¿Cómo se organizan actualmente ante incidentes en su comunidad?  
2. ¿Qué problemas tienen al coordinar con serenazgo o PNP?  
3. ¿Qué información necesitan en un tablero comunitario para decidir rápido?  
4. ¿Qué nivel de personalización requieren en permisos de acceso a cámaras o alertas?  
5. ¿Qué esquema de suscripción sería más viable: por unidad habitacional, por sensor común o por administración?

**C. Autoridades locales / Serenazgo**  
1. ¿Qué dificultades enfrentan hoy para responder a incidentes vecinales?  
2. ¿Qué tipo de información en tiempo real les facilitaría priorizar emergencias?  
3. ¿Cómo debería integrarse un sistema de seguridad comunitario con sus protocolos actuales?  
4. ¿Qué formato de evidencia (video, fotos, reportes automáticos) sería más útil para agilizar su respuesta?  
5. ¿Qué expectativas tendrían respecto a la colaboración ciudadana mediante apps como ProtectX?

---

### 2.2.2. Registro de entrevistas

| Entrevistado | Segmento | Fecha      | Video                                                                                                                            |
|--------------|----------|------------|----------------------------------------------------------------------------------------------------------------------------------|
| INT-001      | Hogar    | 08/09/2025 | [![Ver video](resources/Cap-1/SSInterview1)](https://drive.google.com/file/d/1ULhjDtqXoQH0KRz3L7NDmq6DvCik1M0b/view?usp=sharing) |
| INT-002      | Junta/Administrador | 16-09-2025 | [![Ver video](resources/Cap-2/Christian.jpg)](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211c036_upc_edu_pe/EeioWrabT_9Hl0h29N9C2bUBo3IXoQKWewVzcleUHOOlxA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=aVkcFt)                                                          |
| INT-003      | Autoridad/Serenazgo | AAAA-MM-DD | [![Ver video]()](https://drive.google.com)                                                                                       |

| … | … | … | … |

---

### 2.2.3. Análisis de entrevistas

- **Patrones comunes:** [Ej. necesidad de evidencias rápidas; coordinación débil; percepción de inseguridad alta].  
- **Diferencias por segmento:**  
  - **Hogares:** buscan sencillez, bajo costo y botón de pánico inmediato.  
  - **Juntas vecinales:** necesitan tableros comunitarios, permisos y reportes periódicos.  
  - **Autoridades:** demandan información en tiempo real, formatos estandarizados y mapas de incidentes.  
- **Conclusiones:** [Definir funcionalidades prioritarias del MVP hogar, comunidad y autoridad; validar supuestos de pago y confianza tecnológica].  

---



## 2.3. Needfinding
### 2.3.1. User Personas  

A continuación presentamos los user personas identificadas basándonos en las entrevistas realizadas para ambos segmentos objetivos. Estos user personas nos ayudarán a entender mejor las necesidades y expectativas de nuestros futuros usuarios.

Segmento 1: **Hogares**

<img src="resources/Cap-2/User-sebastian.png" alt="Entrevista 1" width="500">

Segmento 2: **Juntas vecinales**

<img src="resources/Cap-2/User-cristhian.png" alt="Entrevista 2" width="500">

### 2.3.2. User Task Matrix  
### 2.3.3. User Journey Mapping  

Segmento Objetivo 1: **Hogares**

<img src="./resources/Cap-2/Journey%20map-Sebastian.png" alt="Sebastian" height=500/>

Se puede evidenciar como es el proceso de selección de Sebastian al momento de elegir un sistema de seguridad para su hogar, 
por el momento se encuentra frustrado pues los sistemas de seguridad que tenía son obsoletos.

Segmento Objetivo 2: **Juntas vecinales**

<img src="./resources/Cap-2/Journey%20map-vecino.png" alt="Sebastian" height=500/>

Se puede ver como los vecinos sienten que las opciones que encuentran de sistemas de seguridad, 
no son 100% confiables y temen ser estafados.

### 2.3.4. Empathy Mapping  
 ### 2.3.5. As-is Scenario Mapping  

<img src="./resources/Cap-1/AsisCasa.png" alt="Asis casa">

<img src="./resources/Cap-1/AsisJunta.png" alt="Asis casa">

## 2.4. Ubiquitous Language  

Sensor IoT : Dispositivo conectado  que recopila datos de la vivienda y los transmite al sistema.

Suscriptor : Persona registrada que contrata un plan de suscripción.

Alerta Inmediata : Notificación en tiempo real enviada al usuario y a la entidad policial más cercana a través de una aplicación.

Cámara Inteligente: Dispositivo de video con detección avanzada que transmite imágenes en vivo a la app y respalda evidencias de seguridad.

Framework:Estructura de desarrollo que define buenas prácticas y provee herramientas para construir software escalable; en ProtectX se usa Spring Boot para el backend y Angular para el frontend.

Angular: Framework de desarrollo frontend en TypeScript usado para construir la aplicación ProtectX, ofreciendo modularidad mediante componentes y servicios.

IDE: Entorno de Desarrollo Integrado


# Capítulo III: Requirements Specification  

## 3.1. To-Be Scenario Mapping  

<img src="./resources/Cap-1/TobeCasa.png" alt="To-be Casa">

<img src="./resources/Cap-1/TobeJunta.png" alt="To-be Junta vecinal">

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

<img src="./resources/Cap-4/Domain_Driven_Software_architecture/Context_Diagram/ProtectX-SystemContext-001.png" alt="To-be Casa">

<img src="./resources/Cap-4/Domain_Driven_Software_architecture/Context_Diagram/ProtectX-SystemContext-001-key.png" alt="To-be Casa">

### 4.6.2. Software Architecture Container Diagrams 

<img src="./resources/Cap-4/Domain_Driven_Software_architecture/Container_Diagram/ProtectX-Container-001.png" alt="To-be Casa">

<img src="./resources/Cap-4/Domain_Driven_Software_architecture/Container_Diagram/ProtectX-Container-001-key.png" alt="To-be Casa">

### 4.6.3. Software Architecture Components Diagrams  

<img src="./resources/Cap-4/Domain_Driven_Software_architecture/Component_Diagram/ProtectX-Component-001.png" alt="To-be Casa">

<img src="./resources/Cap-4/Domain_Driven_Software_architecture/Component_Diagram/ProtectX-Component-001-key.png" alt="To-be Casa">

---
## 4.7. Software Object-Oriented Design  
### 4.7.1. Class Diagrams

<img src="./resources/Cap-4/Class_Diagram/ProtectX-ClassDiagram.png">

### 4.7.2. Class Dictionary 

### 4.7.2. Class Dictionary  

| Clase                  | Propósito                              | Atributos                                   | Métodos                                                                 |
|-------------------------|----------------------------------------|---------------------------------------------|-------------------------------------------------------------------------|
| Usuario                 | Representa a la persona del sistema    | `datosUsuario`                              | `getDatos()`                                                            |
| Credencial              | Maneja datos de acceso y seguridad     | `user`, `pass`, `token`                     | `encrypt()`, `get()`, `set()`                                          |
| Sesion                  | Gestiona la sesión activa del usuario  | `credencial`, `controladores`, `notificaciones` | `showUserData()`, `showSensor()`, `updateNotification()`, `updateData()`, `triggerEvent()`, `setAlarm()` |
| Sensor                  | Representa un dispositivo de medición | `type`, `name`, `data`, `time`, `position`  | `read()`, `readings()`                                                 |
| ControladorSensor       | Administra múltiples sensores          | `sensor[array]`                             | `new()`, `delete()`, `show()`, `update()`                              |
| Alarma                  | Representa un dispositivo de alerta    | `type`, `name`, `data`, `time`, `position`  | `read()`, `readings()`                                                 |
| ControladorAlarma       | Administra múltiples alarmas           | `alarma[array]`                             | `new()`, `delete()`, `show()`, `update()`                              |
| Notificacion            | Maneja mensajes del sistema            | `mensaje`, `time`                           | `read()`, `getTime()`                                                  |
| ControladorNotificacion | Administra notificaciones en cola      | `notif[cola]`                               | `new()`, `delete()`, `show()`, `update()`                              |
| Evento                  | Representa sucesos del sistema         | `descripcion`, `dato`, `time`               | `makeMessage()`, `getDato()`, `getTime()`                              |
| ControladorEvento       | Administra eventos en pila (stack)     | `evento[stack]`                             | `new()`, `delete()`, `show()`, `update()`, `email()`, `callPolice()`, `firefighters()` |



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
