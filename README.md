# 基数ソート/Radial Sort
## 概要
ソートアルゴリズムの一つ。
有限個の全てのデータが最大値と最小値、形式が判明しているときに適応できる。

## アルゴリズム
1. 各データに複数のキーを設定する(1の位、10の位、100の位…など)
2. 各データを下位のキーから **安定ソートで** ソートする

## 計算時間
O(kN)
k:キーの数

## 参考
<https://ja.wikipedia.org/wiki/%E5%9F%BA%E6%95%B0%E3%82%BD%E3%83%BC%E3%83%88>

---
## このmarkdownを書いた目的
基数ソートの理解を深めるため

~~ 決して markdown を書く練習に丁度いいと思って書いたわけではない ~~ ←なんで打ち消し線適用されないの？

| たかが | markdownの | 練習の |
|:---|:---:|---:|
| ために | 表組みに | まで |
| ここまで | 凝るわけ | ないじゃないですか！ |

> 引用はこういうふうにすればいいんよ

` int hoge = 0; `

` int fuga = 1; `

```python
hello = "Hello"
world = "World"
exclamation = "!"
print hello, world, exclamation
```
### 参考
[Markdownで行こう！](https://gist.github.com/wate/7072365)
