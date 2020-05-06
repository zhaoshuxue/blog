---
title: 搭建VUE开发环境
date: 2020-05-06 22:28:59
categories: "vue"
tags: 
  - vue
  - js
---
## 准备工作

> 安装nodejs
> 安装npm

## 安装vue-cli脚手架

```
npm install --global vue-cli
```

验证： 输入`vue`

<!--more-->

## 创建项目 

```
vue init webapck projectName
```

输入之后就一直回车，直到出现是否要安装vue-route，这个我们在项目要用到，所以就输入y 回车

下面会出现是否需要js语法检测，这个我们暂时用不到，就可以直接输入no，后面的都可以直接输入no，都是我们暂时用不到的

## 安装依赖，运行

进入`projectName`文件夹，输入： `npm install`

运行： `npm run dev`

localhost:8080