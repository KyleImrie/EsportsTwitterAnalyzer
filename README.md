# EsportsTwitterAnalyzer
The objective of this project is to develop a sentiment analysis and data visualization platform on the Google Cloud Platform. In working on this project, I hope to develop my skills in working with Apache Kafka and the GCP ecosystem.

This project is a work-in-progress. Below, I have described my project as I see it developing over the coming weeks.

## Introduction
Some of my passions are eSports games and the communities that exist around them. With livestreaming on Twitch and social media becoming evermore popular, it is easier than ever before to feel connect to your favorite personalities in the community of your favorite video game.

For example, I love the game Super Smash Brothers Melee. This game was released nearly 18 years ago and, despite many sequel installments in the series, remains nearly as popular as it has ever been. To play such an old game requires a certain kind of personality, and those personalities shine heavily through Twitter.

I personally follow hundreds of figures through the Smash community on Twitter and I enjoy seeing both their reactions to tournament results and their everyday musings on real life. What I wanted to develop was a tool that made understanding these trends in social media better.

## Backend
The goal for the near-term future is to develop a Producer application for Apache Kafka that ingests live Tweets through the Twitter API. These tweets will be fed into Google's BigQuery data warehouse for future analysis.

I plan to use Google's Cloud Natural Language service to provide sentiment analysis for these Tweets.

This section is a work-in-progress.

## Frontend
This section is a work-in-progress.
