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

## Files
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

---

## Hyperparameter Tuning

Each notebook includes a hyperparameter optimization section, where the process using GridSearch and Optuna is demonstrated. This section also allows further exploration in search of improved solutions.

However, these blocks can be skipped, as an additional section is provided to generate the models using the best hyperparameters found.

It is important to note that the notebooks expect the datasets to be located in Google Drive, inside a folder named `Datos V2` within `My Drive`.  
This can be modified to other locations by adjusting the lines where the datasets are loaded.
