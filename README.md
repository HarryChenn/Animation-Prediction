# Animation-Prediction-Model

- [Research Question](#Research Question)
- [Data filtering/Cleaning](#Data filtering/Cleaning)
- [Topic Modeling Result Interpretation](#Topic Modeling Result Interpretation)
- [Web Scrapper](#Web Scrapper)

    
## Research Question
Our main objective is to identify the factors that contribute to the difference in the popularity of different animations. Popularity is a perfect indicator to measure an anime's success. There are multiple factors that affect anime's popularity. The production studio, the genre, and previously published reviews, for instance, could all have an effect. 

## Data filtering/Cleaning
As we are not creating a original dataset initially, the existing dataset has already been preprocessed, cleaned, and organized. The dataset, created by Marlesson Santana from Kaggle.com, was categorized into three files including the files of the review, profile, and anime. As shown above, the anime.csv contains lists including uid(user ID), titles, correspond synopsis, genre, aired(first broadcast period), episodes, members, popularity(popularity ranking), score, and finally ranked(a ranking according to score). As a result, there is no method needed to clean the data.

By running the code in Topic Modeling, we will get a list of word topics

## Topic Modeling Result Interpretation
As for the previous lists of topic word choices shown, words like "young", "trying", "gain", and "game"are shown to be related to Shonen manga, which is a Japanese manga category with an target audience of adolescent boys.
Next, to determine whether there is a correlation between the choice of topic and the popularity of an anime, we will then use the same method to extract the keyword topics for the remaining two popularity groups and compare their results.
Furthermore, we will continue explore the factors that may have an imnpact on the success of an animation. Following the collection of the trends for the animations, we will web-scraping additional variables. By combining metadata, we hope to investigate whether popular anime production studio are generally well-liked for all of their animations, whether anime with a school setting receives more airtime, or whether action movies in general might get better reviews, by combining metadata.

## Web Scrapper
By running the code in Web Scrapper, we can get the associated production studio based on the given popularity group. Then we can find the pattern of animation's popularity with its production studio

