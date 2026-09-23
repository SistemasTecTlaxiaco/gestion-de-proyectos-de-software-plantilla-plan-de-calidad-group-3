# Historias de Usuario y Calidad

## Proyecto

**Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano**

Las historias de usuario permiten describir las principales necesidades de los usuarios del sistema y relacionarlas con los criterios de calidad del proyecto.

Cada historia será revisada considerando aspectos como usabilidad, rendimiento, seguridad, confiabilidad y adaptación al contexto de la región Mixteca.

---

## HU-01. Catálogo digital

**Como:** artesano.

**Quiero:** registrar y mostrar mis ollas de barro y canastas tejidas.

**Para:** que los posibles compradores puedan consultar los productos disponibles.

### Aspectos de calidad

- Los datos del producto deben registrarse correctamente.
- Las imágenes de los productos deben poder validarse.
- La información debe mostrarse de manera clara.
- El catálogo debe ser sencillo de utilizar.
- Las consultas principales deben procurar un tiempo de respuesta menor o igual a 2 segundos.
- El sistema debe considerar las condiciones de conectividad limitada de algunas comunidades.

### Criterios de aceptación

- El artesano puede registrar un producto.
- El producto registrado aparece correctamente en el catálogo.
- La información del producto puede consultarse.
- Los datos obligatorios son validados.
- No se permiten registros incompletos.

---

## HU-02. Control de inventario

**Como:** artesano.

**Quiero:** registrar las piezas disponibles y actualizar sus cantidades.

**Para:** evitar errores en el inventario.

### Aspectos de calidad

- Las cantidades deben validarse correctamente.
- No deben permitirse cantidades negativas.
- Las modificaciones deben actualizar correctamente el inventario.
- La información debe mantenerse íntegra.
- La interfaz debe ser sencilla para facilitar su utilización.

### Criterios de aceptación

- El artesano puede registrar una cantidad disponible.
- El sistema permite actualizar las existencias.
- El sistema evita cantidades negativas.
- Los cambios realizados se muestran correctamente.
- La información del inventario permanece disponible después de actualizarla.

---

## HU-03. Registro de ventas

**Como:** artesano.

**Quiero:** registrar las ventas realizadas.

**Para:** llevar un control de mis operaciones comerciales.

### Aspectos de calidad

- Los datos de la venta deben validarse.
- La información debe registrarse correctamente.
- Se debe proteger la información relacionada con las operaciones.
- Deben evitarse registros duplicados o incompletos.
- La información registrada debe conservar su integridad.

### Criterios de aceptación

- El artesano puede registrar una venta.
- El sistema valida los datos necesarios.
- La venta queda registrada correctamente.
- La información de la venta puede consultarse.
- El registro de la venta actualiza la información correspondiente cuando sea necesario.

---

## HU-04. Reportes e información de impacto

**Como:** responsable del proyecto.

**Quiero:** generar información relacionada con productos, ventas e impacto.

**Para:** facilitar el seguimiento y la transparencia del proyecto.

### Aspectos de calidad

- Los reportes deben mostrar información clara.
- Deben utilizarse los datos necesarios para cada reporte.
- La información debe generarse correctamente.
- Se debe proteger la información utilizada.
- Los reportes deben ser fáciles de consultar.

### Criterios de aceptación

- El responsable puede generar un reporte.
- El reporte contiene la información correspondiente.
- Los datos mostrados coinciden con la información registrada.
- La información puede consultarse de manera clara.
- No se muestran datos innecesarios.

---

# Relación de las historias con la calidad

| Historia | Calidad relacionada | Consideraciones principales |
|---|---|---|
| HU-01 | Usabilidad, rendimiento y confiabilidad | Catálogo sencillo, datos correctos y consultas rápidas |
| HU-02 | Confiabilidad, usabilidad y seguridad | Validación de cantidades e integridad del inventario |
| HU-03 | Seguridad, confiabilidad y usabilidad | Validación y protección de las operaciones |
| HU-04 | Confiabilidad, seguridad y usabilidad | Información clara y generación correcta de reportes |

---

# Revisión de las historias de usuario

Las historias de usuario serán revisadas antes de iniciar su desarrollo.

La revisión considerará:

1. Que la historia utilice correctamente el formato **Como / Quiero / Para**.
2. Que la necesidad del usuario sea clara.
3. Que los criterios de aceptación sean verificables.
4. Que se identifiquen posibles riesgos.
5. Que se consideren aspectos de calidad.
6. Que la historia sea compatible con las condiciones del contexto regional.
7. Que pueda ser validada mediante pruebas.

# Criterio para considerar una historia terminada

Una historia de usuario podrá considerarse terminada cuando:

- Cumpla con su descripción.
- Cumpla todos sus criterios de aceptación.
- Haya sido revisada por el equipo.
- Se hayan realizado las pruebas correspondientes.
- No presente errores críticos.
- Se encuentre registrada correctamente en GitHub.
- Se encuentre integrada con las demás funcionalidades cuando corresponda.
- La documentación necesaria esté actualizada.
