# Week 2 Assignment
### Github repo link
[here](https://github.com/sanidhyaanand/MLOps_Assignment)
### Command List
```shell
git clone https://github.com/sanidhyaanand/MLOps_Assignment.git
dvc init
mkdir data
mkdir ../external_cache
dvc cache dir ../external_cache
dvc add .\data\creditcard.csv
git add 'data\creditcard.csv.dvc' 'data\.gitignore'
git commit -m "added raw data"
dvc remote add -d storage s3://anythingiwant/datastore
git add .dvc/config
git commit -m "configuring remote"
dvc push
```
### Accuracy and Weighted F1 scores
#### Experiment 1 - Decision Trees
Accuracy: 0.9992977774656788
Weighted F1 Score: 0.9993081879885035

#### Experiment 2 - Random Forests
Accuracy: 0.9996137776061234 <br>
Weighted F1 Score: 0.999596639330722 <br>
