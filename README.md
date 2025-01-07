
# Assignment 2

## Overview

This project contains Python scripts, data files, and resources used for APLT Assignment 2. The structure includes code for processing the training data and generating the linear model regression analysis between word duration and surprisal. 

## File Structure

### Folders
- **csv_files/**  
  This folder contains CSV data files used for analysis:
  - `data_1.csv`: First dataset for processing.
  - `data.csv`: Contains the word tokens, respective surprisal scores and word duration scores.

### Python Scripts
- **get_durations.py**  
  A script to get word duration.

- **get_histogram.py**  
  A script to generate a histogram of word duration and their frequencies in the data.

- **get_linear_model.py**  
  A script to generate the linear model regression analysis between word duration and surprisal. 

- **get_surprisals.py**  
  A script to calculate word-level surprisal values from the training data.

### Text Files
- **sentence1.txt to sentence10.txt**  
  Text files containing individual sentences used for the recoded data.

### Raw Files
- **wiki.test.raw**  
  Raw text data used for testing.

- **wiki.train_1147.raw, wiki.train_3356.raw, wiki.train_4000.raw**  
  Training data sets for the sentence composition and word surprisal calculations.

## How to Use

1. **Setup**  
   Ensure you have Python installed, along with required libraries (e.g., pandas, nmatplotlib, etc.).

2. **Run Scripts**  
   Use the scripts for specific tasks:
   - To generate histograms, run:
     ```bash
     python get_histogram.py
     ```
   - To calculate surprisal values, run:
     ```bash
     python get_surprisals.py
     ```


## Requirements
- Python 3.8 or higher
- Required libraries (install using `pip install -r requirements.txt` if applicable)

## Notes
- This project assumes the data is pre-processed before being used in the scripts.
- For large datasets, ensure your machine has sufficient memory and processing power.
