## NLP.project
Useing web api,NLP,wordcloud,LDA model,We analysed text data from post-purchase reviews of three different brands of water heaters, Haier, Midea and VanWard, but at the same price level, on the Jingdong e-commerce platform to extract valid information through text analysis and to discover consumers' individual needs for water heaters.
##  Operating environment

Python 3.7
## package
jieba
re
pandas
matplotlib.pyplot

## process

1. obtaining the raw data (text comment corpus) for analysis, part of which is crawled by itself.
##raw data
##Attention：when obtaining data api interface, cookie network authentication needs to log in first


2. carrying out basic processing operations on the acquired data, 
including data pre-processing, Chinese word separation, deactivation word filtering and other operations.
##Word cloud script useing csv file for word frequency analysis


##Attention：Every time you run out of 分词与去停用词.py script, remember to save the original file, the processed data will overwrite the original data

3. after the text comment data has been processed, multiple means are applied to analyse the comment data in various aspects.
##3.1Use the lda model to calculate the topic optimal solution
##Attention：Change the number of topics each time when useing lda.py



4. to obtain valuable content from the analysis of the corresponding results of the text comment data.
## note
The JD website is constantly changing, and the code may not always work properly.
If you find a bug, Welcome to Pull Request.
