# Text classification model with NLP and ScikitLearn on song lyrics from [lyrics.com](lyrics.com)
***Natural language processing (NLP)***


## Table of Contents
- [General info](#general-info)
- [Technologies and Libraries](#technologies-and-libraries)
- [Setup](#setup)


### General info
This project is about a text classification model for song lyrics from [lyrics.com] for two artists:
- Web Scraping
- Regular Expressions
- Parsing HTML
- Bag of Words

### Technologies and Libraries
- Python 3.8
- requests
- re
- BeautifulSoup
- pandas
- ScikitLearn
    - CountVectorizer
    - TfidfVectorizer
    - make_pipeline
    - GridSearchCV
    - LogisticRegression
- seaborn
- matplotlib

### Setup
Using **Anaconda** is recommended for quick lunch.
To make this project user friendly, I've combined each method in [execution.py](https://github.com/memredikici/song_lyrics_classification/blob/master/execution.py).
1.  To run the program, you need to `cd` into the folder that contains the files.
    ```
    $ cd ../song_lyrics_classification
    ```
2. Enter on terminal `python execution.py <first Artist> <second Artist> ` 
    - You can use `python execution.py beyonce coldplay` to make a prediction through trained model.
        ```
        $ python execution.py beyonce coldplay
        ```
3. Follow instructions.
4. Enter a word or phrase to see the probability to which artist the entry might belong.
    ```
    please enter something to be predicted: love
        beyonce  coldplay
    love  0.958847  0.041153
    ```

