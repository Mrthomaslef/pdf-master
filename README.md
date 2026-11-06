<img src="assets/icon.svg" width="64" height="64" alt="PDF Master">

# PDF Master — Lecteur & Éditeur PDF Ultra-Fluide

Application web & mobile (PWA) de lecture et d'édition de fichiers PDF **sans fioritures**, **60 fps** et **100 % locale** (aucun serveur, aucun envoi de données, confidentialité absolue).

Basée sur le duo open-source de référence **Mozilla PDF.js** (rendu vectoriel haute densité) et **pdf-lib** (modification binaire et réécriture native du PDF), inspirée de *ShizukuIchi/pdf-editor*.

## Fonctionnalités

- **Lecture ultra-fluide (Mobile & Ordi)** :
  - Rendu *lazy* via `IntersectionObserver` à 60 fps et support écrans Retina / Mobile.
  - Filtres de confort visuel en 1 clic : **Normal**, **Mode Nuit (Inversé)**, **Sépia**, **Contraste Élevé**.
  - Recherche plein texte instantanée (`Cmd/Ctrl + F`) avec saut direct vers les pages.
  - Historique des derniers fichiers PDF ouverts sauvegardé localement dans `IndexedDB`.
- **Édition directe sur le PDF** :
  - **Texte & Remplissage de formulaires** : ajout, déplacement, choix de la taille et de la couleur.
  - **Signature manuscrite** : pavé de signature tactile (doigt, Apple Pencil, souris) avec encre bleue, noire ou rouge.
  - **Surligneur fluo & Stylo à main levée** : tracé vectoriel fluide directement sur la page.
  - **Blanc correcteur (Masquer)** : couvre proprement un texte ou élément existant avant de réécrire par-dessus.
  - **Tampons rapides & Date du jour** : `SIGNÉ`, `VALIDÉ`, `URGENT`, `CONFIDENTIEL`, `DATE DU JOUR`.
  - **Insertion d'image / photo** : redimensionnable à la volée.
- **Gestion des pages (Volet latéral)** :
  - Réorganisation des pages (monter / descendre).
  - Rotation à `90°` d'une page ou suppression de page.
  - **Fusion de PDF** (ajouter un autre PDF à la suite) et ajout de page vierge A4.
- **Export PDF natif (`Cmd/Ctrl + S`)** : génère et télécharge instantanément le fichier `.pdf` aplati avec toutes vos annotations.
