---
title: "Chapitre 4 - Généralités sur les fonctions"
draft: false
tags:
  -
---
 ## I- Notion de fonction et vocabulaire
### 1) Notion de fonction

>[!FAQ] Définition :
>Une fonction $f$ est une relation qui à tout nombre réel $x$ associe *au plus* un réel noté $f(x)$ qu'on appelle l'image de $x$ par la fonction $f$
>>[!NOTE] Remarque :
>>Au plus un signifie 0 ou 1
>
>>[!TIP] Notation :
>On note $f:x$->$f(x)$
>
>>[!EXAMPLE] Exemples :
>$f(x)$->$2x+7$ est une fonction
>$g(x)$->$x^2$ est une fonction
>La relation qui à tout entier naturel non nul associe tous ses diviseurs positifs n'est pas une fonction

### 2) Ensemble de définition d'une fonction
>[!FAQ] Définition :
>Soit $f$ une fonction
>Son ensemble de définition, noté $D_f$ est l'ensemble de tous les réels qui ont une image sur $f$
>
>>[!NOTE] Remarque :
>>Un dénominateur doit être non nul
>>Une expression sous une racine carrée doit être positive ou nulle
>
>>[!EXAMPLE] Exemples :
>Déterminer les ensembles de définition de :
>$f(x)$->$\frac {1} {x}$ / $D_f=]-\infty;0[U]0;+\infty[=R*$
>$g(x)$->$x^2$ / $D_g=R$
>$h(x)$->$-2x+7$ / $D_h=R$
>$v(x)$->$\frac  {x+5} {3x-6}$ / $D_v=]-\infty;2[U]2;+\infty[=R$\ $2$
>$w(x)$->$\sqrt {5x+10}




### 3) Antécédent d'un réel donné par une fonction
>[!FAQ] Définition :
>Soit $f$ une fonction définie sur $D_f$ et $a$ un réel
>Un antécédent de $a$ est un réel $x$ appartenant à $D_f$ dont l'image par $f$ est égale à $a$
>C'est à dire que $f(x)=a$
>>[!NOTE] Remarque :
>>Un réel peut avoir aucun, un, ou plusieurs antécédents
>
>>[!EXAMPLE] Exemple :
>>Soit $f$ la fonction définie sur $R$ par $f(x)=-2x+5$
>>Déterminer le ou les antécédents éventuels de 0 par $f$
>>$f(x)=0$
>><=>$-2x+5=0$
>><=>$-2x=-5$
>><=>$x=\frac {-5} {-2}$
>><=>$x=2,5$
>>L'antécédent de $0$ par $f$ est $2,5$




## II- Courbe représentative d'une fonction
### 1) Définition
>[!NOTE] Définition :
>On se place dans le repère $(O;I;J)$
La courbe représentative d'une fonction $f$, définie sur $D_f$ est l'ensemble des points d'abscisse $x\in D_f$ et d'ordonnée $f(x)$
On la note $c_f$
>>[!EXAMPLE] Exemple :
>>$f(x)=\frac {1} {x}$
>>https://www.desmos.com/calculator/kbm0oshqkc
>>**Voir tableau juste après**
>>Le point $A(3;0,33)$ appartient il à $C_f$ ?
>>$f(3)=\frac {1} {3}\ne0,33$
>>donc $A\notin C_f$

| x    | -4    | -2   | -1  | -0,5 | -0,25 | 0     | 0,25 | 0,5 | 1   | 2   | 4    |
| ---- | ----- | ---- | --- | ---- | ----- | ----- | ---- | --- | --- | --- | ---- |
| f(x) | -0,25 | -0,5 | -1  | -2   | -4    | ///// | 4    | 2   | 1   | 0,5 | 0,25 |



### 2) Lecture graphique d'image et d'antécédent
>[!TIP] Principe :
>Soit $f$ une fonction définie sur $D_f$ et $C_f$ sa courbe représentative
>L'image de $x_0\in D_f$ est l'ordonnée du point d'abscisse $x_0$ de $C_f$
>Les antécédents de $y_0$ par $f$ sont, s'il en existe les abscisses des points d'ordonnées $y_0$ de $C_f$
>Image $=$ Ordonnée
>Antécédent $=$ Abscisse
### 3) Fonction paire, fonction impaire
>[!FAQ] Définition :
>Un ensemble de $R$ est dit symétrique par rapport à 0 si pour tout nombre de l'ensemble, son opposé appartient à l'ensemble
>>[!EXAMPLE] Exemple :
>>[-10;10] est symétrique par rapport à 0
>>[-5;4] est symétrique par rapport à 0

>[!FAQ] Définition :
>Soit $f$ une fonction définie sur un ensemble de définition $D$ symétrique par rapport à 0
>On dit que $f$ est pair si pour tout réel $x\in D, f(-x)=f(x)$
>On dit que $f$ est impair si pour tout réel $x\in D, f(-x)=-f(x)$
>>[!EXAMPLE] Exemple :
>>Soit $f$ la fonction carré
>>Pour tout réel $x, f(x)=x^2$
>>$f(-x)=(-x)^2=x^2$
>>$f$ est pair
>
>>[!FAQ] Propriété :
>>La courbe représentative d'une fonction paire est symétrique par rapport à l'axe des ordonnées
>>https://www.desmos.com/calculator/lvlzvtgl9w
>>La courbe représentative d'une fonction impaire est symétrique par rapport à l'origine du repère
>>https://www.desmos.com/calculator/gqyirpytig
### 4) Variations des fonctions
#### 1) Fonction croissante, fonction décroissante
>[!FAQ] Définition
>Soit $f$ une fonction et $I$ un intervalle compris dans son ensemble de définition
>On dit que $f$ est croissant sur $I$ si pour tous réels $a$ et $b$ de $I$ tels que $a<b$, on a $f(a)\le f(b)$
>On dit que $f$ est strictement croissant sur $I$ si pour tous réels $a$ et $b$ de $I$ tels que $a<b$, on a $f(a)< f(b)$
>
>Soit $f$ une fonction et $I$ un intervalle compris dans son ensemble de définition
>On dit que $f$ est décroissant sur $I$ si pour tous réels $a$ et $b$ de $I$ tels que $a<b$, on a $f(a)\ge f(b)$
>On dit que $f$ est strictement décroissant sur $I$ si pour tous réels $a$ et $b$ de $I$ tels que $a<b$, on a $f(a)> f(b)$
>>[!EXAMPLE] Exemple :
>>Démontrer que la fonction définie par $f(x)=-5x+7$ est strictement décroissant sur $R$
>>Soient $a$ et $b$ deux réels tels que $a<b$
>>Cherchons à comparer $f(a)$ et $f(b)$, soit $-5a+7$ et $-5b+7$
>>Donc $-5a>-5b$
>>Donc $-5a+7>-5b+7$
>>Donc $f(a)>f(b)$
>>On a $a<b$ et $f(a)>f(b)$, donc la fonction $f$ est strictement décroissante sur $R$

>[!FAQ] Définition :
>On dit que $f$ est monotone sur $I$ si $f$ est soit croissant sur $I$, soit décroissant sur $I$
>>[!EXAMPLE] Exemple :
>>Fonction monotone :
>>https://www.desmos.com/calculator/ulfdse3phq
>>Fonction non monotone
>>https://www.desmos.com/calculator/h2kkseac9c

>[!FAQ] Définition :
>Soit $f$ une fonction et $I$ un intervalle compris dans son ensemble de définition
>On dit que $f$ est constant sur $I$ lorsque tous les réels de I ont la même image par $f$
>Pour tous réels $a$ et $b$ de $I$, on a $f(a)=f(b)$
>La courbe représentative d'une fonction constante est une portion de droite parallèle à l'axe des abscisses.
>>[!EXAMPLE] Exemple :
>>$f(x)=30$

#### 2) Courbe de variation
>[!FAQ] Définition :
>Etudier les variations (ou le sens de variation) d'une fonction. C'est indiquer les intervalles sur lesquels elle est croissante, et ceux sur lesquels elle est décroissante.
>On résume les résultats dans ce que l'on appelle un tableau de variations.

#### 3) Extremum d'une fonction
>[!FAQ] Définition :
>Soit $f$ une fonction définie sur un intervalle $I$
>On dit que $f$ admet un maximum en $a\in I$, lorsque pour tout réel $x$ de $I$,$f(x)\le f(a)$
>On dit alors que $f(a)$ est le maximum de $f$ sur $I$ et qu'il atteint en $a$
>On dit que $f$ admet un minimum en $b\in I$, lorsque pour tout réel $x de I$, $f(x)\le f(b)$
>On dit alors que $f(b)$ est le minimum de $f$ sur $I$ et qu'il atteint en $b$
>>[!FAQ] Définition :
>>On appelle extremum de $f$ sur $I$ le minimum ou le maximum de $f$ sur $I$



