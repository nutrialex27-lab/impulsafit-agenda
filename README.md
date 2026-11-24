# IF Agenda · Android 0.4.0 beta

Agenda de ImpulsaFit en Condes Wellness & Fitness. Repositorio público; descarga sin iniciar sesión.

[Descargar actualización Android (.APK)](https://github.com/nutrialex27-lab/impulsafit-agenda/releases/download/v0.4.0-beta.1/ImpulsaFit_Agenda_Android.apk)

Instala encima de la versión anterior sin desinstalarla. Se mantiene la firma y el paquete para conservar los registros. Haz antes una copia JSON desde Ajustes. Android 8 o posterior.

## Confirmar y cancelar directamente en la agenda

1. Guarda una reserva. Con Respuestas directas activado, la app prepara un enlace individual con la cita y la normativa de Condes.
2. Envía el mensaje inicial por WhatsApp. En Android puede abrirse ya preparado al guardar; siempre tienes que pulsar Enviar. No hay envío automático mediante una API de pago.
3. El cliente abre el enlace y pulsa Confirmar o Cancelar. La respuesta se guarda directamente: no tiene que enviar otro WhatsApp y no tienes que registrarla a mano.
4. La app recoge respuestas con Internet al abrirse, al recuperar el foco y cada 45 segundos mientras está visible. No hay notificaciones push ni actualización en segundo plano garantizada.

Sin respuesta, la reserva se mantiene confirmada al vencer el plazo. Una ausencia o cancelación fuera de plazo consume sesión. La hora de respuesta la fija el servidor; las realizadas, ausencias y cancelaciones fuera de plazo se contabilizan sin gestionar un saldo de bonos.

En Ajustes puedes desactivar Respuestas directas para volver al flujo manual por WhatsApp. Las reservas semanales repetidas preparan el aviso de la primera sesión; comunica las otras desde sus fichas.

## Datos y código editable

Los nombres, teléfonos y notas se guardan en tu agenda y no se publican. El servicio de respuestas recibe solo fecha, duración, servicio, ubicación pública y normativa de cada cita. Cada enlace permite gestionar una única reserva. Las copias JSON contienen datos y accesos para recuperar su gestión; guárdalas en privado.

[ImpulsaFit_Agenda_Codigo_Android.zip](ImpulsaFit_Agenda_Codigo_Android.zip) contiene la app, el contenedor Android y response-service/ con el servicio público, pruebas y migraciones. Las claves de firma y credenciales de publicación no se incluyen.

No se utilizan servicios externos de pago para enviar WhatsApp. El alojamiento depende de los límites y disponibilidad de la cuenta; no se promete gratuidad perpetua de terceros.

## Verificación

17 pruebas de agenda y sincronización, 7 pruebas del servicio con SQLite, comprobación de tipos, compilación web y firma APK v2/v3 superadas. Verificado en navegador el flujo publicado: cliente confirma/cancela y la agenda actualiza su estado sin registro manual. La instalación y la conexión nativa de la versión beta deben probarse en Android físico.
