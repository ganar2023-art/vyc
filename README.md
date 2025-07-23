# Landing Page - Vero y Chiara

## Descripción del Proyecto

Este proyecto consiste en una página de aterrizaje (landing page) moderna, sencilla y totalmente responsive. Fue creada como un único archivo `index.html` para maximizar la portabilidad y facilidad de despliegue. La página está diseñada para funcionar como un panel de acceso rápido, permitiendo a los usuarios contactar a través de WhatsApp para solicitar la creación de usuarios en diversas plataformas de juego.

El diseño es minimalista y enfocado en la usabilidad, con un fondo oscuro, un logo principal y una grilla de seis botones que dirigen a acciones específicas.

(https://veroychiara.vercel.app/print_vyc.png)

---

## ✨ Características Principales

-   **Archivo Único**: Todo el código (HTML y CSS) se encuentra en `index.html` para una gestión simplificada.
-   **Diseño Responsive**: Se adapta perfectamente a cualquier tamaño de pantalla, desde móviles y tablets hasta computadoras de escritorio.
-   **Layout Moderno**: Utiliza CSS Grid para crear una grilla de botones simétrica y organizada.
-   **Interactividad**: Sutiles efectos de `hover` (zoom) en el logo y los botones para mejorar la experiencia de usuario.
-   **Integración con WhatsApp**: Todos los enlaces están configurados para abrir una conversación de WhatsApp con un mensaje predefinido, agilizando el proceso de registro.
-   **Optimización para Redes Sociales**: Incluye meta-tags de Open Graph (`og:title`, `og:image`, `og:description`) para que se muestre una vista previa atractiva al compartir el enlace en WhatsApp, Facebook, etc.

---

## 🛠️ Tecnologías Utilizadas

-   **HTML5**: Para la estructura semántica del contenido.
-   **CSS3**: Para los estilos, el diseño responsive y las animaciones. Se utilizan características modernas como:
    -   **Flexbox**: Para centrar el contenido principal.
    -   **Grid Layout**: Para la grilla de botones.
    -   **Variables CSS (`:root`)**: Para una fácil gestión de valores recurrentes como colores o transiciones.
    -   **Media Queries**: No fueron explícitamente necesarias gracias a la naturaleza fluida del diseño con Grid y Flexbox.

---

## 🚀 Instalación y Uso

No se requiere ningún proceso de compilación o instalación. Solo necesitas un navegador web.

1.  **Clona o descarga** este repositorio.
2.  **Asegura los recursos**: Coloca los siguientes archivos en la misma carpeta que `index.html`:
    -   `logo_vyc.jpeg` (El logo principal de la página)
    -   `favicon.jpeg` (El ícono que aparece en la pestaña del navegador)
3.  **Abre el archivo**: Haz doble clic en `index.html` para abrirlo en tu navegador web preferido (Google Chrome, Firefox, Safari, etc.).

---

## 📂 Estructura de Archivos

El proyecto debe tener la siguiente estructura de archivos para funcionar correctamente:

```
/
├── index.html
├── logo_vyc.jpeg
└── favicon.jpeg
```

-   `index.html`: El corazón del proyecto. Contiene toda la lógica de estructura y presentación.
-   `logo_vyc.jpeg`: Imagen del logo principal. Es fundamental para la identidad visual.
-   `favicon.jpeg`: Ícono de la página.

---

## 🎨 Personalización

El código está comentado y estructurado para que sea fácil de modificar.

-   **Cambiar enlaces de WhatsApp**: Modifica los atributos `href` en las etiquetas `<a>`. Puedes usar un generador de enlaces de WhatsApp para crear los textos que necesites.
-   **Cambiar imágenes de los botones**: Actualiza las URL en los atributos `src` de las etiquetas `<img>` dentro de cada botón.
-   **Ajustar colores**: Los colores de fondo de cada botón están definidos por las clases `.btn-1`, `.btn-2`, etc. Puedes cambiar los códigos hexadecimales en la sección `<style>` del `head`.
-   **Modificar texto para redes sociales**: Edita el contenido de la meta-etiqueta `og:description` para cambiar el texto que aparece al compartir el enlace.
````