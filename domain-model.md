#Domain Models In Here

<span style="font-size:0.5em;">Story</span>
<br />
As a supermarket shopper,
So that I can pay for products at checkout,
I'd like to be able to know the total cost of items in my basket.


<span style="font-size:0.5em;">Model</span>
<br />
| Classes         | Methods                                             | Scenario               | Outputs                   |
|-----------------|-----------------------------------------------------|------------------------|---------------------------|
| `SuperMarket`   | `itemCostCalculator(Dictionary<string,int> receipt)`| sum up item cost (keys)| total cost (int total)    |
|                 |                                                     |                        |                           |
<br />
<span style="font-size:0.5em;">Story</span>
<br />
As an organized individual,
So that I can evaluate my shopping habits,
I'd like to see an itemized receipt that includes the name and price of the products
I bought as well as the quantity, and a total cost of my basket.

<span style="font-size:0.5em;">Model</span>
<br />
| Classes         | Methods                                                 | Scenario                                                | Outputs                   |
|-----------------|---------------------------------------------------------|---------------------------------------------------------|---------------------------|
| `SuperMarket`   | `showReceipt(Dictionary<string,int> receipt, int total)`| print items with their costs, and total cost at the end | printed receipt on console|
|                 |                                                         |                                                         |                           |