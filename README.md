# Loading-and-querying-postgresql-database-using-python

Kindly note my efforts are well documented in the code, reading the code alone is sufficient to understand what the work is all about.
SQL and Python have been used extensively in this work.

1. The countries, continents, and languages data have been downloaded from annexare repository using wget.
The downloaded files are in .json format, and have been imported into python.
The continents, countries, and languages data have been extracted from the countries json file.
The currencies and languages data have been cleaned by removing whitespaces, brackets and apostrophes.
Postgresql was used inside python for this work with the aid of the psycopg2 library.
Separate tables have been created for the continents, countries, currencies, and languages.
These tables have been loaded into a database I created for this work called assignment in postgresql.
The continents code were renamed with the actual continents name before loading the continent table into the database.
The first 10 rows have been fetched from each table to confirm that the tables have actually been loaded into the database.
Each table has been altered to include a primary key called id, which are just integers of 1 to the length of the data.

2(a). The list of all continents and total number of countries in each has been obtained using SQL queries, and have been
nicely formatted in a tabular format.

2(c). The list of all countries and total number of languages spoken has been obtained using SQL queries, and have been
nicely formatted in a tabular format.

2(b). The list of all countries and total number of languages spoken has been obtained using SQL queries and python (pandas groupby function), and have been
nicely formatted in a tabular format. The language code and language name in the language.json file imported earlier in the code have been mapped to the
language data in the country table so the name of each language would be displayed in full for better readability. 

You can also run the codes to confirm the authenticity.	

Thank you.
