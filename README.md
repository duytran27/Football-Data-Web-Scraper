# Football Web Scraper

This project is a Python-based web scraper designed to collect detailed football match events data from websites like WhoScored. The scraper automates the process of extracting key football match statistics and stores the data into a Supabase PostgreSQL database for further analysis and visualization.

## Features
- **Automated Scraping**: Scrapes football match events, including xG, possession, player, and team statistics.
- **Data Handling**: Utilizes BeautifulSoup for HTML parsing and Selenium for navigating dynamic content on the web.
- **Supabase Integration**: Data is automatically stored in a PostgreSQL database hosted on Supabase, making it easily accessible for further analysis.
- **Efficient Data Storage**: Uses Pandas and Pydantic models to structure, validate, and store match events.

## Technologies Used
- **Python**: Core language for writing the scraping scripts.
- **BeautifulSoup**: Used for parsing HTML content from the websites.
- **Selenium**: Automates the browser to interact with dynamic web pages and handle JavaScript content.
- **Pandas**: For data structuring and manipulation.
- **Pydantic**: Used to ensure data models are validated before storage.
- **Supabase**: Cloud-based PostgreSQL database for data storage and retrieval.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure you have a valid `.env` file for your Supabase credentials:
    ```env
    project_url=<your-supabase-url>
    project_api=<your-supabase-api-key>
    supabase_password=<your-supabase-password>
    ```
4. Run the script to start scraping match events:
    ```bash
    python scraper.py
    ```

## Credits
- Data sourced from [WhoScored](https://www.whoscored.com) and stored in [Supabase](https://supabase.com).

---

Feel free to contribute or raise issues for improvements.
