## I- Vocabulaire
### 1) Vocabulaire général
>[!FAQ] Définition :
>La population est l'ensemble que l'on étudie
>>[!EXAMPLE] Exemple :
>>La classe de 2°14

>[!FAQ] Définition : Le caractère est la propriété étudiée
>>[!EXAMPLE] Exemple :
>>Le temps de trajet pour aller au lycée
### 2) Effectif et fréquence
>[!FAQ] Définition
>L'effectif d'une valeur est le nombre d'éléments de la population qui possèdent cette valeur
>La fréquence  d'une valeur est $\frac {\text {effectif de la valeur}} {\text {effectif total}}$
>>[!TIP] Remarque :
>>La somme de tous les effectifs est égale à l'effectif total
>>La somme de toutes les fréquences est égale à 1
>>Pour étudier une série, on peut regrouper différentes valeurs dans des intervalles sans valeur commune, que l'on appelle des classes
>
>>[!EXAMPLE] Exemple :
>>Voici les notes obtenues à une interrogation notée sur 5 dans une classe de 30 élèves
>>2-2-2-2-2-2-2-3-3-3-3-3-3-3-3-4-4-4-4-4-4-4-4-5-5-5-5-5-5-5
>>cf *T1* et *T2*


| Note      | 0   | 1   | 2                | 3                | 4                | 5                | Total |
| --------- | --- | --- | ---------------- | ---------------- | ---------------- | ---------------- | ----- |
| Effectif  | 0   | 0   | 7                | 8                | 8                | 7                | 30    |
| Fréquence | 0   | 0   | $\frac {7} {30}$ | $\frac {8} {30}$ | $\frac {8} {30}$ | $\frac {7} {30}$ | 1     |
T1

| Note      | $[0;2,5[$        | $[2,5;5]$         | Total |
| --------- | ---------------- | ----------------- | ----- |
| Effectif  | 7                | 23                | 30    |
| Fréquence | $\frac {7} {30}$ | $\frac {23} {30}$ | 1     |
T2

>[!TIP] Remarque :
>Dans toute la suite, le tableau des effectifs d'une série sera noté *T3*
>Dans toute la suite, le tableau des fréquences sera noté *T4*


| Valeurs   | $x_1$ | $x_2$ | ... | $x_k$ |
| --------- | ----- | ----- | --- | ----- |
| Effectifs | $n_1$ | $n_2$ | ... | $n_k$ |
T3

| Valeurs    | $x_1$ | $x_2$ | ... | $x_k$ |
| ---------- | ----- | ----- | --- | ----- |
| Fréquences | $f_1$ | $f_2$ | ... | $f_k$ |
T4
## II- Moyenne et écart-type
### 1) Moyenne
>[!FAQ] Définition :
>>[!FAQ] Si on dispose d'un tableau des effectifs
>>La moyenne de la série notée $x$ est définie par :
>>$\frac {x_1\times n_1+x_2\times n_2+...+x_k\times n_k} {n_1+n_2+...+n_k}$
>
>>[!FAQ] Si on dispose d'un tableau des fréquences
>>La moyenne de la série notée $x$ est définie par :
>>$x_1\times f_1+x_2\times f_2+...+x_K\times f_k$
>
>>[!TIP] Remarque :
>>Si on a des classes, on prend comme valeur le centre des classes. Pour $[a;b[$, le centre est $\frac {a+b} {2}$
>
>>[!EXAMPLE] Exemple :
>>1) Calculer la moyenne pour le tableau des effectifs des notes : 3,5
>>2) Calculer la moyenne pour le tableau des fréquences des notes : 3,5
>>3) Calculer la moyenne pour le tableau des effectifs des classes des notes : 3,17
>
>>[!FAQ] Propriété : *Linéarité de la moyenne*
>>Si toutes les valeurs de la série sont multipliées par une même valeur $a$, alors la moyenne est multipliée est multipliée par $a$.
>>Si on ajoute une valeur $b$ à toutes les valeurs de la série, alors la moyenne est augmenté de $b$
### 2) Ecart-type
>[!FAQ] Définition :
>La variance d'une série statistique est le réel $V$ défini par :
>$V=\frac {n_1\times (x_1-\bar {x})^2+n_2\times (x_2-\bar {x})^2+...+n_k\times (x_k-\bar {x}) } {n_1+n_2+...+n_k}$
>L'écart-type d'une série est le réel $\sigma$ défini par :
>$\sigma=\sqrt {V}$

>[!TIP] Remarque :
>L'écart-type mesure la dispersion des valeurs autour de la moyenne
>Plus il est grand, plus les valeurs sont dispersées
>Plus il est faible, plus les valeurs sont homogènes
## III- Médiane et écart-interquartile

### 1) Médiane
>[!FAQ] Définition :
>L'effectif cumulé croissant d'une valeur est la somme des effectifs de toutes les valeurs qui sont inférieures ou égales à cette valeur.
>>[!TIP] Remarque :
>>On définit de même la fréquence cumulée croissante
>
>>[!FAQ] Définition :
>>Dans une série statistique de $n$ valeurs ordonnées dans l'ordre croissant, la médiane, notée notée $Me$ est un nombre qui sépare la série en deux série de même effectif
>>- Si $n$ est impair, la médiane est la valeur du milieu, de rang $\frac {n+1} {2}$
>>- Si $n$ est pair, la médiane est la moyenne des deux valeurs
>
>>[!EXAMPLE] Exemple :
>>10, 11, 12, 13, 14, 15, 16
>>Il y a 7 valeurs et 7 est impair
>>$\frac {7+1} {2}=4$ La médiane est la 4$^{eme}$ valeur $Me=13$
>>
>>Il y a 30 valeurs et 30 est pair
>>La médiane est la moyenne de la 15$^{eme}$ et de la 16$^{eme}$ valeur
>>$Me=\frac {3+4} {2}=3,5$
### 2) Ecart interquartile
>[!FAQ] Définition :
>Le premier quartile est la plus petite valeur de la série telle que au moins un quart des valeurs lui soient inférieures ou égales. On le note $Q_1$
>Le troisième quartile est la plus petite valeur de la série telle que au moins trois quart des valeurs lui soient inférieures ou égales. On le note $Q_3$
>>[!TIP] Méthode :
>>Les valeurs doivent être ordonnées dans l'ordre croissant
>>On note $n$ l'effectif total
>>Pour $Q_1$, on calcule $\frac {1} {4}n$, on arrondit à l'entier supérieur que l'on note $K$ et on prend la valeur de rang $K$
>>Pour $Q_3$, on calcule $\frac {3} {4}n$, on arrondit à l'entier supérieur que l'on note $K$ et on prend la valeur de rang $K$
>
>>[!FAQ] Définition :
>>L'écart interquartile est la différence $Q_3-Q_1$
>
>>[!TIP] Remarque :
>>Environ 50% des valeurs sont comprises entre $Q_1$ et $Q_3$
## IV- Compléments
>[!FAQ] Définition :
>L'étendue est la différence entre la plus grande valeur et la plus grande valeur