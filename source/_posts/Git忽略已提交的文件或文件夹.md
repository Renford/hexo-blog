---
title: Git忽略已提交的文件或文件夹
subtitle: Git忽略已提交的文件或文件夹
date: '2016-09-09'
catalog: true
header-img: ""
tags: 
- 杂记 
- git

---

## .gitignore 文件的用途
 该文件只能作用于 Untracked Files，也就是那些从来没有被 Git 记录过的文件（从未 add 及 commit 过的文件）。
也就是说，add+commit后的文件或文件夹XX，再在 .gitignore 添加XX，无效。

## 具体操作
1、确保当前修改已提交

```unix
git status
```

2、从 Git 的数据库中删除对于该文件的追踪

```unix
git rm XX -r
```

3、把对应的规则写入 *.gitignore* 文件

4、提交＋推送

```unix
git add -A
git commit -m "git ignore XX"
git push origin master
```

注意：*git rm --cached* 删除的是追踪状态，而不是物理文件
