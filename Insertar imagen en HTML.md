# 4 Formas de insertar imagen en HTML

**Introdución:**

En este post veremos los siguientes puntos:
+ ¿Cómo insertar una imagen en html? (.png,.jpg, .webp, .svg, .gif)
+ ¿Cómo insertar una imagen en el body (cuerpo o background)?
* ¿Cómo insertar una imagen a un elemento (etiqueta) botton?
- ¿Cómo insertar una imagen en un input?

El objetivo es aprender distintas formas de insertar una imagen en una página web, bien sin más preámbulo empecemos.

## Insertar imagen en HTML

Para insertar una imagen en HTML usamos la etiqueta "<img>" de la siguiente forma:

    <!-- Insertando imagen en HTML -->
	<img src="Image/Avatar(Ney_Nehimy)2017_fondo blanco.png" alt="Ney">

Donde:

src: Es la url o ruta de la ubicación de la imagen.
alt: Es usado para describir la imagen, esta descripción es visible cuando nuestra imagen no carga.

## Insertar imagen en el <body>

Bueno, para poner una imagen de fondo en HTML vamos a usar un poco de CSS. En el siguiente ejemplo veremos como poner una imagen en el <body> desde el archivo HTML.

<!-- Insertando imagen en el body -->
<style> body{ background-image: url('Image/Minios(Ney).svg'); } </style>

## Insertar imagen en el elemento <button>

En este caso lo que buscamos es que la imagen funcione como un botón, es decir que al hacer clic en la imagen se ejecute algo.

En el siguiente ejemplo al hacer clic el la imagen nos va a redirigir a otro enlace.

<!-- Incrustando imagen en un elemento <button> -->
<button name="button">			
	<a href="https://twitter.com/ney01010">
	    <img class="button-img" src="Image/NekoGrande1.png">
	</a>
</button>

## Insertar imagen en el elemento <input>

<Input type = "image"> indica que una imagen funcione como un botón, en este ejemplo también vamos a redigir a una  url; pero esta vez con el "<Input>".


<!-- Incrustando imagen en un elemento <input> -->
		
<form action="https://twitter.com/ney01010">
    <input type="image" src="Image/icono_ney.png" alt="ImageNey" class="HeadNey">
</form>
        
        
