# Global Terrorism Data Analysis #
![terror attack](https://i.imgur.com/d5meDH5.png)




## Predictng Terrorist "Group" given the data features. ##
![pulwama attack](https://i.imgur.com/Gutnojl.png)

## Road map ##

![terror attack](https://i.imgur.com/XjfalWc.jpg)

### 1- Feature engineering : ###
a- Adding attributes to make more sensible attribute
b- Removing the outliers i.e terrorists group which has occurrence less than 10 in the dataset

### 2- EDA : ###
a-Histogram Analysis : Observing the frequency distribution of numerical attributes.
b-Scatter plot Analysis : Geographical distribution of casualities
c- Observing the most active terrorist Organizations : This shows that the dataset is highly imbalanced
d- Wordcloud : On Motives,Target,Types,Summary

### 3- Data Preparation : ###
a- Imputing nan values of categorical data points by their mode(most frequent)
b- Applying pipeline to numerical features(imputer,scaling) and categorical features(1-hot encoding)
c- Splitting training and test features and labels

### 4- Handling Imbalanced dataset: ###
a- Using SMOTE(Synthetic Minority Over-sampling Technique): This creates the oversampling of minority classes considering the neighbours of the class
b- Using class_weight (During training) : This makes the model more bias towards the minority by penalizing heavily for the error happening in the case of minority class then to the majority class

### 5- Using Random Forest classifier ###
### 6- F1 Score : 0.719373911056525(avg:micro);0.6913907382270787(avg:weighted) ###
