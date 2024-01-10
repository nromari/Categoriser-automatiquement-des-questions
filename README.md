Stack Overflow est un site célèbre de questions-réponses liées au développement informatique.

Pour poser une question sur ce site, il faut entrer plusieurs tags afin de retrouver facilement la question par la suite. Pour les utilisateurs expérimentés, cela ne pose pas de problème, 
mais pour les nouveaux utilisateurs, il serait judicieux de suggérer quelques tags relatifs à la question posée.
L'objectif de ce projet est de développer un système de suggestion de tags pour le site.
Celui-ci prendra la forme d’un algorithme de machine learning qui assignera automatiquement plusieurs tags pertinents à une question.

Méthode :
- Appliquer des méthodes d’extraction de features spécifiques des données textuelles.
- Mettre en œuvre une approche non supervisée afin de proposer des mots clés.
- Mettre en œuvre une approche purement supervisée et comparer les résultats avec l’approche non supervisée. Plusieurs méthodes d’extraction de features seront testées et comparées ; au minimum :
une approche de type bag-of-words ; 3 approches de Word/Sentence Embedding : Word2Vec (ou Doc2Vec, Glove…), BERT et USE. 
-Mettre en place une méthode d’évaluation propre, avec une séparation du jeu de données pour l’évaluation.
