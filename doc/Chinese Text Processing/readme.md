## Text processing in Chinese text with 3 popular mudules: **jieba**, **pkuseg**, and **THULAC**.
For more details on the three Text Processing Modules, please refer to the link below:
  - [jieba](https://github.com/fxsjy/jieba): 
    * Support three types of segmentation mode:

      1. Accurate Mode attempts to cut the sentence into the most accurate segmentations, which is suitable for text analysis.
      2. Full Mode gets all the possible words from the sentence. Fast but not accurate.
      3. Search Engine Mode, based on the Accurate Mode, attempts to cut long words into several short words, which can raise the recall rate. Suitable for search engines.

    * Supports Traditional Chinese
    * Supports customized dictionaries
    * MIT License
  - [pkuseg](https://github.com/lancopku/pkuseg-python): https://github.com/lancopku/pkuseg-python
  - [THULAC](https://github.com/thunlp/THULAC-Python): https://github.com/thunlp/THULAC-Python


## [Stop words list](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/tree/master/doc/Chinese%20Text%20Processing/stop%20words)
  - [cn_stopwords](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Chinese%20Text%20Processing/stop%20words/cn_stopwords.txt): contains common punctuation marks, numbers, stop words.
  - [hit_stopwords](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Chinese%20Text%20Processing/stop%20words/hit_stopwords.txt): contains more complicated punctuation marks, stop words.
  - [scu_stopwords](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Chinese%20Text%20Processing/stop%20words/scu_stopwords.txt): contains chinese words only, also focusing on colloquialism and idiom.
  - [baidu_stopwords](https://github.com/Junyan-Guo/NLP-Deep-Learning-Demo/blob/master/doc/Chinese%20Text%20Processing/stop%20words/baidu_stopwords.txt): both English and Chinese stop words are contained, simple punctuation marks
