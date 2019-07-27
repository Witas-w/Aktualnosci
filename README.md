# aktualnosci
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>testowa.pl</title>
        <style>
      
        body{
         color: white; 
    background: #396f38;
    margin: 0;
   
   
        }
       .menu-1{
           background: white;
           top: 0px;
           width: 100%;
           height: 70px;
           position: absolute;
           font-family: fantasy;
           float: left;
          
       }
       #aut{
        
         color: blue;  
       }
      #klik{
         color: grey; 
      }
      #lokko{
          position: absolute;
          top: 40px;
          left: 127px;
          font-family: fantasy;
          
      }
      nav{
          text-decoration: none;
      }
      a{
        text-decoration: none;
        color: black;
       
      }
      a:hover{
          background-color: red;
          color: white;
      }
      a:active{
          background-color: red;
            color: white;
      }
      .lok{
         position: absolute; 
         left: 20px;
      }
      .klok{
           position: absolute;
           left: 120px;
      }
      .loki{
           position: relative;
           left: 173px;
      }
      #lokiter{
          background-color: #4e9447;
          position: absolute;
          top:123px;
          right: 47px;
         width:25%;
         font-size: 10px;
      }
      #akt{
          border-bottom:1px solid white;
          
      }
      .img{
          float: left;
          top: 500px;
          left: 20px;
          width: 25%;
          height: 30%;
          position: fixed;
      }
        </style>
    </head>
    <body>
    <div class="menu-1">
    
        <p><span id="aut">Autor:</span><span id="klik"><em><strong> JAKUB<BR>WITKOWSKI</strong></em></span></p>
         </div>
         <div id="lokko">
        <nav>
            <a class="lok" href="#">Aktualnosci</a>
            <a class="klok" href="#">Blog</a>
            <a class="loki" href="#">Galeria zdjęć</a>
        </nav>
        <img class="img" src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Ustka_z_lotu_ptaka_IMG_6828.jpg">
        </div>
        <div id="lokiter">
         <h3 id="akt">Aktualności</h3>
         <p>Obecnie jestem na wakacjach w Ustce. Ustka to miejscowość w województwie Pomorskim w powiecie Słupskim w gminie Ustka. Położona jest ona nad ujściem rzeki Słupii do morza Bałtyckiego</p>
        </div>
       
   
 
    </body>
</html>
