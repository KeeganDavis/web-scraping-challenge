# web-scraping-challenge
## Description
The part_1_mars_news notebook uses automatic browsing with splinter to open up the webpage and scrape the titles and the preview text of the articles on the page. The titles and preview texts are then added to a list of dictionaries and then displayed in the notebook before closing the browser. The part_2_mars_weather notebook uses automatic browsing with splinter to scrape the contents of the table on the page. The data from each row is then added to a pandas dataframe. This dataframe is then analyzed to see how many months exist on mars, how many Martian days worth of data is in the table, the coldest and warmest months on Mars, the months with the highest and lowest atmospheric pressure, and approximate how many Earth days exist in a year on Mars. The dataframe is then exported to a csv and the browser is closed.
## Requirements 
The requirements for this repository are matplotlib, pandas, bs4, and splinter.
## Installation
Clone the repository: git@github.com:KeeganDavis/web-scraping-challenge.git
## Usage
To run the part_1_mars_news notebook, select a kernel and run all code blocks to scrape the titles and preview texts. To run the part_2_mars_weather notebook, select a kernel and run all code blocks to scrape the table data, create a dataframe, analyze the data and generate figures, and export the dataframe to a csv.