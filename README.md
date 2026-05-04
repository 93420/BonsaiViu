# 🌳 BonsaiViu

Une application Android moderne pour gérer votre collection de bonsaïs avec photos, entretiens et rappels intelligents.

**A modern Android app to manage your bonsai collection with photos, maintenance tracking, and smart reminders.**

## Téléchargement / Download
[bonsaiviu.v0.16.7.apk](https://github.com/93420/BonsaiViu/releases/download/BonsaiViu.v0.16.7/bonsaivio.v0.16.7.apk)
ou / or
[Release](https://github.com/93420/BonsaiViu/tags)

## 📥 Installation

### Prérequis / Prerequisites
- Android 15 (API 29) ou supérieur / or higher
- ~100 MB d'espace de stockage / storage space

### Installation de l'APK sur ton téléphone Android

Si tu as reçu l'application sous forme de fichier `.apk` (au lieu de la télécharger depuis le Play Store), voici comment l'installer.

### Étape 1 : Autoriser l'installation depuis des sources inconnues

Par défaut, Android bloque l'installation d'applications qui ne viennent pas du Play Store. Tu dois autoriser cette installation **temporairement**.

#### Sur Android 8 et versions ultérieures (recommandé)

1. **Télécharge** ou **copie** le fichier `.apk` sur ton téléphone (par email, câble USB, Google Drive, etc.).
2. **Ouvre** le fichier `.apk` depuis ton gestionnaire de fichiers ou depuis les téléchargements.
3. Une fenêtre s'affiche : **« Pour des raisons de sécurité, votre téléphone n'est pas autorisé à installer des applications inconnues provenant de cette source. »**
4. Tape sur **« Paramètres »** dans cette fenêtre.
5. Active le bouton **« Autoriser cette source »** (ou **« Autoriser les installations »**).
6. Reviens en arrière (bouton ← ou geste retour).

#### Sur Android 7 et versions antérieures

1. Ouvre **Paramètres → Sécurité** (ou **Paramètres → Confidentialité**).
2. Cherche l'option **« Sources inconnues »** et **active-la**.
3. Accepte l'avertissement de sécurité.

---

### Étape 2 : Installer l'APK

1. **Ouvre** à nouveau le fichier `.apk` (depuis tes téléchargements ou ton gestionnaire de fichiers).
2. Tape sur **« Installer »**.
3. Attends la fin de l'installation (quelques secondes).
4. Une fois terminé, tape sur **« Ouvrir »** pour lancer l'app, ou **« Terminer »** pour revenir au menu.

✅ L'application **BonsaiViu** est maintenant installée ! Tu la retrouves dans ton tiroir d'applications, comme n'importe quelle autre app.

---

### Étape 3 : Revenir à la configuration sécurisée (recommandé)

Par sécurité, il est **fortement recommandé** de **désactiver** l'installation depuis des sources inconnues une fois l'app installée. Cela évite d'installer accidentellement des applications malveillantes à l'avenir.

#### Sur Android 8 et versions ultérieures

1. Ouvre **Paramètres → Applications** (ou **Paramètres → Apps et notifications → Accès spécial**).
2. Cherche **« Installation d'applications inconnues »** (ou **« Installer des applications inconnues »**).
3. Sélectionne l'app que tu as utilisée pour installer l'APK (ex. : **Chrome**, **Fichiers**, **Drive**, **Gmail**…).
4. **Désactive** le bouton **« Autoriser cette source »**.

#### Sur Android 7 et versions antérieures

1. Ouvre **Paramètres → Sécurité**.
2. **Désactive** l'option **« Sources inconnues »**.

🔒 Ton téléphone est de nouveau protégé contre les installations non autorisées.

---

### Mises à jour de l'application

Si une nouvelle version de l'APK est disponible :
- **Télécharge** le nouveau fichier `.apk`.
- **Réautorise temporairement** l'installation depuis des sources inconnues (étapes ci-dessus).
- **Installe** le nouvel APK par-dessus l'ancien (tes données seront **conservées**).
- **Désactive à nouveau** les sources inconnues.

> ⚠️ Important : **avant** une mise à jour majeure, fais une sauvegarde (`.bonsaibak`) au cas où !

---

## 📸 Screenshots

| Accueil / Home | Bonsaï / Bonsai | Pot / Pot |
|---|---|---|
| <img src="screenshots/home.png" width="250" alt="Accueil / Home"> | <img src="screenshots/detail.png" width="250" alt="Bonsaï / Bonsai"> | <img src="screenshots/pot.png" width="250" alt="Pot / Pot"> |

| Entretiens / Maintenance | Galerie / Gallery | Rappels / Reminders |
|---|---|---|
| <img src="screenshots/care.png" width="250" alt="Entretiens / Maintenance"> | <img src="screenshots/gallery.png" width="250" alt="Galerie / Gallery"> | <img src="screenshots/reminders.png" width="250" alt="Rappels / Reminders"> |

## 🧭 Guide des écrans / Screen Guide

### 🏠 Écran d'accueil / Home Screen
L'écran principal affiche un résumé de votre collection :
- **Nombre total de bonsaïs** dans votre collection
- **Catalogues** organisés par catégories
- **Navigation rapide** vers toutes les fonctionnalités
- **Barre de navigation inférieure** pour un accès facile

**Home screen shows your collection summary with total count, catalogs, and quick navigation.**

### 📚 Écrans Catalogues / Catalog Screens
Organisez vos bonsaïs par catégories personnalisées :
- **Liste des catalogues** avec compteur de bonsaïs
- **Ajout/modification de catalogues** avec icônes personnalisables
- **Suppression** avec confirmation
- **Tri automatique** par nom

**Organize bonsais in custom catalogs with icons, counters, and easy management.**

### 🌲 Écran Détail / Detail Screen
Vue complète d'un bonsaï spécifique :
- **Informations principales** : nom, espèce, date d'acquisition, localisation
- **Galerie de photos** avec photo principale mise en avant
- **Historique d'entretien** complet avec filtres par type
- **Actions rapides** : modification, suppression, ajout de photos
- **Miniatures** pour un aperçu visuel rapide

**Complete bonsai view with info, photo gallery, maintenance history, and quick actions.**

### ✏️ Écran Édition / Edit Screen
Création et modification de fiches bonsaï :
- **Formulaire complet** : nom, espèce, date, localisation, notes
- **Association au catalogue** via menu déroulant
- **Validation** des champs obligatoires
- **Sauvegarde automatique** dans la base de données

**Create and edit bonsai records with complete form, catalog assignment, and validation.**

### 📷 Écran Photos / Photos Screen
Gestion des photos de vos bonsaïs :
- **Ajout de photos** depuis la galerie ou l'appareil photo
- **Définition de la photo principale** en un clic
- **Suppression** avec confirmation
- **Affichage en grille** optimisé
- **Stockage local** des images

**Manage bonsai photos: add from gallery/camera, set main photo, delete, grid view.**

### 🔧 Écran Entretiens / Maintenance Screen
Suivi détaillé de tous les entretiens :
- **Types d'entretien** : arrosage, rempotage, taille, fertilisation, traitement, autre
- **Historique complet** avec date et notes
- **Création de rappels** automatiques pour les entretiens récurrents
- **Filtrage** par bonsaï et par type
- **Miniatures** pour identifier rapidement chaque bonsaï

**Track all maintenance: watering, repotting, pruning, fertilizing, treatment. Create recurring reminders.**

### 🖼️ Écran Galerie / Gallery Screen
Consultation plein écran des photos :
- **Mode plein écran** avec zoom activé
- **Navigation** par balayage entre les photos
- **Informations** sur la photo affichée
- **Retour facile** vers l'écran précédent

**Full-screen photo viewer with zoom, swipe navigation, and photo info.**

### ⏰ Écran Rappels / Reminders Screen
Gestion intelligente des rappels d'entretien :
- **Création de rappels** ponctuels ou récurrents
- **Association à un bonsaï** spécifique
- **Notifications** automatiques via WorkManager
- **Activation/désactivation** rapide par toggle
- **Suppression** par appui long avec confirmation
- **Affichage optimisé** : rappels actifs en haut, inactifs en transparence (38%) avec badge "Inactif"
- **Synchronisation instantanée** : vérification immédiate après création/modification
- **Rappels récurrents** : conservent l'alignement de date (ex: tous les 7 jours à partir de la première occurrence)

**Smart reminder management: one-time or recurring, toggle active/inactive, long-press to delete, instant sync with WorkManager.**

## 💾 Sauvegardes et Données / Backup & Data

### Export / Sauvegarde
Depuis l'accueil :

- **Exporter** : génère un fichier `dbz-bonsai-backup_<date>.bonsaibak` via le Storage Access Framework.
  L'archive (format ZIP) contient :
  - `backup.json` — bonsaïs, pots, entretien, photos (ExportPayload v4)
  - `images/` — toutes les photos référencées (profil + galerie)
- **Importer** : ouvre une archive `.bonsaibak` (ou un ancien `.json` sans photos, pour rétrocompatibilité). Les images sont copiées dans le stockage privé de l'app cible et les URIs remappées automatiquement — la collection est fonctionnelle telle quelle sur un nouvel appareil.
- **Sauvegarde automatique** : case à cocher dans la boîte d'export. À chaque fermeture de l'app, une archive horodatée est écrite dans le dossier sélectionné (les 2 plus récentes sont conservées).

### ⚠️ Important
- Les sauvegardes manuelles nécessitent l'activation du **mode développeur** sur Android
- La désinstallation de l'application **supprime toutes les données**
- Il est recommandé de **sauvegarder régulièrement** votre collection
- Une fonctionnalité d'export/import intégré est prévue dans une future version

**Manual backups require developer mode. Uninstalling deletes all data. Built-in export/import coming in future version.**


## 👤 Auteur / Author

Développé avec ❤️ pour les amateurs de bonsaïs

**Developed with ❤️ for bonsai enthusiasts**

---

⭐ Si vous trouvez cette application utile, n'hésitez pas à laisser une étoile !

**If you find this app useful, feel free to star the repo!**
