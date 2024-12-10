# TSLAmy

TSLAmy: a novel amyloid hexapeptide aggregation prediction approach based on two-stage learning


● Description of the document

 -- The code folder contains the model code and datasets.
 
 -- The predictions folder contains predictions of aggregation for all hexapeptides except the modeled dataset.
 | Filename   | Content |
| :----- | :--- |
| 1_stage_one_train_physicochemical_feature_extraction.ipynb   | Training feature extraction module   |
| 2_stage_one_extracte_physicochemical_features.ipynb   | Generate result of the physicochemical feature extraction   |
| 3_stage_one_extracte_ESM_features.ipynb   | Extracting ESM-2 sequence features   |
| 4_stage_two_aggregation prediction.ipynb   | Train the two features extracted from stage one to obtain a predictive classification model   |


● Environment

 -- python=3.10
 
 -- pytorch=2.3.0
 
 -- tensorflow=2.15.0
