# Capital IQ Transcript Crawler

## 1. Introduction

A web crawler based on Selenium and BeautifulSoup

## 2. Installation

### 2.1. Dependencies

* [ChromeDriver](https://chromedriver.chromium.org/downloads "link") 
* Selenium
* BeautifulSoup

### 2.2. A Capital IQ account

```python
browser = getBrowser(username = "YourAccount", password = "YourPassword")
```

You must have a account before run this web crawler.

### 2.2. Company ID

```python
getHTML(browser, IDs = [24107])
```
The ID of company "3Com Corporation" is 24107.

And the crawler will lead you to ->

https://www.capitaliq.com/CIQDotNet/Transcripts/Summary.aspx?companyId=24107
