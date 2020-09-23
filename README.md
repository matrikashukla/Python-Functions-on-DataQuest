# Python-Functions-on-DataQuest

# EXTRACT FUNCTION AND FREQUENCY FUNCTION

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
   
# FREQUENCY TABLE   

 3.Write a function named freq_table() that generates a frequency table for any column in our iOS apps data set.
   The function should take the index number of a column in as an input (name the parameter as you want).
   Inside the function's body:
   Loop through the apps_data data set (don't include the header row) and extract the value you want by using the parameter (which is expected to be an index number).
   Build the frequency table as a dictionary.
   The function should return the frequency table as a dictionary.
   Use the freq_table() function to generate a frequency table for the user_rating column (the index number of this column is 7). Store the table in a variable named ratings_ft.  

# MEAN FUNCTION
 
 4.Write a function named mean() that computes the mean for any column we want from a data set.
   The function should take in two inputs: a data set and an index value.
   Inside the body of the mean() function, use the extract() function to extract the values of a column into a separate list, and then compute the mean of the values in that        list using find_sum() and find_length().
   The function should return the mean of the column.
   Use the mean() function to compute the mean of the price column (index number 4). Assign the result to a variable named avg_price.
