# Reconstitution3D
Reconstruction d'une image 3D à partir de coupes 2D via l'algorithme du Marching Cubes et des techniques de traitement d'images. Les coupes sont issues de scans CT (computed tomography) - technique mesurant l'absorption des rayons X par les tissus. Le dataset utilisé comme exemple est le suivant (à télécharger et placer dans le dossier CT_files) : 
- https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-chest

Les parties les plus claires seront extraites des images : en d'autres termes, ce programme reconstitue en 3D la structure osseuse du sujet (ainsi que le système cardiovasculaire dans certains cas, dépendant de comment ont été obtenu les coupes).
