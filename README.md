
## [Project 1: Multi-Label Classification of Fashion Articles Images](https://github.com/CarolinaKra/FashionArticlesImageClassification)
* Developed a CNN model that predicts the gender, the category and the subcategory of fashion article images
* Carried out Exploratory Data Analysis
* Carried out data cleansing and Image Processing as part of the data preparation stage
* I applied the keras functional API for building models with multiple outputs
* I explored models with different local receptive field sizes and number of filters on the conv2d layers, different number of nodes in the dense layer, addition of BatchNormalisation and addition of Dropout layer of different rates.
* The final model achieved an averaged accuracy of 94.1%, which includes a 98.3% accuracy for masterCategory, 94.7% for subCategory and 89.4% for gender.
* The model successfully classified all the different classes within masterCategory, almost all of them within subCategory but for the gender task classification, the model struggled to classify correctly the unisex articles.

![correct image](/Carolina_Portfolio/assets/correct0%20(1).png)
![incorrect image](/Carolina_Portfolio/assets/incorrectgender%20(1).png)

_the above images show examples of a correctly and an incorreclty classified article images_

## [Project 2: Sentiment Analysis on Tourist Accommodation Reviews](https://github.com/CarolinaKra/SentimentAnalysisHotelReviews)
* Developed a model to predict the sentiment of a textual Tourist Accommodation Review
* Showed the keywords that are used in negative and positive reviews.
* Developed different pre-processing strategies using NLP tools. 
* Applied different machine learning models: Naive Bayes, Decision Trees, SVM
* Used pre-trained lexicon based-models for sentiment analysis from Textblob and NLTK
* Evaluated the best combination of pre-processing and ML models and the pre-trained model
* The best model achieved an accuracy of 86.3% and an f1 with macroaveraging of 64.2% 
* Found that it is feasible to predict positive and negative reviews, but not so much the neutral ones

![features](/Carolina_Portfolio/assets/NLPimportantFeaturessmall.png)

_this shows the most important words in the reviews the model found to differentiate the positive from the negative reviews_

## [Project 3: Wine Quality Predictor](https://github.com/CarolinaKra/WineQualityPredictor)
* Developed a Neural Network model that attempts to predict the sensory quality of wine based on its physicochemical properties.
* This project followed the Universal Machine Learning Workflow.
* I used a Design-of-Experiments (DoE) strategy to explore the influence of 3 hyperparameters: number of nodes per layer, number of layers and the type of activation function. The aim of the DoE was to maximise the exploratory space while minimising the number of experiments.
* The final model achieved an accuracy of 67.62%, improving the initial 44.9% of the baseline model.
* The confusion matrix showed the model confused the original class with a similar class (e.g. 6 with 7).
* Improvements of the predictor model could be done by changing the model as a regressor or bin classes to form general classes (low, medium, high quality).

![doe](/Carolina_Portfolio/assets/DoE%20(1).png) 

_this is the Design of Experiment strategy I used to find the optimal hyperparameters for the neural network arquitecture_

## [Project 4: Life Saving Decision Support System](https://github.com/CarolinaKra/LifeSavingDSS)
* Developed a Decision Support System (DSS) that can determine whether a person needs resuscitation using user inputs into an app and live data from wearable devices.
* Set Objective, Task and Constraints
* Created a Conceptual Design of the DSS
* Implemented a DSS using Bayesian Network as a knowledge model in python
* Queried the DSS to obtain the best decision in different scenarios

![BayesianNetwork](/Carolina_Portfolio/assets/graph.png)

_this is a graphical representation of the bayesian network I created for the dss_

## [Project 5: Blockchain Development](https://github.com/CarolinaKra/Blockchain)
* Development of a cryptocurrency
* Development of the transaction unit, using cryptography for the transaction signature and the transaction verification
* Development of the block unit, and the function for mining a block using proof-of-work as the consensus mechanism
* Development of the blockchain itself with the possibility of reorg in the case of a fork, keeping the chain with the highest difficulty
* The development of a blockchain keeps track of the user status, which includes a nonce and its balance.
* Unification of the developed code with other given programmes to be able to mine blocks in a distributed blockchain.
* Further research and essay writing on different areas within the cryptocurrency world








Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CarolinaKra/Carolina_Portfolio/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
