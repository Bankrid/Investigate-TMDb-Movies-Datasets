Investigate a TMDb Movies Datasets

INTRODUCTION 

This dataset contain information about 10,000 movies collected from The Movies Database (TMDb). I will explore it to find pattern and answer questions like does movies running time has similar distribution with revenue? which movies has the longest and the shortest running time? etc.

CONCLUSION

I performed descriptive analysis on the dataset and answered questions like 
   * Which Movies Genres generates the highest and the lowest revenue respectively? Highest revenue is from **Action** while lowest is from **TV Movies**
   * Does the movies runtime correspond to the budget? **Movies runtime does not correspond to budget**
   * Does the popularity directly imply revenue produced? **Populrity does not necessarily mean high revenue**
   * For Generes above average of budget and revenue, does budget determines the revenue ? **No it does not**
   * Does high budject genres imply high revenue? **Budegt and revenue has similar distribution**
   * Which genre is the most produced? Most produced genre is **Drama**


LIMITATION

* During the analysis, I was able to relate different features in the dataset such as revenue and budget, runtime and budget, popularity and genres etc, but I can't say affirmatively that one feature can be used to predict the other because the correlation relationship is not determine. 
* About 50% of the data has zero values for both revenue_adj and budget_adj. The zero values were omitted during the plot of histogram distribution that compares budget_adj and revenue_adj. So, the chart is not the representation of the whole dataset
* Production_companies can be insightful in determining the popularity and success of movies but I have to drop the column due to the large number of missing values