

SOBRE EL PROYECTO

Nombre del proyecto: CULTIVA ESTUDIO (cultiva-vottasueiro) 
Breve descripción: el proyecto está basado en mi emprendimiento personal en dónde me dedico al diseño de sitios web en wordpress. La idea fue crear en html y sass una reversión de mi web actual, incluyendo el contenido más importante y cambiándole el branding para hacerla distinta a la web que ya tengo. 
Tipo de sitio web: profesional. La web cuenta con 5 páginas en total: inicio, servicios, proyectos, nosotros y contacto.
Objetivo web: mostrar los servicios que ofrecemos, los proyectos realizados y que sirva como otro canal de contacto. 

TECNOLOGÍA Y CÓDIGOS

El proyecto fue desarrollado en Visual Studio Code utilizando HTML para la estructura del sitio. Se utilizó SASS para crear su diseño y estilo, incorporando en el mismo Flexbox y Grid para direccionar y acomodar elementos. Se incluyeron fragmentos de código de Bootstrap, animaciones y transiciones. Se crearon partials para reducir la cantidad de códigos cómo mixins y extends. La web es responsive aplicando media queries en cada página. Toda la web incluye SEO optimizando títulos, metas e imágenes (las configuraciones aplicadas de SEO se encuentran detallas en el archivo pdf SEO).

Muestra de códigoss:
HTML 
<div>
        <ul>
                <li><a href="../index.html">Inicio</a></li>
                <li><a href="./servicios.html">Servicios</a></li>
                <li><a href="./proyectos.html">Proyectos</a></li>
                <li><a href="./nosotros.html">Nosotros</a></li>
                <li><a href="./contacto.html">Contacto</a></li>
        </ul>
</div>

SASS

.nosotros{
    @extend %flex;
    h1{
        font-size: 60px; 
        font-weight: 300; 
        text-align: center;
        margin: 45px 0px 0px 0px;
    }
    p{
        font-size: 22px; 
        font-weight: 200;
        font-style: oblique; 
        text-align: center;
        padding: 20px 160px 70px 160px;
    }
}

BOOTSTRAP
 <section class="newsletter"> 
         <div>
                <h2>¿Querés recibir novedades, descuentos y estar actualizado?</h2>
                <p>Dejanos tu mail a continuación para suscribirte a nuestro newsletter</p>
            </div>
            <div class="email-label">
                <label for="email"> </label>
                <input type="email" name="email" placeholder="email@ejemplo.com">
            </div>
            <div class="suscribirme">
                <button type="button" class="btn btn-secondary btn-dark">SUSCRIBIRME</button>
        </div>
</section>

EXTENDS

%cta {
    background-color: $color-uno;
    color: $color-dos;
    border-radius: 4px;
}

MIXINS
@mixin flex ($flex, $justify, $wrap) {
    display: $flex;
    justify-content: $justify;
    flex-wrap: $wrap;
}

MEDIA QUERIES

@media screen and (max-width:400px){
    .proyectos .imagenes-proyectos img{
        width: 300px; 
        height: 300px;
    }
}

CONTACTO

hola@cultivaetsudio.com
+549 116558-2201



