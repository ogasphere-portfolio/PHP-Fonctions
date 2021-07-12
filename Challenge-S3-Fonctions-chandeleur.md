# Challenge : En avant les fourneaux !

La chandeleur est arrivée et il vous faut la bonne quantité d'ingrédients pour faire pâte légère et onctueuse. Cependant, le nombre d'ingrédients dépend aussi de votre nombre convives. Nous ne traiterons pas ici de l'éternel débat entre crêpes et galettes, mais nous servirons de ce point de départ pour appliquer nos calculs de _"quantitée"_ et **travailler avec les fonctions utilisateur**.

Ainsi, vous pourrez vous-même choisir votre nombre d'invités (c'est quand même mieux :D)

**Instructions**

Dans un script PHP, pour *chaque formule* ci-dessous :

Créer une fonction qui prend en paramètre les données nécessaires au calcul

Cette fonction va renvoyer *une valeur* de retour qui correspond à ce qui est attendu dans les intitulés suivant:

1. Le nombre d'invités
2. La quantité totale d'ingrédients
3. Le poids en Oz
4. Le poids en livres
5. Le nombre de calories consommées par l'ensemble des invités
6. Niveau d'alerte aux discussions houleuses

Puis :

- Afficher à l'écran la liste de tous les paramètres utilisés pour tous les calculs (l'ensemble des variables nécessaires à la recette)

- Afficher à l'écran l'intitulé de chaque calcul (h1 ou h2), puis son résultat (p).

On considerera la recette suivante pour 16 crêpes (2 par personne) soit :
- 250 g de farine
- 4 oeufs
- 50 cl litre de lait
- 1 pincée de sel
- 50 g de beurre
- 1 sachet de sucre vanillé
- 1 cuillère à soupe de fleur d'oranger

## Nombre d'invités

- La recette n'est pas probante pour moins de 8 personnes

- Vous ne pouvez pas recevoir plus 20 personnes à table, parce que ça fait déjà beaucoup ;)

> On affichera, par exemple un message selon le contexte du type :
> Il n'y a pas assez d'invités ...

## Quantité totale d'ingrédients

Selon le nombre de personnes présentes, il vous faudra multiplier les quantités par un coefficient :

- 8 = 1
- 8  > personnes < 11 = 1.5
- 11 >= personnes < 14 = 1.80
- 14 >= personnes < 16 = 2
- 16 >= personnes <= 20 = 4

> On affichera, par exemple :
> farine (g) : 500
> oeufs : 8
> lait (cl) : 100
> Pincée de sel : 2
> beurre (g) : 100
> sachet de sucre vanillé : 2
> cuillère à soupe de fleur d'oranger : 2

## Poids en Oz

- Un oz représente 28g

## Poids en livres

- Un gramme représente un millième de kilogramme
- Une livre vaux 0,453 kilogramme

## Nombre de calories consommées par l'ensemble des invités
- Il y a deux crêpes par personne
- Une crêpe représente 60 kcal

## Niveau d'alerte aux discussions houleuses

Ce risque est complètement *aléatoire* et ne dépend que de l'humeur de vos convives.

Ce niveau d'alerte est représenté par cette échelle :

- 0 = 'J'ai trop mangé, je vais bien dormir ce soir!';
- 1 = 'Mamie fait mieux les crêpes que toi.';
- 2 = 'C'était pas si mal quand M. X était président.';
- 3 = 'Le Mont Saint-Michel appartient à la Bretagne.';
- 4 = 'Je suis ton père.';
- 5 = 'Tu es sûr que ce sont des crêpes ?!';

> On affichera, par exemple :
> Risque de niveau 0 : J'ai trop mangé, je vais bien dormir ce soir !

### Exemple de rendu

<kbd>![](/rendu/chandeleur.png)</kbd>
