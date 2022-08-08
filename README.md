# Is Magic: The Gathering becoming too complex
The oldest trading card game in the world turns 30 next year

## Data
Data analysis can be found in sets.ipynb, art.ipynb and text.ipynb

| Filename | Description |
| :----------- | :----------- |
| all_sets.csv | A list of all Magic products, 1993-present |
| expansions.csv | A filtered list of only expansion sets |

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