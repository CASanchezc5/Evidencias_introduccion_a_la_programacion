<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
# Actividad: Diseñar un formulario de pedido de un producto 
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
    - Nombre del producto
    - Cantidad
    - Precio unitario
    - Precio total
    - Dirección de envío
    - Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
    - Método de pago
    - Fecha de entrega
    - Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.


# Solución 

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formularios</title>
    <style>
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>
    <form action="">
        <header>
            <h1>Formulario para pedido de un Producto</h1>
        </header>

        <div>
            <label for="idproducto">*Nombre del Producto</label>
            <input type="text" name="producto" id="idproducto" placeholder="Ingrese el nombre del producto" size="50"
                autofocus required>
        </div>
        <br>
        <div>
            <label for="idcantidad">*Cantidad</label>
            <input type="number" name="cantidad" id="idcantidad" placeholder="Ingrese la cantidad a pedir" required>
        </div>
        <br>
        <div>
            <label for="idpreciou">Precio Unitario ($)</label>
            <input type="number" name="preciou" id="idpreciou" required>
        </div>
        <br>
        <div>
            <label for="idpreciot">Precio Total ($)</label>
            <input type="number" name="preciot" id="idpreciot">
        </div>
        <br>
        <div>
            <label for="iddirecenv">*Dirección de Envío</label>
            <input type="text" name="direcenvio" id="iddirecenv" required>
        </div>
        <br><br>
        <div>
            <h2>Información del Contacto</h2>
            <div>
                <label for="idnombre">*Nombre</label>
                <input type="text" name="nombre" id="idnombre" placeholder="Ingrese su nombre" required>
            </div>
            <br>
            <div>
                <label for="idcorreo">*Correo Electronico (email)</label>
                <input type="email" name="correo" id="idcorreo" placeholder="Ingrese su correo electronico" size="40"
                    required>
            </div>
            <br>
            <div>
                <label for="idtelefono">Telefono</label>
                <input type="tel" name="telefono" id="idtelefono" placeholder="Ingrese su número telefonico"
                    minlength="10" size="25">
            </div>
        </div>
        <br><br>
        <div>
            <h2>Otra Información</h2>
            <div>
                <label for="idmetpago">Método de Pago</label>
                <select name="metpago" id="idmetpago" required>
                    <option value="efectivo" selected>Efectivo</option>
                    <option value="credito">Targeta de Credito</option>
                    <option value="debito">Targeta Debito</option>
                </select>
            </div>
            <br>
            <div>
                <label for="idfecha">Fecha de Entrega</label>
                <input type="date" name="fecha" id="idfecha">
            </div>
            <br>
            <div>
                <label for="idcomentario">Comentario</label>
                <textarea name="comentario" id="idcomentario" cols="30" rows="10" minlength="50"
                    maxlength="100"></textarea>
            </div>
        </div>
        <br>
        <div>
            <input type="submit" value="Enviar">
            <button type="reset">Borrar</button>
        </div>

    </form>

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





