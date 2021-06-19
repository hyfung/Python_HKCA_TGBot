# Python_HKCA_TGBot

## Motivation
When the scheme came out everyone is asking questions repetitively so I thought could I do something to help.

I wrote this bot to help Hongkongers to help themselves for application of Open Work Permit.

I also added some daily life features like crawling currency rate, COVID stats etc.

The bot was first hosted on my Jetson Nano at home but later migrated to Google Cloud Platform.

People can gather information interactively by using bot commands defined by me.

Including but not limited to
- Readme
- Application Procedures
- Deadline Calculation
- NOC CLass lookup

## Functionality

### Application Guide
Pretty much everything you need to apply Open Work Permit

![alt text](https://github.com/hyfung/Python_HKCA_TGBot/blob/white/images/help.png "")

### Application Deadline Calculation
Deadline calculation released by Canadian Government is tricky so I wrote a function to accept an input, the bot will calculate the rest for you

- You must apply for OWP before
- You must seek a job before
- You must apply for PR before

![alt text](https://github.com/hyfung/Python_HKCA_TGBot/blob/white/images/date.png "")

### Realtime Currency Exchange Rate
- Crawl Yahoo! for currency rate
- Parsed the page with Beautifulsoup4
- Cached the result for a few minutes

![alt text](https://github.com/hyfung/Python_HKCA_TGBot/blob/white/images/currency.png "")

### Realtime Canada COVID Stats
Crawled the Canadian Government stat API for data

![alt text](https://github.com/hyfung/Python_HKCA_TGBot/blob/white/images/covid.png "")

### NOC Class Lookup
Previously people were guessing if only NOC 0AB is eligible and I wrote this to assist them in NOC lookup

![alt text](https://github.com/hyfung/Python_HKCA_TGBot/blob/white/images/noc.png "")
