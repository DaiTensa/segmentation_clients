# Projet 5 : Segmentation Clients site E-Commerce
***
![olist](https://github.com/DaiTensa/segmentation_clients/blob/main/figures/Capture%20d%E2%80%99%C3%A9cran%202023-03-07%20091224.png?raw=true)
***
## présentation du projet

L'entreprise Olist souhaite que je fournisse à ses équipes d'e-commerce une segmentation des clients qu'elles pourront utiliser au quotidien pour leurs campagnes de communication.

Mon objectif et de comprendre les différents types d'utilisateurs en analysant leur comportement d'achat.

À la fin de notre étude, nous fournirons à l'équipe marketing une description actionnable de la segmentation, nous analyserons par la suite la stabilité des segments au cours du temps afin de prévenir des actions de maintenance.

**Qu'est-ce que la segmentation client ?** 

Comprendre le paysage du marché dans les entreprises et élaborer des stratégies commerciales ou marketing ciblées adaptées à chaque groupe. La segmentation est l'action de découpage de la population (les clients) en sous-ensembles homogènes, selon différents critères de segmentation.

# Mission
Les notebooks comprennent diverses étapes, allant de l'intégration des données, en passant par différentes étapes de cleaning et d'analyses exploratoires et features engineering et enfin la segmentation à l'aide des modèles d'apprentissage non suppervisés. 

![mission](https://github.com/DaiTensa/segmentation_clients/blob/main/figures/Copie%20de%20Frise%20chronologique.png?raw=true)

**1.** Features Engineering : Définition de critères de segmentation, Récence, Fréquence, le montant monétaire, le prix moyen, les versements échelonnés moyens, le nombre moyen de jours de livraison, etc.
**2.** Clustering : Méthode RFM; RFM + Reviews; RFM + Reviews + Behavior; RFM + Reviews + Behavior + Catégories; All columns.
**3.** Pour chaque méthodes: Nous utiliserons les algorithmes KMeans, DBSCAN et C.A.H.  
**4.** Visualisation des clusters : Boxplot, Barplot, Distributions, Réduction de dimension. 

![rfm](https://github.com/DaiTensa/segmentation_clients/blob/main/figures/Copie%20de%20Frise%20chronologique%20(2).png?raw=true)


# Compétences

- Adapter les hyperparamètres d'un algorithme non supervisé afin de l'améliorer.
- Évaluer les performances d’un modèle d'apprentissage non supervisé.
- Transformer les variables pertinentes d'un modèle d'apprentissage non supervisé.
- Mettre en place le modèle d'apprentissage non supervisé adapté au problème métier.

# Source de données
Brazilian E-Commerce Public Dataset by Olist [La base de données](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)