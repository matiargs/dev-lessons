# Clase 04

## [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
- que es?
	- Es un framework para crear interfaces responsivas y orientadas a mobile first
	- Tiene un listado muy grande de componentes web ya listos para usar, ej:
		- botones
		- navbar
		- inputs
		- modals
		- spinners
		- imagenes
	- por que es importante el grid system?
	-  ventajas:
		- se adapta a todas las pantallas, es perfecto para responsive
		- mobile first
		- es beginner-friendly por que con muy poco conocimiento se puede hacer una interfaz de gran calidad.
### Como se usa?
Incluyendo el stylesheet en el html, ya te brinda todas las clases necesarias para utilizar los componentes que trae definidos.
```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
```


### Layout
#### Containers
Los contenedores es la estructura mas común de un layout. 

![container](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/older-content/tdn/container610a498a5bdb429aa0c02e4f6ced8948.jpg?sfvrsn=2759355a_1)

#### Responsive Breakpoints
- que es un breakpoint?
	- Son las medidas de anchura en donde se realizan saltos para el diseño **responsive** y se aplican los estilos CSS concretos para unas determinadas media queries. Es decir, los **breakpoints** son los saltos en los que la pantalla cambia de layout
- que significa que sea "**responsive**"?
	- responsive quiere decir que va a responder y ajustarse a los cambios de ancho de la pantalla de forma automatica. Gracias a esto es que se puede diseñar y programar una pagina que se vea bien en una compu y en el celu.

![responsive-breakpoints](http://theme.support/wp-content/uploads/2018/02/responsive_breakpoints.jpg)

#### Grid System, que es?
Sistema de Grilla o Grid System es 


- usa flexbox, que es?
	- hasta 12 columnas por fila
- Bootstrap breakpoints?
	-  **.col-\*** \-for screens narrower than 576px.
	-  **.col-sm-\*** \-for screens wider than 576px.
	-  **.col-md-\*** \- for screens wider than 768px.
	-  **.col-lg-\*** - for screens wider than 992px.
	-  **.col-xl-\*** - for screens wider than 1200px.
- como se define una columna de un ancho minimo?
- row y columns
	- las columnas solo existen dentro de una fila (row) no pueden no tener un padre.
	- el contenido que estamos diseñando en columnas y filas siempre debe vivir dentro de una columna.
	- que es el `gutter` de las columnas?
	- el ancho de las columnas siempre son porcentajes de la pantalla, por eso es que sirve para que las interfaces sean 100% responsive.
![Bootstrap Grid System](https://www.bitdegree.org/learn/storage/media/images/bootstrap-grid-system.o.png)
	
## Git [(docs)](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/GitHub)
 Versionado de código (git)
	- git vs svn?
	- [documentación](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/GitHub)
	- qué es git?
	- para que se usa?
		- interfaz vs consola
	- diferencia entre git y github?
	- git clone
	- git push
	- git pull
	- [Github Desktop](https://desktop.github.com/)
