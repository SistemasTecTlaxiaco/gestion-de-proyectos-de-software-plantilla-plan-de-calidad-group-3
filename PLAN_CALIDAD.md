# PLANTILLA PLAN DE CALIDAD

## Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano

**Instituto Tecnológico de Tlaxiaco**
**Ingeniería en Sistemas Computacionales**
**Asignatura:** Gestión de Proyectos de Software
**Grupo:** 7US

**Docente:** Ing. Roman Cruz José Alfredo

### Integrantes

* Sandoval Hernández Edgar Axel – 22620093
* Adriana Hernández Martínez – 22620083

**Lugar y fecha:** Tlaxiaco, Oax., a 11 de septiembre de 2026.

---

# 1. Introducción

El presente Plan de Calidad establece los criterios, procedimientos, métricas y actividades que se utilizarán para asegurar la calidad del **Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano**.

El proyecto tiene como propósito apoyar a los artesanos de la región Mixteca mediante una herramienta digital que permita organizar información de productos, controlar inventarios, registrar ventas y generar información útil para la comercialización de sus productos.

Debido a las condiciones que pueden presentarse en algunas comunidades de la región, como conectividad limitada, recursos tecnológicos reducidos y diferentes niveles de experiencia en el uso de herramientas digitales, el sistema debe considerar principalmente la **usabilidad, rendimiento, confiabilidad, seguridad, accesibilidad y mantenibilidad**.

Para estructurar el Plan de Calidad se consideran principios de **CMMI y MoProSoft**, adaptándolos al tamaño, alcance y necesidades del proyecto **Open Hub Tec**. Además, se utilizarán herramientas de **Inteligencia Artificial** como apoyo para la revisión de historias de usuario, criterios de aceptación, métricas y posibles riesgos de calidad.

El plan también contempla el análisis del **Costo de la Calidad (CoQ)** para identificar cuánto esfuerzo requiere prevenir problemas y cuánto esfuerzo podría ser necesario para corregirlos posteriormente.

---

# 2. Objetivos de Calidad

## 2.1 Objetivo general

Establecer un conjunto de criterios, métricas y procedimientos que permitan desarrollar un sistema de gestión comercial confiable, usable, seguro y mantenible, adaptado a las condiciones de los artesanos de la región Mixteca.

## 2.2 Objetivos específicos

### Confiabilidad

* Mantener una disponibilidad objetivo del **99 %** durante los periodos en los que el sistema se encuentre habilitado para los usuarios.

### Usabilidad

* Diseñar interfaces sencillas que permitan registrar productos, consultar inventarios y registrar ventas sin requerir conocimientos técnicos avanzados.

### Rendimiento

* Procurar que las consultas principales del catálogo y del inventario tengan un tiempo de respuesta menor o igual a **2 segundos** en condiciones normales de operación.

### Seguridad

* Proteger la información de usuarios, productos, inventarios y ventas mediante controles de acceso, validación de datos y buenas prácticas de programación.

### Mantenibilidad

* Mantener código organizado, documentado y versionado en GitHub para facilitar futuras modificaciones y correcciones.

### Accesibilidad

* Diseñar interfaces que puedan utilizarse desde equipos con recursos limitados y considerando diferentes niveles de alfabetización digital.

### Adaptación al contexto regional

* Considerar las limitaciones de conectividad de algunas comunidades de la Mixteca, evitando depender de procesos que requieran constantemente grandes cantidades de datos.

---

# 3. Alcance del Plan de Calidad

El Plan de Calidad se aplicará a las principales funcionalidades contempladas en el Product Backlog:

* Catálogo digital de artesanías.
* Registro y consulta de productos.
* Control de inventario.
* Registro de ventas.
* Gestión de información de los artesanos.
* Generación de reportes.
* Registro de información para seguimiento del impacto.
* Documentación y control del código fuente.
* Pruebas funcionales y de usabilidad.
* Revisión de historias de usuario.
* Control de versiones mediante GitHub.

El plan será aplicado durante las etapas de **análisis, diseño, desarrollo, pruebas y revisión de los incrementos del proyecto**.

---

# 4. Criterios de Calidad

| Criterio           | Objetivo                                       | Indicador                             | Meta         |
| ------------------ | ---------------------------------------------- | ------------------------------------- | ------------ |
| **Usabilidad**     | Facilitar el uso del sistema                   | Tareas completadas correctamente      | ≥ 90 %       |
| **Rendimiento**    | Reducir tiempos de espera                      | Tiempo promedio de respuesta          | ≤ 2 segundos |
| **Confiabilidad**  | Reducir errores durante la operación           | Casos exitosos                        | ≥ 95 %       |
| **Seguridad**      | Proteger información                           | Vulnerabilidades críticas encontradas | 0            |
| **Mantenibilidad** | Facilitar modificaciones                       | Incidencias de código documentadas    | 100 %        |
| **Accesibilidad**  | Facilitar el uso por diferentes usuarios       | Funciones accesibles                  | ≥ 90 %       |
| **Compatibilidad** | Permitir funcionamiento en equipos disponibles | Pruebas satisfactorias                | ≥ 95 %       |

---

# 5. Integración de CMMI y MoProSoft

La aplicación de **CMMI y MoProSoft** no se realizará como una implementación completa de estos modelos, sino como una adaptación de sus prácticas al contexto académico y al tamaño del proyecto **Open Hub Tec**.

## 5.1 Aplicación de CMMI

| Práctica                     | Aplicación en el proyecto                                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Gestión de requisitos**    | Las historias de usuario se documentarán mediante el formato Como/Quiero/Para y criterios de aceptación.                       |
| **Planificación**            | Las actividades se organizarán mediante el Product Backlog y el tablero eduScrum.                                              |
| **Gestión de configuración** | El código y documentos importantes serán controlados mediante GitHub.                                                          |
| **Medición y análisis**      | Se utilizarán métricas de calidad, tiempos de respuesta, errores y pruebas realizadas.                                         |
| **Verificación**             | Cada funcionalidad será revisada mediante pruebas antes de considerarse terminada.                                             |
| **Validación**               | Las historias de usuario serán comparadas con sus criterios de aceptación para comprobar que resuelvan la necesidad planteada. |
| **Gestión de riesgos**       | Se identificarán riesgos relacionados con conectividad, seguridad, errores de datos y disponibilidad.                          |

## 5.2 Aplicación de MoProSoft

| Categoría                       | Aplicación en el proyecto                                          |
| ------------------------------- | ------------------------------------------------------------------ |
| **Dirección**                   | Definición de objetivos y prioridades del proyecto.                |
| **Gestión**                     | Organización de actividades, recursos, tiempos, riesgos y calidad. |
| **Operación**                   | Desarrollo, integración, pruebas y entrega de las funcionalidades. |
| **Administración de proyectos** | Seguimiento del Product Backlog, sprints y actividades del equipo. |
| **Desarrollo y mantenimiento**  | Diseño, programación, pruebas y corrección de errores.             |

---

# 6. Relación con las Fases del Proyecto

| Fase           | CMMI                      | MoProSoft  | Aplicación                          |
| -------------- | ------------------------- | ---------- | ----------------------------------- |
| **Análisis**   | Gestión de requisitos     | Desarrollo | Revisión de historias de usuario    |
| **Planeación** | Planificación             | Gestión    | Organización del Sprint             |
| **Desarrollo** | Gestión de configuración  | Desarrollo | Programación y control de versiones |
| **Pruebas**    | Verificación y validación | Operación  | Ejecución de pruebas                |
| **Revisión**   | Medición y análisis       | Gestión    | Evaluación de métricas              |
| **Entrega**    | Validación                | Operación  | Revisión del incremento             |

---

# 7. Historias de Usuario y Calidad

Las principales historias de usuario consideradas para el análisis de calidad son:

## HU-01. Catálogo digital

**Como** artesano,
**quiero** registrar y mostrar mis ollas de barro y canastas tejidas,
**para** que los posibles compradores puedan consultar los productos disponibles.

## HU-02. Control de inventario

**Como** artesano,
**quiero** registrar las piezas disponibles y actualizar sus cantidades,
**para** evitar errores en el inventario.

## HU-03. Registro de ventas

**Como** artesano,
**quiero** registrar las ventas realizadas,
**para** llevar un control de mis operaciones comerciales.

## HU-04. Reportes e información de impacto

**Como** responsable del proyecto,
**quiero** generar información relacionada con productos, ventas e impacto,
**para** facilitar el seguimiento y la transparencia del proyecto.

---

# 8. Análisis del Costo de la Calidad (CoQ)

El Costo de la Calidad se analizará mediante la comparación entre el esfuerzo utilizado para prevenir y detectar errores y el esfuerzo estimado para corregirlos después de que ocurran.

Para este proyecto se utilizará la siguiente relación:

### Índice de prevención/corrección

**Índice de prevención/corrección = Horas de prevención ÷ Horas de corrección**

También se calculará el ahorro potencial:

**Ahorro potencial = Horas de corrección − Horas de prevención**

Un mayor ahorro potencial indica que las actividades preventivas pueden evitar una cantidad importante de trabajo posterior.

---

# 9. Costo de Calidad por Historia de Usuario

| ID        | Historia de Usuario   | Prevención / inspección | Corrección estimada | Relación P/C | Ahorro potencial |
| --------- | --------------------- | ----------------------: | ------------------: | -----------: | ---------------: |
| **HU-01** | Catálogo digital      |                     4 h |                10 h |         0.40 |              6 h |
| **HU-02** | Control de inventario |                     5 h |                12 h |         0.42 |              7 h |
| **HU-03** | Registro de ventas    |                     6 h |                15 h |         0.40 |              9 h |
| **HU-04** | Reportes e impacto    |                     3 h |                 8 h |         0.38 |              5 h |
| **Total** |                       |                **18 h** |            **45 h** |     **0.40** |         **27 h** |

## Interpretación

De acuerdo con la estimación realizada, las cuatro historias de usuario requieren aproximadamente **18 horas de actividades preventivas y de inspección**, mientras que una corrección posterior de los problemas podría representar aproximadamente **45 horas**.

Por lo tanto, las actividades preventivas podrían evitar aproximadamente **27 horas de trabajo correctivo y validaciones** antes de considerar una historia como terminada.

---

# 10. Adaptación a la Región Mixteca

El contexto regional es un elemento importante del Plan de Calidad, debido a que el sistema estará orientado a artesanos que pueden trabajar bajo diferentes condiciones de infraestructura tecnológica.

Por esta razón se consideran las siguientes situaciones:

| Situación                              | Riesgo                      | Acción de calidad                      |
| -------------------------------------- | --------------------------- | -------------------------------------- |
| **Conectividad limitada**              | Interrupción de operaciones | Reducir cantidad de datos transferidos |
| **Equipos con pocos recursos**         | Lentitud                    | Diseñar interfaces ligeras             |
| **Diferentes conocimientos digitales** | Dificultad de uso           | Utilizar interfaces sencillas          |
| **Errores de captura**                 | Información incorrecta      | Validar campos                         |
| **Pérdida de información**             | Afectación del inventario   | Implementar mecanismos de respaldo     |
| **Falta de experiencia técnica**       | Dificultad de mantenimiento | Documentar el sistema                  |
| **Diferentes dispositivos**            | Problemas de visualización  | Realizar pruebas de compatibilidad     |

---

# 11. Métricas de Calidad

Para comprobar objetivamente la calidad del sistema se utilizarán las siguientes métricas.

## 11.1 Rendimiento

**Fórmula:**

> Tiempo promedio = Σ tiempos de respuesta / número de pruebas

**Meta:** ≤ 2 segundos en consultas principales.

## 11.2 Tasa de errores

**Fórmula:**

> Tasa de errores = (Errores encontrados / Pruebas realizadas) × 100

**Meta:** mantener una tasa de errores baja y corregir los errores críticos antes de liberar una funcionalidad.

## 11.3 Cumplimiento de historias

**Fórmula:**

> Cumplimiento = (Historias aceptadas / Historias terminadas) × 100

**Meta:** ≥ 95 %.

## 11.4 Cobertura de pruebas

**Fórmula:**

> Cobertura = (Funciones probadas / Funciones identificadas) × 100

**Meta:** ≥ 90 %.

## 11.5 Incidencias críticas

**Meta:** 0 incidencias críticas pendientes al finalizar un Sprint.

---

# 12. Criterios de Aceptación de Calidad

Una historia de usuario podrá considerarse terminada cuando:

1. Cumpla con su descripción.
2. Cumpla todos sus criterios de aceptación.
3. Haya sido revisada por el equipo.
4. Se hayan realizado las pruebas correspondientes.
5. No presente errores críticos.
6. Se encuentre registrada correctamente en GitHub.
7. Se encuentre integrada con las demás funcionalidades cuando corresponda.
8. La documentación necesaria esté actualizada.

---

# 13. Uso de Inteligencia Artificial para la Auditoría de Calidad

La Inteligencia Artificial se utilizará como herramienta de apoyo para revisar las historias de usuario y detectar posibles problemas antes de iniciar su desarrollo.

La IA no sustituirá la decisión del equipo. Las sugerencias obtenidas serán revisadas por los integrantes y podrán ser **aceptadas, modificadas o rechazadas**.

## 13.1 Prompt de auditoría de historias de usuario

```text
Actúa como auditor de calidad de software. Analiza la siguiente historia de usuario utilizando el formato Como/Quiero/Para. Identifica ambigüedades, requisitos incompletos, posibles errores, criterios de aceptación faltantes, riesgos de seguridad, problemas de usabilidad y aspectos relacionados con el contexto de conectividad limitada de la región Mixteca.

Propón mejoras concretas y separa tus observaciones en: problemas detectados, propuesta de mejora y criterio de aceptación sugerido.
```

## 13.2 Prompt para criterios de aceptación

```text
Analiza esta historia de usuario y genera criterios de aceptación verificables utilizando condiciones claras. Los criterios deben permitir comprobar mediante pruebas si la historia fue implementada correctamente. Considera usabilidad, rendimiento, seguridad y funcionamiento con conectividad limitada.
```

## 13.3 Prompt para métricas

```text
A partir de esta historia de usuario, propone métricas objetivas para evaluar su calidad. Incluye nombre de la métrica, fórmula, unidad de medida, meta y método de verificación.
```

## 13.4 Prompt para revisión de riesgos

```text
Analiza esta funcionalidad de un sistema de gestión comercial para artesanos de la región Mixteca. Identifica riesgos relacionados con conectividad, pérdida de información, errores de captura, seguridad, rendimiento y usabilidad.

Para cada riesgo indica su posible impacto y una medida preventiva.
```

---

# 14. Registro de Auditoría de IA

| Historia  | Aspecto revisado         | Resultado de IA                                                | Decisión del equipo |
| --------- | ------------------------ | -------------------------------------------------------------- | ------------------- |
| **HU-01** | Criterios de aceptación  | Se detectó necesidad de validar imágenes y datos del producto. | Aceptada            |
| **HU-02** | Validación de inventario | Se recomendó validar cantidades y evitar valores negativos.    | Aceptada            |
| **HU-03** | Seguridad                | Se recomendó validar datos de acceso y transacciones.          | Aceptada            |
| **HU-04** | Reportes                 | Se recomendó definir datos mínimos necesarios.                 | Aceptada            |

---

# 15. Plan de Pruebas

| Tipo de prueba               | Objetivo                                          | Responsable            | Momento                  |
| ---------------------------- | ------------------------------------------------- | ---------------------- | ------------------------ |
| **Prueba funcional**         | Comprobar que cada función opere correctamente    | Equipo                 | Durante desarrollo       |
| **Prueba de usabilidad**     | Comprobar facilidad de uso                        | Equipo                 | Al finalizar cada módulo |
| **Prueba de rendimiento**    | Medir tiempos de respuesta                        | Equipo                 | Antes de entrega         |
| **Prueba de seguridad**      | Identificar vulnerabilidades básicas              | Equipo                 | Durante integración      |
| **Prueba de compatibilidad** | Revisar funcionamiento en diferentes dispositivos | Equipo                 | Antes de entrega         |
| **Prueba de aceptación**     | Verificar criterios de las historias              | Product Owner / equipo | Fin del Sprint           |

---

# 16. Gestión de Defectos

Los errores encontrados se registrarán en el tablero del proyecto.

Se utilizarán las siguientes categorías:

* **Crítico:** impide utilizar una función principal.
* **Alto:** afecta considerablemente una función.
* **Medio:** afecta parcialmente una función.
* **Bajo:** problema visual o de poca afectación.

Los defectos críticos deberán ser atendidos antes de considerar terminada la historia correspondiente.

---

# 17. Control de Versiones y Documentación

GitHub será utilizado como herramienta para mantener el control de versiones del proyecto.

Se deberán conservar:

* Código fuente.
* Historias de usuario.
* Criterios de aceptación.
* Documentación.
* Evidencias de pruebas.
* Registro de cambios.
* Archivos relacionados con la configuración del proyecto.

Cada modificación importante deberá quedar identificada mediante un **commit** que permita conocer qué cambio fue realizado.

---

# 18. Seguimiento mediante eduScrum

El Plan de Calidad se integrará al trabajo del equipo mediante el tablero eduScrum.

Las actividades podrán organizarse mediante las siguientes etapas:

**Propuestas → En estudio → Aprobada por el equipo → En desarrollo → En pruebas → Terminada**

También podrá utilizarse una columna de **Descartadas** cuando una propuesta no sea viable para el proyecto.

El tablero permitirá observar el avance de las actividades y detectar retrasos o problemas de calidad.

---

# 19. Relación entre Calidad y Product Backlog

Cada historia de usuario deberá contar con:

1. Identificador.
2. Descripción.
3. Criterios de aceptación.
4. Prioridad.
5. Riesgos identificados.
6. Actividades de prevención.
7. Pruebas necesarias.
8. Resultado de las pruebas.
9. Estado de la historia.
10. Evidencia de aceptación.

Esto permitirá relacionar directamente el Plan de Calidad con el Product Backlog.

---

# 20. Fuentes Externas y Complementarias

Como apoyo para la elaboración del Plan de Calidad se consideran fuentes relacionadas con:

* CMMI y mejora de procesos de desarrollo de software.
* MoProSoft y modelos de procesos para organizaciones de software.
* Calidad de software.
* Ingeniería de requisitos.
* Pruebas de software.
* Gestión de proyectos ágiles.
* Open Source.
* Documentación de Stellar y Drips para los aspectos relacionados con el proyecto.

Las fuentes deberán registrarse en formato **APA** en la versión final del documento.

---

# 21. Evidencias de Calidad

Como evidencia del cumplimiento del Plan de Calidad se conservarán:

* Historias de usuario revisadas.
* Criterios de aceptación.
* Capturas del tablero eduScrum.
* Evidencias de pruebas.
* Registro de errores.
* Evidencias de GitHub.
* Resultados de las métricas.
* Registro de auditoría mediante IA.
* Cálculos del Costo de la Calidad.
* Revisiones realizadas por el equipo.
* Documentación del proyecto.

---

# 22. Responsabilidades del Equipo

| Actividad                             | Responsable            |
| ------------------------------------- | ---------------------- |
| Revisión de historias de usuario      | Equipo                 |
| Revisión mediante IA                  | Equipo                 |
| Desarrollo                            | Equipo                 |
| Pruebas                               | Equipo                 |
| Control de versiones                  | Equipo                 |
| Registro de errores                   | Equipo                 |
| Seguimiento del tablero               | eduScrum Master        |
| Validación de criterios de aceptación | Equipo / Product Owner |
| Actualización del Plan de Calidad     | Equipo                 |

---

# 23. Conclusiones

El presente Plan de Calidad permite establecer una estrategia organizada para controlar la calidad del **Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano**.

La adaptación de prácticas de CMMI y MoProSoft permite relacionar la gestión de requisitos, planificación, desarrollo, pruebas, medición y control de cambios con las actividades del proyecto **Open Hub Tec**.

El análisis del Costo de la Calidad muestra que invertir tiempo en prevención, revisión y pruebas puede reducir el esfuerzo necesario para corregir errores posteriormente.

Asimismo, la consideración del contexto de la región Mixteca permite que la calidad no se limite únicamente al funcionamiento técnico del software, sino que también considere aspectos como conectividad limitada, facilidad de uso, recursos tecnológicos disponibles y diferentes niveles de experiencia digital.

Finalmente, el uso de Inteligencia Artificial como herramienta de apoyo para auditar historias de usuario, generar criterios de aceptación, identificar riesgos y proponer métricas fortalece el proceso de revisión.

---

# 24. Bibliografía

# Referencias
# 24. Referencias

* CMMI Institute. (2026, 25 de agosto). *CMMI model quick reference guide*. https://cmmiinstitute.com/resource-files/public/cmmi-model-quick-reference-guide

* Drips Network. (s. f.). *Overview*. Drips Docs. https://docs.drips.network/the-protocol/overview/

* GitHub. (s. f.). *GitHub Docs*. https://docs.github.com/es

* Oktaba, H., Alquicira Esquivel, C., Su Ramos, A., Martínez Martínez, A., Quintanilla Osorio, G., Ruvalcaba López, M., López Lira Hinojo, F., Rivera López, M. E., Orozco Mendoza, M. J., Fernández Ordóñez, Y., & Flores Lemus, M. A. (2003). *Modelo de Procesos para la Industria de Software (MoProSoft)*. Secretaría de Economía. https://www.red-tic.unam.mx/content/modelo-de-procesos-para-la-industria-de-software-moprosoft

* Stellar Development Foundation. (s. f.). *Grants and funding*. Stellar. https://stellar.org/grants-and-funding

* Stellar Development Foundation. (s. f.). *Stellar Community Fund*. https://communityfund.stellar.org/
