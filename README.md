# Movies_ETL
Module 8 ETL, Extract Transform Load
## Overview of Module 8
The purpose of this module was to **ETL** a large set of data to create a single uniform and homologous data set for a Hackathon.

-**Extract** the data from 3 different sources. A Wikipedia JSON object, a Kaggle MetaData CSV file and MovieLens rating CSV.

-**Transform** the data into the same format, using Pandas, Numpy, Re, and Time modules. As well as filtering and removing any unnecessary or corrupted data. Finally merging the seperate data sets into one DataFrame.

-**Load** the data into a SQL database, using SQLalchemy. The data in the ratings csv was so large that it needed to be parsed into blocks of 1,000,000 inorder to not overload the conversion engine.
