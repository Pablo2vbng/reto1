# Proyecto: Mini-sitio para el Mercado "La Albóndiga"

**Reto 1 - Diseño de Interfaces Web | UAX FP (Curso 2025/2026)**

---

### Carta de Presentación

Estimado/a evaluador/a,

Presento la solución al Reto 1, consistente en el diseño y la maquetación de un sitio web estático para un mercado de barrio ficticio, "La Albóndiga". El proyecto ha sido desarrollado siguiendo estrictamente las directrices del enunciado, utilizando exclusivamente **HTML5 y CSS3**, sin el uso de frameworks, librerías o JavaScript.

El enfoque principal ha sido la correcta **estructuración semántica** del contenido, el cumplimiento de los **estándares de accesibilidad** básicos y la creación de un **diseño responsive** que garantice una correcta visualización en dispositivos móviles, tabletas y ordenadores de escritorio.

Espero que el resultado cumpla con los objetivos y requisitos definidos en el reto.

### Resumen del Proyecto y Navegación

El sitio web busca ofrecer una presencia digital al mercado de barrio, permitiendo a los usuarios conocer sus productos, su personal y contactar fácilmente.

#### Mapa del Sitio

El sitio se compone de 3 páginas principales:
*   **Inicio (`index.html`):** Página de bienvenida con productos destacados, la historia del mercado y opiniones de clientes.
*   **Puestos (`puestos.html`):** Muestra información sobre el personal clave del mercado.
*   **Contacto (`contacto.html`):** Incluye un formulario para que los usuarios envíen sus consultas.

#### Cómo Navegar

La navegación es intuitiva a través del menú principal presente en la cabecera de todas las páginas. Adicionalmente, el logo del mercado siempre enlaza a la página de inicio.

### Instrucciones de Uso

El proyecto es un sitio web estático y no requiere ningún tipo de instalación ni servidor.

1.  Descomprimir el archivo `.zip` entregado.
2.  Navegar a la carpeta `src/`.
3.  Abrir cualquiera de los archivos `.html` (se recomienda empezar por `index.html`) en un navegador web moderno (como Google Chrome, Firefox, etc.).

### Decisiones de Diseño

*   **Layout y Maquetación:** Se ha utilizado **Flexbox** como sistema principal para la maquetación de las secciones de tarjetas (productos, opiniones, puestos) y para alinear los elementos en la navegación y el pie de página. Esto garantiza un comportamiento flexible y responsive.
*   **Paleta de Colores:**
    *   `--primary-color: #2c3e50` (Azul oscuro para textos principales y footer).
    *   `--secondary-color: #e74c3c` (Rojo para botones, enlaces y llamadas a la acción).
    *   `--background-color: #ecf0f1` (Gris claro para el fondo general, buscando un buen contraste).
*   **Tipografía:** Se ha seleccionado la familia de fuentes calibri, por su alta legibilidad en pantallas digitales.
*   **Responsividad:** El diseño es *mobile-first*. Se han definido dos puntos de ruptura (`@media` queries) principales: uno para tabletas (a partir de 768px) y otro para ordenadores de escritorio (a partir de 1200px), ajustando las columnas y el tamaño de los elementos.

### Validación y Calidad del Código

*   **W3C Validator:** El código HTML de todas las páginas ha sido validado utilizando el **W3C Markup Validation Service**, confirmando que está libre de errores.
*   **Lighthouse:** Se ha realizado una auditoría con Google Lighthouse en la página principal, obteniendo una puntuación superior a 90 en la categoría de **Accesibilidad**, lo que confirma el uso correcto de atributos `alt`, la asociación de `labels` en el formulario y una estructura de encabezados lógica.

Desarrollado por **Pablo Vidal Vidal**# reto1
