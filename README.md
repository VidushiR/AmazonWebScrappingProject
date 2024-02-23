# AmazonWebScrappingProject
Amazon Web Scrapping Project

Used BeautifulSoup libray along with other libraries - requests, time, datetime and smtplib.
# Connect to Website and pull in data from amazon URL 
Got the machine specific information such as (User Agent information) from this url - https://httpbin.org/get

# Clean up the data a little bit
# Create a Timestamp for your output to track when data was collected
# Create CSV and write headers and data into the file
# Run below commands only once, otherwise it will delete all the data. Thats why commented below commands to not run it again and again.
    # with open('AmazonWebScraperDataset.csv', 'w', newline='', encoding='UTF8') as f:
    # writer = csv.writer(f)
   # writer.writerow(header)
   # writer.writerow(data)

now import pandas as pd and #Now we are appending data to the csv
#Combine all of the above code into one function
# Runs check_price after a set time and inputs data into your CSV
# If uou want to try sending yourself an email (just for fun) when a price hits below a certain level you can try it
# out with this script


