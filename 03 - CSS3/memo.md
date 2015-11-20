
## Feuille de style ##

**blog.html**
```css
<head>
  <meta charset="utf-8">
  <title>Mon site à la menthe</title>
  <meta description="Le blog de mon super site sur la menthe">
  <link rel="stylesheet" href="style.css">
</head>
```

**style.css**
```css

element{
  propriete-1:valeur-1;
  propriete-2:valeur-2;
  ...
}

h1{color:red;}
```

## Couleurs ##

**style.css**
```css
h1{
  color:red;
  color:#FF0000;
  color:rgb(255,0,0);

  background-color: black;
}
```

```css
h1{color: #113F2A;}

h2{
  color:#8EC9A5;
  background-color:#D0F2DD;
}

p{color:#555;}

a{color:#25A95C;}

```

```css
p{
  color:#555;
  color:rgb(255,0,0) !important;
  color:blue;
}
```

## Les identifiants ##

**style.css**
```css
h1{color: #113F2A;}

h2{
  color:#8EC9A5;
  background-color:#D0F2DD;
}

h2#top{
  color: #E54F04;
  background-color: #FC9764;
}

p{color:#555;}

a{color:#25A95C;}
```

**blog.html**
```html
<h2 id="top">L'histoire de la menthe</h2>
```

## Les classes ##

**blog.html**
```html
<p class="resume">
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
</p>
```

**style.css**
```css
p.resume{
  background-color: #EEE; 
}
```

Différences Classes et Identifiants


## Les tailles ##

**style.css**
```css
header{
  background-color: #EEE;

  width: 1020px;
}

section{
  width: 1020px;
}

footer{
  background-color: #EEE;

  width: 1020px;
  height: 110px;
}

```

## Les commentaires ##

**style.css**
```css
/*
 * GÉNÉRIQUE
 */

h1 {
  color: #113F2A;
}

h2 {
  color:#8EC9A5;
  background-color:#D0F2DD;
}

p {
  color:#555;
}

a {
  color:#25A95C;
}

section {
  background-color: #EEE;
  width: 1020px;
}

#conteneur {
  background-color: #FFF;
}

footer {
  height: 110px;
}


/*
 * BLOG
 */

#top{
  color: #E54F04;
  background-color: #FC9764;
}

p.resume{
  background-color: #EEE;
}

```

## Les layouts ##

**layout.html**
```html
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="utf-8">
    <title><!--Titre de la page--></title>
    <meta description="<!--Description de la page-->">
    <link rel="stylesheet" href="style.css">
  </head>

  <body>
    <!--Haut de page-->
    <section>
      <header>
        <img src="images/logo.png" alt="logo du site">

        <nav>
          <ul>
            <li><a href="accueil.html">Bienvenue</a></li>
            <li><a href="blog.html">Blog</a></li>
          </ul>
        </nav>
      </header>
    </section>

    <!--Section principale de la page-->
    <section id="conteneur">
      <!--Contenu de la page ... -->
    </section>

    <!--Pied de page-->
    <section>
      <footer>
        copyright &copy; minters 2015
      </footer>
    </section>

  </body>
</html>
```

**style.css**
```css
/*
 * GÉNÉRIQUE
 */

h1 {
  color: #113F2A;
}

h2 {
  color:#8EC9A5;
  background-color:#D0F2DD;
}

p {
  color:#555;
}

a {
  color:#25A95C;
}

/*
 * LAYOUT
 */

section {
  background-color: #EEE;
  width: 1020px;
}

#conteneur {
  background-color: #FFF;
}

footer {
  height: 110px;
}

/*
 * BLOG
 */

#top{
  color: #E54F04;
  background-color: #FC9764;
}

p.resume{
  background-color: #EEE;
}

```

## Liste d'articles ##

**blog.html**
```html
    <!--Section principale de la page-->
    <section id="conteneur">
      <h1 title="Le plus gros titre de ma page">Mes articles</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi vel accusamus maiores molestias obcaecati, commodi tempora aperiam quo sunt laudantium. Accusamus repellendus dolor maxime neque incidunt, blanditiis ipsum, perferendis repellat.
      </p>
      <hr>

      <!--Liste résumé des articles de mon blog-->
      <div class="resume">
        <h2 id="top">L'histoire de la menthe</h2>
        <img src="images/mint.jpg" alt="Feuille de menthe">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
        </p>
        <a href="articles/article-3.html">Lire la suite &rarr;</a>
      </div>

      <div class="resume">
        <h2>Un dessert très frais</h2>
        <img src="images/mint-2.jpg" alt="Dessert à la menthe">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
        </p>
        <a href="articles/article-2.html">Lire la suite &rarr;</a>
      </div>

      <div class="resume">
        <h2>Les bonbons mythiques</h2>
        <img src="images/mint-3.jpg" alt="Bonbons à la menthe">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
        </p>
        <a href="articles/article-3.html">Lire la suite &rarr;</a>
      </div>
    </section>
```
**style.css**
```css
/*
 * BLOG
 */
/**Liste**/

#top{
  color: #E54F04;
  background-color: #FC9764;
}

.resume{
  width: 450px;
}

.resume h2{
  background-color:#D0F2DD;
}

.resume p{
  background-color: #EEE; 
}


/**Articles**/
```

## Image de style ##

**style.css**
```css
/*
 * GÉNÉRIQUE
 */

body{
  background: url(images/fond.png);
}
```

## Les fonts ##

**style.css**
```css
p{
  color:#555;
  font-family: 'arial', 'helvetica', 'sans-serif';
}
```

```css
@font-face {
    font-family: 'caviar';
    src: url('fonts/CaviarDreams-webfont.eot');
    src: url('fonts/CaviarDreams-webfont.eot?#iefix') format('embedded-opentype'),
         url('fonts/CaviarDreams-webfont.woff') format('woff'),
         url('fonts/CaviarDreams-webfont.ttf') format('truetype'),
         url('fonts/CaviarDreams-webfont.svg#caviar_dreamsregular') format('svg');
    font-weight: normal;
    font-style: normal;
}
```

## Le reset ##

**style.css**
```css

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
```

## Font size ##

**style.css**

```css
h1{
  color: #113F2A;
  font-family: 'caviar';
  font-size: 50px;
}

h2{
  color:#8EC9A5;
  background-color:#D0F2DD;
  font-family: 'caviar';
  font-size: 30px;
}

p{
  color:#555;
  font-family: 'arial', 'helvetica', 'sans-serif';
  font-size: 16px;
}

#top{
  color: #E54F04;
  background-color: #FC9764;
  font-size: 35px;
}

```

## Padding Margin ##

**style.css**
```css
/*
 * BLOG
 */

 /**Liste**/

.infobar {
  background-color: yellow;
  padding: 20px 10px;
}

.resume{
  background-color: yellow;
  width: 450px;
  margin: 30px 30px 0 30px;
}
```

## Margin auto ##

**style.css**
```css
#enveloppe{
  width: 1020px;
  margin: 30px auto;
}
```

**blog.html**
```css
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="utf-8">
    <title>Mon site à la menthe</title>
    <meta description="Le blog de mon super site sur la menthe">
    <link rel="stylesheet" href="style.css">
  </head>

  <body>

    <div id="enveloppe">

      <!--Haut de page-->
      <section>
        <header>
          <img src="images/logo.png" alt="logo du site">

          <nav>
            <ul>
              <li><a href="accueil.html">Bienvenue</a></li>
              <li><a href="blog.html">Blog</a></li>
            </ul>
          </nav>
        </header>
      </section>

      <!--Section principale de la page-->
      <section id="conteneur">

        <div class="infobar">
          <h1>Mes articles</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi vel accusamus maiores molestias obcaecati, commodi tempora aperiam quo sunt laudantium. Accusamus repellendus dolor maxime neque incidunt, blanditiis ipsum, perferendis repellat.
          </p>
        </div>



        <!--Liste résumé des articles de mon blog-->
        <div class="resume">
          <h2 id="top">L'histoire de la menthe</h2>
          <img src="images/mint.jpg" alt="Feuille de menthe">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
          </p>
          <a href="articles/article-1.html">Lire la suite &rarr;</a>
        </div>

        <div class="resume">
          <h2>Un dessert très frais</h2>
          <img src="images/mint-2.jpg" alt="Dessert à la menthe">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
          </p>
          <a href="articles/article-2.html">Lire la suite &rarr;</a>
        </div>

        <div class="resume">
          <h2>Les bonbons mythiques</h2>
          <img src="images/mint-3.jpg" alt="Bonbons à la menthe">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod aperiam, dignissimos non ea harum perferendis...
          </p>
          <a href="articles/article-3.html">Lire la suite &rarr;</a>
        </div>
      </section>

      <!--Pied de page-->
      <section>
        <footer>
          <span>copyright &copy; minters 2015</span>
        </footer>
      </section>
      

    </div>  

  </body>
</html>



```


