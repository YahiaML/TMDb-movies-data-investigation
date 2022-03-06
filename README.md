This data was cleaned from original data on Kaggle: https://www.kaggle.com/tmdb/tmdb-movie-metadata.

## Dataset Description
**TMDb movie data** is a dataset containing 21 columns for 10866 Movies,

which are :



```
[id', 'imdb_id', 'popularity', 'budget', 'revenue', 'original_title',
       'cast', 'homepage', 'director', 'tagline', 'keywords', 'overview',
       'runtime', 'genres', 'production_companies', 'release_date',
       'vote_count', 'vote_average', 'release_year', 'budget_adj',
       'revenue_adj]
```

***These columns can be classified as the following :***

**1.** Significant columns for this analysis :
```
['popularity', 'budget', 'revenue', 'genres', 'vote_average' ]
```

**2.** Helpful columns for this analysis :
```
['original_title', 'cast','director','runtime', 'production_companies', 'release_date',
        'vote_count', 'release_year', 'budget_adj','revenue_adj]
```
**3.** Columns have nothing to provide us for this analysis: 

```
["id", 	"imdb_id", 	"homepage", "tagline", "keywords",	"overview"]
```

##Question(s) for Analysis

1. Which genres are most popular from year to year?
2. Are the high revenue related to the high popularity?
3. Which properties affects the movie vote average?
4. Which stars have the highest vote average movies?
5. Which directors have the highest vote average movies?
