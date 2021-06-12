# TEDed-Talks-views-prediction
TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000 TED talks including transcripts in many languages Founded in 1984 by Richard Salman as a nonprofit organization that aimed at bringing experts from the fields of Technology, Entertainment, and Design together, TED Conferences have gone on to become the Mecca of ideas from virtually all walks of life. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates.

---

### Dataset info

* Number of records: 4,005

* Number of attributes: 19

### Features information:

The dataset contains features like:

* talk_id: Talk identification number provided by TED
* title: Title of the talk
* speaker_1: First speaker in TED's speaker list
* all_speakers: Speakers in the talk
* occupations: Occupations of the speakers
* about_speakers: Blurb about each speaker
* recorded_date: Date the talk was recorded
* published_date: Date the talk was published to TED.com
* event: Event or medium in which the talk was given
* native_lang: Language the talk was given in
* available_lang: All available languages (lang_code) for a talk
* comments: Count of comments
* duration: Duration in seconds
* topics: Related tags or topics for the talk
* related_talks: Related talks (key='talk_id',value='title')
* url: URL of the talk
* description: Description of the talk
* transcript: Full transcript of the talk
### Target Variable :

* views: Contains Count of views of every talk
---
# The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website. 
For that we have to do some feature engineering as follows:

* Here, we have only 3 numerical columns in our dataset out of which 1 is our target variable and 2 can be used as features and rest all columns are either categorical or they contains textual data.
* So, our main goal here is to find or generate some numerical or categorical features using these columns. 
Prerequisites

* Good understanding of ML algorithms
Technologies used

* IDE- Google colab

# Project Work flow
---

1. Importing Libraries

2. Loading the dataset

3. Data Cleaning

4. EDA on features

5. Feature selection

6. Fitting the regression models

7. HyperParameter Tuning

8. Evaluation Metrices of the model

9. Final selection of the model

10. Conclusion

Sources: This project is part of AlmaBetter Curriculum.
# XGBoost
XGBoost stands for Extreme Gradient Boosting. XGBoost is a powerful machine learning algorithm that is dominating the world of applied machine learning and Kaggle competitions. It is an implementation of gradient boosted trees designed for speed and accuracy.

XGBoost (Extreme Gradient Boosting) is an advanced implementation of the gradient boosting algorithm. It has proved to be a highly effective machine learning algorithm extensively used in machine learning competitions. XGBoost has high predictive power and is almost 10 times faster than other gradient boosting techniques. It also includes a variety of regularization parameters which reduces overfitting and improves overall performance. Hence, it is also known as regularized boosting technique.

XGBoost was developed by Tianqi Chen in C++ but also enables interfaces for Python, R and Julia. Initially, he started XGBoost as a research project as part of the Distributed (Deep) Machine Learning Community. It became popular in the ML competitions after its use in the winning solution of the Higgs Machine Learning Challenge.
# Credits
Sumanta | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumanta97/ )
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sksuman97/)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@sumanta-skm98)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/1DkZqmtw2c_I-EEAOw9iyzd-EAeBoJ6nj/view?usp=sharing)


Contact me for Data Science Project Collaborations
# References
1. A Gentle Introduction to XGBoost for Applied Machine Learning by Jason Brownlee on August 17, 2016 in XGBoost Available- https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/
2. wikipedia.org, XGBoost- https://en.wikipedia.org/wiki/XGBoost
3. Target encoding- https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/target-encoding.html#:~:text=Target%20encoding%20is%20the%20process,by%20the%20target%20encoder%20model.&text=This%20can%20help%20improve%20machine,dealing%20with%20high%20cardinality%20columns.
4. Medium target encoding- https://medium.com/analytics-vidhya/target-encoding-vs-one-hot-encoding-with-simple-examples-276a7e7b3e64
