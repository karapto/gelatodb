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
