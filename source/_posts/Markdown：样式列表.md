---

title: Markdown：样式列表

date: 2025-01-20 14:00:00
comments: true
tags:
  - Markdown
  - Hexo
categories: 博客开发
keywords: [Markdown, Hexo, 样式列表]
top_group_index: 1
cover: https://justyy.com/wp-content/uploads/2016/01/markdown-syntax-language.png
---


## 标题
Markdown 支持六级标题：
```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
渲染效果：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 文本样式
```markdown
**加粗** 或 __加粗__
*斜体* 或 _斜体_
***加粗斜体*** 或 ___加粗斜体___
<u>下划线</u>（HTML 标签）
~~删除线~~
```
渲染效果：
- **加粗** 或 __加粗__
- *斜体* 或 _斜体_
- ***加粗斜体*** 或 ___加粗斜体___
- <u>下划线</u>（HTML 标签）
- ~~删除线~~

## 列表
### 无序列表
```markdown
- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
```
- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2

### 有序列表
```markdown
1. 项目 1
2. 项目 2
   1. 子项目 2.1
   2. 子项目 2.2
```
1. 项目 1
2. 项目 2
   1. 子项目 2.1
   2. 子项目 2.2

## 复选列表 
{% checkbox 纯文本测试 %}
{% checkbox checked, 支持简单的 [markdown](https://guides.github.com/features/mastering-markdown/) 语法 %}
{% checkbox red, 支持自定义颜色 %}
{% checkbox green checked, 绿色 + 默认选中 %}
{% checkbox yellow checked, 黄色 + 默认选中 %}
{% checkbox cyan checked, 青色 + 默认选中 %}
{% checkbox blue checked, 蓝色 + 默认选中 %}
{% checkbox plus green checked, 增加 %}
{% checkbox minus yellow checked, 减少 %}
{% checkbox times red checked, 叉 %}

## 引用
```markdown
> 这是一个引用
> 这是一段多行引用
```
> 这是一个引用
> 这是一段多行引用

## 代码
### 行内代码
```markdown
`行内代码`
```
渲染效果：`行内代码`

### 代码块

```markdown
print("Hello, World!")
```


## 链接和图片

```markdown
[百度](https://www.baidu.com)
![图片示例](https://pic1.imgdb.cn/item/64eeb7c8661c6c8e5488e091.png)
```

渲染效果：[百度](https://www.baidu.com)

![图片示例](https://pic1.imgdb.cn/item/64eeb7c8661c6c8e5488e091.png)



## 分割线
```markdown

***

```

渲染效果：

***



## HTML 标签
```markdown
<div style="color: red;">红色文本</div>
```

渲染效果：
<div style="color: red;">红色文本</div>

---


