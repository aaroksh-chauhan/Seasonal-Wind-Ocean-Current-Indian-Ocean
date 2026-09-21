# Seasonal Wind and Ocean Current Patterns over the Indian Ocean

## Overview
This project maps how wind speed and ocean surface currents vary across the 
four seasons (Winter, Summer, Monsoon, and Post-Monsoon) over the northern 
Indian Ocean region, visualizing both magnitude and direction.

## Objective
- Compute and map seasonal wind speed and direction across the Arabian Sea, 
  Bay of Bengal, and surrounding Indian Ocean region
- Compute and map seasonal ocean surface current speed and direction for the 
  same region
- Compare how both wind and ocean circulation patterns shift across the four 
  seasons, particularly the strengthening during the monsoon

## Data
- **Source:** Gridded reanalysis data — wind components (u, v) for the wind 
  speed maps, and ORAS (Ocean Reanalysis System) surface current data for the 
  ocean current maps
- **Region:** Northern Indian Ocean, covering the Arabian Sea and Bay of 
  Bengal (approx. 50°E–90°E, 10°S–30°N)
- **Seasons:** Winter, Summer, Monsoon, and Post-Monsoon

## Tools & Methods
- **Language:** Python
- **Key libraries:** xarray, numpy, matplotlib, cartopy
- **Method:** Calculated wind speed magnitude from wind components and plotted 
  it as a seasonal 4-panel map with wind direction vectors overlaid; separately 
  computed ocean surface current speed and direction from ORAS data and 
  plotted it the same way, as a seasonal 4-panel comparison

## Results
- Wind speed showed a dramatic seasonal increase during the Monsoon season, 
  reaching over 18 m/s in the western Arabian Sea (the Findlater Jet region), 
  compared to under 9 m/s in other seasons
- Wind direction reversed between seasons, consistent with the monsoon's 
  seasonal wind reversal over the Indian Ocean
- Ocean surface currents also intensified during the Monsoon season, most 
  visibly in the western Arabian Sea, mirroring the pattern seen in the wind 
  data — showing how monsoon winds drive ocean surface circulation
- Current speeds were generally low (under 0.08 m/s) outside the monsoon, with 
  localized higher-speed regions near the equator and western boundary

## Skills Demonstrated
- Seasonal climatology analysis of wind and ocean circulation
- Working with gridded reanalysis data (wind and ORAS ocean current data)
- Vector field visualization (wind/current direction and magnitude)
- Scientific visualization using Python (cartopy, matplotlib)

## Author
Aaroksh Chauhan — M.Sc. Atmospheric and Oceanic Sciences, IIT Bhubaneswar
