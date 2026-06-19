# Permisos

## Descripción

El módulo Permisos permite registrar, consultar y gestionar solicitudes de ausencia realizadas por los usuarios del sistema.

![Permisos de Ausencia](images/permisos-principal.png)

## Funcionalidades Principales

- Consultar solicitudes de permiso.
- Filtrar permisos por estado.
- Registrar nuevas solicitudes de ausencia.
- Aprobar solicitudes pendientes.
- Rechazar solicitudes pendientes.
- Consultar el historial de permisos.

## Estados de una solicitud

Las solicitudes de permiso pueden encontrarse en alguno de los siguientes estados:

- **Pendiente:** La solicitud está en espera de revisión.
- **Aprobado:** La solicitud fue aceptada.
- **Rechazado:** La solicitud fue denegada.

## Uso del módulo

1. Seleccione un estado para filtrar las solicitudes registradas.
2. Presione **Recargar** para actualizar la información.
3. Revise las solicitudes existentes y su estado.
4. Utilice las acciones disponibles para aprobar o rechazar solicitudes pendientes.

## Solicitar Permiso de Ausencia

Para registrar una nueva solicitud, seleccione la opción **Solicitar Permiso**.

![Solicitar Permiso](images/permisos-solicitar.png)

### Campos del formulario de permiso

- **Empleado***: Seleccione el empleado que solicita el permiso.
- **Fecha inicial***: Seleccione la fecha de inicio del permiso.
- **Fecha final***: Seleccione la fecha de finalización del permiso.
- **Justificación***: Describa el motivo del permiso.
- **Documento de respaldo (PDF)**: Adjunte un archivo PDF de respaldo.

### Cómo registrar el permiso

1. Seleccione el empleado desde el menú.
2. Complete la fecha inicial y la fecha final.
3. Escriba la justificación del permiso.
4. Adjunte el documento de respaldo en formato PDF.
5. Presione **Registrar** para enviar la solicitud.

### Botones de acción

- **Cancelar**: Cierra el formulario sin guardar la solicitud.
- **Registrar**: Envía la solicitud de permiso para revisión.

!!! warning

    Los campos marcados con un asterisco (*) son obligatorios para poder registrar la solicitud.

## Gestión de Solicitudes

Los usuarios autorizados pueden revisar las solicitudes registradas y realizar las siguientes acciones:

- Aprobar solicitudes pendientes.
- Rechazar solicitudes pendientes.
- Consultar el historial de permisos registrados.

!!! note
    Las acciones disponibles pueden variar según el rol asignado al usuario.