I made use of google colab to perform task1, that is datacleaning,handling nulls,encoding,feature selection.
step1: i manually loaded the dataset into the colab notebook. And then copied the path of that dataset.
step2: i made use of pandas to read the csv file. 
step3: analysed the dataset. after analysing it i observed that the cabin has too many missing values. and passenger_id,name,and ticket are generally not useful for prediction. so itried dropping irrelevant and high-missing columns
step4:tried filling missing values. like filled missing values in age column with the median age which is 28.0 and filled missing values in embarked column with the mode
step5: applied encoding. coverted sex column using label encoding and converted embarked column using one-hot encoding
step6:standardized the numerical features of the titanic dataset using standardscaler
step7: tried to visualize the outliers for the scaled nummerical features using boxplots
step8:outliers were removed using the interquartile range method.we now obtain the resulting dataset x_final and y_final that is highly cleaned,fully numb=erical,scaled and had its extreme outliers removed.
