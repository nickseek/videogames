# videogames


This repo aims to gain some insight into video games sales - choice of publisher and genre in particular.

In this repository, analysis is based on the data provided here: https://www.kaggle.com/datasets/gregorut/videogamesales. 

This is a dataset that contains a list of video games with sales greater than 100,000 copies. It was generated by a scrape of vgchartz.com.

### The data is utilized to answer 3 questions:

    1. Which Genres and publishers sell best?
    2. What is the top selling publisher per genre?
    3. What is the reason for the low correlation between Japan and Global sales?

### The following libraries are needed to run the code:

    Pandas
    Numpy
    Matplotlib
    seaborn

## Contents of the repository:

1. Data files: 
    
    1.1. 'vgsales.csv' (original file)  
    
    1.2 'vgsales_p.csv' (processed file).
2. Jupyiter notebook files:

    2.1 - data_exploration notebook, generally exploring the data: which columns are in the file, % of nan values, amount of unique values, correlation matrix, top frequency values and some basic plots.
    
    2.2. - data_preparation notebook, processing the data (handling NaNs)

    2.3 - business_question notebook, answering the questions presented above



## Analysis findings

Best selling genre: Action (20% of sales).
Best selling publisher: Nintendo (also 20% of sales).

However Nintendo's best selling genre is Platform (24%), and the best selling publisher in action genre is Take-Two Interactive.

Checking top publisher per genre we can see that while Nintendo is the top seller in most of the genres, it does not rule the top three selling genres: Action, Sports and Shooter.

Looking into why there is a low correlation between Japan and Global sales, we find that the Japanese market is dominated by the Role-Playing genre, which takes up 25% of all Japan game sales. 

Similarly, Nintendo holds 35% of the Japanese games market, much ahead of all remaining publishers there. 

This is unlike global sales which have more than one strong player and where Nintendo is also the strognest publisher, but only takes 20% of the market.