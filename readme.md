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
    * Show data documentation
    * Could live in Airflow
* Superset
    * Visualize transformed data in the DB


## How it should work
1. Install docker, docker-compose
1. Download/clone the repository
1. Run `docker-compose up`
1. Go to Airflow
    1. Trigger the API extractor
    1. Trigger upload to DB
    1. Trigger DBT modelling
    1. Trigger DBT documentation
1. Go to Superset
    1. Visualize created modelling
