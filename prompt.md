# Prompt de classification des scans

## Contexte

Tu vas m'aider a classer mes feuilles de cours scannees.

## Chemins

- **Source (scans bruts):** `C:\Users\camillemarchandbelmo\quartz\content\scan`
- **Destination (images classees):** `C:\Users\camillemarchandbelmo\quartz\content\Images`
- **Index:** `C:\Users\camillemarchandbelmo\quartz\content\fichiers.md`

## Etapes

1. **Avant de commencer**, lis le fichier `fichiers.md` pour voir l'index existant et connaitre les prefixes deja utilises et leur dernier numero
2. **Regarde toutes les images** dans le dossier `Images` pour voir ce qui est deja classe
3. **Regarde toutes les images** dans le dossier `scan` pour voir les nouveaux fichiers a classifier
4. Pour chaque nouveau scan, **lis le texte de l'image** pour voir a quoi ca correspond
5. **Deplace** chaque fichier de `scan` vers `Images` en le renommant avec le code (ex: `FR-1.jpg`)
6. **Regenere l'index** `fichiers.md` en scannant tout le dossier `Images`

## Format de l'index fichiers.md

L'index est organise par matiere. Pour chaque matiere, un titre `##` puis chaque fichier avec son code en gras et un embed Obsidian:

```
## Francais

- **FR-1**
  ![[FR-1.jpg]]
- **FR-2**
  ![[FR-2.jpg]]

## Anglais

- **AN-1**
  ![[AN-1.png]]

## Mathematiques

- **MA-1**
  ![[MA-1.pdf]]
- **MA-2**
  ![[MA-2.pdf]]
```

## Regles

- Si un prefixe est nouveau (pas encore dans l'index), demande-moi quel nom de matiere lui associer
- Trie les matieres par ordre alphabetique dans l'index
- Trie les numeros par ordre croissant dans chaque matiere
- Ne touche pas aux fichiers deja dans `Images`
- Si tu vois que 2-3 images font partie du mm doc, commence pas le début en attribuant l'id