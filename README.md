# Plant-Pathology-2020-Competition

Welcome you! This is my implementation of some Machine Learning algorithms for the [Titanic: Machine Learning from Disaster Competition](https://www.kaggle.com/c/titanic) hosted at Kaggle.

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/Logo.PNG?raw=true)

The goal of the Competition was simple enough: 
- Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

I was able to achieve the top 17% leaderboard with an MC AUROC Score of 0.97165, getting the 219° place (of a total of 1317 teams).

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/rank.PNG?raw=true)

First, i performed a simple EDA on the dataset provided by Kaggle. You can check it in the notebook `Exploratory Analysis.ipynb`.

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/EDA.PNG?raw=true)

Second, in the notebook `CNN Train in Pytorch.ipynb` you shall find every bit of detail of how the training was accomplished using a `ResneSt50` architecture. By the end of the entire training process, i was able to achieve a `95.968%` accuracy on the test set.

![alt text](https://raw.githubusercontent.com/ChristianCFranca/Plant-Pathology-2020-Competition/main/git-images/CMResults.PNG?raw=true)

I set a seed if you wish to reproduce the results. You can obtain the dataset in the original link of the competition that i provided at the beggining.
