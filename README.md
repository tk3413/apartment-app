# apartment app

## observation

apartment price fluctuations are seasonal

## question

is the cost to rent an apartment dependent on the time of year?

## preliminary research

- cost to rent an apartment noticably trends higher during the 4 months that surround school graduation dates (nov - feb, may - aug)
- cost peaks around jan and jul
- additional move-in bonuses are more widely advertised during the remaining 4 months (mar - apr, sept - oct), likely due to fewer movers during this time


## hypothesis

apartment price trends upwards as the school semester comes to a close

## test

observational test to be conducted by scraping websites that advertise apartment move in prices in the northern virginia region and analyzing price data over the course of a year

overall data warehousing architecture is composed of the following four components all run on AWS:
- data ingestion scripts
- postgres database and RESTful server
- cron scripts to coordinate regular data pull and validations
- real-time visualization of data trends over time
