<!DOCTYPE html>
<html>
<head>
   <title> Bienvenido a Netflix</title>
   <link rel="stylesheet" href="Style Bienvenido.css" />
   <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@400;700&family=Open+Sans:wght@500&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@900&family=Roboto:wght@900&display=swap" rel="stylesheet">

</head>
<body>
<div class="contenedor">

   <header> 
      <h1>Netflix</h1> 
      <form>
         <select class="idioma" name="idioma">

            <option>Español</option>
            
            <option>Ingles</option>
                        
            </select>

            <input class="inicio" type="submit" value="Iniciar sesion">
         
      </form>
   </header>
   <h2 class="text 1">Películas y series sin límites y mucho más</h2>
   <h3 class="text 2">Disfruta donde quieras. Cancela cuando quieras</h3>
   <h4 class="text 3">¿Quieres ver algo ya? Escribe tu dirección de correo para crear una suscripción a Netflix o reactivarla.</h4>
<form class="empezar">

   <input type="email" required>

   <input type="submit" value="Empezar >">

</form>
  
</div>

</body>
</html>




And the css code 


h1{
    font-family: 'Bebas Neue', sans-serif;
    font-size: 75px;
    color: red;
    margin: 30px 100px;
}

body{
    background-image: linear-gradient(
       rgba(0,0,0,0),
       rgba(0,0,0,0.6)
    ), url("https://www.teknofilo.com/wp-content/uploads/2021/06/Netflix-1280x720.jpg");    
    background-repeat: no-repeat;
    background-size: cover;
    color: aliceblue;
}

h2{
    font-family: 'Roboto', sans-serif; 
    text-align: center;
    font-size: 50px;
    font-weight: bold;
    margin-top: 150px;
    margin-bottom: 0%;
    
}

h3{
    font-family: 'Roboto', sans-serif;
    text-align: center;
    font-size: 30px;
    font-weight: 300;
    margin-top: 10px;
}

h4{
    font-family: 'Roboto', sans-serif;
    text-align: center;
    font-size: 25px;
    font-weight: 300;
    margin-top: 50px ;
}




.idioma{
    position: absolute;
    text-align: right;
    top: 50px;
    left: 1200px;
}

.inicio{
    position: absolute;
    text-align: right;
    top: 50px;
    left: 1300px;
}

.empezar{
    text-align: center;

}
