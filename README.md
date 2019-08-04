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
           height: 30px;
           line-height: 30px;
           right: 0px;
           top: 20px;
           z-index: 3;
       }
       .menu{
         margin-right: 30px;  
       }
       .menu a{
           clear: right;
           text-decoration: none;
           color: black;
           position: relative;
           line-height: 40px;
           margin-right: 30px; 
       }
       label{
           position: absolute;
           font-size: 26px;
           line-height: 40px;
           display: none;
           width: 26px;
           right: 10px;
           
       }
       #toggle{
           display: none;
           top: 10px;
           right: 10px;
       }
       
       
       
       @media only screen and (max-width: 500px){
         label{
          
           
          
           display: block;
           cursor: pointer;
}  
         .menu{
           display: none;
           text-align: center;
           width: 400px;
          position: relative;
          top: 25px;
          right: 0px;
          left: 0px;
           margin-right: 0px;
}
         .menu a{
           display: block;
           width: 400px;
           text-decoration: none; 
           border-bottom: 1px solid black;
           margin: 0;
           color: black;
           background-color: white;
           top: 25px;
           right: 0px;
           left: 0px;
            text-align: center;
          }
          
          #toggle:checked + .menu {
          display: block;
}
       }
       a:hover{
          background-color: red;
          color: white;
       }
       a:active{
          background-color: red;
           color: white;
       }
     
        </style>
    </head>
    <body>
    <div class="menu-1">
    
        <p><span id="aut">Autor:</span><span id="klik"><em><strong> JAKUB<BR>WITKOWSKI</strong></em></span></p>
         </div>
         
         
         
         
         
        
        <div class="nav"> 
         <label for="toggle">&#9776;</label>
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
