# Zomato data analysis

Introduction 

Food is the main wellspring of imperative vitality in our body – it literally makes up every part of us. Eating makes us feel good; it is also a social urge nowadays. Advancements in technology have paved way for various innovations in the consumer services domain - food delivery apps being one among the important ones. Zomato (initially Foodiebay) is an Indian restaurant aggregator and food delivery startup, founded in 2008 by two IIT Delhi alums. Today, Zomato caters to 24 countries, has over 80 million active users and provides a variety of services such as restaurant search and discovery, online ordering, table reservations and management, POS systems and subscription services. 

For our analysis, we decided to use the Zomato Bangalore dataset, which was scraped for educational purposes (https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants). The copyrights are owned by Zomato Media Pvt. Ltd. The dataset contains information that one can find on the app – ratings, reviews and addresses of restaurants, most popular dishes and approximate cost of dining.

Bangalore is the IT capital of India – a significant portion of the population relies on restaurant food, due to lack of time to cook daily. There are over 12,000 restaurants in Bangalore, serving a multitude of cuisines. The main goal of our analysis is to gather latent insights from data that are easy for consumers and restaurant owners to understand and make better and informed choices. We built a variety of functionalities – 

* Visual guide to gain insight about desirable restaurants based on constrains such as location, budget votes and rating 

![](https://i.imgur.com/AdqP4mY.png)

* An interactive guide which lets users select the location and restaurant of choice, and view a word cloud of reviews to gauge how good or bad the restaurant might be 
* Finding the optimal combination of restaurants in a desired location, aimed at maximizing dine outs in a month, based on ratings and cost of dining, given constraints such as budget (a variation of the Knapsack Problem). Also compare time taken by both algorithms  Predicting rating using multiple linear regression – based on online ordering, table booking and cost of dining of two people 
* Heatmap of number of restaurants by extracting latitudes and longitudes
