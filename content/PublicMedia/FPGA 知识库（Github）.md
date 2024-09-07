# FPGA 知识库（Github）

本项目收集了github中许多FPGA开源项目。主要目的是分享FPGA的优秀文章，学习网站，以及开源项目。

**知识库旨在为学习FPGA的小伙伴提供一系列：**

- 分享FPGA入门路线
- 分享开源的FPGA项目
- 免费且靠谱的FPGA学习资料
- FPGA岗求职面试指南
- 分享一系列原创文章和项目

*赠人玫瑰手有余香。知识库会持续保持更新，欢迎收藏品鉴*

## 一、开发环境搭建与软件包下载

vivado版本越高，需要安装的存储空间越大，需要性能强大的CPU和大运行内存才能跑的动。建议根据自己的电脑配置选择版本，笔记本电脑建议上手vivado2017.4，台式机电脑安装更好，运行和综合布线速度更快，linux系统比windows系统运行速度更快。

**vivado安装包**：

- [vivado 2017.4](https://pan.baidu.com/s/192qKequAoHLnk8fHWSmC3A)（提取码：24iu）
- [vivado2018](https://pan.baidu.com/s/1e69TFTj--aKQHHJFGEQ78g)（提取码：9wen）
- [vivado 2019.1](https://pan.baidu.com/s/1eATN-tRC-rKfoBmxBe8RjQ)（提取码：plr3）

**Quartus安装包**：

- [Quartus9.1](https://pan.baidu.com/s/1xjgVAOXvIlDm0_Q7Lk3nQA)（提取码：0zhv）
- [Quartus12.0](https://pan.baidu.com/s/15aXxE7sqb8-j1lOgK58CfA)（提取码：uff4）
- [Quartus13.0](https://pan.baidu.com/s/1hyJgM4JRY63hG6AURtmvtg)（提取码：qmlc）

**Modelsim安装包**：

- [Modelsim](https://pan.quark.cn/s/457f6d046d8a)

*更多版本不断更新中，请关注公众号《FPGA入门到精通》*

## 二、FPGA入门

### 数字电路基础

数字电路是FPGA的基础，可以初步了解和学习，遇到问题可以再来书里找相关知识学习。

- [《数字电子技术基础》第5版 -- 阎石](https://pan.quark.cn/s/4826f478cb94)

### verilog HDL教程

> HDL语言(Hardware Design Language)，用于FPGA开发建模，语法类似于软件C语言，但设计思想完全不一样，类似于建模

- [《Verilog数字系统设计教程》夏宇闻](https://pan.quark.cn/s/56886154ed1e)

### system verilog 教程

> system verilog主要用于编写测试仿真激励，验证verilog HDL设计的电路是否正常。

- [《SystemVerilog验证方法学》夏宇闻](https://pan.quark.cn/s/79dd6d6ce842)

### 网上教程

- [米联客ZNYQ入门教程](https://pan.quark.cn/s/73a9505e778b)
- [Verilog那些事儿](https://pan.quark.cn/s/8d8cd4d58959)

### 时序约束

- [猫叔的FPGA时序约束教程](https://pan.quark.cn/s/ba0f96126c62)
- [UG903](https://docs.xilinx.com/r/en-US/ug903-vivado-using-constraints)

### 官方网站

- [Xilinx官网](https://china.xilinx.com/)
- [Inter FPGA（altera）官网](https://www.intel.cn/content/www/cn/zh/products/programmable.html)
- [Lattice官网](https://www.latticesemi.com/zh-CN/)

### 开发环境搭建

- [FPGA开发软件（vivado + modelsim）环境搭建](https://blog.csdn.net/mengzaishenqiu/article/details/129000700?csdn_share_tail=%7B%22type%22%3A%22blog%22%2C%22rType%22%3A%22article%22%2C%22rId%22%3A%22129000700%22%2C%22source%22%3A%22mengzaishenqiu%22%7D)

### 练习网站推荐

> HDLBits可以提供 Verilog基础教程，内容丰富，包括Verilog的基础语法、由逻辑门与触发器组成的电路、组合时序电路的概念、模块层级概念、testbench等的编写，还能够在线仿真，并提供结果对比，非常好用的一个网站。

- [HDLbits](https://hdlbits.01xz.net/wiki/Main_Page)

## 三、FPGA进阶

### 器件选型指南

Xilinx公司的器件选型指南

- [低成本器件的选型指南](https://www.eetree.cn/wiki/_media/cost-optimized-product-selection-guide.pdf)
- [7系器件的选型指南](https://www.eetree.cn/wiki/_media/7-series-product-selection-guide.pdf)
- [Ultrascale系列器件的选型指南](https://www.eetree.cn/wiki/_media/ultrascale-fpga-product-selection-guide.pdf)
- [Ultrascale+系列器件的选型指南](https://www.eetree.cn/wiki/_media/ultrascale-plus-fpga-product-selection-guide.pdf)

[Altera/Intel公司的器件选型指南](https://www.eetree.cn/wiki/_media/intel_product-catalog.pdf)

[Lattice Semi公司的器件选型指南](https://www.eetree.cn/wiki/_media/psg_2019_i0211k_rev20.pdf)

### ZNYQ

- [UG585](https://docs.xilinx.com/v/u/en-US/ug585-Zynq-7000-TRM)
- [Znyq Book](https://pan.baidu.com/s/1hkYBfdRZJH0m4Hs-tY_95A)（提取码：5498）
  
  ### HLS
- [UG1399-HLS-编程指南](https://docs.xilinx.com/r/zh-CN/ug1399-vitis-hls)
- [HLS开发手册](https://pan.baidu.com/s/1qJEc6AulWpNSxCgSJ6oM6Q)（提取码：ih7q）
- [HLS工具使用手册](https://pan.baidu.com/s/1MC-gXmSOvc5ROtNSp_9n1A)（提取码：vl0r）
- [hls_bluebook](https://pan.baidu.com/s/1xLJx8Lv6S8kMrFwEV3SBAw)（提取码：h1ud）
  
  ### 硬件驱动
- [xilinx wiki](https://xilinx-wiki.atlassian.net/wiki/spaces/A/overview?homepageId=18844350)
- [Xilinx-github](https://github.com/Xilinx)

## 四、开源项目

### opencores 开源网站

- [opencores](https://opencores.org/)

### PYNQ

> PYNQ已广泛用于机器学习研究和原型设计

- [xilinx PYNQ](https://github.com/Xilinx/PYNQ)
- [RFSoC QPSK Transceiver](https://github.com/strath-sdr/rfsoc_qpsk)
- [PYNQ-PRIO](https://github.com/byuccl/PYNQ-PRIO)
- [PYNQ-Helloworld](https://github.com/Xilinx/PYNQ-HelloWorld)
- [RISC-V-On-PYNQ](https://github.com/drichmond/RISC-V-On-PYNQ)
- [PYNQ Extended Kalman Filter (EKF)](https://github.com/sfox14/pynq-ekf)
- [spooNN](https://github.com/fpgasystems/spooNN)
- [iSmartDNN](https://github.com/onioncc/iSmartDNN)
- [DAC 2018 System Design Contest-TGIIF](https://github.com/hirayaku/DAC2018-TGIIF)
- [cv2PYNQ](https://github.com/wbrueckner/cv2pynq)
- [PYNQ_Projects](https://github.com/Pieter-Berteloot/PYNQ_Projects)
- [ZipML-PYNQ](https://github.com/fpgasystems/ZipML-PYNQ)
- [PYNQ-BOT](https://github.com/Xilinx/PYNQ-BOT)
- [PYNQ Light Cube](https://github.com/sonnyhcl/PYNQ-Light-Cube)
- [IIoT-SPYN](https://github.com/Xilinx/IIoT-SPYN)
- [PYNQ-Networking](https://github.com/Xilinx/PYNQ-Networking)
- [QNN-MO-PYNQ PIP INSTALL Package](https://github.com/Xilinx/QNN-MO-PYNQ)
- [LSTM-PYNQ Pip Installable Package](https://github.com/tukl-msd/LSTM-PYNQ)
- [BNN-PYNQ PIP INSTALL Package](https://github.com/Xilinx/BNN-PYNQ/)
- [PYNQ PR Overlay](https://github.com/AEW2015/PYNQ_PR_Overlay)
- [PYNQ - Computer Vision](https://github.com/Xilinx/PYNQ-ComputerVision)
- [PynqGzip](https://gitlab.dcae.pub.ro/research/PynqGzip)
- [SPynq: Spark on Pynq](https://github.com/AcceleratedCloud/SPynq)
- [FIR Filter with DMAs in SDSoC Ported to python](https://github.com/hackwa/pynqfire/blob/master/notebooks/fir.ipynb)
- [PYNQ-Classification](https://github.com/awai54st/PYNQ-Classification)
- [FGPU Demo using PYNQ on the Xilinx ZC706](https://github.com/malkadi/FGPU_IPython/)
- [Vectorblox PYNQ Fork](https://github.com/VectorBlox/PYNQ)

### FPGA4FUN

> fpga4fun是一个非常不错的FPGA免费学习网站

#### 基础项目：

- [音乐盒](https://www.fpga4fun.com/MusicBox.html)
- [LED显示](https://www.fpga4fun.com/Opto.html)
- [乒乓球游戏](https://www.fpga4fun.com/PongGame.html)
- [R/C伺服电机](https://www.fpga4fun.com/RCServos.html)
- [文本LCD模块的控制](https://www.fpga4fun.com/TextLCDmodule.html)
- [正交解码](https://www.fpga4fun.com/QuadratureDecoder.html)
- [PWM和1位DAC](https://www.fpga4fun.com/PWM_DAC.html)
- [消抖动](https://www.fpga4fun.com/Debouncer.html)
- [跨越时钟域](https://www.fpga4fun.com/CrossClockDomain.html)
- [计数的艺术](https://www.fpga4fun.com/Counters.html)
- [外部贡献](https://www.fpga4fun.com/ExternalContributions/)
  
  #### 接口项目：
- [RS-232接口](https://www.fpga4fun.com/SerialInterface.html)
- [I2C接口](https://www.fpga4fun.com/I2C.html)
- [SPI接口](https://www.fpga4fun.com/SPI.html)
- [EPP接口](https://www.fpga4fun.com/EPP.html)
- [JTAG接口](https://www.fpga4fun.com/JTAG.html)
- [SD card接口](https://www.fpga4fun.com/SD.html)
- [PCI接口](https://www.fpga4fun.com/PCI.html)
- [PCI Express接口](https://www.fpga4fun.com/PCI-Express.html)
- [Ethernet接口](https://www.fpga4fun.com/10BASE-T.html)
- [HDMI接口](https://www.fpga4fun.com/HDMI.html)
- [SDRAM控制器](https://www.fpga4fun.com/SDRAM.html)
  
  #### 高阶项目：
- [数字示波器](https://www.fpga4fun.com/digitalscope.html)
- [图像化LCD屏](https://www.fpga4fun.com/GraphicLCDpanel.html)
- [DDS直接数字合成](https://www.fpga4fun.com/DDS.html)
- [CNC步进电机控制](https://www.fpga4fun.com/CNC.html)
- [Spoc CPU软核](https://www.fpga4fun.com/spoc.html)

### 通信类

- [高频SDR收发模块项目](https://github.com/softerhardware/Hermes-Lite2)
- [SDR](https://github.com/TAPR/DCP6)
- [基于Cyclone III的VHF SDR接收器](https://github.com/marsohod4you/FPGA_SDR)
- [基于Cyclone III的FM Radiosender](https://github.com/marsohod4you/FPGA_FM_transmitter)
- [用Verilog实现的GPS接收器](http://www.aholme.co.uk/GPS/Main.htm)

### 音视频

- [音合成器OPL3](https://github.com/gtaylormb/opl3_fpga/tree/master/fpga/bd/opl3_cpu)
- [吉他效果引擎（VHDL）](https://github.com/Vladilit/fpga-multi-effect)
- [VGA摄像头模块OV7670接口](https://github.com/westonb/OV7670-Verilog)
- [VGA模式发生器](https://github.com/jbush001/FPGAWhack)
- [用VHDL写的H.264视频编码器](https://github.com/bcattle/hardh264)
- [用Verilog写的H.265视频编码器](https://github.com/Bearzeng/h.265_encoder)
- [将数码相机连接到PMOD](http://hamsterworks.co.nz/mediawiki/index.php/Zedboard_OV7670)
- [用于MIPI显示的2D图形控制器](https://github.com/gtjennings1/UPDuino-LH154Q01-Display/tree/master/FPGA/source)
- [用于嵌入式MCU的2D图形控制器](http://andybrown.me.uk/2014/06/01/ase/")
- [JESD204B高速接口](https://github.com/m-labs/jesd204b)
- [用Verilog实现的ieee 754浮点库](https://github.com/dawsonjon/fpu)

### RSIC-V

- [icoSoC Risc-V微控制器，在icoBoard上运行接口]()
- [搭乘无序的Risc-V CPU]()
- [V-Scale Risc-V CPU实现]()
- [完整的32位Risc-V SoC，具有大量外设]()
- [Risc-V CPU（来自Vectorblox）]()

### 通用处理器

- [用Verilog实现的Lisp MCU](https://github.com/jbush001/LispMicrocontroller)
- [一个完整的CPU，SPI，VGA，串口](https://github.com/mattstock/bexkat1)
- [带游戏机的68000 CPU](https://github.com/neogeodev/NeoGeoFPGA-sim)
- [6502 CPU核心（Verilog）](https://github.com/Arlet/verilog-6502)
- [GPU](https://github.com/jbush001/NyuziProcessor)
- [一个开源的Verilog GPU实现（不适合icoBoard）和描述](https://github.com/HeavyPixels/QuickSilverNEO)
- [许多完整的传统家庭计算机系统在Verilog中实现，如Acorn Archimedes](https://github.com/mist-devel/mist-board/tree/master/cores)
- [一个带调试器连接的小型CPU](https://github.com/atgreen/moxie-cores)

### 存储器管理

- [SDRAM控制器](https://github.com/stffrdhrn/sdram-controller)

### 测量

- [基于FPGA的逻辑分析仪](https://blackmesalabs.wordpress.com/2016/10/24/sump2-96-msps-logic-analyzer-for-22/)

### 其它

- [用于10 GBit以太网的TCP/IP协议栈](https://github.com/dsidler/fpga-network-stack)
- [SATA for Elphel Camera项目](https://git.elphel.com/Elphel/x393)
- [AXI总线开源实现（Xilinx上的SystemVerilog）](https://github.com/muzafferkal/axi-bfm)
- [数字伺服](https://github.com/nist-ionstorage/digital-servo)
- [红外接收器](https://github.com/circuitvalley/WireFrame-FPGA)
- [CMAC使用AES作为分组密码来键控散列函数](https://www.eetree.cn/wiki/verilogopensource)

### 官方开源仓库

- [ADI开源HDL库](https://github.com/analogdevicesinc/hdl)
- [ALINX黑金官方仓库](https://github.com/alinxalinx)
- [Digilent 官方仓库](https://github.com/Digilent)
- [赛灵思中文学习资料和开源设计](https://github.com/xupsh)

# 五、原创文章系列

- [数字电路基础知识](https://mp.weixin.qq.com/s?__biz=MzU3MTc1NDUzNg==&mid=2247483685&idx=1&sn=bb5651544a47afc91ac22fad3cec7d20&chksm=fcda1062cbad997411109a78d7e84ce164b07b857f106b62099a5c24149708b8ec36e7dee800&token=1330069221&lang=zh_CN#rd)
- [FPGA开发软件（vivado + modelsim）环境搭建](https://blog.csdn.net/mengzaishenqiu/article/details/129000700?csdn_share_tail=%7B%22type%22%3A%22blog%22%2C%22rType%22%3A%22article%22%2C%22rId%22%3A%22129000700%22%2C%22source%22%3A%22mengzaishenqiu%22%7D)
- [xilinx FPGA在线调试方法总结（vivado+ila+vio）](https://mp.weixin.qq.com/s?__biz=MzU3MTc1NDUzNg==&mid=2247483763&idx=1&sn=35dc09a8ac67a653e44d32df09263e2d&chksm=fcda1034cbad99221d9b270aa77099be5f58e67c829a7520a1c40aba0f7c2aacacde21a30c47&token=1330069221&lang=zh_CN#rd)


