<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->
# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado `<header>`
- Tres párrafos `<p>`
- Una imagen `<img>`
- Un pie de página `<footer>`

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados `<h1>`
- Color azul a los párrafos `<p>`
- Borde grueso negro a la imagen `<img>`

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un `<div>`
- Centrar el contenido de la sección `<section>`


# Solución

Asi queda la actividad realizada con su respectivo index.html y style.css:


**Index.html**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>

</head>

<body>
    <header>
        <h1>CSS</h1>
        <img src="https://firebasestorage.googleapis.com/v0/b/imagenes-dd8e6.appspot.com/o/css.png?alt=media&token=eb1d877b-44cc-4a26-ba5a-84ad4843bffb" alt="logo css">
    </header>


    <h2 id="principal">Selectores de CSS</h2>
    <h3 id="sombras">Algunos son:</h3>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laborum, <span class="destacado">praesentium quod odit
            at optio</span> quae, eius unde minima voluptatum dicta beatae nulla fugit a dolorem ut? Totam veniam ex,
        aliquam error mollitia consequuntur aperiam. Distinctio, assumenda officiis a nostrum dolorum nulla possimus
        voluptatum similique corrupti vitae molestiae dolores, doloremque illum.</p>
    <p class="grande">Lorem, dolorum.</p>

    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur distinctio temporibus asperiores fugit vel
            aperiam hic accusamus eos excepturi dolore? Possimus reprehenderit delectus repudiandae eligendi dolorum
            earum in, nemo illo?</p>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur numquam dicta aut, obcaecati neque
            dolores aliquam illo omnis fugiat hic.</p>
    </div>

    <section>
        <P>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque, aliquid consectetur, molestiae in beatae
            similique non asperiores repudiandae veniam, facere alias atque fugiat quo sed eum optio ratione explicabo
            adipisci possimus necessitatibus doloremque illum ex molestias praesentium. Cum vitae maiores porro debitis
            consequuntur, nisi ipsum aut incidunt dignissimos reprehenderit autem nulla enim quidem quisquam ipsa
            sapiente. Odit repudiandae deserunt ad accusantium temporibus iusto consectetur blanditiis necessitatibus?
            Quae commodi magnam debitis accusantium consequatur placeat optio, culpa error est deserunt soluta delectus,
            vel quibusdam voluptatibus distinctio laborum ullam. Magni, placeat aliquam deserunt, nam molestias
            consequatur numquam adipisci quas corrupti corporis voluptatem vel.</P>
    </section>

    <footer>
        Carlos Andrés Sánchez Correa
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>



</body>

</html>
```


**Style.css**

```css
/* SELECTORES DE ETIQUETA */
h1{
    color: red;
}

p{
    color: blue;
}

img{
    border: 5px solid black;
}

footer{
    background-color: #8885856b;
}


/* SELECTORES DE CLASE */
.destacado{
    color: green;
}

.grande{
    font-size: 20px;
}


/* SELECTORES DE IDENTIFICACION */
#principal{
    color:yellow;
}

#sombras{
    text-shadow: 5px 5px teal;
}


/* SELECTORES DESCENDIENTES */
div p{
    color: gray;
}

section p{
    text-align: center;
}
```








