## 入力
- input, split
- map
- tuple

##　計算系
- abs
- +. -, *, /, %, //
- 階乗
  ```python
  import math

  print(math.factorial(5))
  ```
- 順列
  ```python
  import math

  def f(n, r):
    return math.factorial(n) // math.factorial(n - r)

  print(f(6, 3))
  ```
- 組み合わせ
  ```python
  import math

  def f(n, r):
    return math.factorial(n) // (math.factorial(n - r) * math.factorial(r))

  print(f(6, 3))
  ```
  
## 型変換
- int
- str
- float

# リスト
- list
- all, any
- sort
- sorted
- sum
- len
- set
- min, max

# その他

