# Rosbank Happy Data Year Competition
https://boosters.pro/champ_21

My solution for LB #16 of 292

1. OpenStreetMap for geo features (distances to tagged offices, parkings, cemeteries etc.) using osmread
2. Russian Post website scraping (Postal codes, address normalization) using Selenium Webriver)
3. Yandex Geocoder API (adresses to lat/lon, administrative areas, city centers) using requests and Beautiful Soup
4. Scraping Alfa-Bank website (>20k ATMs incl. partners, JSON) using requests
5. Sberbank ATM locations from Excel file (>68k in >33k locations)
6. Official data on average region salary and population, gensim/FastText to deal with misprints and abbreviations in Excel files
7. Mean/Target encoding
8. 4 folds lightgbm

Many ideas were borrowed from
https://boosters.pro/uploads/champs/champ_21/baseline.ipynb
https://github.com/datasouls/mts-geohack/blob/master/Geohack112_StarterKit.ipynb
