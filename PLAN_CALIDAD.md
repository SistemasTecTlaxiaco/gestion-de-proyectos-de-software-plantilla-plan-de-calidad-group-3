# PLAN DE CALIDAD DEL PROYECTO

## Gestión de Proyectos de Software

**Proyecto:** Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano

**Asignatura:** Gestión de Proyectos de Software

**Unidad:** 2

**Documento:** Plan de Calidad

**Grupo:** 7US

**Fecha:** Septiembre de 2026

**Institución:** Instituto Tecnológico de Tlaxiaco

**Carrera:** Ingeniería en Sistemas Computacionales

**Docente:** Ing. Roman Cruz José Alfredo

---

## Integrantes

| Nombre                        | Número de control |
| ----------------------------- | ----------------- |
| Sandoval Hernández Edgar Axel | 22620093          |
| Adriana Hernández Martínez    | 22620083          |

---

# 1. Introducción

El presente Plan de Calidad establece los criterios, actividades, métricas y responsabilidades que se utilizarán para asegurar la calidad del **Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano**.

El proyecto está orientado a apoyar a los artesanos de la Región Mixteca, principalmente en el registro de productos, control de inventario, registro de ventas y generación de información relacionada con sus actividades comerciales.

El Plan de Calidad considera aspectos como la usabilidad, rendimiento, confiabilidad, seguridad, mantenibilidad, accesibilidad y compatibilidad.

También se integran prácticas de **CMMI**, **MoProSoft**, eduScrum y auditoría mediante Inteligencia Artificial (IA), con el propósito de organizar el desarrollo y facilitar la revisión de la calidad del proyecto.

---

# 2. Objetivos de Calidad

## 2.1 Objetivo general

Garantizar que el sistema cumpla con los requisitos establecidos y proporcione una solución funcional, confiable, segura y fácil de utilizar, considerando las condiciones tecnológicas y necesidades de los artesanos de la Región Mixteca.

## 2.2 Objetivos específicos

* **Confiabilidad:** Reducir errores y asegurar que la información registrada se conserve correctamente.
* **Usabilidad:** Diseñar una interfaz sencilla y fácil de utilizar.
* **Rendimiento:** Procurar tiempos de respuesta adecuados para las operaciones principales.
* **Seguridad:** Proteger la información y evitar vulnerabilidades críticas.
* **Mantenibilidad:** Mantener el código documentado y organizado para facilitar futuras modificaciones.
* **Accesibilidad:** Permitir que diferentes usuarios puedan utilizar el sistema.
* **Compatibilidad:** Procurar que el sistema funcione correctamente en diferentes dispositivos.
* **Adaptación al contexto regional:** Considerar problemas como conectividad limitada, equipos de bajos recursos y diferentes niveles de conocimiento tecnológico.

---

# 3. Alcance del Plan de Calidad

El presente Plan de Calidad comprende las actividades relacionadas con:

* Análisis de requisitos.
* Planeación del proyecto.
* Desarrollo del sistema.
* Pruebas funcionales y no funcionales.
* Revisión de historias de usuario.
* Revisión mediante Inteligencia Artificial.
* Control de errores y defectos.
* Control de versiones mediante GitHub.
* Documentación del proyecto.
* Evaluación de métricas de calidad.
* Evidencias de pruebas y aceptación.
* Revisión del cumplimiento de las historias de usuario.
* Seguimiento mediante eduScrum.

El plan será aplicado durante las diferentes etapas del desarrollo del sistema.

---

# 4. Criterios de Calidad

| Criterio de calidad | Meta                             |
| ------------------- | -------------------------------- |
| Usabilidad          | ≥ 90 %                           |
| Rendimiento         | ≤ 2 segundos                     |
| Confiabilidad       | ≥ 95 %                           |
| Seguridad           | 0 vulnerabilidades críticas      |
| Mantenibilidad      | 100 % de incidentes documentados |
| Accesibilidad       | ≥ 90 %                           |
| Compatibilidad      | ≥ 95 %                           |

Estos criterios servirán como referencia para verificar el nivel de calidad alcanzado por el sistema.

---

# 5. Integración de CMMI y MoProSoft

Para fortalecer la calidad del proyecto se consideran prácticas de **CMMI** y procesos de **MoProSoft**.

## 5.1 Prácticas consideradas de CMMI

Se consideran las siguientes prácticas:

* Gestión de requisitos.
* Planeación del proyecto.
* Gestión de configuración.
* Medición y análisis.
* Verificación.
* Validación.
* Gestión de riesgos.

Estas prácticas permiten organizar las actividades del proyecto y verificar que los productos desarrollados cumplan con los requisitos establecidos.

## 5.2 Procesos considerados de MoProSoft

Se consideran los siguientes procesos:

* Dirección.
* Gestión.
* Operación.
* Administración de proyectos.
* Desarrollo y mantenimiento.

La integración de estos modelos permite establecer una forma organizada de planear, desarrollar, revisar y mejorar el sistema.

---

# 6. Relación con las fases del proyecto

| Fase       | CMMI                      | MoProSoft                   | Aplicación en el proyecto                      |
| ---------- | ------------------------- | --------------------------- | ---------------------------------------------- |
| Análisis   | Gestión de requisitos     | Desarrollo                  | Identificación de necesidades de los artesanos |
| Planeación | Planeación del proyecto   | Administración de proyectos | Definición de actividades y recursos           |
| Desarrollo | Gestión de configuración  | Desarrollo y mantenimiento  | Elaboración del sistema                        |
| Pruebas    | Verificación y validación | Desarrollo y mantenimiento  | Comprobación del funcionamiento                |
| Revisión   | Medición y análisis       | Gestión                     | Evaluación de métricas y resultados            |
| Entrega    | Validación                | Operación                   | Entrega de una versión funcional               |

---

# 7. Historias de Usuario y Calidad

Las historias de usuario permiten definir las funciones principales que deberá cumplir el sistema y los criterios que se utilizarán para evaluar su calidad.

## 7.1 HU-01: Catálogo digital de artesanías

**Como** artesano
**Quiero** registrar y mostrar mis ollas de barro y canastas tejidas
**Para** que los compradores conozcan los productos disponibles.

### Criterios de aceptación

* Registrar el nombre, descripción y precio del producto.
* Validar que los campos obligatorios estén completos.
* Permitir consultar los productos registrados.
* Mostrar la información de manera clara.
* Conservar correctamente la información registrada.

### Aspectos de calidad

* Usabilidad.
* Seguridad.
* Rendimiento.
* Confiabilidad.

---

## 7.2 HU-02: Control de inventario

**Como** artesano
**Quiero** controlar la cantidad de productos disponibles
**Para** conocer mi inventario actual.

### Criterios de aceptación

* Registrar productos y cantidades disponibles.
* Actualizar las cantidades del inventario.
* Evitar que se registren cantidades negativas.
* Mostrar la información del inventario de forma clara.
* Conservar correctamente los cambios realizados.

### Aspectos de calidad

* Usabilidad.
* Seguridad.
* Rendimiento.
* Confiabilidad.

---

## 7.3 HU-03: Registro de ventas

**Como** artesano
**Quiero** registrar mis ventas
**Para** llevar un control de mis transacciones.

### Criterios de aceptación

* Registrar correctamente una venta.
* Validar los datos antes de guardar la información.
* Conservar correctamente la información de la venta.
* Actualizar el inventario cuando se registre una venta.
* Evitar registros duplicados.

### Aspectos de calidad

* Usabilidad.
* Seguridad.
* Rendimiento.
* Confiabilidad.

---

## 7.4 HU-04: Reportes e información de impacto

**Como** responsable del proyecto
**Quiero** generar información relacionada con productos, ventas e impacto
**Para** facilitar el seguimiento y la transparencia del proyecto.

### Criterios de aceptación

* Consultar la información registrada.
* Mostrar reportes de manera clara.
* Verificar que los datos de los reportes coincidan con la información almacenada.
* Permitir consultar productos y ventas.
* Mostrar resultados que apoyen el seguimiento de la actividad del proyecto.

### Aspectos de calidad

* Usabilidad.
* Rendimiento.
* Confiabilidad.
* Seguridad.

---

# 8. Costo de la Calidad

El Costo de la Calidad permite analizar el esfuerzo necesario para prevenir y corregir errores durante el desarrollo del proyecto.

Se utilizarán las siguientes fórmulas:

## 8.1 Índice de prevención/corrección

**Índice de prevención/corrección = Horas de prevención ÷ Horas de corrección**

## 8.2 Ahorro potencial

**Ahorro potencial = Horas de corrección − Horas de prevención**

Estas fórmulas permiten comparar el tiempo utilizado para prevenir problemas con el tiempo necesario para corregirlos.

---

# 9. Costo de Calidad por Historia de Usuario

| Historia de Usuario | Horas de prevención | Horas de corrección |   Índice | Ahorro potencial |
| ------------------- | ------------------: | ------------------: | -------: | ---------------: |
| HU-01               |                 4 h |                10 h |     0.40 |              6 h |
| HU-02               |                 5 h |                12 h |     0.42 |              7 h |
| HU-03               |                 6 h |                15 h |     0.40 |              9 h |
| HU-04               |                 3 h |                 8 h |     0.38 |              5 h |
| **Total**           |            **18 h** |            **45 h** | **0.40** |         **27 h** |

De acuerdo con estos datos, se consideran **18 horas de prevención** y **45 horas de corrección**, lo que representa un ahorro potencial de **27 horas** mediante actividades preventivas.

El detalle del Costo de la Calidad se encuentra en:

[`costo-calidad/costo-calidad-historias.md`](./costo-calidad/costo-calidad-historias.md)

---

# 10. Adaptación al contexto de la Región Mixteca

El sistema debe considerar las condiciones tecnológicas y sociales del contexto en el que será utilizado.

| Situación identificada             | Riesgo                              | Acción de calidad                                 |
| ---------------------------------- | ----------------------------------- | ------------------------------------------------- |
| Conectividad limitada              | Pérdida de comunicación             | Optimizar el sistema para consumir pocos recursos |
| Equipos de bajos recursos          | Bajo rendimiento                    | Reducir procesos innecesarios                     |
| Diferentes conocimientos digitales | Dificultad para utilizar el sistema | Diseñar una interfaz sencilla                     |
| Errores de captura                 | Información incorrecta              | Implementar validaciones                          |
| Pérdida de información             | Datos incompletos                   | Utilizar mecanismos de respaldo                   |
| Falta de experiencia técnica       | Dificultad de mantenimiento         | Documentar el sistema                             |
| Diferentes dispositivos            | Problemas de compatibilidad         | Realizar pruebas en diferentes dispositivos       |

---

# 11. Métricas de Calidad

Las métricas permitirán verificar el cumplimiento de los objetivos de calidad.

## 11.1 Rendimiento

**Tiempo promedio de respuesta = Tiempo total de respuesta ÷ Número de solicitudes**

**Meta:** ≤ 2 segundos.

## 11.2 Tasa de errores

**Tasa de errores = Errores encontrados ÷ Pruebas realizadas × 100**

Esta métrica permitirá conocer la cantidad de errores encontrados durante las pruebas.

## 11.3 Cumplimiento de historias de usuario

**Cumplimiento = Historias de usuario terminadas ÷ Historias de usuario planificadas × 100**

**Meta:** ≥ 95 %.

## 11.4 Cobertura de pruebas

**Cobertura de pruebas = Casos de prueba ejecutados ÷ Casos de prueba planificados × 100**

**Meta:** ≥ 90 %.

## 11.5 Incidentes críticos

**Meta:** 0 incidentes críticos pendientes al finalizar el sprint.

El detalle de las métricas se encuentra en:

[`metricas/metricas-calidad.md`](./metricas/metricas-calidad.md)

---

# 12. Criterios de Aceptación

Una historia de usuario podrá considerarse terminada cuando cumpla con las siguientes condiciones:

* Cumplir con los criterios de aceptación establecidos.
* Haber sido revisada por el equipo.
* Haber realizado las pruebas correspondientes.
* No presentar errores críticos pendientes.
* Encontrarse registrada en GitHub.
* Estar integrada correctamente al proyecto.
* Tener la documentación correspondiente actualizada.
* Contar con evidencias de las pruebas realizadas.

---

# 13. Auditoría mediante Inteligencia Artificial

La Inteligencia Artificial será utilizada como una herramienta de apoyo para revisar la calidad de las historias de usuario y detectar posibles problemas.

La IA podrá ayudar a:

* Revisar historias de usuario.
* Identificar criterios de aceptación incompletos.
* Revisar métricas.
* Detectar posibles riesgos.
* Proponer mejoras.

La IA no sustituye la decisión del equipo. Las sugerencias generadas podrán ser:

* Aceptadas.
* Modificadas.
* Rechazadas.

La decisión final será tomada por los integrantes del equipo.

Los prompts y resultados de las revisiones se encuentran en:

* [`auditoria-ia/prompts-auditoria.md`](./auditoria-ia/prompts-auditoria.md)
* [`auditoria-ia/registro-auditoria-ia.md`](./auditoria-ia/registro-auditoria-ia.md)

---

# 14. Registro de Auditoría de IA

| Historia de Usuario | Revisión realizada                                  | Resultado |
| ------------------- | --------------------------------------------------- | --------- |
| HU-01               | Validación de información y criterios de aceptación | Aceptada  |
| HU-02               | Validación del inventario y cantidades negativas    | Aceptada  |
| HU-03               | Revisión de seguridad y transacciones               | Aceptada  |
| HU-04               | Revisión de reportes y criterios de aceptación      | Aceptada  |

Las revisiones se realizaron como apoyo al análisis del equipo.

---

# 15. Plan de Pruebas

Las pruebas permitirán verificar el funcionamiento del sistema y el cumplimiento de los criterios de aceptación.

| Tipo de prueba | Objetivo                                            | Responsable | Momento                 |
| -------------- | --------------------------------------------------- | ----------- | ----------------------- |
| Funcional      | Verificar las funciones del sistema                 | Equipo      | Durante el desarrollo   |
| Validación     | Comprobar los datos registrados                     | Equipo      | Durante el desarrollo   |
| Usabilidad     | Comprobar facilidad de uso                          | Equipo      | Después de cada función |
| Rendimiento    | Medir tiempos de respuesta                          | Equipo      | Durante las pruebas     |
| Seguridad      | Detectar vulnerabilidades                           | Equipo      | Antes de la entrega     |
| Confiabilidad  | Verificar conservación de información               | Equipo      | Durante las pruebas     |
| Compatibilidad | Comprobar funcionamiento en diferentes dispositivos | Equipo      | Durante las pruebas     |
| Aceptación     | Comprobar cumplimiento de requisitos                | Equipo      | Al finalizar            |

Actualmente, los casos de prueba se encuentran documentados y **pendientes de ejecución**, ya que las pruebas se realizarán conforme avance el desarrollo.

El detalle de los casos de prueba se encuentra en:

[`pruebas/plan-de-pruebas.md`](./pruebas/plan-de-pruebas.md)

---

# 16. Gestión de Defectos

Los defectos encontrados durante el desarrollo y las pruebas del sistema serán identificados, registrados y atendidos mediante un proceso de seguimiento.

El proceso de gestión de defectos será:

**Identificar → Registrar → Analizar → Corregir → Verificar → Cerrar**

## 16.1 Clasificación de defectos

| Prioridad | Descripción                                                                                      | Acción                       |
| --------- | ------------------------------------------------------------------------------------------------ | ---------------------------- |
| Alta      | El defecto impide utilizar una función importante o afecta información relevante.                | Corregir prioritariamente.   |
| Media     | El defecto afecta una función, pero existe una alternativa para continuar utilizando el sistema. | Programar su corrección.     |
| Baja      | El defecto tiene un impacto menor y no impide utilizar las funciones principales.                | Corregir cuando sea posible. |

## 16.2 Estados de los defectos

Los estados utilizados para dar seguimiento serán:

**Abierto → En corrección → Verificado → Cerrado**

* **Abierto:** el defecto fue identificado y registrado.
* **En corrección:** se está trabajando en la solución.
* **Verificado:** se comprobó que la corrección funciona correctamente.
* **Cerrado:** el defecto fue solucionado y validado.

Los defectos críticos deberán corregirse antes de considerar terminada una historia de usuario.

Actualmente no se registran defectos encontrados sin evidencia, debido a que las pruebas todavía están pendientes.

El registro detallado se encuentra en:

[`defectos/gestion-defectos.md`](./defectos/gestion-defectos.md)

---

# 17. Control de Versiones y Documentación

GitHub será utilizado como herramienta para administrar el código y la documentación del proyecto.

Se almacenarán:

* Código fuente.
* Historias de usuario.
* Criterios de aceptación.
* Documentación.
* Evidencias de pruebas.
* Registro de cambios.
* Configuraciones necesarias.
* Evidencias del tablero eduScrum.

Los cambios importantes deberán identificarse mediante **commits descriptivos**, permitiendo conocer las modificaciones realizadas durante el desarrollo.

---

# 18. Flujo eduScrum

El proyecto utilizará el siguiente flujo para organizar las actividades:

**Tareas/Propuestas → Revisión con IA → Aprobado por el equipo → En proceso → Terminada**

También se considera la columna:

**Descartadas**

para aquellas propuestas que no sean seleccionadas por el equipo.

Este flujo permitirá visualizar el avance de las actividades y facilitará el seguimiento del trabajo.

La evidencia del tablero se encuentra en:

[`evidencias/tablero-eduscrum.png`](./evidencias/tablero-eduscrum.png)

---

# 19. Calidad y Product Backlog

Cada elemento del Product Backlog deberá considerar información relacionada con la calidad.

| Elemento                  | Descripción                      |
| ------------------------- | -------------------------------- |
| ID                        | Identificador de la historia     |
| Descripción               | Función solicitada               |
| Criterios de aceptación   | Condiciones que debe cumplir     |
| Prioridad                 | Importancia dentro del proyecto  |
| Riesgos                   | Posibles problemas               |
| Actividades de prevención | Acciones para evitar errores     |
| Pruebas                   | Pruebas necesarias               |
| Resultado                 | Resultado obtenido               |
| Estado                    | Situación actual de la actividad |
| Evidencia                 | Capturas, documentos o registros |

---

# 20. Fuentes Externas y Complementarias

Para complementar el Plan de Calidad se consideran fuentes relacionadas con:

* CMMI.
* MoProSoft.
* Calidad de software.
* Ingeniería de requisitos.
* Pruebas de software.
* Gestión ágil de proyectos.
* Open Source.
* Stellar.
* Drips.

Estas fuentes sirven como apoyo para establecer prácticas relacionadas con la calidad, gestión del proyecto y tecnologías consideradas dentro del contexto del proyecto.

---

# 21. Evidencias de Calidad

Las evidencias del cumplimiento del Plan de Calidad podrán incluir:

* Historias de usuario revisadas.
* Criterios de aceptación.
* Capturas del tablero eduScrum.
* Evidencias de pruebas.
* Registro de errores.
* Evidencias de GitHub.
* Resultados de métricas.
* Registro de auditoría mediante IA.
* Cálculos del Costo de la Calidad.
* Revisiones realizadas por el equipo.
* Documentación del proyecto.

Las evidencias serán almacenadas y organizadas dentro del repositorio de GitHub.

La organización de las evidencias se encuentra en:

[`evidencias/README.md`](./evidencias/README.md)

---

# 22. Responsabilidades del Equipo

| Responsable          | Actividades                                 |
| -------------------- | ------------------------------------------- |
| Equipo de desarrollo | Desarrollo, pruebas y corrección de errores |
| Product Owner        | Revisión de requisitos y aceptación         |
| eduScrum Master      | Organización y seguimiento del trabajo      |
| Equipo               | Revisión de calidad y toma de decisiones    |
| Equipo               | Registro de evidencias en GitHub            |

Todos los integrantes deberán participar en las actividades de revisión y seguimiento de la calidad.

---

# 23. Estado del Plan de Calidad

El Plan de Calidad se encuentra en proceso de desarrollo y actualización conforme avance el proyecto.

Actualmente se cuenta con la documentación de:

* Historias de usuario.
* Métricas de calidad.
* Plan de pruebas.
* Auditoría mediante IA.
* Costo de la Calidad.
* Gestión de defectos.
* Evidencias.
* Organización del trabajo mediante eduScrum.

Las pruebas y sus evidencias se incorporarán conforme avance el desarrollo y se realicen las comprobaciones correspondientes.

---

# 24. Conclusiones

El Plan de Calidad permite establecer una guía para asegurar que el **Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano** cumpla con los requisitos definidos y mantenga un nivel adecuado de calidad.

La integración de prácticas de CMMI y MoProSoft permite organizar las actividades de desarrollo, mientras que eduScrum facilita la organización y seguimiento del trabajo del equipo.

También se consideran las condiciones particulares de la Región Mixteca, como la conectividad limitada, los equipos de bajos recursos y los diferentes niveles de conocimiento tecnológico.

Finalmente, el uso de métricas, pruebas, control de defectos, GitHub y auditoría mediante IA permitirá contar con evidencias para verificar el cumplimiento de los objetivos de calidad durante el desarrollo del proyecto.

---

# 25. Referencias

* CMMI Institute. (2026, 25 de agosto). *CMMI model quick reference guide*. https://cmmiinstitute.com/resource-files/public/cmmi-model-quick-reference-guide

* Drips Network. (s. f.). *Overview*. Drips Docs. https://docs.drips.network/the-protocol/overview/

* GitHub. (s. f.). *GitHub Docs*. https://docs.github.com/es

* Oktaba, H., Alquicira Esquivel, C., Su Ramos, A., Martínez Martínez, A., Quintanilla Osorio, G., Ruvalcaba López, M., López Lira Hinojo, F., Rivera López, M. E., Orozco Mendoza, M. J., Fernández Ordóñez, Y., & Flores Lemus, M. A. (2003). *Modelo de Procesos para la Industria de Software (MoProSoft)*. Secretaría de Economía. https://www.red-tic.unam.mx/content/modelo-de-procesos-para-la-industria-de-software-moprosoft

* Stellar Development Foundation. (s. f.). *Grants and funding*. Stellar. https://stellar.org/grants-and-funding

* Stellar Development Foundation. (s. f.). *Stellar Community Fund*. https://communityfund.stellar.org/
