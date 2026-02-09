In this project , i created a model that could predict the survival of an individal on the titanic based on the Passenger_id , AGE ,Pclass,SibSP,Fare, Sex and Port Embarked.
The Necessary libraries where imported
I checked the numerical and categorical variables in the dataset using the .describe(include = 'all')
Used the .isnull().sum() to check for missing values
Plotted the Survived column against the existing columns to determine those survived based on the columns
To deal with missing values , i imputed and dropped columns where necessary
Splitted the data into two , One with the Survived column and one without the Survived columns
Further split into training and testing by import Train_Test_Split from sklearn
Scaled the data by importing StandardScaler from sklearn
used ML Models to evaluate the data and picked one with the highest accuracy.
