問題
---------

$N \times N$ 正方行列 $M$ が与えられます。
$M$ は $K$ 個の要素のみが非零で、$i$ 個目は $M(a_i, b_i) = c_i$ です。
$M$ の行列式をmod 998244353で求めてください。

制約
---------

- $1 \leq N \leq 3000$
- $1 \leq K \leq 10000$
- $0 \leq a_i, b_i \leq N - 1$
- $0 \leq c_i < 998244353$

入力
---------

```
$N$ $K$
$a_1$ $b_1$ $c_1$
$a_2$ $b_2$ $c_2$
:
$a_K$ $b_K$ $c_K$
```

サンプル
---------

{{example example_00}}

{{example example_01}}
