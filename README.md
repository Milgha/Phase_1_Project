# Phase_1_Project
# Microsoft Studio

![](Images/README%20Header.png)

## Overview

Microsoft wants to make a big impression with their new film studio. Using data from internet movie databases, what recommendations can we provide to make their first project a financial success?

## Business Understanding

The primary questions we wish to answer to provide a recommendation are:

•	What does a hit film look like? 

•	What kind of talent would work best in that film?

•	What should the production budget be?

## Data Understanding

We took the data for our analysis from two sources: IMDb, and The Numbers. Both are extensive sources with many data entries on metrics we wish to include such as production budget and film metadata. To provide a more relevant recommendation to the stakeholder Microsoft, we used films from the years of 2012 to 2018 that garnered more than 1000 ratings on IMDb.

Our analysis found that the most profitable genres are Animation, Adventure, Sci-Fi, Action, and Family. With these genres in mind, we can draw out a potential team from a list of consistently profitable talent. For performers, Robert Downey Jr. and Bryce Dallas Howard are both well-known names that appear in profitable films in the top genres. Some strong directors that would work well in these genres are Colin Trevorrow and Francis Lawrence. For writer, Guillermo del Toro would be a great fit with his broad experience in the top genres. 

![](Images/2022-08-26%2009_30_21-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

![](Images/2022-08-26%2009_32_02-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

![](Images/genreplot.png)

We found a positive correlation between budget and profit, so a higher budget film would be best to maximize profit. Looking at the budget information for the 100 most profitable films, the median budget was $160 million, and median profit was $600 million dollars.

![](Images/2022-08-26%2009_32_44-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

## Conclusions

Animated movies are extremely profitable, but discussion with the stakeholder is needed to determine if opening an animation studio is feasible compared to a traditional film studio. We recommend Microsoft goes with consistently profitable star performers such as Robert Downey Jr. and Bryce Dallas Howard, proven adventure directors like Colin Trevorrow or Francis Lawrence, and a writer such as Guillermo del Toro with broad experience in our chosen genres.

A big film franchise to emulate would be Jurassic World or, if animation is a feasible direction, The Incredibles. The stakeholder should expect to spend around 150 million dollars on their production budget to make a big hit.

## Future Consideration

In future, we can investigate the feasibility of making Animation movies and see how to compete with big names like Disney. Also, the possibility of partnership with other studios like Universal and Paramount can be investigated. Budget breakdown would be another thing to be analyzed to see how much needs to be spent on different aspects like casts, advertisement as well as hidden costs. 

```bash
+---Code
|   |   Master_Notebook.ipynb
|
+---Data
|   |   bom.movie_gross.csv.gz
|   |   im.db.zip
|   |   rt.movie_info.tsv.gz
|   |   rt.reviews.tsv.gz
|   |   tmdb.movies.csv.gz
|   |   tn.movie_budgets.csv.gz
|   |
|   \---im.db
|           im.db
|
+---Images
|
|   .gitignore
|   Master_Notebook.pdf
|   Github_repo.pdf
|   Master_Notebook.ipynb
|   Microsoft_Film_Studio.pdf
|   README.md
```