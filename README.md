# NLP-Friends
2020-1R Natural Language Process

## Environment 
Google Colab, Runtime : TPU

## Requirement 
1) Friends Dataset(http://doraemon.iis.sinica.edu.tw/emotionlines/download.html)<br>
2) Kaggle Dataset(https://www.kaggle.com/c/cose461e/overview)

## Filepath Setting 
1) friends_path : folder which contains Friends dataset(freinds_train.json, friends_dev_json, friends_test.json)
2) kaggle_path : folder which contains Kaggle Dataset(en_data.csv, en_sample.csv)

## SorceCode Refence

1) WeightedCategoricalCrossentropy <br>
https://stackoverflow.com/questions/61919774/unexpected-keyword-argument-sample-weight-when-sub-classing-tensor-flow-loss-c<br>

2) BertForSequenceClassification <br>
https://huggingface.co/transformers/_modules/transformers/modeling_bert.html#BertForSequenceClassification

3) TPU Setting <br>
https://github.com/GoogleCloudPlatform/training-data-analyst/issues/678
