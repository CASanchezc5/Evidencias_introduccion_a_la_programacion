<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
# Actividad: Crear una tabla HTML con información sobre productos. 
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

![Tabla](/img/tabla.png)


# Solución 

```html
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tablas</title>

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
  <h1>Tablas</h1>
  <h2>Consolas de Videojuegos</h2>

  <table border="1">
    <thead>
      <tr>
        <th>Codigo</th><!--celda A-->
        <th>Nombre</th><!--celda B-->
        <th>Descripción</th><!--celda C-->
        <th>Precio</th><!--celda D-->
        <th>Stock</th><!--celda E-->
        <th colspan="2">Fecha de creación</th><!--celda F-->
      </tr>
    </thead>

    <tbody>
      <tr><!--FILA NUMERO 1-->
        <td rowspan="2">VC001</td>
        <td rowspan="2">Xbox360</td>
        <td>Es la segunda videoconsola de sobremesa de la marca Xbox producida
          por Microsoft. Como principales características técnicas, están su
          unidad central de procesamiento basado en un IBM PowerPC y su unidad
          de procesamiento gráfico que soporta la tecnología de Shaders
          Unificados.</td>
        <td rowspan="2">700.000 COP</td>
        <td rowspan="2" colspan="2">20</td>
        <td rowspan="2">2023-08-24</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: negro y blanco</td>
      </tr>

      <tr><!--FILA NUMERO 2-->
        <td rowspan="2">VC002</td>
        <td rowspan="2">Play Station 5</td>
        <td>Es la quinta consola de videojuegos de sobremesa desarrollada por la
          empresa Sony Interactive Entertainment. Las principales
          características de hardware de la PlayStation 5 incluyen una unidad
          de estado sólido personalizada para transmisión de datos de alta
          velocidad para permitir mejoras significativas en el rendimiento del
          almacenamiento, una GPU AMD capaz de mostrar una resolución de 4K de
          hasta 120 cuadros por segundo, trazado de rayos acelerado por
          hardware para realismo, iluminación y reflejos y el motor Tempest
          que permite efectos de audio 3D acelerados por hardware.</td>
        <td rowspan="2">2.800.000 COP</td>
        <td rowspan="2" colspan="2">30</td>
        <td rowspan="2">2023-07-16</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: negro y blanco</td>
      </tr>

      <tr><!--FILA NUMERO 3-->
        <td rowspan="2">VC003</td>
        <td rowspan="2">Nintendo Switch</td>
        <td>Es una consola de videojuegos desarrollada por Nintendo. Se
          considera a Switch una consola híbrida. Se puede utilizar como
          consola de sobremesa con la unidad principal insertada en una
          estación de acoplamiento para conectarla con un televisor.
          Alternativamente, puede ser extraída de la base y utilizada de forma
          similar a una tableta a través de su pantalla táctil o colocada
          sobre una superficie gracias a su soporte plástico integrado siendo
          así visible por varios jugadores.</td>
        <td rowspan="2">1.300.000 COP</td>
        <td rowspan="2" colspan="2">25</td>
        <td rowspan="2">2023-05-30</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: azul, amarillo, gris, turquesa y coral</td>
      </tr>

      <tr><!--FILA NUMERO 4-->
        <td rowspan="2">VC004</td>
        <td rowspan="2">Xbox Series X|S</td>
        <td>Xbox Series X sería cuatro veces más potente que Xbox One X; Microsoft también ha promovido el "modo
          automático de baja latencia" y la "entrada de latencia dinámica" para mejorar la capacidad de respuesta.
          Algunas de sus características incluyen la incorporación de una CPU de 8 núcleos y 16 hilos de ejecución a 3,8
          GHz de la arquitectura Zen 2 de AMD y una GPU de 52 unidades de cómputo de la arquitectura de gráficos RDNA 2,
          que ofrece hasta 12 teraflops de potencia.</td>
        <td rowspan="2">2.300.000 COP</td>
        <td rowspan="2" colspan="2">50</td>
        <td rowspan="2">2023-06-15</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: blanco y negro; solo en negro para la X</td>
      </tr>

      <tr><!--FILA NUMERO 5-->
        <td rowspan="2">VC005</td>
        <td rowspan="2">Play Station 3</td>
        <td>Es la tercera videoconsola descontinuada del modelo PlayStation de Sony Computer Entertainment.
          características importantes de la consola eran sus capacidades sólidas de multimedia,la conectividad con la
          PlayStation Portable ​(y más con la actualización 4.0 con su sucesora, PlayStation Vita) y su principal
          formato de disco óptico de alta definición, Blu-ray Disc, como su principal medio de almacenamiento.</td>
        <td rowspan="2">2.500.000 COP</td>
        <td rowspan="2" colspan="2">50</td>
        <td rowspan="2">2023-06-20</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: negro, azul y rojo</td>
      </tr>

      <tr><!--FILA NUMERO 6-->
        <td rowspan="2">VC006</td>
        <td rowspan="2">Nintendo Wii U</td>
        <td>Es la séptima consola de sobremesa creada por Nintendo y directa sucesora de Wii. Wii U es la primera
          consola de Nintendo en producir gráficos en alta definición hasta una resolución de 1080p. Incluyó un nuevo
          mando que incorporó una pantalla táctil que recibía señal en calidad 480p de la consola, lo que permitió
          seguir jugando incluso cuando el televisor estaba apagado. A este nuevo mando se le ha denominado: Wii U
          GamePad.</td>
        <td rowspan="2">800.000 COP</td>
        <td rowspan="2" colspan="2">20</td>
        <td rowspan="2">2023-08-18</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: blanco y negro</td>
      </tr>

      <tr><!--FILA NUMERO 7-->
        <td rowspan="2">VC007</td>
        <td rowspan="2">Play Station 4</td>
        <td>Es la cuarta videoconsola del modelo PlayStation. El peso de la consola rondaría los 2,8 kg y la caja en
          total serían unos 4 kg​ La tecnología de PlayStation 4 sería relativamente similar al hardware que se
          encuentra en los ordenadores personales.En cierto momento del desarrollo se contempló que Nvidia fuese quien
          fabricara la unidad gráfica para PS4 pero según declaraciones de Tony Tamasi, vicepresidente de contenido y
          tecnología de Nvidia, esto no le convendría a la compañía por el impacto que tendría en sus posibilidades en
          otros mercados.</td>
        <td rowspan="2">1.100.000 COP</td>
        <td rowspan="2" colspan="2">25</td>
        <td rowspan="2">2023-07-30</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: blanco, negro, azul y rojo</td>
      </tr>

      <tr><!--FILA NUMERO 8-->
        <td rowspan="2">VC008</td>
        <td rowspan="2">Play Station Portable PSP</td>
        <td>Es una videoconsola portátil de la multinacional de origen japonés, y la cuarta consola de Sony en ser
          diseñada por Ken Kutaragi, PSP servía para videojuegos, conectarse a internet y reproducir y ver multimedia.
          Se trata de la primera consola portátil a nivel mundial de Sony y la segunda lanzada en Japón. La consola PSP
          cambió la tendencia de hacer cada vez aparatos portátiles más pequeños, sacando al mercado una consola con una
          pantalla mayor y convirtiéndose en la segunda consola portátil con un D stick (después de la Neo Geo Pocket).
        </td>
        <td rowspan="2">600.000 COP</td>
        <td rowspan="2" colspan="2">10</td>
        <td rowspan="2">2023-08-23</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: blanco, negro, plateado(silver), azul, amarillo, verde y rojo</td>
      </tr>

      <tr><!--FILA NUMERO 9-->
        <td rowspan="2">VC009</td>
        <td rowspan="2">Game Boy Advance</td>
        <td>Es una consola de videojuegos de la compañía Nintendo. Cuenta con un procesador ARM propio de 32 bits a
          16,78 MHz (ARM7TDMI), basado en la arquitectura RISC, con una potencia suficiente para permitir el desarrollo
          de juegos utilizando el lenguaje de programación C. El microprocesador ARM es capaz de ejecutar tanto un juego
          de instrucciones con un tamaño de instrucción de 32 bits, como un juego de instrucciones llamado "Thumb" de un
          tamaño de 16 bits (pero igualmente, de 32 bits). Esta consola, además, lleva el procesador CISC de 8 bits que
          tiene la Game Boy clásica y la Game Boy color (el LR35902). Este procesador lo usa para dar soporte al
          software de estas dos consolas anteriores.</td>
        <td rowspan="2">800.000 COP</td>
        <td rowspan="2" colspan="2">10</td>
        <td rowspan="2">2023-08-20</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: negro, plateado(silver), azul, morado, amarillo, verde, rosado y rojo</td>
      </tr>

      <tr><!--FILA NUMERO 10-->
        <td rowspan="2">VC0010</td>
        <td rowspan="2">Sega Saturn</td>
        <td>Es la cuarta videoconsola de sobremesa producida por Sega. una doble CPU con dos núcleos Hitachi SH-2 para
          manejar gráficos tridimensionales. El sistema tiene una biblioteca con más de 1000 juegos desarrollados por
          Sega y terceras compañías, todos ellos publicados en formato CD-ROM. La mayoría se editaron solo en el mercado
          japonés. Además incorporaba un cargador de cartucho que permitía ampliar la memoria RAM para ciertos títulos.
        </td>
        <td rowspan="2">900.000 COP</td>
        <td rowspan="2" colspan="2">10</td>
        <td rowspan="2">2023-07-05</td>
      </tr>
      <tr>
        <td>Esta disponible en colores: negro, blanco y gris</td>
      </tr>

    </tbody>
  </table>


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





