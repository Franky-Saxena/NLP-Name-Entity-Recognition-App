
# NLP-Name-Entity-Recognition Streamlit App

In this project we want to identify the Names and Entities from the text we can use this project to summarize the text very easily.

In this project we have two parts:
    '''
    1. First one is for word Tokenization.
    2. Name Entity Recognition.
    '''
In:
    1. In this we are just tokenizing the raw text which ever is present there and also removing the stop words.
    2. In this we are identifing the Name, Organization, Date, etc. And show the frequency table for that also.

## Modules used:
* Streamlit
* spacy_streamlit
* spacy
    * load
        * `en_core_web_sm`

## To Run the Name Entity Recognition
run a following command in terminal of pycharm
```
python app.py
```
## Deployment
```
1. Load the necessary Modules
2. Initialize the spacy
3. And load the `en_core_web_sm` package.
4. Start Conditional Statement.
5. First is for Tokenization.
6. else part for the Name Entity Recognition.
7. And Display it on the Streamlit App.
```


## Demo

![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-Name-Entity-Recognition-App/main/Untitled1.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-Name-Entity-Recognition-App/main/Untitled2.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-Name-Entity-Recognition-App/main/Untitled3.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-Name-Entity-Recognition-App/main/Untitled4.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/NLP-Name-Entity-Recognition-App/main/Untitled5.png)
