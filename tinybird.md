# Tinybird

Here is a collection of content I developed while at Tinybird. I learned a ton there. 

## Blog posts 

* [Designing and implementing a weather data API](https://www.tinybird.co/blog-posts/designing-and-implementing-a-weather-data-api) - Revisitied my flood-warning system experience in the Tinybird context.
* [8 considerations for designing public data APIs](https://www.tinybird.co/blog-posts/8-considerations-for-designing-public-data-apis) - A high-level view of building public APIs and how Tinybird helps abstract away many backend concerns when storing and publishing real-time data. 
* [Real-time anomaly detection](https://www.tinybird.co/blog-posts/real-time-anomaly-detection) - My favorite Tinybird project.
* Ghost wrote this with a Tinybird Python guru: [Killing the ProcessPoolExecutor](https://www.tinybird.co/blog-posts/killing-the-processpoolexecutor) - One of my favorite writing projects. I learned a lot and it's always fun collaborating with engineers.

During the summer of 2023, we experimented with writing high-level content for [The New Stack](https://thenewstack.io/):
* [The basics of event-driven architectures](https://thenewstack.io/the-basics-of-event-driven-architectures/)
* [Change data capture for real-time access to backend databases](https://thenewstack.io/change-data-capture-for-real-time-access-to-backend-databases/)
* [The fundamentals of data API design](https://thenewstack.io/the-fundamentals-of-data-api-design/)
* [Real-time databases: Who is using them and why](https://thenewstack.io/real-time-databases-who-is-using-them-and-why/)

During my Tinybird travels, I also had a great introduction to change data capture, and a deep dive into real-time leaderboards. 
* [A practical guide to real-time CDC with Postgres](https://www.tinybird.co/blog-posts/postgres-cdc)
* [A practical guide to real-time CDC with MySQL](https://www.tinybird.co/blog-posts/mysql-cdc)
* [Building real-time leaderboards with Tinybird](https://www.tinybird.co/blog-posts/building-real-time-leaderboards-with-tinybird)

## Repositories

* [zero-to-tinybird](https://github.com/tinybirdco/zero-to-tinybird)
* [use-case-real-time-anomaly-detection](https://github.com/tinybirdco/use-case-real-time-anomaly-detection)
* [demo-user-facing-leaderboard](https://github.com/tinybirdco/demo-user-facing-leaderboard)
* [weather-data-api](https://github.com/tinybirdco/weather-data-api)
* [materialized-views-workshop](https://github.com/tinybirdco/materialized-views-workshop)
* [mongodb-cdc-workshop](https://github.com/tinybirdco/mongodb-cdc-workshop)

## Workshops

* Kicked off my workshop series with a `Zero-to-Tinybird` set of content:
  * From Kafka to Analytics - April 2024
  * From Kafka to analytics - March 2024
* Master Materialized Views in Tinybird - September 2024
* Real-time MongoDB CDC with Confluent and Tinybird - September 2024
* Build performant analytics dashboards over Postgres data - August 2024
* Building Customer-Facing Dashboards for SaaS Products - June 2024
* Build Real-Time Leaderboards - June 2024
* Building Real-Time Anomaly Detection Systems - May 2024
I joined [Tinybird](https://www.tinybird.co/) in April 2023 as a developer advocate so you will see a set of Tinybird-related projects here (others on the Tinybird account). 

## Projects
  * [A collection of unsupervised methods for detecting anomalies in real-time data](https://github.com/tinybirdco/use-case-real-time-anomaly-detection). These recipes are written in SQL and are applied to streaming data in real-time. With this project, five types of anomalies can be detected:
    * **Out-of-range**: Identifying data points that fall outside a specified valid range.
    * **Rate-of-change**: Detecting abrupt changes or spikes in the rate of change of data.
    * **Timeout**: Flagging data points that cease to arrive within a predefined time interval.
    * **Interquartile Range (IQR)**: Using statistical methods to identify outliers based on the interquartile range.
    * **Z-score**: Applying standard deviation-based analysis to identify anomalies in data distribution.
* Designed a [hands-on workshop](https://github.com/tinybirdco/zero-to-tinybird) for learning to build API endpoints. This project includes an example set of Tinybird Data Source and Pipe definitions.
* [A set of weather data API endpoints designed and hosted on Tinybird](https://github.com/jimmoffitt/weather-api). 
* [A Python script that makes requests to the OpenWeatherMap API and streams the data to a Tinybird-hosted project](https://github.com/jimmoffitt/get_and_send_weather_data). The Anomaly Detection project includes another example data generator. 
  * Includes a [Python script for publishing to a Google Pub/Sub stream](https://github.com/tinybirdco/pubsub-website-events-poc), Tinybird resources for ingesting that stream and API Endpoints for publishing the data, and a Grafana dashboard JSON Model. 


