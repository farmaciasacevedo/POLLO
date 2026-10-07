# Prototipo: Landing Page Inbound Marketing - Pollo Pinulito

> **Aviso Importante:**  
> Prototipo elaborado con fines académicos. No corresponde al sitio oficial de Pollo Pinulito.

---

## 🍗 Descripción del Proyecto
Este proyecto es una Landing Page moderna, responsiva e interactiva creada como ejemplo práctico y pedagógico de una estrategia de **Inbound Marketing** para el sector de comida rápida (Fast Food / QSR).

Integra los elementos visuales tradicionales de **Pollo Pinulito** (rojo, amarillo, blanco y negro) con una experiencia de usuario optimizada para la conversión mediante un **Lead Magnet** de bienvenida (15% OFF).

---

## 🚀 Cómo Visualizar y Usar el Proyecto

1. **Abrir directamente:**
   - Haz doble clic en el archivo `index.html` para abrirlo en cualquier navegador web (Google Chrome, Microsoft Edge, Firefox, Safari).
   - No requiere servidor backend, compilación ni configuración previa; todas las interacciones (validación de formulario, generación dinámica del cupón, copiado al portapapeles y animación de confeti) funcionan con JavaScript nativo.

2. **Ejecutar con un servidor local (Opcional):**
   ```bash
   # En Windows PowerShell o terminal:
   npx serve .
   # o con Python:
   python -m http.server 8080
   ```

---

## ✨ Características Principales

1. **Identidad Visual de Comida Rápida:**
   - Logo de Pollo Pinulito que el usuario ya compartió, incluido en `assets/pinulito-logo.png`.
   - Colores representativos: Rojo (`#D3131B`), Amarillo mostaza/dorado (`#FFC20E`), Blanco puro y Negro carbón.
   - Tipografía atrevida y moderna (*Montserrat* y *Poppins*).

2. **Formulario de Captación (Lead Magnet):**
   - **Campos:** Nombre, Correo electrónico, Teléfono y Cumpleaños.
   - **Botón destacado:** *“Quiero mi 15% OFF”* con efecto pulsante.
   - **Mensaje de confirmación interactivo:**
     *“¡Bienvenido a la Familia Pinulito! Tu cupón de 15% de descuento está listo.”*

3. **Cupón Digital Interactivo:**
   - Estilo de ticket troquelado con muescas circulares y borde perforado.
   - Título principal del cupón: **15% OFF - Primera compra web/app**.
   - Código único generado dinámicamente (`PINU-15-XXXX`).
   - Botón de 1 clic para copiar el código al portapapeles.
   - Código de barras y botón para guardar o imprimir el cupón.

4. **Secciones de Soporte de Alto Impacto:**
   - Beneficios del programa de fidelización del Club Pinulito.
   - Muestra de combos populares con cálculo de ahorro en tiempo real.
   - Explicación del canje en 3 sencillos pasos.
   - Prueba social (reseñas de clientes guatemaltecos).
   - Modal interactivo con la justificación académica de Inbound Marketing.

5. **Descargo de Responsabilidad en el Pie de Página:**
   *“Prototipo elaborado con fines académicos. No corresponde al sitio oficial de Pollo Pinulito.”*

## Publicar en GitHub Pages

1. Crea el repositorio **farmaciasacevedo/pollo**, con visibilidad **Public** y la opción **Add README** activada.
2. Extrae `pollo-listo.zip`. Sube todos los archivos y la carpeta `assets` que están dentro de la carpeta extraída a la raíz del repositorio. No subas el ZIP ni una carpeta por encima del HTML: `index.html` debe quedar directamente en la raíz.
3. Abre **Settings → Pages**.
4. Selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.
5. Cuando GitHub termine de publicar, abre **https://farmaciasacevedo.github.io/pollo/**.

Esta es la dirección prevista; se confirma como publicada una vez que GitHub complete el despliegue.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Qué incluye esta versión

- Hoja de estilos Tailwind CSS 3.4.17 ya compilada en `assets/tailwind.min.css`. No hay que instalar herramientas para publicar ni cargar Tailwind desde un CDN.
- El logo se incluye en la carpeta `assets`, junto con el aviso de licencia de Tailwind.
- Las fuentes Montserrat y Poppins siguen cargándose desde Google Fonts, como en el original. Si no hay conexión, se utilizan las fuentes alternativas definidas en la página.
- El formulario es una demostración: no crea cuentas, no guarda datos y no envía correos ni mensajes de WhatsApp. El cupón generado es ilustrativo y no canjeable.
- El cupón se puede copiar y se corrigió la impresión para mostrar únicamente el ticket.
- Se corrigió la regla `hidden` que impedía que ciertos elementos aparecieran en escritorio, y se añadió la animación de confirmación que faltaba.
- Se conservan los colores, los textos principales, las secciones y la estructura del diseño original.
