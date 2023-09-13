<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->
# Actividad: Creando mi primer sitio web 
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto


## index.html
![Index](/img/index.png)

## about.html
![About](/img/about.png)

## contact.html
![Contact](/img/contact.png)

# Solución 
## Index


```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Carlos Andrés Sánchez C">
    <link rel="shortcut icon" href="img/icono1.ico" type="image/x-icon">
    <title>Inicio</title>
  </head>
  <body>
    <header>
      <h1>Mi Primer Sitio Web</h1>
      <figure>
        <img src="img/icono.png"  alt="desarrollo web">
      </figure>
    </header>
    <hr>

    <nav>
      <a href="about.html">Acerca de</a>
      <a href="contact.html">Contacto</a>
    </nav>

    <figure>
      <img src="img/designer-0.svg" alt="desarrollo web">
    </figure>
    <main>
      <articule>
        <h2>Presentación</h2>
        <p>
          Bienvenido a este sitio web, en el cual encontraras cosas muy
          interesantes sobre desarrollo de software
        </p>
        <section>
          <p>
            <u><b>¿Que es una Web?:</b></u> La <i>World Wide Web (WWW)</i>,
            también conocida como la Web o el Internet, es un sistema de
            hipertexto público que está disponible para cualquiera con acceso a
            una computadora y una conexión a Internet. La Web está formada por
            millones de sitios web, que son páginas web que contienen
            información y recursos. Los sitios web están interconectados a
            través de enlaces de hipertexto, lo que permite a los usuarios
            navegar de un sitio a otro.
          </p>
        </section>
        <section>
          <p>
            <u><b>¿De qué trata HTML?:</b></u> <strong>HTML5</strong> es la
            quinta versión del lenguaje de marcado de hipertexto (HTML), que se
            utiliza para estructurar y presentar contenido en la web. HTML es el
            lenguaje fundamental utilizado para crear páginas web y definir su
            estructura y contenido. HTML5 trajo consigo una serie de mejoras y
            nuevas características en comparación con las versiones anteriores
            de HTML, lo que lo convirtió en un estándar ampliamente adoptado
            para el desarrollo de sitios web y aplicaciones web.
            las etiquetas de encabezado de HTML se escriben de la siguiente manera &lt;h1&gt;&lt;/h1&gt;
          </p>
        </section>
        <section>
          <p>
            <u><b>¿De qué trata CSS?:</b></u> Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Consectetur eveniet hic ipsum possimus
            beatae quibusdam velit id quia repellat tempora natus, adipisci,
            iste at voluptatum sit aliquam maiores. Doloremque excepturi
            cupiditate consequuntur. Voluptatem mollitia sapiente distinctio
            impedit voluptates debitis fuga, perspiciatis recusandae. Deserunt
            aliquam voluptate vel nesciunt laboriosam alias deleniti.
          </p>
        </section>
        <section>
          <p>
            <u><b>¿De qué trata JavaScript?:</b></u
            >Lorem ipsum, dolor sit amet consectetur adipisicing elit.
            Architecto facere sed rem itaque quibusdam. Quibusdam ipsam fuga
            eum, at ab officiis explicabo hic voluptatibus dolorum ex
            cupiditate, voluptate dignissimos optio laborum odio tenetur nulla
            id, odit itaque? Adipisci aliquid a dolorum magnam aut, soluta
            laboriosam, debitis voluptatum molestias nemo placeat.
          </p>
        </section>
      </articule>
    </main>

    <footer>
      <ul>
        <li>
          <a href="http://www.facebook.com" target="_blank">Ir a Facebook</a>
        </li>
        <li>
          <a href="http://www.instagram.com" target="_blank">Ir a Instagram</a>
        </li>
        <li>
          <a href="http://www.twitter.com" target="_blank">Ir a X</a>
        </li>
      </ul>

      <p>Copyright &copy;2023 - Carlos A. Sánchez</p>
    </footer>
  </body>
</html>

```


## About

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Carlos Andrés Sánchez C">
    <title>Acerca</title>
  </head>
  <body>
    <main>
      <header>
        <h1>Acerca de Nosotros</h1>
      </header>
      <hr>
      <div>
        <h2>Historia</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste nisi
          tenetur officia, necessitatibus reiciendis quod qui rerum, similique
          provident eos quas? Neque, animi? Reiciendis, repellendus similique.
          Omnis ipsam aut amet. Corporis, doloremque. Quos, impedit! Sit quas
          eveniet explicabo enim voluptatem quasi nostrum aspernatur consectetur
          eligendi doloribus rem eius quia, facilis reiciendis nam repellendus
          soluta perspiciatis vel aperiam, voluptates dolores corporis?
          Asperiores sequi quidem voluptates iste blanditiis omnis labore
          architecto consectetur, facere repellat assumenda ex nam fuga vel
          repellendus delectus minus hic nihil deserunt cum. Libero rerum nemo
          saepe optio quibusdam. Laboriosam vitae dolorem quod aut maxime,
          deserunt minus iure maiores suscipit libero ab tempore vero fugiat
          itaque eos officiis accusantium cum accusamus exercitationem error
          architecto. Architecto deserunt ex quisquam! Doloribus! Adipisci
          explicabo ducimus, itaque quidem exercitationem obcaecati numquam
          tempore esse. Quia repellendus atque debitis fugit alias dolore illo
          quae nobis quas cumque a aliquam, temporibus eius, harum, minus
          delectus numquam. Quisquam ipsum fugiat aliquid veniam saepe modi
          aspernatur optio qui eum ut voluptate est, molestiae nulla impedit
          ipsam, excepturi libero, et repellendus autem nam accusantium culpa
          consectetur quasi? Ullam, maiores. Consequuntur quam velit
          voluptatibus facere dignissimos, esse rem reiciendis veniam nisi amet
          tenetur provident cupiditate dolorem harum, vitae explicabo et iusto,
          nostrum quisquam quia nemo necessitatibus corrupti ad. Voluptate,
          odio. Cumque magni placeat voluptates veniam dolor esse vitae,
          voluptas laudantium optio, at debitis commodi. Est, adipisci sequi
          obcaecati minus earum pariatur et commodi autem culpa in,
          exercitationem recusandae, sit distinctio? Iste hic vitae, cumque,
          deleniti ad molestias fugit voluptatum perferendis harum dolore autem
          ab eveniet iusto quibusdam minima architecto eos quos ullam accusamus
          iure libero omnis vel nihil non. Possimus! Non repellendus quos dicta
          at esse saepe perspiciatis enim voluptatibus quas consequatur suscipit
          accusantium, cum atque rem qui! Ex nostrum enim culpa veniam dolorum
          mollitia reprehenderit, beatae aut eius nam. Similique totam nam
          inventore ex id nobis placeat, eaque eveniet consequatur perferendis
          molestiae exercitationem ab itaque deleniti illum, autem quis, qui
          nisi quo voluptas! Commodi, expedita. Ratione rem vero quas!
          Repudiandae commodi deleniti optio, architecto, fuga iusto deserunt
          ipsam libero voluptatum quam sint et eaque iste nesciunt, esse
          temporibus. Animi tempore aliquam ipsa voluptate et. Exercitationem
          officia ut distinctio dolore? Temporibus molestias aspernatur saepe
          sequi provident modi, similique atque quis aperiam iure dignissimos
          ipsam dicta, voluptatem reiciendis cum vel expedita esse officiis
          error adipisci! Adipisci inventore assumenda soluta eum placeat.
          Commodi quae nisi dolores in adipisci libero perspiciatis sed eveniet
          natus architecto laboriosam, dignissimos, quos id totam ut tenetur
          ipsum dicta exercitationem. Hic voluptatum eaque, odio id recusandae
          corrupti asperiores. Corrupti voluptatibus asperiores, maiores
          suscipit et provident consequuntur magni sequi, sapiente doloremque
          harum nobis perferendis aperiam ipsam? Explicabo delectus laborum iste
          harum necessitatibus dolores non sequi obcaecati, accusamus tempora
          doloribus? Veniam ipsa corporis ut nam, nobis, necessitatibus officia
          tempore quidem et ea incidunt adipisci quis delectus assumenda totam.
          Doloribus accusamus ad architecto unde praesentium beatae iste minima
          magnam dolor tempore. Odio fugiat ipsum laboriosam quo soluta? Nemo
          eum culpa sequi ipsa eaque, commodi doloribus velit, deserunt,
          voluptate dolor voluptas earum! Similique iusto earum maxime optio
          accusamus fuga expedita neque. Accusamus. Delectus accusamus
          architecto doloremque ad quasi reiciendis beatae neque saepe dicta
          suscipit qui quo maxime aliquid, quae dolorem odio. Eligendi aperiam
          perspiciatis consectetur, error perferendis sapiente. Officiis
          aspernatur voluptate inventore. Fugit, debitis aliquam. Incidunt
          quaerat tempore quod aspernatur amet officiis inventore? Dolorem
          recusandae impedit, culpa sequi saepe error ut vel natus officiis
          doloremque minima animi eum. Assumenda voluptate ad id? Fugit tenetur
          cumque odit doloremque excepturi dolor culpa tempora blanditiis
          aspernatur ea! Non quaerat atque aliquam velit aliquid illum omnis
          vitae nisi porro, fugit, pariatur est magnam exercitationem voluptatem
          culpa.
        </p>
      </div>

      <div>
        <h2>Mision y Visión</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum,
          repudiandae sequi, dolor maxime veniam consequuntur pariatur esse
          excepturi inventore, perferendis odit quidem? Temporibus quibusdam
          placeat vero harum iusto rem sapiente velit atque blanditiis saepe cum
          impedit aspernatur alias fugit, beatae ea, quas veritatis debitis!
          Hic, nulla adipisci neque nostrum placeat quibusdam possimus laborum
          necessitatibus. Est incidunt iste architecto tenetur vero aliquid
          necessitatibus, nisi asperiores, vitae laudantium deleniti beatae
          voluptas velit quas magnam voluptatum, nulla debitis. Nisi eius
          doloremque ea dolore impedit laudantium, suscipit autem ex! Fugiat,
          quia, beatae tempora amet aliquam laudantium et ea delectus pariatur
          quas sint distinctio provident?
        </p>
      </div>

      <img src="img/user-avatar-9.svg" alt="nosotros">

      <button><a href="index.html">Ir a inicio</a></button>

      <footer>
     
        <ul>
          <li>
            <a href="http://www.facebook.com" target="_blank">Ir a Facebook</a>
          </li>
          <li>
            <a href="http://www.instagram.com" target="_blank">Ir a Instagram</a>
          </li>
          <li>
            <a href="http://www.twitter.com" target="_blank">Ir a X</a>
          </li>
        </ul>
  
        <p>Copyright 2023 - Carlos A. Sánchez</p>
  
      </footer>
    </main>
  </body>
</html>

```


## Contact

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Carlos Andrés Sánchez C">
    <title>Contacto</title>
</head>
<body>
    <header>
        <h1>Contactenos</h1>
    </header>
    <hr>
    <img src="img/entrepreneurs-e.svg" alt="contacto">

    <form action="">
        <label for="nombre">Nombres</label>
        <input type="text" name="nombres" id="nombre" placeholder="Escriba su nombre" autofocus required><br>
        <label for="apellidos">Apellidos</label>
        <input type="text" name="apellidos" id="apellido" placeholder="Escriba sus apellidos" required><br><br>

        <label for="email">Email</label>
        <input type="email" name="correo" id="email" placeholder="Escriba su correo" required><br><br>

        <label for="tel">Telefono</label>
        <input type="number" name="telefono" id="tel" maxlength="20"><br><br>

        <label for="edad">Edad</label>
        <select name="edad" id="">
            <option value="Menores de 15">Menores de 15</option>
            <option value="De 15 - 18">De 15 - 18</option>
            <option value="De 19 - 30">De 19 - 30</option>
            <option value="De 31 - 40">De 31 - 40</option>
            <option value="De 41 - 50">De 41 - 50</option>
            <option value="Mayores de 50">Mayores de 50</option>
        </select><br><br>

        <label for="genero">Genero</label>
        <input type="radio" name="gen" id="genero" value="Masculino" checked >Masculino
        <input type="radio" name="gen" id="genero" value="Femenino">Femenino
        <input type="radio" name="gen" id="genero" value="Otro">Otro<br><br>   <!-- el name me sirve para poder escoger uno de los 3 (pero tienen que ir con el mismo nombre) y no se me escojan los 3 al mismo tiempo -->

        <label for="coment">Comentario</label>
        <textarea name="comentario" id="coment" cols="30" rows="10"></textarea>

        <button type="submit" value="Enviar">Enviar</button>

    </form>

    <button><a href="index.html">Ir a inicio</a></button>

    <footer>
     
      <ul>
        <li>
          <a href="http://www.facebook.com" target="_blank">Ir a Facebook</a>
        </li>
        <li>
          <a href="http://www.instagram.com" target="_blank">Ir a Instagram</a>
        </li>
        <li>
          <a href="http://www.twitter.com" target="_blank">Ir a X</a>
        </li>
      </ul>

      <p>Copyright 2023 - Carlos A. Sánchez</p>

    </footer>


</body>
</html>
```






