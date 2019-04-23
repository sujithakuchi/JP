# JP
PargeLogs and store
# Used pandas for reading and parsing the data
# Python 3 is used for execution
For each station
# It takes input as station names in a text file , each station separated by line
# For each station, it forms the url and hit it and read in form of csv to a dataframe
# The cleaning of data like removing #, *, replacing --- with 0, remove header line with degC, Closed 
# Seperate the sting dataframe with column named XX based of space
# Add column station to the dataframe
Final combined dataframe
# Finally concat all station dataframes to a single dataframe
# Remove all NAN columns and unwanted data
# Add valid column names. Convert columns to numeric
# Finally caculate metrics out of finally loaded dataframe using groupby, tail, rank,sort_values
# Note: This code works when all the given stations lists are considered
