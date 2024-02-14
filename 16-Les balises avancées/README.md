# Attributs spécifique de la balise command
1. `type` : Cet attribut détermine le type de commande ou de bouton. Les valeurs courantes peuvent inclure "command" pour une commande générique, "checkbox" pour une case à cocher, "radio" pour un bouton radio, etc.

2. `label` : Cet attribut spécifie le libellé associé à la commande ou au bouton. Il est généralement affiché pour indiquer à l'utilisateur ce que fait la commande.

3. `icon` : Cet attribut permet de spécifier une icône associée à la commande. L'icône est généralement affichée à côté du libellé pour fournir une indication visuelle de la fonction de la commande.

4. `disabled` : Cet attribut est un attribut booléen qui, lorsqu'il est présent, indique que la commande est désactivée, c'est-à-dire qu'elle ne peut pas être utilisée. Cela peut être utile pour indiquer à l'utilisateur qu'une commande n'est pas disponible dans certaines circonstances.

5. `checked` : Cet attribut est spécifique aux boutons de type "checkbox" ou "radio". Lorsqu'il est présent, il indique que la case à cocher ou le bouton radio est sélectionné par défaut.

6. `radiogroup` : Cet attribut est utilisé pour regrouper les boutons radio associés. Tous les boutons radio avec le même attribut `radiogroup` appartiennent au même groupe, et dans un groupe donné, un seul bouton peut être sélectionné à la fois. Cela permet de créer des groupes de boutons radio qui fonctionnent ensemble pour sélectionner une option parmi plusieurs.