# Leçon 1 : Introduction

La première chose à bien comprendre, lorsque l'on utilise les **regex**, c'est que toute donnée (que ce soit une adresse mail, le contenu d'une page, une URL, un numéro de téléphone, etc.) est essentiellement composée de caractères.

Dès lors que nous allons souhaiter intervenir sur une donnée (que ce soit pour en extraire une information, pour en modifier la structure, pour la comparer, etc.), il nous faut un outil pour localiser telle ou telle partie de la donnée en question, et c'est à ça que servent les regex.

Concrètement, une regex est un modèle (pattern) correspondant à une séquence spécifique de caractères.

La plupart des patterns utilisent des caractères [ASCII](https://fr.wikipedia.org/wiki/American_Standard_Code_for_Information_Interchange), lettres, chiffres, signes de ponctuation et les autres symboles disponibles sur un clavier, mais il est aussi possible d'utiliser des caractères unicode.

Vous trouverez ci-dessous un encart avec quelques lignes de texte et un champs de saisie où écrire votre **regex**. Pour passer à la leçon suivante, vous devrez utiliser les syntaxes et les concepts abordés dans la leçon pour écrire une expression régulière qui correspondent aux lignes présentées.

## Tester les Regex

Vous pouvez tester vos regex en utilisant le site [RegEx Tester](https://www.regextester.com/).

Pour celà, il vous suffit de taper le texte sur lequel vous recherchez une correspondance dans le champ "Test String", puis d'écrire votre regex dans le champ "Regular Expression".

La box tout à droite du champ de saisie vous indiquera alors combien de correspondances (match) ont été trouvées.

## Exercice

Pour continuer, essayez d'écrire un pattern qui corresponde (match) aux 3 lignes affichées... par exemple essayez simplement les lettres communes à chaque ligne.

| tâche | texte   |
| ----- | ------- |
| match | abcdefg |
| match | abcde   |
| match | abc     |

## Solution

<details>
    <summary>Afficher la solution</summary>

`abc`

</details>
