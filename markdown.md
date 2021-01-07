# Les secrets du Markdown

Le **Markdown** est un language qui permet d'écrire du HTML de façon raccourcie. Voici les différentes façons de styliser du texte, plus simplement ! :heart_eyes:

## Sommaire 
* Titres
* Paragraphes
* Listes
* Emphase
* Liens
* Images
* Code

## Titres
Il y a deux façons d'écrire les titres en Markdown.
La première manière, plus pratique et complète, est d'ajouter un ou plusieurs # devant le titre :

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4

La deuxième manière est de "souligner" le titre, comme dans l'exemple ci-dessous :

Titre de niveau 1
====================

Titre de niveau 2
-------------------

## Paragraphes 
Pour réaliser un paragraphe, rien de plus simple, il suffit de sauter / laisser une ligne vide entre les deux textes.

## Listes 
### Listes non-ordonées
Pour créer une liste, il suffit d'ajouter "*" ou "+" ou "-"  au début de chaque ligne. Il est également possible d'imbriquer une liste dans une autre :
* Puce 1
* Puce 2 
    * Puce a
    * Puce b
+ Puce 3
- Puce 4

### Listes ordonées 
Pour créer une liste numérotée, il faut ajouter le numéro correspondant au début de chaque ligne :
1. Puce 1
2. Puce 2
3. Puce 3

## Emphase (gras, italique, ...)
L'emphase est une mise en valeur d'un mot ou d'un groupe de mots.

Pour réaliser une emphase faible, l'équivalent du <em> sur HTML, il suffit d'entourer le mot d'une étoile \* ou d'un trait de souligenement \_ au début et à la fin du mot ou du groupe de mots. Le mot apparaît en italique.
Comme ceci : *italique* ou _italique_

Pour réaliser une emphase forte, l'équivalent du <strong> sur HTML, il suffit d'entourer le mot de deux étoiles \*\* ou de deux traits de souligenement \_\_ au début et à la fin du mot ou du groupe de mots. Le mot apparaît en gras. 
Comme ceci : **gras** ou __gras__

## Liens
Pour écrire un lien sur *Markdown*, il faut entourer le lien cliquable entre crochets \[\] et le lien URL entre parenthèses \(\).
Comme ceci : Rendez-vous sur [Becode.org] (https://becode.org/)!

Il s'agit de l'équivalent de <p>Rendez-vous sur <a href="https://becode.org"> Becode.org </a>!</p> sur HTML.

## Images
### Images statiques
Pour publier une image statique, c'est le même principe que les liens sauf qu'il faut ajouter un ! devant les crochets.

Il faut donc entourer l'équivalent de l'alt du HTML entre crochets \[\] et le précéder d'un !. Le lien URL de l'image est entre parenthèses \(\).
Comme ceci :  ![baby Yoda] (https://cdn.radiofrance.fr/s3/cruiser-production/2020/11/e51977ae-afa4-41bd-a014-03ae5c6b7b5f/801x410_capture_decran_2020-11-10_a_165950.jpg)

Il s'agit de l'équivalent de <p><img src="https://cdn.radiofrance.fr/s3/cruiser-production/2020/11/e51977ae-afa4-41bd-a014-03ae5c6b7b5f/801x410_capture_decran_2020-11-10_a_165950.jpg" alt="baby Yoda" /></p>

### Images animées
Pour publier une image animée, le principe est le même.

Il faut donc entourer l'équivalent de l'alt du HTML entre crochets \[\] et le précéder d'un !. Le lien URL de l'image est entre parenthèses \(\).
Comme ceci :  ![baby Yoda] (https://giphy.com/gifs/mashable-baby-yoda-mandalorian-the-C0ZArORmrDQCRTIFnQ)

Il s'agit de l'équivalent de <p><img src="https://giphy.com/gifs/mashable-baby-yoda-mandalorian-the-C0ZArORmrDQCRTIFnQ" alt="baby Yoda" /></p>
