# 👶 BébéLog — PWA

Application mobile progressive (PWA) pour la gestion quotidienne d'un nouveau-né, de la naissance jusqu'à l'école maternelle.

## 🚀 Déploiement sur GitHub Pages (5 minutes)

### Étape 1 — Créer le dépôt GitHub

1. Connectez-vous sur [github.com](https://github.com)
2. Cliquez sur **New repository** (bouton vert)
3. Nommez-le : `bebelog` (ou ce que vous voulez)
4. Laissez-le **Public** ✅
5. Cliquez **Create repository**

### Étape 2 — Uploader les fichiers

**Option A — Via l'interface web (le plus simple) :**

1. Dans votre nouveau dépôt, cliquez **uploading an existing file**
2. Glissez-déposez **tous** ces fichiers/dossiers :
   ```
   index.html
   manifest.json
   sw.js
   icons/  (tout le dossier)
   ```
3. Cliquez **Commit changes**

**Option B — Via Git (terminal) :**

```bash
git clone https://github.com/VOTRE_USERNAME/bebelog.git
cd bebelog
# Copiez tous les fichiers ici
git add .
git commit -m "🚀 Initial BébéLog PWA"
git push
```

### Étape 3 — Activer GitHub Pages

1. Dans votre dépôt, allez dans **Settings** (onglet en haut)
2. Dans le menu gauche, cliquez **Pages**
3. Sous **Source**, sélectionnez **Deploy from a branch**
4. Branch : **main** — Folder : **/ (root)**
5. Cliquez **Save**

### Étape 4 — Accéder à votre app

Après ~2 minutes, votre app sera accessible à :

```
https://VOTRE_USERNAME.github.io/bebelog/
```

Remplacez `VOTRE_USERNAME` par votre nom d'utilisateur GitHub et `bebelog` par le nom de votre dépôt.

---

## 📲 Installer l'app sur mobile

### Sur Android (Chrome)
1. Ouvrez l'URL dans Chrome
2. Un bandeau **"Ajouter à l'écran d'accueil"** apparaît automatiquement
3. Ou : menu ⋮ → **Ajouter à l'écran d'accueil**

### Sur iPhone/iPad (Safari)
1. Ouvrez l'URL dans **Safari** (obligatoire, pas Chrome)
2. Appuyez sur l'icône **Partager** (carré avec flèche)
3. Faites défiler et appuyez **Sur l'écran d'accueil**
4. Confirmez avec **Ajouter**

L'app s'installe comme une vraie application native, **fonctionne hors-ligne** et les données sont sauvegardées automatiquement sur l'appareil.

---

## 📁 Structure des fichiers

```
bebelog-pwa/
├── index.html       ← Application complète (React + tout le code)
├── manifest.json    ← Configuration PWA (icône, couleurs, nom…)
├── sw.js            ← Service Worker (cache offline)
├── icons/           ← Icônes de l'app (toutes tailles)
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── README.md        ← Ce fichier
```

---

## ✨ Fonctionnalités

- 🏠 **Accueil** — Stats du jour, actions rapides, profil du bébé avec calcul de l'âge
- 🍼 **Repas** — Biberon, allaitement (timer), mixte, solides
- 🌙 **Sommeil** — Chronomètre en temps réel, historique
- ❤️ **Santé** — Couches, poids, taille, température (alertes fièvre), médicaments, vaccins, notes
- 🌱 **Éveil** — Étapes du développement, activités, calendrier vaccinal officiel
- ✅ **Routine** — Checklists quotidienne / hebdomadaire / étapes clés
- 💾 **Données** — Sauvegarde/chargement JSON, stats complètes
- 💛 **Soutien** — Ko-fi + Bitcoin

## 🔒 Confidentialité

Toutes les données restent **sur votre appareil** (localStorage). Rien n'est envoyé sur un serveur.

---

Fait avec ❤️ pour les nouveaux parents
