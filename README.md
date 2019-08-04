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
       .nav{
           position: absolute;
         
           text-align: right;
           color: black;
           height: 65px;
           line-height: 70px;
           right: 0;
           top: 20px;
           z-index: 3;
       }
       .menu{
           margin: 0 10px;
       }
       .menu a{
           clear: right;
           text-decoration: none;
           color: black;
           margin: 0 10px;
           line-height: 70px;
       }
       label{
           margin: 0 40px 0 0;
           font-size: 26px;
           line-height: 70px;
           display: none;
           float: right;
       }
       #toggle{
           display: none;
           
       }
       
       
       
       @media only screen and (max-width: 500px){
         label{
           display: block;
           cursor: pointer;
}  
         .menu{
           text-align: center;
           width: 100%;
}
         .menu a{
           display: block;
           border-bottom: 1px solid #EAEAEB;
           margin: 0;
           background-color: white;
}
          toggle:hover + .menu{
           display: block;
}
       }
        </style>
    </head>
    <body>
    <div class="menu-1">
    
        <p><span id="aut">Autor:</span><span id="klik"><em><strong> JAKUB<BR>WITKOWSKI</strong></em></span></p>
         </div>
         
         
         
         
         
        
        <div class="nav"> 
         <label for="toggle"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/VisualEditor_-_Icon_-_Menu.svg/1024px-VisualEditor_-_Icon_-_Menu.svg.png"></label>
         <input type="checkbox" id="toggle">
         <div class="menu">
      <a href="https://witas-w.github.io/Aktualnosci/">Aktualności</a>
            <a href="https://witas-w.github.io/Bloguje-witas/">Blog</a>
            <a href="https://witas-w.github.io/Galeria-zdjec/">Zdjęcia</a>
     </div>  
        
     </div>    
       
       <img id="img" src="https://s6.ifotos.pl/img/3E431C6E-_qseaxrr.jpg"> 
        
        <div id="lokiter">
         <h3 id="akt">Aktualności</h3>
         <p>Obecnie jestem na wakacjach w Ustce. Ustka to miejscowość w województwie Pomorskim w powiecie Słupskim w gminie Ustka. Położona jest ona nad ujściem rzeki Słupii do morza Bałtyckiego.</p>
        </div>
       
   
 
    </body>
</html>
