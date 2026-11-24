# ImpulsaFit Agenda · Android

IF Agenda es la aplicación de reservas de ImpulsaFit en Condes Wellness & Fitness, para Android 8 o posterior. Funciona en el móvil sin acceder a ChatGPT. Repositorio público y descarga sin iniciar sesión.

## Descargar e instalar

[Descargar IF Agenda para Android (.APK), versión 0.3.0 beta](https://github.com/nutrialex27-lab/impulsafit-agenda/releases/download/v0.3.0-beta.1/ImpulsaFit_Agenda_Android.apk)

Abre el APK e instala la actualización sobre la versión anterior, sin desinstalarla. Mantiene el paquete y la firma para conservar los registros. Haz una copia JSON desde Ajustes antes de actualizar.

## Confirmar o cancelar

1. Configura tu número en Ajustes → Tu número de WhatsApp para respuestas, o al preparar el primer mensaje.
2. Envía la reserva o el recordatorio desde tu WhatsApp. El texto identifica las normas como normativa del centro Condes Wellness & Fitness.
3. El cliente recibe dos enlaces: CONFIRMAR SESIÓN y CANCELAR SESIÓN. Elige uno y pulsa Enviar en WhatsApp; la respuesta llega a tu número.
4. En la ficha de la reserva, registra Cliente confirma o Cliente cancela y la hora en que llegó la respuesta. La agenda no lee WhatsApp automáticamente.

Al vencer el plazo de cancelación, una reserva sin respuesta se muestra como Confirmada · sin respuesta. El mensaje explica que el silencio no cancela la cita y que una ausencia o cancelación fuera de plazo consume una sesión. Al registrar realizada, cancelación fuera de plazo o ausencia se contabiliza una sesión consumida; no se gestiona un saldo de bonos ni hay cobros o descuentos automáticos.

## Otras funciones

- Clientes, agenda diaria, semanal y mensual.
- Reservas semanales repetidas y detección de horarios solapados.
- Normativa y plazos editables, con condiciones guardadas por reserva.
- Copias JSON y exportación ICS mediante el selector de archivos de Android.
- Diseño coral y azul noche e icono propio.

No utiliza APIs de pago ni suscripciones externas. Los enlaces de WhatsApp preparan mensajes; el envío y el registro son manuales.

## Código editable y datos

[ImpulsaFit_Agenda_Codigo_Android.zip](ImpulsaFit_Agenda_Codigo_Android.zip) contiene el proyecto completo y android-app/, con scripts e instrucciones de compilación. La clave privada de firma se conserva por separado y no se publica.

Los clientes y reservas se guardan en el almacenamiento privado de la aplicación de tu móvil. No se suben a GitHub ni se sincronizan automáticamente con otros dispositivos o con la edición web. Guarda copias JSON desde Ajustes. Desinstalar elimina los datos locales; actualiza sobre la app existente.

## Verificación

Versión beta: compilación, firma APK v2/v3, paquete y versión verificados. Once pruebas de lógica y comprobación de tipos superadas. Probada en navegador la generación de opciones, importación de copias y cancelación por fecha de recepción. La instalación y el uso nativo de esta actualización requieren prueba en un dispositivo Android físico.
