# Regarding reproducibility

The API I used refreshes data daily (e.x. daily prices), so it would be difficult to reproduce my results when requesting data from the API. To solve this, I exported the data on the day of my report submission and included an alternate version called MidtermReproducible which reads the csv files instead of requesting data from the API, so the study is 100% reproducible.

The code to request from the API is in both files (just commented out in the reproducible version). If you are looking at the code to mark, I suggest looking at the original MidtermPokemon.rmd file. If you want to run and get the exact same results, run the MidtermReproducible.rmd file.

# Regarding Feedback

I chose a dataset and research question that personally interested me. I was previously working with a finance dataset, but stopped working with it when I was half way through after raising concerns over serious violations of modelling assumptions (e.x. data dependent with each other). In my current data, I find some relationships between my response and key predictors, but I fail to find significant relationships. I also built some preliminary models outside of the report, which led to some poor results such as a low adjusted R^2. For my final project, I want to create an effective model that describes a strong relationship. As mentioned in my report, I am currently trying to find new variables to consider with my current dataset, but it is hard to find significant variables with the resources available to me. For the remainder of the project until the final, would you recommend that I switch to a separate dataset with a different research question, to try to find stronger relationships and develop a more effective model? Thank you!
