#  A clean and interactive dashboead by using power BI of IPL_2025 
### output:
<img width="1268" height="700" alt="image" src="https://github.com/user-attachments/assets/38fa0a39-375a-4636-b0aa-ef231504bd8b" />

## process :
### Extract & Understand the Dataset:

Check for the following common IPL datasets:

 - matches.csv → match-level details (teams, date, winner, etc.)
 - deliveries.csv → ball-by-ball data (bowler, batsman, runs, extras)
 - player_stats.csv or similar
 - orange_cap.csv
 - purple_cap.csv
 - Sheet1 (used  for team logo and captian's image and information )

### Data Cleaning (in Power Query)
•	Remove null/blank rows.
•	Convert data types (e.g., date → Date/Time)
•	Remove duplicate rows.
•	Join datasets 
 Established relationship between multiple tables

 ### EDA (Exploratory Data Analysis)
  Use Power BI visuals to perform the following:
- Match-Level Insights
- Total matches played
- Total no. of vanues
- Wins by each team (bar chart)
-	Toss decisions & outcomes
- Matches per venue (treemap)
- Top 2 Man_of_the_match player 
- orange cap stats with multi-row-card with picture 
- purple cap stats
- player who hit most 6's
- multi-card visulization of player who hit most 4's
- Top 10 stricker


## Future Enhanchment:

#### Web Scraping to Enrich Dataset
Use Python (BeautifulSoup or Selenium) to fetch live/player info from:
- https://www.iplt20.com
- https://www.espncricinfo.com
- https://www.wikipedia.org
LIKE  --Scraping Player Profiles and use profile picture 



 #### Add page navigation buttons 
 #### Add season wish informative dashboad
 #### Responsive for Moblie aslo 



      
      
 

