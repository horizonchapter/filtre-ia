---
name: filtre-ia
description: Retirer l'aspect « fait par une IA » d'une interface, d'une application ou d'un site pour qu'il paraisse conçu par un studio professionnel. À utiliser sur toute interface avant validation.
---

# Filtre IA : enlever le style « généré »

Objectif : une interface propre et professionnelle que personne ne soupçonne d'avoir été faite par une IA. Ce skill peut travailler avec [impeccable](https://github.com/pbakaus/impeccable) et [taste-skill](https://github.com/Leonxlnx/taste-skill) s'ils sont installés (les charger aussi) ; il ajoute une chasse ciblée aux signes typiques.

## 1. Capturer
Captures de chaque écran (desktop et mobile) via le navigateur. Regarder chaque capture avant de juger.

## 2. Chasser les signes typiques d'une interface générée
- Cartes arrondies partout avec ombre douce et bordure grise identiques ; tout est dans une boîte.
- Dégradés violet/bleu, halos lumineux, verre dépoli décoratif sans raison.
- Emojis ou icônes génériques devant chaque titre ; pastilles colorées partout.
- Grilles de 3 ou 4 cartes de même taille avec titre + phrase + icône.
- Titres du type « Supercharge your workflow », textes vagues, majuscules partout, tirets longs dans chaque phrase.
- Espacements uniformes partout (aucune hiérarchie), tout centré, boutons tous en pilule.
- Police par défaut (Inter partout sans travail de graisse et de taille), nombres non alignés (pas de chiffres tabulaires).
- Données factices ou états vides non traités.

## 3. Corriger comme un studio
- Hiérarchie : une seule chose importante par écran, le reste plus petit et plus calme.
- Moins de boîtes : séparer par l'espace et des filets fins plutôt que par des cartes.
- Typographie : 2 graisses, 3 ou 4 tailles maximum, chiffres tabulaires dans les tableaux et statistiques.
- Couleur : une teinte d'accent, utilisée rarement ; gris légèrement teintés plutôt que gris neutres.
- Densité d'outil pro (type Linear, Vercel, Arc) : alignements stricts sur une grille, tailles de clic correctes, états survol/actif/désactivé/chargement/vide/erreur tous dessinés.
- Textes courts, concrets, dans la langue naturelle du produit ; libellés d'action précis (« Programmer », pas « Envoyer »).
- Détails qui font pro : micro-transitions de 150 à 200 ms, focus visible, raccourcis clavier affichés, tooltips sobres.

## 4. Vérifier
Nouvelles captures avant/après. Passer la liste du point 2 : zéro signe restant. Un sous-agent indépendant relit et répond à : « Est-ce que ça ressemble à un produit fait par une équipe de design ? » S'il hésite, on reprend.

## Sortie
Liste des changements faits, captures avant/après, et 3 propositions d'amélioration en plus pour validation.
