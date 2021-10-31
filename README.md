# p6 : Classification de produits à base de texte et d'images 
## Contexte et problématiques :

Projet de marketplace e-commerce que veut lancer l’entreprise « place de marché »
La mise en ligne des produits par les vendeurs passe par une phase de catégorisation manuelle et couteuse 
Une évolution importante du nombre de produits du site est prévue (passage à l’échelle)

## Objectif : 
étude de faisabilité d’un moteur de classification ayant pour but d’améliorer l’expérience utilisateur et faire face aux challenges d’un passage à l’échelle en :

  Classifiant les produits en se basant sur des méthodes NLP et méthodes de traitement d’images
  Fusionnant les modèles et dégageant la synthèse sur la faisabilité du moteur

## Etapes du travail :
### Partie NLP :
Transformer les descriptions (vectorisation, word embedding)
Classifier les produits avec un modèle de classification non supervisée 
### Partie Image : 
Représenter les images des produits avec des descripteurs : apprroche Bag of Visual Words BOVW, ou avec un CNN en transfer learning 
Classifier les produits avec une méthode de classification  non supervisée
Combiner les meilleurs modèle NLP et Image
Tester le process de classification avec un modèle supervisée (classifieur Gradient Boosting ou autre)
Evaluer la faisabilité de moteur de classification 
Prévoir la mise à jour du dataset et la durée de vie du modèle
