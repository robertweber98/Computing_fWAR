# Computing_fWAR
## An attempt to compute fWAR of fangraphs.com for position players
The following contains a step-by-step attempt to compute fangraphs.com's WAR for position players. I was able to manually calculate all pieces of the metric that use public data.

UBR (Ultimate Baserunning) and UZR (Ultimate Zone Rating) use the private UZR data set so I was not able to achieve a manual calculation for the listed metrics and any pieces that utilize said metrics. I do, however, have an attempt posted for UBR I say "attempt" because I achieved numbers for UBR using the statcast data, but they do not match those of fangraphs.

### Data
#### The data used for this are taken from a variety of places that are listed below with the date acquired. The data sets themselves are not included to ensure compliance with the terms of use of the different destinations. 
- fangraphs.com 2017 "batting leaders" page for all players with team splits and a plate-appearance minimum of 0 in a custom table with the following stats: Name, Team, G, AB, PA, H, 1B, 2B, 3B, HR, R, RBI, BB, IBB, SO, HBP, SF, SH, GDP, SB, CS, OBP, wOBA, RE24, wSB, UBR, wGDP, wRAA, wRC, Bat, Fld, Rep, Pos, RAR, and WAR. (07/16/2018)
- the full 2017 Statcast data set scraped with scraping code borrowed from baseballr. (06/11/2018)
- a data set of mlb player ids and player names from the CrunchTimeBaseball website. (06/20/2018)
- the fangraphs.com basic park factors in the Guts! section
- the fangraphs.com fielding data set from the 2017 "batting leaders" page for all players with team splits and a plate-appearance minimum of 0. The table needed is the page default. 

### Help is welcome and much appreciated
In the "Computation" Rmd, I have my attempt at fWAR for postion players performing all the calculations possible due to the data restricition, and the numbers still do not match perfectly. Also, none of the fielding data is public (to the best of my knowledge) so, using the statcast data, I wasn't able to get anywhere close to their numbers.
I massively appreciate any help anybody is able to give to make this code more effective and accurate. I feel that I have a pretty good start, but I must be missing something.

Feel free to conctact me with any questions, concerns, or developments. 
Thank you
