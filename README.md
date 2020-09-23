# Python-Functions-on-DataQuest

1 .Write a function named extract() that can extract any column you want from the apps_data data set.
   The function should take in the index number of a column as input (name the parameter as you want).
   Inside the function's definition:
   Create an empty list.
   Loop through the apps_data data set (excluding the header). Extract only the value you want by using the parameter (which is expected to be an index number).
   Append that value to the empty list.
   Return the list containing the values of the column.
   Use the extract() function to extract the values in the prime_genre column. Store them in a variable named genres. The index number of this column is 11.
 2.Write a function named freq_table() that generates a frequency table for any list.
   The function should take in a list as input.
   Inside the function's body, write code that generates a frequency table for that list and stores the table in a dictionary.
   Return the frequency table as a dictionary.
   Use the freq_table() function on the genres list (already defined from the previous screen) to generate the frequency table for the prime_genre column. Store the frequency        table to a variable named genres_ft.
   Feel free to experiment with the extract() and freq_table() functions to easily create frequency tables for any column you want.
