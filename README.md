# w266_project_topmusichits


Final project for Berkeley MIDS class w266 where we utilized a Spotify dataset and analyzed various songs' lyrics and their music metadata from the 2000s to now and predicted whether the song would be a top hit on the Billboard Weekly Hot 100 charts. Group members include Sumedh Shah, Kanika Mahajan, and Natali Ojeda Meneses.


## Abstract
Music evolves over time and identifying features that make a song popular is challenging. However, the music industry can immensely benefit by incorporating specific features like certain lyric phrases and musical attributes to produce more hit songs that will make the Billboard charts. This project explores feeding in chunks of song lyrics and its music metadata into a fine-tuned BERT model to identify hit songs and hones in on the importance of lyrics compared to the song’s metadata. Compared with traditional classification models like Naive Bayes and Logistic Regression, BERT achieves higher performance in classifying hits. Training BERT consistently with newer songs would make it possible to understand the ever evolving direction of music and seems like a promising approach to produce more hit songs.

# Project Organization

    ├── LICENSE
    ├── README.md          <- The top-level README describing the project aims
    ├── data
    │   ├── raw            <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   └── processed      <- The final, canonical data sets for modeling.
    ├── notebooks          <- .ipynb notebooks. 
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    └── src                <- Source code for use in this project.
        └── data           <- Scripts to download or generate data


Repository structured based on [cookiecutter data science](https://drivendata.github.io/cookiecutter-data-science).
