---
layout: post
title: "How to install opencode easily"
author: "我真的好懒哦~"
date: 2025-07-01
tags: ['opencode','install']
categories: ['opencode','ai agent']
---

# **如何快速安装opencode**

## **1. 安装node.js**

### 1.1 在浏览器搜索(https://nodejs.org/zh-cn)

### 1.2 点击页面中的获取node.js按钮，安装相应版本即可（我用的是windows）
![node.js官网页面图片](../assets/nodejs.png)

### 1.3 安装完成后，在cmd中输入node -v，查看是否安装完成；接下来输入npm -v，查看是否安装完成，显示效果如下：
![node.js安装完成效果图](../assets/nodejs-v.png)

## **2.安装opencode**

### 2.1 在浏览器搜索(https://opencode.ai/zh/download)
### 安装windows版本即可
![opencode官网图片](../assets/opencode-download.png)

### 2.2 安装完成后，在cmd中输入以下命令安装opencode
```
npm i -g opencode-ai
```
![安装opencode完成效果图](../assets/opencodenpm.png)

### 2.3 在cmd中输入以下命令，查看opencode是否安装成功
```
opencode -v
```
![查看opencode版本效果图](../assets/opencode-v.png)

### 2.4 使用opencode：在cmd中输入以下命令启动opencode
```
opencode
```
### 效果图如下：

![opencode启动效果图](../assets/opencodes.png)

### 其中，可以在当前窗口下输入相应命令使用opencode
### 例如，使用
```
/models
```
### 查看可使用的模型列表


## **3. 在vs code中使用opencode**

### 3.1 安装vs code中的opencode插件
#### 1. 打开vs code
#### 2. 点击左侧活动栏中的扩展图标（四个方块组成的图标）
#### 3. 在搜索框中输入"opencode"
#### 4. 找到opencode插件并点击安装
![vs code安装opencode插件效果图](../assets/vscodeop.png)

### 3.2 打开一个文件，在页面右上角的位置点击“opencode”图标，即可使用
![vs code使用opencode效果图](../assets/vscodeopencode.png)
