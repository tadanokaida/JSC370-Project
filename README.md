# Regarding reproducibility

The API I used refreshes data daily (e.x. daily prices), so it would be difficult to reproduce my results when requesting data from the API. To solve this, I exported the data on the day of my report submission and included an alternate version called MidtermReproducible which reads the csv files instead of requesting data from the API, so the study is 100% reproducible.

The code to request from the API is in both files (just commented out in the reproducible version). If you are looking at the code to mark, I suggest looking at the original MidtermPokemon.rmd file. If you want to run and get the exact same results, run the MidtermReproducible.rmd file.
