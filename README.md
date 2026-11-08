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


# Cards 

<div class="cardContainer">
          <div class="card">

            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPyt9o2vV7qbUzPXo1bet8BsmumaYMNWALTk29xdsx5A&s=10">

            <div class="cardContent">

              <h3>Card Title</h3>
              
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus harum aliquid ipsam</p>

              <a href="" class="btn">Read More</a>

            </div>
          </div>

         </div>

  .cardContainer{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 100px;
}

.card{
  width: 325px;
  background-color: aqua;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.2);
  margin: 20px;
}

.card img{
  width:100%;
  height: auto;
}

.cardContent{
  padding: 16px;
}

.cardContent h3{
  font-size: 28px;
  margin-bottom: 8px;
}

.cardContent p{
  color: #666;
  font-size: 15px;
  line-height: 1.3;
}

.cardContent .btn{
  display: inline-block;
  padding: 8px 16px;
  background-color: #333;
  text-decoration: none;
  border-radius: 4px;
  margin-top: 16px;
  color: #fff;
}



# evento onclick js


          <button onclick="eventoClick()">Clique Aqui</button>

         
          

        </section>
      </main>
      
      <footer>
        
      </footer>
      <script src="script.js"></script>
    </div>

function eventoClick(){
    alert('Acionou um evento de Click');
}


# mudar cor com onclick

function eventoClick(){
    alert('Acionou um evento de Click');
    document.body.style.backgroundColor = "yellow";
}

# Evento de Click Duplo

 <button ondblclick="eventodblClick()">Clique Aqui</button>

 function eventodblClick() {
    alert('Acionou um evento de Click Duplo');
    document.body.style.backgroundColor = "green";
}
    
