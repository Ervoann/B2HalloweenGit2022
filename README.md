L’objectif de ce document est d’expliquer
les choix réalisés lors de la réalisation
du projet Halloween GIT. Pour cela nous
expliquerons étapes-par-étapes les décisions
prises.


Etape 1 :
Pour cette première étape, nous nous
accordons pour que je crée le repo github. Une
fois créer, je me rends sur GitKraken, je clone et
j’initialise le repo. Une fois, cela fait sans réaliser
de branche, je crée directement une page Index.
html comprenant un titre de page en head ainsi
q’un body vide. Je push ensuite l’ensemble de
ces ajout depuis GitKraken
Léa récupère via un clone du repo sur Gitkraken
les récentes modifications. Nous nous
accordons à nous partager le travail en deux
parties, je m’occuperais donc des 4 premières
langues ainsi que le hotfix tandis que Léa
s’occupera des langues suivantes.


Etape 2 :
Je m’attelle donc désormais à la création de la
première feature, pour cela, je me place sur le
master et je commence par créer une branche
«Development» qui contiendra l’ensemble des
features avant release. Je me place ensuite
dans celle-ci et fait partir une seconde branche
« ervoann_feat_french ». Une fois la page
JoyeuxHalloween.html et le lien vers cette
même page créée je stage les modifications
apportées au dossier et le commit. 
Avant n’étant alors mise en production. Léa ne push
par ailleurs pas ses features pour éviter tout
conflit de version avec moi.


Etape 5 :
Pour ce hotfix je me place au niveau du master
depuis lequel je crée une branche ervoann_
hotfix_italian_to_russian. Je retourne ensuite
dans vscode pour changer la version italienne en
russe tout-en m’assurant que le lien dans l’index.
html soit à jour. Après avoir commit ce hotfix je
merge ce hotfix au master tout en m’assurant
de push ces dernières modifications. Une fois
fait, j’ajoute un tag (V1.1) à la branche afin de
définir une release avec cette modification.


Etape 6 :
Dans cette étape, je commence par créer une
branche ervoann_feat_dutch depuis la branche
master. Une fois les modifications apportées aux
différents fichiers, je commit mes modifications,
mais ne réalise aucun merge, en effet cette
feature ne fait pas partie de la future release de
la Step 4 crée par Léa.


Etape 7 :
Pour cette étape, comme pour la précédente
Léa se base sur la branche Development2
pour créer une nouvelle feature lea_feat_serbe
dans laquelle elle ajoute un joyeux halloween
en serbe qu’elle commit par la suite. Pour finir
Léa merge cette nouvelle branche à sa branche
Development2. Elle enchaîne ensuite par un
merge de cette dernière branche dans le master
en veillant à corriger les conflits avec l’ancienne
version italienne devenue russe. Léa conclue
finalement par merge ajouter un tag (V1.2) pour
nommer cette nouvelle release.


Etape 8 :
Pour cette 8ème et dernière étape après avoir
pull les modifications de Léa je merge la branche
de la feature ervoann_feat_dutch à la branche
master tout en veillant à corriger les conflits
ceci concluant ce projet de gestion de code via
GitHub & GitKraken.


Etape 9 :
Maintenant que l’ensemble des versions ont
été publiées, il est désormais temps de passer
au css. Pour cela, je me base sur le master et
créer une nouvelle branche Development3 sur
laquelle je crée une feature ervoann_feat_css.
J’ajoute alors une page css ainsi qu’une image de
background, je joue un peu avec les typos et les
couleurs et ajoute un bouton home menant vers
la page index.html dans l’ensembles des sous
pages. Une fois toutes les modifications faites
je me rends sur GitKraken, je stage et commit
mes modifications et merge une première fois
ervoann_feat_css dans Development puis une
deuxième fois avec Development dans master.
Une fois fait, je m’assure de push mes branches
et d’ajouter un tag V1.3 pour ces nouvelles
modifications


Pour conclure ce document, nous aimerions
évoquer dans une dernière partie les difficultés
que nous avons rencontrées lors de la réalisation
de ce projet. En effet malgré les cours suivis,
nous avons rencontré de multiples difficultés
à différentes étapes. En commençant une
difficulté à savoir au départ quel branche créer
à partir de quel branche ce qui nous valus
de recommencer l’exercice à de nombreuses
reprises. Ensuite le choix de quand merge
nous à souvent bloquer alors que nous nous
trouvions à quelques étapes de la fin du projet.
Finalement, la grande difficulté a été de nous
accorder sur qui s’occupait de quelle étape et en
fonctions quand pusher pour éviter les conflits
de vertsion inutiles.
l’étape suivante je merge mes modifications
dans ma branche «Development».


Etape 3 :
Pour cette étape, je me place une fois de plus
au niveau de la branche «Development» depuis
laquelle je crée une nouvelle branche «ervoann_
feat_english». Une fois, cela fait via vscode je
crée une page HappyHalloween.html que je lie
au fichier index.html par un lien comme dans
l’étape précédente. Je réalise ensuite la même
manipulation avec l’espagnol et l’italien (création
des branche ervoann_feat_spanish et ervoann_
feat_italian depuis la branche Development
+ merge de ces dernières dans la branche
Development). Avant de passer la main à Léa
pour la suite, je merge Development dans mon
master, j’enchaîne ensuite en puchant toutes
ces nouvelles pages, mais aussi en conclusion
en ajoutant un tag à ma branche Development
intitulé V1.0.


Etape 4 :
Pour cette étape Léa pull avant de commencer
pour récupérer l’ensemble des dernière
modification. Une fois, cela fait elle se place sur le
master pour y créer une branche Development2
qui lui servira de base pour créer les futures
features. Une fois cela fait, elle réalise les
mêmes étapes de création de branches et de
merge que pour l’étape précèdente pour les
features lea_feat_portugese, lea_feat_german
et lea_feat_polish. Une différence apparait tout
de même à cette étape, en effet léa merge ces
feature dans Development2, mais ne merge
pas cette branche au master, aucune release 
