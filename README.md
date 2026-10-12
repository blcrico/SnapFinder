# 🧭 SnapFinder

**SnapFinder** est une application mobile autonome au design OLED minimaliste, combinant une boussole de type *Precision Finding* (style iOS UWB), une messagerie chiffrée avec mode hors-ligne Bluetooth, une interface d'appels et une gestion locale des comptes et des amis. Conçue dans un fichier unique elle est idéale pour être compilée directement en application native.

---

## 🚀 Fonctionnalités Clés

* **🔐 Authentification Sécurisée** : Création de compte et connexion avec vérification stricte du mot de passe et persistance locale (`localStorage`).
* **🎯 Boussole Precision Finding (UWB)** : Flèche directionnelle ultra-fluide avec interpolation par le plus court chemin (zéro téléportation aux frontières 0°/360°), affichage de la distance en mètres et alertes de proximité visuelles/sonores.
* **💬 Messagerie & Mode Bluetooth P2P** : Chat instantané et simulation de relais hors-ligne (*Off-Grid*) via `BroadcastChannel` en zone blanche.
* **📞 Appels HD** : Interface d'appels vocaux et vidéo avec compteur de durée en direct et options de contrôle (micro/caméra).
* **👥 Gestion & Suppression des Amis** : Ajout rapide de contacts par scan de Code QR, saisie manuelle de pseudo (`@identifiant`) ou suppression en un clic.
* **📲 Ergonomie iOS & Geste Tactile** : Navigation fluide par onglets, interface noire absolue optimisée pour les écrans OLED, et fermeture des modales par balayage vers le bas (*swipe-to-close*).

---

## 🛠️ Stack Technique

* **HTML5 / CSS3 / JavaScript (Vanilla)** : Architecture ultra-légère en un seul fichier.
* **Tailwind CSS** : Design moderne et épuré.
* **FontAwesome** : Icônes vectorielles.
* **QRCode.js** : Génération et lecture de codes QR.

---

## 📱 Utilisation & Compilation

Les téléchargements sont associés à leur version :

* [Version 1.0 — Télécharger SnapFinder](https://drive.google.com/file/d/1UyP8iKZe7zy67nrjTZ_Dvcxrnrm797uN/view?usp=drive_link)


* Version 1.1 — Bientôt disponible


Ouvrez le fichier téléchargé directement.

---

## 📄 Licence

Ce projet est sous licence. Libre d'utilisation mais pas de modification et de copy.
