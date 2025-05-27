# juanjodominguez
Homenaje al guitarrista Juanjo Dominguez


# Descripción del sitio web: Juanjo Domínguez

Este proyecto es una página web en HTML y CSS dedicada al guitarrista argentino **Juanjo Domínguez**, destacando su historia, discografía, videos y un formulario de contacto.

## 📄 Estructura del Sitio

El sitio está organizado en una sola página (estructura **one-page**) con navegación interna por anclas (`#id`). Contiene las siguientes secciones principales:

### 1. Encabezado (`<header>`)
- Título del sitio: "Juanjo Domínguez".
- Menú de navegación con enlaces a las secciones: `Inicio`, `Discografía`, `Video`, `Consultas`.
- El menú es fijo al principio de la página y reaparece al volver arriba.

### 2. Sección `Inicio` (`#inicio`)
- Breve biografía del artista.
- Imagen destacada de Juanjo tocando la guitarra.
- Cita destacada de Paco de Lucía.

### 3. Sección `Discografía` (`#discografia`)
- Muestra 3 discos con su carátula e información.
- Usa `Grid y Flexbox` para organizar las tarjetas de los discos y lista de temas.
- Adaptada a distintos tamaños de pantalla con `media queries`.

### 4. Sección `Video` (`#video`)
- Reproductor de YouTube embebido con un video destacado de Juanjo Domínguez.

### 5. Sección `Consultas` (`#consultas`)
- Formulario de contacto con los campos: Nombre, Correo electrónico, Teléfono y Mensaje.
- Incluye validaciones HTML básicas (`required`).

### 6. Pie de Página (`<footer>`)
- Menú de navegación repetido.
- Texto de copyright.

### 7. Enlaces "Volver arriba"
- Enlace con el texto "↑ Volver arriba" que lleva al menú del sitio (`#menu`).

---

## 🎨 Estilos (CSS)

- Fuente principal: **Merriweather**, importada desde Google Fonts.
- Diseño responsive mediante **media queries**:
  - Celulares: navegación en columna y contenido apilado.
  - Tablets: distribución uniforme.
  - PC: distribución amplia y separada.
- Uso de `Flexbox` para:
  - Navegación.
  - Lista de temas.
  - Formularios.
- Estilos visuales:
  - Colores sobrios (negro, verde, blanco).
  - Bordes redondeados, sombras suaves y espaciado limpio.
  - Botones con efecto hover.
- Uso de `Grid` para:
  - Contenedores de discos.


---

## 🔧 Tecnologías utilizadas

- HTML5
- CSS3
- Google Fonts
- Flexbox y Grid
- Media Queries
- YouTube embed

---

## 📁 Archivos relacionados

- `index.html`: estructura principal del sitio.
- `style.css`: hoja de estilos personalizada.
- `img/`: carpeta con imágenes de discos y de Juanjo.
- `info.md`: este archivo de documentación.

---

## 👤 Autor del sitio Torres Ariel Mauricio

Sitio desarrollado como homenaje a Juanjo Domínguez.  
Creado como parte de un proyecto académico de Talento Tech sobre Front End JS.
C25013


