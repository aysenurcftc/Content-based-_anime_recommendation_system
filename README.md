# Content based anime recommendation system :v:

A content-based anime recommendation system uses cosine similarity to recommend animes. Built systems use only genres and synopsis(summary) for a recommendation.

![resim](https://w0.peakpx.com/wallpaper/191/702/HD-wallpaper-izuku-midoriya-cool-my-hero-academia.jpg)

## DATASET

This dataset is taken from ::point_right: https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020

Dataset contains 16206 animes

#### anime_with_synopsis.csv
1) MAL_ID	
2) Name
3) Score	
4) Genres
5) sypnopsis

### Content based recommendation

This type of recommendation system takes in an anime for instance that a user currently likes as input.  Then it analyzes the contents of the anime to find other animes that have similar content. Then it recommends the most relevant animes according to their ranks.

![resim2](https://github.com/NurFortuna/Content-based-_anime_recommendation_system/blob/main/content-base.png)

### Cosine Similarity

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.The smaller the angle, higher the cosine similarity. [1]

We use cosine similarity between these vectors to find out how similar they are. We can calculate this using ``` cosine_similarity() ``` function from sklearn.metrics.pairwise library.

![resim](https://cs.carleton.edu/cs_comps/0910/netflixprize/final_results/knn/img/knn/cos.png)
