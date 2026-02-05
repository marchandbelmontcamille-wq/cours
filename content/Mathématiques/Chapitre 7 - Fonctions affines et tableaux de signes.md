## I- Fonction affine
### 1) Définition et représentation graphique
>[!FAQ] Définition :
>Une fonction affine est une fonction $f$ définie sur $R$ par $f(x)=mx+p$ où $m$ et $p$ sont deux réels.
>>[!NOTE] Cas particuliers :
>>Si $m=0$, la fonction est définie par $f(x)=p$. C'est une fonction constante.
>>Si $p=0$, la fonction est définie par $f(x)=mx$. C'est une fonction linéaire.
>
>>[!EXAMPLE] Exemple :
>>f(x)=5x+2
>>f(x)=10
>>f(x)=2x
>
>>[!FAQ] Propriété :
>>Soit $f$ une fonction affine définie par $f(x)= mx+p$
>>Sa courbe représentative est la droite d'équation $y=mx+p$
>>$m$ est le coefficient directeur de la droite
>>$p$ est l'ordonnée à l'origine
>
>>[!FAQ] Propriété :
>>Soient $f$ une fonction affine définie par $f(x)=mx+p$ et $a$ et $b$ deux réels
>>On a $m=\frac {f(b)-f(a)} {b-a}$
>
>>[!EXAMPLE] Exemple :
>>Déterminer la fonction affine $f$ telle que $f(1)=2$ et $f(-1)=3$
>>$f$ est une fonction affine, donc pour tout réel $x$, $f(x)=mx+p$
>>$m=\frac {f(1)-f(-1)} {1-(-1)}=\frac {2-(-3)} {2}=\frac {5} {2}$
>>Donc $f(x)=\frac {5} {2}x+p$
>>Or $f(1)=2$
>>Donc $\frac {5} {2}\times 1+p=2$
>>Donc $p=-\frac {1} {2}$
>>Donc pour tout réel $x$, $f(x)=\frac {5} {2}x-\frac {1} {2}$
### 2) Sens de variation
>[!FAQ] Propriété : 
>Soient $f$ une fonction affine définie par $f(x)=mx+p$
>Si $m>0$, alors $f$ est strictement croissante
>Si $m<0$, alors $f$ est strictement décroissante
>Si $m=0$, alors $f$ est constante
>>[!EXAMPLE] Exemples :
>>1) $f(x)=2x+1$ 
>>$m=2>0$ Donc $f$ est strictement croissante
>>2) $g(x)=-x+3$
>>$m=-1<0$ Donc $g$ est strictement décroissante
### 3) Tableaux de signes
>[!EXAMPLE] Exemples :
>1) Soit $f$ la fonction affine définie par $f(x)=2x-6$
>1$^{ere}$ étape : On cherche quand $f(x)$ s'annule
>$f(x)=0$ <=> $2x-6=0$ <=> $2x=6$ <=> $x=3$
>2$^{eme}$ étape : On étudie les variations de $f$
>$m=2>0$, donc $f$ est strictement croissante
>3$^{eme}$ étape : on construit le tableau de signes
>2) Soit $f$ la fonction affine définie par $f(x)=-3x+6$
>$f(x)=0$ <=> $-3x+6=0$ <=> $-3x=-6$ <=> $x=2$
>$m=-3<0$, donc $f$ est strictement décroissante
## II- Tableaux de signes produit et quotient
>[!TIP] Méthode :
>Pour étudier le signe d'un produit ou d'un quotient de deux fonctions affines, on regroupe dans un seul tableau les tableaux de signes de deux fonctions
>La présence d'un "0" signifie que l'expression s'annule. La présence d'une double barre verticale signifie que l'expression n'est pas définie
>>[!EXAMPLE] Exemple :
>>Dresser le tableau de signes de $(2x-6)\times(-3x+6)$
>>Voir *T1*

| x                      | -$\infty$ | 2    | 2   | +$\infty$ |
| ---------------------- | --------- | ---- | --- | --------- |
| $2x-6$                 | -         | \|   | 0   | +         |
| $-3x+6$                | +         | 0    | \|  | -         |
| $(2x-6)\times(-3x+6)$  | -         | 0    | 0   | -         |
| $\frac {2x-6} {-3x+6}$ | -         | \|\| | 0   | -         |
*T1*
