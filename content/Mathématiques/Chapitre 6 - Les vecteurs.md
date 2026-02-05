## I- Notion de vecteur
### 1) Définition
>[!FAQ] Définition :
>Soient $A$ et $B$ deux points
> La translation qui transforme le point $A$ en point $B$ est la transformation qui à tout point $M$ associe l'unique point $N$ tel que ABNM soit un parallélogramme
> A cette translation, on associe le vecteur $\overrightarrow {AB}$, qui symbolise le déplacement de $A$ vers $B$, ou de $N$ vers $M$
> On le représente par une flèche allant de $A$ vers $B$
>>[!TIP] Remarque :
>>Un vecteur a une infinité de représentants
>>Le vecteur $\overrightarrow {AA}$ est le vecteur nul. On le note $\overrightarrow {0}$
>
>>[!FAQ] Propriété :
>>Soient $A$ et $B$ deux points distincts
>>Le vecteur $\overrightarrow {AB}$ est caractérisé par :
>>- Sa direction : celle de la droite $(AB)$
>>- Son sens : De $A$ vers $B$
>>- Sa norme notée $||\overrightarrow {AB}||$ : la longueur AB
>
>>[!TIP] Remarque : 
>>On peut également noter un vecteur avec une seule lettre minuscule
>>Par exemple : $\overrightarrow {u}$
>>La norme du vecteur $\overrightarrow {u}$ se note $||\overrightarrow {u}||$
### 2) Egalités de deux vecteurs
>[!FAQ] Définition :
>Dire que $\overrightarrow {AB}=\overrightarrow {CD}$ signifie que $D$ est l'image de $C$ par la translation qui transforme $A$ en $B$
>>[!FAQ] Propriété :
>>Deux vecteurs $\overrightarrow {AB}$ et $\overrightarrow {CD}$ sont égaux si et seulement si $ABCD$ est un parallélogramme (éventuellement aplati)
>
>>[!TIP] Remarque :
>>Le parallélogramme $ABDC$ est aussi caractérisé par les trois autres égalités :
>>$\overrightarrow {BA}=\overrightarrow {BC}$
>>$\overrightarrow {DB}=\overrightarrow {CA}$
>>$\overrightarrow {BD}=\overrightarrow {AC}$
>>Une seule égalité suffit à prouver que c'est un parallélogramme
>
>>[!EXAMPLE] Exercice :
>>$ABCD$ et $CEFD$ sont deux parallélogrammes
>>Quelle est la nature de $ABEF$ ? Justifier
>>$ABCD$ est un parallélogramme
>>Donc $\overrightarrow {AB}=\overrightarrow {DC}$
>>$CEFD$ est un parallélogramme 
>>Donc $\overrightarrow {DC}=\overrightarrow {FE}$
>>Alors $\overrightarrow {AB}=\overrightarrow {FE}$
>>Donc $ABEF$ est un parallélogramme
>
>>[!FAQ] Propriété :
>>Le point $K$ est le milieu de $[AB]$ si et seulement si $\overrightarrow {AK}=\overrightarrow {KB}$
## II- Coordonnées d'un vecteur dans un espace
>[!FAQ] Définition :
>Dans un repère du plan, les coordonnées du vecteur $\overrightarrow {u}$ sont les coordonnées du point $M$ tel que $\overrightarrow {OH}=\overrightarrow {u}$
>Si $M(x;y)$, on note $\begin {pmatrix} x\\y\end {pmatrix}$ les coordonnées de $\overrightarrow {u}$
>>[!FAQ] Propriété :
>>Dans un repère, si $A(x_A;y_A)$ et $B(x_B;y_B)$ alors $\overrightarrow {AB}\begin {pmatrix} x_B-x_A\\y_B-y_A\end {pmatrix}$
>>$\overrightarrow {AB}\begin {pmatrix} x_B-x_A\\y_B-y_A\end {pmatrix}$
>>
>>$\overrightarrow {AB}\begin {pmatrix} -2-2\\2-(-1)\end {pmatrix}$ donc $\overrightarrow {AB}\begin {pmatrix} -4\\3\end {pmatrix}$
>>
>>$\overrightarrow {CA}\begin {pmatrix} x_A-x_C\\y_A-y_C\end {pmatrix}$
>>
>>$\overrightarrow {CA}\begin {pmatrix} 2-3\\-1-1\end {pmatrix}$ donc $\overrightarrow {CA}\begin {pmatrix} -1\\-2\end {pmatrix}$
>
>>[!FAQ] Propriété :
>>Deux vecteurs sont égaux si et seulement si ils ont les mêmes coordonnées dans un repère du plan
>
>>[!FAQ] Propriété :
>>Dans un repère orthonormé, soit $\overrightarrow {u}\begin {pmatrix} x\\y\end {pmatrix}$
>>$||\overrightarrow {u}||=\sqrt {x^2+y^2}$
## III- Opérations sur les vecteurs
### 1) Somme de deux vecteurs
>[!TIP] Remarque :
>La somme de deux translations est aussi une translation

>[!FAQ] Définition : 
>La somme de deux vecteurs $\overrightarrow {u}$ et $\overrightarrow {v}$ est le vecteur assotié à la translation résultant de l'enchainement des translations de vecteur $\overrightarrow {u}$ et de vecteur $\overrightarrow {v}$
>>[!TIP] Remarque :
>>L'ordre n'a pas d'importance : $\overrightarrow {u}+\overrightarrow {v}=\overrightarrow {v}+\overrightarrow {u}$
>
>>[!FAQ] Propriété : *Relation de Chasles*
>>Pour tous points $A$, $B$ et $C$ du plan, on a :$\overrightarrow {AB}+\overrightarrow {BC}=\overrightarrow {AC}$
>
>>[!FAQ] Propriété :
>>Dans un repère du plan, soient $\overrightarrow {u}\begin {pmatrix}x\\y\end {pmatrix}$ et $\overrightarrow {v}\begin {pmatrix}x'\\y'\end {pmatrix}$
>>Alors, $\overrightarrow {u}+\overrightarrow {v}\begin {pmatrix}x+x'\\y+y'\end {pmatrix}$
>
>>[!FAQ] Propriété : *Règle du parallélogramme*
>>$ABCD$ est un parallélogramme si et seulement si $\overrightarrow {AB}+\overrightarrow {AD}=\overrightarrow {AC}$
### 2) Opposé d'un vecteur, différence de deux vecteurs
>[!FAQ] Définition :
>Soit $\overrightarrow {u}$ un vecteur du plan
>Le vecteur opposé du vecteur $\overrightarrow {u}$, noté $\overrightarrow {-u}$ est le vecteur tel que $\overrightarrow {u}+(\overrightarrow {-u})=\overrightarrow {0}$
>C'est le vecteur qui possède la même direction et la même norme que $\overrightarrow {u} mais qui a un sens contraire
>>[!FAQ] Propriété :
>>Pour tous points $A$ et $B$ du plan, on a $\overrightarrow {BA}=\overrightarrow {-AB}$
>
>>[!FAQ] Définition :
>>Soient $\overrightarrow {u}$ et $\overrightarrow {v}$ deux vecteurs du plan
>>Le vecteur $\overrightarrow {u}-\overrightarrow {v}$ est défini par $\overrightarrow {u}-\overrightarrow {v}-\overrightarrow {u}+(\overrightarrow {-v})$
>
>>[!FAQ] Propriété :
>>Dans un repère du plan, soient $\overrightarrow {u}\begin {pmatrix}x\\y\end {pmatrix}$ et $\overrightarrow {v}\begin {pmatrix}x'\\y'\end {pmatrix}$
>>Alors $\overrightarrow {-u}\begin {pmatrix}-x\\-y\end {pmatrix}$ et $\overrightarrow {u}-\overrightarrow {v}\begin {pmatrix}x-x'\\y-y'\end {pmatrix}$
### 3) Produit par un nombre réel
>[!FAQ] Définition :
>Soient $\overrightarrow {u}$ un vecteur du plan et $k$ un réel.
>Le produit du vecteur $\overrightarrow {u}$ par le réel $k$, noté $k\overrightarrow {u}$ est défini par :
>Si $k=0$, ou $\overrightarrow {u}=0$, alors $k\overrightarrow {u}=0$
>Sinon, $k\overrightarrow {u}$ est le vecteur :
>- De même direction que $\overrightarrow {u}$
>- De même sens que $\overrightarrow {u}$ si $k>0$ et de sens contraire si $k<0$
>- De norme $|k|\times ||\overrightarrow {u}||$
>>[!FAQ] Propriété :
>>Dans un repère du plan, soient $\overrightarrow {u}\begin {pmatrix} x \\ y\end {pmatrix}$ et $k$ un réel
>>Alors $k\overrightarrow {u}\begin {pmatrix} kx \\ ky\end {pmatrix}$
>
>>[!EXAMPLE] Exemple :
>>Dans un repère du plan, soient $\overrightarrow {AB}\begin {pmatrix} 2 \\ 1\end {pmatrix}$ et $C$ et $D$ deux points tels que $\overrightarrow {AC}=3\overrightarrow {AB}$ et $\overrightarrow {AD}=-2\overrightarrow {AB}$
>>1) Dans un repère du plan, tracer un représentant du vecteur $\overrightarrow {AB}$, du vecteur $\overrightarrow {AC}$ et du vecteur $\overrightarrow {AD}$
>>2) Par le calcul, déterminer les coordonnées de $\overrightarrow {AC}$ et de $\overrightarrow {AD}$







