# Amazon Data Scraping using Python
This is a step-by-step guide to scraping data from Amazon website and converting it into a CSV file format. The guide will explain everything in a simple manner, from understanding web scraping, understanding the structure of HTML data, and discussing some of the prerequisites required for this project.

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
