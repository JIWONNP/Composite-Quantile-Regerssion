# Composite Quantile Regression Approach to Batch Effect Correction in Microbiome Data

## Model Introduction

<img width="452" alt="image" src="https://github.com/user-attachments/assets/b0b2bbd4-f8c1-4e0d-a296-82872ccf29c6">

The proposed model employs an approach that combines the negative binomial regression model with the composite quantile regression method to correct for batch effects.

It is written in the R programming language.


### Step 1: Source Code Download

To get started with the model, you'll first need to download the necessary R scripts. These are packaged together in a ZIP file named `R_code.zip`.

#### Included Scripts
- `Background_code.R`: Establishes the required background setup and loads necessary libraries.
- `Data_preprocessing.R`: Handles preprocessing of your input data.
- `Processing.R`: Contains the core functionality to run the model and process the data.

You can download the ZIP file from the following link:
[Download R_code.zip](URL-to-download-R_code.zip)

### Step 2: Input Files

You'll need to prepare and provide specific input files in CSV format to use with the model:
- **Count Matrix with Covariates:** `count_matrix_covar.csv`
  
  <img width="176" alt="image" src="https://github.com/user-attachments/assets/c54edccc-569b-461b-adf6-9783a6e529a1">

- **Sample by OTU Count Matrix:** `samplebyotu_countmatrix.csv`

  <img width="338" alt="image" src="https://github.com/user-attachments/assets/ba49b517-8f37-47be-9663-5a976291a6ed">

- **Clinical Data:** `clinicalinfo_total.csv`

  <img width="338" alt="image" src="https://github.com/user-attachments/assets/3c66921c-1a98-4720-9ceb-36c9810daac9">


### Step 3: Running the Model

Once you have the source code and input files, you can run the scripts in sequence starting from `Background_code.R` followed by `Data_preprocessing.R`, and finally `Processing.R` to get the results.


