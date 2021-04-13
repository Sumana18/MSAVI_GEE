# MSAVI_GEE
**Brief Introduction:**

*   The modified soil-adjusted vegetation index (MSAVI) is a vegetation index, which is used to lift limits on applying NDVI to the areas with a high composition of bare soil. 
*   MSAVI is used in the areas where indices like NDVI provide invalid data, mostly due to a small amount of vegetation, or due to a lack of chlorophyll therein. Thus, the index is used to minimize the soil background influence and to increase the dynamic range of vegetation signal.
*   Especially to be used  for analysis of young crops; for arid regions with sparse vegetation (less than 15% of total area) and exposed soil surfaces.
Its ranges form -1 to +1, Higher the value denser the vegetation.

**The formula:**

`MSAVI = (2 * NIR + 1 – sqrt ((2 * NIR + 1)2 – 8 * (NIR - Red))) / 2`

MSAVI has been calculated by querying the required LANDSAT 8 data using Google Earth Engine API in Python
