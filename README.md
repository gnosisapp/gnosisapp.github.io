# Gnosis — Convertidor de Documentos y Archivos Privado con IA integrada.

> Herramienta web rápida, privada y ligera para procesar y convertir documentos, imágenes y archivos directamente en el navegador, sin subir información a servidores externos.

Sitio Web: https://gnosisapp.github.io/

---

## Características Principales

- **Procesamiento 100% Local:** Los archivos no salen del dispositivo del usuario; se procesan en la memoria local del navegador.
- **PWA (Progressive Web App):** Instalable en teléfonos móviles (Android / iOS) y computadoras para ejecutarse como aplicación nativa.
- **Soporte Offline:** Permite abrir y procesar conversiones sin conexión a internet activa tras la primera carga.
- **Eficiencia y Rapidez:** Sin tiempos de espera por subida o descarga de servidores remotos.

---

## Manual de Uso

### 1. Conversión de Archivos en la Web
1. Ingresa a https://gnosisapp.github.io/.
2. Selecciona la herramienta o formato que deseas trabajar (PDF, imágenes, compresión, etc.).
3. Arrastra tu archivo al recuadro o presiona el botón para seleccionarlo desde tu dispositivo.
4. Elige los parámetros de conversión deseados.
5. Haz clic en el botón de procesar y descarga el resultado.

### 2. Cómo instalar la Aplicación en Teléfonos Móviles

#### En Android (Google Chrome):
1. Entra al enlace desde Google Chrome.
2. Toca el menú de opciones (tres puntos verticales en la esquina superior derecha).
3. Selecciona la opción "Instalar aplicación" o pulsa sobre el aviso inferior que aparece en pantalla.
4. La aplicación se añadirá al cajón de aplicaciones de tu dispositivo.

#### En iPhone / iPad (Safari):
1. Entra al enlace desde Safari.
2. Toca el botón Compartir (icono cuadrado con flecha hacia arriba).
3. Desliza hacia abajo en el menú y selecciona "Agregar a la pantalla de inicio".
4. Confirma pulsando "Agregar".

---

## Privacidad y Seguridad

Gnosis está diseñada bajo el principio de privacidad por diseño:
- No requiere cuentas, registros ni datos personales.
- No utiliza bases de datos remotas ni almacena copias de los archivos.
- Los documentos se eliminan de la memoria temporal del navegador al cerrar la pestaña o la aplicación.

---

## Créditos y licencias

Gnosis es software propietario. Consulta el archivo [LICENSE](LICENSE). Los componentes de terceros que usa se rigen por sus propias licencias y no están cubiertos por las restricciones de esa licencia.

### Componentes de terceros

| Componente | Uso | Licencia |
|---|---|---|
| [jsPDF](https://github.com/parallax/jsPDF) | Creación de PDF | MIT |
| [PapaParse](https://www.papaparse.com) | Lectura y escritura de CSV | MIT |
| [JSZip](https://stuk.github.io/jszip/) | Archivos DOCX y ZIP | MIT o GPL v3 (se usa bajo MIT) |
| [lamejs](https://github.com/zhuker/lamejs) | Codificación MP3 | LGPL |
| [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) | Códigos QR | MIT |
| [pdf-lib](https://pdf-lib.js.org) | Unir PDF | MIT |
| [PDF.js](https://mozilla.github.io/pdf.js/) | Lectura de PDF y miniaturas | Apache 2.0 |
| [WebLLM](https://webllm.mlc.ai) | Ejecuta el modelo de Gnovi en el navegador | Apache 2.0 |
| Llama 3.2 1B Instruct | Modelo de lenguaje de Gnovi | Llama 3.2 Community License |

Todos se cargan sin modificar.

### Gnovi y Llama

**Built with Llama.** Gnovi funciona con Llama 3.2, un modelo creado por Meta que se ejecuta en el dispositivo de la persona usuaria. Gnosis lo integró, pero no lo desarrolló ni lo entrenó. Llama 3.2 se licencia bajo la Llama 3.2 Community License y su copyright pertenece a Meta Platforms, Inc. El uso de Gnovi está sujeto a esa licencia y a su política de uso aceptable:

Licencia: https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/LICENSE

Política de uso aceptable: https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/USE_POLICY.md

Gnovi es una IA en Beta y puede cometer errores.

### MP3 y LAME

La exportación a MP3 usa lamejs, una adaptación del proyecto [LAME](https://lame.sourceforge.net), publicada bajo LGPL. Se carga como archivo independiente y sin cambios.

### Wikipedia

Si la persona activa la búsqueda, Gnovi consulta es.wikipedia.org. Ese contenido pertenece a sus autores y se ofrece bajo [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

### Privacidad

Los archivos se procesan en el dispositivo y no se envían a ningún servidor de Gnosis. Las librerías y el modelo se descargan de servidores de terceros, y la consulta de búsqueda en Wikipedia solo sale del dispositivo si activas esa opción.
