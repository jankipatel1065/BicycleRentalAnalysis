# Bicycle Rental Analysis 🚴‍♀️📊

## Overview

Explore how different rider types (casual vs. annual members) use bike share services differently through in-depth analysis and visualization.

## Libraries Used

- `tidyverse`
- `dplyr`
- `tidyr`
- `skimr`
- `tibble`
- `janitor`
- `lubridate`

## Project Steps

### Step 1: Processing Data

- Imported and integrated data from multiple CSV files.
- Converted data types and handled missing values.
- Created new columns for analysis, such as Hour_of_Day, Weekday, Day_of_Month, and Month.

### Step 2: Cleaning Data

- Removed rows with NA values.
- Handled outliers in trip duration.
- Renamed columns for better understanding.
- Sorted and ordered the data.

### Step 3: Analysis/Visualization

- Explored rider type distribution, bike type preferences, and start time tendencies.
- Visualized key insights through various plots and charts.

## Key Insights

1. **Rider Distribution:**
   - 63.62% of riders are annual members, while 36.38% are casual riders.

2. **Bike Type Preferences:**
   - Annual members prefer classic bikes over electric bikes, while casual riders are the only group to use docked bikes.

3. **Start Time Tendencies:**
   - Annual members exhibit consistent start times, likely for commuting, while casual riders have longer average trip durations.

## Visualizations

- [Count of Riders](#visualization-1-count-of-both-riders)
- [Bike Type Preferences](#visualization-2-total-rides-of-different-bike-type-of-both-the-rider-groups)
- [Start Time Tendencies](#visualization-3-stating-time-of-both-riders-on-hourly-basis-on-a-day)
- [Starts Per Hour](#visualization-4-number-of-starts-per-hour-of-both-the-riders-group)
- [SPH By Weekday](#visualization-5-number-of-starts-per-hour-every-day)
- [Start Time Tendencies By Weekday](#visualization-6-stating-time-of-both-riders-group-every-day)
- [Rides Per Day By Rider Type](#visualization-7-total-rides-per-day-relative-to-each-rider-type)
- [Rides Per Month By Rider Type](#visualization-8-total-rides-per-month-relative-to-each-rider-type)
- [Average Daily Trip Duration](#visualization-9-average-trip-duration-everyday)

## Conclusion

Gain valuable insights into rider behavior and preferences, guiding decisions for improving bike share services.

Feel free to explore the interactive visualizations and dive deep into the world of bike share data analysis!
