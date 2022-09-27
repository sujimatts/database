
## What is Sharding?
Sharding is a database architecture pattern related to ```horizontal partitioning``` — the practice of separating one table’s rows into multiple different tables, known as partitions. Each partition has the same schema and columns, but also entirely different rows. Likewise, the data held in each is unique and independent of the data held in other partitions.

It can be helpful to think of horizontal partitioning in terms of how it relates to ```vertical partitioning```. In a vertically-partitioned table, entire columns are separated out and put into new, distinct tables. The data held within one vertical partition is independent from the data in all the others, and each holds both distinct rows and columns. The following diagram illustrates how a table could be partitioned both horizontally and vertically:

![image](https://user-images.githubusercontent.com/40743779/192419009-9faf9d64-ab97-47c5-aee7-2d8a8a228ef1.png)
