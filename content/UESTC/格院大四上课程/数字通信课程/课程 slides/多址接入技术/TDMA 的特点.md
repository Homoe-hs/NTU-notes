---
title: TDMA 的特点
date: 2023-12-18 18:58
modification date: 2023 十二月 18日 星期一 18:58:11
aliases:
  - 
tags:
  - 
publish: "true"
---

## 优点

1. **多信道支持：** 允许每个载波或射频通道上存在多个信道，提高频谱利用率。
2. **突发传输：** 由于采用时分共享原则，实现了突发传输，发射机在空闲期间可以关闭，节省能量。
3. **带宽灵活：** 可根据调制方案和每个载波通道上的语音信道数量等因素调整带宽，适应不同需求。
4. **灵活的数据速率：** 通过为不同用户分配多个时隙，实现了根据用户需求灵活调整的数据速率。

## 缺点

1. **高 ISI：** 由于较高的传输符号速率，导致较高的间符号干扰（ISI），需要使用自适应均衡器来处理。
2. **高帧同步开销：** 需要分配总传输比特数中的相当部分用于同步目的和信道识别，导致帧同步开销较高。
3. **信道保护：** 为了分隔用户，需要引入保护时隙，增加了系统的复杂性和开销。
