
# Recommendation System (Content Based)

In this python project, I am trying to build a movie recommendation system based on *user interactions*. For example, 
- previously watched movies,
- user search query

I will use movie data csv from url https://query.data.world/s/uikepcpffyo2nhig52xxeevdialfl7

I followed following steps to implement this project.
1. Load data from above url.
2. Selected relevant columns from the dataset
3. Prepared text content as suitable for applying filtering algorithms
4. Extracted *Keywords* for each record
5. Created a *Bag of words*
6. Dropped all other irrelevant columns.
7. Generate *CountVectorizer()*
8. Generate *Cosine Similarity Matrix*
9. Implemented *recommender* function


Finally, I filter top 10 movie suggestions based on a *user search query*. (*i.e. movie title*)


## Installation

I have used [*rake_nltk*](https://csurfer.github.io/rake-nltk/_build/html/index.html) for this project.

```bash
  !pip install rake_nltk
```
    
## 🏆 Lessons Learned

1. Cosine Similarity
2. Document Term Frequency
3. Bag of Words
4. Basic text pre-processing for NLP
5. Basic usage of *rake_nltk* and *Rake()* class
6. *CountVectorizer()* to convert *Bag of words* to numeric data


![Logo](https://github.com/tharangachaminda/content_based_recommender_system/blob/main/netflix_recommender.jpg)
