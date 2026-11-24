# ImpulsaFit Agenda · Android

**IF Agenda** es la edición instalable de la agenda de ImpulsaFit para Android 8 o posterior. Incluye la agenda dentro de la aplicación y guarda los registros en el móvil. No necesita acceder a una página de ChatGPT para funcionar.

## Descargar e instalar

Entra en **[Releases](https://github.com/nutrialex27-lab/impulsafit-agenda/releases)** y descarga **ImpulsaFit_Agenda_Android.apk** de la versión Android 0.2.0-beta.1. Abre el APK descargado para iniciar la instalación. El icono se llama **IF Agenda** y utiliza el calendario coral con reloj.

Este repositorio es privado; GitHub puede pedirte iniciar sesión para descargar el archivo. Después de instalar, la agenda se abre desde su propio icono.

## Código editable

**[ImpulsaFit_Agenda_Codigo_Android.zip](ImpulsaFit_Agenda_Codigo_Android.zip)** contiene el proyecto completo y la carpeta `android-app/`, con el contenedor Android, instrucciones y scripts de compilación. La clave privada de firma se conserva por separado y no está incluida en el repositorio ni en la distribución.

## Funciones

- Clientes, agenda diaria, semanal y mensual.
- Reservas semanales repetidas y detección de horarios solapados.
- Política de cancelación editable y mensajes de WhatsApp preparados con fecha, hora y condiciones.
- Copias JSON mediante el selector de archivos de Android y restauración desde un archivo elegido.
- Exportación ICS para llevar las reservas al calendario.
- Diseño coral y azul noche e icono propio.

Los WhatsApp requieren pulsar Enviar en WhatsApp y confirmar manualmente el envío al volver. No hay envío automático ni APIs de pago.

## Datos y actualizaciones

Las reservas se guardan en el almacenamiento privado de la aplicación en ese móvil. No se suben a GitHub ni se sincronizan automáticamente con la edición web o con otro dispositivo. Haz copias JSON desde Ajustes para trasladarlas o conservarlas fuera del móvil. Guarda una copia antes de desinstalar: Android elimina los datos de las aplicaciones desinstaladas.

Las actualizaciones con el mismo paquete y la misma firma conservan los datos. Los cambios del repositorio no se despliegan automáticamente.

## Estado de esta entrega

Versión de prueba. Se verificaron compilación, recursos, actividad de inicio, firma APK v2/v3 y estructura del paquete. La interfaz y el almacenamiento local ya se probaron en navegador. Falta comprobar la instalación y el uso en un dispositivo Android físico o emulador.

La edición HTML anterior permanece disponible como copia para abrir en navegador.
