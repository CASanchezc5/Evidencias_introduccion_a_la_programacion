<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->
# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5 
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame
Utiliza encabezados para títulos en cada elemento `(<h1>...<h6>)`.

Crea una descripción para cada elemento utilizando párrafos `(<p>)`.

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa `<strong>` para resaltar texto importante.
- Utiliza `<br>` para insertar saltos de línea si es necesario.
- Agrega `<span>` para aplicar estilos específicos a porciones de texto.
- Emplea `<i>` para enfatizar o dar énfasis a palabras o frases.
- Utiliza `<u>` para subrayar texto cuando sea necesario.
- Considera el uso de `<div>` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.


## Plantilla Inicial
```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
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

## Semántica y Estructura de la Plantilla
El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

`<!DOCTYPE html>`: Esto define el tipo de documento como HTML5.

`<html>`: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

`<head>`: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque `<style>` para agregar reglas de estilo CSS.

`<title>`: Establece el título de la página en la pestaña del navegador.

`<style>`: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

`<body>`: Aquí se coloca el contenido principal visible de la página.

`<header>`: Sección de encabezado que contiene el título principal y un subtítulo.

`<h1>` y `<h3>`: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

`<section>`: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

`<h2>`: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

`<p>`: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

`<footer>`: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea `<br>` para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

- La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.
- El encabezado (`<header>`) tiene un fondo oscuro, texto blanco y un espacio de relleno.
- Cada sección (`<section>`) tiene un borde, un espacio de relleno y un margen inferior.
- Los encabezados de nivel 1 y 3 están centrados.
- Los encabezados de nivel 2 (`<h2>`) tienen color azul.
- El pie de página (`<footer>`) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.

# Solución 

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
      body {
        font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
          "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
      }

      header {
        background-color: #4b9deb;
        color: rgb(2, 7, 17);
        padding: 20px;
        text-align: center;
        margin-bottom: 5px;
      }

      section {
        border: 2px solid #ddd;
        padding: 20px;
        margin-bottom: 20px;
      }

      h2 {
        color: blue;
      }

      footer {
        background-color: #333;
        color: white;
        padding: 20px;
        text-align: center;
      }
    </style>
  </head>

  <body>
    <header>
      <h1>Etiquetas Multimedia HTML5</h1>
      <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
      <h2>Imágenes</h2>
      <ul>
        <a href="#computador"><li>Computador</li></a>
        <a href="#faro"><li>Faro</li></a>
        <a href="#lobo"><li>Lobo</li></a>
        <a href="#ballena"><li>Ballena</li></a>
      </ul>

      <h3 id="computador">Computador</h3>
      <p>
        Es una máquina electrónica digital programable que ejecuta una serie de
        comandos para procesar los datos de entrada, obteniendo convenientemente
        información que posteriormente se envía a las unidades de salida.
      </p>
      <img src="computadores_escritorio.jpeg" alt="computador" width="500" />
      <a href="https://es.wikipedia.org/wiki/Computadora" target="_blank"
        >Para más información</a
      >

      <h3 id="faro">Faro</h3>
      <p>
        Un faro es una torre de señalización luminosa situada en el litoral
        marítimo o tierra firme, como referencia y aviso costero o aéreo para
        navegantes,siguiendo un código descriptivo que sirve para identificarlo
        denominado luz característica.
      </p>
      <img src="faro.jpg" alt="faro" width="250" />
      <a href="https://es.wikipedia.org/wiki/Faro" target="_blank"
        >Para más información</a
      >

      <h3 id="lobo">Lobo</h3>
      <p>
        El lobo europeo (Canis lupus lupus), también conocido como el lobo
        común, lobo euroasiático o lobo gris, es la subespecie más conocida de
        Canis lupus. Se trata de una subespecie de lobo originaria de Europa y
        de las zonas boscosas y esteparias de la antigua Unión Soviética.
      </p>
      <img src="lobo.png" alt="lobo" width="500" />
      <a href="https://es.wikipedia.org/wiki/Canis_lupus_lupus" target="_blank"
        >Para más información</a
      >

      <h3 id="ballena">Ballena</h3>
      <p>
        Los balénidos (Balaenidae) son una familia de cetáceos misticetos que
        incluye cuatro especies, distribuidas en dos géneros, Balaena y
        Eubalaena. Sin embargo el término ballena es usado en sentido amplio
        para referirse a todos los grandes cetáceos incluidos en el parvorden
        Mysticeti (cetáceos con barbas) como el rorcual azul (Balaenoptera
        musculus) y a varias especies del parvorden Odontoceti (cetáceos
        dentados).
      </p>
      <img src="ballena.jpg" alt="ballena" width="500" />
      <a href="https://es.wikipedia.org/wiki/Balaenidae" target="_blank"
        >Para más información</a
      >
    </section>

    <section>
      <h2>Videos</h2>

      <h3>Caracol</h3>
      <p>
        El término caracol es el nombre común de los moluscos gasterópodos
        provistos de una concha espiral. Hay caracoles marinos (a veces
        denominados caracolas), dulceacuícolas y terrestres. Los caracoles se
        mueven por medio de una serie de contracciones musculares ondulatorias
        que recorren la cara inferior del pie.
      </p>
      <video src="caracol.mp4" controls width="500"></video>

      <h3>Rio</h3>
      <p>
        Un río es una corriente de agua que fluye con continuidad por un cauce
        en la superficie terrestre o bien puede ser subterráneo. Pueden ser
        tanto naturales como artificiales.
      </p>
      <video src="rio.mp4" controls width="500"></video>
    </section>

    <section>
      <h2>Audios</h2>
      <ul>
        <a href="#electronica">
          <li>Musica Electronica</li>
        </a>
        <a href="#jazz">
          <li>Musica Jazz</li>
        </a>
        <a href="#pajaros">
          <li>Pajaros</li>
        </a>
        <a href="#lluvia">
          <li>Lluvia</li>
        </a>
      </ul>

      <h3 id="electronica">Musica Electronica</h3>
      <p>
        Este audio contiene sonidos que hacer referencia una musica electronica.
        La música electrónica es aquel tipo de música que emplea instrumentos
        musicales electrónicos y tecnología musical electrónica para su
        producción e interpretación
      </p>
      <audio src="electronica.mp3" controls></audio>

      <h3 id="jazz">Musica Jazz</h3>
      <p>
        Este audio contiene sonidos que hacer referencia una musica jazz. El
        jazz es un género musical nacido a finales del siglo xix en los Estados
        Unidos, que se expandió de forma global a lo largo del siglo xx. La
        identidad musical del jazz es compleja y no puede ser delimitada con
        facilidad.
      </p>
      <audio src="jazz.mp3" controls></audio>

      <h3 id="pajaros">Pajaros</h3>
      <p>
        Este audio contiene sonidos que hacer referencia al canto de los
        pajaros. Las aves son una clase de animales vertebrados, que regulan su
        temperatura, que caminan, saltan o se mantienen solo sobre las
        extremidades posteriores​, mientras que las extremidades anteriores han
        evolucionado hasta convertirse en alas que, junto con otras
        características anatómicas únicas, les permiten, a la mayor parte de
        ellas, volar, si bien no todas vuelan.
      </p>
      <audio src="pajaros.mp3" controls></audio>

      <h3 id="lluvia">Lluvia</h3>
      <p>
        Este audio contiene sonidos que hacer referencia a la lluvia.La lluvia
        (del lat. pluvĭa) es un fenómeno atmosférico de tipo hidrometeorológico
        que se inicia con la condensación del vapor de agua que forma gotas de
        agua, las cuales pasan a formar las nubes y cae al suelo. El calor
        atmosférico origina el ascenso de las nubes y su enfriamiento, con lo
        cual crece el tamaño de las gotas de agua y su mayor peso las hace
        precipitarse hacia la superficie terrestre, dando origen así a la
        lluvia.
      </p>
      <audio src="lluvia.mp3" controls></audio>
    </section>

    <section>
      <h2>iFrames</h2>

      <h3>Boostrap</h3>
      <p>
        Bootstrap es una biblioteca multiplataforma o conjunto de herramientas
        de código abierto para diseño de sitios y aplicaciones web. Contiene
        plantillas de diseño con tipografía, formularios, botones, cuadros,
        menús de navegación y otros elementos de diseño basado en <u>HTML</u> y
        <u>CSS</u>, así como extensiones de <u>JavaScript</u> adicionales
      </p>
      <iframe
        src="https://getbootstrap.com/docs/5.0/getting-started/introduction/"
        frameborder="0"
        width="500"
        height="300"
      ></iframe>

      <h3>You Tube</h3>
      <p>
        Es un sitio web de origen estadounidense dedicado a compartir videos.
        Presenta una variedad de clips de películas, programas de televisión y
        vídeos musicales, así como contenidos amateur como videoblogs y YouTube
        Gaming. En este caso se muestra el video musical de la cancion
        <strong>"Eclipse de luna"</strong> del artista mexicano
        <i>Aleks Syntek</i>
      </p>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/CdRWz_oQr-g"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
      ></iframe>
    </section>

    <footer>
      Carlos Andrés Sánchez Correa
      <br />
      <br />
      CESDE
      <br />
      <br />
      &copy;2023
    </footer>
  </body>
</html>

```




