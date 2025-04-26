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
|Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.| **Bernaola Pérez, André Arturo**<br>*TB1*<br>Aprendí a profundizar en el enfoque Lean UX y reforcé mis conocimientos sobre Problem Statements, Assumptions y Hypothesis Statements. Me aseguré de actualizar mis técnicas de investigación rápida, formulé hipótesis claras y utilicé el Lean UX Canvas para estructurar de forma efectiva el Capítulo I: Presentación. Durante el proceso puse en práctica herramientas colaborativas como Miro para diseñar flujos de usuario y validé mis ideas con el equipo antes de plasmarlas en el documento.<br></br>**Gutierrez Garcia, Jose Eduardo**<br>*TB1*<br>Actualicé mis habilidades de investigación de usuarios aprendiendo nuevas metodologías de entrevistas y análisis competitivo. Apliqué Needfinding en el Capítulo II, creando User Personas, User Journey Maps y Empathy Maps que reflejan los hallazgos de las entrevistas. Aprendí a sintetizar datos cuantitativos y cualitativos para definir el Ubiquitous Language y asegurarme de que todos los términos del dominio estuvieran claros y alineados con las necesidades reales de padres y cuidadores.<br></br>**Sanchez Ignacio, Jefrey Martin**<br>*TB1*<br>Actualicé mis conocimientos de Impact Mapping y priorización de funcionalidades, traduciendo los hallazgos de la etapa de análisis en User Stories y un Product Backlog consistente. Aprendí a definir To-Be Scenarios y a organizar el backlog por valor de negocio en el Capítulo III. En este proceso profundicé en técnicas de estimación ágil y priorización MoSCoW, asegurando que cada historia estuviera correctamente refinada y alineada con los objetivos SMART del proyecto. <br></br> **Velarde Luyo, Piero Alberto**<br>*TB1*<br>Aprendí y apliqué prácticas avanzadas de Domain-Driven Design: realicé EventStorming para descubrir Candidate Contexts, modelé Domain Message Flows y elaboré Bounded Context Canvases. Además, actualicé mis competencias en context mapping y diseñé diagramas de arquitectura de software en niveles de contexto, contenedor y despliegue para el Capítulo IV. Esto me permitió entender mejor cómo se comunican los distintos módulos y cómo garantizar la escalabilidad y mantenibilidad de la solución. | TB1: <br> Como equipo, actualizamos y aplicamos de manera integrada conceptos de Lean UX, investigación de usuarios, modelado de dominio y arquitectura de software. Cada uno fortaleció tanto su perfil profesional—desde entrevistas y mapeos hasta diseño de flujos de mensajes y diagramas de despliegue—como nuestra capacidad colectiva para construir una plataforma móvil robusta y centrada en las necesidades reales de padres y cuidadores. Este aprendizaje conjunto nos ha preparado para afrontar con metodología y rigor el desarrollo de la solución, mejorando nuestra colaboración, comunicación y alineación estratégica.|

| Criterio específico | Acciones realizadas | Conclusiones |
|----|----|----|
|Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.|**Bernaola Pérez, André Arturo**<br>*TB1*<br>Aprendí a identificar tendencias emergentes en UX y metodologías ágiles revisando artículos y estudios de caso semanalmente, lo que me permitió actualizar mis técnicas en Lean UX y validación rápida; luego compartí estos aprendizajes con el equipo en sesiones quincenales de retroalimentación.<br></br>**Gutierrez Garcia, Jose Eduardo**<br>*TB1*<br>Reconocí la importancia de profundizar en investigación de usuarios, por lo que me inscribí en un curso avanzado de entrevistas cualitativas, exploré Figma y Miro con tutoriales diarios y documenté plantillas reutilizables para mapas de empatía y user journeys en nuestra wiki interna.<br></br>**Sanchez Ignacio, Jefrey Martin**<br>*TB1*<br>Aprendí nuevas prácticas de priorización de backlog al participar en un workshop de Product Discovery y actualicé mis conocimientos en Impact Mapping y Scrum; apliqué metodologías de estimación ágil (Planning Poker, T-shirt sizing) en nuestras sesiones de sprint para mejorar la precisión de los compromisos. <br></br> **Velarde Luyo, Piero Alberto**<br>*TB1*<br>Reconocí la necesidad de dominar Domain-Driven Design y me uní a un grupo de estudio sobre EventStorming, lo que me permitió actualizar mis competencias en context mapping y arquitectura de microservicios; luego modelé flujos de mensajes complejos y documenté cada bounded context en nuestra herramienta colaborativa. | TB1: <br> Como equipo, reafirmamos que el aprendizaje permanente es fundamental para mantenernos competitivos y mejorar la calidad de nuestro proyecto. Cada integrante adoptó hábitos de actualización continua y aplicó nuevas metodologías, fortaleciendo nuestras habilidades técnicas y nuestra capacidad de adaptación, colaboración y crecimiento conjunto en el desarrollo de la plataforma móvil de cuidado infantil.|

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
### 2.1.2. Estrategias y tácticas frente a competidores  

## 2.2. Entrevistas  
### 2.2.1. Diseño de entrevistas  
### 2.2.2. Registro de entrevistas  
### 2.2.3. Análisis de entrevistas  

## 2.3. Needfinding  
### 2.3.1. User Personas  
### 2.3.2. User Task Matrix  
### 2.3.3. User Journey Mapping  
### 2.3.4. Empathy Mapping  
### 2.3.5. As-is Scenario Mapping  

## 2.4. Ubiquitous Language  

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

**Conlusiones**

El equipo ha demostrado una sólida adopción del aprendizaje continuo al integrar nuevas metodologías (Lean UX, investigación cualitativa, DDD y estimaciones ágiles) en el proyecto, lo que ha mejorado nuestra capacidad de colaboración, la calidad de los entregables y la alineación con las necesidades de padres y cuidadores.

**Recomendación**
Establecer un ritual mensual de “lunch & learn” interno en el que cada miembro comparta un concepto, herramienta o práctica reciente y cómo aplicarla al proyecto, asegurando así la difusión constante de conocimiento y la retroalimentación colectiva.

## Bibliografía

Del Rosario Rivero Pérez, M., & De Educación, P. M. (2013). _El valor educativo de los cuidados infantiles: para la atención de los niños y niñas de 0 a 3 años. Guía de orientación_. En Ministerio de Educación eBooks. [http://disde.minedu.gob.pe/handle/20.500.12799/5177](http://disde.minedu.gob.pe/handle/20.500.12799/5177)

Marin, H. M. (2022, 23 junio). “Uno de los grandes desafíos es reducir la brecha entre los niños que atendemos y los que aún nos necesitan”. _El Comercio Perú_. [https://elcomercio.pe/lima/sucesos/aldeas-infantiles-uno-de-los-grandes-desafios-es-reducir-la-brecha-entre-los-ninos-que-atendemos-y-los-que-aun-nos-necesitan-dereje-wordofa-presidente-internacional-de-aldeas-infantiles-sos-peru-noticia/](https://elcomercio.pe/lima/sucesos/aldeas-infantiles-uno-de-los-grandes-desafios-es-reducir-la-brecha-entre-los-ninos-que-atendemos-y-los-que-aun-nos-necesitan-dereje-wordofa-presidente-internacional-de-aldeas-infantiles-sos-peru-noticia/)

Condiciones de vida en el Perú: impacto económico de los servicios de cuidado infantil. (2021). En Instituto Nacional de Estadística E Informática (INEI). Recuperado 22 de agosto de 2024, de https://www.inei.gob.pe

## Anexos