# Étude de Marché pour l'Exportation de Poulet
## Méthode de clustering / Analyse non-supervisée

Ce projet présente une étude de marché basée sur trois tables Excel. L'entreprise qui mène cette étude est basée en France et souhaite exporter du poulet vers un ou plusieurs pays.    
L'objectif principal de cette étude est d'utiliser des techniques statistiques non supervisées pour sélectionner un pays ou un groupe de pays comme marché cible pour l'exportation de poulet.  Les principales méthodes utilisées dans cette étude sont le clustering (CAH et k-means), le scatter plot, l'ACP (Analyse en Composantes Principales) avec une représentation graphique détaillée des clusters, et la heatmap.

### Contenu du Projet
Le projet est structuré en plusieurs partie, l'ordre est important pour comprendre l'analyse.

**Analyse Exploratoire des Données**     
Dans cette première étape, nous effectuerons une analyse exploratoire des données pour mieux comprendre le jeu de données. Cela comprendra des étapes telles que la visualisation des distributions, analyse univariée et bivariée.     

**Traitement des Données**       
Nous effectuerons des opérations de nettoyage et de prétraitement sur les données. Il s'agit de la gestion des valeurs manquantes, la création de nouvelles variables pertinentes, et la fusion des tables pour obtenir une seule table de données consolidée.     

**Clustering**    
Nous appliquerons la méthode de clustering : **CAH et k-means** pour regrouper les pays en fonction de certaines caractéristiques importantes.

**Scatter Plot**    
Nous créerons des scatter plots pour visualiser graphiquement les clusters et identifier les groupes de pays ayant des caractéristiques similaires.

**Analyse en Composantes Principales (ACP)**    
Nous effectuerons une ACP pour réduire la dimensionnalité des données et représenter graphiquement les clusters en utilisant des variables supplémentaires.

**Heatmap**     
Nous créerons une heatmap pour visualiser les corrélations entre les variables et identifier les facteurs importants dans la sélection du marché cible.

### Prérequis
Nous travaillerons dans l'environnement composé de :      
Python 3.x      
pandas      
numpy     
scikit-learn     
matplotlib     
seaborn     

### Structure des Fichiers    

├── notebook.ipynb    
├── data     
│   ├── table1.xlsx      
│   ├── table2.xlsx     
│   ├── table3.xlsx     
└── README.md      

Le dossier "data" contient les fichiers Excel des trois tables nécessaires pour l'étude de marché.      
Le fichier notebook.ipynb est un cahier Jupyter contenant tout le code et les analyses du projet.      
Le fichier README.md est le présent document, fournissant une description détaillée du projet.      

### Conclusion
Ce projet GitHub présente une étude de marché pour l'exportation de poulet en utilisant des techniques statistiques non supervisées.     
Les méthodes de clustering, l'ACP, le scatter plot et la heatmap permettent de visualiser et d'analyser les données pour sélectionner un pays ou un groupe de pays comme marché cible.    
En suivant ce projet, vous pourrez réaliser des analyses de marché approfondies basées sur des données réelles et prendre des décisions éclairées pour l'exportation de poulet en fonction des caractéristiques spécifiques de chaque pays.      
Le traitement des données et la création de nouvelles variables pertinentes sont également inclus dans le projet pour améliorer la qualité de l'analyse exploratoire et des résultats de clustering. 

Ce projet fait partie de la formation data-anlyst par Openclassrooms & ENSAE (certificat bac+4)
