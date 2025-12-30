# Leçon 3 : Correspondre avec des caractères spécifiques

Le métacaractère `.` que nous venons de voir est très puissant... parfois il est même trop puissant ! Si on cherchait une expression régulière correspondant à des numéros de téléphone, nous ne souhaiterions pas valider une chaîne comportant des lettres comme `(abc) def-ghi-klm `.

Il est possible de faire correspondre notre pattern avec plusieurs caractères spécifiques en les listants entre crochets. Par exemple le pattern `[abc]` ne correspondra qu'a un seul caractère pouvant être `a`, `b` ou `c` et rien d'autre.

## Exercice

Trouvez une expression régulière qui corresponde aux 3 premières lignes ci-dessous, mais qui évite les 3 dernières. Vous constatez qu'en utilisant le`.` il est impossible de ne pas correspondre avec les 3 dernières lignes.

| tâche | texte |
| ----- | ----- |
| match | can   |
| match | man   |
| match | fan   |
| skip  | dan   |
| skip  | ran   |
| skip  | pan   |

## Solution

<details>
    <summary>Afficher la solution</summary>

`[cmf]an` ou `[^drp]`

</details>
