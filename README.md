# Amazon Web Scraping With Python

## Project Overview
This project aims to automate the process of monitoring product prices on Amazon using Python. By leveraging web scraping techniques, the project collects and analyzes data on product pricing, helping data analysts track price trends and identify potential cost-saving opportunities. The data is extracted and stored in a structured format, enabling further analysis and visualization. Additionally, the project includes functionality to send email notifications when significant price changes occur, ensuring timely updates for better decision-making. The tools used in this project include requests and BeautifulSoup for web scraping, pandas for data manipulation, and standard libraries for email automation.

## Resources

### Data Source
- [Amazon Product Link](https://www.amazon.com/Funny-Data-Systems-Business-Analyst/dp/B07FNW9FGJ/ref=sr_1_3?dchild=1&keywords=data%2Banalyst%2Btshirt&qid=1626655184&sr=8-3&customId=B0752XJYNL&th=1)

### Software
- [Jupyter Notebook](https://github.com/priyanka-velu/Amazon_Web_Scraper/blob/main/Amazon_Web_Scraping_Python_Pandas.ipynb)
- Python (Pandas)

## Web Scraping Steps

### Connect to Website

![Connect to Website](https://github.com/user-attachments/assets/845dae6f-c3e6-4f61-a402-90ba69188382)

- Use the requests and BeautifulSoup libraries to connect to the Amazon website and fetch the product page.

### Add Title, Datetime, CSV, and Pandas

![Add title, datetime, csv, and pandas](https://github.com/user-attachments/assets/8d9a7050-b8b6-4606-b8f3-6d54df35291f)

- Extract the product title, current date and time, and save the data to a CSV file using the pandas library.

### Append Data to CSV

![Append Data to csv](https://github.com/user-attachments/assets/41193b5b-a97d-493e-9638-b4df2198c70c)

- Update the CSV file with new data by appending the latest product information.

### Create Function to Check Price

![Create Function to Check Price](https://github.com/user-attachments/assets/4425e1cc-ba8d-4d81-8197-96a027acad6c)

- Define a function that checks the product's price and logs it for monitoring purposes.

### Test Function

![Test Function](https://github.com/user-attachments/assets/b3317a19-bcb0-4e6c-a522-c9cbedb25e1c)

- Run the function to verify it correctly retrieves and logs the product's price.

### Create Function to Send Email

![Create Function to Send Email](https://github.com/user-attachments/assets/f0848711-e933-4a5a-9562-4f1eaba4c1dc)

- Implement a function that sends an email notification if the product price drops below a specified threshold.
