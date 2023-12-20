# Machine-Learning-Project 2023 
## Presentation of the projetct
Welcome to the file of progress for the Machine Learning Project of Data Science and Machine Learning course of the University of Lausanne. Our Machine Learning problem is about assesing sentence difficulty.The team of this repository is composed of Alessandro BARBIERI and Taylan SAHIN.

We have a dataset with some senteces in french and their difficulties levels. We have to train this model to create our own model in aim to predict the most accurate possible an other dataset with other sentences. 
To find the most accurate models we have to try differents models and parameters to find the best one. There is a ranking for this profect with all the members and you can find the evolution of this competition and support us.  https://www.kaggle.com/competitions/detecting-french-texts-difficulty-level-2023/overview

## Orgisation in the group 
On this GITHUB we create a kind of schedule do be aware what to do and. This is our schedule. 
![image](https://github.com/BARB5327/Machine-Learning-Project-UNIL_TUDOR/assets/75091137/fe1a4224-6ecd-4809-8033-e0431cf63c66)


## Structure of the GITHUB
We will write our evolution in a table of progress where will speak about the of the group, the differents models that we test and the differents parameters. Furthermore we'll do an interactive interface to show our results with streamlit, and present a video with our results available on this link :https://www.youtube.com/watch?v=xfMngmtuoGc
You can find our models in the models section of the project. If you want to find the documentation that help us for this project, you have to go on the documentation section. Unfortunately the code of our Streamlit app is not available in the project because the latter is too heavy. If you want to discover the code of this app, send me an email at :alessandro.barbieri@unil.ch and we will share you the streamlit app or you can click on this link : https://drive.google.com/drive/folders/14jXji8eeCZRpP5WAOhvc6OSE2dGx7qKZ?usp=drive_link

However you can see how the app work in our youtube presentation. 

In this project your can find our table of progress file with all the others folders and also the setup to configure gitHub in your terminal. 

## Methodology 
For this project we begin to do some research for the best models. And we decide to try some models. These models are KNN, Logistic Regression, Random Forest and Decision Tree. These models can be used for classification and are not so complex. We wanted to see how good they were. This models are explains on the table of progress as the part1 of our project. Then the part 2 is composed of CNN, LSTM, BERT and Camembert models. These ones are more complex and are energy intensive. 
### Models in part 1 
We use tfidf vector to vectorize the sentences and then their own classifier. And also some other method to try to optimize the models like stop words for the Logistic Regression. We want to know more about what we did with these stop words ? You know where to go --> Models in our project folder. 

### Model in part 2 
For the models in part2 we use a label encoder to encode the difficulty level as figure from 0 to 5 for our 5 labels. And then we configure our models to train and then evaluate the model. We use also some tensors and tokenization like the Camembert tokenizer specialized for french sentences. 

## Results 
Here you can see a recap from our results. You can see some metrics on the training dataset and also our score in Kaggle.
![image](https://github.com/BARB5327/Machine-Learning-Project-UNIL_TUDOR/assets/75091137/b9ebcc07-3e7a-4cd6-a022-121494557628)

### Here a graph to represent to you these results 
![newplot](https://github.com/BARB5327/Machine-Learning-Project-UNIL_TUDOR/assets/75091137/4fa94235-8f8c-468b-a3cb-315743ccc36c)
## App Streamlit 
In our app streamlit you can type a senetence and then, it will predict the difficulty of the sentence. 

![image](https://github.com/BARB5327/Machine-Learning-Project-UNIL_TUDOR/assets/75091137/e128c088-1778-4420-b912-287528993c18)

## Youtube video 
This is the link to the youtube video : https://www.youtube.com/watch?v=xfMngmtuoGc
# Contact us 
If you have any remark, suggrestion or questions don't hesitate to contact : Alessandro BARBIERI by mail alessandro.barbieri@unil.ch
![Logo_Université_de_Lausanne svg](https://github.com/BARB5327/Machine-Learning-Project-UNIL_TUDOR/assets/75091137/9965ca3e-83ee-40ec-bd80-6ce421757791)



