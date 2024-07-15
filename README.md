# Web-Server-Logs-Pyspark
Pyspark Data Manipulation Queries on Web Server Logs

I've used the Kaggle Web Access Logs Dataset (https://www.kaggle.com/datasets/eliasdabbas/web-server-access-logs/data)
for performing basic pyspark data manipulation queries.
This exercise was performed as a learning activity to learn pyspark and sparkSQL.

The aim of this project is to extract as many cyber security relevant information as possible. Below queries have been performed in this codebase.

# 1. Count the number of occurrences of each HTTP status code
# 2. Show list of unsuccessful requests (Status code not 200)
# 3. Find the top 10 IP addresses making requests and whether they are malicious or not
# 4. Identify Potential Unauthorized Access Attempts (401) and if the IP is malicious or not
# 5. Detect Multiple Failed Login Attempts
# 6. Find Most Frequently Accessed Sensitive Endpoints (/admin)
# 7. Identify Large File Downloads
# 8. Detect Unusual Activity Patterns. Show all the IPs which have made huge amount of requests in a 5 minute window
