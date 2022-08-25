# StockSentimentTracker: All of the Trends, None of the Trolls

## Overview:

### New app that provides busy retail investors with timely updates on the latest social media meme stock trends, without ever having to log into Reddit or Twitter

BERKELEY, CA - In January 2021, the price of GameStop stock rose 2000% over 3 weeks. This sudden rise was the result of a short squeeze triggered largely by a community of retail investors on the subreddit r/wallstreetbets. Since then, the “meme stock” movement has exploded across social media, with the 3 most popular stocks each averaging over 3,000 mentions per day on Reddit and Twitter. 

There is certainly a lot of interest in the movement (r/wallstreetbets has over 12 million members alone), but only a small fraction of those interested are actively participating in the conversation. Many investors are simply looking to understand the latest discussion on these forums in the hopes of getting in (or out) early on the next trending stock. This is where a team of students at UC Berkeley has stepped in. Their new app, MemeStockTracker, consolidates data from Reddit and Twitter, providing a holistic view of the number of mentions and sentiment of stocks across the platforms. Don’t have time to check the app? Users can also set an alert to receive daily notifications when activity or sentiment changes for their favorite stock. 

While there are a number of existing apps tracking meme stock mentions or sentiment, none offer the simplicity and time-saving alert capabilities of MemeStockTracker. A simple yet comprehensive leaderboard gives users all of the information they need to determine which stocks are worth taking a deeper look at, and email notification functionality gives them the opportunity to stay up to date on the stocks they care about with just a few clicks.

A number of technical components underpin the app’s functionality, as illustrated below. Twitter, Reddit, and Yahoo Finance APIs are leveraged to source stock menitions and price data. An ensemble of sentiment models then calculates sentiment probabilities. Finally, the information is beautifully displayed in a sleek UI developed in Anvil. Amazon EC2 allows the app data to be refreshed automatically each day.

Reception of the app has been very positive so far. 95% of the app’s initial users said they would use the app again, with most praising the quality of information, time saved, and ease of use. One user claimed “This app is exactly what I’m looking for. It gives me all of the information I need with minimal effort.” Don’t believe them? Try the app yourself at the link below.

## App Preview
!()[pt1.png]
!()[pt2.png]
!()[pt3.png]
!()[pt4.png]
!()[pt5.png]
#### To see the app in action, click [HERE](https://stocksentimenttracker.anvil.app/)!
