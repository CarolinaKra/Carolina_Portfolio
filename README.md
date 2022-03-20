
# About me:
I am a Data Scientist with AI specialisation. I am currently working on my final project for my MSc in Data Science and AI from the University of London.
I have a strong interest in AI, Neural Networks and Machine Learning.

Besides this, I have a very strong analytical mind and I am a values-driven professional.
I was born in Argentina, as a child and a teenager, I participated in various Mathematical Olympiads and reached the national final. I moved to Israel as a teenager, where I finished college and served in the Israeli Army as a medic. Then, I have studied for my BSc in Biotechnology Engineering at the Ben Gurion University of the Negev. During the last year, as part of my final project, I proposed an optimised method to produce biodiesel from waste. This has strengthened my values for a sustainable environment and led to my interest in the renewable energy sector. This is the sector where I have spent most of my professional career, both in Israel and in the UK, working on different projects such as product development, process optimisation and analytical test method development. Several years ago, I realised that the parts I enjoyed the most from my work were the parts that I analysed data and I tried to fit models into the analytical results. By 2019, I started researching and self-learning Data Science and in April 2020, I enrolled in the MSc. Data Science and AI programme. This career path reflects better my personal interests and my core strenghs. This Portfolio reflects some of the projects I have done during my master's and as part of my last job at Johnson Matthey Fuel Cells.

# My Projects:
## [Project 1: Multi-Label Classification of Fashion Articles Images](https://github.com/CarolinaKra/FashionArticlesImageClassification)
### My Computer Vision Project with Convolutional Neural Networks
* Developed a CNN model that predicts the gender, the category and the subcategory of fashion article images
* Carried out Exploratory Data Analysis
* Carried out Data Cleansing and Image Processing as part of the data preparation stage
* I applied the keras functional API for building models with multiple outputs
* I explored models with different local receptive field sizes and number of filters on the conv2d layers, different number of nodes in the dense layer, addition of BatchNormalisation and addition of Dropout layer of different rates.
* The final model achieved an averaged accuracy of 94.1%, which composes of a 98.3% accuracy for masterCategory, 94.7% for subCategory and 89.4% for gender.
* The model successfully classified all the different classes within masterCategory, almost all of them within subCategory but for the gender task classification, the model struggled to classify correctly the unisex articles.

![correct image](/docs/assets/correct0.png)
![incorrect image](/docs/assets/incorrectgender.png)

_Examples of a correctly and an incorreclty classified article images_

_The dataset contained low quality images (80x60 pixels) to speed up the model learning process_

## [Project 2: Sentiment Analysis on Tourist Accommodation Reviews](https://github.com/CarolinaKra/SentimentAnalysisHotelReviews)
### My Natural Language Processing Project
* Developed a model to predict the sentiment of a textual Tourist Accommodation Reviews.
* Showed the keywords that are used in negative and positive reviews.
* Developed different pre-processing strategies using NLP tools. 
* Applied different machine learning models: Naive Bayes, Decision Trees and SVM.
* Used pre-trained lexicon based-models for sentiment analysis from Textblob and NLTK.
* Evaluated the best combination of pre-processing and ML models together and the pre-trained model to select the best final model.
* The best model achieved an accuracy of 86.3% and an f1 with macroaveraging of 64.2%. 
* Found that it is feasible to predict positive and negative reviews, but not so much the neutral ones.

![features](/docs/assets/NLPimportantFeaturessmall.png)

_The most important words in the reviews the model found to differentiate between the positive and the negative reviews_

## [Project 3: Wine Quality Predictor](https://github.com/CarolinaKra/WineQualityPredictor)
### My first Neural Network Project
* Developed a Neural Network model that attempts to predict the sensory quality of wine based on its physicochemical properties.
* This project followed the Universal Machine Learning Workflow.
* I used a Design-of-Experiments (DoE) strategy to explore the influence of 3 hyperparameters: number of nodes per layer, number of layers and the type of activation function. The aim of the DoE was to maximise the exploratory space while minimising the number of experiments.
* The final model achieved an accuracy of 67.62%, improving the initial 44.9% of the baseline model.
* The confusion matrix showed the model confused the original class with a similar class (e.g. 6 with 7).
* Improvements of the predictor model could be done by changing the model as a regressor or bin classes to form general classes (low, medium, high quality).

![doe](/docs/assets/DoE.png) 

_Design of Experiment strategy I used to find the optimal hyperparameters for the neural network arquitecture_

## [Project 4: Life Saving Decision Support System](https://github.com/CarolinaKra/LifeSavingDSS)
### My Artificial Intelligence Project
* Developed a Decision Support System (DSS) that can determine whether a person needs resuscitation using user inputs into an app and live data from wearable devices.
* Set Objective, Task and Constraints
* Created a Conceptual Design of the DSS
* Implemented a DSS using Bayesian Network as a knowledge model in python
* Queried the DSS to obtain the best decision in different scenarios

![BayesianNetwork](/docs/assets/graphsmall.png)

_Graphical representation of the bayesian network I created for the dss showing the prior probabilities_

## [Project 5: Blockchain Development](https://github.com/CarolinaKra/Blockchain)
### I took part of the creation of ZimCoin
* Developed a cryptocurrency
* Developed the transaction unit, using cryptography for the transaction signature and the transaction verification
* Developed the block unit, and the function for mining a block using proof-of-work as the consensus mechanism
* Developed the blockchain itself with the possibility of reorg in the case of a fork, keeping the chain with the highest difficulty
* The development of a blockchain keeps track of the users' status, which includes their nonce and their balance.
* Unification of the developed code with other given programmes to be able to mine blocks in a distributed blockchain.
* Further research and essay writing on different areas within the cryptocurrency world

## [Project 6: Influence Of Video Conferences](https://github.com/CarolinaKra/InfluenceOfVideoConferences)
### My DataViz and Qualitative Analysis Project
* Analysed the Influence of Video Conferencing on society during the Covid-19 Pandemic (Dec 2020) 
* Set Research Question, Motivation and Objectives
* Designed and Conducted a self-administered survey
* Cleaned and Prepared the Data for Analysis
* Analysed Data with Tables, Visualisations and Correlation Calculations
* Concluded that Video Conferencing brings a great benefit for the society in the way that people can connect and the way that individuals can develop, especially during the pandemic
* Predicted that in the future post-pandemic, the population will use Video Conferencing less frequently than the time during pandemic, and it will continue to be an important tool for work and study purposes.

![levelofhelp](docs/assets/levelofHelp.png)

_Example of a visualisation within the project which shows how much Video Conferencing helped the population cope with social distancing during the pandemic_

## Project 7: Understading the raw material and production process effects in the product viscosity curve
### Attempting to solve a real business/production problem
* Created a model which was composed of two different models to understand the relationship between the raw materials properties, the production process with the product characteristics. 
* The company was having high defect rates which make her loose money.
* With a new analysis method I demonstrated the link between the intermediate product characteristics with the defect rates in the final product.
* The result of this analysis method is not a number but a combination of two variables forming a curve.
* Joined data from different sources across the company (suppliers, production, QC lab) and prepared the final dataset.
* Created a model to link the product characteristic, represented as a curve, with the different input data to understand the main factors that affected the product. 
* The final model was composed of two models
  * The first was done with the Functional Data Explorer from JMP PRO, which aim is to decompose the curves into eigen-fuctions and eigen values. This is similar to Principal Component Analysis but with more advanced functionality.
  * The second model was done as a regression with Partial Least Squares due to the high multi-correlation between the inputs.
* This model shown that the main contribuitor to the product charcateristic was one of the raw material however it was difficult to pinpoint on a specific property due to correlation between them.
* A further experiment with different raw material properties was carried out however it didn't led to a significant results.
* This work was selected as one of the 20 projects to be presented in a 5-day internal science conference.
* I gave a an online presentation about this project in this conference to an audience of hundreeds of JM scientist and engineers around the globe.



