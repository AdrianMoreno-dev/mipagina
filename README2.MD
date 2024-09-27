<!-- <!DOCTYPE html> : indica al nevegador que este es un documento HTML5.  -->
<!DOCTYPE html>
<!-- <html lang="en"> La etiqueta raiz de un documento HTML. el atributo lang especifica el idioma del contenido -->
<html lang="es">
<!--<head> contiene metadatos sobre el documento, como el titulo y la configuracion de caracteres  -->
<head>
    <!-- <meta charset="UTF-8"> : define la codificacion de caracteres utilizada en el documento  -->
    <meta charset="UTF-8">
    <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0">: ayuda a controlar el diseño en dispositivos moviles -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <title>: define el titulo de la pag que aprece en la pestaña del navegador -->
    <title>Primera pagina web gruopo 9</title>
</head>
<!-- <body>: contiene el contenido visible de la pagina web -->
<body>
    <!-- <header> : Seccion que agrupa la parte superior de la pagina, incluye el titulo y la navegacion -->
    <header>
            <!-- h1 Se utiliza para el titulo principal de la pag. Debe ser unicio por pagina y representar el tema central del contenido -->
        <h1>Bienvenidos a Mi Pagina Web</h1>
        <!-- nav: seccion que contiene enlaces de navegacion -->
        <nav>
            <!-- <ul> : crea una lista no ordenada. <li> define cada elemento de la lista -->
            <ul>
                <!--a href= crea un enlace. al atributo href indica la direccion a la que se dirige el enlace -->
                <li><a href="https://www.google.com/" target="_blank" rel="noopener noreferrer">Sobre mi</a></li>
                
                <li><a href="contacto.html" target="_blank" rel="noopener noreferrer">Contacto</a></li>
                <li><a href="paginas/informacion.html" target="_blank" rel="noopener noreferrer">informacion</a></li>
            </ul>
        </nav>
    </header>

<!-- section: define secciones tematicas en el contenido -->
    <section>
            <h2>Sobre Mi</h2>
            <!-- <p> defice un parrafo de texto -->
            <p>Hola, Soy un programador FullStack</p>
            <!-- Aqui se agregara un articulo -->
            <article>
                <h3>Mi trayectoria</h3>
                <p>Desde pequeño he estado interesado en la tecnologia y la programacion</p>
            </article>

            <div>
                <h3>Intereses</h3>
                <ul>
                    <li>Programacion</li>
                    <li>Entreno</li>
                    <li>Familia</li>
                </ul>
            </div>
    </section>

    <section>
        <h2>Contacto</h2>
        <p>Puedes contactarme a traves de: <a href="mailto:adrianmoreno74@gmail.com">mi correo</a></p>
    </section>
    <section>
        <h2>Mis lenguajes de programacion</h2>
        <!--<ol>: Crea una lista ordenada -->
        <ol>
            <li>HTML</li>
            <li>css</li>
            <li>JavaScript</li>
        </ol>


    </section>

<!-- <footer>: Seccion que contiene informacion depie de pagina, como derechos de autor -->
    <footer>
        <p>&COPY; 2024 Mi pagina web. Todos los derechos reservados.</p>
    </footer>
</body>
</html>