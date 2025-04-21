JUPITER NOTEBOOK FOR ACTION/CHARACTER AND MALE/FEMALE DIALOGUE CLASSIFICATION

A PDF report details the Aim, matériels, méthodes and result of this project.

Change these variables to modify the datasets used : 

  usedPaths = [hZDPath] #Paths to the datasets used
  gameID = 'Horizon_Zero_Dawn' #To save trained models and other outputs with the game(s) name
  wholeDataset = True #Whether to use the whole dataset or 20% of it to reduce computation time

Change this one if you change the classifier : 
  ClassifierID = 'MLPClassifier' #To save trained models and other ouputs with the classifier name

output/ folder container the result for previous experiments.

Trained models were removed because too heavy for github (>100MB)
You will have to train your own models to use the additionnel part of the notebook (manual testing on another dataset than the one the model is trained on)

Dataset built from the Video Game Dialogue Corpus : 
https://github.com/seannyD/VideoGameDialogueCorpusPublic
