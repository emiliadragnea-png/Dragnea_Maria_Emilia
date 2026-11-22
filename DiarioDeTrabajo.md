<!-- Primero hice el diario de trabajo en este archivo markdown, luego lo pasé a pdf. -->



# Diario de trabajo — Pingüiland
## 0. Portada

**Proyecto:** Pingüiland 
**Autor/a:** Maria Emilia Dragnea
**Grupo:** DAM VESPERTINO
**Modalidad:** Presencial
**Módulo:** Lenguajes de Marcas
**Unidad didáctica:** UD02. Utilización de lenguajes de marcas en entornos web
**Fecha de entrega:** 22/11/2026

---

## 1. Descripción del proyecto

Pinguiland es una página web temática dedicada a los pingüinos. El objetivo del proyecto es crear un sitio web sencillo utilizando HTML y CSS, donde se pueda encontrar información sobre estos animales de una forma visual y organizada.

La web está formada por tres páginas: una página principal de presentación, una sección de curiosidades sobre los pingüinos y una página de contacto con un formulario.

He elegido esta temática porque me gustan los pingüinos y me pareció una idea divertida para realizar el proyecto y practicar los contenidos de HTML y CSS que he aprendido.

---

## 2. Planificación

Antes de empezar a construir la web, organicé el proyecto en tres páginas para distribuir la información y facilitar la navegación. Todas las páginas comparten un menú superior que permite desplazarse entre ellas.

### 2.1. Mapa del sitio

El sitio está formado por tres páginas HTML enlazadas entre sí mediante un menú de navegación.

- **index.html:** página principal, presentación de Pinguiland e introducción a los pingüinos.
- **curiosidades.html:** información curiosa, alimentación, especies y una tabla comparativa.
- **contacto.html:** formulario para introducir el nombre, correo electrónico, tema de interés y mensaje.

Las tres páginas permiten navegar al resto utilizando el menú.

### 2.2. Boceto básico

La distribución general que he planteado para las páginas es la siguiente:

1. Cabecera con una imagen de fondo, título y texto de presentación.
2. Menú de navegación con enlaces a las tres páginas.
3. Zona central con los apartados de contenido.
4. Pie de página con el nombre del proyecto y su autor/a.

La página principal contiene una introducción, una imagen y bloques informativos. La página de curiosidades incluye listas y una tabla. La página de contacto contiene un formulario.

### 2.3. Estructura de carpetas

He organizado los archivos del proyecto en diferentes carpetas para mantener separados los documentos HTML, los estilos CSS y las imágenes.

- Los archivos HTML se encuentran en la carpeta principal.
- La carpeta `css` contiene la hoja de estilos `estilos.css`.
- La carpeta `img` contiene las imágenes utilizadas en la web.

He utilizado nombres de archivos en minúsculas, sin espacios ni caracteres especiales, y rutas relativas para enlazar los recursos.

### 2.4. Guía de estilo

Para el diseño de Pinguiland he escogido una combinación de colores inspirada en el hielo, el mar y los tonos de los pingüinos.

- **Azul oscuro (#244b63):** utilizado en la cabecera, el pie de página y otros elementos destacados.
- **Azul claro (#b9dce9):** utilizado en el menú y elementos decorativos.
- **Fondo azul muy claro (#eaf6fa):** utilizado como fondo general de la web.
- **Blanco (#ffffff):** utilizado en los apartados de contenido para facilitar la lectura.
- **Azul medio (#467c98):** utilizado en efectos al pasar el ratón y algunos detalles.

Como fuente he utilizado Arial, porque es sencilla, fácil de leer y está disponible en la mayoría de los dispositivos. También he utilizado bordes redondeados, espacios entre los elementos y distintos tamaños de texto para que la información sea más clara y la web tenga un aspecto agradable.

## 3. Registro de sesiones

| Fecha | Tiempo aproximado | Tarea realizada | Resultado | Problemas o pendientes |
|-------|-------------------|-----------------|-----------|------------------------| 
| 28/10 | 2h | Creación de la estructura inicial de la página principal con HTML. | Primera página creada con cabecera, menú, contenido y pie de página. | Familiarizarme con la estructura de HTML. |
| 30/10 | 1h30min | Creación de la hoja de estilos CSS y elección de colores. | Primera versión del diseño de Pinguiland. | Ajustar los estilos para que los elementos se vieran correctamente. |
| 4/11 | 1h | Añadí una imagen de pingüino y una imagen de fondo en la cabecera. | La web empezó a tener un aspecto más visual y personalizado. | Ajustar la imagen y la transparencia de la cabecera. |
| 6/11 | 2h | Creación de la página de curiosidades con listas y tabla. | Página con información sobre especies y alimentación. | Organizar el contenido para que fuera fácil de leer. |
| 11/11 | 2h | Creación de la página de contacto con un formulario. | Formulario con campos de texto, selección, mensaje y botón. | El formulario es visual y no envía datos a un servidor. |
| 13/11 | 2h | Mejoras de diseño, tarjetas, efectos hover y adaptación a pantallas pequeñas. | Diseño más completo y consistente entre páginas. | Revisar detalles visuales y funcionamiento de los enlaces. |
| 20/11 | 4h | Revisión final de las páginas y preparación de la entrega. | Sitio web organizado en tres páginas conectadas. | Comprobar los requisitos y preparar los archivos de entrega. |

## 4. Decisiones de diseño justificadas

### 4.1. Estructura semántica

He utilizado diferentes elementos HTML para organizar el contenido de las páginas. Por ejemplo, `header` para la cabecera, `nav` para el menú de navegación, `main` para el contenido principal, `section` para separar los apartados y `footer` para el pie de página.

He elegido esta estructura porque permite organizar la información de forma clara y facilita la comprensión del código.

### 4.2. Inclusión de CSS

He utilizado principalmente una hoja de estilos externa llamada `estilos.css`, ubicada en la carpeta `css`, para mantener el diseño común de las páginas en un mismo archivo y evitar repetir código.

También he incluido un ejemplo de CSS interno mediante la etiqueta `style` y un ejemplo de CSS en línea mediante el atributo `style` en un elemento HTML, ya que son formas de aplicar estilos que se pedían en el ejercicio.

### 4.3. Selectores

Durante el proyecto he utilizado selectores de diferentes tipos:

- Selectores de etiquetas, como `body`, `header`, `nav`, `section` e `img`, para aplicar estilos generales.
- Selectores de clase, como `.tarjeta`, `.destacado` y `.nota`, para modificar elementos concretos.
- Selector de ID, como `#arriba`, utilizado como destino del enlace para volver al principio de la página.
- Selectores descendientes, como `nav a` y `form label`, para aplicar estilos a elementos situados dentro de otros.
- Pseudoclases, como `:hover`, para cambiar el aspecto de los elementos al pasar el ratón por encima.

### 4.4. Modelo de caja

He utilizado propiedades como `margin`, `padding` y `border` para organizar el espacio de los elementos.

El margen permite separar los apartados entre sí, el padding crea espacio interior entre el contenido y el borde, y border permite añadir bordes para diferenciar las secciones y las tarjetas.

También he utilizado bordes redondeados mediante `border-radius` para suavizar el aspecto de los bloques.

### 4.5. Navegación

He creado un menú de navegación utilizando enlaces con la etiqueta `a`. El menú aparece en las tres páginas y permite ir a Inicio, Curiosidades y Contacto.

He utilizado CSS para cambiar el color, separar los enlaces y añadir un efecto cuando se pasa el ratón sobre ellos.

### 4.6. Tablas y formularios

En la página de curiosidades he utilizado una tabla para comparar diferentes especies de pingüinos, indicando su hábitat y su altura aproximada.

En la página de contacto he creado un formulario con campos para el nombre, correo electrónico, tema de interés y mensaje. He utilizado etiquetas `label` vinculadas a sus campos mediante `for` e `id`, además de atributos como `name`, `type` y `required` para identificar los campos y establecer cuáles son obligatorios.

### 4.7. Adaptación a diferentes pantallas

He añadido una regla `@media` para adaptar algunos elementos cuando la pantalla tiene un ancho reducido. De esta forma, el menú y las tarjetas pueden organizarse mejor en dispositivos móviles y el contenido resulta más cómodo de ver.

## 5. Dificultades y soluciones

| Problema | Causa | Solución | Fuente consultada |
|---|---|---|---|
| La imagen no se mostraba correctamente. | La ruta o el nombre del archivo de imagen podía no coincidir con su ubicación. | Comprobar la carpeta `img`, el nombre del archivo y la ruta utilizada en `src`. | Investigación y comprobación en VS Code. |
| La cabecera necesitaba mejorar visualmente. | El diseño inicial era demasiado sencillo y quería añadir una imagen de fondo sin que el texto perdiera legibilidad. | Utilizar una imagen de fondo con una capa de color semitransparente mediante `linear-gradient`. | Asistente de IA y pruebas visuales en el navegador. |
| El contenido de la web necesitaba estar mejor organizado. | Al principio la página tenía pocos apartados y un diseño básico. | Añadir secciones, tarjetas informativas, espacios, bordes y estilos para organizar el contenido. | Asistente de IA y comprobaciones en el navegador. |

## 6. Declaración de uso de inteligencia artificial

| Herramienta | Para qué la usé | Consulta realizada (resumen) | Qué hice con la respuesta |
|---|---|---|---|
| ChatGPT | Recibir orientación para organizar el proyecto y aprender a utilizar HTML y CSS. | Solicité ayuda paso a paso para crear una web temática sobre pingüinos, organizar sus páginas, añadir imágenes y aplicar estilos. | Utilicé las explicaciones y ejemplos como guía para construir el proyecto en VS Code, probando los cambios en el navegador y adaptando el sitio durante el proceso. |

## 7. Recursos y referencias

- Reino Animalia Fandom. *img01.webp*. Imagen utilizada en la página principal de Pinguiland. https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQla5yw-X-4hN5tLb1WNWuQOdF_lIId4ErnWM9Qme7Vcg&s=10  
- OpenAI. ChatGPT. Herramienta de inteligencia artificial utilizada como apoyo para resolver dudas, comprender conceptos de HTML y CSS y recibir orientación durante el desarrollo del proyecto. https://chatgpt.com/ 

El código se ha elaborado siguiendo las explicaciones y ejemplos utilizados durante el desarrollo del proyecto.

## 8. Reflexión final y autoevaluación

**1. ¿Qué es lo que mejor has aprendido con este proyecto?**

Lo que más he aprendido ha sido cómo se organiza una página web utilizando HTML y cómo se puede cambiar su apariencia con CSS. También he aprendido a enlazar varias páginas, añadir imágenes, crear tablas y formularios y utilizar diferentes selectores.

**2. ¿Qué te ha costado más y cómo lo has superado?**

Al principio me costaba saber qué código debía utilizar y dónde colocar cada elemento. He ido resolviendo las dudas poco a poco, probando los cambios en Visual Studio Code y viendo el resultado en el navegador. La ayuda recibida durante el desarrollo también me ha servido para entender mejor los pasos.

**3. ¿Qué mejorarías si tuvieras más tiempo?**

Si tuviera más tiempo, añadiría más imágenes y contenido sobre diferentes especies de pingüinos, mejoraría algunos detalles visuales y ampliaría las secciones de la web para que Pinguiland tuviera todavía más información y personalidad.