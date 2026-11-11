---
name: "anatomy"
description: "Transforme n'importe quel objet, machine ou système (moteur de fusée, cœur, appli…) en schéma interactif avec curseurs, vue démontée et légendes. Se déclenche sur « anatomy » ou « montre-moi comment ça marche »."
---

# Anatomy

Transforme un sujet en une **machine interactive** que l'on peut explorer, au lieu d'une explication en texte.

## Quand l'utiliser
- L'utilisateur écrit « anatomy » suivi d'un sujet.
- Il demande comment fonctionne un objet, une machine, un organe ou un système, et un schéma interactif aiderait à comprendre.

## Étapes
1. **Identifier le sujet** (ex. « moteur de fusée »). S'il est trop vague, poser une seule question courte.
2. **Lister les parties clés** (5 à 10 composants) et le rôle de chacune, en une phrase simple.
3. **Choisir 1 ou 2 paramètres qui font bouger le système** (ex. poussée, débit, vitesse, température).
4. **Construire une page HTML autonome** (un seul fichier, SVG ou canvas) et la publier comme artifact.

## Contenu obligatoire de la page
- Un schéma propre et lisible du sujet, en SVG.
- **Au moins un curseur** qui change visiblement le schéma (ex. « Poussée »).
- **Un curseur « Démonter »** : une vue éclatée où les pièces s'écartent les unes des autres.
- **Un interrupteur « Légendes »** qui affiche ou masque les noms des pièces.
- Au clic ou au survol d'une pièce : une courte explication de son rôle.
- Un titre simple et une étiquette « Interactif ».

## Style
- Fond clair crème, texte sombre, un seul accent de couleur (terracotta).
- Typographie sobre (serif pour le titre, sans-serif ou mono pour les étiquettes).
- Mobile d'abord : tout doit tenir et se manipuler au doigt sur un écran de téléphone.
- Textes en français, phrases courtes, sans jargon.

## Règles
- Rester fidèle à la réalité : ne pas inventer de pièces ni de chiffres. Si une information est incertaine, le dire.
- Pas de logo, marque ou personnage protégé dans le dessin.
- Après publication, donner une phrase de résumé et proposer d'ajouter un paramètre ou une pièce.