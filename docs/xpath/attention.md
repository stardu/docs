# 注意事项

获取xpath位置有两种方法，一直是直接在浏览器中右键`Copy Xpath`，这种一般是绝对位置，另一种是自己根据element属性，编写相对位置。

如果该网站允许加载JavaScript或者浏览器有渲染，会导致直接在浏览器中复制的Xpath位置不正确，所以建议是点击右键——显示网页源代码，从这里查看网页结构，一般可以根据`class`的`name`来编写xpath。




# 作业

自己尝试使用xpath、css两种选择器去解析 [腾讯新闻](https://news.qq.com/) 的标题与内容，看看自己使用哪种解析方法比较顺手。
