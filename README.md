# 💻 Importante do Front-End

Repositório de consulta rápida com estruturas essenciais, truques e snippets de **HTML**, **CSS** e **JavaScript** para desenvolvimento web (menus, cards, responsividade e eventos).

---

## 📑 Índice
1. [Base HTML](#1-base-html)
2. [Base CSS](#2-base-css)
3. [Menu NavBar](#3-menu-navbar)
4. [Media Queries (Responsividade)](#4-media-queries-responsividade)
5. [Cards com Flexbox](#5-cards-com-flexbox)
6. [Eventos em JavaScript](#6-eventos-em-javascript)

---

## 1. Base HTML
Estrutura semântica inicial de uma página web.

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="keywords" content="">
    <meta name="author" content="">
    <title>Título da Página</title>
    <link rel="stylesheet" href="style/style.css">
  </head>
  <body>
    <div id="container">

      <nav>
        <!-- Menu de navegação -->
      </nav>  
      
      <header>
        <h1>Título Principal</h1>
      </header>
      
      <main>
        <section id="" class="">
          <!-- Conteúdo principal -->
        </section>
      </main>
      
      <footer>
        <!-- Rodapé -->
      </footer>
      
    </div>
  </body>
</html>
```

---

## 2. Base CSS
Esqueleto inicial para estilização (salvar dentro de uma pasta chamada `style/style.css`).

```css
html {
  background-color: ;
  text-align: center;
  padding: 0;
  margin: 0;
}

#container {
  text-align: center;
  background-color: ;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: ;
  height: ;
}

nav, header, main, section, footer {
  width: ;
  height: ;
}
```

---

## 3. Menu NavBar

### HTML
```html
<nav class="navbar">
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Login</a></li>
    <li><a href="#">Sign up</a></li>
    <li><a href="#">Footer</a></li>
  </ul>
</nav>
```

### CSS
```css
.navbar ul {
  list-style-type: none;
  background-color: gray;
  padding: 0px;
  margin: 0px;
  overflow: hidden;
}

.navbar li {
  float: left;
}

.navbar a {
  color: white;
  text-decoration: none;
  padding: 15px;
  display: block;
  text-align: center;
}

.navbar a:hover {
  background-color: lightblue;
}
```

---

## 4. Media Queries (Responsividade)
Breakpoints padrão para adaptar o layout a diferentes tamanhos de tela (Mobile, Tablet e Desktop).

```css
/* Telas muito pequenas (Celulares até 575px) */
@media screen and (max-width: 575.98px) {
  /* Seu CSS aqui */
}

/* Telas pequenas (Celulares em paisagem >= 576px) */
@media screen and (min-width: 576px) { /* Sintaxe Tradicional */ }
@media (width >= 576px) { /* Sintaxe Moderna */ }

/* Telas médias (Tablets >= 768px) */
@media screen and (min-width: 768px) { /* Sintaxe Tradicional */ }
@media (width >= 768px) { /* Sintaxe Moderna */ }

/* Telas grandes (Notebooks/Desktops >= 992px) */
@media screen and (min-width: 992px) { /* Sintaxe Tradicional */ }
@media (width >= 992px) { /* Sintaxe Moderna */ }

/* Telas extra grandes (Monitores >= 1200px) */
@media screen and (min-width: 1200px) { /* Sintaxe Tradicional */ }
@media (width >= 1200px) { /* Sintaxe Moderna */ }
```

---

## 5. Cards com Flexbox

### HTML
```html
<div class="cardContainer">
  <div class="card">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPyt9o2vV7qbUzPXo1bet8BsmumaYMNWALTk29xdsx5A&s=10" alt="Imagem do Card">

    <div class="cardContent">
      <h3>Card Title</h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus harum aliquid ipsam.</p>
      <a href="#" class="btn">Read More</a>
    </div>
  </div>
</div>
```

### CSS
```css
.cardContainer {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 100px;
}

.card {
  width: 325px;
  background-color: aqua;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.2);
  margin: 20px;
}

.card img {
  width: 100%;
  height: auto;
}

.cardContent {
  padding: 16px;
}

.cardContent h3 {
  font-size: 28px;
  margin-bottom: 8px;
}

.cardContent p {
  color: #666;
  font-size: 15px;
  line-height: 1.3;
}

.cardContent .btn {
  display: inline-block;
  padding: 8px 16px;
  background-color: #333;
  text-decoration: none;
  border-radius: 4px;
  margin-top: 16px;
  color: #fff;
}
```

---

## 6. Eventos em JavaScript

### Evento de Clique Simples (`onclick`)
**HTML:**
```html
<button onclick="eventoClick()">Clique Aqui</button>

<!-- Lembre-se de importar o script antes de fechar o </body> -->
<script src="script.js"></script>
```

**JavaScript (`script.js`):**
```javascript
function eventoClick() {
  alert('Acionou um evento de Click');
}
```

### Mudar Cor de Fundo com Clique
**JavaScript:**
```javascript
function eventoClick() {
  alert('Acionou um evento de Click');
  document.body.style.backgroundColor = "yellow";
}
```

### Evento de Clique Duplo (`ondblclick`)
**HTML:**
```html
<button ondblclick="eventodblClick()">Clique Duplo Aqui</button>
```

**JavaScript:**
```javascript
function eventodblClick() {
  alert('Acionou um evento de Click Duplo');
  document.body.style.backgroundColor = "green";
}
```
