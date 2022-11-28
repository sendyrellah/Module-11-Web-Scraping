# Module-11-Web-Scraping
Mission to Mars

## Overview of Project
An aerospace company wants to receive information about news about Mars and the climates on Mars. In this direction, a study was conducted by collecting information from open sources.

## Analysis  
Using Splinter, Selenium and WebDriverManager to access the target website with Splinter. Then with Beautiful Soup, we follow the HTML commands of the page and obtain the information requested from us. For this study, what is requested from us is the Mars News website. It is possible to access this study from the "mars_data_challenge_part_1.ipynb" section. There are articles in the HTML page and these articles can be obtained in lists with their id's, titles and descriptions. Article lists are exported in JSON format. JSON format is used to export to MongoDB database.
In another study, Jupyter Notebook named "mars_data_challenge_part_1.ipynb", Mars temperature data was accessed in two ways using Splinter, Selenium and WebDriverManager, Beautiful Soup and read_html formats. While accessing the data in both ways is simple, read_html is completed in less time. At the beginning of this study, Mars temperature data on the website was shown as DataFrame and pandas library was used to read HTML. In the study, in both methods, data can be obtained as DataFrame and transferred to MongoDB database. Finally, the cleaning process was performed on the MongoDB database, and the study was terminated.

## Results 
In this study, the temperature values obtained with the help of bar charts are visualized on a monthly basis. In this way, the lowest and highest temperature data and monthly differences in atmospheric pressure values can be easily analyzed. 