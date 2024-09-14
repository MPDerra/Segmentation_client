Notre projet repose sur un groupe automobile qui a l’intention de pénétrer de nouveaux marchés avec ses produits existants
(P1, P2, P3, P4 et P5). Après une analyse approfondie, ils ont conclu que le comportement des nouveaux marchés est similaire
à celui de leur marché existant.

Sur son marché existant, l’équipe de vente a classé tous les clients en 4 segments (A, B, C, D). Ensuite, ils ont effectué
une sensibilisation et une communication segmentées pour un autre segment de clients. Cette stratégie a fonctionné exceptionnellement bien pour eux. Ils prévoient d’utiliser la même stratégie pour les nouveaux marchés et ont identifié
2627 nouveaux clients potentiels.


Notre objectif est donc de développer un modèle capable prédire le segment auquel appartient chacun des 2627 nouveaux clients. En d'autres termes, nous cherchons à classifier la segmentation des clients en quatres catégories distinctes, en se basant sur des critères spécifiques. Cette prédiction peut être utile pour les sociétés de cartes de crédit afin de mieux comprendre leurs client,personnaliser leurs offres, cibler des campagnes de marketing spécifiques et prendre des décisions commerciales éclairées en fonction des besoins et des comportements des différents segments de leur clientèle.

- **Reference:**
    - [https://www.kaggle.com/datasets/kaushiksuresh147/customer-segmentation](https://www.kaggle.com/datasets/kaushiksuresh147/customer-segmentation)

Cet ensemble de données a été acquis lors du hackathon analytics 1. Nous sommes dans un cas de classification multiclasse. On veut prédire la segmentation de la clientèle d'un groupe d'automobile. L'objectif de ce projet est de concevoir un modèle d'apprentissage permettant de prédire avec le moins d'erreurs possibles et de classifier la segmentation des clients en quatres catégories distinctes, en se basant sur des critères spécifiques. Pour cela nous disposant d'une base de données composée de onzes variables explicatives : ID, Gender, Ever Married, Age, Graduated, Profession, Work Experience, Spending Score, Family Size, Var 1 et Segmentation. Ci-dessous, un descriptif de ces variables.

- `ID` : Identifiant unique.
- `Gender` : Sexe du client .
- `Ever Married` : Etat civil du client.
- `Age` : Age du client.
- `Graduated` : Le client est-il diplômé
- `Profession`: Profession du client.
- `Word Experience` : Expérience professionnelle en année.
- `Spending score` : Score de dépenses du client.
- `Family Size` : Nombre de membres de la famille du client (y compris le client).
- `Var 1` : Catégorie anonymisée du client
- `Segmentation (Target)` : Segmentation du client.
