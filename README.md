# 視訊處理期末專題 Empty Space

## 封面
![](https://i.imgur.com/WJwpSnM.png)

## 介紹

- 主要就是讓玩家操控戰鬥機，閃躲BOSS的火球攻擊，並把四個BOSS打敗。
- 戰鬥機有血量有子彈，子彈打完需要等待填充，過程中會有道具子彈包 ![](https://i.imgur.com/bxkBYHi.png)(增加子彈數量) 和補血包 ![](https://i.imgur.com/TrOPjBr.png) ，玩家可以透過移動撿取道具。

![](https://i.imgur.com/BWl9aw2.png)
![](https://i.imgur.com/FneDLgD.png)


---
## 操控原理:利用webacm捕捉特定顏色的物體

使用Opencv內的HSV轉換，把藍色面積取出來，再計算中心點座標，達到玩家可以使用藍色物體操控戰鬥機的效果。

![](https://i.imgur.com/2qdiHVh.jpg)


