[\\]: <> (Ce document est une reproduction\résumé d'une page Wikipedia) 
# Markdown 

**Markdown** est un langage de balisage léger créé en 2004 par [***John Gruber***](https://fr.wikipedia.org/wiki/John_Gruber) avec l'aide d'*Aaron Swartz1,2,* dans le but d'offrir une syntaxe facile à lire et à écrire. Un document balisé par **Markdown** peut être lu en l'état sans donner l’impression d'avoir été balisé ou formaté par des instructions particulières.

Un document balisé par Markdown peut être converti en
 [***HTML***](https://fr.wikipedia.org/wiki/Hypertext_Markup_Language#:~:text=Le%20HyperText%20Markup%20Language%2C%20g%C3%A9n%C3%A9ralement,pour%20repr%C3%A9senter%20les%20pages%20web.)
, en *PDF* ou en d'autres formats. Bien que la syntaxe **Markdown** ait été influencée par plusieurs filtres de conversion de texte existants vers *HTML* — dont *Setext, atx, Textile, reStructuredText, Grutatext et EtText* —, la source d’inspiration principale du Markdown est le format du courrier électronique en mode texte.

![Logo Markdown](https://www.svgrepo.com/show/354040/markdown.svg)

## Évolution 
Depuis sa création originelle par *John Gruber*, **Markdown** n'a pas connu d'évolution notable de la part de ses auteurs. De plus, ce format n'a jamais été formellement standardisé.

Un certain nombre de variantes ont donc été développées par d'autres, afin de pallier ce qui a été perçu comme des limitations inhérentes à une syntaxe très simplifiée. À titre d'exemples, on pourra citer ***MultiMarkdown*** et ***GitHub Flavored Markdown***. Ce dernier est utilisé pour les articles et la documentation sur ***GitHub***, mais a également été largement adopté sur plusieurs éditeurs de texte supportant le format **Markdown** au niveau de la coloration syntaxique ou de la prévisualisation.

Il existe également des greffons pour de nombreux logiciels, tels que « Markdown Here » pour **Firefox** et **Chrome**. Le système de gestion de contenu **WordPress** intègre nativement quelques éléments de ce langage depuis la version 4.3.

En mars *2016*, deux **RFC** ont été publiées dans un but de standardisation :

1. **RFC 776310**, qui introduit le type MIME text/markdown à partir de la variante originale de Markdown.

2. **RFC 776411**, qui répertorie des variantes **MultiMarkdown, GitHub
Flavored Markdown (GFM), Pandoc, CommonMark, Markdown Extra** et autres.
L'initiative **CommonMark**, débutée en *2012*, vise à pallier le manque de standardisation et les ambiguïtés du format en créant une spécification fortement définie du langage. Elle est désormais utilisée par, entre autres :
      * **DiscoursGitLab**
      * **Reddit**
      * **Qt**
      * **Stack Overflow**
      * **Stack Exchange13**

[![Logoreddit](https://pbs.twimg.com/card_img/1578366606559875072/VfnjWVO2?format=png&name=360x360)](https://www.reddit.com/)

## Mises en oeuvre
Plusieurs mises en œuvre existent et ce dans différents langages de programmation : **en Perl, en PHP, en Ruby, en Python, en Java, en C#, en Haskell, en Gambas, en R et même en JavaScript, notamment avec strapdown.js**. Depuis la version 2.0 de **Swift**, il est aussi possible d'utiliser le **Markdown** dans ses playgrounds.

## Usages 
Le langage de balisage léger **Markdown** est utilisé dans de nombreuses applications, que ce soit dans des logiciels/éditeurs de code, des logiciels d'écriture, des plateformes de code, ou encore dans des chaînes d'édition avec l'addition d'autres logiciels. Les domaines concernés peuvent être le développement informatique (**Markdown** est habituellement utilisé pour formater le fichier (***README*** décrivant le code source d'un programme), la rédaction de documentation technique ou encore la publication académique.

C’est aussi le langage de balisage choisi par de nombreuses plateformes d’écriture collaborative, comme **Authorea ou Manubot**. Il existe plusieurs logiciels permettant de rédiger le **Markdown** en temps réel sur le web, comme **CodiMD, Etherpad ou Firepad**.

## Quelques exemples 
Voici quelques exemples de syntaxe **Markdown**. Les balises **HTML** équivalentes sont données. Cette liste n'est pas exhaustive.
### **Formatage**
>Pour mettre du texte en emphase on peut utiliser des * ou des _. 1 de chaque côté pour *italique*. 2 de chaque côté pour **gras**. trois de chaque côté pour ***italique + gras***.  - *Vega laliberté*

Exemple _italique_ :
Comme ceci `*Important*` ou comme ceci `_Important_` 

Exemple __gras__ :
Comme ceci `**Important**` ou comme ceci `__Important__`

Exemple ___gras + italique___ :
Comme ceci `***Important***` ou comme ceci `___Important___`

### **Code**
Il est aussi possible de mettre du code dans vos documents MarkDown ne utilisant `` `code` `` ceci quand c'est seulement une ligne et cela `` ```code``` `` quand cette une longue ligne de code ou un bloc de code.

### **Tableaux**
Il est aussi possible de faire des tableaux :
```
| Titre 1       |     Titre 2     |        Titre 3 |
| :------------ | :-------------: | -------------: |
| Colonne       |     Colonne     |        Colonne |
| Alignée à     |   Alignée au    |      Alignée à |
| Gauche        |     Centre      |         Droite | 
```
Voici le résultat :
| Titre 1       |     Titre 2     |        Titre 3 |
| :------------ | :-------------: | -------------: |
| Colonne       |     Colonne     |        Colonne |
| Alignée à     |   Alignée au    |      Alignée à |
| Gauche        |     Centre      |         Droite |

### **Liste**
Sauter une ligne avant le début de la liste.

Pour créer une liste non ordonnée (balise HTML)
```
* Pommes
* Poires
    * Sous élément avec au moins quatre espaces devant.
```
Et une liste ordonnée (balise HTML)
```
1. mon premier
2. mon deuxième
```
Et une liste en mode case à cocher
```
- [ ] Case non cochée
- [x] Case cochée
```
### **Image**
Pour afficher une image (balise HTML)
```
![Texte alternatif](url_de_l'image ou chemain "texte pour le titre, facultatif")
```
## Lien vers l'article wikipedia en question : 
[![wikipedia logo](./Wikipedia-logo-v2.svg.png)](https://fr.wikipedia.org/wiki/Markdown)