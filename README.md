# Predicting Diseases From Symptoms

This is an attempt to predict diseases from the given symptoms. A decision tree was trained on two datasets, one had the scraped data from [here](http://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html).

This dataset is uncleaned so preprocessing is done and then model is trained and tested on it.

Next another decision tree was also trained on [manually created dataset](https://github.com/Aniruddha-Tapas/Predicting-Diseases-From-Symptoms/tree/master/Manual-Data) which contains both training and testing sets. This data is cleaned and extensive and hence learning was more accurate. The exported decision tree looks like the following :

![Decision-Tree](https://raw.githubusercontent.com/Aniruddha-Tapas/Predicting-Diseases-From-Symptoms/master/tree-top5.png)


Head over to [Data-Analyis.ipynb](https://github.com/Aniruddha-Tapas/Predicting-Diseases-From-Symptoms/blob/master/Data-Analysis.ipynb) to follow the whole process.

<hr>

#### To Do:

- [ ] Create a web service in Flask for disease predictions using the trained model.
- [ ] Perform Affinity Analyis to observe which symptoms usually occur together.

<hr>