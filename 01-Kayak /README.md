# Objective 
Create on behalf of Kayak an application to recommend where people should plan their next holidays based on weather and hotel ratings.

## Main goals 🎯
- Use an **API** to get some information about the weather and coordinates of each city
- Create a spyder to crawl and scrape booking.com key data such as hotel name, booking.com page url, localisation, score given by users and a short text description of the hotel.
- Store the gathered data in a **S3** bucket 
- Make the data available in a data warehouse, transfer your data from **S3** to **AWS RDS**

# Methods & Tools 
_[Nominatim API](https://nominatim.org/release-docs/develop/api/Search/), [Openweather API](https://openweathermap.org/api/one-call-api), Pandas,  Scrapy, AWS S3, AWS RDS_