NAME     :   V.Savitha
BATCH    :   DTM9
PROJECT  :   YOUTUBE DATA HARVESTING AND WAREHOUSING
LANGUAGES & TOOLS USED  : PYTHON, MONGODB, MYSQL, PANDAS

INTRODUCTION :
    This project is a YouTube API Harvesting that allows users to retrieve and analyze data from 
YouTube channels. It utilizes the YouTube Data API to fetch information such as channel statistics, 
video details, comments, and more. It provides various functionalities to extract and 
process YouTube data for further analysis and insights.

FEATURES :
    The YouTube Data Harvesting offers a range of features to help you extract and analyze data 
from YouTube. Some of the key features include:
    Retrieve channel statistics: 
        Get detailed information about YouTube channels, including subscriber count, view count, 
    video count, and other relevant metrics.

    Fetch video details: 
        Extract data such as video title, description, duration, view count, like count, dislike 
    count and publish date for individual videos.

    Analyze comments: 
        Retrieve comments made on YouTube videos and perform analysis, such as sentiment analysis or 
    comment sentiment distribution.

    Data storage: 
        Store the collected YouTube data in a database for easy retrieval and future reference.

TECHNOLOGIES USED :
    Python: 
      The project is implemented using the Python programming language.
    YouTube Data API: 
      Utilizes the official YouTube Data API to interact with YouTube's platform and retrieve data.
    Streamlit: 
      The user interface and visualization are created using the Streamlit framework, providing a 
    seamless and interactive experience.
    MongoDB: 
      The collected data can be stored in a MongoDB database for efficient data management and 
    querying.
    MySQL: 
       MySQL is used to connect with the SQL database and henceforth storing in tables. 
    PyMongo: 
      A Python library that enables interaction with MongoDB, a NoSQL database. It is used for storing
    and retrieving data from MongoDB in the YouTube Data Scraper.
    Pandas: 
      A powerful data manipulation and analysis library in Python. Pandas is used in the YouTube Data 
    Scraper to handle and process data obtained from YouTube, providing functionalities such as data 
    filtering, transformation, and aggregation.

APPLICATION FLOW :
    1. Copy the channel id of a youtube channel from the about section and paste it in the 'select 
channel id' text box.
    2. The respective channel id data will be displayed in a brief table format.
    3. By clicking on the Upload MongoDB button, the required channel data will be uploaded to the
MongoDB Database.
    4.Choose the MySQL Database tab and select the channel from the dropdown menu to load the data
to SQL Database.
    5.Choose the Queries tab and select any from the dropdown menu to view a detailed analysis of 
the channel data.

CONCLUSION :
    This YouTube API scrapper project aims to provide a powerful tool for retrieving, analyzing, and 
visualizing YouTube data, enabling users to gain valuable insights into channel performance, video 
engagement, and audience feedback.

