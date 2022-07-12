# Extra Markup

| Contenidos |
|------------|
| Doctypes |
| Comments in HTML |
| ID attribute |
| Class attribute |
| Grouping in a block |
|  |
## Doctypes
Se usa para deirle al buscador qué versión de HTML se está usando.  
Nosotros estaremos usando la siguiente forma por usar HTML 5.

~~~html
<!DOCTYPE html>
~~~

## Comments in HTML
Si quieres agregar un comentario al código y no deseas que sea visible para el usuario, puedes agregar texto entre los siguienes caracteres:
~~~html
<!-- Esto es un comentario en HTML -->
~~~

## ID Attribute
Todos los elementos pueden tener un atributo de **id**. Se usa para identificar de manera única ese elemento de los otros en la página.  
No se pueden tener dos elementos con el mismo id en la misma página.

~~~html
<p id="pullquot">Aquí podrías poner una cita de un libro y luego ponerle estilo usando CSS</p>
~~~

## Class Attribute
Todos los elementos de HTML pueden tenern el atributo **class**. Algunas veces, en vez de querer identificar de manera única un elemento, lo quieres hacer en distintos gurpos

~~~html
<p class="importante">Este párrafo es importante</p>
<p class="general">Este párrafo solo contiene información general</p>
~~~

## Block Elements
Son aquellos que siempre aparecen en una nueva línea en el buscador.  
Ejemplos de ellos son los siguientes elementos:
~~~html
<h1>Headers</h1>
<p>Párrafos</p>
<ul>
    <li>Listas</li>
    <li> Y sus elementos</li>
</ul>
~~~

## Inline Elements
Algunos elementos siempre aparecen en la misma línea que sus vecinos.  
Ejemplos de ellos son:
~~~html
<a> <b> <em> <img>
~~~

## Grouping Text & Elements in a Block
El elemento `div` te permite agrupar elementos juntos en un block-level box.  
  
Por ejemplo, puedes crear un elemento `div` para contener todos los elementos del header. Los elementos del div empiezan en una nueva línea, pero además de esto, no hay ninguna diferencia para el usuario final.
  
La ventaja de esto es que con CSS puedes modificar el estilo de cada bloque por separado al usar los atributros de **id** y **class**.
