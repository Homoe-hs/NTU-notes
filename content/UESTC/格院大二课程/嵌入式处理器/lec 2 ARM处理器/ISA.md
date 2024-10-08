---
aliases:
  - Instruction Set Architecture
  - 指令集体系
  - 指令集结构
  - ISA
  - 指令集
tags: 
publish: "true"
---

# 指令集架构

## 定义

指令集架构是计算机体系结构中与程序设计有关的部分，包含了基本数据类型，指令集，寄存器，寻址模式，存储体系，中断，异常处理以及外部 I/O。指令集架构包含一系列的 opcode，即操作码（机器语言），以及由特定处理器执行的基本命令。

不同的处理器“家族”——例如Intel IA-32和x86-64、IBM/Freescale Power和ARM处理器家族——有不同的指令集架构。

指令集体系与微架构（一套用于执行指令集的微处理器设计方法）不同。使用不同微架构的电脑可以共享一种指令集。例如，Intel的Pentium和AMD的AMD Athlon，两者几乎采用相同版本的x86指令集体系，但是两者在内部设计上有本质的区别。

一些虚拟机支持基于 Smalltalk，Java 虚拟机，微软的公共语言运行时虚拟机所生成的字节码，他们的指令集体系将 bytecode（字节码）从作为一般手段的代码路径翻译成本地的机器语言，并通过解译执行并不常用的代码路径，全美达以相同的方式开发了基于 x86 指令体系的 VLIW 处理器。

