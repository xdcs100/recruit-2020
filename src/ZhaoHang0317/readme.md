# zhaohang 03.17

## Test3 - 大鱼吃小鱼

长度为 `n` 的数组, 每一个数字可以吃掉左边或者右边的数字, 被吃掉的数字会让吃掉它的数字减去自身的数字   

`ex: 3 eat 2 3 change to 1`    

最后剩一个数字, 求数字最大是多少

1. ***如果正数, 负数, `0` 有两种存在, 所有数的绝对值之和***
2. ***只有正数或者负数, 除了绝对值最小值的所有数的绝对值之和 减去绝对值最小数的绝对值***