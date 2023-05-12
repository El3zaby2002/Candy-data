# Candy-data
SUMMARY :
*   first i drop the columns that have nan value More than half of its value

*   i impute the NaN values in going_out column with rather not to say and the most frequency responce *No*

*  Then with Gender i impute the NaN values with I'd rather not say and the most frequency responce *Male*

*  the age column had string so i was not able to convert to int , so i used pd.to_numeric to convert to numbers and the rows that was not able to convert became NaN, and mean age is *42*

*   with the country it was quite difficult to deal with all this NaN Values and missing value and i did some manual replacement, in the end i put all the odd values in other to make it easier for read, with the most frequency responce *usa*


*  the same with *day* and *dress* columns i impute the NaN values and the values with the most frequency responce

*   state column had too much nuique values so i dropped it

*  i go through each column of Q6 and impute the NaN values in each column with 'OTHER' value, then i made a score poinet to 
classification  the candy either it best or worest

*  in the end i visualized other comments after impute NaN value  

