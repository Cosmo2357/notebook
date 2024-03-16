# notebook
### 二項分布の確率質量関数

1. **一般的な形式**:
$$
C(n, k) \times p^k \times q^{(n-k)}
$$
- ここで、\( p \) は成功の確率、\( q \) は失敗の確率（\( q = 1 - p \)）を意味します。
- この形式は、成功と失敗の確率を明確に区別したい場合に使われます。


2. **補完的な形式**:
$$
P(X = k) = C(n, k) \times p^k \times (1-p)^{n-k}
$$
- この表現では、失敗の確率が \( 1-p \) として直接示されています。
- 成功の確率と失敗の確率が補完的な関係にある（合計して1になる）ことを映しています。