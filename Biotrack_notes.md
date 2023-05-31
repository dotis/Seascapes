## SS/Biotrack meeting 5/31/23
MTK, FMK, EMH, NH, M. Cimino, Nathan F., Ryan V., Thiago C., Lorenzo Davidson (Brown), D. Otis, Barbara Block, M. McKinzie

Topic: How to link seascapes with animal tracking data?

How can dynamic pelagic SS predict pelagic megafauna?

First collaborative step to synergize SS and Biotrack groups

Using satellite tracking data as opposed to passive acoustics, which is restricted to coastal areas

Use satellite-linked telemetry data (direct measurements when animals surface)

Multiple species if possible on both east and west coasts

5-km at 8-day resolution for SS. 5-km should be adequate. Is 8-day ok? Would be good to get daily. 

Potential analyses? GAM, generalized linear models

Could also use SDM or habitat suitability models

Megan C. - only a few SS on the west coast (more on the east coast?). How predictive can they be? Would we get more classes with a higher spatial resolution?

MTK - Finer resolution spatially can be done. Would capture upwelling fronts. Could also have finer classification (more classes). It can cluster in finer resolution. How many classes to get to 90% of variation.

50-60 classes can capture 95% of the variability, but there are issues (noise) in oligotrophic regions. 

FMK - Can use many years/seasons to use (up to 20 years of sat. data). What can we get now with 8-day/5-km?

MTK - How to animals spatially aggregate?  - Could use 4-km daily resolution. FMK disagrees (this is a large effort already).

EMH - Can we aggregate the movement data (Chelsea Black at UM)? Can we analyze the movement data further to better define the ecology?

Ryan V. Perhaps a rolling 3-day might be useful to help fill cloud gaps

FMK Ryan, yes-- that would be a good idea. And for 4 km data that won't be such a heavy computational lift. issue is you can't just average seascape class... perhaps a Mode could work

NH - How can the animal data drive the questions/analysis? Graphs of major SS w/shark points and histogram.

ANimal data can be classified (resident vs. transient - movement vs. foraging in one area) mp parameter

MTK - Need to look at mode of composited SS, as these are a classification. Can we look at the center animal location over a month or 8-day period?

Are the animals in patches? Or, along boundaries between patches.

FMK - Also could use SS uncertainty fields. 

MTK - Yes, Can elucidate fronts. How diffuse are frontal boundaries? How different are the water masses? If animals are always in a 1, they are staying in that water mass.

BB - Animal data comes in many forms. High uncertainty (0.5-1.0 degrees). This is difficult and animal-dependent. Birds (GPS tags), but not shark (SPOT tags?)

NH - Use GPS tags and restrict to a certain level of accuracy. 

MTK - Maybe we need to dig into the limitations of animal data.

BB - SPOT tags don't report every day. Error bounds are put on these, sometimes better than others. Start with something easy (something that reports a lot), get as many points as you can, then bring in sat. data.

BB - Much of the tag data is well below 5-km. Many gaps in both datasets. Data becomes linearized. Best approaches may be with raw data (bird or pinneped data).

MTK - But can we look at a regional case study over a few years and do the daily ss classification?

Megan C. Will this analysis better on the east vs. west coast?

MTK - There are fewer on the west coast, but there are more than 3 on the WC.

FMK - I don't know if the underlying satellite data allows daily - like sea surface height and others will be based on very coarse spatial and temporal data interpolation. IR and color are gappy due to clouds (which is the reason we use ~weekly averages) etc.

NH - This is a good start. Let's keep it simple for now and perhaps look for other collaborative grants. 

Thiago - What do we want here? Validation of SS? What is the end goal? This lacks clarity right now.

BB - We lack clarity here. There is a lot of uncertainty with the animal data. Very few of us (in the animal tracking world) know about seascapes.

Megan M. In addition to TOPP datasets, there is also publicly available cetacean, shark, seabird data available for the west coast through ATN

MTK - The ADT are daily. And what Ryan is suggestion is a rolling 3 day mean to interpolate between clouds. In the NCC we have 50% retrieval from May to October in some areas, but more like 25%. So still will have clouds, but perhaps less data, but more accurate data.

Ryan V. - The advantage I see in terms of Seascapes is that it integrates several oceanographic parameters into a single value. I am interested in the possibility, as Maria mentioned, about increasing the class resolution. Then eddies/fronts might pop out a little more?

TC - If validating seascapes is the main goal, I would consider implementing multistate models to assess movement rates among seascape classes

NH - Can SS group help us interpret SS classes? If animals persist within a class, what is that telling us?

EMH - What are applications here? Perhaps an alert system for certain taxa when a SS class appears.

NH - Bycatch reduction is on

Enrique - there is one alert system set up like this for sturgeon East coast (nasa funded)

Ryan V. I want to get the word out about all of this! More meetings to raise awareness of ss with NOAA groups. - Kickoff around September.

MTK - Yes, Enrique and Megan, this is Matt Oliver and Matt (?) Breece's work! Very cool stuff and also in optically complex inland waters.




 
