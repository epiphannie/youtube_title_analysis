This project uses the dataset "Trending Youtube Video Statistics" from Kaggle. Youtube does not curate the dataset but is responsible for determining what is 'trending' based on a proprietary algorithm. The dataset contains a snapshot of the top trending videos from each day, ranging from December 1, 2017 to May 31, 2018.

The original goal of the project was to determine the most popular sentence structure of top trending Youtube videos. However, as you will see, the structure of video titles does not lend itself to a grammatical approach. Instead, this project focuses on the most common sequences of parts of speech in title segments and also reveals a few fun facts about the dataset.

The project itself is housed in a Jupyter notebook (youtube_titles_experiment.ipynb), but can be downloaded in other formats as well.

To run the project locally, you will need to download the two csv files also included in the repo:
* USvideos.csv
* parts_of_speech.csv

Be advised, step 31 takes a little time to run (60 seconds?). Lots of crunching happening!
There is also an intentionally triggered testing error in cell 15.
