# NLP-Demo      [*!Still on Working!*]
**Deep Learning for Natural Language Processing**

## 1. [Overview]((https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Overview)) 
  In this section, materials (paper and websites) are contained for better understanding of the following projects.
  + [Algorithms Application](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Overview/NLP%26Deep%20Learning.pdf)

## 2. Text Processing
  + [1. Processing in Chinese Text](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processing)
  
    * [Chinese Stop Words](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processing/stop%20words)
    * [Jieba, Pkuseg, Thulac: Demo](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Chinese%20Text%20Processing/Chinese%20Text%20Processing.ipynb)
  + [2. Processing in English Text](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/English%20Text%20Processing)
  + [3. Language Translation](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Language%20Translation)

## 3. Application
+ **1. Text Classification**
  - [Movie Comments (English)](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Application/Movie%20Comments)
      -[BiLSTM](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Application/Movie%20Comments/Movie%20Classification.ipynb)
  - [Movie Reviews (Chinese)](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processng)

+ **2. Sentiment Analysis**

+ **3. Topic Modeling**

+ **4. Name Entitity Recognition**


## 4. General Structure of NLP tasks:

<img src="figs/Structure.png" alt="Structure" width="800"/>

## 5. Datasets
+ **1. Text Classification**

## 6. Key differences between text processing in English and Chinese text data:

  - **Segmentation**: Sophisticated and important to Chinese.
  
    + Chinese
                 
                 "世界你好" -> "世界", "你好"
                 "汉堡好吃" -> "汉堡", "好吃"
    
    + English
                 
                 "Hello World" -> "Hello", "World"
                 "Hamburger is delicious" -> "hamburger", "is", "delicious"  # segementation & transfer to lowercase
    
  - **Lemmatization**: Only for English.
    
    Lemmatization is often used for **Text Minning**, **NLP** for better understanding and analysis of the text.
                 
                   "did", "done", "doing", "does" -> "do"
                   "potatoes" -> "potato"                 
                   "cities" -> "city"                 
                   "children -> "child"
                 
  - **Stemming**:
    
    The word output after stemming may be meaningless.
    
    Stemming is often used for **Information Retrieval**.
                 
                   "hourse" -> "hors"
                   "writing" -> "write" / "writ"
