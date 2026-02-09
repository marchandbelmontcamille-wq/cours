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

Allez sur la page de téléchargement : [[V1.1.0]]
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

© 2026 Camille Marchand Belmont. Tous droits réservés.
Consultation et usage personnel autorisés. Toute modification
ou redistribution nécessite l'autorisation écrite de l'auteur.
[Lire la licence complète]()

## Changelogs
##### V1.0.0
Version initiale
##### V1.1.0
Ajout de la page des paramètres
##### V1.1.1 (en préparation)
- Réglage d'un bug d'affichage sur la partie EDT du dashboard
- Amélioration de la compatibilité avec les proxies scolaires
- Ajout de la license
## 🙏 Crédits
- Camille Marchand Belmont - Conception, direction et développement
- [Claude](https://claude.ai) (Anthropic) - Assistance au développement
- [pronotepy](https://github.com/bain3/pronotepy) - API Python non-officielle pour Pronote
- [Textual](https://textual.textualize.io/) - Framework TUI moderne pour Python