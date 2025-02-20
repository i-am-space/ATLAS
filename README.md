# ATLAS
- A graphical analysis of the game Atlas

## ASSUMPTIONS
- List of all countries with names and ISO 3166-1 codes in all languages and all data formats
- For the sake of accuracy and faithfullness to the original Atlas game, I'll be bending the rules of "officially recognized" a little bit to include approximately 55 other countries that would otherwise not be here. After all, these are perfectly valid places to name in a real game of Atlas.
- I didn't take the top 500 most populated cities exactly, I took the first 500 cities sorted by population that would actually be present in the graph, so that my resultant graph would actually have 500 nodes.
-

## DIRECTORY STRUCTURE
```
ATLAS
├── data
│   ├── cities_and_countries.csv
│   ├── cities.csv
│   ├── country.csv
│   ├── worldcities.csv
├── .gitignore
├── Cities.ipynb
├── CitiesAndCountries.ipynb
├── CommunityDetection.ipynb
├── Countries.ipynb
├── DataPrep.ipynb
├── LinkPrediction.ipynb
├── README.md
```