# Mock Case of Precision Marketing
> Analyzing Purchased Products by Customers

## Case
In today's fiercely competitive market environment, understanding customer behavior is crucial for devising effective marketing strategies. The company aims to enhance sales volume by introducing precision marketing, which involves personalized product recommendations tailored to individual customers.

## Objective
To visualize the connections between products purchased by customers and identify potential cross-selling or upselling opportunities. 
By creating a network diagram, we aim to gain insights into the relationships between different products and customer segments.

## Analytic Process
- Data Cleaning
###### To Separate the item customers purchased by "," as every item correspond to the customer who bought.
![image](https://github.com/41071119H-Irene/connection-graph/assets/112916890/3a530f03-bf94-4640-aa4c-0ed26f924a43)
###### Make the data into a defaultdict(list)
![image](https://github.com/41071119H-Irene/connection-graph/assets/112916890/60456b53-a32d-42c9-80a0-9e187d648008)

- Visualize the Data
###### Using Networkx to Draw the Connection Map, to find the connection between the customers and the items they purchased.
  ![image](https://github.com/41071119H-Irene/connection-graph/assets/112916890/729ca1ee-67e4-413a-91e2-257bfba969b9)

- Insights
## Conclusion
