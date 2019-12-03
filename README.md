# Practica02-MiSitioWeb-CSS-
Práctica 2, implementación de formato CSS.
1. Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web (CSS)”
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura1.PNG)

2. Realizar un commit y push por cada requerimiento de los puntos antes descritos.
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura2.PNG)

3. Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator.
Validación de página Index.html
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura3.PNG)

Validación de página About.html
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura4.PNG)

Validación de página Contactos.html
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura5.PNG)

Validación de página Menu.html
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura6.PNG)

Validación de página Suggestion.html
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/Captura7.PNG)

4. Luego, se debe crear el archivo README del repositorio de GitHub.
![](https://github.com/Jhorjho92/Practica02-MiSitioWeb-CSS-/blob/master/readme/readme.PNG)

5. Generar informe de los resultados en el formato de prácticas. Debe incluir:

a. El desarrollo de cada uno de los puntos antes descritos así como las reglas CSS utilizadas para resolver cada punto.
ok
b. La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cuál, se puede generar fotografías instantáneas (pantallazos).
<!DOCTYPE html>
<html>
    <head>
        <!--
            Author:     Jorge V. Pizarro
            Date:       28-Oct-2019
            Filename:   Index.html
        -->
        <meta charset="utf-8">
        <meta name="keywords" content="ceviche, camaron, cangrejo, encebollado, carnes, asado">
        <link type="text/css" rel="stylesheet" href="./css/threecolumns.css">
        <link type="text/css" rel="stylesheet" href="./css/banner.css" >
        <link type="text/css" rel="stylesheet" href="./css/estilos.css">
        <link type="text/css" rel="stylesheet" href="./css/estilos.css">
        <link type="text/css" rel="stylesheet" href="./css/index.css">
        <link href="./css/all.css" rel="stylesheet"> <!--load all styles -->
        <title>La Cevicheria Mar y Tierra - Index</title>
    </head>
    <body>
        <header>
            <div align="center" class="logobanner">
                    <a href="index.html"><img src="./imagenes/logo-horizontal.jpg" alt="La Cevichería"></a>    
            </div>  
            <ul class="menulistbanner">
                <li><a href="index.html">INICIO</a></li>
                <li><a href="./documentos/general/menu.html">MENU</a></li>
                <li><a href="./documentos/general/about.html">NOSOTROS</a></li>
                <li><a href="./documentos/general/contact.html">CONTACTOS</a></li>
                <li><a href="./documentos/general/suggestion.html">SUGERENCIAS</a></li>
                <form class="formbuscar">
                    <fieldset class="campobuscar">
                        <input type="search" placeholder="Buscar..."/>
                        <button type="submit">
                            <i class="fas fa-search"></i>
                        </button>
                    </fieldset>
                </form>
            </ul>
        </header>
        
        <section>
            <img alt="" src="./imagenes/portada.jpg" id="imgportada">
        </section>

        <h1>Mar y Tierra</h1>
        <p id="pIndex">
            Deleita tu paladar con la mejor comida del mar. Con la mejor sazón de la cuidad y los mejores mariscos. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corrupti quidem reiciendis optio earum molestiae voluptates eius voluptate soluta illum ex, facilis labore officiis commodi a, iusto esse ut maiores fugit!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel animi atque harum at laudantium recusandae quaerat officia, eaque enim aut cum similique omnis corrupti impedit esse accusamus! At, quos quae?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita temporibus minus explicabo aliquam provident dolore voluptates? Ex harum ducimus recusandae cum ipsum quos atque, excepturi facilis illo, aperiam perferendis optio?
        </p>

        <footer>
            &copy; Jorge Vinicio Pizarro Romero &#8226; Universidad Politécnica Salesiana &#8226; <a href=»mailto:jpizarror@est.ups.edu.ec»>jpizarror@est.ups.edu.ec</a>
        </footer>
    </body>
</html>


<!DOCTYPE html>
<html>
    <head>
        <!--
            Author:     Jorge V. Pizarro
            Date:       28-Oct-2019
            Filename:   About.html
        -->
        <meta charset="utf-8">
        <meta name="keywords" content="ceviche, camaron, cangrejo, encebollado, carnes, asado">
        <link type="text/css" rel="stylesheet" href="../../css/banner.css" >
        <link type="text/css" rel="stylesheet" href="../../css/estilos.css">
        <link type="text/css" rel="stylesheet" href="../../css/threecolumns.css">
        <link href="../../css/all.css" rel="stylesheet"> <!--load all styles -->
        <title>La Cevicheria Mar y Tierra - Index</title>
    </head>
    <body>
        <header>
            <div align="center" class="logobanner">
                    <a href="../../index.html"><img src="../../imagenes/logo-horizontal.jpg" alt="La Cevichería"></a>    
            </div>
            <ul class="menulistbanner">
                <li><a href="../../index.html">INICIO</a></li>
                <li><a href="menu.html">MENU</a></li>
                <li><a href="about.html">NOSOTROS</a></li>
                <li><a href="contact.html">CONTACTOS</a></li>
                <li><a href="suggestion.html">SUGERENCIAS</a></li>
                <form class="formbuscar">
                    <fieldset class="campobuscar">
                        <input type="search" placeholder="Buscar..."/>
                        <button type="submit">
                            <i class="fas fa-search"></i>
                        </button>
                    </fieldset>
                </form>
            </ul> 
        </header>
        
        <nav>
            <h1 class="menutext">
                <a href="../../index.html">Inicio</a> &gt; Menu
            </h1>
        </nav>

        <section id="sectionvideo">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/_HUlWpum9LI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </section>
        
        <section>
            <p>Camarones Reventados</p>
            <img src="../../imagenes/menu/camaron-reventado.png" id="imgmenu">
        </section>
        <section>
            <p>Filete de Pescado</p>
            <img src="../../imagenes/menu/filete-pescado.jpg" id="imgmenu">
        </section>
        <section>
            <p>Langostino al Ajillo</p>
            <img src="../../imagenes/menu/langostino-ajillo.jpg" id="imgmenu">
        </section>
        
        <footer>
            &copy; Jorge Vinicio Pizarro Romero &#8226; Universidad Politécnica Salesiana &#8226; <a href=»mailto:jpizarror@est.ups.edu.ec»>jpizarror@est.ups.edu.ec</a>
        </footer>
    </body>
</html>


#sectionvideo{
    width: 100%;
    margin: 0 auto;
    align-content: center;
}
#sectionvideo iframe{
    align-content: center;
    padding-left: 30%;
}

section{
    width: 33%;
    float: left;
    padding: 10px 10px;
    box-sizing: border-box;
}
#imgmenu{
    width: 85%;
    height: 85%;
    padding-left: 40px;   
}
p{
    text-align: center;
}


<!DOCTYPE html>
<html>
    <head>
        <!--
            Author:     Jorge V. Pizarro
            Date:       28-Oct-2019
            Filename:   About.html
        -->
        <meta charset="utf-8">
        <meta name="keywords" content="ceviche, camaron, cangrejo, encebollado, carnes, asado">
        <link type="text/css" rel="stylesheet" href="../../css/banner.css" >
        <link type="text/css" rel="stylesheet" href="../../css/estilos.css">
        <link type="text/css" rel="stylesheet" href="../../css/twocolumns.css">
        <link href="../../css/all.css" rel="stylesheet"> <!--load all styles -->
        <title>La Cevicheria Mar y Tierra - Index</title>
    </head>
    <body>
        <header>
            <div align="center" class="logobanner">
                    <a href="../../index.html"><img src="../../imagenes/logo-horizontal.jpg" alt="La Cevichería"></a>    
            </div>
            <ul class="menulistbanner">
                <li><a href="../../index.html">INICIO</a></li>
                <li><a href="menu.html">MENU</a></li>
                <li><a href="about.html">NOSOTROS</a></li>
                <li><a href="contact.html">CONTACTOS</a></li>
                <li><a href="suggestion.html">SUGERENCIAS</a></li>
                <form class="formbuscar">
                    <fieldset class="campobuscar">
                        <input type="search" placeholder="Buscar..."/>
                        <button type="submit">
                            <i class="fas fa-search"></i>
                        </button>
                    </fieldset>
                </form>
            </ul> 
        </header>
        
        <nav>
            <h1 class="menutext">
                <a href="../../index.html">Inicio</a> &gt; Contacto
            </h1>
        </nav>
        <section>
            <p>
                    <h6>La Cevicheria</h6>
                    <p id="psalto">
                        Mar y Tierra <br>
                        Todo en mariscos y carnes a tu servicio.
                    </p>
                    <h5> <i class="fas fa-map-marker-alt"></i>  Dirección</h5>
                    <p id="psalto">
                            Av. 25 de Marzo y entrada a San Miguel (Sector Ricaurte)<br>
                        Cuenca <br>
                        Ecuador <br>
                    </p>
                    
                    <h5><i class="fas fa-phone-alt"></i>Telefonos:</h5>
                    <p id="psalto">
                        +593 980 919 109 <br>
                        +593 740 313 69
                    </p>
                    
            </p>
        </section>
        <section>
            <form class="formContact">
                <h2>Contacto:</h2>
                <input type="text" name="Nombre" placeholder="Nombre" id="inputcontacto">
                <input type="text" name="Correo" placeholder="Correo" id="inputcontacto">
                <input type="text" name="Telefono" placeholder="Teléfono" id="inputcontacto">
                <input type="text" name="Asunto" placeholder="Asunto" id="inputcontacto">
                <textarea name="" placeholder="Escriba aquí su mensaje."></textarea>
                <input type="button" value="Enviar" id="boton">
            </Form>
        </section>
        <footer>
            &copy; Jorge Vinicio Pizarro Romero &#8226; Universidad Politécnica Salesiana &#8226; <a href=»mailto:jpizarror@est.ups.edu.ec»>jpizarror@est.ups.edu.ec</a>
        </footer>
    </body>
</html>


section{
    width: 50%;
    float: left;
}

.formContact{
    width: 550px;
    margin: auto;
    background: rgba(0, 0, 0, 0.2);
    padding: 5px 10px;
    box-sizing: border-box;
    border-radius: 5px;
}

h2 {
    color: #2A4C6F ;
    text-align: left;
    margin: 0;
    font-size: 25px;
    margin-bottom: 10px;
}

#inputcontacto, #boton, textarea {
    width: 100%;
    margin-bottom: 20px;
    padding: 10px 10px;
    box-sizing: border-box;
    font-size: 14px;
    border: none;
    font-family: monospace;
}

textarea{
    min-width: 100%;
    max-width: 100%;
    max-height: 200px;
    min-height: 100px;
}

#boton:hover{
    cursor: pointer;
}


p{
    margin: 0px;
    
}

h6, h5{
    font-size: 25px;
    margin: 0;
    padding: 0px 50px ;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif, Helvetica, 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

h5{
    font-size: 20px;
    padding-top: 20px;
}

.fa-map-marker-alt {
    background: #fff;
}

#psalto{
    padding-left: 75px;
}


*{
    border: none;
    border-style: 0;
    color: #2A4C6F ;
}

body{
    margin: 0;
    background-attachment: fixed;
}

.menutext{
    color: #C12B37;
    font-family: sans-serif;
    font-size: 20px;
}

.menutext a{
    text-decoration: none;
    font-family: sans-serif;
    padding-left: 25px;
    color: #E04644;
    font-size: 20px;
    
}

.colores {    
    color: #004F68;
    color:#003A64, #6FCB55, #6B499E, #C12B37, #FBDA68, #00B9E0;
    color: #2A4C6F, #92D25E, #8F5FA5, #D0383E, #FCDF73, #3DC2E3;
    color:#555E7B, #B7D968, #B576AD, #E04644, #FDE47F, #7CCCE5;
}

footer{
    width: 100%;
    float: left;
}

c. La evidencia de la validación de cada página HTML.
Ok

d. La evidencia de la validación de las hojas de estilos CSS.
Ok

e. Concluciones:
La practica nos permitió conocer de manera apropiada de como dar formato de estilo a nuestas página, ya que html es solamente el cuerpo o información que deseamos presentar.
Pero CSS nos ayuda a que su presentación sea mas adecuada y a la vez mas presentable ante las personas que puedan interactuar con ellas.

f. En el informe se debe incluir la información de GitHub (usuario y URL del repositorio de la práctica)
Usuario GITHUB: Jhorjho92
Email: jota_pi@hotmail.es
Link: https://github.com/Jhorjho92/Practica01-My-Blog 
