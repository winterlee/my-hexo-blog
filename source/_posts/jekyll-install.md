---
title: jekyll 安装
date: 2020-05-25 14:04:27
tags:
---

## 安装 jekyll
```
gem install jekyll 卡死状态
```

### 尝试解决
```
gem sources 显示当前源
gem sources -r https://rubygems.org/ 删除源
gem sources -a https://gems.ruby-china.com/ 添加淘宝源 或 其他源

```
### ruby版本过低,先不管它，先安装bundler

```
gem install bundler 正常安装了
bundler -v 查看安装成功了
```
