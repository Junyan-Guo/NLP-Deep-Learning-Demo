# RGA-NLP-Demo
**Deep Learning for Natural Language Processing**

## Content
+ **0. Overview**
  In this section, materials (paper and websites) are contained for better understanding of the following projects.

+ **1. Text Processing**
  - [Processing in Chinese Text](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processing)
  - [Processing in English Text](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/English%20Text%20Processing)

## Application
+ **1. Text Classification**
  - [Movie Reviews (English)](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processng)
  - [Movie Reviews (Chinese)](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processng)

+ **2. Sentiment Analysis**

+ **3. Topic Modeling**

+ **4. Name Entitity Recognition**


## Key differences between text processing in English and Chinese text data:

  - **Segmentation**:
  
    + Chinese
                 
                 "世界你好" -> "世界", "你好"
                 "汉堡好吃" -> "汉堡", "好吃"
    
    + English
                 
                 "Hello World" -> "Hello", "World"
                 "Hamburger is delicious" -> "hamburger", "is", "delicious"  # segementation & transfer to lowercase
    
  - **Lemmatization**:
    
    Lemmatization is often used for **Text Minning**, **NLP** for better understanding and analysis of the text.
    
    + English
                 
                 "did", "done", "doing", "does" -> "do"
                 "potatoes" -> "potato"                 
                 "cities" -> "city"                 
                 "children -> "child"
                 
  - **Stemming**:
    
    The word output after stemming may be meaningless.
    
    Stemming is often used for **Information Retrieval**.
    
    + English
                 
                 "hourse" -> "hors"
                 "writing" -> "write" / "writ"
