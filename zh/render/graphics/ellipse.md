# ellipse

`ellipse()` 方法创建椭圆。   

| 参数 |   描述
| -------------- | ----------- |
|cx | 圆的中心的 x 坐标。
|cy | 圆的中心的 y 坐标。
|rx | 圆的 x 半径。
|ry | 圆的 y 半径。

## 实例

```javascript
var ctx = node.getComponent(cc.Graphics);
ctx.ellipse(200,100, 200,100);
ctx.fill();
```

<a href="graphics/ellipse.png"><img src="graphics/ellipse.png"></a>

<hr>

返回 [Graphics 组件参考](../../components/graphics.md)
