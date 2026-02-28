Mi Estenotipista 🎙️

Mi Estenotipista es una aplicación web moderna diseñada para la transcripción fiel de audio en tiempo real. Permite capturar audio tanto del micrófono como del sistema (audio interno), convirtiéndolo en texto instantáneamente y permitiendo la exportación tanto del contenido transcrito como del audio grabado en formato MP3.

✨ Características

Transcripción en tiempo real: Visualiza el texto conforme se procesa el habla utilizando la API de Reconocimiento de Voz de la Web.

Grabación Dual: Capacidad para mezclar audio del micrófono y del sistema (ideal para grabar reuniones o clases online).

Visualizador de Ondas: Gráficos dinámicos en colores pasteles que reaccionan al volumen y frecuencia del audio.

Control Total: Funciones de Grabar, Pausar, Detener y Limpiar datos.

Exportación: - Texto en formato .txt.

Audio procesado en formato .mp3 (utilizando la librería lame.js).

Diseño Responsivo: Interfaz estilo Glassmorphism optimizada para escritorio y dispositivos móviles.

🚀 Cómo usarlo

Clona el repositorio:

git clone [https://github.com/tu-usuario/mi-estenotipista.git](https://github.com/tu-usuario/mi-estenotipista.git)


Abre el archivo:
Simplemente abre transcripcion.html en cualquier navegador moderno (Chrome, Edge o Safari).

Configuración:

Pulsa GRABAR y otorga permisos de micrófono.

Si deseas grabar el audio del sistema, selecciona la pestaña o pantalla correspondiente y asegúrate de marcar la casilla "Compartir audio".

Finalización:

Al terminar, pulsa DETENER.

Usa los botones inferiores para descargar tus archivos.

🛠️ Tecnologías utilizadas

HTML5 & CSS3: Diseño personalizado con variables CSS y animaciones.

JavaScript (Vanilla): Lógica de la aplicación sin dependencias pesadas.

Web Speech API: Para el motor de transcripción.

MediaRecorder API: Para la captura de flujo de audio.

Web Audio API: Para la mezcla de canales y el visualizador de frecuencias.

Lame.js: Para la codificación de audio a MP3 en el lado del cliente.

🔒 Privacidad

Esta aplicación funciona localmente en el navegador.

El audio no se envía a ningún servidor externo para su procesamiento (excepto los servicios nativos de transcripción del sistema operativo/navegador).

Las grabaciones se procesan íntegramente en tu dispositivo.

✒️ Autor

Creado por El loco de la mochila - Blog Averroes

Este proyecto fue desarrollado como una herramienta de accesibilidad y productividad para facilitar la toma de notas.
