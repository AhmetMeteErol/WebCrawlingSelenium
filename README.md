# Web Crawling via Selenium
We have selected the website "https://ranking.glassdollar.com/" for our web crawling operation.

The website has a pop-up cookies welcomer. That's why, we couldn't use directly the library "BeautifulSoup". We needed to use Selenium in order to close pop-up. Then we could see our target informations' data in html.

Yet, to get companies url, I tried to click and get the current url. But in that point, I couldn't return my original page.
