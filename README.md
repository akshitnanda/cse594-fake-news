# cse594-fake-news
Repository for Analysis of Fake News Classification Methods

You can clone this repository using `git clone https://github.com/akshitnanda/cse594-fake-news`

## Step 1
Verify that you have Python3 and Jupyter Notebook installed. (Install Python3 and Anaconda3 for Jupyter Notebook Access)

## Step 2
Please download and place the Google News Pre-Trained Vectors in the base folder.
'https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz'

## Step 3
Install the required dependencies with `pip install -r requirements.txt'

## Step 4
Verify that you have the `bin_dataset` and `liar_dataset` folders for ISOT and LIAR Dataset Inputs

## Code Execution
The following files are used for our experimental analysis : 

### Linear_ISOT_Dataset 
Contains the analysis of Linear Classifier Models with ISOT Dataset

### LSTM_ISOT_Dataset 
Contains the analysis of LSTM Classification with ISOT Dataset

### Linear_ISOT_Dataset_Reuters 
Contains the analysis of Linear Classifier Models with ISOT Dataset after removing the 'Reuters' keyword

### Linear_Binary_LIAR_Dataset 
Contains the analysis of Linear Classifier Models with LIAR Dataset adjusted for Binary Classification

### Multiclass_LIAR_Dataset
Contains the analysis of Linear Classifier Models with LIAR Dataset

### LSTM_Binary_Liar_Dataset 
Contains the analysis of LSTM Model with LIAR Dataset adjusted for Binary Classification

### LSTM_LIAR_Dataset 
Contains the analysis of LSTM Models with LIAR Dataset