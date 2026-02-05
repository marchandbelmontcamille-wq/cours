---
title: "Chapitre 3 - Calcul littéral"
draft: false
tags:
  -
---

## I - Ecritures fractionnaires
>[!EXAMPLE] Exemples :
$\frac {4} {3} \times \frac {2} {7} = \frac {8} {21}$
$\frac {4} {3} + \frac {2} {7} = \frac {28} {21} + \frac {6} {21} = \frac {34} {21}$
$\frac {\frac {4} {3}} {\frac{2} {7}} = \frac {4} {3} \times \frac {7} {2} = \frac {28} {6} = \frac {14} {3}$
## II - Expressions algébriques

>[!FAQ] Définition : *Expressions algébriques*
>*Développer un produit*, c'est l'écrire sous forme d'une somme.
*Factoriser une somme*, c'est l'écrire sous forme d'un produit.
*Réduire une somme*, c'est écrire cette somme sous la forme la plus condensée possible, en regroupant les termes de même nature.
*Exemple :*
$3x^2+x-5-x^2+x+5=2x^2+2x$

>[!FAQ] Propriété : *Distributivité*
Pour tous réels a, b, c, d et k, on a :
$k(a+b)=ka+kb$
$(a+b)(c+d) = ac+ad+bc+bd$

>[!FAQ] Propriété : *Identités remarquables*
Pour tous réels a et b, on  a :
$(a+b)^2=a^2+2ab+b^2$
$(a-b)^2 = a^2 - 2ab +b^2$
$(a+b)(a-b)=a^2-b^2$

## III - Puissances et racines carrées
### 1) Puissances
>[!FAQ] Définition : *Puissances*
Pour tout réel a et tout entier naturel n :
$a^n=a\times a\times a\times a\times a\times ... \times a$ avec $n$ facteurs
si $a \ne 0$, $a^{-n}$ = $\frac {1} {a^n}$
Par convention $a^0=1$
*Exemples :*
$4^3=4\times 4\times 4=64$

>[!FAQ] Propriété : *Opérations avec les puissances*
Soient $a\in R$, $b\in R$, $m\in Z$ et $n\in Z$ 
$a^m\times a^n=a^{m+n}$
$\frac {a^m} {a^n}=a^{m-n}$
$(a^m)^n=a^{m\times n}$ 
>$(a\times b)^n=a^n\times b^n$
>$(\frac {a} {b})^n=\frac {a^n} {b^n}$ 

>[!EXAMPLE] Exemples :
$3^4\times 3^7=3^{4+7}=3^{11}$
$\frac {5^4} {5^6}=5^{4-6}=5^{-2}$
$(x^2)^4=x^{2\times 4}=x^8$
$3^8\times2^8=(3\times 2)^8=6^8$
$\frac {10^4} {5^4}=(\frac {10} {5})^4=2^4$
### 2) Racine carrée
>[!FAQ] Définition : *Racine carrée*
Soit $a$ un nombre réel positif ou nul
On appelle *racine carrée* de $a$ l'unique nombre réel ou positif donc le carré vaut $a$
On le note $\sqrt a$
On a donc $(\sqrt a)^2=\sqrt a \times \sqrt a=a$ 

>[!EXAMPLE] Exemple :
La racine carrée de 36 est 6

>[!FAQ] Propriété : *Opérations avec les racines carrées*
Pour tous réels $a$ et $b$ positifs
$\sqrt {a\times b}=\sqrt a\times \sqrt b$
Si $b\ne 0$, $\sqrt {\frac {a} {b}}=\frac {\sqrt a} {\sqrt b}$

>[!EXAMPLE] Exemple :
>$\sqrt 2 \times \sqrt 3=\sqrt {2\times 3}=\sqrt 6$

>[!FAQ] Remarque :
$\sqrt {a+b}\ne \sqrt a + \sqrt b$
$\sqrt {a-b}\ne \sqrt a-\sqrt b$
## IV - Equations et inéquations
### 1) Equations
>[!FAQ] Définition :
>*Résoudre une équation* dans un ensemble de réels $I$, c'est trouver tous les éléments de $I$ pour lesquels l'égalité est vérifiée : c'est l'ensemble des solutions
>Deux équations sont dites *équivalentes* si elles ont le même ensemble de solution
>On symbolise l'équivalence par une double flèche <=>

>[!TIP] Méthode :
>Il faut isoler l'inconnue dans un membre de l'égalité
>Pour cela, on ajoute, soustrait, multiplie ou divise par un même nombre les deux membres de l'égalité
#### Equations se ramenant à des équations du 1$^{er}$ degré
>[!FAQ] Propriété :
>Un produit est nul si et seulement si un au moins un de ses facteurs est nul

>[!FAQ] Propriété :
>Un quotient est nul si et seulement si son numérateur est nul et ET son dénominateur est non nul

>[!FAQ] Propriété :
>Soient $A$, $B$, $C$ et $D$ quatre expressions algébriques, avec $B\ne 0$ et $D\ne 0$
>$\frac {A} {B}=\frac {C} {D} <=> A\times D=B\times C$

>[!EXAMPLE] Exemples :
>1) $2x-3=0$ <=> $2x=3$ <=> $x=\frac {3} {2}$
>Cette équation n'a q'une solution : $\frac {3} {2}$
>$S=$ {$\frac {3} {2}$}
>2) $x(x+3)=0$ <=> $x=0$ ou $x+3=0$ <=> $x=0$ ou $x=-3$
>Cette équation a deux solutions : $0$ et $-3$
>$S=$ {$0;-3$}
>3) $2x+3=2x+2$ <=> $2x+3-2x=2x+2-2x$ <=> $3=2$
>Cette équation n'a pas de solutions
>$S=${$\emptyset$}  
>4) $\frac {x-3} {x+2}=0$ <=> $x-3=0$ et $x+2\ne 0$ <=> $x=3$ et $x\ne -2$
>Cette équation n'a qu'une solution : $3$
>$S=$ {$3$}

### 2) Inéquations
>[!FAQ] Définition :
>Soient $a$ et $b$ deux nombres réels
>On dit que $a$ est strictement inférieur à $b$, et on note $a < b$ si $b-a > 0$

>[!FAQ] Propriétés :
>Pour tous nombres réels $a$, $b$ et $c$ tels que $a<b$, on a $a+c<b+c$ (ajouter ou soustraire un même nombre conserve l'ordre)
>Si $c>0$, alors $a\times c < b\times c$  (multiplier ou diviser par un nombre strictement positif conserve l'ordre)
>Si $c<0$, alors $a\times c > b\times c$ (multiplier par un nombre strictement inverse l'ordre)

>[!EXAMPLE] Exemple : Résoudre l'inéquation suivante
>$x+1 < 3x+3$ <=> $x-3x<3-1$ <=> $-2x<-2$ <=> $x>-1$
>$S=]-1;+\infty[$
