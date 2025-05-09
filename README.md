# Página web de Dulcinea Cream

Esta es mi landing page. Creé una página sencilla para un negocio de postres y dulces artesanales llamado "Dulcinea Cream".

## ¿Qué hace mi página?

Mi página muestra información sobre algunos de nuestros productos que es de mi emprendimiento. Incluye:

- Un encabezado con logo y menú de navegación
- Una sección principal con una imagen grande y texto
- Tarjetas de los productos que ofrecen (brownies, cheesecake y galletas)
- Un formulario para que los clientes puedan contactar al negocio
- Un pie de página con información

## Estructura de carpetas

```
BOOTCAMPS/
  ├── index.html
  ├── js
  ├── assets
  ├── css/
  │   └── style.css
  └── img/
      ├── logo.png
      ├── postres.jpg
      ├── brownie.jpg
      ├── cheesecake.jpg
      └── galletas.jpg
```


## Metodología BEM

Para organizar mi CSS, utilicé la metodología BEM (Block, Element, Modifier), que aprendí recientemente en un curso que hice. BEM me ayuda a nombrar mis clases CSS de forma ordenada:

- **Bloque**: Una sección independiente de la página (por ejemplo: header, hero, productos)
- **Elemento**: Una parte de un bloque (por ejemplo: header__logo, hero__title)
- **Modificador**: Una variante de un bloque o elemento (aunque no necesité usarlos en este proyecto)

### Ejemplos de BEM en mi código:

- `.header` es un bloque
  - `.header__logo-container` es un elemento del header
  - `.header__logo-img` es un elemento del header
  - `.header__logo-text` es un elemento del header
  - `.header__nav` es un elemento del header

- `.hero` es un bloque
  - `.hero__content` es un elemento del hero
  - `.hero__image` es un elemento del hero

- `.producto-card` es un bloque
  - `.producto-card__title` es un elemento de la tarjeta
  - `.producto-card__img` es un elemento de la tarjeta

## Lo que aprendí

En este proyecto practiqué:
- Estructurar una página web con HTML 
- Nombrar clases usando BEM
- Usar CSS Grid para la sección principal
- Crear tarjetas de productos
- Hacer un formulario básico
- Aplicar estilos CSS básicos como colores, fuentes y espaciados

## Cómo ver la página

Para ver mi página:
1. Descarga todos los archivos
2. Asegúrate de tener todas las imágenes en la carpeta "img"
3. Abre el archivo index.html en tu navegador

