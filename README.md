# *README PARTE TEÓRICA* 💻✏️

### *1. ¿Qué es HTML y cuál es su función en la web?* 🐼
HTML, que significa HyperText Markup Language (Lenguaje de Marcado de Hipertexto), es el lenguaje estándar para estructurar documentos destinados a mostrarse en navegadores web. A través de etiquetas, HTML organiza el contenido como texto, imágenes, videos, enlaces y otros elementos, formando la base de toda página en internet.
HTML sirve para estructurar el contenido de una página web con títulos, párrafos, imágenes y enlaces.
También aporta significado semántico, lo que mejora la accesibilidad y el posicionamiento en buscadores.
Finalmente, actúa como la base de integración con CSS para el diseño y JavaScript para la interactividad.
---
---
### *2. ¿Qué es una etiqueta HTML? y menciona las etiquetas más comunes.* 🐼

Una etiqueta HTML es un elemento de marcado que se usa para indicar al navegador cómo debe mostrarse o estructurarse una parte del contenido en una página web. Están formadas por un nombre entre corchetes angulares `(< >)` y, generalmente, se escriben en pares: una etiqueta de apertura `<p>` y otra de cierre `</p>`.
Etiquetas HTML más comunes: 
 - `<html>` → Indica el inicio del documento HTML.
 - `<head>` → Contiene metadatos, enlaces a estilos, scripts, etc.
 - `<title>` → Define el título de la página en la pestaña del navegador.
 - `<body>` → Contiene todo el contenido visible de la página.
 - `<h1>` a `<h6>` → Encabezados de mayor a menor importancia.
 - `<p>` → Párrafos de texto.
 - `<a>` → Hipervínculos o enlaces.
 - `<img>` → Inserta imágenes.
 - `<ul>`,`<ol>`,`<li>` → Listas (no ordenadas, ordenadas y elementos de lista).
 - `<div>` y `<span>` → Contenedores para agrupar y organizar elementos.
 - `<form>`,`<input>`,`<button>` → Formularios e interacción del usuario.
---
### *3. ¿Qué es un atributo de una etiqueta HTML? y menciona los más comunes.* 🐼

Un atributo en HTML es una propiedad extra que se añade dentro de una etiqueta para dar información adicional o modificar su comportamiento. Siempre van en la etiqueta de apertura y se escriben con la forma `nombre="valor"`.
🔹 Ejemplo: `<img src="gato.jpg" alt="Un gato bonito" width="200">`
Donde los atributos siempre van dentro de la etiqueta y modifican cómo se comporta o se muestra:
- `<img>` → es la etiqueta para mostrar una imagen.
- `src="gato.jpg"` → atributo que indica la ruta de la imagen.
- `alt="Un gato bonito"` → atributo que muestra un texto alternativo si no carga la imagen.
- `width="200"` → atributo que define el ancho de la imagen en píxeles.

### ✅ Atributos más comunes en HTML: ✅
- `id` → Identificador único para un elemento.
- `class` → Agrupa elementos con un mismo estilo o comportamiento.
- `style` → Aplica estilos en línea `(ej. style="color:red;")`.
- `src` → Fuente de un recurso `(ej. en <img> o <script>)`.
- `alt` → Texto alternativo en imágenes, útil para accesibilidad y SEO.
- `href` → Dirección de un enlace.
- `title` → Texto emergente al pasar el cursor.
- `width` y `height` → Definen tamaño de imágenes o videos.
- `type` → Especifica el tipo de input en formularios.
- `value` → Valor de un campo de formulario.
--- 
### *4. ¿Qué es CSS y cómo se utiliza para el diseño web?* 🐼

CSS (Cascading Style Sheets) es el lenguaje que define la apariencia visual de una página web. Se usa junto con HTML, separando el contenido de su diseño. Gracias a CSS, un sitio puede tener colores, tipografías, espaciados, fondos, efectos y animaciones, manteniendo el código más limpio y fácil de mantener.
### En diseño web, CSS se utiliza para aplicar estilos visuales como fuentes, colores, tamaños, fondos, bordes, sombras y animaciones; además permite la separación entre contenido y diseño, ya que los estilos se guardan en archivos externos que hacen el sitio más organizado y veloz; también facilita un diseño adaptable mediante media queries y técnicas como flexbox que ajustan la visualización a móviles, tablets o escritorio; y, finalmente, aporta eficiencia, pues las propiedades modernas de CSS3 sustituyen imágenes decorativas, reduciendo el peso de la página y mejorando su rendimiento.
---
### *5. ¿Qué es una propiedad en CSS? y menciona las propiedades más comunes.* 🐼

Una propiedad en CSS es una característica que permite modificar el estilo visual o el comportamiento de un elemento HTML. Se coloca dentro de una regla CSS y se acompaña de un valor específico. Las propiedades son los parámetros que configuran desde el color y tamaño de la fuente hasta la animación, el espacio, el fondo y mucho más. Se escribe como `propiedad: valor;`, por ejemplo:
🔹`p { color: blue; font-size: 16px; }`
Propiedades más comunes:
- Texto: `color`, `font-size`, `font-family`, `font-weight`, `text-align`
- Caja (Box Model): `margin`, `padding`, `border`, `width`, `height`
- Fondo y estilo: `background-color`, `background-image`, `border-radius`, `box-shadow`
- Diseño/Layout: `display`, `flex`, `grid`, `position`
- Efectos: `transition`, `animation`
---

### 6. ¿Qué es un selector en CSS y cuáles tipos existen? 🎯
Los selectores en CSS permiten elegir qué elementos HTML se van a estilizar. Básicamente son la forma de “apuntar” a un elemento para aplicarle reglas de diseño.  
**Tipos más comunes**:
- `elemento {}` → selecciona etiquetas (ej: `p`, `h1`).
- `.clase {}` → selecciona elementos con una clase.
- `#id {}` → selecciona un elemento con un id único.
- `* {}` → selecciona todos los elementos.
- `elemento elemento {}` → selecciona elementos dentro de otros (ej: `div p`).

---

### 7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web? ⚡
JavaScript es un lenguaje de programación que permite dar dinamismo e interactividad a las páginas web. Mientras que HTML estructura y CSS diseña, **JavaScript agrega acciones**, como validar formularios, mostrar alertas, modificar contenido sin recargar la página o crear animaciones.

---

### 8. ¿Cuáles son los tipos de datos primitivos en JavaScript? 🔢
Los datos primitivos son los valores básicos que maneja el lenguaje.  
**Principales tipos:**
- `string` → cadenas de texto.
- `number` → números (enteros y decimales).
- `boolean` → verdadero o falso.
- `null` → valor vacío intencional.
- `undefined` → valor sin asignar.
- `symbol` → identificadores únicos.
- `bigint` → números muy grandes.

---

### 9. ¿Cómo funcionan las estructuras de control de flujo en JavaScript? 🔄
Controlan la ejecución del código según condiciones o repeticiones:
- `if` / `else` → ejecutan código si una condición se cumple o no.
- `switch` → evalúa múltiples casos de una variable.
- `for` → repite un bloque un número determinado de veces.
- `while` → repite mientras se cumpla una condición.
- `do...while` → ejecuta al menos una vez y luego evalúa la condición.

---

### 10. ¿Por qué es importante usar nombres significativos para variables y métodos? 📝
Usar nombres claros hace que el código sea **más fácil de leer, mantener y entender** por otros desarrolladores (o por ti mismo en el futuro). Evita confusiones y ayuda a identificar rápidamente qué hace cada parte del programa.

---

### 11. ¿Qué es una variable de entorno y por qué son importantes? 🌍
Son valores definidos fuera del código que la aplicación puede usar, como claves de API, puertos o configuraciones.  
**Importancia:**
- Separan datos sensibles del código.
- Facilitan la configuración en distintos entornos (desarrollo, pruebas, producción).
- Mejoran la seguridad y portabilidad.

---

### 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas? 🛠️
Son utilidades integradas en el navegador que permiten inspeccionar, depurar y optimizar sitios web.  
👉 Se accede con `F12` o `Ctrl + Shift + I` (Windows/Linux) y `Cmd + Option + I` (Mac).

---

### 13. ¿Qué se puede hacer en el panel "Elements"? 📑
Permite **inspeccionar y modificar en tiempo real** el código HTML y los estilos CSS de una página. Es útil para probar cambios rápidos sin alterar los archivos originales.

---

### 14. ¿Cómo se utiliza el panel "Console" y para qué es útil? 💻
La consola sirve para **ejecutar código JavaScript en tiempo real**, mostrar errores y depurar. También permite imprimir mensajes (`console.log`) para verificar el funcionamiento del programa.

---

### 15. ¿Qué información se puede obtener del panel "Network" y por qué es importante? 🌐
Muestra todas las **peticiones y recursos** que carga una página: archivos, imágenes, scripts y tiempos de carga. Es clave para:
- Detectar errores en solicitudes.
- Optimizar el rendimiento.
- Verificar si un recurso está siendo bloqueado o tarda demasiado.

---
