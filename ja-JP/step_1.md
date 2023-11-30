次のように三角形を描きます。`triangle(x1, y1, x2, y2, x3, y3)`

`triangle`が呼び出される前に設定されていた輪郭線と塗りつぶしの値を使って三角形が描かれます。

--- code ---
---
language: python
filename: main.py
---

    triangle(210, 250, 330, 150, 220, 160)  # (x1, y1), (x2, y2), (x3, y3)

--- /code ---

The triangle will be drawn with a corner at each of the three coordinates given by (x1, y1), (x2, y2), (x3, y3).

![The output area showing a triangle with corners at the coordinates from the code.](images/example.png)
