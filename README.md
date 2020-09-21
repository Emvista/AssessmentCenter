# AssessmentCenter

Tâche

La reconnaissance des entités nommées consiste à repérer des éléments textuels et à les classer dans des catégories prédéfinies (noms de personnes, d'organisations, de marques, d'équipes sportives, etc.). Par exemple, dans "Luc mange une pomme", "Luc" doit être classé dans la catégorie "Personne". La reconnaissance d'entités nommées est souvent considérée comme l'une des briques de fondation des systèmes visant à structurer un texte tout-venant. 

La tâche consiste à développer un modèle de machine learning/deep learning capable de classer chaque token ("unité" de la phrase). En entrée, on utilisera le jeu de données déjà tokenisé décrit ci-dessous avec un découpage de 80% pour l'entraînement et 20% pour le test. 

Description du jeu de données :

Corpus développé par Emvista pour la reconnaissance d’entités nommées. Ce corpus a été construit à partir de résumés d’articles Wikipedia. Il est composé de 587 résumés et de 3 125 entités nommées annotées avec l’encodage BIO et les concepts de l’ontologie NERD. Voir la publication associée pour plus de détails : https://www.researchgate.net/publication/330702389_Reconnaissance_d'entites_nommees_iterative_sur_une_structure_en_dependances_syntaxiques_avec_l'ontologie_NERD 
Ce corpus est sous licence Creative Commons CC-BY-NC-SA et LGPL-LR.
