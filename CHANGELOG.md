# Change Log

Masm-code 改动日志。[格式参考](http://keepachangelog.com/)

## [1.2.0] - 2020-03-15

### 新增
+ 新的命令`在DOSBox中编译运行`。自动编译运行代码

## [1.1.3] - 2020-03-13

### 改动
+ 修复了代码片段Assume的语法错误，删除Mov，增加Starter快速生成起始代码框架

## [1.1.2] - 2020-03-13

### 改动
+ 语法高亮规则调整
+ 增加代码片段PROC（定义过程）、MACRO（定义宏）、TESTJ、CMPJ（实现分支语句）、LOOP（编写循环）
+ 更换清晰度更高的logo

## [1.1.1] - 2020-03-11

### 改动
+ 修复了变量名中的数字被当作立即数渲染的bug

## [1.1.0] - 2020-03-11

### 新增
+ Intel 8086汇编的code snippet（SEG,ASSUME,STR,MOV）
+ 语法高亮增加新的匹配模式（DUP、?、以及中文符号）

### 改动
+ 换了logo

## [1.0.4] - 2020-03-10

### 改动
+ 修复了Masm和DOSBox无法下载的问题，现在**应该**不会再遇到文件大小0kb的问题了
+ 略微改动了logo


## [1.0.3] - 2020-03-09
+ 尝试失败，改了回来

## [1.0.2] - 2020-03-09
+ 尝试移除node_modules减小扩展体积

## [1.0.1] - 2020-03-09

### 改动
+ 修复了扩展没有logo的问题（其实就是我忘了）

## [1.0.0] - 2020-03-09

### 新增
+ Intel 8086汇编的语法高亮
+ 自动下载Masm和DOSBox。