# Digital Futures Capstone Project
# Video Game Recommendation System
 
## Contributors
[Liam Dearlove](https://github.com/ldearlove) |

## Overview
This repository contains the code and documentation for a video game recommendation system developed as a part of the Digital Futures Capstone Project. This project
demonstrates the skills and knowledge acquired from 12 weeks training with Digital Futures. These skills include Python, pandas, data visualisation and machine learning
models.

The video game recommendation system leverages data from Steam, including user playtime and game details such as genre. It employs hybrid filtering (a mixuture of content-based and collaborative filtering) to analyse the data and generate personalised game recommendations for users.

## Contents
This repository contains:
* `Video_game_recommendation.ipynb`: The main notebook containing the final implementation of the recommendation system.
* `Initial_Research.ipynb`(formerly `Rough_work.ipynb`): A notebook containing initial research and analysis along with all rough work done during the project.

## Dataset
The dataset for this project is obtained by web scraping and using the Steam API to gather information about users and their owned games. The primary data points include:
* Steam user IDs
* Game IDs
* Game names
* Game genres
* Playtime for each game for each user

## Methodology

The project involves several key steps:

1. Data Collection: Using XML web scraping and the Steam API to gather data.
2. Data Preprocessing: Cleaning and organizing the data for analysis.
3. Modeling: Employing hybrid-based filtering, which combines content-based filtering and collaborative filtering to build the recommendation model.
4. Evaluation: Assessing the model's performance and fine-tuning as necessary.

## Exploratory Data Analysis (EDA)

The notebook includes Exploratory Data Analysis (EDA) and data visualizations to provide insights into the dataset. Various graphs and plots are used to highlight key trends and patterns in the data.

## Usage

1. Open the `Video_game_recommendation.ipynb` notebook in Jupyter Lab.
2. Ensure you replace the placeholder `ENTER_YOUR_STEAM_API_KEY_HERE` in the notebook (found in code cell 4) with your actual Steam API key.
3. Run the cells sequentially to execute the code and generate game recommendations.

## Acknowledgements

Special thanks to Digital Futures for the training and support throughout this project.