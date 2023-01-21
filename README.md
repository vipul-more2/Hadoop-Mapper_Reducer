# Mapper_Reducer
##mapper and reducer function for grouping and sorting data 

MovieLens dataset link:
http://media.sundog-soft.com/es/ml-100k.zip

The python file contains mapper and mutiple reducer functions which groups and sorts the data in ascending order.
File u.data from the dataset contains tabular information about movies and their orresponding ratings. The aim is to get the number of ratings per movie from the dataset which is distributed across HDFS. Use of Mapper And reducer functions(written in python) helps sort, reduce and organize the data in hadoop environment.

Connect to Hadoop environment using Putty(Windows) or Terminal(MacOS) and run the command "python RatingsBreakdown.py u.data" 
If the code file and dataset file is not in the same location then give the path of datafile in the above command 
