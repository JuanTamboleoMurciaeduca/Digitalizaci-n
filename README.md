# Página Web Básica sobre Redes LAN

Este proyecto es una página web simple escrita en HTML, CSS y JavaScript para presentar información sobre redes LAN. A continuación, se explican las etiquetas utilizadas en el código, los estilos aplicados mediante CSS y la funcionalidad añadida con JavaScript.

## Estructura del Archivo HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redes LAN</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <button onclick="toggleDarkMode()">Cambiar Modo Claro/Oscuro</button>
    <!-- Contenido de la página -->
    <script src="script.js"></script>
</body>
</html>
```

### Explicación de las Etiquetas Usadas

| Etiqueta | Descripción |
|----------|------------|
| `<!DOCTYPE html>` | Define el tipo de documento como HTML5. |
| `<html lang="es">` | Elemento raíz del documento, con atributo `lang="es"` para indicar que el idioma es español. |
| `<head>` | Contiene metadatos sobre la página. |
| `<meta charset="UTF-8">` | Especifica la codificación de caracteres para soportar caracteres especiales. |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Ajusta la escala de la página en dispositivos móviles. |
| `<title>` | Define el título de la página que aparece en la pestaña del navegador. |
| `<link rel="stylesheet" href="styles.css">` | Enlaza el archivo CSS para aplicar estilos a la página. |
| `<body>` | Contiene el contenido visible de la página. |
| `<button>` | Botón que activa la funcionalidad de cambiar entre modo claro y oscuro. |
| `<script src="script.js">` | Enlaza el archivo JavaScript que proporciona funcionalidades a la página. |
| `<h1>` | Encabezado principal de la página. |
| `<h2>` | Subtítulos para secciones dentro de la página. |
| `<p>` | Párrafo de texto. |
| `<ul>` | Lista desordenada (con viñetas). |
| `<ol>` | Lista ordenada (numerada). |
| `<li>` | Elemento dentro de una lista (`ul` o `ol`). |
| `<table>` | Crea una tabla. |
| `<tr>` | Fila dentro de una tabla. |
| `<th>` | Encabezado de columna en una tabla. |
| `<td>` | Celda de datos dentro de una tabla. |
| `<footer>` | Pie de página con información adicional. |

## Estilos CSS Aplicados

El archivo `styles.css` define los estilos para mejorar la presentación de la página web.

### Principales Estilos Utilizados

| Selector | Descripción |
|----------|------------|
| `body` | Define la fuente, el color de fondo y el espaciado general de la página. |
| `h1, h2` | Estiliza los encabezados con colores y bordes decorativos. |
| `ul, ol` | Ajusta los márgenes de las listas. |
| `table` | Aplica un diseño con bordes y fondo blanco para mejorar la visualización. |
| `th` | Define el color de fondo de los encabezados de la tabla. |
| `footer` | Estiliza el pie de página con un fondo oscuro y texto claro. |
| `.dark-mode` | Clase que cambia el fondo y el color de texto para modo oscuro. |

## Funcionalidad JavaScript

Se ha añadido un archivo `script.js` que contiene una funcionalidad para cambiar entre modo claro y modo oscuro en la página.

### Código Principal

```javascript
function toggleDarkMode() {
    document.body.classList.toggle('dark-mode');
}
```

Al hacer clic en el botón "Cambiar Modo Claro/Oscuro", se alterna la clase `dark-mode` en el elemento `body`, cambiando los estilos visuales del sitio.

## Uso

Para ver la página:
1. Asegúrate de que los archivos `index.html`, `styles.css` y `script.js` estén en la misma carpeta.
2. Abre el archivo `index.html` en cualquier navegador web.
3. Usa el botón para alternar entre modo claro y oscuro según prefieras.
