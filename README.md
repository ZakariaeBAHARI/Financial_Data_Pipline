# Financial_Data_Pipline

This project demonstrates a data pipeline that fetches stock data from the Alpha Vantage API, streams it using Kafka, stores it in a PostgreSQL database, processes it with a Python script, and saves the processed data to a CSV file.

## Pipline Architecture

![Pipeline Architecture](https://github.com/ZakariaeBAHARI/Financial_Data_Pipline/blob/main/architecture.png)

## Project Structure

- `docker-compose.yml`: Docker Compose file to set up Kafka, Zookeeper, and PostgreSQL.
- `producer.py`: Script to fetch data from Alpha Vantage API and produce Kafka messages.
- `consumer.py`: Script to consume Kafka messages and store data in PostgreSQL.
- `process.py`: Script to process data from PostgreSQL and save it to a CSV file.


