# 🔐 Sec-lab

Collection simple et organisée de ressources pour l’audit web, le hardening et la formation :  
listes de mots, payloads, outils, guides, writeups et labs.

> **Usage éthique uniquement** — destiné à l’audit autorisé, la formation et la recherche.

---

### 🧩 Structure

Les ressources sont importées directement **à la racine** pour garder une organisation claire et simple.  
Chaque dossier correspond à un projet ou un ensemble d’outils, contenant :
- le contenu importé (snapshot),
- un `README.md` minimal indiquant la **source**, la **licence**, et un **disclaimer éthique**.

---

### 📜 Règles d’usage

- 🔒 Utiliser uniquement sur des environnements **autorisés**.  
- ❌ Ne jamais committer de **secrets** (mots de passe, clés privées, tokens).  
- ⚖️ Respecter la **licence** du dépôt source.  
- ⚠️ Ajouter un **avertissement clair** pour tout POC sensible ou potentiellement dangereux.

---

### ⚠️ Clause de non-responsabilité ⚠️

Ce dépôt est fourni **à des fins éducatives, de recherche et de tests autorisés uniquement**.  
L’auteur et les contributeurs de ce projet **déclinent toute responsabilité légale, civile ou pénale** concernant :
- l’usage abusif, illégal ou non autorisé des outils ou ressources présents dans ce dépôt,  
- les dommages directs ou indirects résultant de leur utilisation,  
- toute activité contraire aux lois en vigueur.  

En clonant, téléchargeant ou utilisant ce dépôt, **vous acceptez l’entière responsabilité** de vos actions et vous engagez à respecter les réglementations en matière de cybersécurité, notamment le **Code pénal français (articles 323-1 à 323-7)** sur l’accès et le maintien frauduleux dans un système de traitement automatisé de données.  

Ce projet n’est **pas affilié, soutenu ni approuvé** par les éditeurs ou organisations dont les outils sont référencés.  
Aucune garantie de bon fonctionnement, d’exactitude ou de sécurité n’est fournie.

---

### 🔄 Mises à jour

Deux approches possibles :

- **Manuelle** : remplacer le dossier par un nouveau snapshot depuis la source.  
- **Automatique** : via un workflow GitHub Actions (ex. `.github/workflows/sync-external-sources.yml`) qui met à jour les ressources.

---

### 🧾 Exemple de `README.md` pour un dossier importé

```md
# <NomDuDossier> (mirror)
Source : <URL du dépôt d’origine>  
Licence : voir dépôt source  
Usage : éthique uniquement (audit autorisé, formation, recherche).  

> Ce miroir est fourni à titre éducatif uniquement.  
> L’auteur décline toute responsabilité en cas d’usage illégal ou non autorisé.
