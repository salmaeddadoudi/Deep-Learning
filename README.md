
# DEEP LEARNING
Le deep learning (apprentissage profond) est une branche du machine learning 
(apprentissage automatique) qui se concentre sur l'utilisation de réseaux neuronaux 
artificiels, appelés réseaux de neurones profonds, pour modéliser et résoudre des 
problèmes complexes. Les réseaux de neurones profonds sont caractérisés par leur 
architecture composée de plusieurs couches de neurones, d'où le terme "profond".
Voici quelques concepts clés liés au deep learning :
• Réseaux Neuronaux Profonds : Ces réseaux sont composés de plusieurs couches 
de neurones, comprenant généralement une couche d'entrée, une ou plusieurs 
couches cachées et une couche de sortie. Chaque couche de neurones effectue des 
transformations sur les données et apprend des caractéristiques de plus en plus 
abstraites à mesure que l'on progresse dans le réseau.
• Apprentissage Automatique Hiérarchique : Les réseaux de neurones profonds 
apprennent de manière hiérarchique, en découvrant des représentations complexes 
et abstraites à partir des données d'entrée. Chaque couche du réseau apprend à 
représenter des caractéristiques de plus en plus abstraites et complexes.
• Réseaux de Neurones Convolutifs (CNN) : Ces réseaux sont spécialement conçus 
pour traiter des données structurées en grilles, telles que des images. Ils utilisent 
des opérations de convolution pour extraire des caractéristiques spatiales des 
données.
• Réseaux Neuronaux Récurrents (RNN) : Ces réseaux sont adaptés pour travailler 
avec des séquences de données, comme du texte ou des séquences temporelles. Ils 
utilisent des connexions récurrentes pour mémoriser des informations du passé.
• Fonctions d'Activation : Les fonctions d'activation, telles que ReLU (Rectified 
Linear Unit), sont utilisées pour introduire de la non-linéarité dans les réseaux de 
neurones, ce qui permet au modèle d'apprendre des relations complexes.
• Applications : Le deep learning a été très réussi dans divers domaines, y compris la 
vision par ordinateur, le traitement du langage naturel, la reconnaissance vocale, la 
traduction automatique, les jeux, la santé, etc.
# Projet DEEP LEARNING
• Un réseau siamois utilise deux branches identiques qui partagent les mêmes poids. 
Chaque branche prend en entrée une question. Les deux branches traitent les 
questions de manière similaire et extraient des caractéristiques à partir de chaque 
question.
• Embeddings Partagés : Les représentations vectorielles des mots (embeddings) 
sont souvent utilisées pour convertir les mots en des vecteurs numériques. Ces 
embeddings sont partagés entre les deux branches du réseau.
• Calcul de Similarité : Une fois que les deux branches ont transformé les questions 
en représentations vectorielles, la similarité entre ces représentations est calculée. 
Cela peut être fait en mesurant la distance euclidienne, la cosine similarity, ou en 
utilisant une fonction de similarité appropriée.
• Fonction de Perte : La fonction de perte mesure la différence entre la similarité 
prédite par le modèle et la véritable similarité entre les paires de questions dans 
l'ensemble d'entraînement. L'objectif est de minimiser cette différence.
• Entraînement : Le réseau est entraîné sur un ensemble de paires de questions avec 
leurs étiquettes de similarité correspondantes. Le modèle ajuste ses poids pour 
apprendre à extraire des caractéristiques pertinentes et à prédire correctement la 
similarité entre les paires de questions.
• Utilisation pour l'Inference : Une fois entraîné, le modèle peut être utilisé pour 
mesurer la similarité entre deux nouvelles questions qui n'ont pas été vues lors de 
l'entraînement
