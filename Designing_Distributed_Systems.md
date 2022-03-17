# PART1
## CH2 sidecar pattern（摩托车的那个旁边东西）
对于legacy系统有好处，在原来的系统上加一些额外的东西，有点ESW的味道

## CH3 Ambassadors（大使)
其实就是router模式，所有的traffic都经过router，把细节隐藏在router下面。
可以额外实现traffic split做A/B test

## CH4 adapter
把以后的服务上面做一个translation层，提供新的东西
额外提到了monitoring，logging，和health monitoring

# PART2
## 微服务
可以独立scale，decoupling
我觉得缺点RPC overhead，似乎并灭有提到。
