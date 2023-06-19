# Green IA

# Tensorflow
TensorFlow est particulièrement adapté au traitement des images dans le domaine de l'apprentissage automatique. Il propose des fonctionnalités spécifiques pour la manipulation et le traitement des données d'images

## Précision
Afin d'augmenter la précision j'ai retiré un <strong>layer</strong> redondant, j'ai modifié la <strong>fonction d'activation</strong> avec une variante de la fonction ReLU et réduit la taille du <strong>batch</strong> (échantillion)


#### Batch
nombre d'échantillons d'entraînement

#### Kernel
filtre de convolution, est une petite matrice de nombres qui est appliquée de manière séquentielle à chaque partie de l'image d'entrée. Il se déplace sur l'image en effectuant des opérations de filtrage

![alt text](https://i.ibb.co/xHJhm2p/Capture-d-e-cran-2023-06-19-a-13-41-08.jpg)

#### Epoch
Une époque consiste à passer par tous les lots d'entraînement une fois. Par exemple, si vous avez un ensemble d'entraînement de 1000 exemples et que vous utilisez des lots de 100 exemples, alors une époque correspondra à 10 itérations sur les lots (1000 exemples / 100 exemples par lot = 10 itérations)

#### Layer
Une couche peut être considérée comme une unité de traitement qui prend des entrées, effectue des opérations sur ces entrées et produit des sorties.

#### Fonction d'activation

Permet au réseau de modéliser des relations complexes entre les entrées et les sorties.
Par exemple, certaines fonctions d'activation renvoient des valeurs dans l'intervalle [0, 1], tandis que d'autres renvoient des valeurs dans l'intervalle [-1, 1]. La plage de sortie peut être adaptée à la tâche spécifique du modèle.
