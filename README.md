# proj-oil-refineries

**Oil refineries optimization**

Oil refineries produce a certain amount of AI-80, AI-92, AI-95 gasoline every week. It is required to distribute the produced fuel to filling stations in such a way as to maximize the total net profit (income – expenses); at the same time, it is allowed to close unprofitable stations.

The total profit consists of the proceeds from the sale of gasoline, the cost of producing gasoline of each brand, the cost of transporting gasoline at the station and fixed costs for the maintenance of gas stations (for example, rent of premises and salaries to employees, etc.). The amount of gasoline that can be sold per week is limited from above by demand. The cost of delivery at the station is proportional to the distance. We can assume that the distance from the refinery to the columns is calculated as the distance between the x and y points in a two-dimensional coordinate system.

**Additional parameters:**  
• weekly expenses for the station: 100,000 KZT.  

**Input data:**  
• [**NPZ.txt**](https://github.com/aziart/proj-oil-refineries/blob/main/data/NPZ.txt) : coordinates (km) (x, y) and weekly gasoline production (Supply) of each brand (AI);  
• [**STATIONS**](https://github.com/aziart/proj-oil-refineries/blob/main/data/STATIONS.txt): coordinates (km) (x, y) and weekly gasoline demand (Demand) of each brand (AI);  
• * [**AI_COSTS**](https://github.com/aziart/proj-oil-refineries/blob/main/data/AI_COSTS.txt): the price of transportation in tc/l/km (Trans Price), the cost of producing one liter of gasoline in tc/l (Prod Price), the sale price of gasoline in tg/l (SellPrice)  

**Output data:**  
• total profit;  
• the amount of gasoline for each pair of refinery–station;  
• list of closed stations;  
• unallocated gasoline for each plant;  
• unmet demand for each station;  
• profitability for each open station (what is the net profit of each station in the end?).  

**SOLUTION:**  
[**Solution.ipynb**](https://github.com/aziart/proj-oil-refineries/blob/main/Solution.ipynb)