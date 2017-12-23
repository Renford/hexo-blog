---
title: Markdown常用语法
subtitle: Markdown常用语法
date: '2016-09-09'
catalog: true
header-img: "markdown.jpg"
tags: 
- 杂记 
- markdown

---

## 1、标题
Markdown 语法：

```unix 
# 第一级标题
## 第二级标题
###### 第六级标题
```

效果如下：

# 第一级标题
## 第二级标题 
###### 第六级标题 

## 2、强调

Markdown 语法：

```unix
*斜体*
**加粗一**
__加粗二__
_下划线_
~~删除线~~
```

效果如下：

*斜体*    
**加粗一**    
__加粗二__    
_下划线_    
~~删除线~~

## 3、列表

### 无序列表

Markdown 语法：

```
* 项目一 无序列表 `* + 空格键`
* 项目二
    * 项目二的子项目一 无序列表 `TAB + * + 空格键`
    * 项目二的子项目二
```

效果如下：

* 项目一 无序列表 `* + 空格键`
* 项目二
    * 项目二的子项目一 无序列表 `TAB + * + 空格键`
    * 项目二的子项目二

### 有序列表

Markdown 语法：

```
1. 项目一 有序列表 `数字 + . + 空格键`
2. 项目二
    1. 项目二的子项目一
    2. 项目二的子项目二
```

效果如下：

1. 项目一 有序列表 `数字 + . + 空格键`
2. 项目二
    1. 项目二的子项目一
    2. 项目二的子项目二

### 任务列表

Markdown 语法：

```
- [ ] 任务一 未做任务 `- + 空格 + [ ]`
- [x] 任务二 已做任务 `- + 空格 + [x]`
```

效果如下：

- [ ] 任务一 未做任务 `- + 空格 + [ ]`
- [x] 任务二 已做任务 `- + 空格 + [x]`

## 4、图片

Markdown 语法：

```
![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif)
格式: ![text](url)
```

效果如下：

![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif)


## 5、链接

Markdown 语法：

```
文字链接：[GitHub](http://github.com)
自动生成连接：<http://www.github.com/>
```

效果如下：

文字链接：[GitHub](http://github.com)    
自动生成连接：<http://www.github.com/>

## 6、引用

### 行内引用

Markdown 语法：

```
像这样即可：`code`
```

效果如下：

像这样即可：`code`

### 多行引用

Markdown 语法：

```
\`\`\`
function fancyAlert(arg) {
    if(arg) {
    $.facebox({div:'#foo'})
    }
}
\`\`\`
```
效果如下：

```js
function fancyAlert(arg) {
    if(arg) {
    $.facebox({div:'#foo'})
    }
}
```

### 区块引用
Markdown 语法：

```
某某说:
> 第一行引用
> 第二行引用
```

效果如下：

某某说:
> 第一行引用    
> 第二行引用

## 7、表格

Markdown 语法：

```
第一格表头 | 第二格表头
--------- | -------------
第一列第一格 | 第二列第一格
第一列第二格 多加文字 | 第二列第二格
```

效果如下：

第一格表头 | 第二格表头
--------- | -------------
第一列第一格 | 第二列第一格 多加文字
第一列第二格 多加文字 | 第二列第二格

## 8、目录

Markdown 语法：

```
{:toc}
[toc]
```

效果如下：

{:toc}
[toc]