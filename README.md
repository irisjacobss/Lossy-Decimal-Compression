# Lossy-Decimal-Compression
The Lossy Decimal Compression Algorithm takes as input the filename as well as the desired decimals for that CSV file. The algorithm will alter all floating-point numbers in the CSV file to the desired decimal length. It will save this new CSV file in the same file path as in which the code is run. Additionally, the code will mention which of the columns were altered as well as information on to what extent the file was compressed. 


The Jupyter file contains an additional function, a Linear Model creator. This function takes the CSV file as well as the maximum number of decimals the user is considering as input. This algorithm will then output a linear equation which one can use to calculate the expected CSV storage space for each of the decimals (computed with the maximum number of decimals in mind). Likewise, it will output the R^2 score as well as a visualisation of the linear model such that the user can judge on the reliability of the linear equation. This will be of use when there is a tradeoff between decimal usage and storage space occupation. 


Lastly, the file also has a timer that can compute the average time the algorithms take to run (note that one will need to input the right function with the right parameters oneself) using a Monte Carlo Simulation of 100 iterations. 
