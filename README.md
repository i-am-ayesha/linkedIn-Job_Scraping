# 🚀 LinkedIn Job Scraper with Selenium
This project uses Selenium to scrape job postings from LinkedIn, extracting key details like job titles, companies, and links. It helps you analyze job market trends and draw valuable insights from it.

## 📌 Project Overview
This script scrapes job postings from LinkedIn and allows you to analyze the data for valuable insights. By following the steps, you’ll be able to:

1. Extract job title, company, location, and links to job postings.
2. Analyze trends in job availability and market demand.
3. Gain insights that can help you in your job search or professional growth.
## 🛠️ Tech Stack
* Python 🐍
* Selenium 🌐
* Pandas 📊
  
## ⚙️ How to Set Up and Run
#### 1. Clone the Repo:

`git clone https://github.com/your-repo/linkedin-job-scraper.git`

`cd linkedin-job-scraper `

#### 2. Set Up Virtual Environment (Optional but recommended):
 
`python -m venv venv`

`venv\Scripts\activate`

#### 3.Install Required Packages:
 
`pip install -r requirements.txt`

#### 4.Configure WebDriver (ChromeDriver/Firefox):

Download the compatible WebDriver for your browser here for Chrome, or here for Firefox.
Add the WebDriver to your PATH or specify its location in the code.
Run the Script:
 
`python scrape_jobs.py`

## 🔍 How It Works
* The script opens LinkedIn using Selenium.
* It scrapes job titles, companies, locations, and job URLs.
* The data is collected into a pandas DataFrame and saved to a CSV file for analysis.
## 📊 Features
* Scrape job postings from LinkedIn with job title, company, location, and URL.
* Export the scraped data to a CSV file for further analysis.
* Analyze job market trends using data analysis techniques in Python.
## 💡 Pro Tips
* **Stay Granular:** Narrow your search filters on LinkedIn for more specific data.
* **Expand Results:** Use the pagination feature to scrape multiple pages.
* **Analyze:** Use Pandas or any data visualization tool to derive insights from the collected data.
