# MachineLearning
# Exploratory Data Analysis
To Gain maximum insight into the data set and its underlying structure. Uncover a parsimonious model, one which explains the data with a minimum number of predictor variables.<hr>
Before going to selecting the alogorithm we have to do data analysis so that we can understand the data.<br>
Sometimes it helps in selceting the alogorithm( Machine Learning Model).<br>
In my case i have spended a lot of time on data analysis, By that i came to conclusion of which <b> Model </b> to use.

<b> Note : I am not sharing the main "Excel" file because it has the lot of important user data. 
I Preprocessed it according to my need and sharing the file by removing all important data </b>

## Visualizations

### Matplotlib

As i am new to Machine learning i learned "Matplotlib library" first and applied to the datasets i have.<br>
<i>P S :I never satisfied with my visualizations</i> :(
<br> 

### Seaborn

Do you know, I am one of the person who satisfied very much when i am using this package LOL!. No need to set ticks, labels, color's. Cool Right!!!!!

I was bit surprised and learning mainly used techniques and applied. But this becomes when i am plotting more data.<br> whether i have to set big figure size (or) sometimes i can't even zoom
my data. I frequently download the data and zooming it for better understading.

### Plotly

A better package i have never seen before. Plotly is build on matplotlib and seaborn.
<br>Its cool javascript based front end allows do any tasks like zoooooooming, selecting particular and downloading it. what not!!

Basically i have used almost seaborn and plotly packages for my visualizations.
A big thanks to those <em>developers!!!<em>
<i> Until now i have done with my visualization part and handled some missing data</i>


# Data Cleaning (Encoding)

If you see the dataset you may find the lot of Categorical features. we have a lot of encoding methods like <i> One Hot Encoding, Label Encoding, Binary Encoding,.....more</i>

#### Frequency Encoding 

Here mostly I have applied frequency encoding because,having more unique values we can't use general encoding methods.

Frequency encoding helps us to give weightage according to it count. So, in many cases we don't need to worry about this.<br>
But it has its own drawbacks which we will discuss later. But in my case when i applied this i got best results.

#### Label Encoding

You can see,i have applied label encoding for 1-3 features, as per the data.

#### Sort Encoding

May be it sounds weird to you but i have applied this in my own way. 
I have taken <i> value_counts </i> and sorted values then i mapped values by enumerating it from 0 to n.<br>
Say, I have 11 types of variables. I sorted the data and applied from 0 to 11.So, the variables are get the values according their count.
Because my "class" label is an categorical type. so, i tried this approach.
<br>
Now, i have a clean numerical data.

# Feature Engineering 

Feature Engineering is a data preparation process technique. One modifies the data such that Machine Learning algorithms identify more patterns.<br>

### Feature Selction

Used Pearson correlation to find the best columns, and dropped unnecessary features.

# Algorithm Selection

Since the class labels are classification type, we have to select the best classification algorithm.<br>
Mostly i have un-even data, i am safe to use <b>DecisionTree Classifier<b>, Generally decision tree tends to overfit the data.<br>
Mostly 30% of the class label is single type, I believe it tends to overfit and used <b>RandomForestClassifier<b> and to select the best parameters i have used
<b>Hyper Parameter Tuning<b> after fitting the data with best params, predict the test_data. 
  <br>Here i got <b>99.3%<b> accuracy for train data and <b>99.2<b> for test data<br>
  
## Performance Metrics

I have used confuion matrix to know where i am wrong.

  

