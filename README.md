# ETL Processes 🧙‍♂️🧙‍♂️

This project is a continuation of the ["Scraping Yelp with scrapy 🌶️"](https://github.com/julientoucoula17/scraping_yelp_with_scrapy) project on my github. What has been added in this project is the transform and load processes.
This constitutes a process an ETL (Extract, Transform, Load) which to put it simply consists of extracting data from a source (in our case, a website), cleansing it and loading it into a database which is usually referred to as a data warehouse.

ETL processes are set up to bring data together in one place so that anyone can use it for their own purposes. They are designed to ensure that the data is properly formatted and validated before it is stored. It becomes a source of truth for businesses. In large organizations, or if you have a lot of data sources, you will benefit greatly from implementing this type of process.

## Installation

If you want to manipulate databases, it is good for you to know about the Python library: sql-alchemy.
SQLAlchemy is the best way to manipulate relational databases using Python code. 
And you will need the Psycopg library which is the PostgreSQL database adapter.

      $ python3 -m pip install sqlalchemy psycopg2-binary
