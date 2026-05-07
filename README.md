# 🌳 BonsaiViu

Une application Android moderne pour gérer votre collection de bonsaïs avec photos, entretiens et rappels intelligents.

Disponible en Anglais, Français, Catalan, Espagnol et Italien.

Available in English, French, Cataln, Spanish and Italian.

**A modern Android app to manage your bonsai collection with photos, maintenance tracking, and smart reminders.**

## Téléchargement / Download
[BonsaiViu.v0.28.0.apk](https://github.com/93420/BonsaiViu/releases/download/BonsaiViu.v0.28.0/bonsaiviu.v0.28.0.apk)
ou / or
[Release](https://github.com/93420/BonsaiViu/tags)

## 📥 Installation

### Prérequis / Prerequisites
- Android 15 (API 29) ou supérieur / or higher
- ~100 MB d'espace de stockage / storage space

### Installation depuis APK / Install from APK
1. Téléchargez le fichier APK depuis les [Releases](https://github.com/christopherre/mybonsai/releases)
2. Activez l'installation depuis des sources inconnues sur votre appareil
3. Ouvrez le fichier APK et suivez les instructions d'installation

**Download the APK from Releases, enable unknown sources, and install.**

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
