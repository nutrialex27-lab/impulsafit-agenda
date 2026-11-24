# ImpulsaFit Agenda

Agenda gratuita para clientes, reservas de EMS, entrenamiento personal y demos. Diseño coral y azul noche, con icono propio de calendario y reloj.

## Abrir e instalar la aplicación

**[Abrir ImpulsaFit Agenda](https://impulsafit-agenda.nutrialex-27.chatgpt.site)**

En Android, abre el enlace con Chrome y usa el menú ⋮ → Añadir a pantalla de inicio / Instalar aplicación. En ordenador, usa la opción de instalar de Chrome o Edge.

La edición web es privada: utiliza tu cuenta de ChatGPT. Las citas se guardan en esa cuenta y pueden consultarse en distintos dispositivos.

## Descargar y probar sin cuenta

Descarga **[ImpulsaFit_Agenda.html](ImpulsaFit_Agenda.html)** y ábrelo con un navegador. La edición descargable contiene el programa, estilos e icono, sin dependencias externas para ejecutarla.

En esta edición los datos se guardan en el navegador del dispositivo. Utiliza Ajustes → Descargar copia de seguridad para conservar los registros o trasladarlos a otra edición. La copia descargable y la edición web no se sincronizan automáticamente.

## Código editable

**[ImpulsaFit_Agenda_Codigo.zip](ImpulsaFit_Agenda_Codigo.zip)** contiene el código completo de esta versión: componentes, estilos, guardado local, API de la edición web, esquema y migraciones, pruebas y archivos de instalación PWA.

Descomprime el ZIP y consulta su README. Para regenerar el HTML después de editar el código: `npm ci` y `npm run build:portable`. La edición local se genera en `public/ImpulsaFit_Agenda.html`.

Este repositorio conserva una entrega de la aplicación y su código en ZIP. No configura por sí solo una sincronización o despliegue automático con la edición web.

## Funciones

- Agenda diaria, semanal y mensual.
- Clientes y reservas semanales repetidas.
- Detección de horarios solapados.
- Mensajes editables con fecha, hora y condiciones de cancelación.
- Plazos editables: recordatorio inicial de 48 horas y cancelación de 24 horas.
- Copias JSON y exportación al calendario con alarmas.

## WhatsApp

Los mensajes se preparan en la aplicación. El entrenador debe pulsar Enviar en WhatsApp y confirmar manualmente el envío al volver. No hay envíos automáticos ni APIs de pago.

El repositorio y las descargas no contienen registros de clientes. Los datos de uso no se suben a GitHub.
