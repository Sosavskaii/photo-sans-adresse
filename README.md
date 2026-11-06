# Ta photo peut donner ton adresse : comment l'éviter

Chaque photo prise avec un téléphone contient des infos cachées (les « métadonnées EXIF ») : le modèle du téléphone, la date, l'heure… et souvent **l'endroit exact** où elle a été prise, si l'appareil photo a accès à ta position.

- **Instagram** et **WhatsApp en mode photo** retirent la position avant de publier ou d'envoyer.
- Mais une photo envoyée **en fichier** (pièce jointe d'un mail, WhatsApp « Document », Drive, WeTransfer…) **garde tout**. N'importe qui peut lire la position en deux clics.

## 1. Couper la position dans l'appareil photo (10 secondes)

- **iPhone** : Réglages → Confidentialité et sécurité → Service de localisation → Appareil photo → **Jamais**.
- **Android** : ouvre l'appli Appareil photo → Paramètres (roue dentée) → désactive **Tags de localisation** / **Enregistrer la position** (le nom change selon la marque).

À l'envoi, sur iPhone, tu peux aussi toucher **Options** en haut de la feuille de partage et décocher **Position**.

## 2. Nettoyer les photos déjà prises : ExifCleaner (gratuit)

Appli gratuite et open source pour Windows, Mac et Linux : [github.com/szTheory/exifcleaner](https://github.com/szTheory/exifcleaner) (licence MIT, par szTheory).

1. Télécharge la dernière version dans **Releases** (à droite sur la page GitHub).
2. Ouvre l'appli et **glisse tes photos dedans**.
3. C'est fini : toutes les métadonnées sont effacées, la photo elle-même ne change pas.

## Vérifier qu'une photo est propre

Sur ordi : clic droit → Propriétés → Détails (Windows) ou Lire les informations (Mac). S'il n'y a plus de coordonnées GPS, c'est bon.

---
Guide écrit par [@sosav.ai](https://instagram.com/sosav.ai). ExifCleaner appartient à ses auteurs.
