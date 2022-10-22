# TODO

- decr
- decrby
- getrange
- getset
- incr
- incby
- incbyfloat
- lcs
- mget
- mset
- msetnx
- setrange
- substr

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

# 压测示例：

- ./src/redis-benchmark -t set -c 100 --threads 2 -r 100000000 -n 1000000
- ./src/redis-benchmark -c 100 --threads 2 -n 1000000 incr foo