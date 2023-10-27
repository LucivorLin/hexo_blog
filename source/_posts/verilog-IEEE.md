---
title: 在IEEE标准中进一步学习verilog
date: 2023-10-27 11:26:59
tags:
---

# 前言

`Verilog` 作为一门硬件描述语言，应用十分广泛。但是无论是[HDLBits (01xz.net)](https://hdlbits.01xz.net/wiki/Main_Page)还是有关的教材，`Verilog`相较于C语言等程序设计语言，对我个人来说，有以下几个体会：

- 除了基础电路单元以外，设计方法等相关内容过于零碎化
- 很多HDL语言的细节处理尚不清楚，难以分辨合法使用的界限
- 不清楚verilog语言对应的FPGA/ASIC资源的综合原理，导致不清楚某些语法功能的结合是否能正常运行
- 有时候会因为自己的项目界限导致语言上的“信息茧房”，难以提升自己对HDL的综合理解

因此，我个人认为自己需要一次权威的、标准的、有系统结构性的对IEEE verilog标准的学习，以期跳出所谓的硬件入门阶段。

**`IEEE Standard for Verilog Hardware Description Language`** 是IEEE牵头指定的、Xilinx等企业参与制定的verilog语言标准。较新的、常用的为2005年版（由于年份情况，在网上常见的是pdf文件）。该标准不像高级设计语言标准更新周期短，长期未做变更。

# 总体结构·目录

HDL不能轻易地用程序设计语言的思路和框架去套，这也是HDL相对难以系统掌握的重要原因（也很难找到关于其的描述，往往学生学到verilog这步鉴于学生能力和课程关系均为自学，就会导致不同于课本教授，导致依赖HDLBits、菜鸟教程等网络学习方法，见效快但零碎、路子野，导致认识不全面、掌握不够深）。

标准文档有以下章节，可以以此作为参考：

1. 概览 (Overview)
2. 参考文献 (Normative references)
3. 词法约定 (Lexical conventions)
4. 数据类型 (Data types)
5. 表达式 (Expressions)
6. 电路布置 (Assignments)
7. 门和开关级建模 (Gate- and switch-level modeling)
8. 用户定义的原语 (User-defined primitives, UDPs)
9. 行为建模 (Behavioral modeling)
10. 任务和函数 (Tasks and functions)
11. 调度语义 (Scheduling semantics)
12. 层次结构 (Hierarchical structures)
13. 配置设计的内容 (Configuring the contents of a design)
14. 指定块 (Specify blocks)
15. 时序检查 (Timing checks)
16. 使用标准延迟格式（SDF）的反向注释 (Backannotation using the standard delay format)
17. 系统任务和方法 (System tasks and functions)
18. VCD时序信号储存文件 (Value change dump (VCD) files)
19. 编译器指令 (Compiler directives)
20. 编程语言接口（PLI）概述 (Programming language interface overview)

26. Verilog过程接口（VPI）的使用 (Using Verilog procedural interface (VPI) routines)
27. VPI例程定义(VPI routine definitions)
28. (Protected envelopes)

