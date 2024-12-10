# TSLAmy

**TSLAmy: a novel amyloid hexapeptide aggregation prediction approach based on two-stage learning**

In this study, we proposed a computational model, TSLAmy, to predict amyloid hexapeptides using a two- stage learning framework. 
1) In the first stage, we extracted physicochemical features and sequence features of hexapeptides . 
2) In the second stage, these features were used as inputs to predict the aggregation potential of hexapeptides. 
3) We predicted the aggregation potential of all 64,000,000 possible hexapeptides and conducted a detailed analysis of the results. 

● **Description of the document**

 -- The code folder contains the model code and datasets.
 
 -- The predictions folder contains predictions of aggregation for all hexapeptides except the modeled dataset.
 | Filename   | Content |
| :----- | :--- |
| 1_stage_one_train_physicochemical_feature_extraction.ipynb   | Training feature extraction module   |
| 2_stage_one_extracte_physicochemical_features.ipynb   | Generate result of the physicochemical feature extraction   |
| 3_stage_one_extracte_ESM_features.ipynb   | Extracting ESM-2 sequence features   |
| 4_stage_two_aggregation prediction.ipynb   | Train the two features extracted from stage one to obtain a predictive classification model   |


● **Environment**

 -- python=3.10
 
 -- pytorch=2.3.0
 
 -- tensorflow=2.15.0
