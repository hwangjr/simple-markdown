## 代码块

### 基本用法
1. 代码段用<code>\`</code>表示，即inline代码，分别对应`<code>`, `<pre>`标签
2. 代码块用<code>\`\`\`</code>来表示（GFM语法-Github Flavored Markdown，部分编译器不支持），再指定其语言类型，实现语法高亮。围栏式代码块可以减少缩进使用，使用很方便。
3. 缩进用四个空格来表示

示例：
```
`System.out.println();`可系统打印出消息
```

<code>\`\`\`</code>

public void print(String text) {
        System.out.println(text);

}

<code>\`\`\`</code>

<code>\`\`\`</code> java

public void print(String text) {
        System.out.println(text);

}

<code>\`\`\`</code>

效果：

`System.out.println();`可系统打印出消息

```
public void print(String text) {
    System.out.println(text);
}
```

``` java
public void print(String text) {
    System.out.println(text);
}
```
