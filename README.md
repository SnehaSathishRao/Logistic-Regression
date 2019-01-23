# Logistic-Regression
**About Algorithm:**<br />

**Data:**<br />
    I have used Amazon data which contains summary of reviews that is featurized using NLP techniques(Bag of words,TfIdf,Average word2vec,TfIdf word2vec) gives higher dimensional.The Amazon data that is been used has already been pre-processed and loaded.<br />
**Summary**:  <br />

|     Model     |  Hyper_parameter(C) |   Train f1-score   |   Test f1-score    |
| ------------- | ------------- |------------- | ------------- |
|    grid_BOW   |          1          | 0.9642443665162167 | 0.9396309039724742 | 
|  grid_TF_IDF  |         1000        | 0.9999918558153551 | 0.9653080068592534 | 
| grid_avgw2vec |         0.1         | 0.8805440673131775 | 0.8805164611616225 | 
|  grid_ww2vec  |         0.01        | 0.8627956446495529 | 0.8664448768648129 |
|    rand_BOW   |  1.349544480197799  | 0.9667247211709147 | 0.9395797531635681 | 
|  rand_TF_IDF  |  1.816945741505411  | 0.9818932155494601 | 0.9541677937937165 | 
| rand_avgw2vec |  0.257604623640196  | 0.8803481300494016 | 0.8804916535171498 |
|  rand_ww2vec  | 0.22082248356008288 | 0.8625781369798761 | 0.8650845185479985 |
