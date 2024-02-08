# Les balises HTML

Les balises HTML sont des éléments essentiels pour la création de pages web. Elles sont utilisées pour définir la structure de la page, le contenu, le style, et bien plus encore. Les balises HTML sont encadrées par des chevrons "<" et ">" et peuvent contenir des attributs qui fournissent des informations supplémentaires sur la balise.

Ce cours sur les balises HTML va passer en revue les principales balises HTML, leurs utilisations et leurs attributs. Nous allons également aborder les meilleures pratiques pour écrire un code HTML valide et accessible, ainsi que les techniques de débogage pour résoudre les erreurs courantes en HTML.

En utilisant les balises HTML, les développeurs web peuvent créer des pages web bien structurées et accessibles qui offrent une expérience utilisateur optimale. Ce cours est destiné à tous ceux qui souhaitent apprendre à créer des pages web en utilisant des balises HTML, qu'ils soient débutants ou qu'ils aient déjà une expérience en développement web.

## Le document HTML

1. `<!DOCTYPE html>` : Cette balise est utilisée pour indiquer le type de document utilisé, ici une page HTML.

2. `<html>` : Cette balise est utilisée pour définir le début et la fin de la page HTML.

3. `<head>` : Cette balise contient les informations qui ne sont pas affichées sur la page web, mais qui sont importantes pour la conception de la page, telles que le titre de la page, les balises méta, les scripts, etc.

4. `<meta>` : Ces balises contiennent des informations sur la page, telles que la description, les mots-clés, l'auteur, etc.

5. `<title>` : Cette balise est utilisée pour définir le titre de la page qui s'affiche dans l'onglet du navigateur.

6. `<body>` : Cette balise est utilisée pour définir le corps de la page HTML, qui contient tout le contenu visible sur la page.

   ![04-balise du document html](./../19-fichiers/04-html.png)

## Les balises de contenu

### Les balises de titre

Les balises de titre (ou "heading tags" en anglais) sont utilisées pour définir la hiérarchie du contenu dans une page web. Il existe six niveaux de balises de titre en HTML, allant de h1 (le titre principal) à h6 (le titre le moins important). Voici un exemple d'utilisation de ces balises:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Exemple d'utilisation des balises de titre</title>
  </head>
  <body>
    <h1>Titre principal de la page</h1>
    <p>Ce paragraphe contient du texte sur le sujet principal de la page.</p>

    <h2>Sous-titre 1</h2>
    <p>Ce paragraphe contient des informations sur le sous-sujet 1.</p>

    <h3>Sous-sous-titre 1</h3>
    <p>
      Ce paragraphe contient des informations plus spécifiques sur le sous-sujet
      1.
    </p>

    <h2>Sous-titre 2</h2>
    <p>Ce paragraphe contient des informations sur le sous-sujet 2.</p>

    <h3>Sous-sous-titre 2</h3>
    <p>
      Ce paragraphe contient des informations plus spécifiques sur le sous-sujet
      2.
    </p>

    <h4>Sous-sous-sous-titre 1</h4>
    <p>
      Ce paragraphe contient des informations encore plus spécifiques sur le
      sous-sujet 2.
    </p>

    <h2>Sous-titre 3</h2>
    <p>Ce paragraphe contient des informations sur le sous-sujet 3.</p>
  </body>
</html>
```

le résultat est le suivant dans le navigateur:
![les titres](./../19-fichiers/05-titres.png)

### Les paragraphes

Les balises de paragraphe en HTML permettent de délimiter le texte en paragraphes distincts et faciliter la lecture et la compréhension du contenu. Voici un exemple d'utilisation des balises de paragraphe en HTML :

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Exemple d'utilisation des balises de paragraphe</title>
  </head>
  <body>
    <h1>Titre principal</h1>
    <p>
      Ce paragraphe contient du texte sur le sujet principal de la page. Le
      texte est séparé en paragraphes pour faciliter la lecture et la
      compréhension du contenu.
    </p>

    <p>
      Un autre paragraphe peut contenir des informations supplémentaires sur le
      sujet principal ou sur un sous-sujet spécifique.
    </p>

    <h2>Sous-titre</h2>
    <p>
      Le sous-titre peut être utilisé pour décrire plus en détail le sujet
      principal, ou pour présenter un sujet secondaire.
    </p>

    <p>
      Un autre paragraphe peut fournir des exemples ou des explications plus
      détaillées sur le sujet.
    </p>

    <h3>Sous-sous-titre</h3>
    <p>
      Le sous-sous-titre peut être utilisé pour fournir des informations plus
      spécifiques sur un sujet ou un point particulier.
    </p>

    <p>
      Un autre paragraphe peut décrire un exemple ou une situation particulière
      pour illustrer le point présenté.
    </p>
  </body>
</html>
```

**le résultat est le suivant:**
![les paragraphes](./../19-fichiers/06-paragraphe.png)

Les balises de paragraphe sont utilisées pour délimiter les différents paragraphes de texte. Cela facilite la lecture et la compréhension du contenu, en permettant aux lecteurs de distinguer facilement les différents points de la page.

### D'autres balises

Les balises HTML sont aussi utilisées pour formater le texte et ajouter des éléments tels que des sauts de ligne et des séparateurs. Voici un aperçu des différentes balises utilisées pour formater le texte en HTML :

La balise "b" est utilisée pour mettre en gras le texte. Par exemple :
`<b>Texte en gras</b>`.
La balise "i" est utilisée pour mettre en italique le texte. Par exemple :
`<i>Texte en italique</i>`.
La balise "big" est utilisée pour agrandir la taille du texte. Par exemple :
`<big>Texte plus grand</big>`.
La balise "small" est utilisée pour réduire la taille du texte. Par exemple :
`<small>Texte plus petit</small>`.
La balise "sub" est utilisée pour afficher le texte en indice (en dessous de la ligne de base). Par exemple :
`<sub>Texte en indice</sub>` ou dans ce cas `H<sub>2</sub>O`.
La balise "sup" est utilisée pour afficher le texte en exposant (au-dessus de la ligne de base). Par exemple : `<sup>Texte en exposant</sup>`.
La balise "br" est utilisée pour insérer un saut de ligne. Par exemple : `Première ligne<br>Deuxième ligne`.
La balise "hr" est utilisée pour insérer une ligne horizontale. Par exemple : `<hr>`.
Voici un exemple de code HTML montrant l'utilisation de ces balises :

```html
<!DOCTYPE html>
<html>
  <head>
    <title>
      Exemple d'utilisation des balises de formatage de texte en HTML
    </title>
  </head>
  <body>
    <p>
      Ceci est un <b>texte en gras</b> et ceci est un <i>texte en italique</i>.
    </p>

    <p>
      Ceci est un <big>texte plus grand</big> et ceci est un
      <small>texte plus petit</small>.
    </p>

    <p>Ceci est la molécule H<sub>2</sub>O et ceci est un a<sup>3</sup>.</p>

    <p>Ceci est la première ligne<br />et ceci est la deuxième ligne.</p>

    <hr />

    <p>
      Ceci est un exemple d'utilisation des balises de formatage de texte en
      HTML.
    </p>
  </body>
</html>
```

**le résultat est le suivant:**

![autres balises](./../19-fichiers/07-autresbalise.png)
Ces balises sont très utiles pour améliorer la lisibilité et la compréhension du contenu de la page. Cependant, il est important de ne pas abuser de ces balises et de les utiliser avec parcimonie, car un texte surchargé de balises peut rendre le contenu difficile à lire et à comprendre.
