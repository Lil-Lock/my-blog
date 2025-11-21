---
date: '2025-11-21T12:13:32+08:00'
draft: false
title: 'My First Post'
---

## 我的第一篇博客

各位好！昨晚我突然萌生一个想法——给自己搭建一个博客，并且部署到公网上。于是我找到了Vercel。

Vercel可以很方便地部署我的网页，我也使用Hugo框架和PaperMod的主题，试图最最简的框架下建立一个博客（当然我对主题的代码做了一些更改，但不大）。具体的方法是，我用Hugo搭建一个博客，然后把这个网页git到Github上，使用Vercel去import这个repo并部署。我每次提交新的帖子到Github时，Vercel就会自动检测并且更新网页。

以下是我写帖子的步骤，这是给我自己看的：

- 第一步，使用 `hugo new posts/xxx.md` 创建一个新的帖子，并且填写内容；
- 第二步，将draft这个属性改为false，然后使用 `hugo server` 渲染静态网页；
- 第三步，把这个网页git到Github上，公网就可以看到新更新的帖子。

好的，这就是我的第一篇博客，再见！