# Etapes

## Table of Contents
  1.  [Hello world](#hello-world)
  1.  [Balises](#balises)
  1.  [Balises existantes](#balises-existantes)
  1.  [Les titres](#les-titres)  
  1.  [Les attributs](#les-attributs)
  1.  [Les liens](#les-liens) 
  1.  [Liens relatifs et absolus](#liens-relatifs-et-absolus)
  1.  [Les images](#les-images)
  1.  [S'organiser](#s-organiser)
  1.  [Structure de page](#structure-de-page)  
  1.  [Le head](#le-head) 
  1.  [Balises structurantes](#balises-structurantes) 
  1.  [Indentation](#indentation)
  1.  [Commentaires](#commentaires) 
  1.  [Accueil](#accueil)
  1.  [Caractères spéciaux](#caractères-spéciaux)   


## Hello world ##

**page.html**
```html
hello world !
```

## Balises ##

**page.html**
```html
<balise>Contenu de ma balise</balise>
```

## Balises existantes ##

**page.html**
```html
<h1>Mon super titre</h1>
<p>Mon <strong>super</strong> paragraphe de blog</p>
```

## Les Titres ##

**page.html**
```html
<h1>Mon hyper gros titre</h1>
<h2>Mon super gros titre</h2>
<h3>Mon gros titre</h3>
<h4>Mon titre normale</h4>
<h5>Mon sous-titre</h5>
<h6>Mon plus petit titre</h6>
<p>Mon <strong>super</strong> paragraphe de blog</p>

```

## Les Attributs ##

**page.html**
```html
<h1 title="Le plus gros titre de ma page">Mon hyper gros titre</h1>
<h2>Mon super gros titre</h2>
<h3>Mon gros titre</h3>
<h4>Mon titre normale</h4>
<h5>Mon sous-titre</h5>
<h6>Mon plus petit titre</h6>
<p>Mon <strong>super</strong> paragraphe de blog</p>

```

## Les Liens ##

**blog.html**
```html
<h1 title="Le plus gros titre de ma page">Mes articles</h1>

<h2>Mon titre de blog</h2>
<p>Voici le résumé d'un super <a href="article.html">article</a> de blog disponible sur <a href="www.google.fr">google</a></p>
```

**article.html**
```html
<h1>Mon article</h1>

<p>Tous mon article de blog</p>
```

## Liens relatifs et absolus ##

**blog.html**
```html
<h1 title="Le plus gros titre de ma page">Mes articles</h1>

<h2>Un super article</h2>
<p>Voici le résumé d'un super <a href="articles/article-1.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Un très bon article</h2>
<p>Voici le résumé d'un très bon article <a href="articles/article-2.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Un article génial</h2>
<p>Voici le résumé d'un très bon article <a href="articles/article-3.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>
```

**articles/article-1.html**
```html
<h1>Mon article 1</h1>

<p>Tous le contenu de mon article 1 ...</p>

<a href="../blog.html">Revenir aux articles</a>
```

## Les images ##

**blog.html**
```html
<h1 title="Le plus gros titre de ma page">Mes articles</h1>

<h2>L'histoire de la menthe</h2>
<img src="mint.jpg" alt="Feuille de menthe">
<p>Voici le résumé d'un super <a href="articles/article-1.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Un dessert très frais</h2>
<img src="mint-2.jpg" alt="Dessert à la menthe">
<p>Voici le résumé d'un très bon article <a href="articles/article-2.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Les bonbons mythiques</h2>
<img src="mint-3.jpg" alt="Bonbons à la menthe">
<p>Voici le résumé d'un très bon article <a href="articles/article-3.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>
```

## S'organiser ##

**blog.html**
```html
<h1 title="Le plus gros titre de ma page">Mes articles</h1>

<h2>L'histoire de la menthe</h2>
<img src="images/mint.jpg" alt="Feuille de menthe">
<p>Voici le résumé d'un super <a href="articles/article-1.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Un dessert très frais</h2>
<img src="images/mint-2.jpg" alt="Dessert à la menthe">
<p>Voici le résumé d'un très bon article <a href="articles/article-2.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Les bonbons mythiques</h2>
<img src="images/mint-3.jpg" alt="Bonbons à la menthe">
<p>Voici le résumé d'un très bon article <a href="articles/article-3.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>
```

**articles/article-1.html**
```html
<h1>Mon article 1</h1>
<img src="../images/mint.jpg" alt="Feuille de menthe">
<p>Tous le contenu de mon article 1 ...</p>
```

## Structure de page ##

**structure.html**
```html
<!DOCTYPE html>
<html>
<head>
<title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Le Head ##

**blog.html**
```html
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<title>Mon site à la menthe</title>
<meta description="Le blog de mon super site sur la menthe">
</head>
<body>

<h1 title="Le plus gros titre de ma page">Mes articles</h1>

<h2>L'histoire de la menthe</h2>
<img src="images/mint.jpg" alt="Feuille de menthe">
<p>Voici le résumé d'un super <a href="articles/article-1.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Un dessert très frais</h2>
<img src="images/mint-2.jpg" alt="Dessert à la menthe">
<p>Voici le résumé d'un très bon article <a href="articles/article-2.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

<h2>Les bonbons mythiques</h2>
<img src="images/mint-3.jpg" alt="Bonbons à la menthe">
<p>Voici le résumé d'un très bon article <a href="articles/article-3.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a></p>

</body>
</html>
```

## Balises structurantes ##

**blog.html**
```html
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<title>Mon site à la menthe</title>
<meta description="Le blog de mon super site sur la menthe">
</head>
<body>

<header>
<img src="images/logo.png" alt="logo du site">
</header>

<section>
<!-- code -->
</section>

<footer></footer>

</body>
</html>

```

## Indentation ##

**blog.html**
```html
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8">
        <title>Mon site à la menthe</title>
        <meta description="Le blog de mon super site sur la menthe">
    </head>

    <body>
        <header>
            <img src="images/logo.png" alt="logo du site">
        </header>

        <section>
            <h1 title="Le plus gros titre de ma page">Mes articles</h1>

            <h2>L'histoire de la menthe</h2>
            <img src="images/mint.jpg" alt="Feuille de menthe">
            <p>
                Voici le résumé d'un super <a href="articles/article-1.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a>
            </p>

            <h2>Un dessert très frais</h2>
            <img src="images/mint-2.jpg" alt="Dessert à la menthe">
            <p>
                Voici le résumé d'un très bon article <a href="articles/article-2.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a>
            </p>

            <h2>Les bonbons mythiques</h2>
            <img src="images/mint-3.jpg" alt="Bonbons à la menthe">
            <p>
                Voici le résumé d'un très bon article <a href="articles/article-3.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a>
            </p>
        </section>

        <footer>
            
        </footer>
    </body>
</html>
```

## Commentaires ##

**blog.html**
```html
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8">
        <title>Mon site à la menthe</title>
        <meta description="Le blog de mon super site sur la menthe">
    </head>

    <body>
        <!--Haut de page-->
        <header>
            <img src="images/logo.png" alt="logo du site">
        </header>


        <!--Section principale de la page-->
        <section>
            <h1 title="Le plus gros titre de ma page">Mes articles</h1>
            <hr>

            <!--Liste résumé des articles de mon blog-->
            <h2>L'histoire de la menthe</h2>
            <img src="images/mint.jpg" alt="Feuille de menthe">
            <p>
                Voici le résumé d'un super <a href="articles/article-1.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a>
            </p>

            <h2>Un dessert très frais</h2>
            <img src="images/mint-2.jpg" alt="Dessert à la menthe">
            <p>
                Voici le résumé d'un très bon article <a href="articles/article-2.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a>
            </p>

            <h2>Les bonbons mythiques</h2>
            <img src="images/mint-3.jpg" alt="Bonbons à la menthe">
            <p>
                Voici le résumé d'un très bon article <a href="articles/article-3.html">article</a> de blog disponible sur <a href="http://www.google.fr">google</a>
            </p>
        </section>

        <!--Pied de page-->
        <footer>
            
        </footer>
    </body>
</html>
```

## Accueil ##

**accueil.html**
```html
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="utf-8">
    <title>Mon site à la menthe</title>
    <meta description="Le blog de mon super site sur la menthe">
  </head>

  <body>
    <!--Haut de page-->
    <header>
      <img src="images/logo.png" alt="logo du site">

      <nav>
        <ul>
          <li><a href="accueil.html">Bienvenue</a></li>
          <li><a href="blog.html">Blog</a></li>
        </ul>
      </nav>
    </header>


    <!--Section principale de la page-->
    <section>
      <h1>Ma page d'accueil</h1>
    </section>

    <!--Pied de page-->
    <footer>

    </footer>
  </body>
</html>
```

## Caractères spéciaux ##

**blog.html**
```html
    <!--Pied de page-->
    <footer>
        copyright &copy; minters 2015
    </footer>
```



