# Weather Dataset Analysis Project

## Overview

This project involves analyzing a weather dataset to answer a series of questions using both Python and SQL. The dataset includes various weather-related parameters such as wind speed, visibility, relative humidity, and weather conditions.

## Dataset

The dataset used for this analysis includes the following columns:
- `Date/Time`: Date and time of the observation
- `Temp_c`: Temperature in Celsius
- `Dew point_Temp_C`: Dewpoint temperature in Celsius
- `Rel_Hum_%`: Relative humidity percentage
- `Wind Speed_km/h`: Wind speed in km/hr
- `Visibility_km`: Visibility in km
- `Press_kPa`: Atmospheric pressure in kPa
- `Weather`: Describes the weather conditions (e.g., Clear, Snow, etc.)
  
## Tasks Completed

1. **Identified Records with Clear Weather:**
   - Extracted records where the weather condition was 'Clear'.

2. **Wind Speed Analysis:**
   - Counted the number of instances where the wind speed was exactly 4 km/hr.

3. **NULL Values Check:**
   - Checked for NULL values in the dataset to ensure data integrity.

4. **Column Renaming:**
   - Renamed the column 'Weather' to 'Weather_Condition' for clarity.

5. **Mean Visibility Calculation:**
   - Calculated the average visibility across the dataset.

6. **Filtered Records Based on Conditions:**
   - Identified records with wind speed greater than 24 km/hr and visibility of 25 km.

7. **Mean Values by Weather Condition:**
   - Computed the mean values of each column for different weather conditions.

8. **Complex Filtering:**
   - Found records where the weather was clear and relative humidity was greater than 50, or visibility was above 40.

9. **Snow Weather Conditions:**
   - Determined the number of unique weather conditions that include snow.

## Tools Used

- **Python:** For data manipulation and analysis using the pandas library (All tasks).
- **SQL:** For querying the dataset and performing aggregation and filtering operations (Tasks 4, 5, 8, and 9).

## Instructions

1. Load the dataset into your Python environment or SQL database.
2. Execute the provided Python scripts or SQL queries to obtain the required results.
3. Review the outputs to validate the answers to the questions posed.

