## Rgalli Contrucción
#### Principal Info WebSite.
---
  
    Detalles de la pagina

> Rgalli
>> <img src ="./img1.png">
>> <img src ="./img2.png">


**Codigo html**
```Html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.0/font/bootstrap-icons.css">
    <!--FontGoogle-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="./css/main.css">

    <!--WAPP-->
    <link rel="stylesheet" href="./whats.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <!--CSS-->
    <link rel="stylesheet" href="./whats2.css">
    
    <!--GoogleMap-->
    

    <!--SWichALTER2-->
    <link href="//cdn.jsdelivr.net/npm/@sweetalert2/theme-dark@4/dark.css" rel="stylesheet">


    <title>RGALLI</title>
  </head>
  <body>
  <!--========================================================== -->
                        <!-- ENCABEZADO -->
  <!--========================================================== -->
    <header class="container-fluid bg-warning d-flex justify-content-center">
        <p class="text-light mb-0 p-2 fs-6">Contactanos +54 9 342 485-2644</p>
    </header>

    <nav  class="navbar navbar-expand-lg navbar-light p-3"  id="menu">
        <div class="container">
          <a class="navbar-brand" href="#">
              <span class="fs-5 text-warning fw-bold">R</span>GALLI
          </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#">Inicio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#equipo">Equipo</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#asesoramiento">Contactanos</a>
              </li>
            </ul>
          </div>

        </div>
      </nav>

    <!--========================================================== -->
                        <!-- SLIDER DE IMAGENES-->
    <!--========================================================== -->
   
    <div id="carousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="3000">
            <img src="./img/slide1.png" class="d-block w-100" alt="">
          </div>
          
 
          <div class="carousel-item" data-bs-interval="3000">
            <img src="./img/slide2.png" class="d-block w-100" alt="...">
          </div>
 

          <div class="carousel-item" data-bs-interval="3000">
            <img src="./img/slide3.png" class="d-block w-100" alt="...">
          </div>
 
 
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carousel"  data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carousel"  data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>    
    
        
     
    <!--========================================================== -->
                        <!-- INTRODUCCION DE SERVICIOS-->
    <!--========================================================== -->


    <section class="d-flex flex-column justify-content-center align-items-center pt-5  text-center w-50 m-auto" id="intro">
    <h1 class="p-3 fs-2 border-top border-3">Una agencia única para todas tus necesidades de <span class="text-primary">Contrucción y Refaccionamiento</span></h1>
     <p class="p-3  fs-4">
         <span class="text-primary">R<span class="text-dark">Galli</span></span> es la agencia donde te ayudamos a cumplir tus proyectos, construimos y hacemos relida aquello que tanto deseas.       
     </p>   
    </section>

   <!--========================================================== -->
                        <!-- TIPOS DE SERVICIOS-->
    <!--========================================================== -->


<section class="w-100">
    <div class="row w-75 mx-auto" id="servicios-fila-1">       
        <div class="col-lg-6 col-md-12 col-sm-12 d-flex justify-content-start my-5 icono-wrap">
            <img src="./img/Planeamiento.png" alt="desarrollo"   width="180" height="160">

            <div>
                <h3 class="fs-5 mt-4 px-4 pb-1">Planeamiento</h3>
                <p class="px-4">Gestionamos un plan de estructura del proyecto.</p>
            </div>

        </div>

        <div class="col-lg-6 col-md-12 col-sm-12 d-flex justify-content-start  my-5 icono-wrap">
            <img src="./img/Contrato.png" alt="concepto" width="180" height="160">

            <div>
                <h3 class="fs-5 mt-4 px-4 pb-1 icono-wrap">Contrato</h3>
                <p class="px-4">Con el Diseño listo, Conseptualización e Implementación del proyecto acudimos a ponerlo en marcha.</p>
            </div>
        </div>   
    </div>
    
    <div class="row w-75 mx-auto mb-5" id="servicios-fila-2">       
        <div class="col-lg-6 col-md-12 col-sm-12 d-flex justify-content-start  my-5 icono-wrap">
            <img src="./img/Refaccionamiento.png" alt="comunicaciones" width="180" height="160">

            <div>
                <h3 class="fs-5 mt-4 px-4 pb-1">Refaccionamiento</h3>
                <p class="px-4">Acudimos a refaccionar su infraestructura como su hogar.</p>
            </div>
        </div>

        <div class="col-lg-6 col-md-12 col-sm-12 d-flex justify-content-start my-5 icono-wrap">
            <img src="./img/Obra por excelencia.png" alt="seo" width="180" height="160" >

            <div>
                <h3 class="fs-5 mt-4 px-4 pb-1">Obra por excelencia</h3>
                <p class="px-4">Con los mejores especialistas tendra una garantia unica de trabajo por exelencia.</p>
            </div>
        </div>   
    </div>

</section>

<!--========================================================== -->
                        <!-- SECCION ACERCA DE NOSOTROS-->
<!--========================================================== -->

<section>
    <div class="container w-50 m-auto text-center" id="equipo">
        <h1 class="mb-5 fs-2">Equipo pequeño con <span class="text-primary">resultados Grandes</span>.</h1>
        <p class="fs-4 ">Siempre buscamos las personas adecuadas para que trabajen con nosotros. Estas en buenas manos para poder comenzar a contruir tus proyectos</p>
    </div>

    <div class="mt-5 text-center">
        <img id="img-equipo" src="./img/obreros-3.png" alt="equipo">
    </div>
    
    <div id="local" class="border-top border-2">
      <div class="mapimagen"><img src="./img/mapPunt.png" alt=""></div>
        <div>
            <div class="wrapper-local">
                <h2>Ubicado en Argentina, Capital Santa fe</h2>
                <h2 class="text-primary mb-4" id="typewriter"></h2>
                <p class="fs-5 text-body">Elijimos Santa fe para nuestra oficina con el objetivo de estar cerca a nuestros clientes. Estamos ubicados en la capital, tambien tenes un sistema de gestion de visitas la cual hablamos directamente con los clientes</p>
                <section class="d-flex justify-content-start" id="numeros-local">
                    <div>
                        <p class="text-primary fs-5">200</p>
                        <p>Dias de Sol</p>
                    </div>
                    <div>
                        <p class="text-primary fs-5">100%</p>
                        <p>Aprobado</p>
                    </div>
                    <div>
                        <p class="text-primary fs-5">24 °C</p>
                        <p>Temperatura</p>
                    </div>
                    
              </section>
            </div>
        </div>
    </div>

  
</section>
<!--SECTION SPECIAL-->


<!--========================================================== -->
                        <!-- SECCION CONTACTOS-->
<!--========================================================== -->

<section id="seccion-contacto" class="border-bottom border-secondary border-2">
  <div id="bg-contactos">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#ffd700" fill-opacity="1" d="M0,32L0,128L84.7,128L84.7,64L169.4,64L169.4,288L254.1,288L254.1,224L338.8,224L338.8,320L423.5,320L423.5,192L508.2,192L508.2,128L592.9,128L592.9,288L677.6,288L677.6,32L762.4,32L762.4,64L847.1,64L847.1,288L931.8,288L931.8,256L1016.5,256L1016.5,96L1101.2,96L1101.2,224L1185.9,224L1185.9,64L1270.6,64L1270.6,320L1355.3,320L1355.3,224L1440,224L1440,0L1355.3,0L1355.3,0L1270.6,0L1270.6,0L1185.9,0L1185.9,0L1101.2,0L1101.2,0L1016.5,0L1016.5,0L931.8,0L931.8,0L847.1,0L847.1,0L762.4,0L762.4,0L677.6,0L677.6,0L592.9,0L592.9,0L508.2,0L508.2,0L423.5,0L423.5,0L338.8,0L338.8,0L254.1,0L254.1,0L169.4,0L169.4,0L84.7,0L84.7,0L0,0L0,0Z"></path></svg>

    <div class="card-group">
      <div class="card" id="asesoramiento">
        <img src="./img/img1.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Amplia experiencia en Areas Escenciales</h5>
          <p class="card-text">Tenemos amplia experiencia en la construcciones y en areas sumamente escenciales de obra, colocacion y mucho mas.</p>
          <p class="card-text"><small class="text-muted">RGALLI Contruyendo para tu confianza</small></p>
        </div>
      </div>
      <div class="card">
        <img src="./img/img2.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Contactanos para que adquieras Promociones</h5>
          <p class="card-text">Comunicate por Whatsapp y te vamos ha asesorar para que puedas tomar las mejores desiciones</p>
          <p class="card-text"><small class="text-muted">No pierdas la Oportunidad!</small></p>
        </div>
      </div>
      <div class="card">
        <img src="./img/img3.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Aquiera muestras de Trabajo</h5>
          <p class="card-text">Al contactarse podremos mostrarles algunos de los grandes trrabajos realizados, podremos establecer una cita previa tambien para poder tomar rienda a tu proyecto que quieras llevar en marcha.</p>
          <p class="card-text"><small class="text-muted">Accede a nuestra galleria de trabajo y trayectoria</small></p>
        </div>
      </div>
    </div>
  </div>
  
  <!--Slider-->
  


<!--========================================================== -->
                      <!-- CONTENEDOR DEL FORMULARIO -->
<!--========================================================== -->
<!--    <div class="container  border-top border-primary " style="max-width: 500px" id="contenedor-formulario">
      <div class="text-center mb-4" id="titulo-formulario">
        <div><img src="./img/callcenter.png" alt="" class="img-fluid ps-5"></div>
        <h2>Contactanos</h2>
        <p class="fs-5">Estamos aqui para hacer realidad de tus proyectos</p>
      </div>

     

      <form   method="POST" data-netlify="true" action="#">     
            <div class= "mb-3">           
              <input type="email" class="form-control" id="email" name="email" placeholder="rgalli.construcciones@gmail.com">
            </div>
 
          
            <div class="mb-3">            
              <input type="input" class="form-control" id="name" name="name" placeholder="Ricardo Galli">
            </div>
      

            <div class="mb-3">
              <input type="tel" class="form-control" name="phone" id="phone" placeholder="Teléfono">
            </div>

          <div class="mb-3">       
            <textarea class="form-control" name="message" id="message" rows="4"></textarea>
          </div>
          
          
          <div class="mb-3">
            <button type="submit" class=" btn btn-primary w-100 fs-5" id="btnEnviar">Enviar Mensaje</button>
          </div>
      </form> 
      
  </div>
</section>   -->



<!--=========================DBase============================-->
<!--========================================================-->

<!--========================================================== -->
                        <!--FOOTER-->
<!--========================================================== -->


<footer class="w-100  d-flex  align-items-center justify-content-center flex-wrap">
  <p class="fs-5 px-3  pt-3 text-dark">RGALLI &copy; Todos Los Derechos Reservados 2022</p>
  <div id="iconos" >
      <a href="#"><i class="bi bi-facebook"></i></a>
      <a href="#"><i class="bi bi-twitter"></i></a>
      <a href="#"><i class="bi bi-instagram"></i></a>  
  </div>
</footer>
<div class="nav-bottom">
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
rel="stylesheet">
   <div class="popup-whatsapp fadeIn">
       <div class="content-whatsapp -top"><button type="button" class="closePopup">
             <i class="material-icons icon-font-color">close</i>
           </button> 
         
          <p>  <img src="./img/logo.png" width="50">¿Quieres hablar con Rgalli? </p>
          
       </div>
       <div class="content-whatsapp -bottom">
         <input class="whats-input" id="whats-in" type="text" Placeholder="Enviar mensaje..." />
          
 
           <button class="send-msPopup" id="send-btn" type="button">
               <i class="material-icons icon-font-color--black">send</i>
           </button>

       </div>
   </div>
   <button type="button" id="whats-openPopup" class="whatsapp-button">
       <div class="float" >
<i class="fa fa-whatsapp my-float"></i></div>
   </button>
   <div class="circle-anime"></div>
</div>
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js" integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0" crossorigin="anonymous"></script> 
    <script src="https://unpkg.com/typewriter-effect@latest/dist/core.js"></script>
    <script src="/alert&toast.js"></script>
    <script src="./main.js"></script>
    <script  src="./script2.js"></script>
    <script src="./firebaseDB.js"></script>
    <!--SweetAlert2-->
    <script src="//cdn.jsdelivr.net/npm/sweetalert2@11/dist/sweetalert2.min.js"></script>

  </body>
</html>
```
**Codigo Javascript**
```javascript
let app = document.getElementById('typewriter');
 
let typewriter = new Typewriter(app, {
  loop: true,
  delay: 75,
});
 
typewriter
  .pauseFor(2500)
  .typeString('La Capital del Santa Fe')
  .pauseFor(200)
  .deleteChars(10)
  .start();

//event

```
**Codigo javascriptmap**
```javascript
let app = document.getElementById('typewriter');
 
let typewriter = new Typewriter(app, {
  loop: true,
  delay: 75,
});
 
typewriter
  .pauseFor(2500)
  .typeString('La Capital del Santa Fe')
  .pauseFor(200)
  .deleteChars(10)
  .start();

//event



```
*Puedes acceder a la pagina desde* 
[Este link](https://rgcontruccion-ar.web.app/)

**Dante Creed** [perfil](https://github.com/dantecreedar)