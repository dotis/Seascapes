### Notes on MODIS/VIIRS/OLCI paper w/Maria at IOCS meeting

1. Highlight MBON regions
2. Highlight "in the news"?
3. Iconic, standard
4. Temperate upwelling, oligotrophic Pacific
5. North Sea
6. Gulf of Maine
7. Or, just MBON plus oligotrophic (US centric)

At each one:
1. For OC inputs: time series, differences
2. For SS: F-stats, time series?

Other comparisons?:
1. Ribbon plots? Dominance in a region (or area covered) - 
"Area" command in MATLAB area(time, array)
Compare area vs. dominance ribbon plots - want to see if surface area and timing of a particular class (or smaller class) different w/MODIS vs. VIIRS
Slopes from Jaoquin to get FLH from OLCI (seasonally varying) 
In each region, a measure of agreement and a measure of uncertainty

Papers which describe SeaWiFS and MODIS Chla, differences in sesitivity in summertime, sunglint

F-stats mismatches are worse at 8-day (add J. Woodill) - compare monthly to 

Other thoughts
systematically remove ocean color
Run the model with and w/o nflh - in many areas, nflh does not add a lot
Look at both MODIS and VIIRS w and w/o nflh

Get L3 inputs from Jaoquin (get them straight from him) - put on ftp 
Is Joaquin using a per-pixel slope?  - Over what region? 

One plot of SST comparisons (test region) - should be the same.
Should we bother w/SST?

### Input products needed from Joaquin 
 - Get all from Joaquin via ftp if possible (monthly, 5-km?)
1. Chl-a (MODA, VSNPP)
2. adg(443) (MODA,VSNPP)
3. NFLH (MODA,S3A/B)
4. Seascape class and prob (MODA,VSNPP)
5. Other - SS w/MODA w/only NFLH changed?

Questions for Joaquin:
1. Time step: MO (coverage is better - can use 8D as a test case in an area of interest)
2. L3 files from OBPG are the ones to use - yes?
3. Updates of other files to end of 2023 - files will go on ftp?
4. Analyses to run? - Should we look at MODA SS w/only NFLH changed?
5. Use of JPSS? - Meaned w/SNPP? - Yes, but doesn't make a huge difference. 
