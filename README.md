# ProjetL3
Ce projet explore deux axes majeurs de l’intelligence artificielle appliquée aux images :

    La classification supervisée d’animaux (tigres, renards, éléphants),

    La reconstruction et génération d’images via des auto-encodeurs.

## Contenu du dépôt

- `ProjetML2_2024_2025.ipynb` : Notebook principal du projet.
- `saved_models/` : Modèles de classification d’images préentraînés (CNN simples, étendus, et transfer learning).
- `AEweights/` : Modèles d’auto-encodeurs (pour reconstruction, débruitage et colorisation).

(les images sont disponibles via le notebook, où ils seront téléchargé via un lien directement sur votre google drive)

## Utilisation

Vous pouvez ouvrir et exécuter les notebooks sur Google Colab où vous aurez accès a des GPU.
Les modèles sont pré-enregistrés, il n’est pas nécessaire de relancer l’entraînement (économie de CO₂ + gain de temps).
Vous pouvez également monter votre Google Drive pour accéder aux données. (Code déjà présent dans le notebook)

L’entraînement de modèles de deep learning consomme beaucoup de ressources GPU et génère une empreinte carbone non négligeable.
C’est pourquoi tous nos modèles entraînés sont déjà disponibles dans ce dépôt.
Vous pouvez tester les prédictions sans relancer les entraînements complets.

# Attention : 
    Les prédictions seules ne reflètent pas toujours la qualité du modèle.
    Les courbes d'apprentissage restent plus représentatives, notamment à cause du sur-apprentissage très présent sur certains modèles.