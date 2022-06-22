# MethylTrans
Repository for MethylTrans. a group of Multitask Transfer Learning models trained to identify 6mA and 5mC methylation sites in rice and maize

## Models and Data

All the novel datasets and models used in the paper are found [in this drive folder.](https://drive.google.com/drive/folders/1DPTNrTcVR8tPy86mzPBaunLlqY2RnJHa?usp=sharing) The folder contains the following subfolders:

- MethylULMFIT - Contains the methylation-pretrained Genomic ULMFiT model
- DNABERT - Contains the methylations-pretrained DNABERT model, as well as the finetuned DNABERT original and DNABERT pretrained models that was used for attention mapping and motif analysis.
- Datasets - Contains the following subfolders:
  - 5mC datasets - contains the Nip5mC and Maize5mC datasets that were used to evaluate the performance of the models.
  - visualizations - contains the datasets that were used to finetune the DNABERT original and DNABERT pretrained models for attention mapping and motif analysis, as well as the dataset that was used for attention mapping and motif analysis
