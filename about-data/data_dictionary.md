
# Data Dictionary

This file describes each column in the `2017_Yellow_Taxi_Trip_Data.csv` dataset.

| Column Name              | Data Type | Description                                                                 | Allowed Values / Notes                          |
|--------------------------|-----------|-----------------------------------------------------------------------------|--------------------------------------------------|
| Unnamed: 0               | int64     | Row index or unique identifier (irrelevant for analysis)                  | Integer                                           |
| VendorID                 | int64     | Taxi provider (1=Creative Mobile, 2=VeriFone)                              | 1 or 2                                           |
| tpep_pickup_datetime     | object    | Date and time of trip start                                                | Timestamp string                                 |
| tpep_dropoff_datetime    | object    | Date and time of trip end                                                  | Timestamp string                                 |
| passenger_count          | int64     | Number of passengers in the taxi                                           | Integer (typically 1–6)                          |
| trip_distance            | float64   | Distance of the trip in miles                                              | Positive float                                   |
| RatecodeID               | int64     | Rate classification code                                                   | 1–6 (e.g., 1=Standard, 2=JFK, 5=Negotiated fare)  |
| store_and_fwd_flag       | object    | Whether the trip record was stored and forwarded later                     | "Y" or "N"                                       |
| PULocationID             | int64     | Pickup location ID (TLC zone identifier)                                   | Integer (TLC location code)                      |
| DOLocationID             | int64     | Dropoff location ID (TLC zone identifier)                                  | Integer (TLC location code)                      |
| payment_type             | int64     | Method of payment                                                          | 1=Credit Card, 2=Cash, 3=No Charge, etc.         |
| fare_amount              | float64   | Base fare amount                                                           | Positive float                                   |
| extra                    | float64   | Additional charges (e.g., rush hour)                                       | Float                                             |
| mta_tax                  | float64   | $0.50 MTA tax for all trips                                                | 0.5 usually                                       |
| tip_amount               | float64   | Amount of tip paid                                                         | Float (can be 0)                                  |
| tolls_amount             | float64   | Total toll amount for the trip                                             | Float                                             |
| improvement_surcharge    | float64   | $0.30 fee to support technology improvements                               | 0.3 usually                                       |
| total_amount             | float64   | Total fare charged (sum of all components)                                 | fare + extras + tolls + tip                      |
