# Star Wars Scripts with Statistical Text Analysis
## 1. Introduction
In this project, we perform a statistical text analysis on the Star Wars scripts from The Original Trilogy Episodes (IV, V, and VI). The analysis includes generating word clouds to visualize the most frequent words in each episode. This project is a tribute to Star Wars Day, celebrated on May 4th.

## 2. Loading Data
### Libraries Used
RWeka, tidyverse, tm, wordcloud, wordcloud2, tidytext, reshape2, radarchart, knitr
### Reading Data
We load the scripts for each episode:
      Episode IV: SW_EpisodeIV.txt
      Episode V: SW_EpisodeV.txt
      Episode VI: SW_EpisodeVI.txt
We also read sentiment lexicons for analysis:
      Bing lexicon
      NRC lexicon
      Afinn lexicon
## 3. Functions
### Cleaning and Preprocessing Functions
      cleanCorpus: Cleans the text by removing punctuation, excess whitespace, stopwords, and numbers.
      frequentTerms: Generates a term-document matrix and identifies the most frequent terms.
      frequentBigrams: Extracts and visualizes the most frequent bigrams (pairs of words).
## 4. Episode IV: A New Hope
      Total dialogues: 1010
      Characters: 60
    Visualizations
      Bar chart: Top 20 characters with the most dialogues
      Wordcloud: Most frequent words
      Bar chart: Most frequent bigrams
## 5. Episode V: The Empire Strikes Back
      Total dialogues: 839
      Characters: 49
    Visualizations
      Bar chart: Top 20 characters with the most dialogues
      Wordcloud: Most frequent words
      Bar chart: Most frequent bigrams
## 6. Episode VI: Return of the Jedi
      Total dialogues: 674
      Characters: 53
    Visualizations
      Bar chart: Top 20 characters with the most dialogues
      Wordcloud: Most frequent words
      Bar chart: Most frequent bigrams
## 7. The Original Trilogy
    Combined Analysis
    Combined dialogues from all three episodes (2523 dialogues)
      Total characters across trilogy: 129
    Visualizations
      Bar chart: Top 20 characters with the most dialogues
      Wordcloud: Most frequent words
      Bar chart: Most frequent bigrams
## 8. Sentiment Analysis
    Using Lexicons
    Bing and NRC lexicons used for sentiment analysis
      Visualization: Comparison cloud for positive and negative words
      Visualization: Sentiment frequencies across all dialogues
      Visualization: Sentiment analysis by character
    Tidy Data Approach
    Most frequent words for each character using tf-idf analysis
## 9. Summary
Comprehensive statistical text analysis of Star Wars scripts from The Original Trilogy.
Insights include frequent words, bigrams, sentiment analysis, and character-specific analysis.
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/065ffef8-d805-4c8d-a30b-cfa95c5d13f8" alt="Image 1" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/e98128d0-13e8-4ac1-974f-98d35a285890" alt="Image 2" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/42de6256-7b48-48bf-8e9f-ea600d17e7a2" alt="Image 3" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/19563103-03e4-4da3-9e33-18151169adaf" alt="Image 4" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/ec79383a-e638-4cc9-9d95-a64c25d24502" alt="Image 5" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/d9dbad0c-2589-4c65-a58a-614bd29232f9" alt="Image 6" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/a8531fa1-e398-4c94-8b36-57592579079a" alt="Image 7" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/4c8c5bd3-c5b4-4c71-ace7-256eb9051be6" alt="Image 8" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/31d38c89-be16-473e-a164-04db7c0edf64" alt="Image 9" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/e7752115-e967-411c-a087-0313f13393d1" alt="Image 10" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/47f74062-4940-42d8-94fd-ac1364c67257" alt="Image 9" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/0feb7e2f-3ddf-4a80-82bf-7b439f4ffe57" alt="Image 10" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/a0bf60a1-cc8e-4b94-a694-0fb995739505" alt="Image 9" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/88cebcdb-915e-4e69-8fba-843016052998" alt="Image 10" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/5f71b54a-dd0f-4859-98ab-1d43efd2b579" alt="Image 9" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/abb3df23-c4ee-49d4-9664-cf7c918cfe52" alt="Image 10" style="width: 45%;">
</div>
<div style="display: flex;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/9ae453ef-a535-41f2-8e49-9274ff6f3641" alt="Image 9" style="width: 45%;">
    <img src="https://github.com/JuhiPathak23/Star-Wars-Scripts-Analysis/assets/73741643/ffbf498e-506f-4256-be42-c4321fab0a93" alt="Image 10" style="width: 45%;">
</div>

## 10. References
References to R packages used for text mining and visualization.
