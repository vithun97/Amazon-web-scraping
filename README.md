# Amazon Data Scraping using Python
As a passionate data enthusiast, I recently undertook a project of extracting data from the Amazon website and converting it into a useful format for analysis, specifically in the form of a CSV file format. This project was a true test of my skills and a deep dive into the world of web scraping, HTML data structure, and the essentials required to conquer it all.  
  
I'm now excited to share my newfound knowledge and expertise, guiding others through a step-by-step process that's simple, yet incredibly impactful. Whether you're just starting out in the world of data or you're a seasoned pro, this guide will provide valuable insights and a rock-solid foundation for your next web scraping endeavor. So buckle up and get ready to harness the power of information with confidence and ease!  

## Data scraping is an important skill for data engineers to have for several reasons:

**1.Data Collection:** Web scraping enables data engineers to collect vast amounts of data from various sources, including websites, and convert it into a format that can be used for analysis and modeling.  
  
**2.Automation:** By automating the data collection process, data engineers can save time and increase efficiency compared to manual data collection methods.  
  
**3.Data Cleaning:** Web scraping often results in large amounts of messy and unstructured data, requiring data engineers to clean and transform the data into a usable format. This skill is essential for data engineers who need to ensure the quality of the data they work with.  
  
## Prerequisites

Jupyter Notebook  
Install the following packages:  
Beautiful Soup (bs4)  
Requests  
Pandas  

## Step 1: Understanding the Basic HTML Structure  
HTML stands for hypertext markup language, and the structure of the HTML code consists of the following elements:  
  
The document type definition, which tells the browser that this is HTML code  
HTML tags, which define the content of the website  
The body tag, where all the content is displayed  
## Step 2: Understanding the Structure of Amazon Website  
You can start by searching for any product on Amazon website and examine the code for the price of the product. You will see the following elements:  
  
Span, which is a tag available in HTML  
Attribute  
Content  
## Step 3: Installing Required Packages  
You will need to install the following packages in your local PC to execute this project:  
  
Beautiful Soup (bs4)  
Requests  
Pandas  
## Step 4: Sending Request to Amazon Website  
You will need to send a request from your local PC to Amazon website to get the HTML code and extract the necessary information. You will need to have the following information before sending the request:  
  
URL of the product page  
HTTP header, which contains the user agent  
## Step 5: Extracting Data  
Once you have the HTML code, you will use Beautiful Soup to extract the necessary information, such as the product title, price, and other details. The extracted data will then be converted into a CSV format using the Pandas package.  
  
## Final Output  
The final output of this project will be a CSV file containing the data extracted from the Amazon website.
