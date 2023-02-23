# surfs_up

## Overview

This project intends to give offer more information on the temperature trends to have more information in decision making. In this particular case, Temperature in Oahu to determine if ice cream shio is sustainable all the year.

## Resources
- Python
- squalchemy
- sqlite:///hawaii.sqlite

## Results

Sqlalchemy was used to extract data from a table, two references: Measurement and Station.

<img width="340" alt="Screen Shot 2023-02-23 at 17 14 19" src="https://user-images.githubusercontent.com/114015620/221052645-cb7e3118-2c8a-4fbb-94ba-dcc6b6f602bd.png">

After quering the data, a DataFrame was built to use pandas for statistical analysis. The same process was followed for June and December. 

<img width="615" alt="Screen Shot 2023-02-23 at 17 15 15" src="https://user-images.githubusercontent.com/114015620/221052798-5d23ae94-2978-4853-9284-666ab463112f.png">


### June

Descriptive statistics where obtained through .describe() function.

<img width="154" alt="Screen Shot 2023-02-22 at 21 44 59" src="https://user-images.githubusercontent.com/114015620/220816970-ac042466-592d-4ea2-a90e-344065841a02.png">

For June the average temperature is 74.94°F in some cases less in some others more, on average 3.25°F. The maximum temperature reached in 85°F and the minimum 73°F. 



### December

<img width="145" alt="Screen Shot 2023-02-22 at 21 44 28" src="https://user-images.githubusercontent.com/114015620/220816924-bf713f8f-4aa7-4c01-869c-0383e3b78e2b.png">

For December the average temperature is 71.04°F in some cases less in some others more, on average 3.74°F. The maximum temperature reached in 83°F and the minimum 56°F.

### Additional information

A query was used to obtain the data of all months a year before, to observe how much the previous year the average temperature varied.

<img width="157" alt="Screen Shot 2023-02-23 at 17 20 27" src="https://user-images.githubusercontent.com/114015620/221053555-6037d53c-1479-492c-aee5-d05aa7827afa.png">

The average temperature was 74.56°F, sometimes more sometimes less on average +/- 4.6°F. This means the behaviour of all year long is nearer June temperature, this supports the idea of an ice cream shop.

What about precipitation? Additional queries were performed to find the precipitation on both months 

- On June

<img width="227" alt="Screen Shot 2023-02-23 at 17 25 49" src="https://user-images.githubusercontent.com/114015620/221054244-8f8961d0-e98f-4d47-99a4-14ce0d40712b.png">

0.13 is the mean value for June. Standard Deviation is 0.33.

- On December

<img width="201" alt="Screen Shot 2023-02-23 at 17 26 09" src="https://user-images.githubusercontent.com/114015620/221054293-bb9032a6-6c50-4d64-a562-118a6eca5a7b.png">

0.21 is the mean value for December. Standard Deviation is 0.54. All values are greater than in June, this may suggest that precipitation is more frequent in december.


## Summary

The temperature 
