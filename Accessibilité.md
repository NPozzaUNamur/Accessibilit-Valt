# Introduction
L’**accessibilité numérique** est une **qualité** qui se définit par : "La **mise** à la **disposition** de tous les **individus**, quels que soient leur **matériel** ou logiciel, leur **infrastructure réseau**, leur **langue** maternelle, leur **culture**, leur **localisation** géographique, ou leurs **aptitudes physiques** ou **mentales,** des **ressources numériques**".

Il est **important** de la prendre en compte lors de la **conception** d’un produit **logiciel**, ceci afin de permettre au plus **grand nombre** d’y **accéder sans discrimination**.

# Lien Avec d’Autres Qualités

Il est fréquent de mélanger les concepts d’**accessibilité** et d’**[utilisabilité](Utilisabilité)**, d’où l’importance de distinguer ces deux aspects. L’**objectif** de l’**accessibilité** est de rendre l’application **accessible** à **tous,** y compris aux **personnes en situation de handicap**, afin d’**assurer** une **utilisation équitable**. En revanche, l’**utilisabilité** vise à **optimiser l’efficacité** de l’application. 

L’**accessibilité contient** des éléments de **[robustesse](Robustesse)**. Une **application accessible** doit pouvoir être **robuste** à des **changements de contenu,** aux **outils d’assistance,** etc.
# Les Types d’Accessibilité
L'accessibilité peut être déclinée en plusieurs types différents, dans notre cas, nous avons choisi : la **langue,** la **cognition,** l’accessibilité **multisensorielle** et l’accessibilité **matérielle**.
## Langue
À travers le monde, il existe une **multitude de langue** ainsi que de culture. Malgré un nombre important de language, seule [35% des européens sont monoglottes](https://fr.statista.com/infographie/31245/europe-langue-maternelle/). Cette observation nous enseigne un point important, pour rendre un **produit accessible**, il faut **supporter** le plus **grand nombre de langue**.

Ceci est le sujet du **standard d'I18N**, à savoir l'*internationalization*. Celui-ci ne propose pas simplement d'effectuer une traduction, mais bien un ensemble de **normes** permettant d'**adapter UX au différentes langue et régions**. Voici une liste, non exhaustive, des différents élément du standard I18N.
* **Unicode**: Aspect fondamental du standard, le **support d'Unicode** dans toutes les couches du produit permet aux utilisateurs d'**utiliser tout les caractères possible**. En tant que francophone, nous expérimentant souvent la mauvaise gestion des accents, ceux-ci n'étant pas reconnues.
* **Direction des textes**: Lorsque l'on prend en compte l'accessibilité linguistique, il est important de considérer la **direction des textes**. Certains langages, comme l'arabe ou l'hébreu, s'**écrivent de droite à gauche**. Il est donc essentiel de prendre en charge cette directionnalité dans la **conception de l'interface utilisateur** et de permettre aux utilisateurs de **basculer entre les différentes directions de texte** si nécessaire.
* **Unités de mesure, Zone horraire, Date**: Il est essentiel de prendre en charge les **différentes unités de mesure utilisées** dans différentes régions du monde, ainsi que les **formats de date et d'heure spécifiques** à chaque culture. Cela permet aux utilisateurs de **comprendre et d'interagir avec les informations** temporelles de manière accessible et adaptée à leurs besoins. 
* **Normes culturelle**: Malgré une signification universelle apparante des **symboles**, ceux-ci **ne sont pas** toujours **compris de la même manière** selon la culture de l'**utilisateur**. Il est donc important de faire un **étude préalable de la culture** des symboles dans chaque regions visées. Un exemple connu est la signification du symbole `✓` qui, au japon peut signifier `incorrecte`.

L'I18N permet donc aux développeurs de **concevoir des produits** pouvant s'adresser au **monde entier**. Cependant, la **couverture** de cette normes n'est que **partielle**. Il est encore **nécessaire** d'effectuer de la **recherche dans ce domaine**. Notamment sur un point assez controversé qu'est les raccourcis claviers. Faut-il les adapter à la langue de l'utilisateur ?

## Cognition
Ce type est consacré aux **méthodes** permettant de **réduire l’effort cognitif** nécessaire afin d’**utiliser** le **produit**. Elle a pour **but** de **rendre l’utilisation possible et agréable** à des personnes **présentant** des **troubles** *dys*. Mais celle-ci est **profitable** pour **tout un chacun**. 

Il faut entendre par effort cognitif, l’effort intellectuel engendré lorsqu’un utilisateur effectue un processus tel que remplir un formulaire ou lire un texte.

Cette accessibilité peut prendre **plusieurs formes**.
- **Assistance**: L'implémentation d'**outils d'assistance** au sein de produit logiciel permet de rendre ceux-ci plus **accessibles**. On peut cité des outils bien connus comme le **lecteur simplifié** des navigateurs web permettant de retirer toutes les distractions, ou encore la **dictée** permettant de remplir du texte via la parole. On remarque donc que dans le premier cas, l'**effort cognitif** demander pour lire une page web est **réduit**. Et dans le second cas, cette outils permet au **personne** présentant des **troubles d'utiliser le produit**.
- **Guideline**: La prise en compte de **guideline est une base de l'accessibilité**. Ici, on parle des **guidelines** issues du principes de ***Compréhension* du WCAG**. 

## Multisensorielle
L’accessibilité **multisensorielle** est un regroupement de trois autres types : accessibilité **auditive**, **physique** et **visuelle**.
## Matérielle
Dans cette section de la grille, nous allons parler davantage d’une partie **physique du logiciel,** à savoir **son/ses supports**. Mais aussi comment sont **prises** en **charge** les **images/vidéos** en fonction du **temps** de **chargement**, d’une **connexion faible,** si une description textuelle est disponible.