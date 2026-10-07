# Classification d'images avec MLP, CNN et transfert d'apprentissage

Ce projet compare plusieurs approches de classification d'images sur le jeu de
donnees CIFAR-10 :

- un perceptron multicouche (MLP) ;
- des reseaux de neurones convolutionnels (CNN) ;
- un modele VGG16 pre-entraine utilise pour le transfert d'apprentissage.

## Utilisation

Ouvrir le notebook
[`Classification_d_image_MLP_CNN_TransfertLearning.ipynb`](./Classification_d_image_MLP_CNN_TransfertLearning.ipynb)
dans Jupyter ou Google Colab, puis executer les cellules dans l'ordre. CIFAR-10
et les poids VGG16 sont telecharges automatiquement par Keras lors de leur
premiere utilisation.

Dependances principales : Python, NumPy, Matplotlib et TensorFlow.
