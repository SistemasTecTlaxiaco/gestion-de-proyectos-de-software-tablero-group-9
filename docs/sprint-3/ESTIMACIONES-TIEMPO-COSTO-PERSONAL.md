# ESTIMACIÓN DE TIEMPO, COSTOS Y PERSONAL REQUERIDO

**Instituto Tecnológico de Tlaxiaco**  
**Carrera:** Ingeniería en Sistemas Computacionales  
**Asignatura:** Gestión de Proyectos de Software (SCG-1009)  
**Unidad:** 3. Planificación del Proyecto  
**Sprint:** 3  
**Proyecto:** Sistema de Control y Comercialización de la Producción de Miel  
**Organización beneficiaria:** Unión de Productores de Miel de San Juan Ñumí, Oaxaca  
**Equipo:** UMIZOOMI  
**Integrantes:** Diego Fidel Sosa Cruz, Félix Ángel García García, Daniel Alejandro López Camarillo y Luis Alexis Morales José.  
**Marco de trabajo:** eduScrum

---

## 1. Introducción

La estimación de tiempo, costos y personal es un proceso necesario para planificar el desarrollo de software. Permite identificar el esfuerzo requerido para implementar las funcionalidades, distribuir responsabilidades y determinar los recursos necesarios para alcanzar los objetivos.

En el Sistema de Control y Comercialización de la Producción de Miel se busca mejorar la organización de los registros de productores, cosechas, inventario y comercialización de la Unión de Productores de Miel de San Juan Ñumí, Oaxaca.

La planificación toma como referencia el objetivo SMART del Sprint 3 y los criterios de aseguramiento de calidad del Sprint 2.

## 2. Objetivo

Estimar las horas de trabajo, los costos y los recursos humanos necesarios para desarrollar el sistema de control y comercialización de miel, considerando las funcionalidades propuestas, las actividades de prevención y corrección de defectos y la organización del equipo mediante eduScrum.

## 3. Alcance funcional

El documento de viabilidad del proyecto identifica las siguientes áreas funcionales:

| Código de planificación | Funcionalidad | Descripción |
|---|---|---|
| F-01 | Registro de productores | Registrar y consultar información de apicultores. |
| F-02 | Control de cosechas | Registrar cantidades y datos de cosechas de miel. |
| F-03 | Administración del inventario | Controlar existencias y movimientos de productos. |
| F-04 | Control de comercialización | Registrar ventas y consultar movimientos comerciales. |
| F-05 | Consulta de información | Facilitar consultas y seguimiento de los registros. |

Los códigos F-01 a F-05 se utilizan para organizar esta estimación y no sustituyen los identificadores oficiales de las historias de usuario del Backlog.

## 4. Antecedentes del Sprint 2

El Plan de Calidad del equipo presenta los siguientes cálculos:

| Historia registrada | Prevención | Corrección | Total |
|---|---:|---:|---:|
| HU-01: Producción y venta de miel | 6 h | 2 h | 8 h |
| HU-02: Cobros y control de locatarios del mercado | 5 h | 3 h | 8 h |
| HU-03: Trazabilidad de mezcal artesanal | 7 h | 1 h | 8 h |
| **Total del plan general** | **18 h** | **6 h** | **24 h** |

La HU-01 está directamente relacionada con el sistema de miel. Las otras historias corresponden a iniciativas diferentes del ecosistema Open Hub Tec.

Por tanto, las 24 horas no se consideran automáticamente la estimación exclusiva del sistema de miel. Para completar su planificación se propone una estimación específica que deberá validar el equipo.

## 5. Estimación del esfuerzo

Se establece un escenario académico inicial, considerando la complejidad relativa de cada funcionalidad.

| Funcionalidad | Desarrollo | Prevención | Corrección | Total |
|---|---:|---:|---:|---:|
| F-01 Registro de productores | 18 h | 6 h | 2 h | 26 h |
| F-02 Control de cosechas | 24 h | 4 h | 2 h | 30 h |
| F-03 Administración del inventario | 30 h | 5 h | 3 h | 38 h |
| F-04 Control de comercialización | 26 h | 4 h | 2 h | 32 h |
| F-05 Consulta de información | 14 h | 3 h | 1 h | 18 h |
| **Total** | **112 h** | **22 h** | **10 h** | **144 h** |

Las 8 horas de calidad de F-01 toman como referencia el cálculo de la HU-01 del Plan de Calidad. Las demás cifras son nuevas estimaciones de planificación, no horas realmente trabajadas ni valores confirmados del Sprint 2.

### Índice de prevención estimado

Índice de prevención = (22 / 32) × 100 = **68.75%**.

Este resultado supera la meta de 60% de prevención indicada en el Plan de Calidad. Sin embargo, solamente representa un escenario estimado que deberá contrastarse con las horas reales de cada sprint.

## 6. Estimación de costos

Para valorar económicamente el esfuerzo se utiliza una tarifa académica hipotética de $150 MXN por hora. Este valor no corresponde a una tarifa documentada en el Plan de Calidad y deberá ser aprobado o sustituido por el equipo.

| Concepto | Horas | Costo académico |
|---|---:|---:|
| Desarrollo | 112 h | $16,800 MXN |
| Prevención de defectos | 22 h | $3,300 MXN |
| Corrección de defectos | 10 h | $1,500 MXN |
| **Total del esfuerzo estimado** | **144 h** | **$21,600 MXN** |

El total no incluye infraestructura, transporte, capacitación ni otros servicios cuyo costo se desconoce.

No se considera un presupuesto definitivo ni un gasto realizado.

## 7. Estimación del personal requerido

Se cuenta con cuatro integrantes del equipo y se propone utilizar una distribución de responsabilidades compatible con eduScrum.

| Integrante | Responsabilidad principal propuesta |
|---|---|
| Félix Ángel García García | Coordinación del proyecto, seguimiento del Backlog y revisión de requisitos. |
| Diego Fidel Sosa Cruz | Aseguramiento de calidad, pruebas y seguimiento de defectos. |
| Daniel Alejandro López Camarillo | Desarrollo de funcionalidades, integración y pruebas unitarias. |
| Luis Alexis Morales José | Desarrollo, apoyo a pruebas y documentación técnica. |

La coordinación, las pruebas y el desarrollo pueden distribuirse entre varios integrantes. Esta propuesta toma como referencia los roles mencionados en el Plan de Calidad y deberá confirmarse con el equipo.

## 8. Capacidad de trabajo

Si los cuatro integrantes participan en las 144 horas estimadas, la carga promedio sería de 36 horas por persona durante el periodo de desarrollo.

Este promedio no implica que todas las tareas deban repartirse por igual, porque las actividades tienen distinta complejidad y requieren diferentes competencias.

Las fechas y el número de horas semanales se deberán registrar en el tablero de GitHub, tomando en cuenta la disponibilidad real de cada integrante.

## 9. Seguimiento mediante eduScrum

Para controlar el cumplimiento de la estimación se propone:

1. Registrar cada funcionalidad como historia de usuario o conjunto de tareas.
2. Establecer criterios de aceptación.
3. Asignar responsables y fechas.
4. Registrar las horas reales de desarrollo, prevención y corrección.
5. Realizar revisiones periódicas del avance.
6. Documentar defectos y evidencias de pruebas.
7. Actualizar las estimaciones ante cambios de alcance.

## 10. Evaluación de la estimación

La administración del inventario presenta la mayor carga estimada debido a la necesidad de controlar cantidades y movimientos de miel sin producir inconsistencias.

El control de comercialización también requiere especial atención porque sus registros deben mantener una relación coherente con el inventario.

Las 144 horas propuestas representan una línea base inicial. Antes de aprobarla, el equipo deberá revisar las historias originales, la disponibilidad de los integrantes y las tecnologías que se utilizarán.

## 11. Conclusión

La estimación del tiempo, los costos y el personal requerido permite establecer una base para organizar el desarrollo del Sistema de Control y Comercialización de la Producción de Miel.

La propuesta considera cinco áreas funcionales, un esfuerzo preliminar de 144 horas y cuatro integrantes con responsabilidades complementarias.

El uso del marco eduScrum y del tablero de GitHub facilitará el seguimiento de las tareas y la actualización de las estimaciones conforme avance el desarrollo.

Los resultados deberán validarse antes de considerarse un compromiso definitivo de tiempo o presupuesto.
