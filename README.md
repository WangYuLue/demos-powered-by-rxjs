# 一些基于 RXJS 的有趣 Demo

interesting demos powered by `rxjs`.

the build tool is `parcel`.

`ts` runtime powered by `ts-node`.

## 01

将演示如何基于 pacel、react、ts 构建一个极简前端项目。

## 02

实现一个**进度条轮训查看状态**的需求。

会有个上传接口，上传文件后服务端会处理文件，并可以通过接口查看处理进度。

> 我们将分别用 **原生写法** 和 **rxjs写法** 来实现，这样可以出两种风格写法的差异。

## 03

来实现一个**简单的拖拽功能**。

要求鼠标在小方块上按下后能够拖着小方块进行移动；鼠标放开后，则运动停止。

> 我们将分别用 **原生写法** 和 **rxjs写法** 来实现，这样可以出两种风格写法的差异。

## 04

04 是 03 的进阶，在 03 的基础上实现小方块拖拽接龙。

![](./images/01.gif)

细节：给定 n 个小方块，要求拖拽第一个小方块进行移动，后续的小方块能够以间隔 0.1s 的时间跟着之前的小方块进行延迟模仿运动。

> 我们将分别用 **原生写法** 和 **rxjs写法** 来实现，这样可以出两种风格写法的差异。
