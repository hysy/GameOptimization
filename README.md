# GameOptimization

# FrozenLake Problem
## とりあえずメモ
Q値にベルマン方程式を用いた Q学習

<img src="https://latex.codecogs.com/gif.latex?Q(s,a)=l \cdot (r+\gamma(max(Q(s',a'))" />

s: どのマスにいるか

l: 学習率

r: その時点での<img src="https://latex.codecogs.com/gif.latex?Q(s,a)" />


a: どの方向から来るのか

y: 割引率

<img src="https://latex.codecogs.com/gif.latex?a=argmax(Q[s,:]+ rand(1,n) \cdot (1/i))" />

i: i回目の学習

n: 行動パターン（今回は上下左右の4通り）

