# Florish Stores
Florish Store is an imaginary Store created for Analysis only.
## Context:

There is need to import the file from it raw state using our preferred analytical tool

## Task
* Analysis of Sales by Order
* Analysed the sales by gender
* Display the top 5 location with the highest sales
* The Channel with more revenue
* Sales by age
## References:
 https://kaggle.com
---------------------


| Name              |Class                             |
|-------------------|----------------------------------|
|1. Mayowa           |Data Anlysis|
## Data importation
![Dataset](https://github.com/iamasprout/Florish-Stores/assets/114030254/f3f32701-721c-44c1-8767-f222873109cb)

Since the Data is clean enough for visualization to dived directly to deriving useful dependants

# derived Formula
Since the variable in age is much i decided to group them to Young, Senior and Adult
```
Agegroup=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Young"))
```
![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/bad62cf8-7093-454c-8cb9-0f38da93f17a)

extracting the first three letters from the month
``` 
Month=TEXT(G2,"mmm")
```
![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/8a01fe70-d7cc-4bb3-9b34-2be1133b45f2)

## Data Visualization
According to what was stated earlier as the tasks we decided to crerte a pivot table 

 Order vs Sales
![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/428ae503-a701-482d-93b9-63743e8f7947)


Sales by Gender

![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/5045e600-1110-4792-b4fb-2d26fe349df7)

 Count by Order Status
 ![image](https://github.com/iamasprout/Florish-Stores/assets/114030254/5e2433b5-edaa-46e3-ae4c-c96763a18559)


After all has been done we need to have all present our findings in a better way

![Dashboard](https://github.com/iamasprout/Florish-Stores/assets/114030254/65776a7b-8a98-40aa-8b20-3e2f66d97ea0)


