問題
---------

整数列 $a_0, a_1, ..., a_{N - 1}$、$b_0, b_1, ..., b_{M - 1}$ が与えられます。整数列 $c_0, c_1, ..., c_{(N - 1) + (M - 1)}$ を求めてください。

ただし、

$$c_i = \sum_{j = 0}^i a_j b_{i - j} \bmod 998244353$$

です

制約
---------

- $1 \leq N, M \leq 2^{19}(=524288)$
- $0 \leq a_i, b_i < 998244353$

入力
---------

```
$N$ $M$
$a_0$ $a_1$ ... $a_{N-1}$
$b_0$ $b_1$ ... $b_{M-1}$
```

出力
---------

```
$c_0$ $c_1$ ... $c_{(N - 1) + (M - 1)}$
```

サンプル
---------

{{example example_00}}

{{example example_01}}
