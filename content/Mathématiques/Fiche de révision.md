## I — Fonction affine

### Définition
Une fonction affine c'est une fonction de la forme :
$$f(x) = mx + p$$
- **$m$** = coefficient directeur (la pente de la droite)
- **$p$** = ordonnée à l'origine (là où la droite coupe l'axe des ordonnées)

### Cas particuliers
- $m = 0$ → **fonction constante** ($f(x) = p$, droite horizontale)
- $p = 0$ → **fonction linéaire** ($f(x) = mx$, passe par l'origine)

### Trouver $m$ à partir de deux points
$$m = \frac{f(b) - f(a)}{b - a}$$

### Sens de variation
- $m > 0$ → $f$ **croissante** 📈
- $m < 0$ → $f$ **décroissante** 📉
- $m = 0$ → $f$ **constante**

---

## II — Tableau de signes d'une fonction affine

### Méthode en 3 étapes :
1. **Trouver la racine** : résoudre $f(x) = 0$
2. **Regarder le signe de $m$** pour savoir le sens de variation
3. **Construire le tableau** :
   - Si $m > 0$ : **négatif puis positif**
   - Si $m < 0$ : **positif puis négatif**

---

## III — Tableaux de signes produit et quotient

### Méthode :
1. Faire le tableau de signes de **chaque** fonction affine séparément
2. Les regrouper dans **un seul tableau**
3. Appliquer la règle des signes ligne par ligne

### ⚠️ Attention pour les quotients :
- Numérateur s'annule → on met **0**
- Dénominateur s'annule → **double barre $||$** (valeur interdite !)

---

# Fiche de révision — Chapitre 10 : Statistiques

---

## I — Vocabulaire

- **Population** : l'ensemble qu'on étudie
- **Caractère** : la propriété étudiée
- **Effectif** : nombre d'éléments qui ont une certaine valeur
- **Fréquence** : $\frac{\text{effectif de la valeur}}{\text{effectif total}}$
- **Classes** : intervalles sans valeur commune pour regrouper les données

> ⚠️ La somme des effectifs = effectif total et la somme des fréquences = 1

---

## II — Moyenne

### Avec les effectifs :
$$\bar{x} = \frac{x_1 \times n_1 + x_2 \times n_2 + ... + x_k \times n_k}{n_1 + n_2 + ... + n_k}$$

### Avec les fréquences :
$$\bar{x} = x_1 \times f_1 + x_2 \times f_2 + ... + x_k \times f_k$$

### Avec des classes :
On prend le **centre de la classe** : pour $[a;b[$, le centre c'est $\frac{a+b}{2}$

### Linéarité de la moyenne :
- On multiplie toutes les valeurs par $a$ → la moyenne est multipliée par $a$
- On ajoute $b$ à toutes les valeurs → la moyenne augmente de $b$

---

## III — Écart-type

### Variance :
$$V = \frac{n_1(x_1 - \bar{x})^2 + n_2(x_2 - \bar{x})^2 + ... + n_k(x_k - \bar{x})^2}{n_1 + n_2 + ... + n_k}$$

### Écart-type :
$$\sigma = \sqrt{V}$$

- $\sigma$ **grand** → valeurs **dispersées**
- $\sigma$ **petit** → valeurs **homogènes**

---

## IV — Médiane

La médiane $Me$ sépare la série ordonnée en deux parties égales :
- $n$ **impair** → valeur de rang $\frac{n+1}{2}$
- $n$ **pair** → moyenne des deux valeurs du milieu

---

## V — Quartiles et écart interquartile

- **$Q_1$** : on calcule $\frac{n}{4}$, on arrondit à l'entier supérieur → rang de $Q_1$
- **$Q_3$** : on calcule $\frac{3n}{4}$, on arrondit à l'entier supérieur → rang de $Q_3$
- **Écart interquartile** : $Q_3 - Q_1$

> Environ **50%** des valeurs sont entre $Q_1$ et $Q_3$

---

## VI — Étendue

$$\text{Étendue} = \text{valeur max} - \text{valeur min}$$

