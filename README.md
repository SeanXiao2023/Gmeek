**简体中文** | **[English](README-en.md)**
# Gmeek

一个博客框架，完全基于`Github Pages` 、 `Github Issues` 和 `Github Actions`。不需要本地部署，从搭建到写作，只需要几分钟的时间，3步搭建好博客，第4步就是写作。

- [Demo页面](http://meekdai.github.io/)
- [更新日志](https://meekdai.github.io/post/Gmeek-geng-xin-ri-zhi.html)

### 特性

- UI界面和Github同源，只引入了Github原生CSS：[primer.style](https://primer.style/css)
- 博客写作在Issues中完成后，自动触发Actions执行部署任务
- 评论系统引入[utteranc.es](https://utteranc.es/)

### 安装
1. 创建自己的`XXX.github.io`的仓库，配置自己的秘钥`secrets.meblog`有读写权限等。
2. 在仓库中创建文件`config.json`和`.github/workflows/Gmeek.yml`复制[链接](CONIFG.md)中的代码分别保存。
3. 在Issues中删除多余标签，创建自己的标签，如`link`、`about`、`日常`等。
4. 打开一篇issue，开始写作，保存issue后会自动创建博客内容，片刻后可通过https://XXX.github.io 访问

如果有问题可在本仓库提交[Issues](https://github.com/Meekdai/Gmeek/issues) 或者添加 QQ：`294977308`

### 鸣谢

- [utteranc.es](https://utteranc.es/)
- [primer.style](https://primer.style/css)
- [gitblog](https://github.com/yihong0618/gitblog)
