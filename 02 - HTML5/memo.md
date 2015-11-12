# Etapes

## Table of Contents
  1.  [Hello world](#hello-world)
  1.  [Balises](#balises)
  1.  [Balises existantes](#balises-existantes)
  1.  [Les titres](#les-titres)  
  1.  [Les attributs](#les-attributs)
  1.  [Les liens](#les-liens) 
  1.  [Liens relatifs et absolus](#liens-relatifs-et-absolus) 


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
