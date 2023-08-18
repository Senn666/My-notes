---
title:Hinas_页面修改
author:SENN
date:2023年8月18日
---

# Hinas_页面修改

## 系统导航页
背景图初始位置为：`/var/www/html/img/icloud.png` 
引用该地址的CSS文件位于：`/var/www/html/css/style.css`

**原代码**
```CSS
    body {
        height: 100%;
        font-size: 100%;
        background: url(../img/icloud.png) repeat fixed !important;
        background-attachment: fixed;
        font-family: 'Helvetica Neue','Microsoft Yahei',SimHei,sans-serif
    }
```
**更改后**
```CSS
background: url(../img/这里是新图片的名字) !important;
```

## 终端登陆欢迎页
文件位于：`/etc/profile.d/99-helloworld.sh`
