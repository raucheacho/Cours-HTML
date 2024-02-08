# INTRODUCTION

## Pourquoi devriez vous prendre ce cours

Si vous êtes intéressé par la création de pages web, ce cours de **HTML** pour débutants est fait pour vous. Nous avons conçu ce cours pour vous aider à apprendre les bases du **HTML**, y compris les balises, les attributs et les valeurs, ainsi que les styles CSS pour personnaliser l'apparence de votre page. Nous vous guiderons à travers les différentes étapes, de l'introduction à la structure de base d'un document **HTML** à la création d'une page **HTML** simple, puis à l'exploration des différentes balises **HTML** pour structurer votre contenu.

Grâce à ce cours, vous apprendrez comment créer vos propres pages web et acquérir les compétences nécessaires pour les personnaliser selon vos préférences. Que vous soyez un étudiant, un professionnel ou simplement intéressé par la création de pages web, ce cours est la première étape pour développer vos compétences en **HTML**.

## Qu'est-ce que vous allez apprendre

Ce cours de **HTML** pour débutants vous permettra de découvrir les fondamentaux de ce langage de balisage et de vous familiariser avec les concepts clés nécessaires pour créer des pages web. Nous débuterons par une introduction à la structure de base d'un document **HTML**, suivi d'un guide sur la création de votre première page **HTML**. Ensuite, nous aborderons les différentes balises **HTML** disponibles pour structurer votre contenu, ainsi que les styles CSS pour personnaliser l'apparence de votre page. Enfin, nous vous montrerons comment tester et valider votre code **HTML** pour vous assurer qu'il est bien structuré et compatible avec les différents navigateurs web.

Que vous soyez débutant ou que vous souhaitiez approfondir vos connaissances en **HTML**, ce cours vous fournira les bases nécessaires pour vous lancer dans la création de vos propres pages web, que ce soit pour un site personnel ou professionnel.

## C'est quoi le HTML

Le HTML (Hypertext Markup Language) est un langage de balisage utilisé pour créer des pages web. Imaginez que vous écriviez une lettre à un ami. Vous commencez par écrire votre nom, la date et l'objet de votre lettre en haut de la page. Ensuite, vous écrivez votre message en utilisant des paragraphes, des titres et des sous-titres pour organiser votre contenu. Le HTML fonctionne de la même manière, mais pour les pages web !

Le HTML permet de structurer et de mettre en forme le contenu d'une page web en utilisant des balises. Les balises sont des éléments de code qui indiquent au navigateur web comment afficher le contenu de la page. Par exemple, la balise **h1** indique au navigateur de faire apparaître un titre principal en gros caractères, tandis que la balise **p** indique que le contenu qui suit doit être affiché comme un paragraphe.

Voici un exemple de code HTML pour créer une page web simple :

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Ma page web</title>
  </head>
  <body>
    <h1>Bienvenue sur ma page web !</h1>
    <p>Voici un paragraphe de texte.</p>
    <img src="mon_image.jpg" alt="Une image">
  </body>
</html>
```

Le HTML est utilisé pour créer des pages web, et est un élément essentiel pour la plupart des sites internet populaires. Par exemple, Amazon utilise le HTML pour structurer et afficher les informations sur ses produits, tandis que YouTube utilise le HTML pour afficher les vidéos et les commentaires des utilisateurs.
Pour créer un petit site eCommerce avec HTML et CSS, vous pouvez suivre les étapes suivantes :

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Ma boutique en ligne</title>
  </head>
  <body>
    <h1>Ma boutique en ligne</h1>

    <div class="product">
      <img
        style="width: 300px"
        src="https://images.unsplash.com/photo-1449247709967-d4461a6a6103?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1742&q=80"
      />
      <h2>Produit 1</h2>
      <p>Description du produit 1.</p>
      <div class="price">2000FCFA</div>
    </div>

    <div class="product">
      <img
        style="width: 300px"
        src="https://images.unsplash.com/photo-1493723843671-1d655e66ac1c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80"
      />
      <h2>Produit 2</h2>
      <p>Description du produit 2.</p>
      <div class="price">3000FCFA</div>
    </div>

    <div class="product">
      <img
        style="width: 300px"
        src="https://images.unsplash.com/photo-1675361771629-08cc12e21935?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80"
      />
      <h2>Produit 3</h2>
      <p>Description du produit 3.</p>
      <div class="price">KDO 😋</div>
    </div>
  </body>
</html>

```

Le resultat suivant sera affiché dans le navigateur:
![0-resultat navigateur sans css](https://raw.githubusercontent.com/raucheacho/Cours-HTML/main/19-fichiers/0-resultat.png)

Le code HTML pour le site ecommerce avec les produits peut être amélioré en ajoutant du CSS pour donner un aspect plus esthétique et professionnel à la page voir l'image suivante.

![1-resultat navigateur avec css](https://raw.githubusercontent.com/raucheacho/Cours-HTML/main/19-fichiers/1-resultat.png)
