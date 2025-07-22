# 🛠️ Git Fixup Workshop

Bienvenue dans cet atelier Git dédié à la commande `fixup` et à la maîtrise du rebase interactif avec `--autosquash`.

## 🎯 Objectifs

- Comprendre le rôle de `git commit --fixup` dans la correction ciblée
- Apprendre à nettoyer un historique avec `git rebase -i --autosquash`
- Pratiquer sur un projet minimal et interactif

## 🚀 Démarrage

1. Clonez le dépôt :

```bash
git clone git@github.com:RymRIA/workshop-git-fixup.git
cd workshop-git-fixup
```

2. Créez votre branche personnelle (remplacez `<prenom>` par le vôtre) :

```bash
git checkout -b atelier-fixup/<prenom>
```

3. Créez un fichier `index.js` :

```bash
touch index.js
```

4. Ajoutez du code dans ce fichier, puis suivez les consignes fournies dans Notion ou en live pour simuler des erreurs, créer des fixups et nettoyer votre historique !

## 🧠 Astuces Git utiles

```bash
git log --oneline            # Pour identifier les commits à corriger
git commit --fixup=<SHA>     # Pour créer un commit de correction ciblé
git rebase -i --autosquash   # Pour fusionner proprement les fixups
git log --oneline --graph    # Pour visualiser l’historique nettoyé
```

---

