# Importante-do-FrontEnd
Partes importantes de uma pagina web Front-End como Menus, Carrosséis e muito mais. 

# Base Html

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title></title>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style/style.css">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <meta name="author" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
    <div id="container">

      <nav>
        
      </nav>  
      
      <header>
        <h1></h1>
      </header>
      
      <main>
        <section id="" class="">

        </section>
      </main>
      
      <footer>
        
      </footer>
      
    </div>
  </body>
</html>


# Base Css

/* Dentre de uma Pasta Chamada Style*/

html{
  background-color: ;
  text-align: center;
  padding: 0;
  margin: 0;
}

#container{
  text-align: center;
  background-color: ;
  Display: ;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: ;
  Height: ;
}

nav{
  width: ;
  Height: ;
}

header{
 width: ;
 Height: ;
}

main{
 width: ;
 Height: ;
}

section{
 width: ;
 Height: ;
}

footer{
 width: ;
 Height: ;
}




# Menu NavBar 

Html 

<nav class="navbar">

        <ul>
          <li><a href="">Home</a></li>
          <li><a href="">Login</a></li>
          <li><a href="">Sign up</a></li>
          <li><a href="">footer</a></li>
        </ul>

      </nav>


Css 

.navbar ul{
  list-style-type: none;
  background-color: gray;
  padding: 0px;
  margin: 0px;
  overflow: hidden;
}

.navbar a{
  color: white;
  text-decoration: none;
  padding: 15px;
  display: block;
  text-align: center;
}

.navbar a:hover{
  background-color: lightblue;
}

.navbar li{
  float: left;
}

# Media Queries 

/* Telas até 575px */
@media screen and (max-width: 575.98px) {
  /* Seu CSS aqui */
}



/* Sintaxe Tradicional */
@media screen and (min-width: 576px) {
  /* Seu CSS aqui */
}

/* Sintaxe Moderna */
@media (width >= 576px) {
  /* Seu CSS aqui */
}


/* Sintaxe Tradicional */
@media screen and (min-width: 768px) {
  /* Seu CSS aqui */
}

/* Sintaxe Moderna */
@media (width >= 768px) {
  /* Seu CSS aqui */
}


/* Sintaxe Tradicional */
@media screen and (min-width: 992px) {
  /* Seu CSS aqui */
}

/* Sintaxe Moderna */
@media (width >= 992px) {
  /* Seu CSS aqui */
}


/* Sintaxe Tradicional */
@media screen and (min-width: 1200px) {
  /* Seu CSS aqui */
}

/* Sintaxe Moderna */
@media (width >= 1200px) {
  /* Seu CSS aqui */
}





@media screen and (max-width: 575.98px) {
  
}




@media screen and (min-width: 576px) {
  
}




@media screen and (min-width: 768px) {
  
}


@media screen and (min-width: 992px) {
  /* Seu CSS aqui */
}




@media screen and (min-width: 1200px) {
 
}
