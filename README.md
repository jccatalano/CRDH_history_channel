## What’s on History?: Tuning into Conspiracies, Capitalism, and Masculinity 

This repository contains the code and data for Joshua Catalano and Briana Pocratsky's article titled "What’s on History?: Tuning into Conspiracies, Capitalism, and Masculinity" published in the 2020 issue of Current Research in Digital History.

### Explanation of Files

#### corpus_creation.Rmd
- This file contains the code used to create the corpus from the text_files folder and create the topic model visualizations.

#### text_files
- This folder contains plain text files of each unique episdode title and description that aired during the period of analysis. 

#### csv_2_text_script.Rmd
- This file was originally used to generate the .txt files from the show_description_unique.csv file. If running the code locally, it is unnecessary to to use this file so long as the text_files folders has been downloaded.

#### frequency_counts.Rmd
- This file contians the code used to analyze and visualize the frequency with which programming aired using the frequency_data.csv file. 

#### jockers_stop_words.txt
- This file contains a list of stopwords created by Matthew Jockers. It is used to help prune words from the corpus. 

### How to Run the Code Locally

1. Dowload the files.
2. Update the file paths contained in corpus_creation.Rmd and frequency_counts.Rmd to corespond to the location where you downloaded the files. In particular, you will need to provide the path to the text_files folder in order to generate the corpus.
3. Use the code provided in corpus_creation.Rmd to generate topic models.
4. Use the code provided in frequency_counts.Rmd to plot word frequency. 






