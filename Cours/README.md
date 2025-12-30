# Atelier Expressions Régulières (aka Regex)

Les **expressions régulières** sont très utiles et très puissantes pour extraire les informations d'un texte quelconque, que ce soit du code, les logs d'un serveur ou les recettes de cuisine de votre grand-mère.

Concrètement, elles prennent la forme d'une suite de caractères, qui peut par exemple ressembler à ça : `.?.?([a-ZA-z0-9]+).*?` (*si, si, promis, c'est pas juste du texte tapé au hasard, c'est un vrai exemple où chaque caractère a son importance*) et qui va servir de modèle pour rechercher et localiser des bouts de texte spécifiques.

Pour rapidement résumer, elles permettent de transformer

- 500g de farine
- 4 oeufs
- 1 pincée de sel

en

```javaScript
[
    {ingredient:"farine", quantity: 500, units:"g"},
    {ingredient:"oeufs", quantity: 4},
    {ingredient:"sel", quantity: 1, units:"pincée"}
]
```

Les leçons suivantes ont pour but de vous familiariser avec l'utilisation pratique des expressions régulières afin de vous permettre de profiter de leur puissance au plus vite.

Commencez par parcourir les [leçons](lessons/00-introduction.md), et finissez par les [3 problèmes](problems) posés.

Vous trouverez un petit exercice à la fin de la plupart des étapes, ainsi que la solution à dérouler une fois que vous aurez passé suffisamment de temps à cogiter !

Bon courage 💪
