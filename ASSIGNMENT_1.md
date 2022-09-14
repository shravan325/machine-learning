#the dataset is imported from kaggle dataset website https://www.kaggle.com/datasets/kanteya/resale-dataset-jan-2018?select=shoes_dataset.csv


#imported the dataset from the documents
read_csv("C:/Users/shravan/OneDrive/Documents/shoes_dataset.csv")


#to view the dataset
View(shoes_dataset) 


#to show the first few data variables
head(shoes_dataset) 


#to show the last set of data variables
tail(shoes_dataset)


#to show the summary of the dataset like max,min,median,mean,mode
summary(shoes_dataset)

#to plot the scatterplot between profit and sales
plot(Profit,Sale)


