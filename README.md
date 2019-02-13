# Scrape-golf-data-from-web

This markdown file scrapes the PGA Tour website for the desired statistics that will be used for analysis and creates a single data frame that includes all 18 stats for 463 players.

The markdown creates a scraper to scrape the needed data from www.pgatour.com/stats. First the scaper is created, then the data for each year and stat is cleaned up and assigned to a corresponding variable. Finally, all stats for each player and year are merged into one data frame for each year. To use the function to get different stats for different years: get_all_data(stat, year) - where stat is corresponding stat number from website (ie. "127") and year is year of data desired (ie. 2018).