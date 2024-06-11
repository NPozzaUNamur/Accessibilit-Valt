# Introduction

L’**accessibilité numérique** est une **qualité** qui se définit par : "La **mise** à la **disposition** de tous les **individus**, quels que soient leur **matériel** ou logiciel, leur **infrastructure réseau**, leur **langue** maternelle, leur **culture**, leur **localisation** géographique, ou leurs **aptitudes physiques** ou **mentales,** des **ressources numériques**".

Il est **important** de la prendre en compte lors de la **conception** d’un produit **logiciel**, ceci afin de permettre au plus **grand nombre** d’y **accéder sans discrimination**.

# Lien Avec d’Autres Qualités

## Utilisabilité

Il est fréquent de mélanger les concepts d’**accessibilité** et d’**[utilisabilité](Utilisabilité.md)**. À juste titre car ces **deux termes sont proches**, cependant la notion d'**accessibilité est plus large**, et **contient** donc la notion d'**[utilisabilité](Utilisabilité.md)**. Cette dernière est présentée comme l'**[un des 4 principes du standard WCAG](WCAG.md#utilisable)**. 

Mais pour être complet, certains aspects de **[utilisabilité](Utilisabilité.md)** ne sont tout de même pas repris dans le standard comme l'attractivité. Ce qui est vraiment interréssant au niveau de l'**accessibilité** est la ***compréhensibilité*** ou encore ***opérabilité***.

## Robustesse

L’**accessibilité contient** des éléments de **[robustesse](Robustesse.md)**. Une **application accessible** doit pouvoir être **robuste** à des **changements de contenu,** aux **outils d’assistance,** etc. 

Cette qualité logicielle est un **[principe du standard WCAG](WCAG.md#robuste)**.

# Les Types d’Accessibilité

L'accessibilité peut être déclinée de plusieurs façons, dans notre cas, nous avons choisi : la **langue,** la **cognition,** l’accessibilité **multisensorielle** et l’accessibilité **matérielle**.
## Langue

À travers le monde, il existe une **multitude de langue** ainsi que de culture. Malgré un nombre important de langues, seuls [35% des européens sont monoglottes](https://fr.statista.com/infographie/31245/europe-langue-maternelle/). Cette observation nous enseigne un point important, pour rendre un **produit accessible**, il faut **supporter** le plus **grand nombre de langues**.

Ceci est le sujet du **standard d'I18N**, à savoir l'*internationalisation*. Celui-ci ne propose pas simplement d'effectuer une traduction, mais bien un ensemble de **normes** permettant d'**adapter UX au différentes langues et régions**. Voici une liste, non exhaustive, des différents élément du standard I18N.
* **Unicode**: Aspect fondamental du standard, le **support d'Unicode** dans toutes les couches du produit permet aux utilisateurs d'**utiliser tous les caractères possibles**. En tant que francophone, nous expérimentons souvent la mauvaise gestion des accents, ceux-ci n'étant pas reconnus.
* **Direction des textes**: Lorsque l'on prend en compte l'accessibilité linguistique, il est important de considérer la **direction des textes**. Certaines langues, comme l'arabe ou l'hébreu, s'**écrivent de droite à gauche**. Il est donc essentiel de prendre en charge cette directionnalité dans la **conception de l'interface utilisateur** et de permettre aux utilisateurs de **basculer entre les différentes directions de texte** si nécessaire.
* **Unités de mesure, Zone horraire, Date**: Il est essentiel de prendre en charge les **différentes unités de mesure utilisées** dans différentes régions du monde, ainsi que les **formats de date et d'heure spécifiques** à chaque culture. Cela permet aux utilisateurs de **comprendre et d'interagir avec les informations** temporelles de manière accessible et adaptée à leurs besoins. 
* **Normes culturelle**: Malgré une signification universelle apparente des **symboles**, ceux-ci **ne sont pas** toujours **compris de la même manière** selon la culture de l'**utilisateur**. Il est donc important de faire une **étude préalable de la culture** des symboles dans chaque région visées. Un exemple connu est la signification du symbole `✓` qui, au japon peut signifier `incorrecte`.

L'**I18N** permet donc aux développeurs de **concevoir des produits** pouvant s'adresser au **monde entier**. Cependant, la **couverture** de cette norme n'est que **partielle**. Il est encore **nécessaire** d'effectuer de la **recherche dans ce domaine**. Notamment sur un point assez controversé qu'est les raccourcis claviers. Faut-il les adapter à la langue de l'utilisateur ?

## Cognition

Ce type est consacré aux **méthodes** permettant de **réduire l’effort cognitif** nécessaire afin d’**utiliser** le **produit**. Elle a pour **but** de **rendre l’utilisation possible et agréable** à des personnes **présentant** des **troubles** *dys*. Mais celle-ci est **profitable** pour **tout un chacun**. 

Il faut entendre par effort cognitif, l’effort intellectuel engendré lorsqu’un utilisateur effectue un processus tel que remplir un formulaire ou lire un texte.

Cette accessibilité peut prendre **plusieurs formes**.
- **Assistance**: L'implémentation d'**outils d'assistance** au sein de produits logiciels permet de rendre ceux-ci plus **accessibles**. On peut citer des outils bien connus comme le **lecteur simplifié** des navigateurs web permettant de retirer toutes les distractions, ou encore la **dictée** permettant de remplir du texte via la parole. On remarque donc que dans le premier cas, l'**effort cognitif** demandé pour lire une page web est **réduit**. Et dans le second cas, cette outil permet aux **personnes** présentant des **troubles d'utiliser le produit**.
- **Guideline**: La prise en compte de **guideline est une base de l'accessibilité**. Ici, on parle des **guidelines** issues du principe de **[*Compréhension* du WCAG](WCAG.md#compréhensible)**. 

## Multisensorielle

L’accessibilité **multisensorielle** est une branche de l'accessibilité répondant aux besoins des personnes présentant un handicap **auditif**, **physique**, **visuel**, ou autres, à interagir avec les produits numériques.

L'**utilisation d'outils d'accessibilité tiers** est courante dans cette branche. En effet, des **outils spécialisés** sont apparus pour répondre aux **besoins** à un **niveau global**. Malgré cela, il est tout de même **important** que les produits logiciels s'**adaptent aux nouveaux usages de leur plateforme**. Tout cela est repris dans le **standard WCAG** sous le principe de ***[robustesse](WCAG.md#robuste)*** ou de ***[perception](WCAG.md#perceptible)***.

Au delà des considérations liées aux outils, il est important d'aborder les autres aspects plus communs. La plupart des personnes ne présente que des **handicaps légers** comme le daltonisme ou la presbyacousie. Un produit se doit donc de respecter des ***guidelines*** permettant de **répondre à leurs besoins aussi**.

Paradoxalement, l'**accessibilité** orientée pour les personnes en présence d'**handicap** est la plus **connue du grand public** tout en n'étant **pas** aussi bien **standardisée**, ni **balisée** et ni **implémentée** que les autres aspects moins connus. Une [étude](https://makeitfable.com/insights/insights-the-state-of-online-shopping-for-people-with-disabilities/) a montré que ce type d'utilisateur **rencontre encore de nombreux problèmes** pour effectuer des actions aussi simples que de **commander** des biens sur **internet**.

## Matériel
Dans cette section de la grille, nous allons parler davantage d’une partie **physique du logiciel,** à savoir **son/ses supports**. Mais aussi comment sont **prises** en **charge** les **images/vidéos** en fonction du **temps** de **chargement**, d’une **connexion faible,** si une description textuelle est disponible.