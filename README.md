# car_classification-
Un mini projet permet de faire la classification des voiture par marque

## Description:   
  **Prétraitement**: Lire image en grayscale  
  **Extraction des caractéristique**: combinaison de deux types: les caractéristiques de Hu moments + spacial features <br />
     * Hu moments calculé par `cv2.HuMoments()`<br />
     * Les caractéristiques spaciales sont: les valeurs de pixels de l'image de 16x16. <br />
  **Apprentissage**: classifieur SVM avec les paramètres `C=10, gamma=0.01, kernel= 'rbf'`  
  **Base de données**: 3 classes seullement  (lamburgini, jeep, BMW) à partie de Stanford dataset https://ai.stanford.edu/~jkrause/cars/car_dataset.html
  ## Description:  
  Accuracy= 70.0 % 
  
  
