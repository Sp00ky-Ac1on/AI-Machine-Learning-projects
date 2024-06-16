# Model One: Iris flowers types Classification

As humans we can easily classify objects just by looking at them, smelling them or touching them. using our senses i essential to do so , but what about machines, can they learn from data so they can classify by their own ?

in this Model i made a machine learning program that you feed it with data about the Flower's:
> petals length & width.

> Sepals length & width.

so it classify it and tell you if it was:
- Iris Versicolor
- Iris Setosa
- Iris Virginca

## Process & Coding Steps :

## 1- Collecting th needed data 
i needed to feed my model with data so it can process it and learn from it.
you can find the flower's data included in the [repo](https://github.com/AnanSoli/)

## 2- preparing the data
 - you will need the following python libraries in this model

> pandas, matplotlib, seaborn, scikit-learn

![alt text](screenshots/import.PNG)

 - add the following code to open, read the comma separated data and save it into a dataframe

![alt text](screenshots/iris-2.PNG)

## 3- Add column headers to the dataframe
 - adding headers to facilitate dataframe reading.

![alt text](screenshots/iris-3.PNG)

## 4- check null data exists
- we need to check if there are any null, empty or any missing data.

![alt text](screenshots/iris-4-empty-values.PNG)

## 5- Getting a count of how much data you have
- it's important for you to know how much of data you are using to train and feed to your model so you can know later how to improve results accuracy.

![alt text](screenshots/iris-5-class-numbers.PNG)

## 6- data visualization
- reading raw data can be sometimes challenging , so visualizing this data will be much easier to read.

    using counting plot to show the flowers classes data count.
![alt text](screenshots/iris-6-count-graph.PNG)

    using scatter plot to show a comparison between the petal width and length for each flower class

![alt text](screenshots/iris-6-scatter-graph.PNG)

    using also scatter plot to show a comparison between the sepal width and length for each flower class
![alt text](screenshots/iris-6-scatter-sepal-graph.PNG)

## 7- Categorizing the data to prepare it for training .
- our dataframe consist of 3 Labels/classes of Iris flowers 
    > Iris Versicolor, Iris Setosa, Iris Virginca  (classes/Labels)

- also four features for each class 
    > Petal length , Petal width

    >Sepal Length, Sepal width

![alt text](<screenshots/7- classes & features.PNG>)

features
![alt text](<screenshots/7-2 features.PNG>)

label
![alt text](<screenshots/7-3 label.PNG>)

## 8- dividing the data we have into traning data and testing data
- we need to divide the data we have into two parts 
    > data used for training the model to classify

    > data used to test the model if the classification is good

     the training data will be 80% of the whole data, and the testing data will be 20% of the whole data.

![alt text](<screenshots/8- divide training & testing.PNG>)


