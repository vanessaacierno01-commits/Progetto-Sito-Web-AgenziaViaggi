# DreamTravel (Travelya) - Sito web per agenzia viaggi
## Indice

1. [Introduzione](#introduzione)
2. [Struttura HTML](#struttura-html)
3. [CSS e Layout](#css-e-layout)
3. [Hero e navigazione](#Hero e navigazione)
4. [Sezioni principali](#Sezioni principali)
4. [Form di contatto](#Form di contatto)
4. [Footer e social](#Footer e social)


## Introduzione
DreamTravel (Travelya) è un sito vetrina responsive per un’agenzia di viaggi. Realizzato interamente in HTML e CSS, mostra destinazioni popolari, offerte speciali e un form di contatto per richieste personalizzate.

## Struttura HTML 

<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DreamTravel</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>...</header>
<section id="about">...</section>
<section id="destinations">...</section>
<section id="offers">...</section>
<section id="contact">...</section>
<footer>...</footer>
</body>
</html>

### Analisi della Struttura

- **`<header>`**:Contiene il logo, la navigazione e la sezione hero iniziale con titolo e pulsante
- **`<section id="about">`**: Spiega chi è l’agenzia e i suoi valori
- **`<section id="destinations"`**: Presenta le destinazioni popolari con immagini e descrizioni
- **`<section id="offers">`**: Elenca le offerte speciali con pulsanti di presentazione
- **`<section id="contact">`**: Modulo di contatto per comunicare con l'agenzia
- **`<footer>`**: Piè di pagina

## CSS e Layout

### Reset e Base Styling

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {

    font-family: 'Montserrat', sans-serif;

    color: #2a2a2a;

    line-height: 1.6;

    background-color: #f9f9f9;
}
```
## Hero e Navigazione

<header>
<nav>
<div class="logo">Travelya</div>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">Chi siamo</a></li>
<li><a href="#destinations">Destinazioni</a></li>
<li><a href="#offers">Offerte</a></li>
<li><a href="#contact">Contatti</a></li>
</ul>
</nav>
<div class="hero">
<h1>Scopri il mondo con noi</h1>
<p>Esperienze uniche, viaggi su misura e ricordi indimenticabili</p>
<a href="#offers" class="btn">Scopri le Offerte</a>
</div>
</header>

### Analisi della struttura 
- **`<nav>`**:barra navigazione con logo e link principali
- **`<.hero>`**: sezione introduttiva con frase e pulsante
- **`<btn">`**: pulsante con effetto hover

## Sezioni principali
### About
### Destinations
### Offers 
### Strattura Aboout Destinations e Offers

<section id="about">
<div class="container">
<h2>Chi siamo</h2>
<p>Agenzia che trasforma sogni in esperienze reali.</p>
</div>
</section>

<section id="destinations">
<div class="container">
<h2>Alcune delle nostre destinazioni</h2>
<div class="grid">
<article>...</article>
<article>...</article>
...
</div>
</div>
</section>

<section id="offers">
<div class="container">
<h2>In Offerta Speciale abbiamo:</h2>
<div class="grid">
<article>...</article>
</div>
</div>
</section>

## Form di contatto
### Struttura

<section id="contact">
<form>
<input type="text" placeholder="Il tuo nome" required>
<input type="email" placeholder="La tua email" required>
<textarea placeholder="Il tuo messaggio" required></textarea>
<button type="submit">Invia</button>
</form>
</section>


## Footer e Social
### Struttura

<footer>
<p>2025 Travelya.</p>
<div class="social">
<a href="#">Instagram</a>
<a href="#">Facebook</a>
<a href="#">TikTok</a>
</div>
</footer>

