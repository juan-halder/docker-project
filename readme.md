# Final goal
## Services
* Extractor API 
    * Retrieve data from an API
    * Data should be updating daily
    * Could live in Airflow
* Airflow
    * Trigger Extractor API
    * Trigger Load into DB
    * Trigger DBT-modelling
* DB (Postgresql)
    * Store the data retrieved through Extractor API
    * Target for DBT
* DBT
    * Transform raw data
    * Could live in Airflow
* Superset
    * Visualize transformed data in the DB


## How it should work

# First goal
* Run DBT against a DB

# Prerequisites
* Postgres DB