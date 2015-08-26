## 图片

### 基本用法
图片和链接的标识很相似，只是在最前面添加`!`。
1. 行内式：方括号后加圆括号即可
2. 参考式：链接文字后面加上另一个方括号，第二个方括号填入标识的标记
3. 目前为止，Markdown还无法指定图片的寬高，如果需要只能使用`<img>`标签

示例：
```
![Markdown](http://daringfireball.net/graphics/logos/ "Markdown")

![Markdown][MarkdownPic]
[MarkdownPic]: http://daringfireball.net/graphics/logos/ "Markdown"
```

效果：

![Markdown](http://daringfireball.net/graphics/logos/ "Markdown")

![Markdown][MarkdownPic]
[MarkdownPic]: http://daringfireball.net/graphics/logos/ "Markdown"
