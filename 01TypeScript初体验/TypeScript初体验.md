# TypeScript初体验

## TypeScript 概述

TypeScript（简称：TS）是 JavaScript 的超集（JS 有的 TS 都有）

TypeScript = Type + JavaScript（为 JS 添加了类型系统）

TypeScript 是微软开发的开源编程语言，设计目标是开发大型应用。 可以在任何浏览器、任何计算机、任何操作系统上运行

## TypeScript 相比 JS 的优势

悲伤的故事：男程序员都是好男人，因为他们总会在电脑前问：我到底又错在哪了？ 

JS 的类型系统存在“先天缺陷” ，绝大部分错误都是类型错误（ Uncaught TypeError ）

- 优势一：类型化思维方式，使得开发更加严谨，提前发现错误，减少改 Bug 时间
- 优势二：类型系统提高了代码可读性，并使维护和重构代码更加容易
- 优势三：补充了接口、枚举等开发大型应用时 JS 缺失的功能
- Vue 3 源码使用 TS 重写，释放出重要信号：TS 是趋势
-  Angular 默认支持 TS；React 与 TS 完美配合，是很多大型项目的首选

## 安装

- 安装node.js（略）
- npm i -g typescript 
- npm i –g ts-node

## ts变量类型

