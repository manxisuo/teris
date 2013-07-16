用Javascript写的俄罗斯方块，是为了练习JS的面向对象编程。

## 特点

扩展性很强

* 可以很容易的增加自定义形状的方块
* 可以修改画布的宽度和高度

## 操作说明

* left: 左移
* right: 右移
* down: 加速下落
* up: 变形
* space: 直接落底

另外，考虑到触屏用户，还增加了点击屏幕进行操作的方式。
即，通过点击画布不同区域，同样可以达到控制的目的。

## Bug
在方块没有完全进入画布前，左右移动方块到边界，会导致Bug。

## 演示
<http://manxisuo.tk/#!2013-05-12-tetris>
