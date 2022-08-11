add_tags_aws deletes the exxisting tags of the aws EC2 instance, reads the details of the new tags of the instance from a csv file passed as a command line argument and update the new tags.

The file is written for the particular new six tags
1. Name 
2. envname
3. orgname
4. teamname
5. techstackname
6. techsubstackname


To the run file pass use the command line given below.

 `$ python3 add_tags_aws.py <path of csv file>`

 for example if your tags csv file is in test directory and name of file is tags.csv

  `$ python3 add_tags_aws.py test/tags.csv`
