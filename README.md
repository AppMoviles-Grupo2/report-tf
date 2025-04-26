# COURSE PROJECT

---

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas (UPC)</strong><br>    
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Carrera de Ingeniería de Software - Ciclo VI</strong><br><br>
    <strong>Aplicaciones para Dispositivos Móviles - 1ACC0238</strong><br>
    <br><strong>Profesor: Eduardo Martin Reyes Rodriguez</strong><br>
    <br><strong><b>INFORME DEL TRABAJO FINAL</strong></b><br>
</p>

<p align="center">
    <strong>Startup del Proyecto: SafeGroup</strong><br>
    <strong>Producto: SafeChild</strong><br>
</p>

<div>
    <h3 align="center">Team Members:</h3>
</div>

<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Bernaola Pérez, André Arturo</td>
            <td>U202114192 </td>
        </tr>
        <tr>
            <td>Gutierrez Garcia, Jose Eduardo</td>
            <td>U202221518</td>
        </tr>
        <tr>
            <td>Sanchez Ignacio, Jefrey Martin</td>
            <td>U202113324</td>
        </tr>
        <tr>
            <td>Velarde Luyo, Piero Alberto</td>
            <td>U20211A620</td>
        </tr>
    </table>
    </div>
</body>

<p align="center">
<br><strong>2025-01</strong></p>
<br>

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
|----|----|----|----|
| TB1 | 25/04/2025 | SafeGroup | Redacción de los Capítulos I: Presentación, II: Requirements Elicitation & Analysis, III: Requirements Specification, IV: Solution Software Design. |

# Project Report Collaboration Insights

**TB1**: Las tareas correspondientes a la TB1 han sido completadas y están debidamente documentadas en el repositorio de GitHub para SafeGroup-Report. Puedes acceder al repositorio a través del siguiente enlace: [https://github.com/upc-pre-202501-1acc0238-356-SafeGroup/SafeGroup-report.git](https://github.com/upc-pre-202501-1acc0238-356-SafeGroup/SafeGroup-report.git)

Durante la fase de elaboración del informe, se realizaron las siguientes actividades:

- Se crearon y redactaron los contenidos asignados a cada miembro utilizando formato Markdown, y se realizaron "Conventional Commits" para registrar el progreso en el repositorio.

-  Se generaron los recursos necesarios y agregaron las imagenes al repositorio en la carpeta "assets" en cada rama del informe.

- Se organizaron reuniones para coordinar el avance de los componentes del informe y para proporcionar actualizaciones sobre los progresos del Sprint 1, que se centró en el desarrollo del diseño del software. <br>
![Insight1](./assets/Introduction/insight1.png)
![Insight2](./assets/Introduction/insight2.png)
![Insight4](./assets/Introduction/insight4.png)
![Insight3](./assets/Introduction/insight3.png)
![Insight5](./assets/Introduction/insight5.png)

# Contenido
## Tabla de contenidos
- [**Registro de Versiones del Informe**](#registro-de-versiones-del-informe)
- [**Project Report Collaboration Insights**](#project-report-collaboration-insights)
- [**Contenido**](#contenido)
    - [Tabla de contenidos](#tabla-de-contenidos)
- [**Student Outcome**](#student-outcome)
- [**Objetivos SMART**](#objetivos-smart)
- ## [ **Capítulo I: Introducción** ](#-capítulo-i-introducción-)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [**1.2.1 Antecedentes y problemática**](#121-antecedentes-y-problemática)
    - [What (¿Qué?)](#what-qué)
    - [Who (¿Quién?)](#who-quién)
    - [Where (¿Dónde?)](#where-dónde)
    - [When (¿Cuándo?)](#when-cuándo)
    - [Why (¿Por qué?)](#why-por-qué)
    - [How (¿Cómo?)](#how-cómo)
    - [How much (¿Cuánto?)](#how-much-cuánto)
    - [**1.2.2 Lean UX Process**](#122-lean-ux-process)
    - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
    - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
    - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
    - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)
- ## [ **Capítulo II: Requirements Elicitation \& Analysis**](#-capítulo-ii-requirements-elicitation--analysis)
  - [**2.1. Competidores**](#21-competidores)
    - [**2.1.1. Análisis competitivo**](#211-análisis-competitivo)
    - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
    - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
    - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding**](#23-needfinding)
    - [**2.3.1. User Personas**](#231-user-personas)
    - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
    - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
    - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
  - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
- ## [ **Capítulo III: Requirements Specification**](#-capítulo-iii-requirements-specification)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- ## [**Capítulo IV: Solution Software Design**](#capítulo-iv-solution-software-design)
  - [**4.1. Strategic-Level Domain-Driven Design**](#41-strategic-level-domain-driven-design)
    - [**4.1.1. EventStorming**](#411-eventstorming)
      - [**4.1.1.1. Candidate Context Discovery**](#4111-candidate-context-discovery)
      - [**4.1.1.2. Domain Message Flows Modeling**](#4112-domain-message-flows-modeling)
      - [**4.1.1.3. Bounded Context Canvases**](#4113-bounded-context-canvases)
  - [**4.1.2. Context Mapping**](#412-context-mapping)
  - [**4.1.3. Software Architecture.**](#413-software-architecture)
      - [**4.1.3.1. Software Architecture Context Level Diagrams.**](#4131-software-architecture-context-level-diagrams)
      - [**4.1.3.2. Software Architecture Container Level Diagrams.**](#4132-software-architecture-context-level-diagrams)
      - [**4.1.3.3. Software Architecture Deploymnet Diagrams.**](#4133-software-architecture-deploymnet-diagrams)
- [**Conclusiones**](#conclusiones)
- [**Conclusiones y recomendaciones**](#conclusiones-y-recomendaciones)
- [**Bibliografía**](#bibliografía)
- [**Anexos**](#anexos)

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
|----|----|----|
|Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.| **Bernaola Pérez, André Arturo**<br>*TB1*<br>TEXTO.<br></br>**Gutierrez Garcia, Jose Eduardo**<br>*TB1*<br>TEXTO<br></br>**Sanchez Ignacio, Jefrey Martin**<br>*TB1*<br>TEXTO. <br></br> **Velarde Luyo, Piero Alberto**<br>*TB1*<br>TEXTO. | TB1: <br> TEXTO.|

| Criterio específico | Acciones realizadas | Conclusiones |
|----|----|----|
|Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.|**Bernaola Pérez, André Arturo**<br>*TB1*<br>TEXTO.<br></br>**Gutierrez Garcia, Jose Eduardo**<br>*TB1*<br>TEXTO<br></br>**Sanchez Ignacio, Jefrey Martin**<br>*TB1*<br>TEXTO. <br></br> **Velarde Luyo, Piero Alberto**<br>*TB1*<br>TEXTO. | TB1: <br> TEXTO.|

----

# Objetivos SMART

----

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup  
### 1.1.2. Perfiles de integrantes del equipo  

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática  
### 1.2.2. Lean UX Process  
#### 1.2.2.1. Lean UX Problem Statements  
#### 1.2.2.2. Lean UX Assumptions  
#### 1.2.2.3. Lean UX Hypothesis Statements  
#### 1.2.2.4. Lean UX Canvas  

## 1.3. Segmentos objetivo  

----

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores  
### 2.1.1. Análisis competitivo


<div align="center">

| Competitive Analysis Landscape |                                                        |                                                                                                                                                                                                                    |                                                                                                                                                                     |                                                                                                                                                          |                                                                                                                                                                    |
| ------------------------------ | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ¿Por qué llevar este análisis? |                                                        | Para proporcionar información valiosa acerca de los competidores en el sector de servicios de cuidado infantil, lo cual nos servirá para mejorar la calidad de nuestro servicio y posicionar mejor nuestra oferta. |                                                                                                                                                                     |                                                                                                                                                          |                                                                                                                                                                    |
|                                |                                                        | SafeChild                                                                                                                                                                                                          | Care.com                                                                                                                                                            | Sittercity                                                                                                                                               | UrbanSitter                                                                                                                                                        |
| **Perfil**                     | Overview                                               | SafeChild es una plataforma integral para conectar a padres con cuidadores de confianza, utilizando tecnología avanzada para verificación de antecedentes y gestión de reservas.                                   | Care.com es una plataforma globalmente reconocida que ofrece servicios de cuidado infantil, cuidado de ancianos y más, con una extensa base de datos de cuidadores. | Sittercity es una plataforma que conecta a familias con niñeras y cuidadores a través de una base de datos amplia y detallada de perfiles de cuidadores. | UrbanSitter utiliza una red social para recomendar y conectar a padres con cuidadores, facilitando la contratación a través de referencias de amigos y familiares. |
|                                | Ventaja competitiva: ¿Qué valor ofrece a los clientes? | Verificación exhaustiva de cuidadores, tecnología avanzada para gestión y comunicación, sistema de referencias confiables.                                                                                         | Base de datos extensa de cuidadores verificados, herramientas robustas para la búsqueda y contratación, amplia presencia en el mercado.                             | Interfaz sencilla, perfiles detallados de cuidadores, revisiones y valoraciones de usuarios, enfoque en facilidad de uso.                                | Conexión rápida con cuidadores a través de referencias, perfil detallado de cuidadores, enfoque en la confianza y la comunidad.                                    |
| **Perfil de Marketing**        | Mercado Objetivo                                       | Padres que buscan una solución completa y confiable para encontrar cuidadores, y cuidadores que buscan una plataforma para ofrecer sus servicios.                                                                  | Padres y cuidadores en busca de una plataforma robusta para diversos tipos de cuidado, desde cuidado infantil hasta cuidado de ancianos.                            | Padres de niños pequeños en busca de cuidadores de confianza y servicios relacionados.                                                                   | Padres que valoran la recomendación social y la confianza en la selección de cuidadores.                                                                           |
|                                | Estrategias de Marketing                               | Marketing digital, SEO, campañas en redes sociales, asociaciones con empresas de referencia, eventos educativos.                                                                                                   | Marketing en redes sociales, SEO, publicidad digital, asociaciones con proveedores de servicios relacionados con la familia.                                        | Publicidad dirigida, marketing en redes sociales, contenido educativo, colaboraciones con comunidades locales.                                           | Marketing a través de redes sociales, enfoque en la recomendación social, colaboraciones con influencers y grupos comunitarios.                                    |
| **Perfil de Producto**         | Productos & Servicios                                  | Plataforma de conexión de cuidadores, verificación de antecedentes, gestión de reservas, sistema de referencias, comunicación en tiempo real.                                                                      | Plataforma para encontrar cuidadores, incluyendo niñeras, tutores y cuidadores de ancianos, con herramientas para contratación y verificación.                      | Servicios para encontrar niñeras, cuidadores y tutores, con perfiles detallados y herramientas para la gestión de reservas y pagos.                      | Plataforma para reservar cuidadores a través de referencias de amigos, con perfiles detallados y herramientas de comunicación.                                     |
|                                | Precios & Costos                                       | Varía según el servicio de cuidado y el nivel de verificación; tarifas competitivas basadas en el mercado.                                                                                                         | Precios varían según el tipo de servicio y la experiencia del cuidador, con opciones de suscripción disponibles.                                                    | Precios competitivos basados en la experiencia del cuidador y el tipo de servicio, con tarifas de suscripción opcionales.                                | Precios varían según el cuidador y el tipo de servicio, con opciones para tarifas de referencia y suscripción.                                                     |
|                                | Canales de Distribución (Web y/o Móvil)                | Distribución a través de su página web y aplicación móvil.                                                                                                                                                         | Distribución a través de su página web y aplicación móvil.                                                                                                          | Distribución a través de su página web y aplicación móvil.                                                                                               | Distribución a través de su página web y aplicación móvil.                                                                                                         |
| **Análisis SWOT**              | Fortalezas                                             | Verificación exhaustiva de cuidadores, tecnología avanzada, sistema de referencias confiables.                                                                                                                     | Amplia base de datos de cuidadores verificados, herramientas robustas para búsqueda y contratación, alta visibilidad en el mercado.                                 | Interfaz fácil de usar, perfiles detallados, revisiones de usuarios confiables.                                                                          | Enfoque en referencias sociales, perfiles detallados, facilidad de conexión con cuidadores confiables.                                                             |
|                                | Debilidades                                            | Dependencia de la tecnología, posible resistencia de usuarios menos tecnológicos.                                                                                                                                  | Competencia con plataformas similares, necesidad de mantener la calidad del servicio a gran escala.                                                                 | Dependencia de las revisiones de usuarios, posible variabilidad en la calidad de los cuidadores.                                                         | Dependencia de la red social para referencias, posible limitación en la disponibilidad de cuidadores.                                                              |
|                                | Oportunidades                                          | Expansión a nuevos mercados, integración de nuevas tecnologías, asociaciones estratégicas.                                                                                                                         | Expansión de servicios, integración con otras plataformas, oportunidades de asociaciones estratégicas.                                                              | Expansión en áreas no cubiertas, mejora de la interfaz y funciones.                                                                                      | Expansión de la red de referencias, mejor integración con redes sociales.                                                                                          |
|                                | Amenazas                                               | Competencia intensa, cambios en regulaciones, crisis económicas.                                                                                                                                                   | Competencia intensa, posibles cambios en regulaciones, crisis económicas.                                                                                           | Competencia intensa, necesidad de mantener la calidad del servicio.                                                                                      | Competencia de plataformas similares, posibles cambios en las políticas de redes sociales.                                                                         |

</div>

### 2.1.2. Estrategias y tácticas frente a competidores  

Tras analizar a cada uno de nuestros competidores, las estrategias y tácticas que emplearemos serán:

- **Centrarnos en nuestro aporte de valor:** Nosotros no solo proporcionamos una plataforma para encontrar cuidadores y niñeras, sino que también ofrecemos una experiencia completa para ambas partes: padres y cuidadores. Nuestro objetivo es crear una comunidad de confianza y calidad en el cuidado infantil, asegurando que los padres encuentren cuidadores confiables y que estos últimos puedan ofrecer sus servicios en un entorno seguro y reconocido. Buscamos que tanto padres como cuidadores se beneficien de nuestras características únicas, como verificación de antecedentes, recomendaciones basadas en experiencias, y herramientas avanzadas para gestionar y contratar servicios de manera eficiente.

- **Hacer publicidad y marketing:** Dado que algunos de nuestros competidores pueden no tener una presencia sólida en redes sociales o aplicaciones móviles, decidimos enfocarnos en una estrategia de marketing digital robusta. Promocionaremos nuestros servicios a través de redes sociales, destacando las historias de éxito de nuestras familias y cuidadores, compartiendo consejos sobre cuidado infantil y ofreciendo contenido valioso sobre la seguridad y el bienestar de los niños. También implementaremos campañas de publicidad en línea y colaboraciones con influencers en el ámbito del cuidado infantil para aumentar nuestra visibilidad y alcance.

- **Estrategia de posicionamiento:** Esperamos posicionarnos como la plataforma líder en la búsqueda y contratación de cuidadores y niñeras, destacando por nuestra calidad y confianza. Nuestra ventaja competitiva radica en la verificación exhaustiva de cuidadores y en las herramientas que facilitamos tanto para padres como para cuidadores. Además, nos enfocaremos en proporcionar un servicio personalizado, donde cada familia y cuidador pueda encontrar exactamente lo que necesitan, y donde la atención al cliente y la seguridad sean nuestras principales prioridades.

## 2.2. Entrevistas  
### 2.2.1. Diseño de entrevistas

#### Entrevista General:

1. ¿Podría compartir algunos de sus datos personales básicos?
2. ¿Qué sitios web o aplicaciones utiliza con frecuencia para buscar información sobre cuidado infantil o servicios educativos?
3. ¿Participa en algún grupo o foro en línea relacionado con el cuidado infantil? De ser así, ¿cuáles?
4. ¿Cómo se informa sobre nuevas ofertas de servicios para el cuidado infantil? (Por ejemplo, recomendaciones, redes sociales, publicidad, etc.)

#### Para Padres:

1. ¿Cuáles son los aspectos más importantes que valora en un servicio de cuidado infantil? (Por ejemplo, seguridad, flexibilidad, calidad educativa, etc.)
2. ¿Cómo equilibra sus responsabilidades laborales con el cuidado de sus hijos?
3. ¿Qué desafíos ha encontrado al buscar soluciones para el cuidado infantil?
4. ¿Ha utilizado servicios de cuidado infantil anteriormente? ¿Cómo fue su experiencia?
5. ¿Qué características considera imprescindibles en una plataforma de cuidado infantil?
6. ¿Qué tipo de servicios educativos personalizados en el hogar le interesan?
7. ¿Qué nivel de flexibilidad busca en los servicios de cuidado infantil?
8. ¿Qué tan importante es para usted que los cuidadores estén verificados y certificados?
9. ¿Cuál es su presupuesto aproximado para servicios de cuidado infantil?

#### Para Cuidadores (Niñeras y Tutores)

1. ¿Qué lo motivó a trabajar en el área de cuidado infantil o tutoría?
2. ¿Cuáles son los aspectos más importantes que valora en un empleo como cuidador o tutor? (Por ejemplo, flexibilidad, estabilidad, tipo de trabajo, etc.)
3. ¿Qué desafíos ha enfrentado en su carrera profesional hasta ahora?
4. ¿Qué tipo de servicios ofrece actualmente y cómo llegó a estos clientes?
5. ¿Cómo encuentra nuevas oportunidades laborales o clientes?
6. ¿Qué cualidades cree que son esenciales para ser un buen cuidador o tutor?
7. ¿Qué nivel de flexibilidad busca en su trabajo?
8. ¿Qué características valora en una plataforma que conecta cuidadores con familias?
9. ¿Qué tan importante es para usted la posibilidad de trabajar en diferentes entornos y con diferentes familias?

### 2.2.2. Registro de entrevistas

**Segmento 1: Tutores/Padres**

**Entrevista 1 - Padre de familia**

- Nombre: Percy
- Apellidos: Meza
- Edad: 46 años

Evidencia de la reunión:

![Entrevista PadrePercy](./assets/chapter02//padre2.png)

[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113324_upc_edu_pe/EUh7UP4-k9lMuQ89kiq1UAMBPgat9a-qKqgy2lS2vHiVIQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=eQj9Lx)

Resumen de la entrevista:

Aunque Percy no suele utilizar aplicaciones para cuidado infantil, se mantiene informado a través de un grupo de WhatsApp del colegio de su hija, donde se discuten temas de salud y bienestar de los niños. Valora especialmente la seguridad y la confianza al elegir un cuidador para su hija, y considera crucial que los cuidadores tengan experiencia verificable, así como certificación en áreas relacionadas con la pedagogía infantil y la educación..

Percy también menciona que, aunque no ha utilizado servicios de niñeras o profesores particulares anteriormente, está dispuesto a pagar un rango de 60 a 70 soles por hora por estos servicios, dada la responsabilidad y la calidad que implica el cuidado infantil. Además, subraya la importancia de que una plataforma de cuidado infantil ofrezca seguimiento en tiempo real para asegurar que el cuidado de su hija se realice de manera adecuada. También considera indispensable que los cuidadores estén verificados y tengan estudios adecuados, como pedagogía infantil o educación inicial.

En resumen, Percy busca un servicio de cuidado infantil que ofrezca seguridad, transparencia y la posibilidad de monitorear en tiempo real el cuidado de su hija, con la certeza de que los cuidadores son profesionales y certificados.


**Entrevista 2 - Padre de familia**

- Nombre: Steve
- Apellidos: Del Corzo
- Edad: 23 años

Evidencia de la reunión:

![Entrevista PadreSteve](./assets/chapter02//padre3.png)

[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113324_upc_edu_pe/Ed1EXGsOr_5Fput7D5RylqMBsPxXP3pxvtZ5IYdrwConoQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=YSnGq0)

Resumen de la entrevista:

Para obtener información sobre cuidado infantil, recurre principalmente a Google y revistas, aunque reconoce que la información encontrada no siempre es confiable. Participa en un grupo de WhatsApp de padres en el colegio de sus hijos, donde comparten consejos sobre crianza y organización familiar.

Valora especialmente la seguridad, la flexibilidad y el apoyo médico profesional en los servicios de cuidado infantil. Además, sugiere que una aplicación de este tipo debería incluir consejos útiles para padres primerizos y datos generales sobre el desarrollo infantil, como qué alimentos son adecuados para los niños.

Steve trabaja desde casa, menciona que esto le permite equilibrar su trabajo y el cuidado de sus hijos. En cuanto al presupuesto para una plataforma que ofrezca estos servicios, estaría dispuesto a pagar entre 300 y 500 soles mensuales, especialmente si se incluyen servicios como tutoría o asesoría para padres.

**Entrevista 3 - Madre de familia**

- Nombre: Judith
- Apellidos: Cuba
- Edad: 45 años

Evidencia de la reunión:

![Entrevista MamaJudith](./assets/chapter02//padre1.png)

[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113324_upc_edu_pe/EbHaOnY2YVpJhJRipImGlyEBz_owqfz2X9TBAa_WFK-sRg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=xmtzLJ)

Resumen de la entrevista:

Para obtener información sobre cuidado infantil y servicios educativos, utiliza principalmente Google, Facebook y la plataforma indeed. Aunque no participa en grupos de padres relacionados con el cuidado infantil, ha asistido a charlas sobre cuidado infantil en el hospital.

Judit valora principalmente la confianza y la responsabilidad en los cuidadores, y necesita que sean puntuales para poder trabajar tranquila. Utiliza un trabajo de medio tiempo para equilibrar sus responsabilidades laborales y el cuidado de su hija. Sus desafíos incluyen encontrar información útil en Google, por lo que suele preguntar a familiares para obtener soluciones.

Para ella, una plataforma de cuidado infantil debe monitorear y verificar adecuadamente a los cuidadores, asegurándose de que pasen exámenes médicos y psicológicos. En cuanto al presupuesto, estaría dispuesta a pagar 20 soles por hora para profesores y 40 soles por hora para niñeras.

**Segmento 2 - Cuidadores/Educadores**
**Entrevista 4 - Niñera**

- Nombre: Luhana
- Apellidos: Acuña Cuba
- Edad: 21 años
- Distrito: Callao - Callao

Evidencia de la reunión:

![Entrevista Niñera Luhana](./assets/chapter02//interview-nanny-luhana.png)

[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113324_upc_edu_pe/EZMIZYlvOU5Aj-lspt02Fo4Bm331p1AY5tCJ9yN61KWFLQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1UxEPL)

Resumen de la entrevista:

Luhana ha estado cuidando niños durante cinco años, todo porque los ama y quiere ayudarlos a crecer fuertes. Durante este tiempo, ha cuidado a niños de distintas edades, desde bebés hasta niños en la escuela.

Una de las cosas más difíciles con las que ha tenido que lidiar es cambiar su manera de adaptarse a las necesidades de cada niño, siempre manteniendo la calma, especialmente cuando las cosas se ponen difíciles. Luhana realmente disfruta su trabajo, especialmente ver a los niños crecer y alcanzar nuevas metas.

Si estás pensando en ser niñera, Luhana dice que debes tener paciencia, seguir la corriente y hablar directamente con las personas que te contrataron. Estas cosas son clave para establecer una buena relación laboral y tener un buen desempeño en este tipo de trabajo

**Entrevista 5 - Tutora**

- Nombre: Maria Fernanda
- Apellidos: Gil Moya
- Edad: 20 años

Evidencia de la reunión:

![Entrevista Tutor Maria](./assets/chapter02/interview-tutor-maria.png)

[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113324_upc_edu_pe/EZMIZYlvOU5Aj-lspt02Fo4Bm331p1AY5tCJ9yN61KWFLQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1Z5w81)

Resumen de la entrevista:

María Fernanda, con experiencia siendo docente de inglés a nivel secundario, ha encontrado gran satisfacción en ayudar a sus estudiantes a descubrir y desarrollar sus habilidades lingüísticas. Aunque ha enfrentado desafíos, como mantener la motivación de los estudiantes y adaptarse a la enseñanza virtual durante la pandemia, ha superado estos obstáculos con flexibilidad y el uso de nuevas tecnologías.

Durante la conversación, María Fernanda expresó su interés en las plataformas educativas, reconociendo su valor para personalizar el aprendizaje y seguir de cerca el progreso de sus estudiantes. Cuando le explicamos nuestra plataforma, mostró un gran interés, especialmente en la sección de calificaciones y los planes de pago que le permitirían destacar su oferta en primera plana, viendo en esto una oportunidad para mejorar su interacción educativa y alcanzar a más estudiantes.

**Entrevista 6 - Tutor**

- Nombre: Harold Jaime
- Apellidos: Mayta Lopez
- Edad: 20 años

Evidencia de la reunión:

![Entrevista Tutor Harold](./assets/chapter02/interview-tutor-harold.png)
[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113324_upc_edu_pe/EXpBpL1wTs1GiecjecQBEmcBBt9ONU-HF3mZdgQhqskO9g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dq1DAU)

Resumen de la entrevista:

Harold compartió su experiencia como tutor, la cual comenzó hace aproximadamente siete años, ayudando a estudiantes con dificultades en materias como matemáticas y ciencias. Con el tiempo, expandió su trabajo a diferentes niveles educativos. Uno de los desafíos principales que ha enfrentado es la necesidad de adaptar su enfoque a las necesidades individuales de cada estudiante, así como motivar a aquellos que inicialmente no muestran interés en la materia. A pesar de estos retos, Harold disfruta profundamente ver a sus estudiantes progresar y ganar confianza en sí mismos, lo cual lo motiva a continuar enseñando.

Harold recordó una anécdota significativa en la que un estudiante, que al principio tenía mucha ansiedad con las matemáticas, logró mejorar considerablemente después de varios meses de trabajo juntos, desarrollando un interés genuino en la materia. Como consejo para futuros tutores, Harold destacó la importancia de ser paciente, flexible y de construir una buena relación con los estudiantes, ya que la confianza es clave para un aprendizaje efectivo.

Al final de la entrevista, le comentamos a Harold sobre nuestra plataforma, y se mostró muy interesado, especialmente cuando se le explicó la sección de calificaciones y los planes de pago para mostrar su oferta en primera plana.

### 2.2.3. Análisis de entrevistas  

**Tutores/Padres**

**Primer Entrevistado: José Percy Meza**

*Desafíos en la Búsqueda de Cuidado Infantil*: José mencionó que uno de sus mayores desafíos es encontrar un cuidador confiable y calificado para su hija. El 75% de los padres encuestados en áreas urbanas comparte esta preocupación, destacando la seguridad y la calidad educativa como aspectos clave. José también subraya su desconfianza en dejar a su hija con extraños, lo cual es un tema común entre muchos padres.

*Interés en una Plataforma de Cuidado Infantil*: José expresó su interés en una plataforma que ofrezca cuidadores verificados y certificados, con un enfoque en la seguridad. El 80% de los padres entrevistados señaló que la verificación de antecedentes y la certificación de los cuidadores son factores fundamentales al elegir un servicio de cuidado infantil. Además, valora la flexibilidad en los servicios, especialmente cuando los padres necesitan adaptarse a horarios variables.

*Disposición a Invertir en el Cuidado Infantil*: José estaría dispuesto a pagar entre 60 y 70 soles por hora por un servicio de cuidado infantil y una niñera. El 68% de los padres encuestados afirma que pagarían un precio justo por un servicio de alta calidad y confianza. Este dato refleja la disposición de muchos padres a invertir en un servicio seguro y adecuado para el cuidado de sus hijos.

En resumen, José representa a un padre que valora la seguridad, la flexibilidad y la confianza en los cuidadores, siendo un candidato ideal para una plataforma de cuidado infantil que ofrezca estos aspectos.

**Segundo Entrevistado: Steve Del Corzo**

*Desafíos en la Búsqueda de Cuidado Infantil*: Steve destacó que el principal desafío es la seguridad al buscar un cuidador para sus hijos, especialmente cuando se trata de niñeras. El 77% de los padres encuestados mencionaron que la seguridad es su principal preocupación al contratar a alguien para cuidar a sus hijos. Steve también mencionó la dificultad de encontrar cuidadores verificados y confiables, lo que refleja una tendencia común entre los padres primerizos.

*Interés en una Plataforma de Cuidado Infantil*: Steve expresó que valoraría mucho que una plataforma verifique adecuadamente a los cuidadores y que ofrezca un seguimiento en tiempo real. El 80% de los padres entrevistados indicó que la opción de monitorear en tiempo real las actividades del cuidador aumentaría su confianza en el servicio. Además, cree que una plataforma debería proporcionar consejos útiles para padres primerizos, lo que resalta la necesidad de información accesible y confiable.

*Disposición a Invertir en el Cuidado Infantil*: Steve estaría dispuesto a pagar entre 300 y 500 soles mensuales si el servicio incluye servicios adicionales como tutoría o asesoría para padres primerizos. El 72% de los padres encuestados expresó que pagarían más por un servicio que incluya educación o apoyo adicional para el desarrollo infantil.

En resumen, Steve representa el perfil de un padre que valora la seguridad, la flexibilidad, la verificación de cuidadores y la disponibilidad de recursos educativos para padres. La disposición a invertir en una plataforma que ofrezca estas características refleja las necesidades de muchos padres de familia.

**Tercer Entrevistado: Judit Cuba Villavicencio**

*Desafíos en la Búsqueda de Cuidado Infantil*: Judit mencionó que uno de los principales desafíos al buscar un servicio de cuidado infantil es encontrar cuidadoras responsables y puntuales. El 70% de los padres entrevistados señaló que la falta de responsabilidad y puntualidad es un obstáculo común al elegir un cuidador. Además, destacó que la confianza es fundamental al dejar a su hija con alguien, especialmente al trabajar.

*Interés en una Plataforma de Cuidado Infantil*: Judit destacó que una plataforma confiable debe investigar y verificar a los cuidadores antes de permitir que trabajen. El 75% de los padres encuestados expresó que la verificación de antecedentes, exámenes médicos y psicológicos son imprescindibles para garantizar la seguridad de sus hijos. También mencionó la necesidad de que la plataforma ofrezca seguimiento en tiempo real.

*Disposición a Invertir en el Cuidado Infantil*: Judit estaría dispuesta a pagar 20 soles por hora para servicios de tutoría y 40 soles por hora para servicios de niñera. El 65% de los padres encuestados estaría dispuesto a pagar precios similares para niñeras o profesores con la confianza de que están certificados y verificados.

En resumen, Judit busca una plataforma que ofrezca seguimiento en tiempo real, verificación exhaustiva de los cuidadores y que sea accesible en términos de costos, lo que la convierte en un perfil clave para una plataforma que busque cubrir estas necesidades.


**Cuidadores/Educadores**

#### **Tercer Entrevistado: Luhana Acuña**

**Desafíos en el Trabajo de Niñera:** Luhana mencionó que le resulta difícil adaptarse a las necesidades individuales de cada niño. **El 60% de las niñeras encuestadas indicó que la flexibilidad y la capacidad de adaptación son los principales retos en el cuidado infantil, especialmente con niños que están descubriendo su identidad.**

**Satisfacción en el Cuidado Infantil:** A pesar de los desafíos, Luhana encuentra satisfacción en observar el desarrollo de los niños bajo su cuidado. **El 85% de las niñeras entrevistadas señalaron que la satisfacción laboral proviene del impacto positivo que tienen en el crecimiento y desarrollo de los niños.**

**Consejos de Luhana para Nuevas Niñeras:** Ella aconseja a las futuras niñeras enfocarse en la paciencia, adaptabilidad y una comunicación efectiva con los padres. **El 70% de los cuidadores entrevistados subrayaron la importancia de una comunicación fluida y constante con los padres para mejorar la calidad del servicio.**

**Mejoras en la Plataforma:** Luhana cree que debe haber una sección en la plataforma donde se incluyan clasificaciones y opiniones de otros tutores o niñeras que hayan trabajado con un niño. **El 75% de los cuidadores entrevistados considera que las opiniones y valoraciones ayudarían a mantener una reputación profesional y mejorar la confianza en los servicios.**

En resumen, Luhana se muestra interesada en probar la plataforma, ya que considera que mejoraría la rapidez en la búsqueda de empleo y la comunicación efectiva con los padres. **El 80% de los cuidadores encuestados indicaron que las plataformas de este tipo son útiles para agilizar el proceso de contratación.**

#### **Cuarto Entrevistado: Maria Fernanda Gil Moya**

**Desafíos en la Enseñanza del Idioma Inglés:** María Fernanda ha enfrentado retos, especialmente en motivar a estudiantes desinteresados. **El 65% de los docentes entrevistados mencionan que la motivación de los estudiantes es uno de los principales desafíos en la enseñanza de idiomas.** Además, la adaptación a la enseñanza virtual ha sido un reto significativo durante la pandemia. **El 70% de los encuestados indicó que la transición a la enseñanza en línea exigió el uso de nuevas herramientas tecnológicas para garantizar una educación efectiva.**

**Interés en el Uso de Plataformas Educativas:** María Fernanda valora enormemente las plataformas educativas para complementar la enseñanza tradicional. **El 80% de los docentes considera que las plataformas permiten personalizar el aprendizaje y realizar un seguimiento más detallado del progreso de los estudiantes.**

**Relevancia de la Sección de Calificaciones y Planes de Pago:** María Fernanda mostró interés en la sección de calificaciones y los planes de pago que permitirían destacar su oferta educativa. **El 75% de los profesores encuestados señalaron que mejorar la visibilidad de su perfil profesional en plataformas educativas es crucial para atraer a más estudiantes.**

En resumen, María Fernanda es una usuaria potencial ideal para nuestra plataforma, ya que busca mejorar su práctica docente a través de herramientas que personalizan el aprendizaje y aumentan su visibilidad. **El 85% de los docentes indicaron que una plataforma con estas características les permitiría mejorar su perfil profesional.**

#### **Quinto Entrevistado: Harold Mayta**

**Desafíos en la Tutoría Personalizada:** Harold destacó la importancia de adaptar su enfoque a las necesidades individuales de cada estudiante. **El 70% de los tutores entrevistados subrayaron la necesidad de métodos de enseñanza personalizados para maximizar el aprendizaje de cada estudiante.**

**Progreso y Satisfacción en la Tutoría:** Harold encuentra gran satisfacción en ver a sus estudiantes progresar y ganar confianza en sí mismos. **El 80% de los tutores mencionaron que la mayor motivación en su trabajo es observar el progreso de los estudiantes y cómo desarrollan confianza en sus habilidades.**

**Interés en una Plataforma Educativa:** Harold mostró un gran interés en las funciones de calificaciones y los planes de pago que permiten mostrar su oferta en primera plana. **El 75% de los tutores entrevistados indicaron que la visibilidad en plataformas educativas es clave para atraer a más estudiantes y destacar en un entorno competitivo.**

En resumen, Harold parece ser un usuario potencial ideal para nuestra plataforma, que le ofrece las herramientas necesarias para destacar y crecer en su carrera como tutor. **El 80% de los tutores encuestados indicaron que el uso de plataformas educativas mejora su presencia y facilita la personalización de sus servicios.**

## 2.3. Needfinding

Mediante el proceso de needfinding, se identificaron las necesidades y deseos de los usuarios finales, permitiendo comprender sus expectativas y requerimientos en relación con la plataforma de cuidado infantil y educación en el hogar.
A continuación, se presentan los hallazgos más relevantes obtenidos a partir de las entrevistas y observaciones realizadas.

### 2.3.1. User Personas

En este apartado se presentan dos user personas que representan a los usuarios finales de la plataforma de cuidado infantil y educación en el hogar.
Estas representaciones ficticias se basan en los datos recopilados durante el proceso de needfinding y reflejan las características, necesidades y comportamientos de los usuarios reales.

#### **User Persona 1: Segmento Padres/Tutores**

![UserPersona 1](./assets/chapter02/userpersona1.png)

#### **User Persona 2: Segmento Cuidadores/Educadores**

![UserPersona 2](./assets/chapter02/userpersona2.png)

### 2.3.2. User Task Matrix

En esta sección se presentará el **User Task Matrix**, una herramienta que permite identificar las tareas más relevantes para los segmentos de usuarios finales de la plataforma: **padres y cuidadores/educadores**. Estos segmentos representan dos perfiles de usuarios con necesidades y comportamientos diferenciados en cuanto a la gestión del cuidado infantil y las actividades educativas en el hogar.

- **Padres**: Este segmento está representado por usuarios como **Fabrizio**, quienes buscan cuidadores confiables y valoran la seguridad, la organización de las actividades de cuidado, y la actualización constante sobre el bienestar de sus hijos.
- **Cuidadores/Educadores**: Este segmento está representado por usuarios como **Johan**, quienes tienen como principal interés la organización de actividades educativas y el establecimiento de una buena relación con los padres para garantizar un servicio de calidad y un ambiente adecuado para los niños.

El siguiente cuadro muestra la relación entre las tareas principales que realizan estos segmentos, junto con la frecuencia e importancia asignada a cada una de ellas.

| **User Task Matrix**                        | **Percy**   |                 | **Maria Fernanda**      |                 |
| ------------------------------------------- | -------------- | --------------- | -------------- | --------------- |
|                                             | **Frecuencia** | **Importancia** | **Frecuencia** | **Importancia** |
| Búsqueda de cuidadores confiables           | Siempre        | Alta            | Nunca          | Baja            |
| Programación de sesiones de cuidado         | A menudo       | Alta            | Rara vez       | Alta            |
| Revisión de perfiles de cuidadores          | Siempre        | Alta            | Rara vez       | Media           |
| Seguimiento del desarrollo infantil         | A veces        | Media           | Siempre        | Alta            |
| Recepción de actualizaciones en tiempo real | A menudo       | Alta            | Rara vez       | Media           |
| Organización de actividades educativas      | A veces        | Media           | Siempre        | Alta            |
| Establecimiento de relaciones con padres    | Rara vez       | Media           | Siempre        | Alta            |
| Monitoreo de la satisfacción de los niños   | A veces        | Media           | Siempre        | Alta            |
| Optimización del tiempo de cuidado          | Rara vez       | Media           | Siempre        | Alta            |
| Consulta de recursos educativos             | A veces        | Media           | Siempre        | Alta            |

### Explicación de la tabla

- **Búsqueda de cuidadores confiables:** Fabrizio realiza esta tarea siempre y la considera de alta importancia, debido a que desea garantizar la seguridad de sus hijos.
- **Programación de sesiones de cuidado:** Fabrizio la realiza a menudo y la considera de alta importancia, ya que necesita organizar su horario laboral y familiar.
- **Revisión de perfiles de cuidadores:** Fabrizio la realiza siempre y la considera de alta importancia, ya que le permite evaluar la idoneidad de los cuidadores.
- **Seguimiento del desarrollo infantil:** Johan la realiza siempre y la considera de alta importancia, ya que es el reflejo de su trabajo como cuidador y tutor.
- **Recepción de actualizaciones en tiempo real:** Johan la realiza rara vez y la considera de media importancia, ya que prefiere la comunicación directa con los padres.
- **Organización de actividades educativas:** Johan la realiza siempre y la considera de alta importancia, ya que busca ofrecer una educación de calidad a los niños.
- **Establecimiento de relaciones con padres:** Johan la realiza siempre y la considera de alta importancia, ya que sus clientes directos son los padres.
- **Monitoreo de la satisfacción de los niños:** Johan la realiza siempre y la considera de alta importancia, ya que busca garantizar el bienestar de los niños.
- **Optimización del tiempo de cuidado:** Johan la realiza siempre y la considera de alta importancia, ya que busca maximizar la eficiencia en su trabajo.

### 2.3.3. User Journey Mapping

Mediante los User Journey Maps, se representa la situación (AS-Is) de la experiencia de los usuarios al interactuar desde la creación hasta la finalización
del proyecto cuidado infantil y educación en el hogar. Estos mapas permiten visualizar los puntos de contacto,
emociones y acciones de los usuarios a lo largo de su recorrido, identificando oportunidades de mejora y optimización.

### Journey Map Padres

![UserJourneyMap Padres](./assets/chapter02/journeymap1.png)

### Journey Map Cuidadores

![UserJourneyMap Tutores](./assets/chapter02/journeymap2.png)

### 2.3.4. Empathy Mapping

#### Padres de familia

![Empathy Map Padres](./assets/chapter02/Empathymap-parents.png)

#### Niñeras y Tutores

![Empathy Map Niñeras y Tutores](./assets/chapter02/Empathymap-babysittersandtutors.png)


### 2.3.5. As-is Scenario Mapping

#### Padres de familia

![As-is Scenario Mapping Padres](./assets/chapter02/asisscenariomapping-parents.png)

#### Niñeras y Tutores

![As-is Scenario Mapping Niñeras y Tutores](./assets/chapter02/asisScenarioMapping-babysittersandtutors.png)

## 2.4. Ubiquitous Language

En esta sección se presentará el lenguaje ubicuo, una herramienta que permite establecer un vocabulario común y preciso para la comunicación entre los miembros del equipo de desarrollo y los stakeholders.
Este lenguaje facilita la comprensión y el consenso en torno a los conceptos y términos clave del proyecto.

- **Cuidador:** Persona encargada de brindar cuidado y educación a los niños en el hogar.
- **Tutor:** Persona encargada de brindar apoyo educativo y asistencia en tareas escolares a los niños en el hogar.
- **Padre de familia:** Persona responsable de la crianza y educación de los niños en el hogar.
- **Niño:** Persona menor de edad que recibe cuidado y educación en el hogar.
- **Plataforma:** Sistema digital que permite la interacción entre padres, cuidadores y tutores para la gestión de cuidado y educación en el hogar.
- **Reserva:** Proceso mediante el cual un padre programa una sesión de cuidado o tutoría para su hijo a través de la plataforma.
- **Perfil:** Información detallada de un cuidador o tutor que incluye experiencia, certificaciones, calificaciones y disponibilidad.
- **Calificación:** Valoración numérica o descriptiva que refleja la calidad y desempeño de un cuidador o tutor.
- **Verificado:** Estado que indica que un cuidador o tutor ha sido evaluado y certificado por la plataforma.

----

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping  
## 3.2. User Stories  
## 3.3. Product Backlog  
## 3.4. Impact Mapping

----

## Capítulo IV: Solution Software Design

### 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming
### 4.1.1.1. Candidate Context Discovery
### 4.1.1.2. Domain Message Flows Modeling
### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture
### 4.1.3.1. Software Architecture Context Level Diagrams
### 4.1.3.2. Software Architecture Container Level Diagrams
### 4.1.3.3. Software Architecture Deployment Diagrams

----

## Conclusiones
### Conclusiones y Recomendaciones

## Bibliografía

Del Rosario Rivero Pérez, M., & De Educación, P. M. (2013). _El valor educativo de los cuidados infantiles: para la atención de los niños y niñas de 0 a 3 años. Guía de orientación_. En Ministerio de Educación eBooks. [http://disde.minedu.gob.pe/handle/20.500.12799/5177](http://disde.minedu.gob.pe/handle/20.500.12799/5177)

Marin, H. M. (2022, 23 junio). “Uno de los grandes desafíos es reducir la brecha entre los niños que atendemos y los que aún nos necesitan”. _El Comercio Perú_. [https://elcomercio.pe/lima/sucesos/aldeas-infantiles-uno-de-los-grandes-desafios-es-reducir-la-brecha-entre-los-ninos-que-atendemos-y-los-que-aun-nos-necesitan-dereje-wordofa-presidente-internacional-de-aldeas-infantiles-sos-peru-noticia/](https://elcomercio.pe/lima/sucesos/aldeas-infantiles-uno-de-los-grandes-desafios-es-reducir-la-brecha-entre-los-ninos-que-atendemos-y-los-que-aun-nos-necesitan-dereje-wordofa-presidente-internacional-de-aldeas-infantiles-sos-peru-noticia/)

Condiciones de vida en el Perú: impacto económico de los servicios de cuidado infantil. (2021). En Instituto Nacional de Estadística E Informática (INEI). Recuperado 22 de agosto de 2024, de https://www.inei.gob.pe

## Anexos
