# Les balises HTML partie 2

Le balise `<bdo>` (bidirectional override) et la balise <bdi> (bidirectional isolation) sont utilisées en HTML pour contrôler la direction du texte et isoler le texte de son contexte environnant, respectivement.

Voici une brève description de chaque balise :

`<bdo>` : Cette balise est utilisée pour spécifier la direction du texte de son contenu, en remplaçant la direction par défaut du texte. Elle peut prendre l'attribut dir, qui peut être défini sur ltr (de gauche à droite) ou rtl (de droite à gauche).
Voici un exemple d'utilisation de la balise `<bdo>` :

```html
<p>
  Ceci est une phrase écrite en français, mais la prochaine partie sera écrite
  en arabe :
</p>
<bdo dir="rtl">مرحبا بك في هذه الصفحة</bdo>
<p>Ceci est le reste de la phrase en français.</p>
```

La balise `<bdi>` (bidirectional isolation) est utilisée pour isoler des parties de texte qui peuvent être dans une direction différente de celle du texte environnant, de sorte que la direction du texte isolé n'affecte pas la direction du texte environnant. Elle peut être utilisée pour éviter le besoin d'éléments <bdo> explicites dans certains cas.
Voici un exemple d'utilisation de la balise `<bdi>`:

```html
<p>
  Ceci est une phrase écrite en français. Voici un nom qui peut être dans une
  langue différente :
</p>
<bdi>张三</bdi>
<p>Ceci est le reste de la phrase en français.</p>
```

La balise `<bdi>` est particulièrement utile lors de l'affichage de contenu généré par l'utilisateur, où vous pourriez ne pas connaître la direction du texte à l'avance.
