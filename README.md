# Project-Js es un proyecto en el cual convergen diferentes funcionalidades javascritp, uso de API´s, responsive design, responsable responsive<!DOCTYPE html>
<html lang="en" data-dark>

<head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Ejercicios del DOM</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/hamburgers/1.1.3/hamburgers.min.css">
        <link rel="stylesheet" href="./css/dom-ejercicios.css">
</head>

<body data-dark>
        <header class="header">
                <h1>
                        Ejercicios del DOM
                </h1>
        </header>
        <button class="panel-btn hamburger hamburger--elastic" type="button">
                <span class="hamburger-box">
                        <span class="hamburger-inner"></span>
                </span>
        </button>
        <aside class="panel">
                <nav class="menu">
                        <a href="#seccion1" data-scroll-spy>Reloj Digital y Alarma Sonora</a>
                        <a href="#seccion2" data-scroll-spy>Eventos del teclado</a>
                        <a href="#seccion3" data-scroll-spy>Cuenta Regresiva</a>
                        <a href="#seccion4" data-scroll-spy>Responsive con JavaScript</a>
                        <a href="#seccion5" data-scroll-spy>Responsive Tester</a>
                        <a href="#seccion6" data-scroll-spy>Detección de Dispositivos (User Agent)</a>
                        <a href="#seccion7" data-scroll-spy>Detección de la Conexión</a>
                        <a href="#seccion8" data-scroll-spy>Detección de la Cámara web</a>
                        <a href="#seccion9" data-scroll-spy>Geolocalización</a>
                        <a href="#seccion10" data-scroll-spy>Filtros de búsquedas</a>
                        <a href="#seccion11" data-scroll-spy>Sorteo Digital</a>
                        <a href="#seccion12" data-scroll-spy>Responsive Slider</a>
                        <a href="#seccion13" data-scroll-spy>Video Inteligente</a>
                        <a href="#seccion14" data-scroll-spy>Validaciónes de Formulario</a>
                        <a href="#seccion15" data-scroll-spy>Sección 15</a>
                </nav>
        </aside>
        <main>
                <section id="seccion1" class="section" data-scroll-spy>
                        <h2>Reloj Digital y Alarma Sonora</h2>
                        <div id="reloj"></div>
                        <div>
                                <button id="activar-reloj">Iniciar Reloj</button>
                                <button id="desactivar-reloj">Detener Reloj</button>
                                <button id="activar-alarma">Iniciar Alarma</button>
                                <button id="desactivar-alarma">Detener Alarma</button>
                        </div>
                </section>
                <section id="seccion2" class="section" data-scroll-spy>
                        <h2>Eventos del teclado</h2>
                        <article class="stage">
                                <div class="ball"></div>
                        </article>
                </section>
                <section id="seccion3" class="section" data-scroll-spy>
                        <h2>Cuenta Regresiva</h2>
                        <div id="countdown"></div>
                </section>
                <section id="seccion4" class="section" data-scroll-spy>
                        <h2>Responsive con JavaScript</h2>
                        <div id="youtube"></div>
                        <div id="gmaps"></div>
                </section>
                <section id="seccion5" class="section" data-scroll-spy>
                        <h2>Responsive Tester</h2>
                        <form id="responsive-tester">
                                <input name="direccion" type="url" placeholder="URL" required>
                                <br>
                                <input name="ancho" type="text" placeholder="Ancho" required>
                                <br>
                                <input name="alto" type="text" placeholder="Alto" required>
                                <br>
                                <input name="probar" type="submit" value="probar">
                                <input name="cerrar" type="button" value="cerrar">
                        </form>
                </section>
                <section id="seccion6" class="section" data-scroll-spy>
                        <h2>Detección de Dispositivos <br>(User Agent)</h2>
                        <div id="user-device"></div>
                </section>
                <section id="seccion7" class="section" data-scroll-spy>
                        <h2>Detección de la Conexión</h2>
                </section>
                <section id="seccion8" class="section" data-scroll-spy>
                        <h2>Detección de la Cámara web</h2>
                        <video id="webcam"></video>
                </section>
                <section id="seccion9" class="section" data-scroll-spy>
                        <h2>Geolocalización</h2>
                        <div id="geolocation"></div>
                </section>
                <section id="seccion10" class="section" data-scroll-spy>
                        <h2>Filtros de búsquedas</h2>
                        <input type="search" placeholder="Buscar..." class="card-filter">
                        <article class="cards">
                                <figure class="card">
                                        <img src="https://placeimg.com/200/200/nature" alt="Nature">
                                        <figcaption>Nature</figcaption>
                                </figure>
                                <figure class="card">
                                        <img src="http://placeimg.com/200/200/any" alt="Any">
                                        <figcaption>Any</figcaption>
                                </figure>
                                <figure class="card">
                                        <img src="http://placeimg.com/200/200/tech" alt="Tech">
                                        <figcaption>Tech</figcaption>
                                </figure>
                                <figure class="card">
                                        <img src="http://placeimg.com/200/200/Animals" alt="Animals">
                                        <figcaption>Animals</figcaption>
                                </figure>
                                <figure class="card">
                                        <img src="http://placeimg.com/200/200/people" alt="People">
                                        <figcaption>People</figcaption>
                                </figure>
                                <figure class="card">
                                        <img src="http://placeimg.com/200/200/Arch" alt="Architecture">
                                        <figcaption>Architecture</figcaption>
                                </figure>
                        </article>
                </section>
                <section id="seccion11" class="section" data-scroll-spy>
                        <h2>Sorteo Digital</h2>
                        <ul class="players">
                                <li class="player">JavaScript</li>
                                <li class="player">PHP</li>
                                <li class="player">JAVA</li>
                                <li class="player">C</li>
                                <li class="player">Python</li>
                                <li class="player">Ruby</li>
                                <li class="player">Go</li>
                                <li class="player">Visual Basic</li>
                                <li class="player">Rust</li>
                                <li class="player">Perl</li>
                        </ul>
                        <button id="winner-btn">Obtener Ganador</button>
                </section>
                <section id="seccion12" class="section" data-scroll-spy>
                        <h2>Responsive Slider</h2>
                        <div class="slider">
                                <div class="slider-slides">
                                        <div class="slider-slide active">
                                                <img src="https://placeimg.com/400/400/animals" alt="animals">
                                        </div>
                                        <div class="slider-slide">
                                                <h4>Diapositiva 2</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi,
                                                        officia! Optio placeat maxime in dolore corrupti iusto ipsam
                                                        nemo vel odio, ab autem voluptas voluptatem ipsum distinctio
                                                        enim perferendis sunt?</p>
                                        </div>
                                        <div class="slider-slide">
                                                <img src="https://placeimg.com/400/400/people" alt="people">
                                        </div>
                                        <div class="slider-slide">
                                                <h4>Diapositiva 4</h4>
                                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi,
                                                        officia! Optio placeat maxime in dolore corrupti iusto ipsam
                                                        nemo vel odio, ab autem voluptas voluptatem ipsum distinctio
                                                        enim perferendis sunt?</p>
                                        </div>
                                </div>
                                <div class="slider-btns">
                                        <a class="prev" href="#">&laquo;</a>
                                        <a class="next" href="#">&raquo;</a>
                                </div>
                        </div>
                </section>
                <section id="seccion13" class="section" data-scroll-spy>
                        <h2>Video Inteligente</h2>
                        <video src="./assets/video.mp4" muted controls loop data-smart-video></video>
                        <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
                        <video src="./assets/videoa.mp4" muted controls loop data-smart-video></video>
                </section>
                <section id="seccion14" class="section" data-scroll-spy>
                        <h2>Validaciónes de Formulario</h2>
                        <form class="contact-form">
                                <legend>Envianos tus comentarios</legend>
                                <input type="text" name="name" placeholder="Escribe tu nombre"
                                        title="Nombre solo acepta letras y espacios en blanco"
                                        pattern="^[A-Za-zÑñÁáÉéÍíÓóÚúü\s]+$" required>
                                <input type="email" name="email" placeholder="Escribe tu email" title="Email incorrecto"
                                        pattern="^[a-z0-9]+(\.[_a-z0-9]+)*@[a-z0-9-]+(\.[a-z0-9-]+)*(\.[a-z]{2,15})$"
                                        required>
                                <input type="text" name="subject" placeholder="Asunto a tratar" required>
                                <textarea name="comments" cols="50" rows="5" placeholder="Escribe tus comentarios"
                                        data-pattern="^.{1,255}$"></textarea>
                                <input type="submit" value="Enviar">
                        </form>
                </section>
                <section id="seccion15" class="section" data-scroll-spy>
                        <h2>Sección 15</h2>
                </section>
        </main>
        <button class="scroll-top-btn hidden">&#11014;</button>
        <button class="dark-theme-btn">🌙</button>
        <script src="./js/index_dom.js " type="module"></script>
</body>

</html>
