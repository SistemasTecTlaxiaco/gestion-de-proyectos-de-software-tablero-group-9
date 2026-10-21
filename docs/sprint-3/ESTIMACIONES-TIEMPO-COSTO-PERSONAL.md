# ESTIMACIÓN DE TIEMPO, COSTOS Y PERSONAL REQUERIDO

**Tecnológico Nacional de México — Instituto Tecnológico de Tlaxiaco**

**Asignatura:** Gestión de Proyectos de Software (SCG-1009)  
**Unidad:** 3. Planificación del Proyecto  
**Sprint:** 3  
**Proyecto:** Sistema de Control y Comercialización de la Producción de Miel  
**Organización beneficiaria:** Unión de Productores de Miel de San Juan Ñumí, Oaxaca  
**Equipo de desarrollo:** UMIZOOMI  
**Integrantes:** Félix Ángel García García, Diego Fidel Sosa Cruz, Daniel Alejandro López Camarillo y Luis Alexis Morales José  
**Metodología:** eduScrum  
**Versión:** 2.0 — Propuesta de planificación pendiente de validación

---

## 1. Introducción

La planificación de un proyecto de software requiere estimar el esfuerzo necesario para desarrollar sus funcionalidades, determinar los recursos económicos y distribuir las responsabilidades entre los integrantes del equipo.

El presente documento desarrolla una propuesta de estimaciones para el Sistema de Control y Comercialización de la Producción de Miel, cuyo propósito es mejorar el registro de productores, las cosechas, el inventario y las actividades de comercialización de la Unión de Productores de Miel de San Juan Ñumí, Oaxaca.

Las estimaciones se relacionan con la auditoría de historias de usuario del Sprint 1 y con el Costo de la Calidad documentado en el Sprint 2, conforme a la instrumentación didáctica de la Unidad 3.

## 2. Objetivo general

Estimar el tiempo de desarrollo, los costos económicos y el personal requerido para implementar las funcionalidades del sistema de miel, estableciendo una distribución de responsabilidades verificable y mecanismos de seguimiento mediante GitHub Projects y eduScrum.

## 3. Relación con el Sprint 1: Backlog

En el repositorio de historias de usuario del equipo se identifican registros relacionados con la producción y comercialización de miel.

| Identificador | Funcionalidad | Evidencia disponible |
|---|---|---|
| HU-P1-003 | Control de inventario disponible | Auditoría de IA, con alerta de inventario inferior a 10 kg |
| HU-P1-004 | Registro de ventas y clientes | Historia corregida con validación para ventas superiores a existencias |
| HU-P1-005 | Reporte mensual | Historia corregida con exportación PDF |
| F-01, provisional | Registro de productores | Descrito en el documento SMART |
| F-02, provisional | Registro y control de cosechas | Descrito en el documento SMART |

Las claves F-01 y F-02 son identificadores de planificación, no historias oficiales confirmadas. Antes de cerrar la evidencia se deben sustituir por sus códigos reales del Backlog.

### Criterios de aceptación relevantes

**Registro de productores:** permitir capturar y consultar datos de los productores participantes, validando campos obligatorios.

**Control de cosechas:** permitir registrar las cantidades de miel obtenidas y consultar los registros asociados con cada productor.

**HU-P1-003, inventario:** controlar la cantidad disponible y utilizar el umbral de alerta de 10 kg señalado en la auditoría.

**HU-P1-004, ventas:** registrar cliente, fecha, cantidad y precio; descontar existencias y rechazar operaciones que excedan el inventario disponible.

**HU-P1-005, reporte mensual:** mostrar los totales de producción, inventario y ventas; permitir exportación PDF y asegurar que los totales coincidan con los registros.

## 4. Trazabilidad con el Sprint 2: Costo de la Calidad

El Plan de Calidad del equipo contiene tres historias correspondientes a diferentes iniciativas de Open Hub Tec:

| Historia del Plan de Calidad | Prevención | Corrección | Total |
|---|---:|---:|---:|
| HU-01, producción y venta de miel | 6 h | 2 h | 8 h |
| HU-02, locatarios del mercado | 5 h | 3 h | 8 h |
| HU-03, trazabilidad de mezcal | 7 h | 1 h | 8 h |
| **Total general** | **18 h** | **6 h** | **24 h** |

El total de 24 horas corresponde al plan general y no debe confundirse con la estimación exclusiva del proyecto de miel.

Para esta actividad se toma como referencia verificable la inversión de **6 horas de prevención y 2 horas de corrección** vinculada con producción y venta de miel.

Se propone distribuir las horas de calidad del proyecto completo en las siguientes funcionalidades. Las horas adicionales no se presentan como datos históricos, sino como nuevas estimaciones que deberán ser aprobadas por el equipo.

## 5. Estimación detallada de tiempo

| Funcionalidad | Desarrollo | Prevención | Corrección | Total |
|---|---:|---:|---:|---:|
| F-01 Productores | 18 h | 6 h | 2 h | 26 h |
| F-02 Cosechas | 24 h | 4 h | 2 h | 30 h |
| HU-P1-003 Inventario | 30 h | 5 h | 3 h | 38 h |
| HU-P1-004 Ventas y clientes | 26 h | 4 h | 2 h | 32 h |
| HU-P1-005 Reporte mensual | 14 h | 3 h | 1 h | 18 h |
| **Total** | **112 h** | **22 h** | **10 h** | **144 h** |

**Nota de trazabilidad:** Las 8 horas iniciales de calidad se documentaron para la actividad general de producción y venta de miel. Su ubicación provisional en F-01 sirve para construir este escenario; no acredita que el Sprint 2 haya asignado esas horas específicamente al registro de productores. El equipo deberá revisar y conciliar esta asignación con sus historias originales.

### 5.1 Justificación de tiempos

- **Productores:** requiere formularios, validaciones, almacenamiento y consultas.
- **Cosechas:** necesita asociación con productores, captura de cantidades y consulta histórica.
- **Inventario:** exige reglas para entradas y salidas, alertas y prevención de inconsistencias, por lo que tiene la mayor estimación.
- **Ventas:** requiere verificar existencias, registrar operaciones y relacionarlas con clientes.
- **Reporte mensual:** implica integrar consultas, calcular totales y exportar información en PDF.

### 5.2 Métricas propuestas

**Horas de calidad:** 22 + 10 = 32 horas.

**Índice estimado de prevención:** 22 / 32 × 100 = **68.75%**.

**Porcentaje de calidad respecto del esfuerzo total:** 32 / 144 × 100 = **22.22%**.

El índice de prevención estimado supera la meta del 60% contemplada en el Plan de Calidad. No constituye todavía un resultado real de ejecución.

## 6. Estimación financiera

Para construir un escenario comparable se utiliza una tarifa académica propuesta de **$150 MXN por hora**, sujeta a validación del equipo.

| Funcionalidad | Horas | Costo de trabajo |
|---|---:|---:|
| Productores | 26 | $3,900 |
| Cosechas | 30 | $4,500 |
| Inventario | 38 | $5,700 |
| Ventas y clientes | 32 | $4,800 |
| Reporte mensual | 18 | $2,700 |
| **Total** | **144** | **$21,600 MXN** |

### 6.1 Desglose por tipo de esfuerzo

| Concepto | Horas | Costo |
|---|---:|---:|
| Desarrollo | 112 | $16,800 |
| Prevención de defectos | 22 | $3,300 |
| Corrección de defectos | 10 | $1,500 |
| **Total** | **144** | **$21,600** |

### 6.2 Insumos adicionales

| Insumo | Estado de estimación |
|---|---|
| Computadoras y herramientas de desarrollo | Verificar disponibilidad institucional y del equipo |
| Hospedaje y base de datos | Por cotizar si se requiere |
| Internet y conectividad | Por estimar |
| Pruebas con productores | Por planificar |
| Capacitación y documentación | Incluye esfuerzo académico; otros gastos, por estimar |
| Servicios relacionados con Stellar/Drips | Solo si se aprueba una integración técnica concreta |

El presupuesto de $21,600 MXN corresponde al esfuerzo humano valorizado. **No equivale al costo total definitivo del proyecto**, porque los insumos adicionales todavía no están cuantificados.

## 7. Estimación de personal requerido

Para desarrollar el proyecto se propone distribuir las actividades entre los cuatro integrantes.

| Integrante | Perfil propuesto | Responsabilidades |
|---|---|---|
| Félix Ángel García García | Coordinación y análisis | Organización de tareas, requisitos, seguimiento del Sprint |
| Diego Fidel Sosa Cruz | Aseguramiento de calidad | Pruebas, verificación de requisitos, control de defectos |
| Daniel Alejandro López Camarillo | Desarrollo | Implementación de funcionalidades, validaciones y pruebas unitarias |
| Luis Alexis Morales José | Desarrollo e integración | Implementación, integración y documentación técnica |

La distribución debe ser aprobada por el equipo. Los roles son compatibles con las responsabilidades registradas en el Plan de Calidad.

## 8. Distribución de carga por integrante

La siguiente propuesta equilibra la carga total de 144 horas, sin asumir que todos los integrantes realizarán actividades idénticas.

| Funcionalidad | Félix | Diego | Daniel | Luis | Total |
|---|---:|---:|---:|---:|---:|
| Productores | 8 | 6 | 8 | 4 | 26 |
| Cosechas | 8 | 8 | 8 | 6 | 30 |
| Inventario | 8 | 12 | 10 | 8 | 38 |
| Ventas y clientes | 8 | 6 | 6 | 12 | 32 |
| Reporte mensual | 4 | 4 | 4 | 6 | 18 |
| **Total por integrante** | **36** | **36** | **36** | **36** | **144** |

Cada asignación representa horas de participación en actividades de análisis, desarrollo, pruebas, revisión o documentación.

Una vez implementado el tablero, las horas deberán registrarse por tarea e integrante. La distribución equitativa es una propuesta, no una evidencia de horas ya trabajadas.

## 9. Organización del tablero GitHub Projects

La rúbrica exige representar el trabajo en un tablero Kanban operativo, no únicamente en este documento.

Se utilizarán las siguientes columnas:

| Columna | Significado |
|---|---|
| Backlog | Historias y tareas identificadas, aún no seleccionadas |
| To Do | Actividades aprobadas para iniciar |
| In Progress | Actividades en ejecución |
| Review | Actividades pendientes de revisión |
| Done | Actividades verificadas y terminadas |

### 9.1 Tareas sugeridas

| Código | Tarea | Responsable propuesto | Estimación del conjunto |
|---|---|---|---:|
| S3-01 | Revisar requisitos y tareas de productores | Félix | Incluida en F-01 |
| S3-02 | Implementar registro y consulta de cosechas | Daniel y Luis | Incluida en F-02 |
| S3-03 | Validar inventario y umbral de 10 kg | Daniel y Diego | Incluida en HU-P1-003 |
| S3-04 | Implementar ventas y rechazo por inventario insuficiente | Luis y Diego | Incluida en HU-P1-004 |
| S3-05 | Generar reportes mensuales y PDF | Luis y Daniel | Incluida en HU-P1-005 |
| S3-06 | Revisar métricas y defectos | Diego | Incluida en horas de calidad |
| S3-07 | Verificar documentación y aceptación | Félix y equipo | Incluida en horas de trabajo |

Estas tareas son una descomposición de las estimaciones anteriores y no representan horas adicionales.

### 9.2 Reglas del tablero

Cada tarjeta de GitHub Projects deberá contener:

- Identificador de historia o tarea.
- Descripción y objetivo.
- Responsable asignado.
- Etiqueta `Sprint-3`.
- Tiempo estimado.
- Costo estimado o vínculo a esta tabla.
- Criterios de aceptación.
- Estado y evidencia de revisión.

La gestión y actualización del tablero deberán realizarse por los integrantes correspondientes bajo seguimiento del responsable eduScrum.

## 10. Criterios de finalización

Una tarea podrá pasar a Done cuando:

1. Cumpla los criterios de aceptación establecidos.
2. Cuente con pruebas documentadas.
3. No presente defectos críticos conocidos.
4. Su revisión haya sido registrada.
5. Se hayan actualizado las horas utilizadas.
6. Existan evidencias que el profesor pueda consultar desde GitHub.

## 11. Conclusión

La propuesta de estimación permite organizar el desarrollo del Sistema de Control y Comercialización de la Producción de Miel mediante un esfuerzo inicial de 144 horas, una valoración académica de $21,600 MXN en trabajo y una distribución propuesta entre cuatro integrantes.

El documento recupera las métricas del Plan de Calidad del Sprint 2 y reconoce que algunas historias del plan general corresponden a otros proyectos.

Para completar la evidencia de planificación será necesario validar las estimaciones, relacionarlas con los identificadores oficiales del Backlog y reflejar las tareas, responsables, estados y criterios de aceptación en un tablero GitHub Projects operativo.
