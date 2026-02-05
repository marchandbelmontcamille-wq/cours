## Fiche de Révision : Les Vecteurs
### I- Notion de Vecteur

#### 1) Définition
- Un vecteur $\overrightarrow {AB}$ symbolise le déplacement de $A$ vers $B$.
- Il est représenté par une flèche de $A$ vers $B$.
- Un vecteur a une infinité de représentants.
- Le vecteur nul est $\overrightarrow {AA}$, noté $\overrightarrow {0}$.

#### Caractéristiques d'un vecteur $\overrightarrow {AB}$ (pour $A \neq B$) :
- **Direction :** celle de la droite $(AB)$.
- **Sens :** de $A$ vers $B$.
- **Norme :** $||\overrightarrow {AB}||$, qui est la longueur $AB$.
- On peut aussi noter un vecteur avec une seule lettre minuscule, par exemple $\overrightarrow {u}$.

#### 2) Égalités de deux vecteurs
- $\overrightarrow {AB}=\overrightarrow {CD}$ signifie que $D$ est l'image de $C$ par la translation de $A$ vers $B$.
- **Propriété :** Deux vecteurs $\overrightarrow {AB}$ et $\overrightarrow {CD}$ sont égaux si et seulement si $ABCD$ est un parallélogramme (éventuellement aplati).
- **Exemple :** Si $ABCD$ et $CEFD$ sont des parallélogrammes, alors $\overrightarrow {AB}=\overrightarrow {DC}$ et $\overrightarrow {DC}=\overrightarrow {FE}$, donc $\overrightarrow {AB}=\overrightarrow {FE}$, ce qui implique que $ABEF$ est un parallélogramme.
- **Milieu :** $K$ est le milieu de $[AB]$ si et seulement si $\overrightarrow {AK}=\overrightarrow {KB}$.

### II- Coordonnées d'un vecteur dans un repère

#### Définition
- Dans un repère du plan, les coordonnées d'un vecteur $\overrightarrow {u}$ sont celles du point $M$ tel que $\overrightarrow {OH}=\overrightarrow {u}$. On les note $\begin {pmatrix} x\\y\end {pmatrix}$.

#### Propriétés
- Si $A(x_A;y_A)$ et $B(x_B;y_B)$, alors $\overrightarrow {AB}\begin {pmatrix} x_B-x_A\\y_B-y_A\end {pmatrix}$.
- Deux vecteurs sont égaux si et seulement si ils ont les mêmes coordonnées.
- Dans un repère orthonormé, la norme d'un vecteur $\overrightarrow {u}\begin {pmatrix} x\\y\end {pmatrix}$ est $||\overrightarrow {u}||=\sqrt {x^2+y^2}$.

### III- Opérations sur les vecteurs

#### 1) Somme de deux vecteurs
- La somme de deux translations est une translation.
- La somme de deux vecteurs $\overrightarrow {u}$ et $\overrightarrow {v}$ est le vecteur associé à l'enchaînement des translations.
- L'ordre n'a pas d'importance : $\overrightarrow {u}+\overrightarrow {v}=\overrightarrow {v}+\overrightarrow {u}$.
- **Relation de Chasles :** Pour tous points $A$, $B$ et $C$, $\overrightarrow {AB}+\overrightarrow {BC}=\overrightarrow {AC}$.
- **Coordonnées :** Si $\overrightarrow {u}\begin {pmatrix}x\\y\end {pmatrix}$ et $\overrightarrow {v}\begin {pmatrix}x'\\y'\end {pmatrix}$, alors $\overrightarrow {u}+\overrightarrow {v}\begin {pmatrix}x+x'\\y+y'\end {pmatrix}$.
- **Règle du parallélogramme :** $ABCD$ est un parallélogramme si et seulement si $\overrightarrow {AB}+\overrightarrow {AD}=\overrightarrow {AC}$.

#### 2) Opposé d'un vecteur, différence de deux vecteurs
- **Vecteur opposé :** Le vecteur opposé de $\overrightarrow {u}$, noté $\overrightarrow {-u}$, est tel que $\overrightarrow {u}+(\overrightarrow {-u})=\overrightarrow {0}$. Il a la même direction et norme que $\overrightarrow {u}$ mais un sens contraire.
- **Propriété :** $\overrightarrow {BA}=\overrightarrow {-AB}$.
- **Différence :** $\overrightarrow {u}-\overrightarrow {v}$ est défini par $\overrightarrow {u}+(\overrightarrow {-v})$.
- **Coordonnées :** Si $\overrightarrow {u}\begin {pmatrix}x\\y\end {pmatrix}$ et $\overrightarrow {v}\begin {pmatrix}x'\\y'\end {pmatrix}$, alors $\overrightarrow {-u}\begin {pmatrix}-x\\-y\end {pmatrix}$ et $\overrightarrow {u}-\overrightarrow {v}\begin {pmatrix}x-x'\\y-y'\end {pmatrix}$.

#### 3) Produit par un nombre réel
- Soient $\overrightarrow {u}$ un vecteur et $k$ un réel. Le produit $k\overrightarrow {u}$ est défini par :
    - Si $k=0$ ou $\overrightarrow {u}=\overrightarrow {0}$, alors $k\overrightarrow {u}=\overrightarrow {0}$.
    - Sinon, $k\overrightarrow {u}$ a :
        - La même direction que $\overrightarrow {u}$.
        - Le même sens que $\overrightarrow {u}$ si $k>0$, et le sens contraire si $k<0$.
        - Une norme de $|k|\times ||\overrightarrow {u}||$.
- **Coordonnées :** Si $\overrightarrow {u}\begin {pmatrix} x \\ y\end {pmatrix}$, alors $k\overrightarrow {u}\begin {pmatrix} kx \\ ky\end {pmatrix}$.