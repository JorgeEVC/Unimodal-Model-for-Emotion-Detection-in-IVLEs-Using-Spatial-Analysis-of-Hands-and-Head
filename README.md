# Unimodal-Model-for-Emotion-Detection-in-IVLEs-Using-Spatial-Analysis-of-Hands-and-Head
## ID: 10344

## Authors

- **Jorge Enrique Velázquez Cano**  
  Tecnológico Nacional de México campus CENIDET

- **Gabriel González Serna**  
  Tecnológico Nacional de México campus CENIDET

- **Leonor Rivera Rivera**  
  Instituto Nacional de Salud Pública

- **Nimrod González Franco**  
  Tecnológico Nacional de México campus CENIDET

- **Máximo López Sánchez**  
  Tecnológico Nacional de México campus CENIDET

- **José Reyez Ortiz**  
  Universidad Autónoma Metropolitana

## Overview
This repository contains the files needed to replicate the results presented in the paper *Unimodal Model for Emotion Detection in Immersive Virtual Environments Using Spatial Analysis of Hands and Head*

## Data Files

The `.xlsx` files contain the records of the variables used for each of the approaches described in the paper. The naming convention indicates the location where the experiments were conducted, followed by the central tendency measure used. The term *redux* indicates that the files do not include more variables than those required for the specific approach. Finally, the name includes the dimension to be predicted.

**Example:**  
The variable `L_ky` in the files `Tejalpa_redux_Act` and `Tejalpa_redux_Val` records the same mean values for this variable, obtained from the scenes and each participant (i.e., 8 scenes × 58 participants, resulting in a total of 646 records).

---

## Jupyter Notebook Files

A notebook is provided for each approach (i.e., central tendency measure):

- `IEEE_Medianas.ipynb` for Median  
- `IEEE_Medias.ipynb` for Mean  

## File Execution

The notebooks can be opened and executed in Google Colab. They include the necessary steps and installations required to reproduce the results presented in the paper.

## Reproducibility

To reproduce the results:

1. Upload the datasets to Google Drive (`My Drive/Datos V2`)
2. Open the notebooks in Google Colab
3. Run all cells in order

Make sure dependencies are installed as indicated in each notebook.

---

## Hyperparameter Tuning

Each notebook includes a hyperparameter optimization section, where the process using GridSearch and Optuna is demonstrated. This section also allows further exploration in search of improved solutions.
> ⚠️ Note: Hyperparameter tuning sections are optional and may increase execution time significantly.

However, these blocks can be skipped, as an additional section is provided to generate the models using the best hyperparameters found.
