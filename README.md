# ✨ XocoCaptur Pro ✨

¡Tu herramienta de captura y reconocimiento de texto, ultra-ligera y potente!

XocoCaptur Pro es una aplicación de escritorio minimalista diseñada para hacerte la vida más fácil. Captura cualquier parte de tu pantalla, extrae texto de imágenes al instante o lee códigos QR con un solo clic.

![XocoCaptur Pro - Interfaz Principal](URL_DE_LA_IMAGEN_DE_TU_APP_AQUI)

---

## 🚀 Funcionalidades Principales

*   **✍️ Reconocimiento de Texto (OCR):** Captura cualquier texto en tu pantalla (un error, un documento, un tuit) y conviértelo a texto plano que puedes copiar y pegar.
*   **📸 Captura de Pantalla Avanzada:** No es una simple captura. Edita tus imágenes al momento:
    *   **Dibuja** sobre ellas para señalar lo importante.
    *   **Gira** la imagen si la necesitas en otra orientación.
    *   **Haz zoom** para ver los detalles.
*   **📱 Lector de Códigos QR:** Captura cualquier código QR en pantalla y obtén el texto o enlace que contiene al instante.
*   **📖 Historial de Capturas:** Guarda automáticamente todas tus capturas de texto para que puedas consultarlas más tarde.
*   **⚙️ Configurable y Sencillo:** Una interfaz minimalista que no molesta y opciones claras para que todo funcione a la primera.
*   **📌 Siempre Visible:** ¿Necesitas tener la herramienta a mano? Fíjala encima de todas las demás ventanas con un solo clic.

---

## 📦 Instalación y Primeros Pasos

Para que XocoCaptur Pro funcione al 100%, solo necesitas dos cosas: la aplicación y una herramienta externa gratuita llamada Tesseract.

### 1. Descargar XocoCaptur Pro

Ve a la sección de **[Releases](URL_DE_TU_SECCION_DE_RELEASES_AQUI)** en este repositorio y descarga la última versión de `XocoCaptur.exe`.

> **Nota:** Al ser un ejecutable no firmado, es posible que Windows muestre una advertencia de seguridad. Simplemente haz clic en "Más información" y luego en "Ejecutar de todas formas".

### 2. Instalar Tesseract OCR (¡Paso Obligatorio para el Texto!)

El reconocimiento de texto (OCR) depende de Tesseract, un motor de reconocimiento de texto de código abierto de Google.

1.  **Descarga el instalador** para Windows desde la [página oficial de Tesseract en UB-Mannheim](https://github.com/UB-Mannheim/tesseract/wiki).
2.  **Ejecuta el instalador.** Durante la instalación, es muy recomendable que marques la casilla para **añadir los idiomas que necesites** (por ejemplo, "Spanish").
3.  **Apunta la ruta donde se instaló.** Generalmente es `C:\Program Files\Tesseract-OCR\`.

---

## 🛠️ Guía de Uso

La interfaz es súper simple y está diseñada para ser intuitiva.

### La Ventana Principal

![Botones de la Interfaz](URL_DE_IMAGEN_EXPLICANDO_BOTONES_AQUI)

*   **📝 Captura OCR:** Inicia una captura para reconocer texto.
*   **📸 Captura de Pantalla:** Inicia una captura para obtener una imagen.
*   **📱 Código QR:** Inicia una captura para leer un código QR.

*   **📌 Siempre Visible:** Fija la ventana por encima de todo.
*   **📖 Historial:** Abre el historial de tus capturas de texto.
*   **⚙️ Configuración:** Abre los ajustes (¡importante para el primer uso!).
*   **❌ Minimizar:** Oculta la aplicación en la bandeja del sistema (al lado del reloj).

### Primer Uso: Configurar Tesseract

1.  Abre XocoCaptur Pro.
2.  Haz clic en el botón de **Configuración** (⚙️).
3.  En la ventana que aparece, haz clic en el botón **"Buscar..."** o **"Browse..."**.
4.  Navega hasta la carpeta donde instalaste Tesseract (ej. `C:\Program Files\Tesseract-OCR\`) y selecciona el archivo `tesseract.exe`.
5.  Haz clic en **"Guardar y Cerrar"**.

¡Listo! La función de reconocimiento de texto ya está activada para siempre.

### Realizar una Captura

1.  Haz clic en el botón de la acción que quieras (OCR, Captura o QR).
2.  La pantalla se oscurecerá ligeramente.
3.  Haz clic y **arrastra el ratón** para dibujar un rectángulo sobre el área que quieres capturar.
4.  ¡Suelta el clic y listo! Se abrirá la ventana con el resultado.

---

## 🔧 Para Desarrolladores (Construir desde el código fuente)

Si quieres modificar el código y compilar tu propia versión, sigue estos pasos:

1.  Clona el repositorio: `git clone https://github.com/tu-usuario/tu-repositorio.git`
2.  Crea y activa un entorno virtual:
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```
3.  Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```
4.  Para ejecutar la aplicación:
    ```bash
    python xococaptur.py
    ```
5.  Para construir el `.exe`:
    ```bash
    pyinstaller xococaptur.spec
    ```

---

## 📄 Licencia

Este proyecto está distribuido bajo la Licencia MIT.
