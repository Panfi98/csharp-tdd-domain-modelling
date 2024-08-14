#Domain Models In Here

Story
As a supermarket shopper,
So that I can pay for products at checkout,
I'd like to be able to know the total cost of items in my basket.


Model 

| Classes         | Methods                                             | Scenario               | Outputs                   |
|-----------------|-----------------------------------------------------|------------------------|---------------------------|
| `SuperMarket`   | `itemCostCalculator(Dictionary<string,int> receipt)`| sum up item cost (keys)| total cost (int total)    |
|                 |                                                     |                        |                           |

Story
As an organised individual,
So that I can evaluate my shopping habits,
I'd like to see an itemised receipt that includes the name and price of the products
I bought as well as the quantity, and a total cost of my basket.

Model 

| Classes         | Methods                                                 | Scenario                                                | Outputs                   |
|-----------------|---------------------------------------------------------|---------------------------------------------------------|---------------------------|
| `SuperMarket`   | `showReceipt(Dictionary<string,int> receipt, int total)`| print items with their costs, and total cost at the end | printed receipt on console|
|                 |                                                         |                                                         |                           |