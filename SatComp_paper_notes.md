### Notes on MODIS/VIIRS/OLCI paper w/Maria at IOCS meeting

1. Highlight MBON regions
2. Highlight "in the news"?
3. Iconic, standard
4. Temperate upwelling, oligotrophic Pacific
5. North Sea
6. Gulf of Maine
7. Or, just MBON plus oligotrophic (US centric)
8. Time frame: 1/1/2017-6/30/2024 (7.5 years) - could stop at 12/31/2023 for full years

At each one:
1. For OC inputs: time series, differences
2. For Rrs: time series, differences
3. For SS: F-stats, time series?
4. Questions: Need code for area plots and fstats (MTK)
5. For Chl and adg443 only can compare MODA, JPSS1, JPSS2, SNPP

### Tasks
1. Overall map of regions
2. Plots of input products and Rrs (publication quality) in MBON regions
3. Plots of SS outputs and differences
4. F-stats? Need code from John Woodill




Other comparisons?:
1. Ribbon plots? Dominance in a region (or area covered) - 
"Area" command in MATLAB area(time, array)
Compare area vs. dominance ribbon plots - want to see if surface area and timing of a particular class (or smaller class) different w/MODIS vs. VIIRS
Slopes from Jaoquin to get FLH from OLCI (seasonally varying) 
In each region, a measure of agreement and a measure of uncertainty

Papers which describe SeaWiFS and MODIS Chla, differences in sesitivity in summertime, sunglint

F-stats mismatches are worse at 8-day (add J. Woodill) - compare monthly to 

Monthly data is fine, except for phenology. Move to 8-day for that.

Other thoughts:
systematically remove ocean color (MTK)
Run the model with and w/o nflh - in many areas, nflh does not add a lot
Look at both MODIS and VIIRS w and w/o nflh

Get L3 inputs from Jaoquin (get them straight from him) - put on ftp 
Is Joaquin using a per-pixel slope?  - Over what region? 

One plot of SST comparisons (test region) - should be the same.
Should we bother w/SST?

### Input products needed from Joaquin
 - Get all from Joaquin via ftp if possible (monthly, 5-km?)
1. Chl-a (MODA, VSNPP) - From NASA
2. adg(443) (MODA,VSNPP) - From NASA
3. NFLH (MODA,S3A/B) - From JT FTP
4. Seascape class and prob (MODA,VSNPP) - From JT FTP
5. Other - SS w/MODA w/only NFLH changed?


