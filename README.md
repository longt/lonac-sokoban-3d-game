# 推箱子 3D 游戏

选择语言: [English](./README-en.md) | [中文](./README-zh.md) 

## 介绍

https://github.com/zukahai/sokoban-3d/assets/85035951/bc061f7f-dc4e-4c92-b09d-c8b09f2b0672

这是一款推桶游戏，你的任务是移动黑色立方体找到球的位置，
要移动立方体，您只需按键盘上的箭头键即可。游戏有许多不同的攻击立方体，例如有几个秘密房间、楼梯、门、钥匙等。你需要找到一种方法来克服这些障碍来找到球的位置。

## 游戏体验

访问 [here](https://sokoban-3d.vercel.app/)

## 创建关卡

### 创建自己的关卡

访问地址: https://sokoban-3d.vercel.app/create/

目录:

- [推箱子 3D 游戏](#推箱子-3d-游戏)
  - [介绍](#介绍)
  - [游戏体验](#游戏体验)
  - [创建关卡](#创建关卡)
    - [创建自己的关卡](#创建自己的关卡)
      - [1. 预览你的关卡](#1-预览你的关卡)
      - [2. 更改块高度](#2-更改块高度)
      - [3. 添加行和列](#3-添加行和列)
      - [4. 添加起点](#4-添加起点)
      - [5. 设置终点](#5-设置终点)
      - [6. 添加规则立方体](#6-添加规则立方体)
      - [7. 添加攀爬立方体](#7-添加攀爬立方体)
      - [8. 添加常规开关](#8-添加常规开关)
      - [9. 添加保持开关](#9-添加保持开关)
  - [如何将你的关卡添加到游戏中](#如何将你的关卡添加到游戏中)
  - [贡献](#贡献)

#### 1. 预览你的关卡
按 `Enter`（回车键） 进行预览:

例如：关卡配置如下

![Create Level 1](./assets/images/create1.png)

当按下 `Enter`后, 将预览关卡:

![Create Level 2](./assets/images/create2.png)

#### 2. 更改块高度

通过单击单元格来更改块高度。值的范围从 0 到 9，代表块的高度。

#### 3. 添加行和列

- 按 ↑ 在上方添加一行
- 按 ↓ 在下面添加一行
- 按 ← 在左侧添加一列
- 按 → 在右侧添加一列

#### 4. 添加起点

按“S”并选择要放置起点的单元格。

#### 5. 设置终点

按“K”并选择要放置终点的单元格。

#### 6. 添加规则立方体

按“P”并选择要放置常规立方体的单元格。
 
#### 7. 添加攀爬立方体

按“Q”并选择要放置攀爬立方体的单元格。

#### 8. 添加常规开关

按“B”显示以下内容：

![Add Regular Switch](./assets/images/create3.png)

单击绿色单元格可在激活开关时更改深度。数字 1 表示按下开关时指定单元格的深度将减少 1。数字-1表示按下开关时指定单元格的深度将减少1。
 
选择要放置开关的单元格，然后选择开关将激活的单元格。

#### 9. 添加保持开关

按“M”并按照与常规开关相同的步骤操作。

## 如何将你的关卡添加到游戏中
 
选择`config.js`，里面是当前的级别数。您需要将其增加1。例如，如果当前有21级，则需要将其更改为22。

![Contribute Step 2](./assets/images/contribute2.png)
 
继续选择`assets`，等待其加载，然后选择`levels`。该窗口将如下所示：

![Contribute Step 3](./assets/images/contribute3.png)

单击如下所示的图标创建一个名为“levelX.json”的新文件，其中“X”是您的级别号。例如，如果要创建级别22，则需要创建文件“level22.json”。

  
请记住将“levelX.json”文件中的“indexLevel”部分更改为“X”。例如，如果您要创建级别 22，则需要将其更改为“var indexLevel = 22;”
 
## 贡献

Thank you to the following contributors for their contributions to this game:

<center>
<a href="https://github.com/zukahai/sokoban-3d-game/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=zukahai/sokoban-3d-game" />
</a>
</center>