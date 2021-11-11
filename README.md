# hw_03 ebay scraping
1. what my ```ebay-dl.py``` file does

basically, you can use my program to search items on ebay and it will scrape information off each of the items. the output contains the name, price, status, shipping cost, numbers sold, and status of all the ebay items on each page (from 1-10). it displayed the infomation in json and csv files, based on what you input into the terminal.

2. how to run the file

this is the code you have to input into the terminal to generate the json files. in the quotations, you enter the item you would like to search. below are the three commands i used to generate the information about my three items.
```
python3 ebay-dl.py 'pokemon'
python3 ebay-dl.py 'stuffed animal'
python3 ebay-dl.py 'weights'
```
i also added the csv flag in order to generate the csv files as well.
```
python3 ebay-dl.py 'pokemon' --csv
python3 ebay-dl.py 'stuffed animal' --csv
python3 ebay-dl.py 'weights' --csv
```

and if you wanna try this yourself, click [here](https://github.com/mikeizbicki/cmc-csci040/tree/2021fall/hw_03)!

