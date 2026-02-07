Client Pronote moderne en ligne de commande (TUI), construit avec [Textual](https://textual.textualize.io/) et [pronotepy](https://github.com/bain3/pronotepy)

## ✨ Fonctionnalités

- 📅 **Emploi du temps** - Visualisez votre emploi du temps avec navigation par semaine
- 📝 **Notes** - Consultez vos notes et moyennes par période (trimestre/semestre)
- 📚 **Devoirs** - Liste des devoirs à venir sur 14 jours
- 💾 **Sauvegarde des identifiants** - Option "Se souvenir de moi"
- 🔄 **Mises à jour automatiques** - Notification quand une nouvelle version est disponible

## 📋 Prérequis

- Python 3.8 ou supérieur
- Un compte Pronote valide

## 🚀 Installation

1. **Téléchargez le fichier ZIP** : [[Pynote_V1.0.0.zip]]

2. Décompressez le fichier ZIP où vous stockez vos programmes(Recommandation : `C:/Users/Utilisateur/AppData/Local/Pynote`) 

3.  Ouvrez un terminal dans le dossier de Pynote

4. **Installez les dépendances**
   ```bash
   pip install --user -r requirements.txt
   ```

## ▶️ Utilisation

lancez dans le terminal :
```bash
python Pynote.py
```

## 🔍 Ajouter à la barre de recherche Windows

1. Faites clic droit sur `Pynote.py`, clique sur `Plus d'options`, puis sur `Créer un raccourci`

2. Renommez le raccourci en `Pynote` (facultatif) 

3. `Win + R` → tape `shell:programs` → Entrée

4. Copiez le raccourci dans ce dossier

5. Tapez "Pynote" dans la recherche Windows !
## 🔒 Sécurité

- Option "Se souvenir de moi" stocke les identifiants dans `~/.pynote_credentials.json`
- La connexion utilise HTTPS vers les serveurs Pronote

## 🐛 Dépannage

### Erreur de connexion
- Vérifiez l'URL Pronote (doit se terminer par `/pronote/eleve.html?login=true`)
- Vérifiez vos identifiants
- L'erreur 23 signifie trop de connexions, attendez quelques minutes

### Problème d'affichage
- Assurez-vous que votre terminal supporte les caractères Unicode
- Essayez d'agrandir la fenêtre du terminal

## 📄 Licence

MIT License - Utilisez ce projet librement.

## 🙏 Crédits

- [pronotepy](https://github.com/bain3/pronotepy) - API Python non-officielle pour Pronote
- [Textual](https://textual.textualize.io/) - Framework TUI moderne pour Python