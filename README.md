# Checkpoint-Sorting-and-searching-algorithms
GoMyCode Checkpoint : Sorting and searching algorithms


- l'algo initialise la variable "n" en obtenant la longueur du tableau d'entiers.

- Il parcourt chaque élément du tableau.

- À chaque itération, l'algorithme stocke la valeur de l'élément à la position "i" dans la variable "clef". Cela servira de référence pour la comparaison.

- Il initialise une variable "j" à "i - 1" pour parcourir les éléments précédents à partir de la position "i".

- L'algorithme entre dans une boucle while, tant que "j" est supérieur ou égal à 0 et que l'élément précédent à la position "j" est 
plus grand que la "clef". Cette boucle permet de déplacer les éléments plus grands vers la droite pour faire de la place pour la "clef".

- Dans la boucle while , l'algorithme déplace l'élément à la position "j" vers la droite (à la position "j + 1") pour libérer de l'espace pour la "clef". Ensuite, il décrémente "j" pour passer à l'élément précédent et continue la comparaison.

- Lorsque la boucle while se termine, la position correcte pour la "clef" est trouvé dans le tableau trié, et il la place à cet emplacement en affectant "clef" à la position "j + 1".