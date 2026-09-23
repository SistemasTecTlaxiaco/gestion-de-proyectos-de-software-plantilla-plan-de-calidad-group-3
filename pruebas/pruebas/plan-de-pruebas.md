# PLAN DE PRUEBAS

## 1. Información general

**Proyecto:** Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano
**Institución:** Instituto Tecnológico de Tlaxiaco
**Asignatura:** Gestión de Proyectos de Software
**Grupo:** 7US
**Integrantes:**

* Adriana Hernández Martínez – 22620083
* Sandoval Hernández Edgar Axel – 22620093

---

## 2. Objetivo

Establecer las pruebas que se realizarán al sistema para verificar que las historias de usuario cumplan con sus criterios de aceptación y que el sistema funcione de manera correcta, confiable, segura y fácil de utilizar.

---

## 3. Alcance

Las pruebas se aplicarán a las historias de usuario definidas en el Plan de Calidad:

* **HU-01 – Catálogo digital de artesanías**
* **HU-02 – Control de inventario**
* **HU-03 – Registro de ventas**
* **HU-04 – Reportes e información de impacto**

Se verificarán principalmente aspectos funcionales, de validación, usabilidad, rendimiento, seguridad y confiabilidad.

---

## 4. Tipos de pruebas

### 4.1 Pruebas funcionales

Permiten comprobar que las funciones del sistema trabajen de acuerdo con lo establecido en las historias de usuario.

### 4.2 Pruebas de validación

Permiten verificar que el sistema valide correctamente los datos introducidos por el usuario.

### 4.3 Pruebas de usabilidad

Permiten comprobar que la información y las funciones del sistema sean claras y fáciles de utilizar.

### 4.4 Pruebas de rendimiento

Permiten verificar que las funciones del sistema respondan dentro de los tiempos establecidos en el Plan de Calidad.

### 4.5 Pruebas de seguridad

Permiten verificar que los datos registrados estén protegidos y que no se permitan operaciones no autorizadas.

### 4.6 Pruebas de confiabilidad

Permiten comprobar que la información registrada se conserve correctamente y que el sistema mantenga un funcionamiento estable.

---

## 5. Casos de prueba por historia de usuario

### HU-01 – Catálogo digital de artesanías

| ID    | Caso de prueba                                                    | Resultado esperado                                    |
| ----- | ----------------------------------------------------------------- | ----------------------------------------------------- |
| CP-01 | Registrar un producto con nombre, descripción y precio.           | El producto se registra correctamente.                |
| CP-02 | Intentar registrar un producto sin completar campos obligatorios. | El sistema solicita completar los campos requeridos.  |
| CP-03 | Consultar un producto registrado.                                 | La información del producto se muestra correctamente. |
| CP-04 | Verificar la presentación de la información.                      | Los datos se muestran de forma clara.                 |
| CP-05 | Guardar un producto y consultarlo posteriormente.                 | La información permanece almacenada correctamente.    |

### HU-02 – Control de inventario

| ID    | Caso de prueba                                     | Resultado esperado                                    |
| ----- | -------------------------------------------------- | ----------------------------------------------------- |
| CP-06 | Registrar un producto con una cantidad disponible. | El producto y su cantidad se registran correctamente. |
| CP-07 | Actualizar la cantidad de un producto.             | La nueva cantidad se guarda correctamente.            |
| CP-08 | Intentar registrar una cantidad negativa.          | El sistema rechaza la cantidad negativa.              |
| CP-09 | Consultar el inventario.                           | La información se muestra de forma clara.             |
| CP-10 | Modificar una cantidad y volver a consultar.       | El cambio se conserva correctamente.                  |

### HU-03 – Registro de ventas

| ID    | Caso de prueba                                           | Resultado esperado                                    |
| ----- | -------------------------------------------------------- | ----------------------------------------------------- |
| CP-11 | Registrar una venta con datos válidos.                   | La venta se registra correctamente.                   |
| CP-12 | Registrar una venta con datos incompletos o incorrectos. | El sistema solicita corregir los datos.               |
| CP-13 | Consultar una venta registrada.                          | La información de la venta se conserva correctamente. |
| CP-14 | Realizar una venta de un producto existente.             | La cantidad disponible del inventario se actualiza.   |
| CP-15 | Intentar registrar nuevamente la misma venta.            | El sistema evita generar un registro duplicado.       |

### HU-04 – Reportes e información de impacto

| ID    | Caso de prueba                                                | Resultado esperado                                         |
| ----- | ------------------------------------------------------------- | ---------------------------------------------------------- |
| CP-16 | Consultar información registrada.                             | Los datos se muestran correctamente.                       |
| CP-17 | Generar o consultar un reporte.                               | El reporte presenta información clara y comprensible.      |
| CP-18 | Comparar los datos del reporte con la información almacenada. | Los datos coinciden con la información registrada.         |
| CP-19 | Consultar información de productos y ventas.                  | La información correspondiente se muestra correctamente.   |
| CP-20 | Revisar la información para dar seguimiento al proyecto.      | Los resultados permiten consultar la actividad registrada. |

---

## 6. Criterios de aceptación de las pruebas

Una prueba se considerará satisfactoria cuando:

* La función evaluada cumpla con el resultado esperado.
* Los datos ingresados sean validados correctamente.
* No se presenten errores críticos durante la prueba.
* La información se conserve correctamente.
* Los criterios de aceptación de la historia de usuario sean comprobados.
* La información sea clara y fácil de consultar.

---

## 7. Registro de resultados

Los resultados se registrarán conforme se realicen las pruebas.

| ID    | Historia de usuario | Resultado | Evidencia   | Estado    |
| ----- | ------------------- | --------- | ----------- | --------- |
| CP-01 | HU-01               | Pendiente | Por agregar | Pendiente |
| CP-02 | HU-01               | Pendiente | Por agregar | Pendiente |
| CP-03 | HU-01               | Pendiente | Por agregar | Pendiente |
| CP-04 | HU-01               | Pendiente | Por agregar | Pendiente |
| CP-05 | HU-01               | Pendiente | Por agregar | Pendiente |
| CP-06 | HU-02               | Pendiente | Por agregar | Pendiente |
| CP-07 | HU-02               | Pendiente | Por agregar | Pendiente |
| CP-08 | HU-02               | Pendiente | Por agregar | Pendiente |
| CP-09 | HU-02               | Pendiente | Por agregar | Pendiente |
| CP-10 | HU-02               | Pendiente | Por agregar | Pendiente |
| CP-11 | HU-03               | Pendiente | Por agregar | Pendiente |
| CP-12 | HU-03               | Pendiente | Por agregar | Pendiente |
| CP-13 | HU-03               | Pendiente | Por agregar | Pendiente |
| CP-14 | HU-03               | Pendiente | Por agregar | Pendiente |
| CP-15 | HU-03               | Pendiente | Por agregar | Pendiente |
| CP-16 | HU-04               | Pendiente | Por agregar | Pendiente |
| CP-17 | HU-04               | Pendiente | Por agregar | Pendiente |
| CP-18 | HU-04               | Pendiente | Por agregar | Pendiente |
| CP-19 | HU-04               | Pendiente | Por agregar | Pendiente |
| CP-20 | HU-04               | Pendiente | Por agregar | Pendiente |

---

## 8. Evidencias

Las evidencias de las pruebas se integrarán mediante:

* Capturas de pantalla de las pruebas realizadas.
* Resultados obtenidos.
* Comentarios en las Issues correspondientes de GitHub.
* Registro de los casos de prueba.
* Evidencias relacionadas con los criterios de aceptación.

Las evidencias se agregarán conforme se realicen las pruebas.

---

## 9. Relación con el Plan de Calidad

Este plan de pruebas complementa el **Plan de Calidad del Software**, ya que permite comprobar el cumplimiento de los criterios de calidad establecidos para las historias de usuario.

Las pruebas estarán relacionadas principalmente con:

* **Usabilidad**
* **Seguridad**
* **Rendimiento**
* **Confiabilidad**
* **Criterios de aceptación**

---

## 10. Estado actual

Las pruebas se encuentran **pendientes de ejecución**.

El presente documento establece los casos y criterios que serán utilizados posteriormente para verificar el funcionamiento del sistema.

---

## 11. Conclusión

El plan de pruebas establece una organización para verificar el funcionamiento del sistema y el cumplimiento de las historias de usuario. Los resultados y evidencias se incorporarán conforme se realicen las pruebas correspondientes.
