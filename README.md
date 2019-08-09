#Text Summarization

Process and Tools-

1- Cleaning the text like converting text into lowercase,removing punctuation.

2- Removing stop words

3- Sentence vector: for this we use TFIDF technique

    TFIDF = Tf*IDF
    
    TF of a word in a sentence = no. of times that word appear in that sentence / Total no. of word
    
    IDF of a word in a setnece = ln(no. of sentences in whole text / no. of sentences where taht word appaers)
    
4- Apply text rank algorithm

for more information- https://medium.com/@shivangisareen/summarise-text-with-tfidf-in-python-bc7ca10d3284
