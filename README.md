# User Intent Prediction in Information-seeking Conversations
This is the reproduction of "[User Intent Prediction in Information-seeking Conversations](https://arxiv.org/pdf/1901.03489.pdf)". The source code can be found in the [github](https://github.com/prdwb/UserIntentPrediction). We also implement the classificatio with BERT. The BERT is used to encode the utterances, and BilSTM is trained for the classification. 

## Data
+ We used the "MSDialog-Intent" data in the [MSDialog](https://ciir.cs.umass.edu/downloads/msdialog/) dataset. 
+ The data is removed in this repository. 

## Code
+ ./BERT : the preprocessing, the generatation of encoded vector from BERT and the training of BiLSTM
+ baselines_classification.ipynb: the training of the baseline ML methods
+ ./neural_models: Neural models from the source code 
+ ./features: Feature generation for ML methods
