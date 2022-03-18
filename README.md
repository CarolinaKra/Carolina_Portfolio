
## [Project 1: Multi-Label Classification of Fashion Articles Images](https://github.com/CarolinaKra/FashionArticlesImageClassification)
* Developed a CNN model that predicts the gender, the category and the subcategory of fashion article images
* Carried out Data exploration and Data cleansing and Image Processing for data preparation
* I applied the keras functional API for building models with multiple outputs
* I explored models with different local receptive field sizes and number of filters on the conv2d layers, different number of nodes in the dense layer, addition of BatchNormalisation and addition of Dropout layer of different rates.
* The final model achieved an averaged accuracy of 94.1%, which includes a 98.3% accuracy for masterCategory, 94.7% for subCategory and 89.4% for gender.
* The model successfully classified all the different classes within masterCategory, almost all of them within subCategory but for the gender task classification, the model struggled to classify correctly the unisex articles.

![correct image](https://github.com/CarolinaKra/Carolina_Portfolio/blob/main/docs/assets/correct0%20(1).png)
![incorrect image](https://github.com/CarolinaKra/Carolina_Portfolio/blob/main/docs/assets/incorrectgender%20(1).png)

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

![features](https://github.com/CarolinaKra/Carolina_Portfolio/blob/main/docs/assets/NLPimportantFeaturessmall.png)

_this shows the most important words in the reviews the model found to differentiate the positive from the negative reviews_






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
