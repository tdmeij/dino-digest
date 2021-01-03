dino-digest
===========

csv tables with digested data from the Dutch national groundwater database Dino

Dutch national groundwater database Dino
----------------------------------------
More than 80.000 groundwater head series from the Netherlands are available on https://www.dinoloket.nl/ and can be downloaded manually free of charge. This repository presents tables with digested data from this groundwater database to help users find groundwater head series with specific characteristics more easily. Files are updated every few months, as creating these tables requires downloading data from dinoloket manually.

Two tables with digested data are available:

###dino-srstats.csv
coordinates, number of measurement years and Gxg statistics of over 80.000 ground water head series

#### fields available:

| column name   | content description                                      |
| -----------   | -------------------                                      |
| series        | identification code of series in Dino
| locname       | identification code of well location in Dino
| filname       | identification code of well filter
| alias         | alternative series name
| xcr           | xcoordinate (Dutch grid)
| ycr           | ycoordinate (Dutch grid)
| mplevel       | level of well measurement reference point (meters NAP)
| filbot        | level of lower end tube filter (mNAP)
| surfacelevel  | level of surface (mNAP)
| firstdate     | date of first groundwater level measurement
| lastdate      | date of last groundwater level measurement
| minyear       | first year with measurements
| maxyear       | last year with measurements
| yearspan      | difference between minyear and maxyear
| nyears        | number of years with measurements
| mean          | mean of groundwater level measurements (mNAP)
| median        | median of groundwater level measurements (mNAP)
| q05           | lower 5% point of groundwater level measurements (mNAP)
| q95           | upper 5% point of groundwater level measurements (mNAP)
| dq0595        | difference between q05 and q95


####dino-locstats.csv
data from srstats aggregated to over 53.000 well locations

#### fields available:
locname,locname,filname,alias,surfacelevel,filbot,xcr,ycr,firstdate,lastdate,minyear,maxyear,nyears,yearspan

for content description of fields see above.

