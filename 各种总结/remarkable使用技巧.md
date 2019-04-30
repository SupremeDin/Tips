本人总结的常用快捷键
撤销：Ctrl/Command + Z
时间：Ctrl/Command + T
加粗：Ctrl/Command + B
斜体：Ctrl/Command + I
删除：Ctrl/Command + D
链接：Ctrl/Command + L
分界线Ctrl/Command + H
标记：Ctrl/Command + Shift + H
插入图片：Ctrl/Command + Shift + I
引用：>

以下内容均是markdown编辑器的介绍，有些快捷键与remarkable是一样的，不过也有不好使的，大家何以借鉴一下。
mermaid语法说明

合理的创建标题，有助于目录的生成
直接输入1次#，并按下space后，将生成1级标题。
输入2次#，并按下space后，将生成2级标题。
以此类推，我们支持6级标题。有助于使用TOC语法后生成一个完美的目录。

在 Markdown 文档中，可以直接采用 HTML 标记插入空格（blank space），而且无需任何其他前缀或分隔符。具体如下所示：

插入一个空格 (non-breaking space)
　　　　&nbsp;    或    &#160;     或      &#xA0;

插入两个空格 (en space)
　　　　&ensp;     或    &#8194;   或      &#x2002;

插入四个空格 (em space)
　　　　&emsp;    或    &#8195;   或      &#x2003;

插入细空格 (thin space)
　　　　&thinsp;   或     &#8201;  或      &#x2009;

　　注意：不要漏掉分号。
列表
列表可以分为无序列表和有序列表，它们分别对应于 html 中的 <ol></ol> 和<ul></ul> 。这个也是非常常用的。

Markdown 中的无序列表，你只需要在文字前面加上 - 就可以了。

Markdown 中的有序列表，只需要在文字前面加上 1. 就可以了（注意了：事实上，这个可以是任意一个阿拉伯数字再加上一个英文的句号，都可以。而不一定是 1.，也可以是2.，甚至是 111.，对于这个阿拉伯数字到底是几没有要求。Markdown 中会自动按着最正确的数字顺序进行“有序排列”。）。