
# Youtube Data harvesting and Warehousing

YouTube Data Harvesting and Warehousing is a application which allows the users to access and analyse data from multiple YouTube channels. This application allows the user to give a YouTube channel ID as input and retrieves the relevant data through Youtube API. and store them in MongoDB just clicking a button. By Selecting a channel name, we can migrate the data from Mongo Database to MySQL. This application provides some insight about those youtube channels  by selecting certain queries

# Developed Using:
*	**Language** - Python
*	**Libraries** - python-youtube, pandas, mysql-connector, PyMySQL,  SQLAlchemy, pyMongo
*	**Database** - MongoDB, MySQL
*	**API key**
*	**Front-End/GUI** - Streamlit

# Workflow:
1.	Create a dashboard using streamlit.
2.	Obtain API credentials by enabling YouTube Data API in Google Developers console.
3.	Using Google API , extract YouTube Channel, Playlist, Video and Comment data.
4.	Push the extracted YouTube data into MongoDB.
5.	Migrate the data from MongoDB to SQL.
6.	Retrieve the youtube information using SQL query.


## Application Workflow
### Home ###
![Home](https://github.com/IamShivakumar/Youtube_DataHarvesting_and_Warehousing/blob/main/Screenshots/Home.png)

### Extract and Tranfer data ###
## • Extract Data: ## 
In Extract Menu you can retrieve data by providing channel id and store it in MongoDB. 

•	NOTE: To get channel Id:- Go to Any youtube channel  Right click anywhere in the homepage of the channel  Click view page source option  Press ctrl+f and search for “?channel”. you’ll find channel id as below screenshot:
![](https://github.com/IamShivakumar/Youtube_DataHarvesting_and_Warehousing/blob/main/Screenshots/channel_id.png)

![Extract](https://github.com/IamShivakumar/Youtube_DataHarvesting_and_Warehousing/blob/main/Screenshots/Extract.png)

## • Transfer Data: ## 
In this menu you can able to migrate the data to structured database MySQL by selecting the channel name.

![Transfer](https://github.com/IamShivakumar/Youtube_DataHarvesting_and_Warehousing/blob/main/Screenshots/Tranfer.png)

### Insights ###
In this menu you can select any queries to provide insights about the data based on the selected query.

![Insights](https://github.com/IamShivakumar/Youtube_DataHarvesting_and_Warehousing/blob/main/Screenshots/Insights.png)
