# Prediction de la stabilite de differentes enzymes
Dans le cadre du projet 8 du parcours Ingénieur Machine Learning d’OpenClassrooms, nous avons choisi une compétition sur la plateforme Kaggle. Ce projet a été mis en place par l’entreprise Novenzyme, qui a pour but de trouver des enzymes dans la nature et de les optimiser afin que ces dernières soient utilisées en industrie. Le but de cette compétition, est de prédire la stabilité thermique des enzymes naturelles et modifiées afin de répondre à des problématiques de société actuelles tel que la production zéro carbone par les industriels. 

Le lien pour la compétition se trouve ici : https://www.kaggle.com/competitions/novozymes-enzyme-stability-prediction

Sur ce lien vous trouverez le contexte de la compétition ainsi que les prix, et les participations des autres participants. Vous pouvez également trouver les données sous forme de fichier csv. 

Il y a 4 fichiers csv, un fichier train, un fichier train updtate qui contient les modifications faites sur certaines données, un fichier test afin d'avoir les séquences et les pH des éléments à tester et un fichier de soumissions qui contiendra la cible obtenu pour les séquences test dans un ordre décroissant. 

<br/> Train.csv: Fichier des entrainements<br/>
<br/>Test.csv : Fichier des tm à prédire<br/>
<br/>Train_updates_20220929.csv : Modification fichier d'entrainement <br/>
<br/>Predict_enz_nettoyage.ipynb : Notebook<br/>
<br/>Logarithmic_transformation-skew.ipynb : Partie du notebook soumit sur kaggle <br/>
<br/>Sample_submission : 2chantillon de la séquence <br/>
<br/>Prediction_tm.csv : Ce fichier est le résultat de la prédiction de la tm en fonction de la séquence<br/>
