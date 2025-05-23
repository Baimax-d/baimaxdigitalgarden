---
{"dg-home":true,"dg-publish":true,"permalink":"/home/","tags":["gardenEntry"],"dgPassFrontmatter":true}
---

![Pasted image 20250523143748.png](/img/user/Pasted%20image%2020250523143748.png)

您可以在[笔记设置](https://dg-docs.ole.dev/getting-started/03-note-settings/)中在数字花园中启用以下功能：

- 局部图
- 全球图
- 反向链接
- 目录
- 文件树导航
- 链接预览
- 搜索
- 前端标签

此外，花园支持您笔记中的各种格式和内容类型。

---

## 维基链接

像通常在Obisidan中一样，使用`[[Wikilink]]`语法链接

### 标题链接

链接到特定标题的工作方式与黑曜石中的工作方式相同  
`[[My Note#Note header]]`

### 阻止链接

链接到特定块的工作方式与黑曜石中的工作方式相同  
`[[My Note#^123abc]]`

### 自定义链接名称

更改维基链接的显示文本的工作方式与黑曜石中的工作方式相同  
![清洁Shot 2023-01-10在18.07.56@2x.png|250](https://dg-docs.ole.dev/img/user/img/CleanShot%202023-01-10%20at%2018.07.56@2x.png)

---

## 代码块

![CleanShot 2022-11-13在15.34.22@2x.png](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2015.34.22@2x.png)

```javascript
let a = 5;
```

![清洁日票 2022-11-13 15.34.59@2x.png|200](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2015.34.59@2x.png)  
`Some inline code`

---

## 数据视图查询

```(dataview)
list from "Advanced"
```

- [与其他解决方案的比较](https://dg-docs.ole.dev/advanced/comparison-to-other-solutions/)
- [添加自定义组件](https://dg-docs.ole.dev/advanced/adding-custom-components/)
- [内容定制](https://dg-docs.ole.dev/advanced/content-customization/)
- [配置构建管道](https://dg-docs.ole.dev/advanced/configure-build-pipeline/)
- [数据视图查询](https://dg-docs.ole.dev/advanced/dataview-queries/)
- [CSS 定制](https://dg-docs.ole.dev/advanced/css-customization/)
- [备注特定设置](https://dg-docs.ole.dev/advanced/note-specific-settings/)
- [托管替代方案](https://dg-docs.ole.dev/advanced/hosting-alternatives/)
- [方法与技巧](https://dg-docs.ole.dev/advanced/tips-and-tricks/)
- [精细的访问令牌](https://dg-docs.ole.dev/advanced/fine-grained-access-token/)
- [添加评论](https://dg-docs.ole.dev/advanced/guides-and-how-tos/adding-comments/)
- [添加分析](https://dg-docs.ole.dev/advanced/guides-and-how-tos/adding-analytics/)
- [路标](https://dg-docs.ole.dev/advanced/roadmap/)

{.block-language-dataview}  
有关数据视图的更多详细信息可在此处找到：[数据视图查询](https://dg-docs.ole.dev/advanced/dataview-queries/)

---

## 呼叫

```
> [!NOTE] Note title
> Information
```

备注标题  

信息

```
> [!WARNING] A warning
> This is a warning
```

警告  

这是一个警告

### 折叠呼叫

```
> [!NOTE]+ Open by default
> Folding/Collapsable callout
```

默认打开  

折叠/可折叠的呼叫

```
> [!FAQ]- Closed by default
> Folding/Collapsable callout
```

默认关闭  

### 嵌套呼叫

```
> [!TIP] Nested callouts
> Text inside the tip callout
> > [!EXAMPLE] Inner callout
> > Multiple nesting layers
> > > [!TODO] Inner inner callout
```

嵌套呼叫  

提示内的文本

内部呼叫  

多个嵌套层

内在内内呼

---

## MathJax/LaTex

[MathJax参考](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

```
$\frac{1}{0} = \infty$
```

---

## 标签

点击下面的标签查看具有相同标签的其他页面。

#示例标签

---

## 嵌入/转入图像

![清洁Shot 2022-11-13在14.24.21@2x.png|250](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2014.24.21@2x.png)

![黑曜石标志.png](https://dg-docs.ole.dev/img/user/img/obsidianlogo.png)

## 转入的文件

### 整个文件

![2022年11月13日14.24.50@2x.png|250](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2014.24.50@2x.png)

[](https://dg-docs.ole.dev/example-pages/transcluded-document/)

这是一份转含的笔记。

这是转接文档中的一个块

### 这是一个标题

内容

#### 这是一个副标题

### 标题块

![清洁Shot 2023-01-05在17.22.10.png](https://dg-docs.ole.dev/img/user/img/CleanShot%202023-01-05%20at%2017.22.10.png)

[](https://dg-docs.ole.dev/example-pages/transcluded-document/#this-is-a-header)

### 这是一个标题

内容

#### 这是一个副标题

### 单块

![CleanShot 2023-01-05在17.22.27.png](https://dg-docs.ole.dev/img/user/img/CleanShot%202023-01-05%20at%2017.22.27.png)

[](https://dg-docs.ole.dev/example-pages/transcluded-document/#02502a)

这是转接文档中的一个块

同样值得注意的是，转包含_不需要_dg-publish属性。它们的行为与图像相同。如果您将某物转入文档中，并发布该文档，则其中转入的所有内容都将像该注释的一部分一样发布。

（关于转接的更多详细信息可以在这里阅读：[内容定制#转接](https://dg-docs.ole.dev/advanced/content-customization/#tranclusions)）

---

## 埃克卡利拉

![清洁Shot 2022-11-13在14.25.34@2x.png|350](https://dg-docs.ole.dev/img/user/img/CleanShot%202022-11-13%20at%2014.25.34@2x.png)
