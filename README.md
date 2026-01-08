🏥 Analyse Épidémiologique de la Fièvre Typhoïde
Projet Académique - Analyse de Données avec Python

📋 Contexte du Projet
Dans le cadre de ce projet, j'occupe le rôle d'analyste de données au sein d'une agence nationale de surveillance épidémiologique. La mission consiste à traiter, nettoyer et analyser un jeu de données de 300 patients suspectés d'infection à la typhoïde dans quatre zones clés : Nord, Sud, Est et Ouest.

L'objectif est de transformer des données brutes en informations exploitables pour orienter les décisions de santé publique.

🛠️ Stack Technique & Outils
Langage : Python 3

Bibliothèques :

pandas & numpy : Nettoyage et manipulation des structures de données.

seaborn & matplotlib : Création de visualisations statistiques avancées.

Environnement : Jupyter Notebook (taff.ipynb).

⚙️ Méthodologie de Travail
L'analyse a été conduite suivant un pipeline rigoureux :

Exploration & Nettoyage (Data Cleaning) :

Normalisation des variables : Correction de la casse et des espaces pour les colonnes Sexe (M/F) et Test_typhoide (Positif/Négatif).

Gestion des types : Conversion des températures et des durées de fièvre pour assurer des calculs précis.

Vérification de l'intégrité : Aucun manquant détecté (0 NaN), garantissant une analyse sur l'échantillon complet.

Traitement des Incohérences :

Analyse des valeurs aberrantes pour la température (vérification des seuils physiologiques).

Analyse Descriptive & Bivariée :

Comparaison des moyennes de température entre patients sains et infectés.

Calcul des taux de positivité par région et par source d'eau.

📊 Résultats & Conclusions de l'Étude
1. Indicateurs Cliniques
Taux de Positivité Global : 61,67 %.

La Fièvre comme marqueur : Une différence significative de température est observée. Les patients positifs présentent une moyenne de 38,9°C, soit environ 1°C de plus que les patients négatifs (37,9°C).

2. Analyse Géographique (Le paradoxe de l'Est)
Risque Individuel : La région Est est la plus critique avec un taux de positivité de 66,2 %.

Volume de Cas : Bien que l'Est soit la plus risquée, l'Ouest concentre la plus grosse part des malades au niveau national (33,5 % de la répartition totale), ce qui suggère un besoin de ressources matérielles plus important dans cette zone.

3. Facteurs Environnementaux
Assainissement : Contrairement aux hypothèses initiales, l'accès à l'assainissement n'est pas lié de manière forte ou directe à la positivité sur l'ensemble du territoire.

Spécificité Locale : Cependant, le manque d'assainissement dans la région Est semble être un facteur aggravant spécifique, expliquant pourquoi cette région présente le taux de positivité le plus élevé du pays.

📁 Structure du Dépôt
taff.ipynb : Le notebook contenant l'intégralité du code Python, des visualisations et des commentaires analytiques.

typhoide_health_data.csv : Le dataset source contenant les informations des 300 patients.

💡 Recommandation de Santé Publique
Basé sur cette analyse, les interventions devraient être prioritaires dans la région Est pour améliorer les infrastructures d'assainissement, tandis que les capacités de traitement clinique devraient être renforcées dans l'Ouest pour faire face au volume de patients.
