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
  
  <img width="214" alt="image" src="https://github.com/user-attachments/assets/ea8be8fb-15bd-46af-beeb-927d503db202">


- **Sample by OTU Count Matrix:** `samplebyotu_countmatrix.csv`

  <img width="512" alt="image" src="https://github.com/user-attachments/assets/1d994855-4b91-4aee-8760-a31099babcc9">


- **Clinical Data:** `clinicalinfo_total.csv`

  <img width="303" alt="image" src="https://github.com/user-attachments/assets/bfdee048-7d78-4b14-b9d4-49fe2f3f9600">


### Step 3: Running the Model

Once you have the source code and input files, you can run the scripts in sequence starting from `Background_code.R` followed by `Data_preprocessing.R`, and finally `Processing.R` to get the results.


