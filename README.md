# Python.DynamicWebScrape.capitalbikeshare
Python3 script to execute a dynamic scrape of all archived csv data on bike share usage into a single data frame for analysis.

Leverages BytesIO to open zip files into IO and read csv files directly into a dataframe without downloading each file. 

Created and tested on MacOS Mojave v10.14.6 via Jupyter 5.7.8 running Python 3.7.3 from Anaconda 1.9.7.

Recommend opening this script in Jupyter and running cells in sequence. 

Users adopting this code should download Chrome Web Driver along with libraries as specified in the code. 

**Key Acknowledgements and References:
1. iterating over and appending dataframes: 

1.a. https://stackoverflow.com/questions/48888001/creating-multiple-dataframes-with-a-loop/48888621

1.b. https://stackoverflow.com/questions/20906474/import-multiple-csv-files-into-pandas-and-concatenate-into-one-dataframe

2. using selenium with chrome web driver to pass data to beautifulsoup: 

2.a. https://medium.com/ymedialabs-innovation/web-scraping-using-beautiful-soup-and-selenium-for-dynamic-page-2f8ad15efe25

2.b. https://www.geeksforgeeks.org/implementing-web-scraping-python-beautiful-soup/

3. getting zip files and opening directly into a pandas df without downloading to disk: https://stackoverflow.com/questions/5710867/downloading-and-unzipping-a-zip-file-without-writing-to-disk


**I read dozens of articles during the development of this code so if I am missing a reference, please let me know. 
