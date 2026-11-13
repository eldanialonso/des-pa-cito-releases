# Problemas frecuentes

Si algo no anda, buscá acá tu caso. Cada respuesta es corta y dice qué hacer.

## Al instalar, Windows dice "Windows protegió su PC"

Es normal: la app todavía no tiene una firma digital (cuesta dinero y por ahora no la tiene). Tocá
**"Más información"** y después **"Ejecutar de todas formas"**. Más detalles (y qué hacer si lo bloquea el
"Control inteligente de aplicaciones") en la [guía de instalación](instalacion.md).

## El video no se reproduce dentro de la app

Algunos dueños de videos no permiten verlos fuera de YouTube, y algunos videos son privados o fueron
borrados. La app te lo avisa con un mensaje. No hay nada que arreglar: **probá con otro video**.

Si el mensaje dice que no se pudo cargar el reproductor, revisá tu conexión a internet y tocá
**"Probar de nuevo"**.

## "Este video no tiene subtítulos"

La app necesita los subtítulos del video en su idioma original (los de YouTube, aunque sean
automáticos). Si no los tiene:

- Con tu [clave gratuita de Google](obtener-api-key-google.md), la IA de Google los escribe sola. Las
  pausas pueden ser un poco menos precisas.
- Sin clave, probá con otro video.
- Si tenés el audio o el video en tu computadora (por ejemplo, una grabación tuya), podés
  [practicar con ese archivo](primeros-pasos.md#practicar-con-un-archivo-tuyo): la app escribe los
  subtítulos sola, sin clave.

## Problemas con un archivo tuyo

- **"No pudimos descargar el reconocimiento de voz"**: la primera vez hace falta internet para bajarlo
  (60 MB, o 190 MB con Mejor calidad). Revisá la conexión y tocá **"Probar de nuevo"**.
- **"No pudimos leer el audio del archivo"** o **"Ese archivo no es un audio o video que la app pueda
  usar"**: el archivo puede estar dañado o en un formato raro. Probá con un mp3, m4a, wav, mp4 o webm.
- **"El archivo dura más de 3 horas"**: probá con uno más corto (o cortalo en partes con otro programa).
- **"Este tipo de archivo (.webm, .ogg, .opus o .flac) se puede usar sólo si dura hasta 20 minutos"**: para
  archivos más largos, usá un .mp4, .m4a, .mov, .mp3 o .wav.
- **"No encontramos el archivo"**: lo moviste, lo renombraste o lo borraste. Elegilo de nuevo con
  **"Elegir un archivo de tu computadora"**.
- **"Falta una parte de la app que escribe los subtítulos"**: volvé a instalar la app
  ([Instalación](instalacion.md)); tus ajustes y tu clave se conservan.
- **Tarda mucho**: escribir los subtítulos usa mucho la computadora. Cerrá otros programas pesados, o elegí
  **Rápido** en **Ajustes → Archivos propios**.

## "YouTube está limitando las descargas"

Si se piden muchos subtítulos seguidos, YouTube pide esperar un rato. La app deja de pedirle subtítulos
y te dice **a qué hora** podés volver a intentar. Mientras tanto:

- Los videos que ya practicaste siguen disponibles en **Prácticas recientes**.
- Con tu clave de Google, la app puede seguir igual con otros videos.

## La clave no funciona

- Revisá que la copiaste **completa**, sin espacios.
- Revisá que sea la del proveedor correcto (la de Google empieza con `AQ.`, o con `AIza` si es vieja). La app te avisa si parece
  de otro proveedor.
- Si recién la creaste, esperá un minuto y tocá **"Probar"** de nuevo.
- Si sigue igual, creá una clave nueva. Pasos: [clave de Google](obtener-api-key-google.md) o
  [proveedores de respaldo](proveedores-de-respaldo.md).

## "Usamos cortes automáticos básicos porque no hubo respuesta de la IA"

Los planes gratuitos tienen un límite de usos por minuto y por día. Cuando se termina, la app sigue
igual con cortes automáticos básicos, que también sirven para practicar. En **Ajustes** ves hasta qué
hora descansa cada proveedor (⏳). Para que no te pase, sumá un
[proveedor de respaldo](proveedores-de-respaldo.md).

Si la IA tarda mucho mientras se prepara la práctica, tocá **"Seguir sin IA"**.

## Las pausas caen en lugares raros

- Con **cortes automáticos básicos** (sin IA) la app corta en silencios y al final de las oraciones,
  pero no entiende el sentido. Con la IA las pausas caen mejor al final de cada idea.
- Con **subtítulos automáticos** de YouTube, una pausa puede caer un poco antes o después.
- Probá otro **largo de fragmento**, o elegí **"Personalizado"** y poné el mínimo y el máximo de
  segundos que quieras.
- Si un fragmento se cortó antes de tiempo, pausá tu turno (**"Pausar"** o la tecla P) y tocá
  **"Repetir"** (o la tecla R) para escucharlo de nuevo. Mientras hablás, "Repetir" está apagado.

## No se escuchan los sonidos del turno

Los sonidos están **apagados** al principio. Prendelos en **Ajustes → Práctica → "Sonido suave al
empezar y al terminar tu turno"** (es un interruptor) y tocá **"Probar sonido de inicio"**. Si igual no
se oye, revisá el volumen de Windows. El volumen del video se cambia en el propio video.

## "Grabar mis turnos" se vuelve a apagar

Al prender **"Grabar mis turnos"**, la app prueba el micrófono. Si no anda, la opción se apaga sola y la app
te dice por qué, con el botón **"Abrir la configuración del micrófono de Windows"**:

- **Windows no deja usar el micrófono:** en **Configuración → Privacidad y seguridad → Micrófono**, prendé
  **"Acceso al micrófono"** y **"Permitir que las aplicaciones de escritorio accedan al micrófono"**.
- **No hay micrófono:** conectá uno.
- **Está ocupado o no responde:** cerrá las otras aplicaciones que lo estén usando.

Después volvé a prender la opción. Más detalles: [Grabar tus turnos](primeros-pasos.md#grabar-tus-turnos).

¿No se escucha tu grabación? Revisá el volumen de Windows: la app la pasa por los mismos parlantes que el
video.

## Los atajos de teclado no responden

- Los atajos (Espacio, P, R, flechas, +, T, G y Esc) funcionan en la pantalla de práctica, salvo mientras
  escribís en un casillero.
- Si hiciste clic en el video, la app recupera el teclado en un momento. Si no, hacé clic en cualquier
  parte fuera del video.
- Con **Tab** pasás de un botón a otro y con **Enter** lo activás.

Lista completa de atajos: [Primeros pasos](primeros-pasos.md#atajos-de-teclado).
