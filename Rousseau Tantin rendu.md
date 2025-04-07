# Rendu site internet
**Rousseau Tantin Maeva, M1 HCP**
## Etapes de conception du site internet
### Utilisation du logiciel _Visual Studio Code_
### Choix du templates
* Site : [HTML 5 UP](https://html5up.net/)
* Choix templates **_Story_** car il permettait de pouvoir mettre des images et d'avoir plusieurs sections pour des thèmes du mémoire.
Ouverture dans Visual Stuio Code.
### Transformation du code pour la page principale
#### Modification textes et images HTML
Dans la section "head" trasnfomation du "title", change l'en-tête de la page web.

Ensuite modification des "h1 / h2 / etc." dans toutes les sections du code, ce qui change les titres de la page principale.
* Première section titre du mémoire
* Deuxième et troisième sections, j'ai choisi de mettre des thèmes possibles pour mon mémoire
* Troisème section : bilbiographie et sources
* Puis choix des différents titres du site.

Après, à travers le "p", j'ai modifié le texte présent dans l'entièreté du site pour le faire correspondre au titre des sections. 

J'ai ensuite appliqué des images, d'abord en les téléchargant puis en les glissant dans le texte image du dossier du site. J'ai remplacé mes images en changeant le lien qui renvoyait dans le code à celle-ci avec la balise "a" et "href" qui permettent de créer l'hyperlien.
* Rajout de "Target_blank" pour renvoyer vers le site de l'image (même chose pour chaque image)
* Même chose pour les sites internets, cependant c'est en appuyant sur le bouton "détails" que cela renvoi au site internet.

#### Modification des couleurs avec le CSS
Pour la section "banner" j'ai créer dans le fichier _main.css_ une section ".banner" pour modifier la couleur du fond. Puis j'ai crée une secion ".banner . button" pour modifier la couleur du bouton. Pour la couleur de l'écriture du bouton j'ai dû rajouter "!important" pour que le changement s'applique.
Pour le reste du site j'ai simplement dû trouver où était la fonction dans le CSS puis modifier celle-ci que ce soit les boutons ou le fond car j'appliquer la même couleur sur tout le site.

### Création d'un lien vers une nouvelle page
D'abord, j'ai ouvert et enregistrer un nouveau document dans le dossier du site internet que j'ai nommé _"Bibliographie.html"_. Pour que le lien fonctionne dans la section _Bibliographie et sources_ de l'index html j'ai crée un lien pour le bouton "learn more" qui ouvre cette page.
* Ensuite j'ai dû écrire une partie du code en reprenant ce qui avait été fait sur la page précédente principalement pour la tête. 
* J'ai créer le corps avec un en-tête pour le titre "header".
* La balise "main" pour le contenu principal
* Deux balises "section" pour les compartiments de cette page dans lequel on trouve un "h2" pour le titre, et des balises "ul" et "li" pour les listes.
* J'ai utiliser la balise "em" pour mettre en italique les titres des ouvrages.

Enfin j'ai crée un id pour le "body" afin de pouvoir modifier le CSS de cette page. Dans le CSS, à la fin j'ai ajouté :
* Une balise de couleur pour les différentes parties
* Une balise padding et margin pour l'espacement
* Une balise pour l'alignement du texte d'en l'en-tête
* Une balise pour enlever les puces car elles ne correpodaient pas à ce que je voulais et je ne savaient pas comment les modifier.

## Bibliographie et sitographie
Site pour les images : 
* Kowalski Jean-Marie. Thucydide, témoin des opérations navales dans la première phase de la guerre du Péloponnèse (431-415 av. J.‑C.). In: _Dialogues d'histoire ancienne_, vol. 40, n°1, 2014. p. 27-51. https://www.persee.fr/doc/dha_0755-7256_2014_num_40_1_3902
* [Les Belles Lettres](https://www.lesbelleslettres.com/livre/9782251451435/coffret-fondation)
* [Mythcreants](https://mythcreants.com/blog/water-travel-before-engines/)
* [Parabaino](https://mythcreants.com/blog/water-travel-before-engines/)
* [Classical art research centre](https://www.carc.ox.ac.uk/carc/pottery)
* [Agorha](https://agorha.inha.fr/database/27)