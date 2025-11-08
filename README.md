# 🔐 Sec-lab

Collection simple et organisée de ressources pour l’audit web, le hardening et la formation :  
listes de mots, payloads, outils, guides, writeups et labs.

> **Usage éthique uniquement** — destiné à l’audit autorisé, la formation et la recherche.

---

### Structure

Les ressources sont importées directement **à la racine** pour garder une organisation claire et simple.  
Chaque dossier correspond à un projet ou un ensemble d’outils, contenant :
- le contenu importé (snapshot),
- un `README.md` minimal indiquant la **source**, la **licence**, et un **disclaimer éthique**.

---

### Règles d’usage

- 🔒 Utiliser uniquement sur des environnements **autorisés**.  
- ❌ Ne jamais committer de **secrets** (mots de passe, clés privées, tokens).  
- ⚖️ Respecter la **licence** du dépôt source.  
- ⚠️ Ajouter un **avertissement clair** pour tout POC sensible ou potentiellement dangereux.

---

### Mises à jour

Deux approches possibles :

- **Manuelle** : remplacer le dossier par un nouveau snapshot depuis la source.  
- **Automatique** : via un workflow GitHub Actions (ex. `.github/workflows/sync-external-sources.yml`) qui met à jour les ressources.

Exemple de `README.md` à placer dans chaque dossier importé :

```md
# <NomDuDossier> (mirror)
Source : <URL du dépôt d’origine>  
Licence : voir dépôt source  
Usage : éthique uniquement (audit autorisé, formation, recherche).
