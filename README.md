# Feedbacks_And_Queries_Portal
A website portal for summarising the feedbacks and, processing and replying the queries of a user. It uses Hadoop DFS for storage of queries and feedbacks. Queries are acknowledged using Natural Language Processing and various Python Libraries, and the result is displayed on the respective ministry portal.

Hadoop part involves the python code for the mapper and the reducer. It also includes the screenshots of the input and output files.

NLP part involves the python code for processing the queries and the feedbacks. The queries are processed using query matching technique called Jaccard Similarity, for matching the queries with the questions already present in the excel database and returning the solution. If the query is not present in the database, then we return the googled result.

The folder contains dummy datasets, json file, feedbacks and queries , result of queries and summary
