# Trabajo-parcial-practica-profesional
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dinosaurios de Argentina</title>
</head>
<body>

    <h1>Dinosaurios de Argentina</h1>

    <section>
        <h2>Introducción</h2>
        <p>Argentina es uno de los países más importantes en el estudio de los dinosaurios debido a la gran cantidad de fósiles encontrados en su territorio.</p>
        <p>Estos descubrimientos han aportado información valiosa sobre la diversidad y evolución de estos animales prehistóricos.</p>
    </section>

    <section>
        <h2>Especies destacadas</h2>
        <p>Entre los dinosaurios más conocidos encontrados en Argentina están el Giganotosaurus, uno de los mayores carnívoros terrestres, y el Argentinosaurus, uno de los dinosaurios más grandes que se conocen.</p>
        <p>Ambos ejemplares representan un patrimonio paleontológico único para el país y el mundo.</p>
    </section>

    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/Giganotosaurus_BW.jpg" alt="Dibujo del Giganotosaurus" width="400">

    <p>Para más información sobre los dinosaurios argentinos puedes visitar 
        <a href="https://es.wikipedia.org/wiki/Dinosaurios_de_Argentina" target="_blank">Wikipedia - Dinosaurios de Argentina</a> 
        o nuestra 
        <a href="#contacto">sección de contacto</a>.
    </p>

    <h3>Tipos de dinosaurios encontrados:</h3>
    <ul>
        <li>Terópodos</li>
        <li>Saurópodos</li>
        <li>Ornitópodos</li>
    </ul>

    <h3>Investigaciones recientes:</h3>
    <ol>
        <li>Descubrimiento del Giganotosaurus en la Patagonia.</li>
        <li>Estudios sobre Argentinosaurus y su tamaño.</li>
        <li>Análisis del ecosistema cretácico argentino.</li>
    </ol>

    <form action="#" method="post">
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre" required><br><br>

        ¿Cuál es tu dinosaurio favorito?<br>
        <input type="radio" id="giga" name="dino_fav" value="Giganotosaurus" required>
        <label for="giga">Giganotosaurus</label><br>
        <input type="radio" id="argen" name="dino_fav" value="Argentinosaurus">
        <label for="argen">Argentinosaurus</label><br><br>

        ¿Qué características te interesan? (puede elegir varias)<br>
        <input type="checkbox" id="tamano" name="caracteristicas" value="Tamaño">
        <label for="tamano">Tamaño</label><br>
        <input type="checkbox" id="habitat" name="caracteristicas" value="Hábitat">
        <label for="habitat">Hábitat</label><br>
        <input type="checkbox" id="alimentacion" name="caracteristicas" value="Alimentación">
        <label for="alimentacion">Alimentación</label><br><br>

        <button type="submit">Enviar</button>
    </form>

    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Argentinosaurus_dinosaur.png" alt="Ilustración del Argentinosaurus" width="400">
        <figcaption>Ilustración artística del Argentinosaurus, uno de los dinosaurios más grandes del mundo.</figcaption>
    </figure>

    <footer>
        <p>&copy; 2025 Dinosaurios Argentina. Visita nuestro 
            <a href="#contacto">contacto</a>.
        </p>
    </footer>

</body>
</html>
```
