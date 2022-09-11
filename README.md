# Meta_Learning
How to run codes for Meta_Learning Research Paper:

•	Pre-Trained_Model.ipynb file: it contains the code used for training and evaluating different pre-trained model for different plant disease classification tasks and the accuracies obtained are stored in the accuracy table manually.

•	Probe_Network.ipynb file: it contains the code used for training probe network on disease classification tasks for extracting vectors corresponding to the datasets. These vectors are then stored for replacing 

•	convergence_stage and intermediate_stage folders: Both these folders consist of two csv files each. “rawembstd.csv” contains the meta-dataset obtained through the above two codes, where “rawembstd.csv” present in convergence_stage folder represents meta-dataset obtained by training probe_network till convergence_stage. Same corresponding to the “intermediate_stage”. Similarly, “Veg_3_stddev.csv” corresponds to the vectors obtained for Veg_3 disease classification task corresponding to the two training stages of the probe network.

•	Models.csv: it contains the names of the pre-trained models used for the experiment

•	Meta_Learning_Ranking.ipynb: it contains the code for calculation of RBO scores. It uses rawembstd.csv file to train the meta-learner and Veg_3_stddev.csv file to recommend the best models and calculate the RBO score by comparing with the original rankings of the model.

•	Plant Disease Image Classification tasks data has not been uploaded due to the size of the data and copyright issues for using data from different resources.
