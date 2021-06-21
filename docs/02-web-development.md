# Web Development

## Content


HTML has many tags that have different behavior.
-   `html` is the root tag
-   `head` defines `metadata` and `references` to other documents
-   `title` specifies the title of the page
-   `body` defines the content of the page

#### Headings
The `h1`, `h2`, `h3`, `h4`, `h5` and `h6` tags are meant for headings.

#### Paragraphs
 The `p` tag is used for paragraphs.

#### Lists
 The `ul` and `ol` tags represent unordered and ordered lists. They can contain `li` tags, which are list items. An `ol` represents a sequence, whereas `ul` represents a set. Rearranging the items in an ordered list changes the list's meaning. Rearranging them in an unordered list does not.

#### Images
 The `img` tag represents videos. The `src` attribute holds the URL of the image to be rendered.
 
 If you want to put an image of your choice that is on your local system:
-   Create a directory `assets/img`
-   Copy the image into the `assets/img` directory
-   Change the `src` attribute to the relative path of the image. If your image is `image.jpg`, change `src` to `assets/img/image.jpg`

#### Links
The `a` or anchor tag renders hyper text links. The `href` attribute holds the URL of 
the resource to be linked. This could be anything. A file. A webpage. Anything.

#### Attributes
- src
- href
- alt
- id
- class

![HTML Structure](https://html.com/wp-content/uploads/html-homepage-layout-demo.png)

## Styling 
### [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
**C**ascading **S**tyle **S**heets) is a declarative language that controls how webpages look in the [browser](https://developer.mozilla.org/en-US/docs/Glossary/Browser). The browser applies CSS style declarations to selected elements to display them properly. A style declaration contains the properties and their values, which determine how a webpage looks.
#### Concepts
- selector
- property
- value

property + value = declaration, multiple declaration to single selector

#### How to apply styles to a document?
- inline
- internal
- external

#### What is Cascading Inheritance? [docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance)

- How the styles will be applied?
- How cascading works?
- Specifity `tags < classes < id's < style inline`

#### Box model
![A visual representation of the box model. Content is surrounded by padding, which is surrounded by the border and then the margin is applied.](https://mdn.mozillademos.org/files/8685/boxmodel-(3).png)

#### Resources
[CSS firsts steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps)
[CSS layout (mdn)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)


## Accessibility
-	[que es?](https://developer.mozilla.org/en-US/docs/Learn/Accessibility)
-	por que es importante?

## Typography - Fonts [docs](https://html.com/fonts/)

## Others
- Favicon

### Preguntas
- Que es HTML? 
- Que es CSS?
- Para que sirve un tag `<a>`?
- Cuales son los tags principales que van dentro del tag `<html>`?
- Cual es la diferencia entre un Checkbox y un Radio button?
- Cual es la diferencia entre `<ol>` y `<ul>`?
- Donde van los atributos?
- Nombrar un atributo que puede ser general a todos los tags?
- Nombrar un atributo que solo pertenece al tag `<image>`?
- Cual es el tag que se utiliza para darle estructura a la pagina?
- Cual es la diferencia entre un atributo y una propiedad?


### Proyecto - Web development
Armar una pagina web con HTML y CSS, acerca del videojuego Portal 2.
Que debe tener?
- 3 secciones
	- home
		- pagina de inicio donde vemos una imagen (puede ser el logo del videojuego) con una breve descripción de la historia
	- personajes e items
		- pagina con un listado desordenado de los personajes e items que aparecen en el juego
		- imagen + nombre del personaje o item
	- donde conseguir el juego
		- pagina con un link al store de steam para poder comprar el juego
- debe tener head, body, footer.
- debe tener tittle
- debe tener una estructura simple de carpetas
- debe tener favicon
- debe tener un listado, ordered o unordered
- si es posible, implementar git y subirlo a un repositorio