Applying clustering and classification for authorship attributtion on Brazilian corpus

Author: Gabriel Albernaz

## Project Overview
This project replicates and extends the authorship attribution analysis of the Federalist Papers conducted by Jockers and Witten (2010). 
Using machine learning techniques, including clustering and classification algorithms, the study aims to confirm the authorship of known 
papers and generate evidence to predict the authorship of the disputed and co-authored papers. The analysis utilizes pre-processed 1-gram 
and bi-gram proportional counts of words from the Federalist Papers to identify stylistic patterns indicative of individual authors. 
Ultimately, this project seeks to contribute to the ongoing scholarly debate surrounding the authorship of these historically significant 
documents 

## Project Log
04/27 - G.A - Acquired new corpus, scrubbed it on Lexos, uploaded the original file to new GitHub repo, began first commits
04/30 - G.A - Processed corpus on Lexos, altered introdution section, read new files

## Requirements
- Python 3.x
- Jupyter Notebook

Required Python libraries:
- pandas
-numpy
-matplotlib
-seaborn
-scikit-learn

## Installation  
1. Clone the repository:  
   git clone <repository-url>

2. Navigate to the project directory:  
   cd federalist-authorship

3. Install the required dependencies:  
   pip install -r requirements.txt

## Usage  
1. Open the Jupyter notebook:  
   jupyter notebook

2. Run Albernaz_Gabriel_P#5.ipynb  

3. Follow the code and markdown cells in order to see:  
   - Data preparation  
   - Clustering results (K-Means & Hierarchical)  
   - Classification models (Decision Tree, SVM, Naive Bayes)  
   - Predictions for disputed papers  
   - Performance comparisons