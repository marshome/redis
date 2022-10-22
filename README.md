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
  - ./src/redis-benchmark -t set -c 4 --threads 4 -r 100000000 -n 50000
  - 官方
  - 4869.02 4755.11 4754.66
- setex
- setnx
- get
- getdel
- getex

# 压测示例：

- ./src/redis-benchmark -c 4 --threads 2 -n 1000000 incr foo