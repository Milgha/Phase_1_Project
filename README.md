# Phase_1_Project
# Microsoft Studio

![](Images/README%20Header.png)

## Overview

Microsoft wants to make a big impression with their new film studio. Using data from internet movie databases, what recommendations can we make about their first project? 

## Business Understanding

Microsoft wants to make a big impression with their new film studio. The primary questions we wish to answer to provide a recommendation for their first project are:
•	What does a hit film look like? 
•	What kind of talent should we recommend?
•	What should the production budget be?

## Data Understanding

We took the data for our analysis from two sources: IMDb, and The Numbers. To provide a more relevant recommendation to the stakeholder Microsoft, we used films from the years of 2012 to 2018 that garnered more than 1000 ratings on IMDb.
Our analysis found that the most profitable genres are Animation, Adventure, Sci-Fi, Action, and Family. With these genres in mind, several talent picks would work well. For performers, Robert Downey Jr. and Bryce Dallas Howard are both well-known names that appear in consistently profitable films in the top genres. Some profitable directors that would work well in these genres are Colin Trevorrow and Francis Lawrence. For writer, Guillermo del Toro would be a great fit. 
We found a positive correlation between budget and profit, so a higher budget film would be best to maximize profit. Looking at the budget information for the 100 most profitable films, the median budget was $160 million, and median profit was $600 million dollars.  

![](Images/2022-08-26%2009_30_21-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

![](Images/2022-08-26%2009_32_02-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

![](Images/2022-08-26%2009_32_02-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

We found a positive correlation between budget and profit, so a higher budget film would be best to maximize profit. Looking at the budget information for the 100 most profitable films, the median budget was $160 million, and median profit was $600 million dollars.

![](Images/2022-08-26%2009_32_44-Microsoft_Film_Studio.pptx%20-%20PowerPoint.png)

## Conclusions

Animated movies are extremely profitable, but discussion with the stakeholder is needed to determine if opening an animation studio is feasible compared to a traditional film studio. We recommend Microsoft goes with consistently profitable star performers such as Robert Downey Jr. and Bryce Dallas Howard, proven adventure directors like Colin Trevorrow or Francis Lawrence, and a writer such as Guillermo del Toro. 
A big film franchise to emulate would be Jurassic World, or if animation is a feasible direction, The Incredibles. The stakeholder should expect to spend around 150 million dollars on their production budget to make a big hit.

## Future Consideration

In future, we can investigate the feasibility of making Animation movies and see how to compete with big names like Disney. Also, the possibility of partnership with other studios like Universal and Paramount can be investigated. Budget breakdown would be another thing to be analyzed to see how much needs to be spent on different aspects like casts, advertisement as well as hidden costs. 

```bash
+---Code
|   |   Master_Notebook.ipynb
|   \---.ipynb_checkpoints
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
+---.ipynb_checkpoints
|
|   .gitignore
|   Master_Notebook.ipynb
|   Microsoft_Film_Studio.pptx
|   README.md
```