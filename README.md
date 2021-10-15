# sales-predictions
This is code for a project that predicts sales for food items and tries to understand factors that contribute to overall sales. I use data from 10 different stores, which is compiled in this dataframe: https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view.

<strong>In this project, I: </strong>

  -Clean and explore the data.
  
  -Make visual representations to better understand the data.
  
  -Make refined visual representations to be able to present my findings from my explorations of the data.
  
  -Use Machine Learning regression models (linear regression, decision trees, bagged trees, and random forests) to create predictions for sales.
  
  -Recommend the best regression model out of the ones I fit to the data.
  
<strong>From what we learn by exploring the data, it can be seen that:</strong>

  -Grocery stores have the lowest sales, and <strong>Type 1 Supermarkets</strong> have the highest sales:
  <img width="836" alt="Screen Shot 2021-10-10 at 1 51 22 PM" src="https://user-images.githubusercontent.com/63165294/137549787-c824bf96-0e21-4ce4-a1e0-8dec9149aed1.png">
  
  
  -OUT027, a medium-size <strong>Type 3 Supermarket</strong>, has the highest sales:
  <img width="852" alt="Screen Shot 2021-10-10 at 1 53 22 PM" src="https://user-images.githubusercontent.com/63165294/137549774-5cf34f3a-c77c-4142-89fa-feb18a9182d4.png">
  
  -In OUT027, most of the items have visilibities closer to the mean visibility, while in other stores the visibility of items is more variable.
  
<strong>From the analysis, I recommend:</strong>
  
  -Avoiding dominating visibility in the store with a few products.
  
  -Avoiding investing in Grocery Stores, because they have (by far!) the lowest sales.
  
  -Doing further analysis on OUT027, a Type 3 Supermarket that significantly outperformed all the other stores in sales, despite not being among the highest-selling store type, Type 1 Supermarkets.

