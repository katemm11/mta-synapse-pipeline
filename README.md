# mta-pipeline

This Synapse pipeline fetches two datasets from the MTA Open Data Portal, Wi-Fi Locations and Subway Hourly Ridership, and uses Spark to clean the data and load it into Data Lake storage in Parquet format. The pipeline then loads the data into a data warehouse in Synapse, creating a dimension table for the station data called DimStation and a fact table for the ride data called FactRides.
