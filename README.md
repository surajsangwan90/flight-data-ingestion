# Flight Data Ingestion using PySpark
## Problem Statement
This project focuses on processing domestic flight data using PySpark. This notebook helps you to load flight data, clean it, and add a new column for flight duration.

## Dataset
The dataset is a CSV file containing flight information such as:

- Flight ID
- Airline code
- Aircraft type
- Departure and arrival time
- Passenger count
- Flight distance
- Ticket price
- Flight status

 ## Tasks Performed

1. Loaded CSV file into PySpark DataFrame
2. Displayed schema and sample data
3. Counted total number of records
4. Filtered records with `passenger_count <= 0`
5. Added a new column `flight_duration_hours` using timestamp difference

## Technologies Used

- PySpark
- Databricks Community Edition

## How to Run

1. Clone the repository
   git clone https://github.com/surajsangwan90/flight-data-ingestion.git
   cd flight-data-ingestion
2. Open flight-data-ingestion.py in Databricks Notebook or run locally.
3. Data is also available. you can use the data locally or upload into dbfs
4. Run the script block line by line to see the output
