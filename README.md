# gelatodb

GelatoDB is an in-memory key-value-store database.
Since GelatoDB is in-memory, once you put it in the memory, the data will melt like gelato when you leave the environment.

## Setup
```
~$ python3
>>> from gelatodb import GelatoDB
>>> testdb = GelatoDB("./test.db")
>>> testdb.set("name","orange")
>>> testdb.get("name")
"orange"
```

## Reference
[1] DeCandia, Giuseppe, Deniz Hastorun, Madan Jampani, Gunavardhan Kakulapati, Avinash Lakshman, Alex Pilchin, Swaminathan Sivasubramanian, Peter Vosshall, and Werner Vogels. "Dynamo: amazon's highly available key-value store." ACM SIGOPS operating systems review 41, no. 6 (2007): 205-220.

[2] Atikoglu, Berk, Yuehai Xu, Eitan Frachtenberg, Song Jiang, and Mike Paleczny. "Workload analysis of a large-scale key-value store." In Proceedings of the 12th ACM SIGMETRICS/PERFORMANCE joint international conference on Measurement and Modeling of Computer Systems, pp. 53-64. 2012.
