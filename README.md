# Cards recognition

## Introduction
We wanted to identify which cards is on a picture.

Firstly, we created a datasets using image processing. I took pictures of 52 cards with different lightings, then used cantour detection to crop out the cards and put them on different background while record their position into a text file and then to the XML format to feed into the model. Here is an example of the genareted dataset
![Example](generated_dataset.jpg)

It is important to note that we want to detect only the small parts at the corners of the cards, as sometimes the other parts are covered. After feeding the dataset into the model, we will get the result and here is an example of the result:
![Example](result.png)




## Library



## Structure and Components
Calculate parameters for linear models using maximum likelihood estimation

- `create_tables.py`: Create tables for database 
- `load_data.py`: Load data for simulation 


