## English Text Processing with **nltk**

For more details on [nltk](https://github.com/nltk/nltk) Module, please refer to the link below:
  - [nltk](https://github.com/nltk/nltk): https://github.com/nltk/nltk

## Key differences between text processing in English and Chinese text data:

  - **Segmentation**:
  
    **Chinese**: 
                 
                 "世界你好" -> "世界", "你好"
                 "汉堡好吃" -> "汉堡", "好吃"
    
    **English**: 
                 
                 "Hello World" -> "Hello", "World"
                 "Hamburger is delicious" -> "hamburger", "is", "delicious"  # segementation & transfer to lowercase
    
  - **Lemmatization**:
    
    Lemmatization is often used for **Text Minning**, **NLP** for better understanding and analysis of the text.
    
    **English**: 
                 
                 "did", "done", "doing", "does" -> "do"
                 "potatoes" -> "potato"                 
                 "cities" -> "city"                 
                 "children -> "child"
                 
  - **Stemming**:
    
    The word output after stemming may be meaningless.
    
    Stemming is often used for **Information Retrieval**.
    
    **English**:
                 
                 "hourse" -> "hors"
                 "writing" -> "write" / "writ"
    
