# Web-Scrape-an-Interactive-Site-Python-
Scrapes the Minnesota marriage website but can be altered to parse through any site. This code was created for a research project. Looking for tips on making the code more efficient.

This code should run through. I reccomend running it (with the headless option turned off) to see how it works. The concept is pretty simple. Essentially, this website only shows 50 records at a time and I want to scrape all of them. You can set filters which triggers some javascript to update the html (I think). This code is essentially a bot. It loads up the site, clicks on the filters to scrape every thing on the site. The filters I use are: county, last name, first name, middle name. It parses through each letter in the alphabet and only scrapes if less that 50 records are returned (so I make sure I get them all). For example, if the search 'A' returned more than 50, it'd try 'AA' next and so on.

It should be noted I have limited experience with Python. This code is not super efficient and a pain to look at. I welcome any tips to improve the code.

Thanks.
