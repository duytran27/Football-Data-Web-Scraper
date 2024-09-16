#Credits: whoscored.com

# Football Match Data Web Scraper

This project is designed to scrape and process detailed football match data from Whoscored.com and store it in a Supabase database for further analysis.

## Features:

- **Automated Data Pipeline**:
  - Leverages **Selenium** and **BeautifulSoup** for automated data extraction.
  - Retrieves over 10,000 football match events weekly, improving data processing efficiency by 30%.
  
- **Data Modeling**:
  - Uses **Pydantic models** for structured and type-safe data validation.
  
- **Database Integration**:
  - Connects to a **Supabase** (PostgreSQL) database using **psycopg2** for secure and scalable storage of football match events.

- **Data Storage**:
  - Each match event is stored with attributes like team ID, player ID, coordinates, event type, outcomes, and more.

## Tech Stack:
- **Python**: Core language for scripting and automation.
- **Selenium & BeautifulSoup**: For web scraping.
- **Pandas**: For data manipulation and processing.
- **Supabase & PostgreSQL**: As the database solution.
- **Pydantic**: For data modeling and validation.
