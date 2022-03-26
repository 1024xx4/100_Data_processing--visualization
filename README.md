Python 実践データ加工/可視化 100本ノック の演習

##### Support site
https://www.shuwasystem.co.jp/support/7980html/6439.html

##### Sample source
###### Sample file
https://www.shuwasystem.co.jp/support/download/6439/100knock-process-visualization.zip

####### Sample image
https://www.shuwasystem.co.jp/support/download/6439/sample_picture.zip

###### Errata
https://www.shuwasystem.co.jp/support/download/6439/%E6%AD%A3%E8%AA%A4%E8%A1%A8.pdf

---
## 関数
```python
import pandas as pd
pd.pivot_table(data, index='', columns='', aggfunc='')
```
Pivot table の表を作成する。
###### 引数
data: DataFrame を指定  
index: 縦の項目を DataFrame の列名で指定  
columns: 横の項目を DataFrame の列名で指定  
aggfunc: 集計方法を指定

---

```python
import matplotlib.pyplot as plt
plt.bar(x, y)
```
棒Graph を描画する
###### 引数
x: 横軸  
y: 縦軸
---
```python
import matplotlib.pyplot as plt
plt.barh(x, y)
```
横向きの棒Graph を描画する
###### 引数
x: 縦軸
y: 横軸