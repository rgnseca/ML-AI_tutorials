# Deep Learning Lab Assignments

Exercices effectués dans le cadre de mon apprentissage du deep learning.

Quatre notebooks Keras/TensorFlow :

1. [`exercise_1_assignment.ipynb`](./exercise_1_assignment.ipynb) : XOR et non-linéarité.
2. [`exercise_2_assignment.ipynb`](./exercise_2_assignment.ipynb) : perceptron et classification.
3. [`exercise_3_assignment.ipynb`](./exercise_3_assignment.ipynb) : CNN et classification.
4. [`exercise_4_skin-cancer_assignment.ipynb`](./exercise_4_skin-cancer_assignment.ipynb) : classification de lésions cutanées avec HAM10000.

## Installation

```bash
python -m pip install numpy pandas matplotlib seaborn pillow scikit-learn tensorflow
```

Le notebook 4 nécessite :

```text
Skin_Cancer_class/
├── HAM10000_metadata.csv
└── HAM10000_images_150x100.tar
```

Les images doivent être extraites selon le chemin indiqué dans le notebook.

## Exécution

1. Ouvrir un notebook dans VS Code.
2. Sélectionner un kernel Python avec les dépendances.
3. Exécuter les cellules dans l'ordre.

## Notions principales

- Perceptron : images aplaties, sans structure spatiale.
- CNN : convolution, pooling et détection de motifs locaux.
- Classification multi-classes : `softmax` + `categorical_crossentropy`.
- Évaluation : accuracy, loss, matrice de confusion, précision et recall.
- Toujours conserver le test set pour l'évaluation finale.

Le fichier [`exercise_functions.py`](./exercise_functions.py) contient les fonctions utilitaires.
