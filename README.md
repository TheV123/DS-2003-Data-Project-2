### Author: Vishal Kamalakrishnan
### Computing Id: cjq2cw

This project will analyze sales of a mock company. The data for the mock company is present into 3 dimensions dim_store, dim_date, and dim_country. dim_country has been stored in a csv file in DBFS. dim_date has been stored in a Azure Mysql Server. dim_store has been stored in a mongo db database. A fact table will be loaded in containing mock company fact table from my midterm project and this data will be streamed into a bronze and silver table. The silver table will be an aggregate of the "realtime" streamed tables and the dim tables and will be useful to see "realtime" buisness process of the mock_company

To run this lab - place the fact_sales1.json, fact_sales2.json, fact_sales3.json in a stream directory in DBFS/Filestore. Place the dim_country csv file in a dim_country directory in DBFS/Filestore. The mongoDB database should aready be populated with the dim_store, but if it is not place the dim_store.json file in a dim_store directory in DBFS/Filestore


