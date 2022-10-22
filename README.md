# TODO

- mset
- msetnx

# OK

- append
- strlen
- psetex
- set
- setex
- setnx
- get
- getdel
- getex
- getset
- incr
- incby
- incbyfloat
- decr
- decrby
- setrange
- getrange
- mget

# 压测示例：

- ./src/redis-benchmark -c 4 --threads 2 -n 1000000 incr foo