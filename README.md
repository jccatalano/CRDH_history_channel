## What’s on History?: Tuning into Conspiracies, Capitalism, and Masculinity 

This repository contains the code and data for Joshua Catalano and Briana Pocratsky's the article titled "What’s on History?: Tuning into Conspiracies, Capitalism, and Masculinity" published in the 2020 issue of Current Research in Digital History.

### Explanation of Files

#### corpus_creation.RmD
- This file contains the code used to create the corpus from the text_files folder and create the topic model visualizations.

#### text_files
- This folder contains plain text files of each unique episdode title and description that aired during the period of analysis. 

#### csv_2_text_script.Rmd
- This file was originally used to generate the .txt files from the show_description_unique.csv file. If running the code locally, it is unnecessary to to use this file so long as the text_files folders has been downloaded.

####frequency_counts.Rmd
- This file contians the code used to analyze and visualize the frequency with which programming aired using the frequency_data.csv file. 

####jockers_stop_words.txt
- This file contains a list of stopwords created by Matthew Jockers. It is used to help prune words from the corpus. 








