# LaCasadePapel
Web creada para informar sobre la serie llamada La Casa de Papel.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Página sobre La Casa de Papel">
    <meta name="author" content="Ángel Hidalgo Morales">
    <title>La Casa de Papel</title> <!--Título que se mostrara en el navegador a la hora de entrar a la web-->
    <link rel="icon" href="icono.png/iconocasadepapel.webp"> <!--Icono mostrado al ver la web en el navegador-->
    <link rel="stylesheet" href="css/styles.css"> 
</head>
<body>
<header> <!--Aquí está todo lo que se mostrara en el encabezado de la página-->
    <h1>La Casa de Papel</h1> <!-- Título inicial de la web-->
    <nav>
    <ul>
        <li><a href="#inicio">Inicio</a></li>  <!--Títulos de diferentes apartados y botones interactivos que te llevan al lugar en el que se enncuentra el título-->
        <li><a href="#tabla">Datos</a></li>
        <li><a href="formulario.html">Formulario</a></li>
    </ul>
</nav>
</header> 

<!-- Apartado de Información -->
<section id="informacion"> <!--Uso section para diferenciar los diferentes apartados de la web-->
    <h2>Información General</h2> <!-- Apartado para Información General-->
    <article> <!--Con article defino un contenido importante para esta web-->
        <h3>Información</h3>
        <p>"La Casa de Papel" es una serie española que narra al principio de la serie el gran atraco a la Fábrica Nacional de Moneda y Timbre, organizado por un misterioso hombre conocido como “El Profesor”. La trama sigue a un grupo de atracadores que adoptan nombres de ciudades para ocultar su identidad mientras ejecutan un plan meticuloso.
            A lo largo de las temporadas este grupo de personas consigue realizar mayores atracos, a la vez que eso ocurre algunos integrantes del grupo no logran salir de los atracos, falleciendo en ellos, y en cada uno de los atracos la situación se va volviendo más tensa y complicada.
        </p>
        <img src="imagenes.jpg/FNMT.webp" alt="Fábrica Nacional de Moneda y Timbre" title="ElAtraco"> <!-- Imagen de la Fabrica Nacional de Moneda y Timbre-->

        <h3>Personajes Principales</h3>
        <ul>
            <li>El Profesor, personaje principal</li> 
            <li>Tokio</li>
            <li>Río</li>
            <li>Nairobi</li>
            <li>Denver</li>
            <li>Berlín</li>
        </ul>
        <img src="imagenes.jpg/Elprofesorimg.webp" alt="Personaje principal" title="ElProfesor">

        <h3>Datos Técnicos</h3>
        <ol>
            <li>Año de estreno: 2017</li>
            <li>Director principal: Álex Pina</li>
            <li>Género: Thriller, Acción</li>
            <li>Número de temporadas: 5</li>
            <li>Plataforma: Netflix</li>
        </ol>
        
        <p>Más información: <a href="https://www.netflix.com" target="_blank">Netflix</a> | <a href="https://www.imdb.com/title/tt6468322/" target="_blank">IMDb</a></p> <!--Enlaces a otras páginas web-->



        <h3>Multimedia</h3> <!--Apartado para Multimedia-->
        <h4>Tráiler</h4> <!--Video Trailer de la serie-->
        <video controls width="600">
            <source src="audio.mp3/Lacasadepapel.mp4" type="video/mp4">
        </video>

        <h4>Audio - Canción más característica de la serie</h4><!--Audio de una canción de la serie-->
        <audio controls preload="auto">
            <source src="audio.mp3/ytmp3free.cc_bella-ciao-la-casa-de-papel-youtubemp3free.org.mp3" type="audio/mpeg">
        </audio>
    </article>
</section>


<section id="tabla"> <!-- Apartado de la Tabla -->
    <h2>Reparto Detallado</h2>
    <table> <!--Inicio de la creación de una tabla-->
        <thead> <!--Lo uso para definir el encabezado de la tabla-->
            <tr>
                <th>Actor</th>
                <th>Personaje</th>
                <th>Temporadas</th>
                <th>Nacionalidad</th>
                <th>Ocupación</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Álvaro Morte</td>
                <td>El Profesor</td>
                <td>1 - 5</td>
                <td>Español</td>
                <td>Planificador/Ingeniero</td>
            </tr>
            <tr>
                <td>Úrsula Corberó</td>
                <td>Tokio</td>
                <td>1 - 5</td>
                <td>Española</td>
                <td>Asaltante</td>
            </tr>
            <tr>
                <td>Pedro Alonso</td>
                <td>Berlín</td>
                <td>1 - 5</td>
                <td>Español</td>
                <td>Asaltante / Líder</td>
            </tr>
            <tr>
                <td>Alba Flores</td>
                <td>Nairobi</td>
                <td>1 - 5</td>
                <td>Española</td>
                <td>Asaltante / Falsificadora</td>
            </tr>
            <tr>
                <td>Jaime Lorente</td>
                <td>Denver</td>
                <td>1 - 5</td>
                <td>Español</td>
                <td>Asaltante</td>
            </tr>
            <tr>
                <td>Miguel Herrán</td>
                <td>Río</td>
                <td>1 - 5</td>
                <td>Español</td>
                <td>Asaltante / Experto en tecnología</td>
            </tr>
        </tbody>
    </table>
</section>

<div class="formulario"> <!--Apartado del Formulario-->
   Puedes completar mi formulario aquí:
    <a href="formulario.html">Ir al Formulario</a> <!--Enlace que te lleva al formulario-->
</div>

<footer> <!--Aquí saldrá lo que se muestre en el pie de página de la web-->
    <p>Página de información sobre La Casa de Papel</p>
</footer>

</body>
</html>
