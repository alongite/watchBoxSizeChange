# 监听HTMl元素大小变化

很多时候没有办法知道元素大小改变了，比如父级元素大小受子元素影响，这时候需要对父元素进行监听，常规的做法是通过setInterval或者requestAnimationFrame来循环获取元素的大小，从而判断是否大小改变。

这个代码是参考 https://blog.crimx.com/2017/07/15/element-onresize/ 这篇文章的观点进行监听的，通过监听元素的scroll事件判断元素大小是否发生变化了。
