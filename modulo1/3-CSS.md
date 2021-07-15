
# CSS

## ¿Qué es CSS?
	Hojas de estilo en cascada
Las hojas de estilo CSS nos permiten definir la apariencia de los elementos HTML. Nos permiten definir el diseño de múltiples elementos y páginas web en un solo sitio.

## Anatomía de CSS

 - Selector
 - Declaraciones
	 - Propiedad
	 - Valor
	 
## Selectores

### Selectores simples
 - `tag name`
 - `id`
 - `class`


### Atributos más comunes
- color
 - background-color
 - border
 - margin
 - padding
 - height
 - width
 - display
 

## CSS en la práctica

### Insertar CSS en un documento HTML

 - Inline (`<tag style="">`)
 - CSS Interno ( `<style>`)
 - CSS externo ( `<link rel="stylesheet" href="mystyle.css">`)
 - Agregar comentarios en CSS.

### CSS con clases por componente y por funcionalidad


## Selectores avanzados

### Selectores combinados

 - Selectores descendientes ( espacio )
 - Selectores hijo (>)
 - Selectores hermano adyacente (+)
 - Selectores hermano general (~)
 
### Selectores de pseudo-clase
Son utilizados para definir el **estado** de un elemento. Los más comunes son:

 - Para Links:
	 - :link
	 - :visited
	 - :hover
	 - :active
 - :hover
 - :first-child
 - :nth-last-child(n)

### Selectores de pseudo-elementos

 - ::after
 - ::before
 - ::first-letter
 - ::first-line
 - ::selection

### Selectores de atributo

 - [atributo]
 - [atributo="valor"]

### Navegar en el DOM con CSS

### Box Model

### Posicionamiento

 - `static` (default)
 - `relative` (relativa a static)
 - `fixed` (fija con respecto al viewport)
 - `absolute` (fija con respecto al primer ancestro posicionado [no static])
 - `sticky` (relative antes de llegar al scroll. fixted después de pasar el scroll.)
