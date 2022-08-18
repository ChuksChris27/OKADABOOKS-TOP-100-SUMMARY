## OKADABOOKS TOP 100 BEST SELLERS SUMMARY
I scrapped the okadabooks best sellers cateogry to gain insights from the website.
The website is a dynamic one, therefor using regular REQUESTS python library wouldn't work perfectly.
I opted to use SELENIUM to scrape my urls, price, and indexes, and ran a for loop to get my title, author, ratings and download count.

## Library Used
- Pandas
- Selenium
- Beautiful Soup
- Matplotlib

### Data Cleaning
- I changed Title and Author from lower case to Title Case
- I categorised the rating into 5 different classes
- I changed splitted the Title string to remove 'Okadabooks'from title
- I subsetted for the first 100 rows

### LIMITATIONS/PROBLEMS ENCOUNTERED
- Using the selenium package for the first time, I had to choose the best element to call from the website source
- The for loop ran for a long time

# CONCLUSION
- The Okadabooks website was successfully scrapped and all data needed was collated
- Different parameters was gathered and plotted using POWER BI
