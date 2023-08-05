<h1 align="center">
                    Text Analysis Web App 💬 📝 ✍️
</h1>

![image](https://github.com/Anas436/Text-Analysis-App/blob/main/Complete%20Text%20Analysis%20Home%20Page.jpg)

This app is used to perform an indepth analysis of a text
The analysis sections include ->

**1. Spam or Ham Detection**

**2. Sentiment Analysis**

**3. Stress Detection**

**4. Hate & Offensive Content Detection**

**5. Sarcasm Detection**

## Tech Stacks Used

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>

## Libraries Used

<img src="https://img.shields.io/badge/numpy%20-%2314354C.svg?&style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/pandas%20-%2314354C.svg?&style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/streamlit%20-%2314354C.svg?&style=for-the-badge&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/nltk%20-%2314354C.svg?&style=for-the-badge&logo=nltk&logoColor=white"/> <img src="https://img.shields.io/badge/scikitlearn%20-%2314354C.svg?&style=for-the-badge&logo=scikitlearn&logoColor=white"/>

## Structure Of The Project

- Each prediction page is conneceted with a Machine Learning Model which uses either of Logistic Regression, Decision Tree, Random Forest Algorithms to predict the results.
- Also we have 5 different datasets being used for each prediction.
- We can land into each prediction site of the web app from the options in the Navigation Menu.
- We have only 1 relevant feature taken into consideration which is the text and then the text is preprocessed and vectoized with help of TF-IDF Vectorizer to fit into the model and tain it.
- So the user gets a broad overview of the text after the analysis

## The feature taken into consideration

| Text Analysis Type | Feature |
| - | - |
| Spam or Ham Detection Page | Text |
| Sentiment Analysis Page | Text |
| Stress Detection Page | Text |
| Hate & Offensive Content Page | Text |
| Sarcasm Detection | Text |

The text is preprocessed then fed to the model.

## Deployment Of The Project

After the modeling part the model is deployed using Streamlit library on Streamlit Share so that the app is available for usage for everyone.

## Glance At The Hosted Application- 

### 1. Home Page
![image](https://github.com/Anas436/Text-Analysis-App/blob/main/images/1.png)

### 2. Spam or Ham Detection Page
![image](https://github.com/Anas436/Text-Analysis-App/blob/main/images/2.png)

### 3. Sentiment Analysis Page
![image](https://github.com/Anas436/Text-Analysis-App/blob/main/images/3.png)

### 4. Stress Detection Page
![image](https://github.com/Anas436/Text-Analysis-App/blob/main/images/4.png)

### 5. Hate & Offensive Content Page
![image](https://github.com/Anas436/Text-Analysis-App/blob/main/images/5.png)

### 6. Sarcasm Detection Page
![image](https://github.com/Anas436/Text-Analysis-App/blob/main/images/6.png)
