# Web-Scraping-Challenge
Module 10 Challenge: Web Scraping

# Main Goal
Extract information from [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html) and produce the following deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

# Technologies
- Python
- Pandas
- Jupyter Notebook
- Beautiful Soup
- Splinter
# Deliverable 1

I completed the following steps to produce deliverable 1:

- I created a beautifulsoup object to extract all text elements from the webpage.

- After extracting the title and preview pair, I stored them into a python dictionary.

- I appended the dictionary to a list.

# Deliverable 2

I completed the following steps to produce deliverable 2:

- I used beautifulsoup to scrape data in the HTML table.
- Assembled the scraped data into a pandas dataframe.
- Converted the data into the appropriate datatypes.
- Analysed the dataset to answer the following questions:

  1.) How many months exist on Mars?
  
  2.) How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  
  3.) What is the average low temperature by month?
  
  - bar chart visual:
    
  ![mars_temp_img](https://github.com/Natphipps/Web-Scraping-Challenge/assets/130694752/234cd3b0-0976-47ae-af98-55903ef8dae8)

  4.) What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  
   - bar chart visual:
     
![image](https://github.com/Natphipps/Web-Scraping-Challenge/assets/130694752/b3c0188d-5d2f-4e10-9053-482a6d3e8b50)

  4.) Find the average pressure by Martian month.
  
  - bar chart visual:
    
    ![image](https://github.com/Natphipps/Web-Scraping-Challenge/assets/130694752/81442fd4-ab96-40f8-849e-c1b6d6bb80a4)
    
  5.) About how many terrestrial (Earth) days exist in a Martian year?
  
  - line plot visual:
    
      ![image](https://github.com/Natphipps/Web-Scraping-Challenge/assets/130694752/81a66628-57da-4114-8a08-1a3784d12eb6)

- Lastly, I explorted the created dataframe to a csv. The header explanation is as follows:

  -  id: the identification number of a single transmission from the Curiosity rover
  -  terrestrial_date: the date on Earth
  -  sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
  -  ls: the solar longitude
  -  month: the Martian month
  -  min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
  -  pressure: The atmospheric pressure at Curiosity's location

# Resources

- Used class activities from the gitlab to help me with this assignment.
- I used stack overflow questions to help me with syntax and errors I ran into.
- I used the matplotlib documentation to help me with charts.
