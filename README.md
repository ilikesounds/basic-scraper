# basic-scraper
a mashup combining data from one site with data from another, and formatting from yet another to extract meaning from information.


This module will scrape the King County Public Health website and return data for a restaurant specified in the `INPSECTION_PARAMS` disctionary

When run it will store to a local file called results.html to limit the amount of queries directed to the website

The return of the module is a dictionary with score based on the infractions assigned by the health dept.
