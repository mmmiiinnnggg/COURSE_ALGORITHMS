# COURSE "ALGORITHMS"
Two assignments: 
* The task of Arbitration (Bellman-Ford algorithm)

  Given table of exchange rates of currencies : for one unit of currency $c_i$, you can buy $R[i,j]$ units of currency $c_j$
  
  |Валюта | USD | EUR | GBP | JPY | CHF | CAD | AUD | RUB |
  | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
  |USD | 1 |0,8651 |0,7340 |111,77 |0,9290 |12,538 |13,692 |720,144 |
  |EUR |11,559 |1 |0,8483 |129,19 |10,740 |14,492 |15,826 |832,316 |
  |GBP |13,626 |11,788 |1| 152,29 |12,657 |17,083 |18,656 |98,124|
  |JPY |0,0089 |0,0077| 0,00657 |1 |0,0083| 0,01122| 0,01225 |0,6443|
  |CHF |10,765 |0,9312 |0,7901 |120,29 |1 |13,495| 14,739 |77,52|
  |CAD |0,7976 |0,6901 |0,5854 |89,15 |0,7411 |1 |10,921 |57,43|
  |AUD |0,7304 |0,6319 |0,5360 |81,64 |0,6784 |0,9157 |1 |52,60|
  |RUB |0,01389 |0,01201 |0,01019 |15,520 |0,01290 |0,01741 |0,01901 |1|
  - The task is to find the max-value of exchange rates product when exchanging through c_i -> c_i1 -> c_i2 -> ... -> c_ik -> c_i for all currency i with no small exchange cycles.
  - Implemented the Bellman-Ford algorithm to find the negative cycle in the graph
  
* Find the center city of Russia (convex-hull construction)
  
  - Given the geographcial coordinates of main cities in Russia. (see `citys.csv`)
  - The task is to find the median city.
  - Implemented Jarvis algorithm from scratch to find convex-hull
