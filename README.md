# CINMS_Spring2019
# Author: Juliette Verstaen (juliette@verstaen.com)

Contents:
1. Rmarkdown and code for analyzing giant sea bass data from Santa Barbara Island
2. Inital steps for using satelite data for tacking squid fishermen

**Sea Bass**
Data Tiddying:
1. The date/time column needs to be in the "yyyy-mm-dd hh:mm:ss" format. When saved as a CSV file this gets messed up (it removes the seconds), so the data needs to be saved as an excel file
2. The station names need to be one of the following format: SB-01, SB-02, SB-03, SB-05, SB-06,, SB-07, SB-08, SB-09, SB-10 (unless more stations are added).
3. Lat/long: Almost every station has 2-3 different lat/longs associated with it (although they are very very close). I didn't mess with this since its close enough. Some points on maps are a little wonky because of this.
4. Columns kept: time stamp, transmitter, station name, lat, and long.

Future fun stuff: 
Add temperature data to some of the graphs and maybe do some statistical testing to prove that the lower temps mean less likely to see seabass. Maybe find a threshold.
