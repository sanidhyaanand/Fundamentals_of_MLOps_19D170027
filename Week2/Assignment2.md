# Week 2 Assignment
### Github repo link
https://github.com/sanidhyaanand/MLOps_Assignment
### Command List
1. git clone https://github.com/sanidhyaanand/MLOps_Assignment.git <br>
2. dvc init
3. mkdir data
4. mkdir ../external_cache
5. dvc cache dir ../external_cache
6. dvc add .\data\creditcard.csv
7. git add 'data\creditcard.csv.dvc' 'data\.gitignore'
8. git commit -m "added raw data"
9. dvc remote add -d storage s3://anythingiwant/datastore
10. git add .dvc/config
11. git commit -m "configuring remote"
12. dvc push
