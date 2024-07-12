# Detection-Ransomwares-avec-RNN

Les ransomwares sont devenus l'une des menaces les plus importantes en cybersécurité ces dernières années. Ces logiciels malveillants chiffrent les données d'un système informatique et demandent une rançon pour les déchiffrer, causant ainsi des dommages considérables aux entreprises et aux particuliers victimes.\\

Face à cette menace grandissante, il est crucial de développer des solutions de détection efficaces pour protéger les systèmes informatiques. C'est dans ce contexte que ce projet  s'intéresse à l'utilisation des réseaux de neurones récurrents (RNN) pour la détection des ransomwares.\\

Les RNN sont des modèles de réseaux de neurones qui sont particulièrement adaptés à l'analyse de séquences de données, comme les traces d'exécution d'un programme. Cela en fait un choix pertinent pour la détection de malwares.

# Réseaux de neurones récurrents (SimpleRNN)


Le Réseau de Neurones Récurrents (RNN) est un type de réseau de neurones où la sortie de l'étape précédente est utilisée comme entrée pour l'étape actuelle. Dans les réseaux de neurones traditionnels, toutes les entrées et sorties sont indépendantes les unes des autres. Cependant, dans les cas où il est nécessaire de prédire le mot suivant d'une phrase, les mots précédents sont nécessaires et il est donc nécessaire de se souvenir des mots précédents. Ainsi, le RNN est apparu pour résoudre ce problème avec l'aide d'une couche cachée. La caractéristique principale et la plus importante du RNN est son état caché, qui se souvient de certaines informations sur une séquence. L'état est également appelé état de mémoire car il se souvient de l'entrée précédente du réseau. Il utilise les mêmes paramètres pour chaque entrée car il effectue la même tâche sur toutes les entrées ou couches cachées pour produire la sortie. Cela réduit la complexité des paramètres, contrairement à d'autres réseaux de neurones.


