# Redimensionnement d’images

Outil web autonome pour redimensionner, cadrer et compresser des images directement dans le navigateur.

## Fonctionnalités

- import de fichiers ou d’un dossier ;
- JPG / JPEG, PNG, WebP et AVIF ;
- dimensions en pixels ou millimètres avec DPI ;
- cadrage automatique Remplir / Ajuster ;
- positionnement, zoom et rotation manuels ;
- compression par qualité ou poids cible ;
- export vers un dossier quand le navigateur le permet ;
- aides contextuelles animées ;
- traitement optimisé pour les images lourdes.

## Performances

Le mode **Optimisé** est activé par défaut :

- aperçu et miniatures allégés ;
- moins de recalculs pendant le zoom, la rotation et le déplacement ;
- utilisation de `OffscreenCanvas` quand disponible ;
- recherche du poids cible accélérée ;
- jusqu’à deux images traitées en parallèle lorsque la mémoire et la taille de sortie le permettent ;
- retour automatique au traitement séquentiel pour les gros fichiers ;
- progression détaillée : décodage, redimensionnement, compression, enregistrement.

Le mode **Qualité max** privilégie un traitement séquentiel et une recherche de compression plus fine.

## Utilisation

Ouvrir `index.html` dans un navigateur récent. Chrome ou Edge sont recommandés pour la sélection directe du dossier de sortie.

## Confidentialité

Les images sont traitées localement dans le navigateur. Aucun serveur n’est nécessaire.

DMBP 2026