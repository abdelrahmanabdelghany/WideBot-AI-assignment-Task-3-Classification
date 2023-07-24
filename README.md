# WideBot-AI-assignment-Task-3-Classification
## Training Process
### Data preparation
* read csv files and create train test splits
* remove stop words
* featur extraction using TfidfVectorizer
### Model Selection
* choose set of parameters for gridsearchcv
* using SGDClassifier
### Results on Test Data
* |   | precision  | recall  | f1_score |accuracy| 
     |---|---|---|---|---|
    |  art-et-culture |  0.81 |0.93   | 0.86 | 0.93|
    | economie  |  0.80 |0.87   |0.86   | 0.87|  
    |  faits-divers  |  0.93 |0.95   | 0.94  | 0.95|  
    |  marocains-du-monde   |  0.84 |0.90   |0.87   | 0.895|  
    |  medias  |  0.94 |  0.86 |0.90   |0.865|   
    | orbites  |  0.62 |  0.55 |  0.58 | 0.55|  
    |  politique | 0.72   |  0.82 |  0.77 |0.825|   
    |   regions | 0.84  | 0.8  |0.82   |   0.8|
    |  societe  |   0.74|  0.60 |   0.66| 0.605|  
    | sport |   0.98|    0.96 |   0.97|0.965|
    |  tamazights  | 0.96  |  0.94  |   0.95|0.935|
    |avg  | 0.83  |   0.84|  0.83 |0.84|

* Precision is a measure of how many of the positive predictions made are correct.  
* Recall is a measure of how many of the positive cases the classifier correctly predicted, over all the positive cases in the data.
* F1-score is a single metric that weights the two ratios (precision and recall) in a balanced way.
* Accuracy is the number of correct predictions over all predictions
## Insights
* The model strugles with two topics orbites and societe. This could be because there is no strong keywords for these topics.




