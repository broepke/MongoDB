# A Quick Start for Taking MongoDB Collections into Pandas DataFrames
 Article on How to Connect to and Extract Data from MongoDB
 
**MongoDB** is in a class of databases known as [**NoSQL**](https://en.wikipedia.org/wiki/NoSQL) databases. NoSQL databases are designed to store and retrieve data without the need for predefined schemas, which is in contrast to relational databases, which require a schema to be defined before you can store data. MongoDB is a [**document store**](https://en.wikipedia.org/wiki/Document-oriented_database), which means it stores data in **JSON-like documents**. 

I recently came across a project where I needed to connect to MongoDB and perform data analysis. One option would be to ask someone familiar with the database to extract the data into a format like CSV, which is easy to pull into Python. However, that's not an efficient way to get the **latest data**. I also knew MongoDB's persistence is in a JSON-like format, and as a Data Scientist, I preferred a **Pandas DataFrame**. As most Data Science practitioners know, once our data is in a DataFrame, we can perform any of our standard operations on that data from [EDA]({filename}../ml/eda.md), to [Feature Engineering]({filename}../ml/featureeng.md), to [Model Selection]({filename}../ml/modelselection.md) and [Evaluation]({filename}../ml/modeleval.md).

**Note:** An even better way would be to extract the data into a Data Warehouse such as [Snowflake](https://www.snowflake.com/en/) via a tool like [Fivetran](https://www.fivetran.com/connectors/mongodb). However, that wasn't practical at this point in the project; this was the next best option!

Read more here: https://www.dataknowsall.com/mongo.html
