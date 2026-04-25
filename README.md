<div align="center">

![Logo Banner](assets/Banner-UPC.png)

### Universidad Peruana de Ciencias Aplicadas  
### Ingeniería de Software  
### 2026-1  

### NRC: 11834  
### Docente: Ivan Robles Fernandez
### Informe de Trabajo Final  

### SoftTech  
### SafeHome  

| **Código** | **Integrante** |
|------------|----------------|
| U20241D932 | Briguite Eryka Carhuaz Centeno |
| U202319329 | Gonzalo Alexander Jaime Forcelledo |
| U201911393 | Mauricio Jared Padilla Merino |
| U202115654 | Luis Ángel Pililaca Vidal |
| U202411373 | Valeria Alexandra Rojas Gómez |

### Abril 2026

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| 1.0 | 08/04/2026 | Grupo SoftTech | Se avanzaron los capítulos correspondientes al AV1 del proyecto SafeHome. |

---

# Project Report Collaboration Insights

**URL del Repositorio:** [SafeHome Project Report](https://github.com/upc-pre-2610-1ASI0729-11834-SoftTech/SafeHome-report)

El informe del proyecto SafeHome fue desarrollado de manera colaborativa por el equipo SoftTech mediante GitHub. Para organizar el trabajo, se utilizó una rama principal `main`, una rama de integración `develop` y ramas `feature/chapter-*` para distribuir el desarrollo del reporte por capítulos.

Cada integrante trabajó en la rama correspondiente a su capítulo o sección asignada, realizando commits con mensajes descriptivos bajo la convención de Conventional Commits. Esta organización permitió mantener la trazabilidad de los cambios, evidenciar la participación del equipo y facilitar la integración progresiva del informe.

---

# Student Outcome ABET 3

**Capacidad de comunicarse efectivamente con un rango de audiencias.**

| Criterio específico | Descripción | Acciones realizadas | Conclusiones |
|--------------------|-------------|---------------------|--------------|
| 3.c1. Comunica oralmente con efectividad a diferentes rangos de audiencia | El estudiante comunica resultados y proceso de ingeniería aplicado para el ciclo de desarrollo y despliegue de una solución web distribuida bajo una arquitectura orientada a servicios, con enfoque innovador e inclusivo. | AV1: El equipo explicó los avances del proyecto SafeHome, incluyendo la problemática, análisis de usuarios, diseño UX/UI, propuesta técnica e implementación inicial. | El equipo logró comunicar oralmente los principales resultados del avance, sustentando las decisiones tomadas en el diseño y desarrollo de la solución. |
| 3.c2. Comunica por escrito con efectividad a diferentes rangos de audiencia | El estudiante comunica por escrito los resultados y el proceso de ingeniería aplicado en el desarrollo de una solución web distribuida. | AV1: El equipo documentó el informe en formato Markdown, registrando evidencias, decisiones de diseño, requisitos, diagramas, arquitectura y avances de implementación. | La documentación permitió comunicar de manera ordenada el proceso de desarrollo del proyecto SafeHome. |

---

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome ABET 3](#student-outcome-abet-3)

- [Capítulo I: Introducción](#capítulo-i-introducción)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)

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
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Capítulo I: Introducción

## 1.1. Startup Profile

Contenido del capítulo I.

### 1.1.1. Descripción de la Startup

Contenido de la sección.

### 1.1.2. Perfiles de integrantes del equipo

Contenido de la sección.

## 1.2. Solution Profile

Contenido de la sección.

### 1.2.1. Antecedentes y problemática

Contenido de la sección.

### 1.2.2. Lean UX Process

Contenido de la sección.

#### 1.2.2.1. Lean UX Problem Statements

Contenido de la sección.

#### 1.2.2.2. Lean UX Assumptions

Contenido de la sección.

#### 1.2.2.3. Lean UX Hypothesis Statements

Contenido de la sección.

#### 1.2.2.4. Lean UX Canvas

Contenido de la sección.

## 1.3. Segmentos objetivo

Contenido de la sección.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En el mercado peruano de sistemas de seguridad para el hogar existe una amplia oferta de soluciones. Sin embargo, la mayoría de estas empresas se concentran principalmente en la videovigilancia y monitoreo perimetral externo, dejando en un segundo plano el monitoreo de anomalías internas, tales como fugas de gas, agua o consumo eléctrico inusual.

Si bien algunas empresas locales y con presencia internacional en el Perú ofrecen soluciones de seguridad, en el mercado internacional se encuentran propuestas más integrales que abordan la seguridad del hogar tanto de forma externa como interna. Estas empresas internacionales, a diferencia de las nacionales, implementan sensores IoT avanzados para la detección de fugas, monitoreo energético y alertas en tiempo real, todo ello integrado en una misma plataforma.

### 2.1.1. Análisis competitivo

| Categoría                     | SafeHome                                                                 | Prosegur Alarmas                                             | Verisure                                                      | Ring (Amazon)                                                 | Vivint Smart Home                                             |
|------------------------------|--------------------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------|
| **Overview**                 | Startup tecnológica enfocada en seguridad del hogar con IoT y analítica | Empresa consolidada en seguridad física en LATAM              | Empresa internacional de alarmas inteligentes                  | Marca de dispositivos inteligentes DIY                        | Empresa de seguridad y automatización del hogar               |
| **Ventaja Competitiva**      | Bajo costo, plataforma centralizada, integración IoT flexible, UX simple | Marca reconocida, monitoreo 24/7, instalación incluida        | Tecnología avanzada, respuesta rápida                          | Integración con ecosistema Amazon, fácil instalación          | Ecosistema integrado, automatización avanzada                 |
| **Mercado Objetivo**         | Familias urbanas, jóvenes profesionales, domótica accesible              | Hogares NSE medio-alto, empresas                              | Hogares premium, negocios                                     | Usuarios tecnológicos, mercado global                         | Hogares premium, mercado tecnológico                          |
| **Estrategias de Marketing** | Marketing digital, modelo freemium, alianzas IoT                         | Publicidad tradicional, ventas directas                       | Marketing agresivo, venta consultiva                          | E-commerce, marketing digital                                | Marketing digital y ventas integradas                         |
| **Productos & Servicios**    | Monitoreo en tiempo real, alertas, sensores IoT, dashboard web           | Alarmas, cámaras, monitoreo profesional                       | Cámaras inteligentes, sensores                               | Seguridad inteligente, dispositivos DIY                       | Automatización del hogar, seguridad inteligente               |
| **Precios & Costos**         | Freemium + suscripción accesible                                         | Costos elevados + mensualidad                                | Alto costo + suscripción                                      | Pago único + suscripción opcional                            | Alto costo + suscripción                                     |
| **Canales de Distribución**  | Web + app móvil                                                          | Web + ventas presenciales                                     | Web + ventas directas                                         | Online (Amazon)                                              | Web + ventas directas                                         |
| **Fortalezas**               | Alta accesibilidad económica, flexibilidad tecnológica, UX moderna       | Alta confianza de marca, soporte profesional                  | Tecnología robusta, reconocimiento global                     | Fácil uso, ecosistema integrado                              | Automatización avanzada                                       |
| **Debilidades**              | Baja reputación inicial, dependencia tecnológica del usuario             | Poca flexibilidad, costos altos                              | Alto precio, instalación requerida                            | Soporte limitado en Perú                                     | Dependencia de internet                                       |
| **Oportunidades**            | Crecimiento del IoT, baja penetración de soluciones integradas           | Digitalización de servicios                                  | Expansión en LATAM                                            | Crecimiento del smart home                                   | Expansión tecnológica                                         |
| **Amenazas**                 | Competidores consolidados, desconfianza en nuevas soluciones             | Nuevas soluciones más económicas                             | Competencia global                                            | Soluciones DIY más económicas                                | Alternativas locales más económicas                          |
## 2.1.2. Estrategias y tácticas frente a competidores

Según el análisis realizado, SafeHome identifica varias oportunidades para diferenciarse 
en un mercado donde la mayoría de las soluciones se concentran en la seguridad perimetral 
externa y videovigilancia. Mientras que los competidores locales como Prosegur Alarmas y 
Verisure destacan por su monitoreo profesional 24/7 y respuesta rápida, y las soluciones 
internacionales como Ring y Vivint se centran principalmente en video y alarmas, SafeHome 
propone una estrategia centrada en el monitoreo integral (externo e interno) y una mayor 
accesibilidad.

Las principales estrategias y tácticas que se adoptarán son las siguientes:

---

### 1. Diferenciación por valor agregado en monitoreo interno

A diferencia de la mayoría de competidores que ofrecen un enfoque limitado en la detección 
de anomalías internas, SafeHome integrará sensores IoT especializados para detectar fugas 
de gas, agua y consumos eléctricos inusuales. Esta funcionalidad responde directamente a 
las necesidades identificadas en las entrevistas realizadas a los segmentos objetivo, donde 
los usuarios expresaron preocupación por riesgos domésticos internos además de las 
intrusiones externas.

---

### 2. Accesibilidad y modelo de negocio flexible

Mientras que Prosegur, Verisure y Vivint suelen requerir contratos a largo plazo y cuotas 
mensuales elevadas, SafeHome implementará un modelo de suscripción más accesible y flexible 
(freemium), orientado especialmente a jóvenes adultos independientes y familias de ingresos 
medios que viven en departamentos. De esta forma se busca reducir la barrera de entrada que 
actualmente existe en el mercado.

---

### 3. Enfoque en plataforma web responsive como canal principal

La mayoría de competidores priorizan aplicaciones móviles o sistemas cerrados con central 
receptora. SafeHome desarrollará una plataforma web responsive como interfaz principal, 
permitiendo un acceso más cómodo desde cualquier dispositivo (computadora, tablet o celular) 
sin necesidad de instalar aplicaciones adicionales. Esto mejora la experiencia de usuario y 
facilita el monitoreo para aquellos que prefieren interfaces web.

---

### 4. Fácil instalación y enfoque DIY *(Do It Yourself)*

Se priorizará un diseño de sensores plug-and-play con configuración intuitiva a través de 
la plataforma web, reduciendo la dependencia de instalación profesional costosa que exigen 
la mayoría de competidores locales.

---

### 5. Estrategia de posicionamiento inicial

SafeHome se posicionará inicialmente en el segmento de jóvenes adultos independientes y 
familias urbanas en Lima Metropolitana, ofreciendo una solución más económica y tecnológica 
que combine seguridad externa con monitoreo inteligente interno, cerrando la brecha 
identificada en el mercado peruano.

---

Estas estrategias permitirán a SafeHome no solo competir, sino también crear un nicho propio 
en el mercado de seguridad doméstica inteligente, enfocándose en la seguridad integral 
accesible y en la tranquilidad real de los usuarios.

## 2.2. Entrevistas

Contenido de la sección.

## 2.2.1. Diseño de entrevistas

### Segmento 1: Jóvenes adultos independientes

1. ¿Podrías indicarnos tu edad, en qué distrito resides y con quién compartes tu departamento actualmente?
2. ¿Qué dispositivos o aplicaciones tecnológicas utilizas diariamente para organizar tu rutina, tus finanzas o el manejo de tu hogar?
3. Cuando dejas tu departamento solo para ir a estudiar o trabajar, ¿qué es lo que más te preocupa respecto a la seguridad de tus pertenencias?
4. ¿Has tenido alguna experiencia directa o cercana de robo o intento de intrusión en tu vivienda? ¿Cómo procediste?
5. Más allá de los robos, ¿alguna vez te ha generado estrés dudar si dejaste conectado algún electrodoméstico o el agua corriendo al salir de casa?
6. Si pudieras monitorear el estado de tu departamento en tiempo real desde tu celular, ¿qué alertas o notificaciones considerarías absolutamente necesarias?
7. ¿Estarías dispuesto a instalar sensores IoT (como detectores de movimiento, humo o gas) por tu cuenta si la configuración desde la app fuera intuitiva y sin cables?
8. Para ti, ¿qué funcionalidad diferenciaría a una aplicación de seguridad básica de una que consideramos imprescindible de revisar todos los días?
9. ¿Cuánto estarías dispuesto a invertir mensualmente por una suscripción que te garantice el monitoreo remoto de tu hogar y alertas inmediatas ante cualquier anomalía?
10. ¿Conoces a otros jóvenes independientes que compartan estas mismas preocupaciones y a quienes les sería útil una plataforma automatizada como esta?

---

### Segmento 2: Familias urbanas

1. ¿Podría indicarnos su edad, el distrito donde reside y cuántas personas conforman su núcleo familiar, incluyendo niños o adultos mayores?
2. Actualmente, ¿cuenta con algún sistema o medida de seguridad en su hogar (cámaras, alarmas, vigilancia vecinal)? ¿Qué tan efectivo le resulta en el día a día?
3. En el contexto actual, ¿cuál considera que es la principal vulnerabilidad de su vivienda frente a la inseguridad en la ciudad?
4. Además de la amenaza externa, ¿qué tan preocupante es para usted el riesgo de incidentes domésticos graves como fugas de gas, cortocircuitos o inundaciones?
5. ¿Alguna vez su familia ha enfrentado una emergencia dentro de casa que no fue detectada a tiempo? ¿Cuáles fueron las consecuencias materiales o emocionales?
6. Nuestro proyecto busca alertar sobre estas anomalías de forma inteligente. ¿Qué valor le daría a un sistema que envíe notificaciones inmediatas a su celular y al de su pareja simultáneamente ante un peligro?
7. En caso de una emergencia real detectada por los sensores (como una intrusión o incendio), ¿preferiría que el sistema alerte automáticamente a las autoridades o prefiere verificar la notificación usted primero?
8. ¿Qué características específicas tendría que cumplir un sistema de monitoreo para que usted confíe plenamente en él para proteger el bienestar de su familia?
9. Si esta tecnología le permitiera prevenir accidentes muy costosos, ¿consideraría pagar un servicio de monitoreo Premium mensual? ¿Qué rango de precio le parecería manejable?
10. ¿Considera que el uso de sensores ambientales (movimiento, humo, gas) es una opción más cómoda y menos invasiva para la privacidad de su familia en comparación con instalar cámaras en todos los cuartos?

---

### Segmento 3: Propietarios de inmuebles en alquiler

1. ¿Podría indicarnos su edad, en qué distritos se ubican sus propiedades y cuántos inmuebles tiene actualmente destinados al alquiler?
2. ¿Cuál es el proceso o método que utiliza hoy en día para verificar el buen estado de mantenimiento y seguridad de sus propiedades alquiladas?
3. En su experiencia como arrendador, ¿cuáles han been los problemas más graves o costosos ocasionados por descuidos de los inquilinos (ej. mal uso de agua, gas, o instalaciones eléctricas)?
4. ¿Alguna vez la negligencia de un inquilino ha dejado su propiedad expuesta a robos, incendios o daños estructurales severos? ¿Cómo se enteró de lo sucedido?
5. ¿Qué tan complejo le resulta asegurarse de que su inversión inmobiliaria está protegida sin generar conflictos o invadir la privacidad de las personas que viven allí?
6. Si existiera un sistema basado en sensores IoT que le envíe alertas al celular solo ante incidentes críticos (fugas de agua, gas o picos inusuales de consumo) sin usar cámaras de video, ¿lo implementaría?
7. ¿Cree que ofrecer un departamento pre-equipado con tecnología inteligente y prevención de desastres le permitiría atraer a mejores inquilinos o justificar un mayor costo de alquiler?
8. Pensando en la gestión de varias propiedades a la vez, ¿le resultaría útil una plataforma web donde pueda ver un panel (dashboard) con el estado de los servicios y sensores de todos sus inmuebles en tiempo real?
9. A nivel económico, ¿preferiría que los equipos de sensores requieran un pago único inicial por la instalación, o un modelo de suscripción mensual que incluya mantenimiento y soporte técnico continuo?
10. ¿Qué otra funcionalidad le pediría a una plataforma de monitoreo de inmuebles para que realmente le reduzca el estrés y los costos imprevistos como propietario?

## 2.2.2. Registro de entrevistas

**Link del video de las entrevistas:** `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4`

---

### Segmento objetivo 1: Jóvenes adultos independientes

---

**Entrevista 1**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Heber Eduardo Jaime Amoretti |
| **Edad** | 30 años |
| **Distrito** | Santiago de Surco |
| **Inicio** | 0:00 |
| **Duración** | 3:26 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Jóvenes profesionales o estudiantes que viven solos o comparten departamento y pasan gran 
parte del día fuera de casa. Utilizan tecnología móvil constantemente y buscan soluciones 
simples que les permitan monitorear su hogar, reducir preocupaciones y mantener control 
remoto sobre la seguridad y los servicios domésticos.

**Resumen de la entrevista:**
La entrevista comienza con Heber Jaime Amoretti, un hombre de 30 años que reside en el 
distrito de Surco y comparte su departamento con otros estudiantes. Heber menciona que, por 
el momento, no utiliza dispositivos o aplicaciones tecnológicas específicas para la 
organización de sus finanzas o el manejo de su hogar, lo que lo sitúa como un usuario con 
gran potencial para adoptar nuevas herramientas digitales de seguridad.

En cuanto a sus preocupaciones, Heber destaca el miedo al robo de sus pertenencias cuando 
deja el departamento solo para ir a trabajar o estudiar. Su mayor inquietud radica en la 
imposibilidad de observar lo que sucede en tiempo real e identificar a posibles intrusos. 
Además, admite que situaciones cotidianas como dudar si dejó conectado un electrodoméstico 
o los servicios abiertos (agua o gas) le generan un estrés considerable, llegando incluso a 
sentir el impulso de regresar a casa para verificarlo.

Sobre la propuesta de SafeHome, Heber considera indispensable recibir alertas de todo tipo, 
desde la apertura de puertas hasta el estado de sus servicios básicos. Se muestra dispuesto 
a instalar sensores IoT (humo, gas o movimiento) de forma autónoma siempre que el sistema 
sea cómodo e intuitivo. Finalmente, aunque no tiene un presupuesto definido, espera que la 
suscripción sea económica y accesible, sugiriendo que la plataforma sería ideal para otros 
jóvenes que vivan solos y compartan estas mismas necesidades de control remoto.

---

**Entrevista 2**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Abraham Coronado |
| **Edad** | 20 años |
| **Distrito** | Pueblo Libre |
| **Inicio** | 3:26 |
| **Duración** | 4:02 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Jóvenes profesionales o estudiantes que viven solos o comparten departamento y pasan gran 
parte del día fuera de casa. Utilizan tecnología móvil constantemente y buscan soluciones 
simples que les permitan monitorear su hogar, reducir preocupaciones y mantener control 
remoto sobre la seguridad y los servicios domésticos.

**Resumen de la entrevista:**
La entrevista se desarrolla con Abraham Coronado, un joven de 20 años que reside en el 
distrito de Pueblo Libre y vive solo en su departamento. Abraham comenta que utiliza 
herramientas tecnológicas básicas para la organización de sus finanzas personales, 
principalmente hojas de cálculo en Excel y aplicaciones móviles para registrar sus gastos 
diarios, aunque no emplea actualmente soluciones tecnológicas específicas orientadas a la 
seguridad o automatización del hogar.

Respecto a sus preocupaciones, menciona que, aunque no ha experimentado situaciones directas 
de robo o intrusión, sí existe un temor latente ante la posibilidad de que alguien ingrese a 
su vivienda cuando se encuentra fuera. Asimismo, reconoce que situaciones cotidianas como 
dudar si dejó encendida la luz o algún electrodoméstico conectado le generan inquietud, 
evidenciando la necesidad de contar con mecanismos de verificación remota que le brinden 
mayor tranquilidad.

En relación con la propuesta de SafeHome, Abraham considera fundamental recibir alertas 
relacionadas con el consumo eléctrico y la detección de dispositivos conectados dentro del 
hogar. Se muestra interesado en instalar sensores IoT, siempre que la configuración sea 
sencilla, intuitiva y sin complicaciones técnicas. Destaca además que una aplicación de 
seguridad debe diferenciarse por su facilidad de uso y por permitir el control remoto 
integral del hogar desde el celular. Aunque no tiene definido un presupuesto mensual 
específico, afirma que estaría dispuesto a pagar por un servicio que garantice monitoreo 
constante y notificaciones inmediatas. Finalmente, señala que varios jóvenes de su entorno 
viven solos y comparten preocupaciones similares, por lo que considera que una plataforma 
automatizada como SafeHome tendría alta aceptación dentro de este segmento.

---

**Entrevista 3**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Elena Milagros Gómez Luque |
| **Edad** | 47 años |
| **Distrito** | Jesús María |
| **Inicio** | 7:30 |
| **Duración** | 5:50 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Jóvenes profesionales o estudiantes que viven solos o comparten departamento y pasan gran 
parte del día fuera de casa. Utilizan tecnología móvil constantemente y buscan soluciones 
simples que les permitan monitorear su hogar, reducir preocupaciones y mantener control 
remoto sobre la seguridad y los servicios domésticos.

**Resumen de la entrevista:**
La entrevista se realiza con Elena, una mujer de 47 años que reside en el distrito de Jesús 
María y vive junto a tres integrantes de su familia en un departamento. Actualmente, comenta 
que no cuenta con un sistema de seguridad dentro de su vivienda, aunque el edificio dispone 
de vigilancia permanente y cámaras de seguridad, lo cual le brinda una sensación general de 
protección en el día a día.

En relación con sus preocupaciones, identifica como principal vulnerabilidad la posibilidad 
de robos o accesos no autorizados al edificio o a los departamentos. Si bien considera bajo 
el riesgo de incidentes domésticos graves, reconoce que situaciones como incendios o 
cortocircuitos podrían representar una amenaza. Además, menciona que en su edificio se han 
presentado emergencias previas, como incendios e inundaciones ocasionadas por descuidos de 
otros residentes, lo que evidencia la importancia de contar con sistemas de alerta temprana.

Respecto a la propuesta de SafeHome, Elena otorga un alto valor a un sistema que envíe 
notificaciones inmediatas al celular tanto de ella como de su pareja, especialmente 
considerando que el hogar permanece solo durante varias horas del día. Señala que preferiría 
un sistema capaz de alertar simultáneamente al usuario y a las autoridades ante una 
emergencia, permitiendo una respuesta más rápida. Asimismo, destaca que la confianza en la 
tecnología dependería principalmente de la seguridad contra posibles hackeos y de la 
facilidad de uso del aplicativo.

En cuanto al modelo de suscripción, considera razonable invertir mensualmente entre 30 y 50 
soles si el sistema garantiza prevención de riesgos y protección familiar. Finalmente, indica 
que los sensores ambientales representan una alternativa menos invasiva para la privacidad 
del hogar, aunque reconoce que pueden complementarse con cámaras de seguridad para lograr 
una protección más integral.

---

### Segmento objetivo 2: Familias urbanas

---

**Entrevista 4**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Angie Alexandra Guardo Caiz |
| **Edad** | 21 años |
| **Distrito** | Santa Anita |
| **Inicio** | 13:20 |
| **Duración** | 3:18 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Integrantes de familias que residen en zonas urbanas con rutinas laborales y escolares 
activas. Priorizan la seguridad del hogar y la protección familiar, valorando herramientas 
tecnológicas fáciles de usar que permitan supervisar la vivienda y prevenir incidentes 
mientras no se encuentran en casa.

**Resumen de la entrevista:**
La entrevista se realiza con Angie Alexandra Guardo Caiz, una joven de 21 años que reside 
en el distrito de Santa Anita y vive junto a sus padres, su hermano, su abuelo y sus 
mascotas. En cuanto al uso de tecnología, comenta que emplea aplicaciones bancarias y hojas 
de cálculo en Excel para la gestión de sus finanzas personales, aunque actualmente no utiliza 
herramientas tecnológicas específicas destinadas a la seguridad o monitoreo del hogar.

Respecto a sus preocupaciones, señala que su principal inquietud al dejar la vivienda sola 
es la posibilidad de que personas desconocidas ingresen al hogar, así como la seguridad de 
sus mascotas y pertenencias personales. Además, menciona que le genera estrés la idea de 
haber dejado algún artefacto eléctrico conectado que pueda representar un riesgo, 
especialmente considerando la presencia de animales domésticos dentro de la vivienda.

En relación con la propuesta de SafeHome, considera fundamental contar con alertas 
relacionadas al ingreso de personas mediante reconocimiento facial, permitiendo identificar 
si quienes acceden al hogar están autorizados. Asimismo, se muestra dispuesta a instalar 
sensores IoT siempre que la configuración sea sencilla, intuitiva y sin cables. Destaca que 
una aplicación de seguridad imprescindible debería permitir verificar el estado de los 
dispositivos eléctricos del hogar y ofrecer control remoto constante desde el celular.

En cuanto al aspecto económico, indica que su disposición de pago dependería de las 
funcionalidades incluidas en el plan, especialmente aquellas vinculadas al reconocimiento 
facial y la detección de artefactos conectados. Finalmente, señala que varios compañeros de 
su entorno universitario comparten preocupaciones similares, por lo que considera que una 
plataforma automatizada como SafeHome tendría aceptación entre jóvenes de su generación.

---

**Entrevista 5**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Nicol Quispe |
| **Edad** | 18 años |
| **Distrito** | Callao |
| **Inicio** | 16:40 |
| **Duración** | 5:49 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Integrantes de familias que residen en zonas urbanas con rutinas laborales y escolares 
activas. Priorizan la seguridad del hogar y la protección familiar, valorando herramientas 
tecnológicas fáciles de usar que permitan supervisar la vivienda y prevenir incidentes 
mientras no se encuentran en casa.

**Resumen de la entrevista:**
La entrevista se realiza a una joven de 18 años que reside en la Provincia Constitucional 
del Callao y vive junto a sus padres y dos hermanos, conformando un hogar de cinco 
integrantes. Actualmente, menciona que su vivienda cuenta con medidas básicas de seguridad, 
como cámaras ubicadas en la entrada y un sistema de alarma simple. Sin embargo, considera 
que estas soluciones no resultan completamente suficientes cuando la casa permanece sola, 
identificando como principal vulnerabilidad el posible ingreso de personas desconocidas.

En relación con los riesgos domésticos, señala una alta preocupación por incidentes internos 
como fugas de gas o cortocircuitos, debido a que pueden ocurrir sin ser detectados 
oportunamente. De hecho, comenta que su familia experimentó anteriormente un cortocircuito 
en la cocina que no fue advertido a tiempo, generando estrés familiar y la necesidad de 
realizar reparaciones eléctricas para evitar futuros incidentes.

Respecto a la propuesta de SafeHome, considera que un sistema capaz de enviar notificaciones 
inmediatas al celular tendría un valor muy alto, ya que permitiría reaccionar rápidamente 
ante emergencias incluso cuando los integrantes del hogar se encuentren fuera. Prefiere que 
las alertas lleguen primero al usuario para verificar la situación antes de contactar 
automáticamente a las autoridades. Asimismo, destaca que la confianza en el sistema 
dependería de su fiabilidad, facilidad de uso, alertas en tiempo real y una instalación 
sencilla.

En cuanto al modelo de suscripción, indica que estaría dispuesta a pagar entre 30 y 60 soles 
mensuales si la tecnología contribuye efectivamente a prevenir accidentes y proteger a su 
familia. Finalmente, considera que el uso de sensores ambientales representa una alternativa 
más cómoda y menos invasiva que instalar cámaras en todos los espacios del hogar, permitiendo 
mantener la privacidad familiar sin perder seguridad.

---

**Entrevista 6**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Claudia Angelina Rios Rios |
| **Edad** | 22 años |
| **Distrito** | Comas |
| **Inicio** | 22:29 |
| **Duración** | 10:00 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Integrantes de familias que residen en zonas urbanas con rutinas laborales y escolares 
activas. Priorizan la seguridad del hogar y la protección familiar, valorando herramientas 
tecnológicas fáciles de usar que permitan supervisar la vivienda y prevenir incidentes 
mientras no se encuentran en casa.

**Resumen de la entrevista:**
La entrevista se realiza con Claudia Angelina, una joven de 22 años que reside en el distrito 
de Comas y vive junto a dos integrantes más de su familia. Actualmente, su hogar no cuenta 
con un sistema formal de seguridad, utilizando únicamente un grupo vecinal de WhatsApp como 
medio de comunicación ante incidentes. Si bien considera que esta medida resulta útil para 
compartir información después de algún evento, reconoce que no permite una reacción inmediata 
frente a situaciones de riesgo.

En relación con la seguridad del hogar, identifica como principal vulnerabilidad el momento 
en que la vivienda queda sola debido a las actividades laborales o académicas de los 
integrantes de la familia. Señala que esta situación incrementa la preocupación tanto por la 
pérdida de bienes materiales como por la seguridad personal en caso de que alguien permanezca 
solo en casa.

Asimismo, manifiesta una alta preocupación por incidentes domésticos como fugas de gas o 
cortocircuitos, debido a que suelen ocurrir de manera silenciosa y pueden afectar no solo a 
la familia, sino también a los vecinos cercanos. Relata que su hogar experimentó previamente 
una fuga de gas detectada varias horas después, lo que generó estrés, gastos económicos y la 
necesidad de realizar reparaciones, reforzando la importancia de contar con alertas tempranas.

Respecto a la propuesta de SafeHome, considera que un sistema capaz de enviar notificaciones 
inmediatas al celular tendría un valor significativo, ya que permitiría reaccionar rápidamente 
y reducir la ansiedad asociada a posibles emergencias. Prefiere recibir primero la notificación 
para verificar la situación y evitar falsas alarmas, aunque considera positivo que el sistema 
pueda escalar automáticamente el aviso a las autoridades si no existe respuesta del usuario.

Entre las características esenciales del sistema, destaca la confiabilidad, facilidad de uso, 
alertas claras y precisas, así como una configuración sencilla que pueda ser utilizada por 
todos los miembros del hogar, incluidos adultos mayores. Indica además que estaría dispuesta 
a pagar entre 30 y 60 soles mensuales por un servicio de monitoreo que prevenga accidentes 
y brinde tranquilidad familiar. Finalmente, considera que los sensores ambientales representan 
una alternativa más cómoda y menos invasiva que las cámaras internas, ya que permiten mantener 
el equilibrio entre seguridad y privacidad dentro del hogar.

---

### Segmento objetivo 3: Propietarios de inmuebles en alquiler

---

**Entrevista 7**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Cristina Reyes Merino |
| **Edad** | 32 años |
| **Distrito** | Surco, Magdalena |
| **Inicio** | 32:30 |
| **Duración** | 8:49 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Propietarios que gestionan viviendas en alquiler y requieren supervisión remota sin presencia 
constante. Buscan soluciones tecnológicas que faciliten el control de accesos, la prevención 
de daños y la administración eficiente de sus propiedades.

**Resumen de la entrevista:**
La entrevista se realizó con Cristina Reyes, de 32 años, propietaria de dos inmuebles 
destinados al alquiler ubicados en los distritos de Surco y Magdalena del Mar. Su incursión 
en el sector inmobiliario inició como una estrategia para generar ingresos adicionales y 
asegurar estabilidad financiera a largo plazo.

Actualmente, el monitoreo del estado de sus propiedades se basa principalmente en visitas 
presenciales periódicas. Sin embargo, este proceso presenta limitaciones, ya que coordinar 
horarios con los inquilinos resulta complicado y visitas frecuentes pueden generar incomodidad 
o sensación de invasión de privacidad. Esta situación evidencia la necesidad de contar con 
mecanismos de supervisión remota que no interfieran con la convivencia entre propietario e 
inquilino.

Durante su experiencia como arrendadora, ha enfrentado incidentes derivados del descuido de 
inquilinos, como filtraciones de agua que afectaron a vecinos colindantes y daños menores en 
electrodomésticos por uso inadecuado. Asimismo, menciona un caso en el que un inquilino dejó 
una ventana abierta durante un viaje, exponiendo la propiedad a posibles robos, situación que 
pudo resolverse a tiempo gracias al aviso del personal de mantenimiento.

La entrevistada considera complejo proteger su inversión inmobiliaria sin afectar la privacidad 
de los arrendatarios, por lo que valora positivamente la implementación de sistemas basados en 
sensores que detecten únicamente situaciones críticas sin recurrir al uso de cámaras internas. 
Indica que ofrecer propiedades equipadas con tecnología preventiva podría justificar un 
incremento en el costo del alquiler. Destaca también la importancia de contar con una 
plataforma centralizada con dashboard web que permita visualizar el estado de múltiples 
propiedades en tiempo real, reduciendo desplazamientos y optimizando la gestión inmobiliaria.

En cuanto al modelo de pago, considera más accesible un esquema de suscripción mensual que 
incluya mantenimiento continuo. Finalmente, propone funcionalidades adicionales como alertas 
ante incendios o inundaciones, registro histórico de incidentes y recomendaciones de 
mantenimiento preventivo, con el objetivo de anticipar riesgos futuros y proteger mejor sus 
activos inmobiliarios.

---

**Entrevista 8**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Saúl Romani Romani |
| **Edad** | 48 años |
| **Distrito** | Lince |
| **Inicio** | 41:18 |
| **Duración** | 5:05 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Propietarios que gestionan viviendas en alquiler y requieren supervisión remota sin presencia 
constante. Buscan soluciones tecnológicas que faciliten el control de accesos, la prevención 
de daños y la administración eficiente de sus propiedades.

**Resumen de la entrevista:**
La entrevista se realizó con Saúl Romani, de 48 años, propietario de un departamento 
destinado al alquiler ubicado en el distrito de Lince. Su principal interés como arrendador 
es mantener el buen estado de la propiedad y proteger su inversión inmobiliaria durante los 
periodos de alquiler.

Actualmente, el método que utiliza para verificar la seguridad y mantenimiento del inmueble 
consiste en visitas presenciales ocasionales, generalmente una o dos veces durante contratos 
anuales de arrendamiento. Sin embargo, reconoce que este sistema resulta limitado, ya que no 
permite detectar problemas en tiempo real ni prevenir incidentes antes de que generen daños 
mayores.

Según su experiencia, los problemas más frecuentes y costosos están relacionados con el 
deterioro de pisos, paredes, puertas y muebles ocasionados por el uso inadecuado de los 
inquilinos. Mencionó también un caso específico en el que el descuido en el cuidado de 
mascotas provocó daños significativos en los pisos del departamento, evidenciando la 
dificultad de supervisar el estado del inmueble sin invadir la privacidad del residente.

El entrevistado manifestó interés en la implementación de sistemas basados en sensores IoT 
que envíen alertas al celular ante eventos relevantes como fugas de gas, movimientos inusuales 
o anomalías en los servicios, destacando que sería importante que tanto propietario como 
inquilino puedan recibir dichas notificaciones. Considera que ofrecer un departamento equipado 
con tecnología inteligente podría resultar atractivo para los inquilinos y justificar un mayor 
costo de alquiler. También señaló que una plataforma web con dashboard centralizado sería 
especialmente útil para propietarios con más de un inmueble.

Finalmente, expresó preferencia por un sistema de suscripción mensual que incluya 
mantenimiento y soporte técnico continuo, ya que permite distribuir mejor los costos y 
garantiza el funcionamiento adecuado de los dispositivos a lo largo del tiempo.

---

**Entrevista 9**

| Campo | Detalle |
|-------|---------|
| **Nombre completo** | Cristian Centeno |
| **Edad** | 41 años |
| **Distrito** | San Ramón, Chanchamayo |
| **Inicio** | 46:24 |
| **Duración** | 12:53 |
| **Link** | `upc-pre-202610-1asi0729-11834-SoftTech-needfinding-sprint-1.mp4` |

**Características del arquetipo:**
Propietarios que gestionan viviendas en alquiler y requieren supervisión remota sin presencia 
constante. Buscan soluciones tecnológicas que faciliten el control de accesos, la prevención 
de daños y la administración eficiente de sus propiedades.

**Resumen de la entrevista:**
La entrevista se realizó con Cristian Centeno, de 41 años, residente del distrito de San 
Ramón, provincia de Chanchamayo. Vive en un núcleo familiar compuesto por tres personas, 
incluyendo un niño pequeño. El entrevistado señaló que su zona de residencia presenta bajos 
niveles de criminalidad en comparación con ciudades grandes como Lima, por lo que actualmente 
no cuenta con sistemas tecnológicos de seguridad, apoyándose principalmente en la vigilancia 
municipal del serenazgo, la cual considera moderadamente efectiva.

En relación con la seguridad del hogar, indicó que la principal vulnerabilidad no proviene 
necesariamente de la delincuencia, sino de posibles riesgos naturales o domésticos propios 
de la zona, como inundaciones o huaycos debido a la cercanía con ríos y quebradas. No 
obstante, afirmó que su familia adopta una cultura preventiva para anticipar riesgos y evitar 
emergencias dentro del hogar.

El entrevistado destacó la importancia de las tecnologías basadas en Internet de las Cosas 
(IoT), especialmente aquellas capaces de enviar alertas en tiempo real al celular ante 
situaciones de peligro. Considera que estos sistemas no solo ayudan a prevenir accidentes 
domésticos, sino que también permiten recopilar información útil para la toma de decisiones 
tanto en el ámbito familiar como empresarial. Asimismo, mencionó que la motivación principal 
para implementar tecnologías de monitoreo estaría relacionada con la protección de su hijo 
pequeño y la supervisión del entorno cuando terceros estén a cargo del cuidado del hogar.

Respecto al funcionamiento del sistema ante emergencias, señaló que la automatización de 
alertas hacia autoridades debería depender del contexto y del nivel de riesgo, permitiendo 
inicialmente la verificación por parte del usuario cuando sea posible. Enfatizó además que 
para confiar plenamente en un sistema de monitoreo, este debe contar con dispositivos 
certificados, estándares de calidad, empresas proveedoras con buena reputación y sólidas 
políticas de protección de datos que garanticen la privacidad familiar.

En el aspecto económico, manifestó disposición a pagar por un servicio premium de monitoreo 
si este logra prevenir pérdidas significativas o riesgos importantes, considerando la 
inversión en seguridad como una medida rentable frente a posibles daños o accidentes. 
Finalmente, señaló que los sensores representan una alternativa menos invasiva que las 
cámaras tradicionales, al ofrecer monitoreo eficiente sin afectar la privacidad de los 
habitantes.

## 2.2.3. Análisis de entrevistas

### Análisis Segmento 1: Jóvenes adultos independientes

Los entrevistados que viven en ciudades con menor nivel de criminalidad indicaron que no 
consideran prioritaria la seguridad contra robos, ya que cuentan con vigilancia local. Sin 
embargo, manifestaron preocupación por riesgos domésticos como inundaciones, fugas de gas 
o accidentes eléctricos, especialmente cuando hay niños o cuando la vivienda queda sola. 
Valoraron positivamente un sistema inteligente que permita anticipar incidentes mediante 
sensores, destacando la importancia de la certificación tecnológica, la protección de datos 
y la confiabilidad del proveedor. Consideran que los sensores ambientales son menos invasivos 
que las cámaras y representan una alternativa adecuada para mantener la privacidad familiar.

---

### Análisis Segmento 2: Familias urbanas

En entornos urbanos, las entrevistas muestran que las familias sí perciben un mayor nivel 
de vulnerabilidad cuando la vivienda queda sola, incluso contando con cámaras o alarmas 
básicas. Los principales insights se relacionan con la necesidad de monitoreo constante sin 
supervisión humana, alertas inmediatas ante intrusiones o accidentes domésticos y herramientas 
que permitan verificar remotamente el estado del hogar desde el celular.

Uno de los participantes expresó que este tipo de alertas puede ayudar a prevenir la pérdida 
de bienes materiales, ahorrando tiempo y dinero, al proteger contra amenazas externas como 
por riesgos internos cotidianos, valorando especialmente sistemas fáciles de instalar, 
automatizados y capaces de enviar notificaciones en tiempo real para reaccionar rápidamente. 
La privacidad también emerge como un factor clave, inclinando la preferencia hacia sensores 
inteligentes que complementen o reemplacen el uso excesivo de cámaras.

---

### Análisis Segmento 3: Propietarios de inmuebles en alquiler

Las entrevistas con arrendadores revelan que valorarían mucho una propuesta tecnológica que 
permita la protección y supervisión eficiente de sus activos inmobiliarios sin generar 
incomodidad en los inquilinos. Actualmente dependen de visitas presenciales ocasionales para 
verificar el estado de las propiedades, lo que dificulta detectar a tiempo filtraciones, 
descuidos o daños estructurales de sus inmuebles.

Uno de los entrevistados valoró el uso de sensores IoT que permitan monitoreo remoto mediante 
dashboards, y añadió que sería útil implementar una funcionalidad que permita la verificación 
de una alerta por parte del inquilino también. Se señaló además que la ausencia de cámaras 
es vital para preservar la privacidad del arrendatario. Consideran que integrar tecnología 
preventiva puede incrementar el valor del alquiler, atraer mejores inquilinos y justificar 
modelos de suscripción mensual con mantenimiento incluido, posicionando a SafeHome como una 
herramienta de gestión inmobiliaria preventiva además de un sistema de seguridad.

---

### Análisis General

Las entrevistas realizadas a familias y propietarios de inmuebles evidencian que, aunque 
muchos hogares cuentan con medidas básicas de seguridad como vigilancia municipal, cámaras 
externas o visitas periódicas de supervisión, aún existe una preocupación importante por los 
riesgos internos del hogar. Problemas como fugas de gas, incendios, filtraciones de agua o 
descuidos de inquilinos representan amenazas que suelen detectarse tarde, generando pérdidas 
económicas y preocupación constante en los usuarios.

Asimismo, los entrevistados coincidieron en la necesidad de contar con herramientas 
tecnológicas que permitan monitorear sus viviendas o propiedades de forma remota sin invadir 
la privacidad de las personas. Se observa una alta aceptación hacia soluciones basadas en 
sensores inteligentes e Internet de las Cosas (IoT), especialmente aquellas que envíen alertas 
inmediatas ante incidentes críticos y permitan centralizar la información en una plataforma o 
dashboard accesible desde el celular o computadora.

Para el proyecto SafeHome, estos resultados validan la propuesta de desarrollar un sistema de 
monitoreo preventivo enfocado en la detección temprana de riesgos domésticos. Las entrevistas 
confirman que existe una oportunidad real de mercado para una solución segura, no invasiva y 
basada en suscripción mensual, capaz de mejorar la protección del hogar, optimizar la gestión 
de propiedades y brindar tranquilidad tanto a familias como a propietarios arrendadores.

## 2.3. Needfinding

Contenido de la sección.

### 2.3.1. User Personas

<p align="center">
  <img src="assets/segmento1.png" width="400"/>
</p>

<p align="center">
  <img src="assets/semento1_1.png" width="400"/>
</p>

---


<p align="center">
  <img src="assets/segmento2.png" width="400"/>
</p>

<p align="center">
  <img src="assets/segmento2_1.png" width="400"/>
</p>

---


<p align="center">
  <img src="assets/segmento3.png" width="400"/>
</p>

<p align="center">
  <img src="assets/segmento3_1.png" width="400"/>
</p>

### 2.3.2. User Task Matrix

## Segmento objetivo 1: Jóvenes Adultos Independientes

| Tarea del Usuario                                                                 | Frecuencia | Importancia |
|----------------------------------------------------------------------------------|------------|-------------|
| Verificar que puertas, ventanas y accesos queden bien asegurados antes de salir | Alta       | Alta        |
| Supervisar el estado del hogar cuando no se encuentra presente                  | Alta       | Alta        |
| Detectar ingresos no autorizados o movimientos sospechosos                      | Alta       | Alta        |
| Confirmar que no existan incidentes internos (humo, fugas, fallas)              | Media      | Alta        |
| Revisar rápidamente si todo está en orden al regresar a casa                    | Alta       | Media       |
| Coordinar una acción inmediata ante una alerta o situación anómala              | Media      | Alta        |

---

## Segmento objetivo 2: Familias Urbanas

| Tarea del Usuario                                                                 | Frecuencia | Importancia |
|----------------------------------------------------------------------------------|------------|-------------|
| Verificar que los accesos del hogar estén protegidos día y noche                | Alta       | Alta        |
| Supervisar constantemente el estado del hogar cuando la familia no está reunida | Alta       | Alta        |
| Detectar robos, intentos de ingreso o situaciones sospechosas                   | Alta       | Alta        |
| Identificar incidentes internos (humo, fugas de gas, fallas eléctricas)         | Alta       | Alta        |
| Coordinar una respuesta rápida para proteger a los integrantes del hogar        | Alta       | Alta        |
| Revisar eventos o incidentes ocurridos en la vivienda                           | Media      | Alta        |

---

## Segmento objetivo 3: Propietarios de Inmuebles en Alquiler

| Tarea del Usuario                                                                 | Frecuencia | Importancia |
|----------------------------------------------------------------------------------|------------|-------------|
| Supervisar el estado general del inmueble ocupado por terceros                  | Alta       | Alta        |
| Detectar daños, usos inadecuados o situaciones anómalas                         | Alta       | Alta        |
| Verificar incidentes como fugas, humo o problemas de servicios básicos          | Alta       | Alta        |
| Controlar el uso adecuado de recursos (agua, luz, gas)                          | Alta       | Alta        |
| Revisar incidentes para prevenir daños mayores                                  | Alta       | Alta        |
| Confirmar seguridad frente a accesos no autorizados                             | Media      | Alta        |
### 2.3.3. User Journey Mapping

<p align="center">
  <img src="assets/segmento1.png" width="400"/>
</p>

<p align="center">
  <img src="assets/semento1_1.png" width="400"/>
</p>

---


<p align="center">
  <img src="assets/segmento2.png" width="400"/>
</p>

<p align="center">
  <img src="assets/segmento2_1.png" width="400"/>
</p>

---


<p align="center">
  <img src="assets/segmento3.png" width="400"/>
</p>

<p align="center">
  <img src="assets/segmento3_1.png" width="400"/>
</p>

## 2.3.4. Empathy Mapping

Contenido de la sección.

## 2.4. Big Picture Event Storming

Contenido de la sección.

## 2.5. Ubiquitous Language

Con el objetivo de garantizar una comunicación efectiva entre el equipo de desarrollo de 
SOFT TECH y los interesados del proyecto, se ha definido el siguiente lenguaje ubicuo basado 
en el dominio de la seguridad doméstica inteligente:

---

### Security and Monitoring Entities (Entidades de Seguridad y Monitoreo)

- **IoT Sensor (Sensor IoT):** Dispositivo físico especializado capaz de detectar anomalías 
  (movimiento, humo, gas, agua) en tiempo real y enviar datos a la plataforma.

- **SafeHome Smart Security System (Sistema de Seguridad Inteligente SafeHome):** Nombre 
  oficial de la solución tecnológica integral basada en Internet de las Cosas para proteger 
  el hogar.

- **Monitoring Dashboard (Dashboard de Monitoreo):** Interfaz principal de la aplicación web 
  donde el usuario visualiza el estado general de su hogar y sus dispositivos.

- **Surveillance Camera (Cámara de Videovigilancia):** Dispositivo de captura de video 
  integrado al sistema para el monitoreo visual externo e interno.

---

### Events and Alerts (Eventos y Alertas)

- **Anomaly (Anomalía):** Cualquier detección inusual realizada por los sensores, como una 
  fuga de gas, consumo excesivo de agua o intrusión no autorizada.

- **Smart Alert (Alerta Inteligente):** Notificación push enviada al usuario en tiempo real 
  ante la detección de un riesgo o anomalía.

- **Security Event (Evento de Seguridad):** Registro cronológico de una actividad detectada 
  por el sistema que requiere atención o seguimiento.

- **Real-Time Notification (Notificación en Tiempo Real):** Aviso inmediato generado por el 
  sistema que permite al usuario actuar oportunamente ante un peligro.

---

### Business and Plans (Negocio y Planes)

- **Freemium Model (Modelo Freemium):** Estrategia de negocio que ofrece funciones básicas 
  gratuitas y funciones avanzadas bajo suscripción.

- **Premium Subscription (Suscripción Premium):** Plan de pago que incluye monitoreo avanzado 
  24/7, detección de fugas y asistencia técnica especializada.

- **DIY Approach (Enfoque DIY - Hazlo tú mismo):** Filosofía de instalación autogestionada 
  por el usuario, sin necesidad de técnicos especializados.

- **Comprehensive Monitoring (Monitoreo Integral):** Capacidad del sistema para supervisar 
  tanto el perímetro externo como el interior de la vivienda.

---

### Roles and Segments (Roles y Segmentos)

- **Admin User (Usuario Administrador):** Persona que posee el control total sobre la 
  configuración de los dispositivos y la gestión de alertas.

- **Visitor (Visitante):** Persona que navega por la Landing Page buscando información sobre 
  los beneficios y servicios de la startup.

- **Independent Young Adult (Joven Independiente):** Segmento objetivo que vive en 
  departamentos urbanos y prioriza la accesibilidad y tecnología.

- **Property Owner (Propietario de Inmueble):** Usuario que utiliza el sistema para supervisar 
  propiedades en alquiler y evitar daños estructurales.
---

# Capítulo III: Requirements Specification

## 3.1. User Stories

### HU01 - Visualizar propuesta de valor

| Campo | Detalle |
|---|---|
| **User Story ID** | HU01 |
| **Epic ID** | 1 |
| **Title** | Visualizar propuesta de valor |
| **Description** | Como visitante, quisiera conocer el propósito del servicio para entender su utilidad. |

**Acceptance Criteria**

**Escenario 1: Mostrar propuesta de valor al ingresar**

- **Dado** que el visitante ingresa al sitio  
- **Cuando** accede a la página principal  
- **Entonces** el sistema muestra la propuesta de valor  

**Escenario 2: Comprensión del propósito del servicio**

- **Dado** que el visitante navega en la página  
- **Cuando** revisa el contenido  
- **Entonces** encuentra información clara del servicio  

---

### HU02 - Ver beneficios del servicio

| Campo | Detalle |
|---|---|
| **User Story ID** | HU02 |
| **Epic ID** | 1 |
| **Title** | Ver beneficios del servicio |
| **Description** | Como visitante, quisiera conocer los beneficios para evaluar el servicio. |

**Acceptance Criteria**

**Escenario 1: Visualización de beneficios**

- **Dado** que el visitante accede a la sección de beneficios  
- **Cuando** revisa la información  
- **Entonces** el sistema muestra ventajas del servicio  

**Escenario 2: Comprensión de ventajas**

- **Dado** que el contenido está disponible  
- **Cuando** el visitante lo visualiza  
- **Entonces** comprende los beneficios ofrecidos  

---

### HU03 - Explorar servicios disponibles

| Campo | Detalle |
|---|---|
| **User Story ID** | HU03 |
| **Epic ID** | 1 |
| **Title** | Explorar servicios disponibles |
| **Description** | Como visitante, quiero visualizar los tipos de servicios disponibles. |

**Acceptance Criteria**

**Escenario 1: Visualizar lista de servicios**

- **Dado** que el visitante accede a la sección servicios  
- **Cuando** revisa el contenido  
- **Entonces** el sistema muestra los tipos de servicios  

**Escenario 2: Diferenciación de servicios**

- **Dado** que existen múltiples servicios  
- **Cuando** el visitante navega  
- **Entonces** puede diferenciarlos claramente  

---

### HU04 - Visualizar testimonios

| Campo | Detalle |
|---|---|
| **User Story ID** | HU04 |
| **Epic ID** | 1 |
| **Title** | Visualizar testimonios |
| **Description** | Como visitante, quiere ver opiniones para generar confianza. |

**Acceptance Criteria**

**Escenario 1: Mostrar testimonios disponibles**

- **Dado** que el visitante accede a testimonios  
- **Cuando** revisa la sección  
- **Entonces** el sistema muestra experiencias de usuarios  

**Escenario 2: Carga correcta de testimonios**

- **Dado** que hay testimonios disponibles  
- **Cuando** se cargan  
- **Entonces** se muestran correctamente  

---

### HU05 - Ver información de contacto

| Campo | Detalle |
|---|---|
| **User Story ID** | HU05 |
| **Epic ID** | 1 |
| **Title** | Ver información de contacto |
| **Description** | Como visitante, quiere encontrar medios de contacto. |

**Acceptance Criteria**

**Escenario 1: Visualizar datos de contacto**

- **Dado** que el visitante accede al footer  
- **Cuando** revisa la información  
- **Entonces** encuentra datos de contacto  

**Escenario 2: Identificación de canales de comunicación**

- **Dado** que la sección está disponible  
- **Cuando** el visitante interactúa  
- **Entonces** puede identificar medios de comunicación  

---

### HU06 - Navegación entre secciones

| Campo | Detalle |
|---|---|
| **User Story ID** | HU06 |
| **Epic ID** | 1 |
| **Title** | Navegación entre secciones |
| **Description** | Como visitante, quiere desplazarse entre secciones fácilmente. |

**Acceptance Criteria**

**Escenario 1: Redirección a secciones seleccionadas**

- **Dado** que el visitante usa el menú  
- **Cuando** selecciona una sección  
- **Entonces** el sistema lo redirige correctamente  

**Escenario 2: Navegación fluida del sitio**

- **Dado** que la página contiene múltiples secciones  
- **Cuando** navega  
- **Entonces** el desplazamiento es fluido  

---

### HU07 - Acceder desde dispositivos móviles

| Campo | Detalle |
|---|---|
| **User Story ID** | HU07 |
| **Epic ID** | 1 |
| **Title** | Acceder desde dispositivos móviles |
| **Description** | Como visitante, quiero visualizar el sitio en móvil. |

**Acceptance Criteria**

**Escenario 1: Adaptación a dispositivos móviles**

- **Dado** que el visitante usa un dispositivo móvil  
- **Cuando** accede al sitio  
- **Entonces** el contenido se adapta correctamente  

**Escenario 2: Mantenimiento de funcionalidad**

- **Dado** que el sitio es responsive  
- **Cuando** se visualiza  
- **Entonces** mantiene su funcionalidad  

---

### HU08 - Ver llamada a la acción

| Campo | Detalle |
|---|---|
| **User Story ID** | HU08 |
| **Epic ID** | 1 |
| **Title** | Ver llamada a la acción |
| **Description** | Como visitante, quiere identificar acciones a realizar. |

**Acceptance Criteria**

**Escenario 1: Identificación de acciones disponibles**

- **Dado** que el visitante visualiza la página  
- **Cuando** revisa el contenido  
- **Entonces** encuentra llamadas a la acción  

**Escenario 2: Comprensión del siguiente paso**

- **Dado** que existen botones de acción  
- **Cuando** el visitante interactúa  
- **Entonces** entiende el siguiente paso  

---

### HU09 - Ver sección “Cómo funciona”

| Campo | Detalle |
|---|---|
| **User Story ID** | HU09 |
| **Epic ID** | 1 |
| **Title** | Ver sección “Cómo funciona” |
| **Description** | Como visitante, quiero entender el proceso del servicio. |

**Acceptance Criteria**

**Escenario 1: Comprensión del flujo del servicio**

- **Dado** que el visitante accede a la sección  
- **Cuando** revisa el contenido  
- **Entonces** comprende el flujo del servicio  

**Escenario 2: Visualización paso a paso**

- **Dado** que el contenido está disponible  
- **Cuando** lo visualiza  
- **Entonces** se muestra paso a paso  

---

### HU10 - Ver preguntas frecuentes

| Campo | Detalle |
|---|---|
| **User Story ID** | HU10 |
| **Epic ID** | 1 |
| **Title** | Ver preguntas frecuentes |
| **Description** | Como visitante, quiere resolver dudas comunes. |

**Acceptance Criteria**

**Escenario 1: Visualizar preguntas frecuentes**

- **Dado** que el visitante accede a FAQ  
- **Cuando** revisa las preguntas  
- **Entonces** obtiene respuestas claras  

**Escenario 2: Resolución de dudas comunes**

- **Dado** que existen preguntas frecuentes  
- **Cuando** se muestran  
- **Entonces** cubren dudas comunes  

---

### HU11 - Registrar dispositivos de seguridad

| Campo | Detalle |
|---|---|
| **User Story ID** | HU11 |
| **Epic ID** | 2 |
| **Title** | Registrar dispositivos de seguridad |
| **Description** | Como usuario, quiere registrar dispositivos, como sensores o cámaras, para monitorear su hogar. |

**Acceptance Criteria**

**Escenario 1: Registro exitoso de dispositivo**

- **Dado** que el usuario ingresa los datos del dispositivo  
- **Cuando** envía la información  
- **Entonces** el sistema registra el dispositivo  

**Escenario 2: Validación de datos incompletos**

- **Dado** que faltan datos obligatorios  
- **Cuando** intenta registrar el dispositivo  
- **Entonces** el sistema solicita completar la información  

---

### HU12 - Visualizar dispositivos registrados

| Campo | Detalle |
|---|---|
| **User Story ID** | HU12 |
| **Epic ID** | 2 |
| **Title** | Visualizar dispositivos registrados |
| **Description** | Como usuario, quiere visualizar sus dispositivos para monitorear su estado. |

**Acceptance Criteria**

**Escenario 1: Visualización de dispositivos disponibles**

- **Dado** que existen dispositivos registrados  
- **Cuando** accede al panel  
- **Entonces** el sistema muestra la lista de dispositivos  

**Escenario 2: Sin dispositivos registrados**

- **Dado** que no existen dispositivos  
- **Cuando** accede  
- **Entonces** el sistema muestra un mensaje informativo  

---

### HU13 - Activar o desactivar dispositivos

| Campo | Detalle |
|---|---|
| **User Story ID** | HU13 |
| **Epic ID** | 2 |
| **Title** | Activar o desactivar dispositivos |
| **Description** | Como usuario, quiere controlar el estado de sus dispositivos para gestionar la seguridad del hogar. |

**Acceptance Criteria**

**Escenario 1: Activación de dispositivo**

- **Dado** que el dispositivo está desactivado  
- **Cuando** el usuario lo activa  
- **Entonces** el sistema cambia su estado a activo  

**Escenario 2: Desactivación de dispositivo**

- **Dado** que el dispositivo está activo  
- **Cuando** el usuario lo desactiva  
- **Entonces** el sistema lo notifica  

---

### HU14 - Visualizar estado de seguridad del hogar

| Campo | Detalle |
|---|---|
| **User Story ID** | HU14 |
| **Epic ID** | 2 |
| **Title** | Visualizar estado de seguridad del hogar |
| **Description** | Como usuario, quiere conocer el estado general para saber si su hogar está seguro. |

**Acceptance Criteria**

**Escenario 1: Visualización del estado actual**

- **Dado** que existen dispositivos activos  
- **Cuando** el usuario consulta el panel  
- **Entonces** el sistema muestra el estado de seguridad  

**Escenario 2: Actualización del estado en tiempo real**

- **Dado** que un sensor detecta actividad  
- **Cuando** ocurre un evento  
- **Entonces** el sistema actualiza el estado  

---

### HU15 - Recibir alertas de seguridad

| Campo | Detalle |
|---|---|
| **User Story ID** | HU15 |
| **Epic ID** | 2 |
| **Title** | Recibir alertas de seguridad |
| **Description** | Como usuario, quiere recibir alertas para actuar ante posibles riesgos. |

**Acceptance Criteria**

**Escenario 1: Generación de alerta por evento**

- **Dado** que un sensor detecta una anomalía  
- **Cuando** ocurre el evento  
- **Entonces** el sistema genera una alerta  

**Escenario 2: Ausencia de alertas sin eventos**

- **Dado** que no hay actividad sospechosa  
- **Cuando** el sistema monitorea  
- **Entonces** no genera alertas  

---

### HU16 - Visualizar eventos de seguridad en tiempo real

| Campo | Detalle |
|---|---|
| **User Story ID** | HU16 |
| **Epic ID** | 3 |
| **Title** | Visualizar eventos de seguridad en tiempo real |
| **Description** | Como usuario, quiere visualizar eventos detectados para monitorear su hogar en tiempo real. |

**Acceptance Criteria**

**Escenario 1: Visualización de eventos en tiempo real**

- **Dado** que existen eventos generados por sensores  
- **Cuando** el usuario accede al panel  
- **Entonces** el sistema muestra los eventos en tiempo real  

**Escenario 2: Ausencia de eventos**

- **Dado** que no existen eventos recientes  
- **Cuando** el usuario accede al panel  
- **Entonces** el sistema muestra un estado sin actividad  

---

### HU17 - Visualizar detalles de evento

| Campo | Detalle |
|---|---|
| **User Story ID** | HU17 |
| **Epic ID** | 3 |
| **Title** | Visualizar detalles de evento |
| **Description** | Como usuario, quiere ver el detalle de un evento para entender la situación detectada. |

**Acceptance Criteria**

**Escenario 1: Visualización de detalle de evento**

- **Dado** que existe un evento registrado  
- **Cuando** el usuario lo selecciona  
- **Entonces** el sistema muestra su información detallada  

**Escenario 2: Evento no disponible**

- **Dado** que el evento no existe  
- **Cuando** el usuario intenta acceder  
- **Entonces** informa que no está disponible  

---

### HU18 - Marcar evento como atendido

| Campo | Detalle |
|---|---|
| **User Story ID** | HU18 |
| **Epic ID** | 3 |
| **Title** | Marcar evento como atendido |
| **Description** | Como usuario, quiere marcar eventos para llevar control de incidencias. |

**Acceptance Criteria**

**Escenario 1: Marcado exitoso de evento**

- **Dado** que el evento está activo  
- **Cuando** el usuario lo marca como atendido  
- **Entonces** el sistema actualiza su estado  

**Escenario 2: Evento ya atendido**

- **Dado** que el evento ya fue atendido  
- **Cuando** intenta marcarlo nuevamente  
- **Entonces** el sistema lo informa  

---

### HU19 - Eliminar registro de evento

| Campo | Detalle |
|---|---|
| **User Story ID** | HU19 |
| **Epic ID** | 3 |
| **Title** | Eliminar registro de evento |
| **Description** | Como usuario, quiere eliminar eventos para mantener organizado el historial. |

**Acceptance Criteria**

**Escenario 1: Eliminación exitosa de evento**

- **Dado** que existe un evento registrado  
- **Cuando** el usuario lo elimina  
- **Entonces** el sistema lo elimina correctamente  

**Escenario 2: Evento inexistente**

- **Dado** que el evento no existe  
- **Cuando** intenta eliminarlo  
- **Entonces** el sistema informa el error  

---

### HU20 - Visualizar estado general del sistema de seguridad

| Campo | Detalle |
|---|---|
| **User Story ID** | HU20 |
| **Epic ID** | 3 |
| **Title** | Visualizar estado general del sistema de seguridad |
| **Description** | Como usuario, quiere ver un resumen del estado de su hogar para evaluar su seguridad. |

**Acceptance Criteria**

**Escenario 1: Visualización del estado general**

- **Dado** que existen dispositivos conectados  
- **Cuando** el usuario accede al panel principal  
- **Entonces** el sistema muestra el estado general del hogar  

**Escenario 2: Actualización del estado en tiempo real**

- **Dado** que ocurre un evento  
- **Cuando** el sistema lo detecta  
- **Entonces** el estado general se actualiza automáticamente  

---

### HU21 - Filtrar solicitudes

| Campo | Detalle |
|---|---|
| **User Story ID** | HU21 |
| **Epic ID** | 4 |
| **Title** | Filtrar solicitudes |
| **Description** | Como usuario, quiere filtrar solicitudes para encontrar información relevante durante el seguimiento del servicio. |

**Acceptance Criteria**

**Escenario 1: Filtrado exitoso de solicitudes**

- **Dado** que existen solicitudes registradas  
- **Cuando** el usuario aplica criterios de filtrado  
- **Entonces** el sistema muestra resultados que cumplen los criterios  

**Escenario 2: Sin coincidencias en el filtrado**

- **Dado** que no existen resultados coincidentes  
- **Cuando** el usuario aplica filtros  
- **Entonces** el sistema muestra una lista vacía  

---

### HU22 - Solicitudes

| Campo | Detalle |
|---|---|
| **User Story ID** | HU22 |
| **Epic ID** | 4 |
| **Title** | Solicitudes |
| **Description** | Como usuario, quiere ordenar solicitudes para priorizar la información relevante del servicio. |

**Acceptance Criteria**

**Escenario 1: Ordenamiento correcto de solicitudes**

- **Dado** que existen múltiples solicitudes  
- **Cuando** el usuario aplica un criterio de orden  
- **Entonces** el sistema ordena los resultados correctamente  

**Escenario 2: Cambio de criterio de orden**

- **Dado** que el usuario selecciona otro criterio  
- **Cuando** aplica el orden  
- **Entonces** el sistema reorganiza la lista  

---

### HU23 - Visualizar historial de solicitudes

| Campo | Detalle |
|---|---|
| **User Story ID** | HU23 |
| **Epic ID** | 1 |
| **Title** | Visualizar historial de solicitudes |
| **Description** | Como usuario, quiero revisar el historial para hacer seguimiento a los servicios realizados. |

**Acceptance Criteria**

**Escenario 1: Visualización de historial existente**

- **Dado** que existen solicitudes registradas  
- **Cuando** el usuario consulta el historial  
- **Entonces** el sistema muestra la información  

**Escenario 2: Historial vacío**

- **Dado** que no existen registros  
- **Cuando** el usuario accede al historial  
- **Entonces** el sistema muestra un mensaje informativo  

---

### HU24 - Recibir notificaciones del servicio

| Campo | Detalle |
|---|---|
| **User Story ID** | HU24 |
| **Epic ID** | 4 |
| **Title** | Recibir notificaciones del servicio |
| **Description** | Como usuario, quiere recibir notificaciones para mantenerse informado del estado del servicio. |

**Acceptance Criteria**

**Escenario 1: Notificación por actualización de estado**

- **Dado** que ocurre un cambio en la solicitud  
- **Cuando** el estado se actualiza  
- **Entonces** el sistema genera una notificación  

**Escenario 2: Ausencia de notificación sin cambios**

- **Dado** que no ocurre ningún evento  
- **Cuando** el sistema evalúa  
- **Entonces** no se genera notificación  

---

### HU25 - Compartir ubicación

| Campo | Detalle |
|---|---|
| **User Story ID** | HU25 |
| **Epic ID** | 4 |
| **Title** | Compartir ubicación |
| **Description** | Como usuario, quiere compartir su ubicación para mejorar el seguimiento del servicio. |

**Acceptance Criteria**

**Escenario 1: Obtención de ubicación correcta**

- **Dado** que el usuario habilita la ubicación  
- **Cuando** el sistema la solicita  
- **Entonces** obtiene las coordenadas correctamente  

**Escenario 2: Ubicación no disponible**

- **Dado** que la ubicación está deshabilitada  
- **Cuando** el sistema intenta obtenerla  
- **Entonces** informa la situación  

---

### HU26 - Autorización en endpoints

| Campo | Detalle |
|---|---|
| **User Story ID** | HU26 |
| **Epic ID** | 4 |
| **Title** | Autorización en endpoints |
| **Description** | Como Developer, quiere validar accesos para proteger la comunicación del sistema. |

**Acceptance Criteria**

**Escenario 1: Acceso autorizado a recursos**

- **Dado** credenciales válidas  
- **Cuando** se realiza la petición  
- **Entonces** el sistema permite el acceso  

**Escenario 2: Acceso no autorizado**

- **Dado** credenciales inválidas  
- **Cuando** se realiza la petición  
- **Entonces** retorna código 401  

---

### HU27 - Control de tiempo de respuesta

| Campo | Detalle |
|---|---|
| **User Story ID** | HU27 |
| **Epic ID** | 4 |
| **Title** | Control de tiempo de respuesta |
| **Description** | Como Developer, quiere controlar tiempos para garantizar una comunicación eficiente. |

**Acceptance Criteria**

**Escenario 1: Respuesta en tiempo esperado**

- **Dado** una petición válida  
- **Cuando** el sistema procesa  
- **Entonces** responde dentro del tiempo definido  

**Escenario 2: Detección de demora**

- **Dado** alta carga  
- **Cuando** se procesa la solicitud  
- **Entonces** se detecta retraso  

---

### HU28 - Persistencia de interacciones

| Campo | Detalle |
|---|---|
| **User Story ID** | HU28 |
| **Epic ID** | 4 |
| **Title** | Persistencia de interacciones |
| **Description** | Como Developer, quiere almacenar interacciones para seguimiento del servicio. |

**Acceptance Criteria**

**Escenario 1: Almacenamiento exitoso**

- **Dado** datos válidos  
- **Cuando** se envían  
- **Entonces** se almacenan correctamente  

**Escenario 2: Error en almacenamiento**

- **Dado** una falla  
- **Cuando** se intenta guardar  
- **Entonces** el sistema notifica el error  

---

### HU29 - Consistencia de datos de seguimiento

| Campo | Detalle |
|---|---|
| **User Story ID** | HU29 |
| **Epic ID** | 4 |
| **Title** | Consistencia de datos de seguimiento |
| **Description** | Como Developer, quiere mantener consistencia en los datos del servicio. |

**Acceptance Criteria**

**Escenario 1: Consistencia en operaciones**

- **Dado** múltiples procesos  
- **Cuando** se ejecutan  
- **Entonces** los datos se mantienen consistentes  

**Escenario 2: Detección de inconsistencia**

- **Dado** que ocurre un error  
- **Cuando** se procesa información  
- **Entonces** el sistema lo identifica  

---

### HU30 - Disponibilidad del servicio

| Campo | Detalle |
|---|---|
| **User Story ID** | HU30 |
| **Epic ID** | 4 |
| **Title** | Disponibilidad del servicio |
| **Description** | Como usuario, quiere acceder al seguimiento del servicio en todo momento. |

**Acceptance Criteria**

**Escenario 1: Sistema disponible**

- **Dado** que el sistema está operativo  
- **Cuando** el usuario accede  
- **Entonces** responde correctamente  

**Escenario 2: Sistema no disponible**

- **Dado** una falla del sistema  
- **Cuando** el usuario intenta acceder  
- **Entonces** informa la indisponibilidad  

## 3.2. Impact Mapping

<p align="center">
  <img src="assets/Impact-Mapping.png" alt="Impact Mapping de SafeHome" width="850"/>
</p>

<p align="center">
  <em>Nota: Elaboración propia.</em>
</p>


## 3.3. Product Backlog

| # Orden | User Story ID | Descripción | Story Points |
|---|---|---|---|
| 1 | HU11 | Registrar dispositivos de seguridad en el sistema | 8 |
| 2 | HU16 | Visualizar eventos de seguridad en tiempo real | 8 |
| 3 | HU20 | Visualizar estado general del sistema de seguridad | 8 |
| 4 | HU26 | Validar acceso seguro a funcionalidades del sistema | 8 |
| 5 | HU28 | Almacenar eventos de seguridad generados | 5 |
| 6 | HU03 | Explorar dispositivos o servicios de seguridad disponibles | 5 |
| 7 | HU06 | Navegar entre secciones del sistema web | 5 |
| 8 | HU07 | Acceder desde dispositivos móviles responsive | 5 |
| 9 | HU12 | Visualizar dispositivos registrados | 5 |
| 10 | HU13 | Activar o desactivar dispositivos de seguridad | 5 |
| 11 | HU17 | Visualizar detalles de eventos de seguridad | 5 |
| 12 | HU18 | Marcar eventos como atendidos | 5 |
| 13 | HU21 | Filtrar eventos de seguridad | 5 |
| 14 | HU24 | Recibir notificaciones de alertas | 5 |
| 15 | HU25 | Visualizar ubicación del evento de seguridad | 5 |
| 16 | HU29 | Mantener consistencia de datos del sistema | 5 |
| 17 | HU30 | Garantizar disponibilidad del sistema | 5 |
| 18 | HU01 | Visualizar propuesta de valor del sistema | 3 |
| 19 | HU02 | Ver beneficios del sistema de seguridad | 3 |
| 20 | HU08 | Identificar llamadas a la acción | 3 |
| 21 | HU09 | Entender cómo funciona el sistema | 3 |
| 22 | HU14 | Visualizar estado de seguridad del hogar | 3 |
| 23 | HU15 | Recibir alertas de seguridad | 3 |
| 24 | HU19 | Eliminar eventos de seguridad | 3 |
| 25 | HU22 | Ordenar eventos de seguridad | 3 |
| 26 | HU23 | Visualizar historial de eventos | 3 |
| 27 | HU27 | Controlar tiempo de respuesta del sistema | 3 |
| 28 | HU05 | Visualizar información de contacto | 2 |
| 29 | HU10 | Ver preguntas frecuentes | 2 |
| 30 | HU04 | Visualizar testimonios | 2 |
---

# Capítulo IV: Product Design

## 4.1. Style Guidelines

Contenido de la sección.

### 4.1.1. General Style Guidelines
La guía general de estilo de SafeHome establece los lineamientos visuales base que se aplicarán en el Landing Page y en la Web Application. Su objetivo es mantener consistencia gráfica, legibilidad, reconocimiento de marca y uniformidad en los componentes de interfaz. Para ello, se definieron reglas comunes de branding, color, tipografía, espaciado y lenguaje visual, de modo que todos los entregables del proyecto utilicen el mismo sistema de diseño.

![](./assets/imagen1-style-guidelines.png)

Branding
La identidad visual de SafeHome se construye a partir de un logotipo compuesto por un isotipo de casa con contorno circular y el nombre de la marca en una composición horizontal. Este recurso gráfico comunica de forma directa los conceptos de hogar, protección y monitoreo. El logotipo se utiliza como elemento principal de reconocimiento visual en pantallas de inicio, barras de navegación, formularios de acceso y secciones de presentación del servicio.
Para conservar consistencia visual, el sistema considera un uso uniforme del logo en relación con el espaciado. La unidad base tomada para márgenes y áreas de seguridad es la altura del ícono del logotipo. De este modo, se evita que otros elementos invadan su área visual y se garantiza una correcta legibilidad en diferentes tamaños de pantalla.

![](./assets/imagen2-style-guidelines.png)

**Paleta de colores**
 
La paleta cromática de SafeHome se compone de cinco colores principales:
 
- `#A7F3E4` para fondos suaves y superficies secundarias.
- `#00E5C3` como color de acento y principal llamada visual.
- `#0D0D0D` para títulos, bloques destacados y contraste fuerte.
- `#6B7280` para texto secundario y elementos de apoyo.
- `#F5F5F5` para fondos neutros y separación visual de secciones.

![](./assets/imagen3-style-guidelines.png)

![](./assets/imagen4-style-guidelines.png)

Esta selección responde a tres necesidades del producto. Primero, transmitir seguridad y limpieza visual mediante tonos claros y neutros. Segundo, destacar acciones relevantes usando un turquesa brillante como color primario de interacción. Tercero, asegurar contraste suficiente entre texto, botones y superficies, especialmente en pantallas donde se muestra información operativa del hogar.
 
**Tipografía**
 
La familia tipográfica seleccionada es Arial Rounded MT Bold. Esta tipografía se utiliza en títulos, botones y elementos principales de interfaz. Su elección responde a dos criterios: buena legibilidad en tamaños medianos y pequeños, y una forma visual amigable que reduce rigidez excesiva sin perder claridad.
 
La jerarquía tipográfica definida es la siguiente:
 
- H1: 36/44 px
- H2: 24/32 px
- H3: 18/26 px
- Texto destacado: 16/24 px
- Texto de párrafo: 14/20 px
- Texto pequeño o de ayuda: 12/16 px

![](./assets/imagen5-style-guidelines.png)

Esta jerarquía permite diferenciar correctamente títulos, subtítulos, bloques descriptivos y mensajes de apoyo. En la aplicación, esto facilita la lectura rápida de estados, servicios, planes y formularios.
 
**Espaciado**
 
El sistema de espaciado se basa en una retícula de múltiplos de **8 px**. Los valores establecidos son 8 px, 16 px, 24 px, 32 px, 48 px, 64 px, 80 px y 96 px. Esta decisión permite mantener alineación consistente entre bloques, separación uniforme entre componentes y una distribución visual predecible en resoluciones desktop y mobile.
 
El uso de una escala fija también facilita la construcción de layouts reutilizables. Por ejemplo, los espacios entre tarjetas, botones, grupos de texto y contenedores siguen una lógica repetible, lo cual simplifica el prototipado y la implementación posterior en desarrollo.
 
**Bordes, radios y sombras**
 
Para la geometría de la interfaz se definieron radios de borde de 4 px, 8 px, 12 px, 16 px, 24 px y 32 px. Esta escala permite adaptar el nivel de redondeo según el tipo de componente. Los campos de formulario, botones y tarjetas usan bordes redondeados para mantener coherencia con la tipografía y con la identidad visual general.
 
En cuanto a profundidad visual, se definieron tres niveles de sombra:
 
- Sombra S: 0 px 2 px 8 px rgba(0,0,0,0.06)
- Sombra M: 0 px 8 px 24 px rgba(0,0,0,0.08)
- Sombra L: 0 px 16 px 40 px rgba(0,0,0,0.12)

![](./assets/imagen6-style-guidelines.png)

Estas sombras se utilizan de forma moderada en tarjetas, bloques destacados y elementos elevados. No se aplican de forma excesiva, ya que el sistema prioriza limpieza visual y lectura clara de contenido.
 
**Lenguaje visual e iconografía**
 
La iconografía del sistema utiliza íconos simples, lineales y de fácil reconocimiento. Entre ellos se incluyen referencias a hogar, seguridad, alertas, configuración, monitoreo y acciones de usuario. Este estilo evita ambigüedad visual y mantiene compatibilidad con el enfoque funcional de la plataforma.
 
A nivel gráfico, SafeHome utiliza una interfaz de baja saturación en fondos y alta claridad en elementos accionables. La combinación entre fondos claros, acentos turquesa y bloques negros destacados permite jerarquizar información sin recargar la pantalla.

![](./assets/imagen7-style-guidelines.png)

**Tono de comunicación**
 
El tono de comunicación definido para SafeHome es **serio, claro, respetuoso y directo**. No se emplea un lenguaje irreverente ni decorativo. La redacción de botones, mensajes, estados y alertas usa frases breves y funcionales.
 
En la dimensión de estilo comunicacional, la propuesta se ubica así:
 
- Serio antes que divertido.
- Semiformal antes que casual.
- Respetuoso antes que irreverente.
- Sereno antes que entusiasta.
Este criterio es coherente con el tipo de producto, ya que SafeHome gestiona información relacionada con monitoreo del hogar, prevención y control. Por ello, la interfaz debe transmitir confianza operativa y no entretenimiento.
 
**Principios de diseño aplicados**
 
Los lineamientos generales del sistema se apoyan en los siguientes principios:
 
- Consistencia: mismo uso de colores, tipografía, iconos y componentes en todo el ecosistema.
- Claridad visual: jerarquía evidente entre títulos, contenido, acciones principales y estados del sistema.
- Legibilidad: tamaños tipográficos y contrastes adecuados para lectura rápida.
- Simplicidad funcional: reducción de elementos innecesarios y priorización de acciones concretas.
- Reconocimiento inmediato: uso estable del logo, la paleta y los patrones visuales en todas las pantallas.

### 4.1.2. Web Style Guidelines

Los Web Style Guidelines de SafeHome definen las reglas visuales y de interacción aplicadas a las interfaces web del Landing Page y de la Web Application. Estas reglas aseguran consistencia entre pantallas desktop y mobile, uniformidad en los componentes y una experiencia de uso predecible. Su aplicación se basa en la guía general de estilo ya definida, adaptándola al comportamiento específico de interfaces web responsive.

![](./assets/imagen8-style-guidelines.png)

**Estructura visual para web**
 
La estructura de pantalla utiliza una organización por bloques claramente delimitados. En el Landing Page, la interfaz se divide en secciones horizontales de navegación, presentación principal, servicios, planes y acceso. En la Web Application, la estructura cambia a un esquema más funcional, con menú lateral o navegación fija y áreas de contenido principal.
 
En desktop, la distribución prioriza el uso de contenedores amplios, tarjetas alineadas y separación clara entre bloques informativos. En mobile, la estructura se reorganiza en una sola columna, manteniendo el mismo orden lógico del contenido, pero adaptando el tamaño de componentes, márgenes y jerarquías visuales.
 
**Diseño responsive**
 
La propuesta web de SafeHome sigue un enfoque responsive para garantizar adaptación a Desktop Web Browser y Mobile Web Browser. La interfaz mantiene la misma identidad visual en ambos formatos, pero ajusta la disposición de elementos según el ancho disponible.
 
Las principales reglas de adaptación son las siguientes:
 
- En desktop, los contenidos se muestran en varias columnas cuando el espacio lo permite.
- En mobile, los bloques se apilan verticalmente.
- Los botones principales mantienen jerarquía visual, pero reducen ancho y padding según pantalla.
- Las tarjetas conservan estructura, aunque cambian de disposición horizontal a vertical.
- La navegación superior simplifica la distribución de opciones en resoluciones pequeñas.
Esto permite que el usuario encuentre la misma información y complete las mismas tareas sin depender de un único tipo de dispositivo.

![](./assets/imagen9-style-guidelines.png)

La navegación principal utiliza un menú visible y de acceso directo. En el Landing Page, las opciones identificadas son Inicio, Servicios, Ver planes e Iniciar sesión, acompañadas del logotipo como elemento de identidad central. Esta navegación se mantiene simple y con pocas opciones para evitar sobrecarga.
 
En la aplicación web, la navegación cambia a una estructura orientada a tareas. Se observa un menú lateral con accesos como Inicio, Cámaras, Dispositivos, Eventos, Alertas, Historial y Configuración. Esta decisión responde a un entorno con mayor volumen de información y acciones frecuentes.
 
Las reglas de navegación son:
 
- mantener visibles las acciones principales;
- usar etiquetas cortas y directas;
- ubicar opciones persistentes en zonas previsibles;
- evitar que el usuario dependa de memorizar rutas.

![](./assets/imagen10-style-guidelines.png)

**Botones y llamadas a la acción**
 
La interfaz web define tres niveles de botones:
 
- Primario, para la acción principal de la pantalla;
- Secundario, para acciones complementarias;
- Terciario, para acciones de menor peso visual o navegación textual.
El botón primario usa el color turquesa como color de acción principal. El secundario emplea contorno con fondo claro. El terciario se presenta como texto con menor peso visual. Esta jerarquía facilita reconocer qué acción debe ejecutarse primero.
 
También se definen estados de interacción consistentes:
 
- Default
- Hover
- Activo
- Deshabilitado
En web, esto es importante porque el usuario espera retroalimentación visual al pasar el cursor, presionar o encontrar acciones no disponibles.

![](./assets/imagen11-style-guidelines.png)

**Formularios y campos de entrada**
 
Los formularios utilizan componentes simples, con bordes redondeados y alto contraste respecto al fondo. Los tipos de campo identificados en la guía son:
 
- input por defecto;
- input con ícono;
- dropdown.
Las reglas aplicadas a formularios son:
 
- mostrar placeholder breve;
- mantener alineación uniforme entre campos;
- usar separación suficiente entre inputs;
- presentar botones de acción inmediatamente después del grupo de campos;
- evitar textos largos dentro del formulario.
En la pantalla de inicio de sesión, por ejemplo, se observa una estructura clara con campos de correo y contraseña, opción de recordar sesión y acceso a recuperación de contraseña. Esto responde a un patrón web estándar y fácil de reconocer.
 
**Tarjetas y contenedores**
 
Las tarjetas se usan como contenedores de información para servicios, planes, cámaras y accesos rápidos. Cada tarjeta presenta una jerarquía interna compuesta por título, contenido breve, ícono o imagen y acción asociada cuando corresponde.
 
Las reglas para tarjetas son:
 
- usar padding interno uniforme;
- separar visualmente título, descripción y acción;
- aplicar sombra ligera para distinguir el bloque del fondo;
- no saturar la tarjeta con demasiadas acciones;
- mantener consistencia de bordes y proporciones entre tarjetas del mismo tipo.
Este patrón se aplica tanto en el Landing Page como en el dashboard de la aplicación.
 
**Alertas y retroalimentación visual**
 
La guía define alertas con codificación por color y por ícono. Se distinguen al menos tres casos:
 
- operación exitosa;
- advertencia;
- error.
Estas alertas permiten comunicar el estado del sistema sin depender solo del texto. En entornos web, esta decisión mejora la detección rápida de eventos y reduce ambigüedad al ejecutar acciones como guardar, iniciar sesión o procesar información.
 
**Iconografía e imágenes**
 
La iconografía empleada es lineal, simple y consistente con el tema de seguridad doméstica. Se usa para representar funciones como monitoreo, control remoto, prevención, alertas y configuración. Los íconos no compiten visualmente con los títulos ni con las acciones principales.
 
Respecto a imágenes, la propuesta utiliza imágenes limpias y realistas. En el Landing Page se incluyen ilustraciones y fotografías relacionadas con el hogar y la vigilancia. Estas imágenes cumplen función de apoyo visual, no de contenido principal. Por ello, siempre se ubican subordinadas a la jerarquía funcional de la pantalla.

![](./assets/imagen12-style-guidelines.png)

**Jerarquía de contenido en web**
 
La interfaz web de SafeHome utiliza una jerarquía visual clara basada en:
 
- tamaño tipográfico;
- contraste de color;
- uso de bloques oscuros para destacar secciones clave;
- separación mediante espacios en blanco;
- agrupación por tarjetas y contenedores.
En el Landing Page, la sección principal da prioridad al nombre del producto, propuesta de valor y botón principal. Luego se presentan servicios y planes. En la aplicación, la prioridad cambia hacia métricas del sistema, visualización de cámaras y accesos de control rápido.
 
**Criterios de interacción**
 
Los principales criterios de interacción definidos para la web son:
 
- las acciones primarias deben ser visibles sin esfuerzo;
- el usuario debe identificar fácilmente dónde hacer clic;
- cada estado interactivo debe tener respuesta visual;
- la navegación debe requerir el menor número de pasos posible;
- los elementos interactivos deben mantener tamaño suficiente para uso en pantallas táctiles y de escritorio.
Estos criterios son consistentes con un producto orientado a monitoreo y control del hogar, donde la rapidez de reconocimiento y la claridad operativa son prioritarias.
 
**Accesibilidad e inclusión en web**
 
La propuesta considera reglas básicas de diseño inclusivo aplicadas a la interfaz web:
 
- contraste suficiente entre fondo y texto;
- jerarquías tipográficas diferenciadas;
- botones con tamaño reconocible;
- etiquetas claras en navegación y formularios;
- distribución ordenada del contenido para reducir carga cognitiva.
Estas decisiones no modifican la estética del sistema, pero sí mejoran su uso por parte de personas con distintas condiciones de lectura, atención o acceso desde distintos dispositivos.

![](./assets/imagen13-style-guidelines.png)

## 4.2. Information Architecture

### 4.2.1. Organization Systems

La arquitectura de información de SafeHome se organiza combinando sistemas de organización jerárquica, secuencial y, en algunos casos, cronológica o matricial, según el tipo de información y la tarea que el usuario necesita realizar. Esta decisión responde a la necesidad de ofrecer una experiencia clara tanto en la zona pública del producto como en la zona privada de monitoreo del hogar. SafeHome cuenta con una parte informativa orientada a los visitantes y una parte operativa enfocada en usuarios que administran dispositivos, revisan alertas y monitorean eventos de seguridad en tiempo real.
 
En la Landing Page se aplicará principalmente una organización jerárquica, ya que el contenido se mostrará de acuerdo con su nivel de importancia visual: primero la propuesta de valor, luego los beneficios del sistema, los servicios disponibles, la explicación de funcionamiento, los testimonios, las preguntas frecuentes y finalmente la información de contacto. Asimismo, en la sección "Cómo funciona" se empleará una organización secuencial, ya que el objetivo es explicar paso a paso cómo SafeHome monitorea el hogar y genera alertas. En esta zona pública, la información se categorizará por tópicos, separando claramente beneficios, servicios, testimonios, preguntas frecuentes y contacto. Adicionalmente, parte del contenido podrá presentarse según audiencia, considerando que el proyecto está dirigido a jóvenes adultos independientes, familias urbanas y propietarios de inmuebles en alquiler.
 
En el proceso de registro e inicio de sesión se utilizará una organización secuencial, ya que el usuario debe seguir un flujo ordenado para comenzar a usar la plataforma: acceder, registrarse o iniciar sesión e ingresar al sistema. Esta estructura paso a paso facilita la comprensión del recorrido inicial y reduce errores en el acceso.
 
Dentro de la aplicación web principal, la organización será mayormente jerárquica y por tópicos. El dashboard principal priorizará visualmente la información crítica, mostrando primero el estado general del hogar y las alertas más relevantes. A partir de este núcleo se agruparán los módulos en categorías funcionales, tales como dispositivos de seguridad, estado del hogar, alertas, eventos en tiempo real, historial, perfil/configuración y soporte. Esta categorización por tópicos permite que el usuario identifique rápidamente dónde realizar cada acción principal dentro del sistema.
 
En el módulo de eventos e historial se aplicará una categorización cronológica, ya que los incidentes de seguridad deben mostrarse en función de la fecha y hora en que ocurrieron. Además, estos eventos también podrán organizarse por tópicos, diferenciando el tipo de incidente detectado, como intrusión, humo, fuga de gas o anomalías en los servicios del hogar. En caso de presentarse mediante tablas o paneles comparativos, también podrá emplearse una organización matricial, relacionando variables como dispositivo, tipo de evento, estado y momento de ocurrencia.
 
[https://www.figma.com/board/ekvGCZkbyE4cyCkpUJp4BR/Untitled?node-id=0-1&t=TtPDIWI59f4syduq-1](https://www.figma.com/board/ekvGCZkbyE4cyCkpUJp4BR/Untitled?node-id=0-1&t=TtPDIWI59f4syduq-1)

![](./assets/Organization-Systems.png)

### 4.2.2. Labeling Systems

El sistema de etiquetado de SafeHome se define con base en claridad, brevedad y consistencia. Las etiquetas se redactan con el menor número de palabras posible para evitar ambigüedad y reducir el tiempo de reconocimiento por parte del usuario. Este criterio sigue la indicación de representar los conjuntos de información mediante etiquetas simples y asociaciones claras entre secciones, acciones y contenidos.
 
**Landing Page**
 
En el Landing Page se emplean etiquetas de exploración y conversión. Las principales son:
 
- Inicio
- Servicios
- Ver planes
- Iniciar sesión
Estas etiquetas aparecen en la navegación principal y representan secciones concretas del contenido. "Inicio" remite a la portada del producto. "Servicios" agrupa las funcionalidades principales ofrecidas por la plataforma. "Ver planes" dirige a la comparación comercial entre opciones disponibles. "Iniciar sesión" conecta al visitante con la parte operativa del sistema.
 
Dentro del contenido también se utilizan etiquetas breves asociadas al producto y a la conversión:
 
- SafeHome
- Monitoreo inteligente 360°
- FREE (essential)
- PREMIUM
- Empieza ahora
- Comparar planes
Estas etiquetas no describen en exceso; solo identifican bloques, beneficios o acciones principales.
 
**Web Application**
 
En la Web Application se utilizan etiquetas operativas orientadas a módulos. Las principales son:
 
- Inicio
- Cámaras
- Dispositivos
- Eventos
- Alertas
- Historial
- Configuración
- Cerrar sesión
Estas etiquetas corresponden a grupos funcionales del sistema y permiten acceder a vistas específicas del panel de control. Cada etiqueta mantiene relación directa con el contenido mostrado dentro del módulo.
 
**Formularios y acciones**
 
En formularios y acciones de acceso se usan etiquetas cortas y reconocibles:
 
- Correo electrónico
- Contraseña
- Recordarme
- ¿Olvidaste tu contraseña?
- Crear cuenta
- Iniciar sesión
En botones y CTAs se mantiene la misma lógica:
 
- Empieza ahora
- Ver planes
- Comparar planes
- Crear cuenta
- Iniciar sesión
**Principios aplicados**
 
- Mínimo número de palabras: cada etiqueta nombra una sección o acción sin explicaciones largas.
- Consistencia semántica: el mismo concepto mantiene el mismo nombre en toda la interfaz.
- Diferenciación por contexto: en el Landing Page predominan etiquetas de exploración; en la aplicación predominan etiquetas operativas.
- Relación directa etiqueta-acción: el usuario puede anticipar qué encontrará al hacer clic.


### 4.2.3. SEO Tags and Meta Tags

Para SafeHome se definen SEO Tags y Meta Tags para las principales páginas del Landing Page y para las vistas base de la Web Application. Como mínimo se incluyen Title, Meta Description, Keywords y Author.
 
**Landing Page - Inicio**
 
- Title: SafeHome | Seguridad y monitoreo inteligente para el hogar
- Meta Description: SafeHome es una plataforma web de seguridad doméstica que permite supervisar el hogar, conocer servicios y revisar planes desde una interfaz clara y responsive.
- Keywords: SafeHome, seguridad del hogar, monitoreo inteligente, hogar seguro, vigilancia web, plataforma de seguridad doméstica
- Author: Equipo SafeHome
**Landing Page - Servicios**
 
- Title: Servicios | SafeHome
- Meta Description: Conoce los servicios de SafeHome para monitoreo del hogar, control de dispositivos y prevención de incidentes desde una solución web de seguridad doméstica.
- Keywords: servicios SafeHome, monitoreo del hogar, control de dispositivos, prevención de incidentes, seguridad doméstica, vigilancia inteligente
- Author: Equipo SafeHome
**Landing Page - Planes**
 
- Title: Planes | SafeHome
- Meta Description: Revisa los planes Free y Premium de SafeHome y compara sus características para elegir la opción adecuada para tu hogar.
- Keywords: planes SafeHome, plan free, plan premium, precios seguridad hogar, monitoreo doméstico, suscripción SafeHome
- Author: Equipo SafeHome
**Web Application - Iniciar sesión**
 
- Title: Iniciar sesión | SafeHome
- Meta Description: Accede a SafeHome para gestionar cámaras, dispositivos, alertas y eventos del hogar desde una plataforma centralizada.
- Keywords: login SafeHome, iniciar sesión SafeHome, gestión del hogar, alertas de seguridad, cámaras y dispositivos
- Author: Equipo SafeHome
**Web Application - Dashboard**
 
- Title: Dashboard | SafeHome
- Meta Description: Visualiza el estado general del hogar con el panel de control de SafeHome mediante cámaras, dispositivos, alertas e historial.
- Keywords: dashboard SafeHome, panel de control, cámaras del hogar, dispositivos inteligentes, alertas del hogar, historial de eventos
- Author: Equipo SafeHome
**Criterios aplicados**
 
- Los títulos usan el nombre del producto y la función concreta de la página.
- Las descripciones resumen contenido real de cada vista.
- Las keywords se relacionan con la funcionalidad observada en el sistema.
- El autor se mantiene uniforme en todas las páginas.

### 4.2.4. Searching Systems

El sistema de búsqueda de SafeHome se plantea de forma distinta para el Landing Page y para la Web Application. La guía pide especificar qué medios de ayuda se brindarán al usuario para buscar datos, qué filtros tendrá y cómo se verán los resultados.
 
**Landing Page**
 
En el Landing Page no se implementa una barra de búsqueda principal. Esto se debe a que el volumen de información es reducido y está organizado en bloques directos: inicio, servicios, planes e inicio de sesión. Por ello, la localización del contenido se resuelve mediante navegación superior, botones de acción y scroll vertical.
 
La ausencia de buscador en esta parte no afecta la localización del contenido porque la arquitectura del Landing Page es corta y secuencial.
 
**Web Application**
 
En la Web Application sí se propone búsqueda dentro de módulos específicos del sistema. El objetivo es ubicar información operativa sin recorrer manualmente todas las secciones.
 
Búsqueda en Cámaras: permite localizar cámaras por nombre de cámara, ambiente y estado. Ejemplos de valores: **Sala**, **Entrada**, **Cocina**, **Activa**, **Desconectada**.
 
Búsqueda en Dispositivos: permite localizar dispositivos por nombre, tipo de dispositivo y estado de conexión. Ejemplos: sensor, alarma, cámara, foco, activo, inactivo.
 
Búsqueda en Eventos y Alertas: permite localizar registros por fecha, tipo de evento, prioridad y estado. Ejemplos: alerta crítica, evento resuelto, pendiente, reciente.
 
**Filtros propuestos**
 
Los filtros principales del sistema son:
 
- **Estado**
- **Tipo**
- **Fecha**
- **Ambiente**
- **Prioridad**
Estos filtros se aplican según el módulo. No todos aparecen en todas las vistas.
 
**Visualización de resultados**
 
Los resultados se muestran en tarjetas o listados según el contenido del módulo. Cada resultado debe presentar como mínimo:
 
- nombre o título del elemento;
- estado actual;
- indicador visual;
- referencia temporal cuando corresponda.
En alertas y eventos, los resultados se ordenan por criterio temporal. En cámaras y dispositivos, los resultados se muestran agrupados por módulo y con prioridad visual al estado del elemento.
 
**Criterios aplicados**
 
- búsqueda orientada a tareas;
- filtros simples y visibles;
- resultados con lectura rápida;
- separación por módulo para evitar sobrecarga.

### 4.2.5. Navigation Systems

El sistema de navegación de SafeHome define las acciones y técnicas mediante las cuales el usuario recorre el Landing Page y accede a las funciones de la Web Application. Esta sección debe explicar cómo los usuarios irán avanzando por el contenido y cómo las rutas principales apoyan el cumplimiento de sus objetivos.
 
**Landing Page**
 
El Landing Page utiliza un **menú superior visible** con las siguientes opciones:
 
- **Inicio**
- **Servicios**
- **Ver planes**
- **Iniciar sesión**
Esta navegación superior permite acceso directo a las partes principales del sitio y evita menús profundos. El usuario puede desplazarse entre secciones clave del producto sin abandonar el flujo general de exploración.
 
Técnicas de navegación en el Landing Page:
 
- **Navegación global superior:** se mantiene visible en la parte superior y concentra las rutas principales de exploración.
- **Navegación secuencial por scroll:** el contenido se organiza verticalmente desde la presentación del producto hasta la comparación de planes y el acceso a login.
- **CTA contextuales:** botones como **Empieza ahora** y **Ver planes** aceleran el avance hacia acciones de conversión.
**Web Application**
 
La Web Application utiliza un **menú lateral persistente** para el acceso a módulos. Las opciones principales observadas en el sistema son:
 
- **Inicio**
- **Cámaras**
- **Dispositivos**
- **Eventos**
- **Alertas**
- **Historial**
- **Configuración**
- **Cerrar sesión**
Esta navegación lateral mantiene visibles los módulos más importantes del sistema mientras el usuario opera dentro del dashboard. El cambio entre secciones se realiza sin romper el contexto general del panel.
 
Técnicas de navegación en la Web Application:
 
- **Sidebar persistente:** permite pasar de un módulo a otro de forma directa.
- **Dashboard como nodo principal:** la vista de inicio concentra accesos rápidos, estados generales y resumen del sistema.
- **Jerarquía por prioridad operativa:** las funciones relacionadas con monitoreo, cámaras y alertas se ubican en primer nivel.
**Mobile Web**
 
En la versión mobile del Landing Page, la navegación mantiene las mismas opciones principales, pero reorganizadas en un formato compacto y de lectura rápida. La estructura sigue siendo secuencial y vertical, priorizando scroll continuo, botones amplios y bloques apilados.
 
**Criterios aplicados**
 
- pocas opciones por nivel;
- rutas directas;
- navegación visible;
- estructura consistente entre desktop y mobile;
- prioridad a acciones principales y módulos clave.

## 4.3. Landing Page UI Design

La propuesta de UI del Landing Page de SafeHome traduce las decisiones del Design System y de la arquitectura de información a una interfaz visual concreta. Según la guía, esta sección debe iniciar explicando cómo las decisiones de diseño y organización del contenido se convierten en una propuesta de interfaz para el Landing Page.
 
El Landing Page de SafeHome se organiza en una secuencia clara de vistas: Inicio, Servicios, Planes e Iniciar sesión. Esta estructura responde a un recorrido corto: presentación del producto, explicación de funcionalidades, comparación comercial y acceso a la plataforma.
 
**Estructura visual general**
 
La propuesta utiliza:
 
- encabezado con navegación principal;
- bloques de contenido separados por secciones;
- tarjetas para agrupar información;
- botones de llamada a la acción;
- imágenes e ilustraciones de apoyo;
- adaptación responsive para desktop y mobile.
La primera vista presenta la marca SafeHome, una breve propuesta de valor y un botón de acción principal. La segunda vista muestra los servicios del sistema mediante tarjetas informativas e íconos. La tercera vista compara los planes disponibles. La cuarta vista permite acceder al sistema mediante un formulario de inicio de sesión.
 
**Aplicación del Design System**
 
La UI aplica directamente la guía de estilo ya definida:
 
- color turquesa para acciones principales;
- bloques oscuros para resaltar información importante;
- fondos claros para lectura del contenido;
- tipografía uniforme en títulos, subtítulos y botones;
- bordes redondeados y tarjetas consistentes.
**Jerarquía de contenido**
 
La jerarquía visual sigue este orden:
 
- marca y propuesta principal;
- beneficios y servicios;
- comparación de planes;
- acceso al sistema.
Este orden se mantiene tanto en desktop como en mobile, cambiando solo la distribución espacial de los elementos.
 
**Adaptación responsive**
 
En desktop, la interfaz aprovecha mayor ancho para mostrar contenido en paralelo. En mobile, los mismos bloques se apilan verticalmente. No se cambia el contenido principal; solo se reorganiza la disposición para mantener legibilidad y continuidad de navegación.

### 4.3.1. Landing Page Wireframe

Esta sección presenta los wireframes del Landing Page para Desktop Web Browser y Mobile Web Browser. La guía indica que aquí debe evidenciarse la aplicación de principios de diseño, arquitectura de información y organización del contenido.
 
Los wireframes del Landing Page de SafeHome están compuestos por cuatro vistas principales:
 
- 01. Landing Inicio
- 02. Landing Servicios
- 03. Landing Planes
- 04. Iniciar sesión
**Wireframe Desktop**
 
01. Landing Inicio
El wireframe muestra una barra superior con navegación principal y, debajo, un bloque principal dividido en dos áreas. En la primera se ubican el nombre del producto, una breve descripción y el botón Empieza ahora. En la segunda se coloca una ilustración asociada al hogar y accesos complementarios.

![](./assets/Landing-imagen1.png)
 
3. Landing Servicios
El wireframe presenta una sección dedicada a los servicios del sistema. Se observa un bloque con título, subtítulo e íconos que representan funciones como detección, control y prevención. A un lado se incorpora una imagen de apoyo.

![](./assets/Landing-imagen2.png)
 
5. Landing Planes
El wireframe organiza la comparación comercial mediante dos bloques: FREE (essential) y PREMIUM. Cada uno contiene lista resumida de características, precio y botón de acción.

![](./assets/Landing-imagen3.png)
 
7. Contáctanos
El wireframe incorpora la pantalla de contacto como parte del flujo del Landing Page. Se observa un formulario centrado con campos sobre datos personales, correo electrónico y mensaje.

![](./assets/Landing-imagen4.png)

### 4.3.2. Landing Page Mock-up

Aquí presentamos los mock-ups del Landing Page de SafeHome para desktop y mobile. La guía indica que en esta parte debe evidenciarse la aplicación de principios de diseño, arquitectura de información y del Design System definido para el producto.
 
Los mock-ups desarrollan visualmente los wireframes y muestran la versión con color, tipografía, imágenes, iconografía y componentes finales.
 
**Mock-up Desktop**
 
01. Landing Inicio
Se aplica un bloque visual oscuro para destacar la identidad del producto y la propuesta principal. El botón turquesa resalta la acción prioritaria. A la derecha se ubica la ilustración del hogar, que cumple función de apoyo visual.

![](./assets/Landing-imagen5.png)
 
3. Landing Servicios
La sección utiliza una combinación de fondo claro, tarjetas informativas, iconografía lineal y una imagen de apoyo. El título de la sección se resalta con alto contraste y la información se distribuye en bloques fáciles de escanear.

![](./assets/Landing-imagen6.png)
 
5. Landing Planes
Los planes Basic Plan y Premium se diferencian mediante contraste visual y estructura de tarjetas. Cada plan presenta beneficios listados, precio y botón de acción en la parte inferior.

![](./assets/Landing-imagen7.png)
 
**Relación entre wireframe y mock-up**
 
El mock-up mantiene la estructura definida en el wireframe. La diferencia está en el nivel de fidelidad visual. Se conservan:
 
- las mismas vistas;
- el mismo orden de contenido;
- las mismas acciones;
- la misma lógica de navegación.
El cambio principal es la incorporación de color, imágenes, tipografía aplicada y estilo final de botones, tarjetas y formularios.

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

En esta sección se presentan los wireframes de media fidelidad para la aplicación web **SafeHome**. El diseño se ha concebido bajo un enfoque funcional y minimalista, utilizando una paleta de colores en escala de grises para centrar la validación en la estructura y usabilidad antes que en la estética visual. La propuesta garantiza una experiencia consistente tanto en entornos de escritorio como en dispositivos móviles mediante un diseño responsivo.
 
- **Gestión de Acceso y Recuperación:** Este flujo se centra en la **Simplicidad**. Los formularios presentan campos claramente etiquetados con validaciones en tiempo real para reducir errores. Se incluye una pantalla de feedback para confirmar acciones exitosas, reforzando la confianza del usuario.

![](./assets/Wireframe-Web-App-1.png)
![](./assets/Wireframe-Web-App-2.png)
![](./assets/Wireframe-Web-App-3.png)
![](./assets/Wireframe-Web-App-4.png)

- **Centro de Control e Información Global:** Es el núcleo del sistema. La **Arquitectura de Información** prioriza el estado de seguridad en la zona superior. El Dashboard utiliza tarjetas (cards) para resumir dispositivos y alertas, permitiendo una visión de 360 grados de la vivienda en una sola mirada.

![](./assets/Wireframe-Web-App-5.png)
![](./assets/Wireframe-Web-App-6.png)
  
- **Gestión de Ecosistema IoT:** Se aplica el principio de **Consistencia**. El uso de filtros y buscadores facilita la escalabilidad del sistema (cuando el usuario tiene muchos sensores). El flujo de registro utiliza un diseño limpio para evitar el abandono durante la configuración del hardware.

![](./assets/Wireframe-Web-App-7.png)
![](./assets/Wireframe-Web-App-8.png)
![](./assets/Wireframe-Web-App-9.png)

- **Monitorización de Alertas y Eventos:** Se diferencia visualmente el "Tiempo Real" (dinámico) del "Historial" (tabular/estático). En el detalle de alertas, se aplica **Jerarquía Visual** para destacar las recomendaciones de seguridad y acciones rápidas (atender/ignorar).

![](./assets/Wireframe-Web-App-10.png)
![](./assets/Wireframe-Web-App-11.png)
![](./assets/Wireframe-Web-App-12.png)
![](./assets/Wireframe-Web-App-13.png)
![](./assets/Wireframe-Web-App-14.png)
- **Personalización y Soporte Técnico:** La configuración está categorizada por bloques lógicos (seguridad, notificaciones, hogar) para facilitar la navegación. La sección de soporte ofrece múltiples canales de ayuda, reduciendo la fricción en caso de fallos técnicos.

![](./assets/Wireframe-Web-App-15.png)
![](./assets/Wireframe-Web-App-16.png)
![](./assets/Wireframe-Web-App-17.png)
![](./assets/Wireframe-Web-App-18.png)

### 4.4.2. Web Applications Wireflow Diagrams

Contenido de la sección.

### 4.4.3. Web Applications Mock-ups

Contenido de la sección.

### 4.4.4. Web Applications User Flow Diagrams

Contenido de la sección.

## 4.5. Web Applications Prototyping

Contenido de la sección.

## 4.6. Domain-Driven Software Architecture

Contenido de la sección.

### 4.6.1. Design-Level Event Storming

Contenido de la sección.

### 4.6.2. Software Architecture Context Diagram

Contenido de la sección.

### 4.6.3. Software Architecture Container Diagrams

Contenido de la sección.

### 4.6.4. Software Architecture Components Diagrams

Contenido de la sección.

## 4.7. Software Object-Oriented Design

Contenido de la sección.

### 4.7.1. Class Diagrams

Contenido de la sección.

## 4.8. Database Design

Contenido de la sección.

### 4.8.1. Database Diagrams

Contenido de la sección.

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

Contenido de la sección.

### 5.1.1. Software Development Environment Configuration

Contenido de la sección.

### 5.1.2. Source Code Management

Contenido de la sección.

### 5.1.3. Source Code Style Guide & Conventions

Contenido de la sección.

### 5.1.4. Software Deployment Configuration

Contenido de la sección.

## 5.2. Landing Page, Services & Applications Implementation

Contenido de la sección.

### 5.2.1. Sprint 1

Contenido de la sección.

#### 5.2.1.1. Sprint Planning 1

Contenido de la sección.

#### 5.2.1.2. Aspect Leaders and Collaborators

Contenido de la sección.

#### 5.2.1.3. Sprint Backlog 1

Contenido de la sección.

#### 5.2.1.4. Development Evidence for Sprint Review

Contenido de la sección.

#### 5.2.1.5. Execution Evidence for Sprint Review

Contenido de la sección.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Contenido de la sección.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Contenido de la sección.

#### 5.2.1.8. Team Collaboration Insights during Sprint


Durante el Sprint 1, el equipo SoftTech trabajó de manera colaborativa en la primera versión de la Landing Page de SafeHome. Para ello, se utilizó GitHub como plataforma de control de versiones, permitiendo registrar los aportes de cada integrante mediante commits individuales.

| Integrante | Actividad |
|---|---|
| Briguite Eryka Carhuaz Centeno (U20241D932) | Implementación de la primera versión del archivo HTML para las secciones principales de la Landing Page. |
| Jaime Forcelledo, Gonzalo Alexander (U202319329) | Desarrollo de la primera versión de estilos de la página mediante CSS. |
| Mauricio Jared Padilla Merino (U201911393) | Implementación del código JavaScript para el cambio de idioma y animaciones de la Landing Page. |
| Valeria Alexandra Rojas Gómez (U202411373) | Implementación de la segunda versión del archivo HTML, agregación de archivos para el cambio de idioma y desarrollo del CSS responsive. |
| Pillaca Vidal, Luis Ángel (U202315654) | Desarrollo de la segunda versión de estilos de la página. |

Como se puede observar en la siguiente captura, el equipo colaboró en la creación de la primera versión de la Landing Page utilizando tecnologías open-source como HTML, CSS y JavaScript. Además, GitHub permitió evidenciar la participación de los integrantes mediante commits, contributors y el historial de cambios del repositorio.

<p align="center">
  <img src="assets/Git-Repository-Contributors1.png" alt="Contributors del repositorio SafeHome Landing Page" width="750"/>
</p>

Asimismo, se evidencia la distribución de contribuciones realizadas por cada integrante durante el Sprint 1. Esta información permite visualizar la participación del equipo en el desarrollo del proyecto y sustentar el trabajo colaborativo realizado en el repositorio.

<p align="center">
  <img src="assets/Git-Repository-Contributors2.png" alt="Insights de contributors del repositorio SafeHome Landing Page" width="750"/>
</p>

| Integrante | Usuario de GitHub |
|---|---|
| Briguite Eryka Carhuaz Centeno (U20241D932) | briicarhuaz |
| Jaime Forcelledo, Gonzalo Alexander (U202319329) | gonzalojaimeforcelledo |
| Mauricio Jared Padilla Merino (U201911393) | MauricioPadilla07 |
| Valeria Alexandra Rojas Gómez (U202411373) | ValeriaAler |
| Pillaca Vidal, Luis Ángel (U202315654) | RiBlankRam |

---

# Conclusiones

Contenido de conclusiones.

---

# Bibliografía

Contenido de bibliografía en formato APA 7.

---

# Anexos

Contenido de anexos.
