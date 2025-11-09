# U-Net-pour-la-Segmentation-d-Images-M-dicales

Description

Ce projet implémente et analyse un modèle U-Net pour la segmentation d’images échographiques du sein.
L’objectif est d’identifier automatiquement les régions suspectes (tumeurs bénignes ou malignes) à partir d’images médicales en niveaux de gris.

Le travail comprend :

Le prétraitement du jeu de données (redimensionnement, normalisation).

La construction et l’entraînement du modèle U-Net.

L’évaluation des performances via les métriques : Accuracy, Loss, IoU (Jaccard).

La visualisation des Feature Maps internes et du résultat final de segmentation.

Résultats principaux
Métrique	Valeur
Accuracy finale	0.9833
Validation accuracy	0.9622
Loss finale	0.0362
IoU (Jaccard)	0.7074
Modèle utilisé

Architecture : U-Net classique

Optimiseur : Adam

Fonction de perte : Binary Crossentropy

Nombre d’époques : 40
Jeu de données

Breast Ultrasound Images Dataset — disponible sur Kaggle :
🔗 https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset

Le dataset contient 780 images échographiques classées en :

Normal

Benign

Malignant
