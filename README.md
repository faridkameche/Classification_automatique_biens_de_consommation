# Classification automatique de biens de consommation

Ce projet porte sur la classification des biens de consommations en partant soit d'une description soit d'une image du bien et où une catégorie est attribuée à un bien. 

Dans le cadre de la reconnaissance de textes, j'ai utilisé :
- CountVectorizer,
- TF-IDF,
- Word2Vec,
- BERT et
- USE.

Dans le cadre de la reconnaissance d'images, j'ai utilisé :
- SIFT,
- ORB et
- le modèle VGG16 (CNN) en transfer learning.

Pour toutes ces méthodes, une matrice de confusion a été déterminée en comparant les catégories originales avec les labels obtenus après un t-SNE et une segmentation par k-means. 

Enfin, deux méthodes mixtes ont été utilisées :
- une méthode mixte entre VGG16 et TF-IDF,
- une méthode mixte entre VGG16 et USE.


