<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->
# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css
Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

# Solución

**index.html**
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
    <div>
        <h1>Titulo Principal</h1>
        
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Exercitationem cupiditate quisquam temporibus sint pariatur quod quaerat aut, illo rerum sapiente eius consequatur molestiae totam blanditiis inventore dicta libero tempore non repellendus possimus enim repellat. Natus exercitationem quas recusandae quasi qui odio laborum cum. Natus nostrum unde nihil dolore voluptatibus expedita. Magni esse dolore similique illo sunt reprehenderit hic accusantium provident suscipit nesciunt. Alias aliquam iusto, nostrum est fugit laboriosam reiciendis dicta, sunt, eius magnam eligendi sequi accusamus? Similique numquam earum debitis incidunt quisquam minima eos voluptate molestias, distinctio consequatur sit officia ipsam labore, ut quo facere? Nam corporis placeat incidunt.</p>

        <a href="#">Enlace</a>
    </div>

    <h2>Titulo Secundario</h2>
    <ul>
        <li>Item1</li>
        <li>Item2</li>
        <li>Item3</li>
        <li>Item4</li>
        <li>Item5</li>
    </ul>
</body>
</html>
```

**style.css**

```css
/* PROPIEDADES COMUNES */
h1{
    color: whitesmoke;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSyFS2THm7HPqyf3Z5zqE_uxdmxTd81vrJvpg&usqp=CAU);
    background-repeat: repeat-x;
    text-align: center;
    height: 5em;
    
}

h2{
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    font-style: italic;
}


a{
    text-decoration: dotted;
}

/* PSEUDOCLASE */
a:hover{ 
    cursor:pointer;
    background-color: aqua;
}

p:hover{
    background-color: aquamarine;
}

li:nth-of-type(1):hover {
    background-color: red;
  }
  
li:nth-of-type(2):hover {
    background-color: green;
  }
  
li:nth-of-type(3):hover {
    background-color: blue;
  }

li:nth-of-type(4):hover {
    background-color: yellow;
  }

li:nth-of-type(5):hover {
    background-color: purple;
  }


/* PSEUDOELEMENTO */

/* de contenido */
p::first-letter{
    color: blue;
    font-size: 100px;
}

/* de posicion */
p::after {
    content: "→";
    font-size: 20px;
    position: absolute;
    bottom: 0;
    right: 0;
  }
 
.p2::before {
    content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
}
```





