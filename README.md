**Recommend a Driver's Lifetime Value** (i.e., the value of a driver to Lyft over the entire projected lifetime of a driver).

This repository contains the analysis of Lyft driver data to determine the driver's lifetime value (LTV) and provide actionable recommendations for the business. The analysis is based on three CSV files provided with the data.

## Data Description

### `driver_ids.csv`

- `driver_id`: Unique identifier for a driver.
- `driver_onboard_date`: Date on which the driver was onboarded.

### `ride_ids.csv`

- `driver_id`: Unique identifier for a driver.
- `ride_id`: Unique identifier for a ride completed by the driver.
- `ride_distance`: Ride distance in meters.
- `ride_duration`: Ride duration in seconds.
- `ride_prime_time`: Prime Time applied to the ride.

### `ride_timestamps.csv`

- `ride_id`: Unique identifier for a ride.
- `event`: Describes the type of event. Possible values:
  - `requested_at`: Passenger requested a ride.
  - `accepted_at`: Driver accepted a passenger request.
  - `arrived_at`: Driver arrived at the pickup point.
  - `picked_up_at`: Driver picked up the passenger.
  - `dropped_off_at`: Driver dropped off a passenger at the destination.
- `timestamp`: Time of the event.

Assumptions:

- All rides in the dataset occurred in San Francisco.
- All timestamps in the dataset are in UTC.


## Analysis and Recommendations

After exploring and analyzing the data, the analysis will focus on the following aspects:

1. **Driver's Lifetime Value (LTV) Recommendation**
2. **Factors Affecting a Driver's Lifetime Value**
3. **Average Projected Lifetime of a Driver**
4. **Segments of Drivers with Higher Value**
5. **Actionable Recommendations for the Business**

For a detailed analysis and findings, please refer to the complete report provided in this repository.

