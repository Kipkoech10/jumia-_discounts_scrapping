#Jumia Discount Product Scraper and Analyzer

## Project Overview

This project scrapes data from  Jumia to create a comprehensive list of products currently offered at a discount.
The scraped data is stored in a csv file, analyzed using Exploratory Data Analysis (EDA) techniques

## Features

- Web scraping of discounted products from a chosen e-commerce platform
- Data storage in a relational database
- Exploratory Data Analysis (EDA) on the collected data


## Technologies Used

- **Programming Language:** Python
- **Web Scraping:** Beautiful Soup, Selenium, Scrapy
- **Data Analysis:** Pandas, NumPy
- **Database:** excel

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ecommerce-discount-analyzer.git
   cd ecommerce-discount-analyzer
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Set up the database:
   [Include instructions for setting up and configuring your chosen database]

5. Configure the web scraper:
   [Provide instructions for setting up the scraper, including any necessary authentication or API keys]

6. Run the scraper:
   ```
   python scraper.py
   ```

7. Perform EDA:
   ```
   python eda.py
   ```

8. Launch the web interface:
   ```
   python app.py
   ```

## Project Structure

```
ecommerce-discount-analyzer/
│
├── scraper/
│   ├── __init__.py
│   ├── amazon_scraper.py
│   └── jumia_scraper.py
│
├── database/
│   ├── __init__.py
│   └── db_operations.py
│
├── analysis/
│   ├── __init__.py
│   └── eda.py
│
├── web_interface/
│   ├── __init__.py
│   ├── app.py
│   └── templates/
│
├── airflow/
│   └── dags/
│       └── scraper_dag.py
│
├── requirements.txt
├── config.py
└── README.md
```

## Usage

1. Run the scraper to collect data:
   ```
   python -m scraper.amazon_scraper  # or jumia_scraper
   ```

2. Perform Exploratory Data Analysis:
   ```
   python -m analysis.eda
   ```

3. Start the web interface:
   ```
   python -m web_interface.app
   ```

4. (Optional) Set up Apache Airflow for automated scraping:
   [Provide instructions for setting up and running Airflow]

## Contributing

Contributions to this project are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Create a new Pull Request

## License

[Choose an appropriate license for your project, e.g., MIT, GPL, etc.]

## Contact

[Your Name] - [Your Email]

Project Link: https://github.com/yourusername/ecommerce-discount-analyzer

## Acknowledgements

- [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Selenium Documentation](https://selenium-python.readthedocs.io/)
- [Scrapy Documentation](https://docs.scrapy.org/en/latest/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Apache Airflow Documentation](https://airflow.apache.org/docs/)
