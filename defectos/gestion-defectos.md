# Gestión de Defectos

## Proyecto

**Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano**

**Asignatura:** Gestión de Proyectos de Software
**Unidad:** 2
**Grupo:** 7US
**Institución:** Instituto Tecnológico de Tlaxiaco
**Carrera:** Ingeniería en Sistemas Computacionales
**Fecha:** Septiembre de 2026

---

## 1. Objetivo

Establecer un procedimiento para identificar, registrar, analizar, corregir y dar seguimiento a los defectos encontrados durante el desarrollo y las pruebas del sistema.

La gestión de defectos permitirá mantener un registro organizado de los problemas encontrados y verificar que las correcciones realizadas funcionen correctamente.

---

## 2. ¿Qué es un defecto?

Un defecto es un comportamiento incorrecto del sistema que provoca que una función no cumpla con los requisitos establecidos o con los criterios de aceptación de una historia de usuario.

Los defectos pueden encontrarse durante el desarrollo, las revisiones o las pruebas del sistema.

---

## 3. Proceso de gestión de defectos

El proceso que se utilizará será:

**Identificar → Registrar → Analizar → Corregir → Verificar → Cerrar**

### Identificar

Detectar un comportamiento incorrecto o un incumplimiento de los criterios de aceptación.

### Registrar

Documentar el defecto indicando la historia de usuario relacionada, descripción, prioridad y evidencia disponible.

### Analizar

Determinar la causa del problema y definir las acciones necesarias para corregirlo.

### Corregir

Realizar los cambios necesarios en el sistema para solucionar el defecto.

### Verificar

Realizar nuevamente la prueba correspondiente para comprobar que el problema fue solucionado.

### Cerrar

Cerrar el defecto cuando la corrección haya sido verificada satisfactoriamente.

---

## 4. Clasificación de defectos

| Prioridad | Descripción                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------ |
| Alta      | El defecto impide utilizar una función importante del sistema o afecta información relevante.    |
| Media     | El defecto afecta una función, pero existe una alternativa para continuar utilizando el sistema. |
| Baja      | El defecto tiene un impacto menor y no impide utilizar las funciones principales.                |

---

## 5. Registro de defectos

Los defectos encontrados durante las pruebas se registrarán utilizando la siguiente información:

| Campo               | Descripción                                     |
| ------------------- | ----------------------------------------------- |
| ID                  | Identificador del defecto                       |
| Historia de usuario | HU relacionada con el defecto                   |
| Descripción         | Explicación del problema encontrado             |
| Prioridad           | Alta, media o baja                              |
| Evidencia           | Captura, resultado de prueba u otra evidencia   |
| Acción correctiva   | Actividad realizada para solucionar el problema |
| Estado              | Abierto, en corrección, verificado o cerrado    |

---

## 6. Estados de los defectos

Los estados utilizados serán:

**Abierto → En corrección → Verificado → Cerrado**

* **Abierto:** el defecto fue identificado y registrado.
* **En corrección:** se está trabajando en la solución.
* **Verificado:** se comprobó que la corrección funciona.
* **Cerrado:** el defecto fue solucionado y validado.

---

## 7. Tabla de seguimiento

Mientras no se hayan realizado las pruebas correspondientes, no se registrarán defectos como encontrados.

| ID | Historia de usuario | Descripción                            | Prioridad | Acción correctiva | Estado    |
| -- | ------------------- | -------------------------------------- | --------- | ----------------- | --------- |
| —  | —                   | No se han registrado defectos todavía. | —         | —                 | Pendiente |

Esta tabla se actualizará conforme avance el desarrollo y se realicen las pruebas.

---

## 8. Evidencias

Las evidencias de los defectos podrán incluir:

* Capturas de pantalla.
* Resultados de pruebas.
* Descripción del comportamiento observado.
* Cambios realizados en el código.
* Evidencia de la prueba posterior a la corrección.
* Registro correspondiente en GitHub.

---

## 9. Relación con el Plan de Calidad

La gestión de defectos forma parte del proceso de aseguramiento de la calidad del proyecto.

Su aplicación permitirá:

* Dar seguimiento a los problemas encontrados.
* Evitar que los defectos queden sin atender.
* Comprobar las correcciones realizadas.
* Mantener evidencia de las incidencias.
* Mejorar la confiabilidad del sistema.
* Apoyar el cumplimiento de los criterios de calidad establecidos.

---

## 10. Estado actual

**Estado:** Documentación inicial.

La gestión de defectos se encuentra preparada para registrar las incidencias que se detecten durante las pruebas del sistema.

No se consideran defectos encontrados hasta que se realicen las pruebas y exista evidencia que permita identificarlos y verificarlos.
