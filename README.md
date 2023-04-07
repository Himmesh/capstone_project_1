##Twitter Data Scraping

A web app built on streamlit using python and snscrape library to scrap data from twitter for the given keyword /hashtag

##Snscrape

Here snscrape is used to scrape tweets from Twitters API without any restrictions or request limits. Moreover, we dont even need a Twitter developer account to scrape tweets when you use snscrape.

##**MongoDB**

With MongoDB here we can upload the scraped data and as we know MongoDB is much more than a database. It’s a complete developer data platform. And with MongoDB Atlas, the cloud offering by MongoDB, Hepls us to establish connection and store data.

##**Streamlit**

As we all know Streamlit turns data scripts into shareable web apps in minutes. All in pure Python. No front‑end experience required. We use it with search box, sliders, buttons, download buttons etc.,

##**Download Files**

We also convert the DataFrames to csv and json files as it will be Downloadable

##**Workflow**

• By using the “snscrape” Library, Scrape the twitter data from Twitter Reference 
• Create a dataframe with date, id, url, tweet content, user,reply count, retweet count, language, source, like count. 
• Store each collection of data into a document into Mongodb along with the hashtag or key word we use to Scrape from twitter.
• Else the data can be downloaded either in form of CSV or JSon format

Create a GUI using streamlit that should contain the feature to enter the keyword or Hashtag to be searched, select the date range and limit the tweet count need to be scraped. After scraping, the data can be displayed in the page or upload the data into Database or download the data into csv and json format.

##**To Execute the Code:**

#Pre-requsites: Your system should be ready with the following modules installed for the code to run 

•	Snscrape: import snscrape.modules.twitter as sntwitter
•	Pandas: import pandas as pd
•	Pymongo: import Pymongo
•	Datetime: import Datetime
•	Streamlit: import streamlit as st
After setting the things up, the following stepts are to be taken to Run the script

Step 1: Open the command promt and cd to the path where the python script/ code is stored.
![image](https://user-images.githubusercontent.com/35806558/230665962-be273dae-71c5-4906-9720-c6108758b9c5.png)

Step 2: Run the script with the command "streamlit run <file_name>"
![image](https://user-images.githubusercontent.com/35806558/230666067-8cc8a007-ce37-4061-a35c-061ed9b0b104.png)

Once the command is executed the command promt will give the following output and parallelly open the browser for the GUI to run 

Command Prompt output:
![image](https://user-images.githubusercontent.com/35806558/230666467-eb204b9c-8749-4e3a-bfda-17868943a374.png)

parallelly it will track all the moments and tasks performed on the webpage 

GUI of Streamlit on webpage:
![image](https://user-images.githubusercontent.com/35806558/230666631-a11f0fca-d7c8-43c4-bb48-e4d7adc0bdc8.png)

Step 3: Select the required option on the Streamlit GUI and you can have the following results

Selected options:
![image](https://user-images.githubusercontent.com/35806558/230667077-5e8aa7d3-77e2-4a98-ae6c-e0af22a92e68.png)

Show Tweets optput:
![image](https://user-images.githubusercontent.com/35806558/230667183-fdcfa1d7-1cbf-4d5f-947d-5bd1e7165348.png)

Download CSV file:
![image](https://user-images.githubusercontent.com/35806558/230667328-cc960c80-7d3b-4318-a15d-6bd31bd6a31d.png)

Download JSon file:
![image](https://user-images.githubusercontent.com/35806558/230667678-15537015-6cbb-44a9-a9cf-0f98ed952019.png)

I opened in note pad so the data wont be identated, if you have any application that can view json files, you should be able to see the data clearly

Data uploaded to local MongoDB:
![image](https://user-images.githubusercontent.com/35806558/230668128-f1f148ff-2701-41ec-ba9d-d9f643ee62ac.png)

