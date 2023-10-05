<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->
# Actividad: Propiedades de posicionamiento de CSS
Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, crea una estructura básica de página web con dos elementos div.
3. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.


Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```

Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

Preguntas:

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

# Solución

**index.html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Ejemplo de posicionamiento de CSS</title>
</head>
<body>
    <div class="elemento-1">CAJA1</div>
    <div class="elemento-2">CAJA2</div> 
</body>
</html>
```

**style.css**
```css
.elemento-1 {
    position: absolute;
    top: 100px;
    left: 100px;
    background-color: red;
    display: flex;
    z-index: 2;
  }

.elemento-2 {
    position: relative;
    top: 100px;
    left: 100px;
    background-color: green;
    display: inline-block;
    width: 100px;
    height:250px ;
    z-index: 1;
  }
```

## Respuesta a las Preguntas
- Diferencia entre position: absolute y position:

**position: absolute:** Cuando se establece position: absolute en un elemento (como .elemento-1 en este caso), este se posiciona en relación con su ancestro posicionado más cercano (un elemento con una posición distinta a static) o en relación con el documento si no hay ancestros posicionados. Las propiedades top, right, bottom y left se utilizan para especificar su ubicación en relación con su ancestro posicionado. El elemento no afecta al flujo normal del documento y se superpone a otros elementos.

**position: relative:** Cuando se establece position: relative en un elemento (como .elemento-2 en este caso), este se posiciona en relación con su posición original en el flujo normal del documento. Las propiedades top, right, bottom y left se utilizan para ajustar su posición en relación con su posición original. A diferencia de position: absolute, el elemento todavía ocupa espacio en el flujo normal del documento, por lo que otros elementos pueden verse afectados por su presencia.


- Uso de z-index para controlar el orden de apilamiento:

La propiedad z-index se utiliza para controlar el orden de apilamiento de elementos posicionados. Un valor más alto en z-index indica que el elemento está más arriba en el orden de apilamiento. En este ejemplo, ambos elementos tienen valores predeterminados de z-index: auto, lo que significa que se apilan en el orden en que aparecen en el HTML. Si se deseas controlar el orden de apilamiento, debes asignar valores de z-index específicos. En este caso al .elemento-1 se le asigno un z-inex de 2 (estará por encima de Elemento-2 ) y al .elemento-2 se le asigno un z-index de 1 (estará detrás de Elemento-1).


- Uso de display para controlar cómo se muestra un elemento:

La propiedad display se utiliza para controlar el tipo de caja que representa un elemento y cómo se comporta en el diseño de la página. En este ejemplo, .elemento-1 tiene display: flex;, lo que convierte a este elemento en un contenedor flexible que afectará a cómo se colocan sus hijos dentro de él. Por otro lado, .elemento-2 tiene display: inline-block;, lo que hace que se comporte como un elemento en línea, pero que permita ajustar su ancho y alto como un bloque. En este caso se añadio un width de 100px y un height de 250px, lo que hizo que la caja cambie en un ancho de 100px y un alto de 250.


En conclusión: **position** controla el posicionamiento, **z-index** controla el orden de apilamiento y **display** controla cómo se muestra un elemento en una página web.









