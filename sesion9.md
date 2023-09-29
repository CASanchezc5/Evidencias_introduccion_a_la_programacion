<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->
# Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

3. En el archivo CSS, agrega el siguiente código:

```css
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```

4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. Practicar el uso de las propiedades de espaciado.

- Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

```css
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

```css
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border: Agrega un borde de 5 píxeles de color rojo.

```css
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border-radius: Agrega un radio de esquina de 10 píxeles.

```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- **Unidades de medida:** Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```

## Preguntas:
1. ¿Qué es la propiedad margin?
2. ¿Qué es la propiedad padding?
3. ¿Qué es la propiedad border?
4. ¿Qué es la propiedad border-radius?
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

# Solución
## Actividad de practica
Hice unos pequeños cambios en el código original en cuanto a estilo de border y tamaños de margin y padding, este fue el resultado (aunque se practicó más veces para ver los posibles cambios que se daban al modificar las unidades de medida).

**Index.html**

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento">
        <h1>Sesion 9</h1>
    </div>
  </div>
</body>
</html>
```

**Style.css**

```css
.contenedor {
    width: 500px;
    height: 500px;
    background-color: steelblue;
    font-size: 20px;
  }
  
  .elemento {
    width: 100px;
    height: 100px;
    margin: 50%; /*cambie el margin a 50% */
    padding: 25%;/*cambie el padding a 25% */
    border: 5px dashed orangered;
    border-radius: 10px;
    background-color: lightgreen;
    font-size: 1em;
  }
```

## Respuestas a las preguntas
1. **Margin:** la propiedad se utiliza para establecer el espacio exterior alrededor de un elemento, es decir, el espacio entre el borde del elemento y los elementos adyacentes.

2. **Padding:** esta propiedad se utiliza para establecer el espacio interior alrededor del contenido de un elemento, es decir, el espacio entre el borde del elemento y su contenido.

3. **Border:** esta propiedad se utiliza para establecer el ancho, estilo y color del borde de un elemento. Entre los estilos de border tenemos: none, hidden, dotted, inset, dashed, double, groove, ridge, outset

4. **Border-radius:** esta propiedad se utiliza para establecer el radio de curvatura de las esquinas de un elemento con borde, permitiendo así crear esquinas redondeadas.

5. Las unidades de medida que se pueden utilizar para las propiedades de espaciado son: 
-	Pixeles (px)
-	Porcentajes (%)
-	Unidades absolutas
    -	Centímetros (cm)
    -	Milímetros (mm)
    -	Pulgadas (in)
    -	Puntos(pt)
-	Unidades relativas
    -	Em (em)
    -	Rem (rem)
    -	Viewport 
        -	Viewport width(vw)
        -	Viewport height (vh)








