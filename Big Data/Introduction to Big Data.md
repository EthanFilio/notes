# What is BD?
> BD is a portfolio of technologies that were designed to **store, manage, and analyze data that is too large to fit on a single machine**, while accommodating for the issue of **growing discrepancy between capacity, throughput, and latency**.

# Three Vs that characterize BD
## Volume
**Data has a lot of value.**
- Data is worth more that the sum of its parts
	![[Pasted image 20261110153153.png]]

**Data totality: one must have complete data.**
## Variety
Variety has to do with **data shapes.**
- Tables
- Trees
	- [[XML]]
	- [[JSON]]
	- YAML
- Graphs
	Unlike trees, graphs can have cycles.
- Cubes
	For business analytics that already use the pivot table.
- Vectors
	Vectors are lists of numbers, where each number is a component of some data.
## Velocity
Three paramount factors:
1. **Capacity**
	How much data can we store?
2. **Throughput**
	How much data can we transmit?
3. **Latency**
	When do I start receiving data?

Progress is made relative to the factors above. But, their progress are not at all equal in enormous amounts. To bridge the gap between factors, the following are employed:
- **Parallelism**
	This bridges the gap between capacity and throughput improvements.
- **Batch Processing**
	Batch processing involves grouping similar tasks together, and it bridges the gap between throughput and latency.
