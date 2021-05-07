# Final_Project
Problem Statement that introduces your selected topic, identifies significant goals associated with the implementation of your applied machine learning method, demonstrates why your problem is important, and describes and analyzes the complex nature of your problem including any process oriented causes and effects. Conclude your problem statement with a stated central research question. You are welcome to articulate a central research question in broad and general terms, given the abbreviated time frame for this investigation.

Problem Statement:

Every year millions of people lose their lives to cardiovascular disease/heart failure due to many different factors but mostly because of poor health. In the US heart failure is the leading cause of death in adults. As the leading cause of death in the US being able to predict heart failure before it happens would be extremely beneficial. 
Can a ML algorithm sufficiently predict the likelihood of someone dying from heart disease based on observable features collected from their health data? This kind of model would be useful to health care providers and patients alike when it comes to assessing the severity of their heart condition whether or not they know if they have one.

At first i wanted to look at using machine learning algorithms to forecast sales data but due to not finding an appropriate dataset i decided to switch to predicting stock prices instead. While there is an abundance of stock price data available i eventually decided that there were too many external factors that go into the daily price movements that affect individual stocks. After this i decided to try making a sentiment analysis classifier, which i did, but then realized afterwards that my research problem statement was not compatible with the dataset that i was using. So i finally decided to make heart failure predictors using a linear estimator, a random forest, and a boosted tree model.

Data Sources: Kaggle
[https://www.kaggle.com/andrewmvd/heart-failure-clinical-data]

Data description:

This dataset was obtained from Kaggle and you can find it in the link above. There are a total of 300 rows in the entire dataset although a larger dataset would have been preferred. Furthermore there are 13 columns of which i will be using 12 since the column 'time' is not relevant to the desired goal. 
The column names are:
      'age', 'anaemia', 'creatinine_phosphokinase', 'diabetes',
      'ejection_fraction', 'high_blood_pressure', 'platelets',
      'serum_creatinine', 'serum_sodium', 'sex', 'smoking', 'time',
      'DEATH_EVENT'
      



