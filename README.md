# Machine-Learning

## Kaggle Competition: Smith's Parasite
[link](https://pages.github.com/](https://www.kaggle.com/competitions/the-smith-parasite/overview)

Prediction Score: 1.00/1.00

<img width="756" alt="Screenshot 2023-02-14 at 15 19 13" src="https://user-images.githubusercontent.com/86632157/218780211-0e21664a-ae5c-41cc-8632-5853dc4693a5.png">

### Introduction
This report concerns a new disease transmitted by a virus that has been discovered in England by Dr. Smith and has already affected over 5000 people. Some of the people contracting the disease are asymptomatic, but the most common symptoms include fever and tiredness. The virus has also been associated with post-disease conditions such as loss of speech, confusion, chest pain and shortness of breath. The circumstances regarding the transmission of the disease are unknown and although there is no apparent connection between the infected people, some groups seem more prone to be infected than others.

The goal of this project is to develop and validate a classification model that predicts if a patient will suffer or not from the Smith Disease based on sociodemographic, health and behavioral data. The efficiency of the predictions made by the model will be measured by the F1 score. 

### Conclusion
In summary, during the execution of the project we developed three different Machine Learning models and trained them using 8 features related to patients’ health, sociodemographic and habits information. We validated and compared the algorithms using stratified four-fold cross-validation, fine-tuned their parameters and assessed their performance using the Accuracy, Precision, Recall, and F1 scores and found that the best performing model to predict the dependent variable was Random Forest, achieving scores of 99%, 99%, 96% and 99% respectively. Putting it all together, the selected model was used to train the whole train dataset in order to predict the test data presented so the labels could be uploaded to Kaggle, generating a final F-1 score of 1.
