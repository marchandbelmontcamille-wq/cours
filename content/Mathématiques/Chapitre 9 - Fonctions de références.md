## I- Fonction carré
### 1) Définition
>[!FAQ] Définition :
>La fonction carré est la fonction $f$ définie sur $R$ par $f(x)=x^2$

>[!TIP] Remarque :
>La fonction carré est positive
>Pour tout réel $x$, $x^2\ge 0$

>[!FAQ] Propriété :
>La fonction carré est paire
>
> [!tldr] Démonstration :
> Pour tout réel $x$, $f(-x)=(-x)^2=x^2=f(x)$
### 2) Courbe représentative et variation

| x    | -3  | -2  | -1  | 0   | 1   | 2   | 3   |
| ---- | --- | --- | --- | --- | --- | --- | --- |
| f(x) | ç   | 4   | 1   | 0   | 1   | 4   | 9   |
>[!TIP] Remarques :
>On dit que la courbe représentative de la fonction carré est une parabole de sommet l'origine du repère
>La courbe représentative de la fonction carré est symétrique par rapport à l'axe des ordonnées

>[!FAQ] Propriété :
>La fonction carré est strictement décroissante sur $[-\infty;0]$ et strictement croissante sur $[0;+\infty]$
### 3) Equations et inéquations
>[!FAQ] Propriété :
>Soit $k$ un réel. L'équation $x^2=k$ a pour ensemble de solutions :
>- $S=\emptyset$ si $k<0$
>- $S=[0]$ si $k=0$
>- $S=[-\sqrt {k}; \sqrt {k}]$ si $k>0$

>[!EXAMPLE] Exemples :
>1) $x^2=16$
>$S=[-4;4]$
>2) $x^2=-3$
>$S=\emptyset$
>3) $x^2<5$
>S=$]-\sqrt{5};\sqrt {5}[$
>4) $x^2<-7$
>$S=\emptyset$
>5) $x^2\ge 5$
>$S=]-\infty;-\sqrt {5}]\text {U}[\sqrt {5};+\infty[$
>6) $x^2>-1$
>7) $S=R$
## II- Fonction inverse
### 1) Définition
>[!FAQ] Définition :
>La fonction inverse est la fonction $f$ définie sur $]-\infty;0[U]0;+\infty[$ par $f(x)=\frac {1} {x}$

>[!FAQ] Propriété :
>La fonction inverse est impaire

>[!TIP] Démonstration :
>L'ensemble de définition est symétrique par rapport à 0 
>Pour tout réel $x$ avec $x\ne 0$, $f(-x)=\frac {1} {-x}=-\frac {1} {x}=-f(x)$
### 2) Courbe représentatives et variations

| x    | -2   | -1  | -0,5 | 0           | 0,5 | 1   | 2   |
| ---- | ---- | --- | ---- | ----------- | --- | --- | --- |
| f(x) | -0,5 | -1  | -2   | $\emptyset$ | 2   | 1   | 0,5 |
>[!tldr] Remarques :
>On dit que la courbe représentative de la fonction inverse est une hyperbole avec pour centre l'origine du repère
>La courbe représentative de la fonction inverse est symétrique par rapport à l'origine

>[!FAQ] Propriété :
>La fonction inverse est strictement décroissant sur $]-\infty;0$ et $]0;+\infty$
>>[!tldr] Remarque :
>>La fonction inverse n'est pas strictement décroissante sur $R$
>>$-2<2$
>>$\frac {1} {-2}<\frac {1} {2}$

>[!FAQ] Propriété :
>Soit $k$ un réel. L'équation $\frac {1} {x}=k$ a pour ensemble de solutions :
>- $S=\emptyset$ si $k=0$
>- $S=(\frac {1} {k})$ si $k\ne 0$
## III- Fonction racine carrée
### 1) Définition
>[!FAQ] Définition :
>La fonction racine carrée est la fonction $f$ définie sur $[0;\infty]$ par $f(x)=\sqrt {x}$
### 2) Courbe représentative et variations
Tableau de variations :

| x    | 0   | 0,25 | 1   | 4   | 9   |
| ---- | --- | ---- | --- | --- | --- |
| f(x) | 0   | 0,5  | 1   | 2   | 3   |

>[!FAQ] Propriété :
>La fonction racine carrée est strictement croissante sur $[0;+\infty[$

### 3) Equation et Inéquations
>[!FAQ] Propriété :
>Soit $k$ un réel
>L'équation $\sqrt {x}=k$ admet comme ensemble de solutions :
>- $S=\emptyset$ si $k<0$
>- $S=\{k^2\}$ si $k\ge 0$

>[!EXAMPLE] Exemples :
>1) $\sqrt {x}=4$ : $S=\{16\}$
>2) $\sqrt {x}=-3$ : $S=\emptyset$
>3) $\sqrt {x}\le 3$ : $S=\{0;9\}$
>4) $\sqrt {x}>5$ : $S=]25;+\infty[$

## IV- Fonction cube
### 1) Définition
>[!FAQ] Définition :
>La fonction cube est la fonction $f$ définie sur $R$ par $f(x)=x^3$

>[!FAQ] Propriété :
>La fonction cube est impaire

>[!TIP] Démonstration :
>Pour tout réel $x$, $f(-x)=(-x)^3=-x^3=-f(x)$

>[!FAQ] Tableau de valeurs :

| x    | -2  | -1  | 0   | 1   | 2   |
| ---- | --- | --- | --- | --- | --- |
| f(x) | -8  | -1  | 0   | 1   | 8   |
>[!FAQ] Propriété :
>La fonction cube est strictement croissante sur $R$
```functionplot
---
title: Fonction cube
xLabel: 
yLabel: 
bounds: [-3,3,-9,9]
disableZoom: false
grid: true
---
f(x)=x^3
```
### 3) Equations et inéquations
>[!FAQ] Propriété :
>Soit $k$ un réel
>L'équation $x^3=k$ admet une unique solution, appelée racine cubique de $k$
>On la note $k^{\frac {1} {3}}$ ou $\sqrt [3] {k}$
>L'inéquation $x^3<k$ a pour solutions $]-\infty;\sqrt [3] {k}$

>[!EXAMPLE] Exemples :
>1) $x^3=2$ : $S=\{\sqrt [3] {2}\}$
>2) $x^3=27$ : $S=\{3\}$
>3) $x^3<10$ : $S=]-\infty;\sqrt [3] {10}[$
>4) $x^3\ge 8$ : $=[2;+\infty[$

