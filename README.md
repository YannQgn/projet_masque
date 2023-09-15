# Projet Masque
Le modèle de classification est basé sur VGG16 pré-entraîné, adapté pour classer les images en deux catégories : "Avec Masque" et "Sans Masque".
Il est sauvegardé sous le nom "best_model.h5".

# Notebook Colab :

- Le code est initialement basé sur un notebook Colab (Brief_Mask.ipynb) et comprend les étapes suivantes :
- Chargement des données d'entraînement (images de personnes portant ou non un masque facial).
- Entraînement du modèle de classification.
- Évaluation du modèle.
- Intégration de la webcam pour capturer des images en temps réel.
- Prédiction en temps réel de l'état du port du masque facial sur les images capturées.

# Captures d'écran :

Les captures d'écran des résultats de la prédiction en temps réel sont enregistrées sous forme d'images.

# Utilisation
- Ouvrez le notebook Colab "Brief_Mask.ipynb" dans votre environnement Colab.
- Exécutez les cellules du notebook dans l'ordre pour charger le modèle, effectuer des prédictions en temps réel à partir de la webcam et afficher les résultats.
