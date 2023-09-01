# Scrapping-LinkedIn-job-details
In this project    
We send an HTTP GET request to the LinkedIn URL.
We parse the HTML content using BeautifulSoup.
We select the job postings based on the appropriate HTML elements and classes.
We iterate through the job postings, filter them based on the job title containing "Software Developer," and collect the relevant data.
We create a DataFrame from the collected data using pandas.
We save the DataFrame to an Excel file named linkedin-jobs.xlsx.
Make sure that the required libraries (requests, BeautifulSoup4, and pandas) installed before running the script. 
