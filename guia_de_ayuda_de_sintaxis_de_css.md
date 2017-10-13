## Guía de ayuda de sintaxis de Css

Autores:
  - Fournier Antonela
  - Fredes Carolina
  - Pellitero Sebastián
  - Torrez Llaves Dara

## Sintaxis CSS

Un conjunto de reglas CSS consiste en un *selector* y un *bloque de declaración*:

##### Selector CSS

El selector **apunta** al elemento HTML que desea diseñar.

##### Bloque de declaración

El bloque de declaración contiene una o más declaraciones separadas por punto y coma.

![alt text](https://www.w3schools.com/css/selector.gif "CSS selectors")

Cada declaración incluye un nombre de propiedad CSS y un valor, separados por dos puntos.
Una declaración CSS siempre termina con un punto y coma, y los bloques de declaración están rodeados por llaves.

En el ejemplo siguiente, todos los elementos `<p>` estarán alineados en el centro, con un color de texto rojo:
```css
p {
     color: rojo;
     text-align: center;
}
```

## Selectores CSS

Los selectores CSS se usan para *__encontrar__* (o seleccionar) elementos HTML basados en su nombre de elemento, id, clase, atributo y más.

#### Selector - Elemento

El **selector de elementos** selecciona elementos basados en el *nombre* del elemento.
Por ejemplo, puede seleccionar todos los elementos `<h1>` en una página de esta manera (en este caso, todos los elementos `<h1>` estarán alineados a la izquierda, con un tamaño de letra de 25px):

```css
h1 {
     text-align: left;
     font-size: 25px;
}
```

#### Selector - ID

El selector id utiliza el atributo id de un elemento HTML para seleccionar un elemento específico.
El id de un elemento debe ser único dentro de una página, por lo que el selector id se utiliza para seleccionar un **único elemento**!
Para seleccionar un elemento con un identificador específico, se escribe un carácter hash (#) seguido del id del elemento.
La regla de estilo siguiente se aplicará al elemento HTML con `id = para1`:

```css
#para1 {
    text-align: center;
    color: rojo;
}
```
***Nota***: *¡Un nombre de identificación no puede comenzar con un número!*

#### Selector - Clases

El selector de clases selecciona elementos con un **atributo de clase específico**.
Para seleccionar elementos con una clase específica, escriba un punto (.) Seguido del nombre de la clase.
En el ejemplo siguiente, todos los elementos HTML con `class = center` estarán en rojo y alineados en el centro:
```css
.center {
    text-align: center;
    color: rojo;
} 
```
También puede especificar que sólo los **elementos HTML específicos** deben verse afectados por una clase.
En el ejemplo siguiente, sólo los elementos `<p>` con `class = center` estarán alineados en el centro:
```css
p.center {
    text-align: center;
    color: rojo;
} 
```
Los elementos HTML también pueden referirse a **más** de una clase.
En el siguiente ejemplo, el elemento `<p>` se denominará según `class = "center"` y `class = "large"`:
```html
<p class="center large"> Este párrafo hace referencia a dos clases. </p>
```
***Nota***: *¡Un nombre de clase no puede comenzar con un número!*	

#### Selector - Agrupaciones
Si tienes elementos con la misma definicion de estilos, como por ejemplo:
h1 {
    text-align: center;
    color: red;
}

h2 {
    text-align: center;
    color: red;
}

p {
    text-align: center;
    color: red;
} 

Es mejor agrupar los selectores, para minimizar el codigo.

Para agrupar selectores, separa cada selector con una coma.

Ejemplo:

h1, h2, p {
    text-align: center;
    color: red;
} 

## Comentarios CSS
Los comentarios son usados para explicar el codigo, y podrian ayudarte cuando editas el codigo luego de un tiempo de haberlo creado.

Los comentarios son ignorados por los browsers.

Un comentario CSS comienza con /* y termina con */. Los comentarios tambien pueden ocupar multiples lineas:

Ejemplo
p {
    color: red;
    /* Esto es un comentario de solo una linea */
    text-align: center;
}

/* Estoe s
un comentario
multilinea */ 

## Bibliografía 
[w3schools.com/](https://www.w3schools.com/)
[developer.mozilla.org/](https://developer.mozilla.org/)
[en.wikipedia.org/wiki/](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

## Presentación
[drive](https://docs.google.com/presentation/d/15QZXqrbooLsYaWN04cKqfhoDMWIUovP91vR6TfxmGAM/edit#slide=id.p)