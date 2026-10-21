# INFORME DE ESTÁNDARES DE CALIDAD

**Instituto Tecnológico de Tlaxiaco**  
**Ingeniería en Sistemas Computacionales**  
**Asignatura:** Gestión de Proyectos de Software  
**Unidad:** Planificación del Proyecto — Sprint 3  
**Proyecto:** TisaaSavi / Noble Origen  
**Ecosistema:** Open Hub Tec  
**Marco de trabajo:** eduScrum  
**Fecha:** Octubre de 2026

---

## 1. Introducción

La calidad del software es fundamental para desarrollar aplicaciones confiables, seguras y capaces de responder a las necesidades de sus usuarios. Para asegurarla, existen modelos de referencia como CMMI y MoProSoft, que proporcionan buenas prácticas relacionadas con la planificación, el desarrollo, la evaluación y la mejora de los procesos.

El presente informe analiza dichos modelos y su aplicación al proyecto TisaaSavi / Noble Origen, una iniciativa orientada a la trazabilidad de prendas artesanales y a la liquidación transparente de pagos para talleres textiles de la Mixteca Alta oaxaqueña.

También se investigan los mecanismos y criterios relevantes del Stellar Community Fund y Drips Protocol, con el propósito de identificar prácticas que contribuyan a la calidad, viabilidad y posible sostenibilidad del proyecto.

## 2. Objetivo general

Investigar y comparar los modelos CMMI y MoProSoft con los criterios y mecanismos de Stellar Community Fund y Drips Protocol, identificando prácticas de calidad aplicables al desarrollo del proyecto TisaaSavi / Noble Origen.

## 3. Descripción del proyecto

TisaaSavi / Noble Origen propone desarrollar una plataforma digital que permita registrar la autoría de prendas textiles artesanales, consultar información mediante códigos QR y facilitar mecanismos transparentes de liquidación.

El proyecto contempla una arquitectura *offline-first* para trabajar bajo condiciones de conectividad limitada, especialmente en comunidades rurales.

Entre las metas establecidas se encuentran registrar 50 prendas artesanales, vincular 15 talleres, alcanzar un tiempo de carga inferior a tres segundos en condiciones de red definidas y lograr una tasa de éxito transaccional del 98%.

Estas cifras representan objetivos del proyecto que deberán comprobarse mediante pruebas y evidencias.

## 4. Modelo CMMI

CMMI (Capability Maturity Model Integration) es un modelo de buenas prácticas para mejorar las capacidades y el desempeño de las organizaciones.

En el desarrollo de software, ayuda a fortalecer la gestión de procesos, la calidad de los productos, el seguimiento de actividades y la mejora continua.

**Aplicación a TisaaSavi / Noble Origen:**

- Documentar los requisitos de las historias de usuario.
- Registrar y controlar los cambios del código mediante GitHub.
- Aplicar revisiones entre integrantes del equipo.
- Ejecutar pruebas funcionales, de seguridad y de funcionamiento sin conexión.
- Medir defectos detectados y acciones correctivas.

La aplicación de estas prácticas no implica que el proyecto cuente con una certificación CMMI.

## 5. Modelo MoProSoft

MoProSoft es un modelo mexicano de procesos para la industria de software. Su objetivo es mejorar la gestión y el desarrollo de productos de software mediante prácticas organizadas.

Se estructura en tres categorías: Alta Dirección, Gerencia y Operación.

**Aplicación a TisaaSavi / Noble Origen:**

- **Alta Dirección:** definir los objetivos y resultados esperados del proyecto.
- **Gerencia:** organizar los recursos, actividades, responsables y fechas de cada sprint.
- **Operación:** desarrollar las funcionalidades, ejecutar pruebas y documentar los resultados.

Para el equipo eduScrum, MoProSoft puede servir como referencia para organizar tareas y establecer responsabilidades sin necesidad de implantar formalmente todos los procesos de una empresa.

## 6. Stellar Community Fund

Stellar Community Fund es un programa de apoyo a proyectos que desarrollan soluciones dentro del ecosistema Stellar.

Su proceso de evaluación contempla elementos como la propuesta de valor, la utilización de Stellar, la calidad de la solicitud, el plan de integración, la preparación del proyecto y su presupuesto, dependiendo de la modalidad de participación.

**Aplicación al proyecto:**

TisaaSavi / Noble Origen propone utilizar Stellar y Soroban para registrar evidencia de trazabilidad y apoyar procesos de liquidación.

Para fortalecer una eventual solicitud sería recomendable presentar:

- Un MVP funcional y demostrable.
- Justificación técnica del uso de Stellar.
- Resultados verificables de pruebas.
- Presupuesto desglosado.
- Cronograma y entregables.
- Evidencia de validación con usuarios.

No se identificó que la certificación formal CMMI o MoProSoft sea un requisito universal del programa. Estos modelos se utilizarían como apoyo interno a la calidad.

## 7. Drips Protocol

Drips es una plataforma de financiamiento para proyectos de código abierto que permite apoyar repositorios y distribuir fondos entre responsables y dependencias.

Su integración con GitHub permite identificar proyectos y configurar mecanismos de distribución de aportaciones.

**Aplicación al proyecto:**

Para explorar su utilización, TisaaSavi / Noble Origen necesitaría identificar qué componentes podrían publicarse bajo una licencia de código abierto, documentar sus dependencias y definir la gobernanza de las posibles aportaciones.

El procedimiento para reclamar un proyecto puede incluir la verificación del repositorio mediante un archivo `FUNDING.json`.

Drips no debe considerarse financiamiento aprobado ni una fuente de ingresos garantizados.

## 8. Comparación de modelos y plataformas

| Modelo o plataforma | Enfoque principal | Aplicación al proyecto |
|---|---|---|
| CMMI | Mejora de procesos y capacidades | Revisiones, pruebas, control de defectos |
| MoProSoft | Gestión organizada de proyectos de software | Responsables, actividades, entregables |
| Stellar Community Fund | Apoyo a proyectos del ecosistema Stellar | Validación del MVP, presupuesto e integración |
| Drips Protocol | Financiamiento de código abierto | Repositorio, dependencias y distribución de aportaciones |

## 9. Recomendaciones de calidad

A partir de la investigación se recomienda:

1. Mantener actualizadas las historias de usuario y sus criterios de aceptación.
2. Realizar revisiones de código mediante Pull Requests.
3. Documentar las pruebas de funcionamiento sin conexión.
4. Medir el porcentaje de transacciones exitosas en condiciones controladas.
5. Proteger la información personal y financiera de los talleres artesanales.
6. Mantener una bitácora de errores y acciones correctivas.
7. Elaborar un presupuesto verificable para cualquier solicitud de financiamiento.
8. Documentar las licencias y dependencias antes de utilizar mecanismos de financiamiento de código abierto.

## 10. Conclusión

La investigación demuestra que CMMI y MoProSoft pueden proporcionar una base metodológica para organizar y mejorar los procesos de desarrollo de TisaaSavi / Noble Origen.

Por otra parte, Stellar Community Fund y Drips Protocol representan alternativas que pueden investigarse para apoyar la sostenibilidad del proyecto, aunque sus condiciones y mecanismos son diferentes.

La adopción de buenas prácticas de documentación, seguridad, pruebas y control de cambios permitirá fortalecer la calidad de la propuesta y generar evidencias para valorar su viabilidad.

## 11. Referencias

- CMMI Institute. (s. f.). *CMMI Development*. https://cmmiinstitute.com/products/cmmi/cmmi-dev
- Secretaría de Economía. (2016). *NMX-I-059-2-NYCE-2016: Requisitos de procesos (MoProSoft)*. https://platiica.economia.gob.mx/normalizacion/nmx-i-059-2-nyce-2016/
- Stellar Development Foundation. (s. f.). *Stellar Community Fund*. https://communityfund.stellar.org/awards
- Drips. (s. f.). *Introduction*. https://docs.drips.network/
- Drips. (s. f.). *Claim your open-source project*. https://docs.drips.network/get-support/claim-your-repository/
