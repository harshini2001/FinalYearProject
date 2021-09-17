# FinalYearProject

## Interesting links:
- [Routing IN R](https://www.kaggle.com/sebastianodiluozzo/route-dataset-and-code?select=MappingRoutes.R)
- [ARCMAP](https://desktop.arcgis.com/en/arcmap/latest/extensions/network-analyst/exercise-3-finding-the-best-route-using-a-network-dataset.htm)
  - Checkout ARCMAP
- [GOOGLE OR](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjEq7nzwaPyAhXS4jgGHbNlBpwQjBAwAnoECBcQAQ&url=https%3A%2F%2Fdevelopers.google.com%2Foptimization%2Frouting%2Frouting_options&usg=AOvVaw01QKtOiYWb65TzGau573cq)
---
## Algorithms
- Genetic algo(GA).
- Tabu search(TS).
- Simulated Annealing(SA).
- Ant colony system.
- Particle Swarm Optimisation 
- RPS - DRP (distribution req planning)
- RPS - MAS 
- Dynamic programming approaches
- SVRP
- DQN (Deep Q Network - combination of RL and CNN)
- OCaPi
- Grey Wolf Optimizer (CGWO)



---
## IDEA:
- INPUT: SRC, DEST, Depots (list)
- STANDARD DATA: Google API (place -> lat, long)
    - Depot - frequency of item deliveries; traffic
    - Cost  - freight weight (balancing load) and transportation cost
    - Distance - time => cost factor 1
    - Delivery urgency - priority based (Time window penalty cost)
    - Fuel efficiency, Carbon emissions
    - Freshness degradation (for cold logistics alone)
    - Road, traffic, weather
    - Vehicle conditions
    - Driving hours and rest
    - (Fleet management)
    - Energy use
    - Safety and security
    - Economic Health
    - Ecosystem impacts
- OUTPUT: Routes + time factor => best k solutions
- METHODOLOGY: Equation based on all factors - try to optimise the score 

- Challenges 
- IDEA: diverse adaption for any country based on standard data
- IDEA: SPARK DISTRIBUTED processing 
1. Finalise mode: Air route, ship route, road route ; or mixed mode
2. Finalise scope: India or US or specific country; 
worldwide, intercontinent


---
1. Identify more factors 
2. Find equation


---
DATASETS: 
1. [Supply Chain Shipment Pricing Data](https://www.kaggle.com/divyeshardeshana/supply-chain-shipment-pricing-data)  
  - Freight cost, mode, weight, dates, vendor, manufacture site
  - SAfrica, Africa
2. [E Commerce Dataset Analysis](https://www.kaggle.com/gsdeepakkumar/e-commerce-dataset-analysis/data?select=olist_order_payments_dataset.csv)
  - Brazil
  - Big dataset n comprehensive
3. [Supply chain based](https://data.world/search?q=supply+chain)
4. [Freight data](https://data.world/datasets/freight)
5. [Route](https://www.kaggle.com/open-flights/flight-route-database)
6. [Route](https://openflights.org/data.html)
7. [Europe Dataset](https://github.com/jwang0306/vehicle-routing-problem/tree/master/data)
8. [Route-> separate source and destination nodes](https://github.com/tejasvi/routero/tree/master/data)


## To decide:
1. Route optimise --- > existing route => optimise
2. Graph dataset => 
3. Lat and Longitude
3. Distributed data.... spark

4. Maximise delivery
Minimise time
Minimise cost

-- > dataset depend
---


