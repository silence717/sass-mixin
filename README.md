## 常用 sass 的 mixin
* clear-fix ： 清除浮动
* absolute-center ： 绝对定位居中
* absolute-center-flex: flex布局居中
* text-overflow-ellipsis：单行文本超出溢出省略号
* multi-text-overflow-ellipsis： 多行文本超出，最后一行做省略号（ 只支持chrome）
   参数：
    * $number：显示几行
* border-radius： 边框圆角
   参数：
    * $number：圆角多大
* box-shadow ： 阴影，box-shadow可以有多组值，所以在变量参数后面添加...
   参数：
    * $shadow... : 阴影设置
* opacity ：  透明度
   参数：
    * number：比例
* linear-gradient: 背景线性渐变
   参数：
    * $angel: 用角度值指定渐变的方向（或角度）
    * $startColor: 指定开始颜色
    * $endColor: 指定结束颜色
    * background-color: $endColor 背景色默认为结束颜色
* multiLineEllipsis：多行文本溢出省略（支持各个浏览器）
   参数：
    * $lineHeight: 行高
    * $lineCount: 几行
    * $bgColor: 背景色
