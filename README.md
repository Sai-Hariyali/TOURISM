<!DOCTYPE html>
<html lang="en">
<head>
    <title>PyTourism</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <link rel="icon" href="logo.jpg">
  <!-- jQuery -->
  <script> 
      $(document).ready(function(){
        $("p,h5,.a5,.f1").mouseover(function(){
        $("p, h5,.a5,.f1").css("background-color", "yellow");
    });
        $("p, h5,.a5,.f1").mouseout(function(){
        $("p").css("background-color", "lightgray");
        $("h5").css("background-color", "white");
        $(".a5,.f1").css("background-color", "peachpuff");
    });
});
  </script>
  <!-- css -->
<style>
        body{
        background-image: url("bgw.jpg");
        }
        .a2{
            padding:2%;
        } 
        .b1{
            padding: 1%;
        }
        .carousel-inner img {
         margin: 0 auto;
         text-align: center;
        }
        .row{
            background-color: white;
            margin-right: 15%;
            margin-left: 15%;
        }
        @media screen and (min-width: 601px) {
            div.a2 {
          font-size: 80px;
        }
    }
        @media screen and (max-width: 600px) {
             div.a3 {
            font-size: 30px;
         }
    }
    </style>
</head>
<body>
<!-- bootstrap -->
    <div class="container-fluid">
        <div class="row">
            <div class="col-sm">
                <img src="logo.jpg" class="img-fluid mx-auto d-block a3"/>
                <center><a class="link" href="https://www.pondytourism.in/">https://www.pondytourism.in/</a></center>
            </div>
            <div class="col-sm text-center display-5 a2">
            <h5 font-size:10vw;><i> Pondicherry (/ˌpɒndɪˈtʃɛri/), now known as Puducherry (/ˌpʊdʊˈtʃɛri/), is the capital and the most-populous city of the Union Territory of Puducherry in India.
The city is in the Puducherry district on the southeast coast of India and is surrounded by the state of Tamil Nadu, with which it shares most of its culture, heritage, and language.
             </i></h5>
            </div>
        </div>
        <div class="row">
            <img src="main.jpg" class="img-fluid mx-auto d-block b1">
        </div>
        <div class="row">
            <div class="col p-3 text-black text-center display-4">AAYI MANDAPAM</div>
        </div>
        <div class="row">
            <div class="col p-3 text-black text-center display-5 a5">Park Monument is a white monument, built during the time of Napoleon III, Emperor of France.</div>
        </div>
        <div class="row">
            <div class="col-sm">
                <img src="prom.jpg" class="img-fluid img-thumbnail rounded float-start ">
                <div class="col p-3 text-black text-center h3 display-5">PROMENADE BEACH</div>
                <div class="col p-3 text-black text-center display-6"> One of the most visited places in this beautiful coastal city, popularly known for its shimmering sand and cosy ambiance.</div>
            </div>
            <div class="col-sm">
                <img src="auro.jpg" class="img-fluid img-thumbnail rounded float-end">
                <div class="col p-3 text-black text-center h3 display-5">AUROVILLE</div>
                <div class="col p-3 text-black text-center display-6">It's a universal city in the making in south-India dedicated to the ideal of human unity based on the vision of Sri Aurobindo and The Mother.</div>
            </div>
        </div>
        <div class="row">
            <img src="frecol.jpg" class="img-fluid mx-auto d-block">
        </div>
        <div class="row">
            <div class="col p-3 text-black text-center h1 display-6">FRENCH COLONY</div>
        </div>
        <div class="row">
            <div class="col p-3 text-black text-center h6 display-5 f1">The spectacular French architecture gives you the feeling as if you have landed in Bordeaux or Montpellier.
        </div>
        <div class="row">
            <div class="col-sm">
                <img src="olh.jpg" class="img-fluid rounded-circle mx-auto d-block">
                <div class="col p-3 text-black text-center h3 display-5">OLD LIGHT HOUSE</div>
                <div class="col p-3 text-black text-center display-6">Built above a rectangular platform, the Lighthouse was a fluted construction with a height of 29 m, located just opposite to the famous Gandhi Statue on the Beach Road</div>
            </div>
            <div class="col-sm">
                <img src="loa.jpg" class="img-fluid rounded-circle mx-auto d-block">
                <div class="col p-3 text-black text-center h3 display-5">DUMAS CHURCH</div>
                <div class="col p-3 text-black text-center display-6">The architectural beauty was built in 1855 is the apple of everyone's eye. Facing the sea, it is a centre of attraction for the tourists and a peaceful place to pray and meditate.</div>
            </div>
        </div>

        <div class="row"> <!--carousel-->
            <div id="demo" class="carousel slide" data-ride="carousel">
                <!-- Indicators -->
                <ul class="carousel-indicators">
                <li data-target="#demo" data-slide-to="0" class="active"></li>
                <li data-target="#demo" data-slide-to="1"></li>
                <li data-target="#demo" data-slide-to="2"></li>
                </ul>
                <!-- The slideshow -->
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="wt2.jpg" class="img-fluid">
                    </div>
                    <div class="carousel-item">
                        <img src="mkgs.jpg" class="img-fluid">
                    </div>
                    <div class="carousel-item">
                        <img src="chinveer.jpg" class="img-fluid">
                    </div>
                </div>
                <!-- Left and right controls -->
                <a class="carousel-control-prev" href="#demo" data-slide="prev">
                <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#demo" data-slide="next">
                <span class="carousel-control-next-icon"></span>
                </a> 
            </div>
        </div>

       <div class="row"><br>
           <div class="col-sm"><br>
            <iframe width="300" height="315" src="https://www.youtube.com/embed/reryq0rxpM0" title="YouTube video player" frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
            </iframe>
           </div>
           <div class="col-sm p-3 text-dark text-center h6 display-6 a3">
               <p font-size:10vw;>Unlike much of India, Pondicherry seems to cherish its heritage rather than wiping it clean with shiny new buildings, or letting it crumble in indifference, has always given its old-world charm a decidedly cosmopolitan flavour.</p>
               <p font-size:10vw;> In recent years, Pondicherry has changed from a sleepy small town to a vibrant tourist destination, and is now dotted with heritage hotels, chic boutiques and Parisian-style cafés.
        It is only when you amble through its hushed alleys that you discover the languid mood that defines the city and the little pieces that make up its soul: a grand villa, a forgotten statue and a shady park.</p>
           </div>
       </div> 
       <div class="row">
        <div class="col-sm p-3 text-dark text-center h6">
        <i>~ where time stops and unravels history !!!</i></p>    
        </div>
       </div>
</div>
</body>
</html>
