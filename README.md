# MVP: predicting pathogenicity of missense variants by deep learning

This repository contains codes to train MVP model and predict missense variants pathogenicity. 


# code and tutorials: 
code/1_prepare_files_for_MVP.ipynb: Generate missense variants features for training and prediction for MVP models.

code/2_train_MVP_models.ipynb: Train MVP models with selected positives and negatives missense variants.

code/3_MVP_prediction.ipynb: Generate MVP raw scores for input variants. 

code/4_get_MVP_prediction_for_all_missense_variants.ipynb: Generate MVP raw scores for all rare missense variants, convert raw score to rank percentile scores.

code/models.py: functions used in MVP model.

# Precomputed MVP score (hg19)
The scores can be accessed through https://figshare.com/articles/dataset/Predicting_pathogenicity_of_missense_variants_by_deep_learning/13204118 or https://www.dropbox.com/s/d9we7gx42b7yatg/MVP_score_hg19.txt.bz2?dl=0.

# citation
Qi H *, Zhang H *, Zhao Y *, Chen C *, Long JJ, Chung WK, Guan Y, Shen Y. MVP predicts the pathogenicity of missense variants by deep learning. Nat Commun 12, 510 (2021). https://doi.org/10.1038/s41467-020-20847-0
