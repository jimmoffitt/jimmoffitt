### 👋 Hi there and welcome 👋

So, here is a collection of repositories written mainly in Python and Ruby, with a fair amount of JavaScript mixed in. 

- 💬 Ask me about: Building APIs, real-time data and event-driven architecture, early-warning systems, and working with weather data.
  
I recently joined [Tinybird](https://www.tinybird.co/) as a developer advocate and you'll see more Tinybird-related projects, demos for showing the kinds of APIs you can build on that platform. I'm sure the first few will include some sort of weather-related theme. 

*Update*: Here are some Tinybird projects:
  * https://github.com/jimmoffitt/weather-api
  * https://github.com/jimmoffitt/get_and_send_weather_data
  * https://github.com/tinybirdco/pubsub-website-events-poc
  
For eight years I was on the Twitter developer relations team, and as such, most of these repositories are focused on collecting, analyzing, and displaying Twitter data. These repositories can be broken up into three types:

- 'Backend' scripts that make API requests, receive the data, and typically store that data somewhere (or if a simple example, just send it off into the ether). 
  - https://github.com/twitterdev/search-tweets-python/tree/v2 - Between 2018-2022, I maintained and enhanced this widely used Python client of the Twitter API search endpoints, including a 2021 migration from API 1.1 Enterprise to API 2.0. There is also [this Ruby implementation](https://github.com/twitterdev/search-tweets-ruby) that I developed and updated over the years. It supports all v2 and enterprise Twitter search endpoints (and not 'standard 1.1'). 

- Web applications in the form of standalone websites or chatbot applications hosted on Twitter. 
  - https://github.com/twitterdev/SnowBotDev - Started as a demo of the Twitter Account Activity API, evolved into a full-featured chatbot application. (Since leaving Twitter, this app is no longer functional due to the TwitterDev account on Heroku being abandoned.)
  - https://github.com/jimmoffitt/SocialFlood - In 2016-2017, I went deep into Twitter data use cases related to flood-warning systems. This and other related content led to receiving two national awards for innovation related to public safety and weather communications. 

- Customer tools for working with Twitter data. 
  - [JSON to CSV translator](https://github.com/jimmoffitt/json2csv) - Many, many customers were not equipped to work with Tweet JSON files and wanted to work instead with simple CSV files for spreadsheets or loading into a database (think of a social studies reseacher who wants to do spreadsheet-hosted analysis). With this tool, you can map the JSON attributes of interest to column fields, point to a collection of JSON files, and generate CSV files.  
  - [Bounding boxes](https://github.com/jimmoffitt/bounding-boxes) - Many of the most popular Twitter API endpoints enable searching for Tweets of interest by matching on locations shared by users. The Twitter query language supports a 'bounding box' operator that matches on rectangular areas with sides no larger than 25 miles. This tool is used to take a 'study area' of interest, however large, and output a set of valid queries with bounding box definitions.
  - [Query migrator](https://github.com/jimmoffitt/rules-migrator) - Twitter API search and filtered stream customers build queries to match on Tweets of interest. Customer can have up to 250,000 queries per real-time stream, and can have even more that are used with search endpoints. This tool was first developed in 2016 to help customers migrate enterprise versions (the "Gnip 2.0" migration). Before I left Twitter, this tool was updated to migrate queries and filters to Twitter API v2 (on a Twitter internal repository).

During the 13 years before Gnip/Twitter, I developed flood-warning software, so you may notice a certain use case dominates. 

📫 How to reach me: 
* https://www.linkedin.com/in/jimmoffitt/
* @snowman.bsky.social
* https://twitter.com/snowman


<!--
**jimmoffitt/jimmoffitt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
