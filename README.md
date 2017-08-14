# 模拟京东云轮播图部分

## 页面布局
   * 默认基本设置：
```
* {
    padding: 0;
    margin: 0;
    list-style-type: none;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}
```
   * 设置banner容器宽度为100%,高度为固定某一高度。overflow:hidden
   * 设置ul宽度为500%,li宽度为20%
   * 设置banner图片部分的li为相对定位，li中的元素为绝对定位。
   * 使用@keyframes定义动画，

## JS部分
   * 定义pic变量为0，
   * 设置定时器，让pic++,使对应部分显示，其他隐藏
   * 当pic==5时，重置pic=0，继续下一轮轮播