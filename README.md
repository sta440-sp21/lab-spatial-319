# Lab: Spatial data visualization (3/19)

`nc_health` contains county-level data from the Robert Wood Johnson Foundation
and contains the following variables:
- `county`: County
- `inactive`: Percentage of adults who are physically inactive
- `obesity`: Percentage of adults who are obese
- `hs`: Percentage of adults who have graduated high school

# Activities

1. Create a choropleth map for a variable of your choice.
2. Evaluate whether there is evidence of spatial autocorrelation for obesity.
3. Create a new variable that corresponds to the average obesity in neighboring
counties (i.e., the spatially-lagged obesity). In your spatial weight matrix,
use a row-standardized binary matrix.
4. Evaluate the *Pearson* correlation between a county's adult physical 
inactivity rate and the average obesity among its neighbors

Challenge: Find county-level population data; modify your spatial weight matrix
to account for the *population* of neighboring counties.
