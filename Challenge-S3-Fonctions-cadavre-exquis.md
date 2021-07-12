# Challenge : Générateur de cadavre exquis

Nous allons adapter le jeu du cadavre exquis pour travailler **nos fonctions utilisateurs et les fonctions internes à PHP ainsi que les tableaux**.

## L'origine du cadavre exquis

Le cadavre exquis est un jeu collectif inventé par les surréalistes et notamment par Jacques Prévert, en 1925. C'est un jeu qui consiste à faire composer une phrase, ou un dessin, par plusieurs personnes sans qu'aucune d'elles ne puisse tenir compte de la collaboration ou des collaborations précédentes.

> **Pour simuler les joueurs, nous utiliserons le hasard - rappelez-vous de `mt_rand()` - et piocherons les phrases dans un tableau les contenant.** Vous avez bien sûr tout le loisir pour définir ces phrases ;)

**Il existe plusieurs façons de jouer au jeu du cadavre exquis :**

## Le cadavre exquis de la phrase

C'est la première variante obtenue par les créateurs du jeu, d'où son nom. On écrira à la suite :


- Un substantif (par exemple _"Le cadavre"_).
- Un adjectif (par exemple _"exquis"_).
- Un verbe (par exemple _"boira"_).
- Un autre substantif (par exemple _"le vin"_).
- Un autre adjectif (par exemple _"nouveau"_).

Ce qui donnera à la lecture de ce papier-ci : _"Le cadavre exquis boira le vin nouveau"_ (premier texte obtenu par les poètes surréalistes amateurs de ce jeu).

## Le cadavre exquis des définitions

On piochera au hasard :

- Une question (par exemple _"Qu'est-ce qu'un éléphant ?"_).
- Une définition (par exemple _"Une machine avec des roues"_).

Ce qui donnera à la lecture : _"Qu'est-ce qu'un éléphant ? Une machine avec des roues."_

## Le cadavre exquis avec des "Si"

On piochera au hasard :

- Une phrase commençant par un _"Si"_, (par exemple _"Si j'avais des ailes"_).
- Puis une action (par exemple _"Je mangerais des champignons"_).

## Le cadavre exquis des syllabes

On utilise des mots de 3 ou 4 syllabes, on définit un thème, par exemple _"les animaux"_ et on doit noter les syllabes des noms des animaux : _"cro"_ (pour crocodile), _"ra"_ (pour girafe) et _"phant"_ (pour éléphant).
On obtient un drôle de _"Croraphant"_ !

Décomposer des mots de cette manière :

- Cro-co-dile
- Gi-ra-fe
- E-lé-phant

Puis prendre au hasard 3 syllabes dans l'ordre (1, 2, 3) et les concaténer, autre exemple avec ces mêmes mots : _"Eradile"_ ou _"Gicophant"_.

## BONUS FUN : Le cadavre exquis en dessin

A partir des 3 variantes d'images fournies dans le dossier _"images"_, recomposer au hasard un personnage avec une tête (top), un corps (middle), des jambes (bottom). On utilisera la balise HTML `img`.

## Source

[Momes.net](Momes.net)

## Rendu

Des examples :

- [Cadavre exquis phrase](/rendu/cadavre-exquis-phrase.png)
- [Cadavre exquis definitions](/rendu/cadavre-exquis-definitions.png)
- [Cadavre exquis si](/rendu/cadavre-exquis-si.png)
- [Cadavre exquis syllabes](/rendu/cadavre-exquis-syllabes.png)
- [Cadavre exquis dessin](/rendu/cadavre-exquis-image.png)
