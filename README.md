# Prompt: Sitio web interactivo sobre economía digital y comercio electrónico (estilo editorial Vogue España)

Actúa como ingeniero/a frontend sénior y diseñador/a de experiencia de usuario con IA. Crea un sitio web interactivo y adaptable a cualquier pantalla usando la base de conocimiento adjunta como fuente principal de información.

Genera código HTML, CSS y JavaScript listo para publicar, con un diseño moderno, navegación intuitiva, adaptación a móvil, buscador, preguntas frecuentes, secciones interactivas y una jerarquía visual clara.

Genera la aplicación en un **único archivo HTML completo y autocontenido** (incluyendo `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`), enlazando **Tailwind CSS** y **FontAwesome** vía CDN en el `<head>`, para que se pueda guardar directamente como `.html` y abrir en cualquier navegador sin configuración adicional.

**No inventes nunca datos que no estén en las fuentes cargadas.** Si falta información para alguna sección, indícalo en lugar de inventarla.

---

## Contexto

- **Público:** personas que comienzan a trabajar en el sector y no conocen la economía digital y el comercio electrónico.
- **Objetivo:** que entiendan qué es la economía digital y el comercio electrónico, qué cambia en su día a día y qué riesgos tiene.
- **Secciones:** Inicio · Qué es · Cómo funciona · Ventajas y riesgos · Preguntas frecuentes · Fuentes.

---

## Estilo visual: diseño web editorial inspirado en Vogue España

Diseña y desarrolla una página web con una estética editorial de alta gama, inspirada en el lenguaje visual de Vogue España (https://www.vogue.es/). El objetivo es transmitir elegancia, sofisticación, modernidad y autoridad editorial, como una revista de moda internacional trasladada al entorno digital.

### 1. Dirección artística

- **Estilo:** editorial de lujo, minimalista, sofisticado y contemporáneo.
- **Personalidad visual:** elegante, atrevida, cultural y aspiracional.
- **Inspiración:** revistas de moda impresas, fotografía de alta calidad, editoriales de tendencias y publicaciones premium.
- **Principio fundamental:** el contenido y las imágenes deben ser los protagonistas; evita los adornos innecesarios, las interfaces recargadas y los efectos visuales excesivos.

### 2. Paleta de colores

Utiliza una paleta predominantemente neutra que permita destacar las fotografías y los titulares.

| Color | Código | Uso |
|---|---|---|
| Blanco puro | `#FFFFFF` | Fondo principal |
| Negro intenso | `#111111` | Titulares, navegación y textos destacados |
| Gris oscuro | `#333333` | Textos secundarios |
| Gris claro | `#E5E5E5` | Separadores y bordes sutiles |
| Gris muy claro | `#F7F7F7` | Fondos alternativos para determinadas secciones |

Reserva los colores intensos para las propias imágenes editoriales y para pequeños detalles cuando sea necesario. No utilices degradados llamativos, sombras pronunciadas ni colores saturados como base del diseño.

### 3. Tipografía

Combina dos familias tipográficas con funciones claramente diferenciadas:

- **Titulares:** tipografía serif de carácter editorial, elegante y con personalidad, similar al estilo de Didot o Bodoni.
- **Navegación, etiquetas y textos auxiliares:** tipografía sans serif limpia y moderna, como Helvetica, Arial o Inter.
- **Titulares principales:** grandes, con contraste tipográfico y una jerarquía visual muy marcada.
- **Cuerpo de texto:** legible, con interlineado generoso y una anchura de lectura cómoda.
- **Etiquetas de categoría:** pequeñas, en mayúsculas y con espaciado entre letras.

Puedes utilizar **Playfair Display** como alternativa accesible para los titulares e **Inter** para los elementos funcionales.

### 4. Cabecera y navegación

Crea una cabecera elegante, limpia y reconocible:

- Logotipo tipográfico de gran presencia, centrado o cuidadosamente alineado.
- Menú horizontal con las principales secciones.
- Navegación secundaria discreta y bien espaciada.
- Iconos minimalistas para búsqueda, menú y cuenta, cuando proceda.
- Líneas divisorias finas para separar la cabecera del contenido.
- Cabecera fija al desplazarse solo si mejora realmente la experiencia de navegación.

El menú debe ser sencillo y funcional. En dispositivos móviles, conviértelo en una navegación compacta con menú desplegable.

### 5. Diseño de la página principal

Construye una portada editorial que funcione como la de una revista digital.

**Noticia o contenido principal**

- Una fotografía de gran formato que ocupe una parte importante del ancho disponible.
- Una composición visual impactante, con fotografía de moda, retratos o escenas editoriales.
- Un titular destacado con tipografía serif y un tamaño considerable.
- Una etiqueta de categoría discreta.
- Una breve introducción y, cuando corresponda, el nombre del autor y la fecha.

**Rejilla de contenidos**

Debajo del contenido principal, organiza los artículos en una composición editorial asimétrica y equilibrada.

- Tarjetas con imágenes grandes y proporciones coherentes.
- Mezcla de artículos destacados y noticias secundarias.
- Titulares de distintos tamaños según su importancia.
- Espaciado generoso entre elementos.
- Alineación precisa y márgenes consistentes.
- Separación entre secciones mediante espacio en blanco y líneas finas.

Evita que todas las tarjetas tengan exactamente el mismo tamaño. La jerarquía visual debe guiar la mirada y dar más importancia a las historias principales.

### 6. Imágenes y fotografía

La fotografía es uno de los elementos más importantes del diseño. Utiliza imágenes editoriales de alta resolución, con iluminación cuidada, composiciones profesionales y una dirección artística coherente.

Prioriza:

- Fotografía de moda y retrato.
- Primeros planos y encuadres cinematográficos.
- Escenas naturales, elegantes y sofisticadas.
- Imágenes con personalidad, textura y una paleta cromática equilibrada.
- Recortes bien definidos y proporciones consistentes.

Las imágenes deben integrarse de forma natural en la composición. No utilices ilustraciones genéricas, fotografías de baja calidad ni imágenes de stock con apariencia artificial.

### 7. Secciones editoriales

Organiza el contenido en secciones claramente diferenciadas, como:

- Moda y tendencias.
- Belleza.
- Cultura y actualidad.
- Estilo de vida.
- Entrevistas y reportajes.
- Inspiración y recomendaciones.

Cada sección debe mantener la misma identidad visual, pero puede tener una composición editorial propia. Introduce títulos de sección destacados, artículos principales y rejillas secundarias para que la página tenga ritmo visual y variedad.

### 8. Detalles de interfaz y animaciones

Utiliza interacciones discretas que refuercen la sensación de calidad:

- Transiciones suaves al pasar el cursor sobre imágenes y enlaces.
- Cambios sutiles de opacidad o escala en las fotografías.
- Animaciones breves y elegantes al aparecer determinados contenidos.
- Subrayados finos en enlaces interactivos.
- Botones minimalistas, con estados *hover* bien definidos.
- Transiciones rápidas y naturales entre estados de navegación.

Evita las animaciones excesivas, los efectos de cristal, las tarjetas con sombras fuertes, los bordes redondeados exagerados y los elementos decorativos propios de un dashboard.

### 9. Diseño adaptable

La web debe funcionar perfectamente en escritorio, tablet y móvil.

- **Escritorio:** composición editorial amplia, con varias columnas y titulares grandes.
- **Tablet:** adapta la rejilla y reduce los espacios de forma proporcional.
- **Móvil:** prioriza la lectura, las imágenes y una navegación sencilla.
- Mantén una jerarquía tipográfica clara en todas las resoluciones.
- Evita desbordamientos horizontales, saltos de diseño y elementos superpuestos.

Optimiza las imágenes y utiliza carga diferida (*lazy loading*) cuando sea apropiado para mejorar el rendimiento.

### 10. Requisitos de implementación

- Utiliza HTML semántico, CSS organizado y JavaScript solo cuando sea necesario.
- Mantén una estructura reutilizable para las tarjetas, las secciones y los elementos de navegación.
- Utiliza variables CSS para los colores, la tipografía, los espacios y los tamaños.
- Cuida la accesibilidad, el contraste, los estados de foco y la navegación mediante teclado.
- Optimiza el rendimiento y los metadatos SEO.
- No sacrifiques la legibilidad por conseguir un resultado visualmente atractivo.

---

## Resultado esperado

Una web editorial premium, elegante y contemporánea, con la fuerza visual de una revista de moda de lujo. Debe destacar por sus fotografías, sus titulares serif, sus espacios en blanco, su composición editorial y su navegación limpia.

> **Importante:** utiliza Vogue España como referencia de dirección artística y diseño editorial, pero crea una identidad original. No reproduzcas su logotipo, sus textos, sus imágenes protegidas ni una copia exacta de su interfaz. Adapta esta dirección visual al contenido y a la identidad de la web que se está desarrollando.
