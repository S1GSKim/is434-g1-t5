# is434-g1-t5

## How to run Twitter_snsscrape_project_misinformation.ipynb

1. Run 12 ipynb files to scrape tweets from 12 News Medias at chosen timeframe, it will create corresponding csv files which are scraped data <br />

Required files : <br />
-ABC News.ipynb <br />
-BuzzFeed.ipynb <br />
-Daily_Express.ipynb <br />
-FoxNews.ipynb <br />
-MailOnline.ipynb <br />
-MSNBC.ipynb <br />
-NBCNews.ipynb <br />
-Telegraph.ipynb <br />
-USATODAY.ipynb <br />
-voxdotcom.ipynb <br />
-washingtonpost.ipynb <br />
-WSJ.ipynb

2. We will make use of scraped data from 12 csv files , and also we need 3 other csv files (Fake.csv, True.csv , manual_testing.csv) which were datasets used to train the open-source fake news detection model. Run the twitter_snscrape_project_misinformation , it will generate the visualization output at the bottom of notebook. <br />

Required files : <br />
-Twitter_snscrape_project_misinformation.ipynb <br />
-Fake.csv <br />
-True.csv <br />
-manual_testing.csv <br />


===========================================================================

## How to run the Sentiment and Topic models files<br>
Sentiment and Topic Model Files: <br>
- TopicModeling-during1.ipynb
- TopicModeling-during2.ipynb
- TopicModeling-post.ipynb
- Project (Sentiment Analysis for during Part 1).ipynb
- Project (Sentiment Analysis for during Part 2).ipynb
- Project (Sentiment Analysis for post covid).ipynb

<br>
Required file : <br />
Scraping Top 200 Users Tweets for 3 time periods (DURING COVID Part 1, DURING COVID Part 2 and POST Covid).ipynb

<b> This will scrape the following time period with the following keywords </b> <br>

keywords: <br>
- covid <br>
- coronavirus <br>
- vaccine <br>
- vax <br>
- Pfizer <br>
- BioNTech <br>
- Sinopharm <br>
- Sinovac <br>
- Moderna <br>
- Oxford/AstraZeneca <br>
- AstraZeneca <br>
- Covaxin <br>
- Sputnik <br>
<br>
<br>
time periods: <br>
- since:2020-12-01 until:2021-02-28 <br>
- since:2022-01-01 until:2022-03-31 <br>
- since:2022-12-01 until:2023-02-28 <br>


output:
during1_covidTweets_v2.csv
during2_covidTweets_v2.csv
post_covidTweets_v2.csv

=======
## How to dashboard<br>

go to code/dashboard/dashboard <br>

In terminal , type 'npm install' , then 'npm start'