# Skills and libraries:

Pandas, Matplotlib, correlation detection, plotting

# Project Description

At your disposal are the data of the Yandex Real Estate service — an archive of ads for several years about the sale of apartments in St. Petersburg and neighboring settlements.
Your task is to perform data preprocessing and study them to find interesting features and dependencies that exist in the real estate market.
The database contains two types of data about each apartment: user-added and cartographic. For example, the first type includes the area of the apartment, its floor and the number of balconies, the second — the distance to the city center, the airport and the nearest park.

# The purpose of the study

According to the ads for the sale of apartments in St. Petersburg and the region, determine the parameters that affect the value of real estate.

# Data description 

- airports_nearest — distance to the nearest airport in meters (m)
- balcony — number of balconies
- ceiling_height — ceiling height (m)
- cityCenters_nearest — distance to the city center (m)
- days_exposition — how many days the ad was placed (from publication to removal)
- first_day_exposition — date of publication
- floor — floor
- floors_total — total floors in the house
- is_apartment — apartments (boolean type)
- kitchen_area — kitchen area in square meters (m2)
- last_price — price at the time of withdrawal from publication
- living_area — living area in square meters (m2)
- locality_name — name of the locality
- open_plan — free layout (boolean type)
- parks_around3000 — number of parks within a radius of 3 km
- parks_nearest — distance to the nearest park (m)
- ponds_around3000 — number of reservoirs within a radius of 3 km
- ponds_nearest — distance to the nearest reservoir (m)
- rooms — number of rooms
- studio — studio apartment (Boolean type)
- total_area — the total area of the apartment in square meters (m2)
- total_images — the number of photos of the apartment in the ad

# General conclusion


The peak of the submission of ads falls on February, the lowest number of ads in May.

On weekends, ads are published twice as often as on weekdays.

The average time an ad is on the site is 183.5 days.

The most common ad placement time is 96 days.

For the time of sale, values that range from 0 to 520 days can be considered normal. Most of the ads are closed after 43-234 days.

The largest correlation between the distance from the center of St. Petersburg and the price of the apartment corr = -0.8.

The cost of the premises strongly depends on the total area and living area corr = 0.6.

A strong influence, but slightly less has the kitchen area corr = 0.5.

Even less affected is the number of rooms corr = 0.4.

A weak inverse correlation is given by the distribution over the years of corr = -0.1.

The price is also affected by the category of floors (first, last, other)

The most expensive square meter:103,995.5 p. Located in St. Petersburg

The cheapest square meter:69,583.5 p. Located in Lomonoso
