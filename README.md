# Is Magic: The Gathering becoming too complex
The oldest trading card game in the world turns 30 next year

## Data
Data analysis can be found in sets.ipynb, art.ipynb and text.ipynb

| Filename | Description |
| :----------- | :----------- |
| all_sets.csv | A list of all Magic products, 1993-present |
| expansions.csv | A filtered list of only expansion sets |

## Relevant figures

### Number of cards in standard
### Number of cards in commander
### Average number of cards in all sets
### Number of Magic products by year
### Number of Magic cards by year
### Average number of cards in a core or expansion set
### Number of Magic products by year in a core or expansion set
### Number of Magic cards by year in a core or expansion set
### Time between sets
### Percent change in number of cards first decade to current decade
### Percent change first set to most recent standard set
### Percent change first set to most recent set
### Percent change first expansion set to most recent standard set
### New products since March 2020
### New cards since March 2020
### Cards released in 1993
### Cards released in 2021
### Cards released in 2022
### Percent change 1993 to 2021
### Percent change 1993 to 2022
### Number of cards with showcase frames
### Number of keyword abilities
### Number of keyword abilities since March 2020
### Cards reprinted the most times
### Top ten longest card names
### Average length of text on cards, 2020-present
### Average length of text on cards, 1993-present
### Average length of text on cards, 2003-2012 vs 2013-2022
### Average length of text on cards by year

## Charts

### Revel in Riches
https://datawrapper.dwcdn.net/NoPbA/6/

## What I learned / Challenges
- It was not immediately obvious how to access all the data in the API
- Recieved a warning on `IOPub data rate exceeded` in Jupyter notebook
- The bulk oracle text file was more than 100 MB in size
- Had some challenges iterating over rows in the data table
- Would have liked to use NLTK or other text analysis tools to look for unique words in the oracle text
- It was challenging to determine fair comparisons, i.e. year-to-year, decade-to-decade, all cards, core and expansion sets only
- "Complexity" is a really abstract thing to measure and needed a more concrete number. Card text length is only one dimension of complexity.
- How to export chart in Datawrapper so that I could animate a segment of a line after a certain date
- It does not appear that you can change the style of chart labels in Datawrapper, i.e. ticks and color of labels on the X and Y-axis
- Card objects are not the same as cards

## Other notes
- When doing sanity checks, some of the queries to Scryfall did not match up to my analysis in Jupyter notebook
- Older cards have some of the longest oracle text in Magic due to reminder text explaining what the old abilities do, i.e. Banding
- Reminder text skews the text length of cards
- Cards have different versions some with reminder text and some without
- Would have liked to find other ways to visualize complexity