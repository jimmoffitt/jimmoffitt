### Hi there and welcome 👋

So, here is a collection of repositories written mainly in Python and Ruby, with a fair amount of JavaScript mixed in. 

For eight years I was on the Twitter developer relations team, and as such, most of these repositories are focused on collecting, analyzing, and displaying Twitter data. These repositories can be broken up into three types:

- 'Backend' scripts that make API requests, receive the data, and typically store that data somewhere (or if a simple example, just send it off to the ether). 
  - https://github.com/twitterdev/search-tweets-python/tree/v2 - Since around 2019, I have driven development of this widely used Python client of the Twitter API search endpoints. In late 2021, I migrated the codebase from API 1.1 Enterprise to API 2.0, and added addtional features. 
  - https://github.com/twitterdev/search-tweets-ruby - Sole developer of this Ruby client of the Twitter API search endpoints (all flavors expect 'standard 1.1'). 

- Web applications in the form of standalone websites or chatbot applications hosted on Twitter. 
  - https://github.com/twitterdev/SnowBotDev - Started as a demo of the Twitter Account Activity API, evolved into a full-featured chatbot application. (Since leaving Twitter, this app is no longer functional due to the TwitterDev account on Heroku being abandoned.)
  - https://github.com/jimmoffitt/SocialFlood - In 2016-2017, I went deep into Twitter data use cases related to flood-warning systems. This and other related content led to receiving two national awards for innovation related to public safety and weather communications. 

- Customer tools for working with Twitter data. 
  - https://github.com/jimmoffitt/json2csv - Many, many customers were not equipped to work with Tweet JSON files and wanted to work instead with simple CSV files (think of a social studies reseacher who wants to due spreadsheet-hosted analysis. 
  - https://github.com/jimmoffitt/bounding-boxes - Twitter API endpoints that enable searched based on user-shared location data require areas of interest defined by matrices of 'bounding boxes' rectangles with edges no longer than 25 miles. This tool is used to take a 'study area' of interest, however large, and output a set of valid bounding boxes.
  - https://github.com/jimmoffitt/rules-migrator - Twitter API search and filtered stream customers build queries to match on Tweets of interest. Customer can have up to 250,000 queries per real-time stream, and can have even more that are used with search endpoints. This tool was first developed in 2016 to help customers migrate to a version of enterprise endpoints. Before I left Twitter, this tool was updated to migrate queries and filters to Twitter API v2 (on a Twitter internal repository).

During the 13 years before Gnip/Twitter, I developed flood-warning software, so you may notice a certain use case dominates. 

And finally, I am searching for the next chapter in my career... I'm excited to see where I land ;) 

🔭 I’m currently working on getting a Windows 11 laptop set up for development. I've been working with the MacOS for a decade now, and I know it will be interesting to return to Windows. With terminal emulators, virtual machines, and a current IDE, I am hoping I'll be on the OS-agnostic road soon. 

📫 How to reach me: https://twitter.com/snowman


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
