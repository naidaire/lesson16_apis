## Getting Data and APIs

### Part 1: Intro to Web Services & APIs

#### Learning Objectives
_After this lesson, you will be able to:_
- Identify relevant HTTP Verbs & their uses.
- Describe Application Programming Interfaces (APIs) and know how to make calls and consume API data.
- Access public APIs and get information back.
- Read and write data in JSON format.
- Use the `requests` library.

---

### Part 2: Webscraping in Class

#### Learning Objectives

- Revisit how to locate elements on a webpage
- Aquire unstructure data from the internet using Beautiful soup.
- Discuss limitations associated with simple requests and urllib libraries
- Introduce Selenium as a solution, and implement a scraper using selenium

---

#### Prerequisites

- Have Beautiful Soup installed
> ```pip install bs4```

- Have Selenium installed
> ```pip install selenium```

- Have [FireFox browser](https://www.mozilla.org/en-US/firefox/new/?utm_source=google&utm_medium=cpc&utm_campaign=Firefox-Brand-US-GGL-Exact&utm_term=firefox&utm_content=A144_A203_A006336&gclid=Cj0KEQjwnPLKBRC-j7nt1b7OlZwBEiQAv8lMLJUyReT6cPzSYdmEA6uD3YDoieuuuusddgAU7XH6smEaAoje8P8HAQ&gclsrc=aw.ds) installed.

- Have GeckoDriver installed.
> ```brew install geckodriver```

---

## Resources

- Find elements [Selenium docs](http://selenium-python.readthedocs.io/locating-elements.html#locating-elements)
- Using Selenium to enter website information [demo](http://thiagomarzagao.com/2013/11/12/webscraping-with-selenium-part-1/)
- Python regex tester [here](http://pythex.org/)
- Setup Firefox profile [here](http://stackoverflow.com/questions/9907492/how-to-get-firefox-working-with-selenium-webdriver-on-mac-osx)


### Part 1: Lesson Guide
TOTAL (170 min)
- Introduction to APIs
- What is an API? (10 min)
- Famous APIs (5 min)
    - Facebook
    - Yelp
    - Echonest
- Web APIs (5 min)
- Making API calls (5 min)
- HTTP (10 min)
- Web applications (5 min)
- Demo: HTTP (10 min)
- Independent practice: HTTP (10 min)
- HTTP Request (10 min)
    - HTTP Request methods
    - HTTP Request structure
- HTTP Response (5 min)
    - Response types overview
- JSON (10 min)
- Independent practice: validating JSON (10 min)
- Guided practice: pulling data from APIs (35 min)
    - Example 1: Star Wars (15 min)
    - Submit queries to the API (10 min)
    - Example 2: Google Geocode (10 min)
- OAuth (15 min)
- Independent practice: python APIs (30 min)
- Closing questions