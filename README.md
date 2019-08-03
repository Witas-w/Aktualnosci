# aktualności
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
           font-family: Arial;
           float: left;
          left: 0px;
       }
       #aut{
        
         color: green;  
       }
      #klik{
         color: grey; 
      }
     
    
      
      #lokiter{
          background-color: #4e9447;
          position: absolute;
          top: 200px;
          right: 10px;
         width:85%;
         font-size: 20px;
         z-index: 2;
      }
      #akt{
          border-bottom:1px solid white;
          
      }
     
      #img {
       position: absolute;
       z-index: 1;
      height: 100%;
      bottom: 0px;
       top: 70px;
       width: 100%;
       right: 0px;
       left: 0px;
       margin: 0;
       }
       ul {
           position: absolute;
           margin: 0px;
           padding: 0px;
           list-style-type: none;
           right: 0px;
           top: 30px;
           z-index: 3;
       }
       ul li{
           width: 150px;
           height: 40px;
           background-color: red;
           opacity: .8;
           line-height: 40px;
           text-align: center;
          font-size: 20px;
              
       }
       ul li a{
           text-decoration: none;
           color: white;
           display: block;
           
       }
       ul li a:hover{
           background-color: green;
       }
       
       
       ul li ul li{
           display: none;
           top: 10px;
           position: relative;
       }
      
       ul li:hover ul li{
           display: block;
       }

        ul li:active ul li{
           display: block;
       }
       
        </style>
    </head>
    <body>
    <div class="menu-1">
    
        <p><span id="aut">Autor:</span><span id="klik"><em><strong> JAKUB<BR>WITKOWSKI</strong></em></span></p>
         </div>
        
       <ul>
       <li><a href="#">Menu</a>
      <ul>
            <li><a class="lok" href="https://witas-w.github.io/Aktualnosci/">Aktualności</a></li>
            <li><a class="klok" href="https://witas-w.github.io/Bloguje-witas/">Blog</a></li>
            <li><a class="loki" href="https://witas-w.github.io/Galeria-zdjec/">Zdjęcia</a></li>
        </ul>
        </li>
        </ul>
   
        <img id="img" src="https://s6.ifotos.pl/img/3E431C6E-_qseaxrr.jpg">
        

        
        
        <div id="lokiter">
         <h3 id="akt">Aktualności</h3>
         <p>Obecnie jestem na wakacjach w Ustce. Ustka to miejscowość w województwie Pomorskim w powiecie Słupskim w gminie Ustka. Położona jest ona nad ujściem rzeki Słupii do morza Bałtyckiego.</p>
        </div>
       
   
 
    </body>
</html>
