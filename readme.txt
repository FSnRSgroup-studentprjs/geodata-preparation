Required files to calculate each step are as below:




1 - to aggregate :

required files: GED_Gaul.csv, AC_gaul.csv 

result of this code : aggregated files with name of all admins and number of event as well as fatalities


2 - to calculate inflation:

required files: match_price_loc.csv (dataframe that has every market with its location and prices for each product)
 
     2.1 - while calculating inflation: 

          during "for" loops, sometimes might be an error, it would be useful to save them as csv and then read them again

result of this code: amount of inflation for each product in each markets for all adm2 in all countries



3 - to calculate avg inflation for each market: 

 required files: match_price_loc.csv


      3.1 - while calculating avg inflation for each market: 

          during "for" loops, sometimes might be an error, it would be useful to save them as csv and then read them again

result of this code: average amount of inflation for all products in each market




4 - to merg conflict and inflation data:

required files: 'GED_CS_HA_inf_final.csv' and 'ACLED_CS_HA_inf.csv' (they are conflict data that are intersected via ArcMap to get HA0 and IPC data and merged with inflation data),

and 'all_admins_f.csv' (it is all of the countries and admin 1 and 2 in order to be sure, that all countries are covered.)

result of this code: final data set