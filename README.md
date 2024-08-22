# 🚀 Web Scraping GitHub Topics

## 🌐 Introduction to Web Scraping

Web scraping is like mining for digital gold! It's a powerful technique that allows you to automatically extract valuable data from websites. Whether you're looking to gather insights, monitor trends, or analyze content, web scraping helps you efficiently collect large amounts of data from the web by parsing through HTML or XML content.

## 🎓 Introduction to GitHub and Problem Statement

GitHub is the go-to platform for developers to share and collaborate on code. But did you know it also features a treasure trove of information through its "Topics" page? Here, you'll find a wealth of categorized technologies, frameworks, and languages, all in one place.

### 🎯 Project Goal

The mission is clear: We'll scrape the top topics from GitHub’s Topics page and store crucial information—like topic titles, descriptions, and URLs—in a CSV file. We’ll then dive deeper into each topic, extracting details about the top repositories and saving that data for easy analysis.

## 🛠️ Tools and Technologies Used

- **Python**: Our trusty programming language, known for its simplicity and versatility.
- **Requests**: A Python library for effortlessly making HTTP requests and retrieving web content.
- **Beautiful Soup**: A library for parsing HTML and XML, perfect for extracting data from web pages.
- **Pandas**: A powerful data manipulation and analysis tool used to structure and save our scraped data into a CSV file.


## 🖱️ Getting Started
### Prerequisites
Ensure you have the following installed:
- **Python 3.x**
- **Jupyter Notebook**
- **Required Python libraries:**
  - *requests*
  - *BeautifulSoup*
  - *pandas*

## 📥 Download the Jupyter Notebook:
Download the **web_scraper.ipynb** file from [here](https://github.com/garv23r/python-web-scraping/blob/main/web_scraper.ipynb).

## 🏃 Running the Jupyter Notebook
- **Launch Jupyter Notebook**
- **Open the Notebook**
- **Execute the Cells:**
  - Follow the instructions in the notebook to run the cells.
  - Enter the required GitHub topic URLs when prompted.
  - The notebook will process the data and save the CSV files.

## 💼 Accessing the Data
After running the notebook, you will find a folder named **data** in your system's Downloads directory. 
<br>
This folder contains all the CSV files with the extracted repository data.

## 🧾 Example Output
The data folder will include CSV files with the following structure:
- **username:** GitHub username of the repository owner.
- **repo_name:** Name of the repository.
- **stars:** Number of stars the repository has.
- **repo_url:** URL of the repository on GitHub.
