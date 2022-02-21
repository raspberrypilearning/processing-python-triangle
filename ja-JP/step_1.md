次のように三角形を描きます。`triangle(x1, y1, x2, y2, x3, y3)`

`triangle`が呼び出される前に設定されていた輪郭線と塗りつぶしの値を使って三角形が描かれます。

--- code ---
---
language: python
filename: main.py
---

  triangle(210, 250, 330, 150, 220, 160) # (x1, y1), (x2, y2), (x3, y3)

--- /code ---

三角形は、(x1, y1)、(x2, y2)、(x3, y3)で与えられる3つの座標を頂点として描かれます。

![コードからの座標を頂点とする三角形を示す出力領域。](images/example.png)
