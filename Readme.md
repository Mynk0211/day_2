add_tags_aws.py deletes the existing tags of the aws EC2 instance, reads the details of the new tags of the instances from a csv file passed as a command line argument and add the new tags.

The file is written for the particular new six tags
1. Name 
2. envname
3. orgname
4. teamname
5. techstackname
6. techsubstackname

Changes can be made according to the csv file column and name of the tags can be changed in the string
in line 29 of the python file.


To the run file pass use the command line given below.

 `$ python3 add_tags_aws.py <path of csv file>`

 for example if your tags csv file is in test directory and name of file is tags.csv

  `$ python3 add_tags_aws.py test/tags.csv`
