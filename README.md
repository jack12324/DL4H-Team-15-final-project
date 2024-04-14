# DL4H-Team-15-final-project

To properly run this notebook follow these steps from the google collab environment:
 1. Obtain access to the MIMIC-III dataset here: https://physionet.org/content/mimiciii/1.4/
 2. Download the preproccessed output of MIMIC_Extract here: https://github.com/MLforHealth/MIMIC_Extract (or run the pipeline yourself)
 3. Add the following folder to your google drive: Colab Notebooks/Data/
 4. Add the embedding-models folder from this repo (and it's contents) to the folder from 3. (so Colab Notebooks/Data/embedding-models/)
 5. Upload the PATIENTS.csv (from MIMIC) NOTEEVENTS.csv (from  MIMIC) and all_hourly_data.h5 (from MIMIC Extract) to the data folder from step 3
 6. Run Notebook up to Data Pre-processessing to set up folders and install dependencies
 7. Read the Data Pre-Processing section of the notebook and edit the PRE_PROCESS and DEMO variables for your needs (PRE_PROCCESS will need to be set to True on the initial run of the notebook. DEMO decides if the processing occurs on the entire dataset or just a subset to demonstrate processing works.)
