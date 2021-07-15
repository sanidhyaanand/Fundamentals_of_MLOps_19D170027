# Week 2 Assignment
### Github repo link
[here](https://github.com/sanidhyaanand/MLOps_Assignment)
### Command List
```shell
git clone https://github.com/sanidhyaanand/MLOps_Assignment.git <br>
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
