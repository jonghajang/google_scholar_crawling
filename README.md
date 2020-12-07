# google_scholar_crawling


![capture](https://user-images.githubusercontent.com/66405055/101364373-d5c42580-38e5-11eb-97f9-2b59e3a0ddcb.PNG)

## Introduction

It is a code that curls article information on Google's scholar site using Python's request and BeautifulSoup.
The imported information is saved in the form of a csv file, making it easy to save only the information you want.


* [request](https://pypi.org/project/requests/)
* [BeautifulSoup](https://pypi.org/project/beautifulsoup4/)
* [DateTime](https://pypi.org/project/DateTime/)
* [pandas](https://pypi.org/project/pandas/)
* [re](https://pypi.org/project/re2/)
* [time](https://pypi.org/project/times/)


## How to Use

> 1. Enter the keyword you want in Google's scholar Search.

> 2. Copy the URL and place the url in the part that specifies the code.

> 3. In Code part of num_article, enter the number of desired articles (default = 10).

> 4. After running, specify the csv output name in code of df_filename. (default = crawling_result)
