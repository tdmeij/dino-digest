dino-digest  
===========  
  
Tables with digested data from the Dutch national groundwater database 
Dinonolket.nl
  
Dutch national groundwater database Dino
----------------------------------------
More than 80.000 groundwater head series from the Netherlands are 
available on https://www.dinoloket.nl/. Data can be downloaded free of 
charge. 
  
This repository presents tables with desciptive statistics for all
available groundwater head series. This way, groundwater head series 
with specific characteristics can be found more easily. 
  
The folowing tables with digested data are available: 
  
| table               | content description                                         |  
| ------------------- | -------------------                                         |  
| peilbuizen-srstats  | descriptive statistics of groundwater head series           |  
| peilbuizen-locstats | descriptive statistics of all head series at onde location  |  
| peilbuizen-xg       | descriptive statistics for each year for all head series    |  
| peilschalen-srstats | descriptive statistics of all surface water level gauges    |  
| peilschalen-remarks | list of remarks added tot gauge measurments                 |  
    
Tables srstats with groundwater head statistics contains values of the GXG,
a descriptive statistic descibing mean head in winter, spring and summer.
This table is available in two versions. In the file ending with mnap contains 
the Gxg in meters relative tot datum level (NAP). Yhe file ending with mv 
contains GxG in meters relative to surface level (maaiveld).
  
Explanation of column contants for tables srstats and locstats:  
  
dino-srstats 
------------ 
statistics from over 80.000 well tube measurements 

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
| q05           | lower 5% point of measurements (mNAP) 
| q95           | upper 5% point of measurements (mNAP) 
| dq0595        | difference between q05 and q95 
| ghg           | mean highest groundwater table 
| glg           | mean lowest groundwater table 
| ghgw          | ghg based on winter measurements only 
| glgs          | glg based on summer measurements only 
| gvg3          | mean spring grondwater level based on 14-3, 28-3 and 14-4 
| gvg1          | gvg based on 1st on april only 
| ghgnyr        | number of years used for ghg 
| glgnyr        | number of years used for glg 
| ghgwnyr       | number of years used for ghgw 
| glgsnyr       | number of years used for glgs 
| gvg3nyr       | number of years used for gvg3 
| gvg1yr        | number of years used for gvg1 
| n1428nr       | number of years used for calculating statistics
| gt            | number of years used for gt
| gtref         | reference level used for calculating statistics


dino-locstats
-------------
Statistics from srstats aggregated to over 53.000 well locations 

| column name   | content description                                      |
| -----------   | -------------------                                      |
| locname       | identification code of well location in Dino
| nfil          | number of well filters
| alias         | alternative series name
| surfacelevel  | level of surface (mNAP)
| filbot        | level of first lower end tube filter (mNAP)
| xcr           | xcoordinate (Dutch grid)
| ycr           | ycoordinate (Dutch grid)
| firstdate     | date of first measurement (over any filter)
| lastdate      | date of last measurement (over any filter)
| minyear       | first year with measurements (over any filter)
| maxyear       | last year with measurements (over any filter)
| nyears        | number of years with measurements (over any filter)
| yearspan      | difference between minyear and maxyear (over any filter)


