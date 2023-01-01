# [BL808](https://doc.soc.xin/BL808)

* [bouffalolab](https://www.bouffalolab.com/)：[C906+E907+E902](https://doc.soc.xin/architecture/riscv)
* [L6R6](https://github.com/SoCXin/Level)：480MHz + 320MHz + 160MHz

## [简介](https://doc.soc.xin/BL808)

[BL808](https://www.bouffalolab.com/) 是一个三核异构架构的AIoT芯片，采用的都是RISC-V架构，最高时钟频率达480MHz。芯片主要包含无线和多媒体两个子系统。

M0集成Wi-Fi/BT/Zigbee无线子系统，可以实现多种无线连接和数据传输，采用平头哥 E907 320MHz 32-bit RISC-V CPU，采用 5 级流水线结构，支持RISC-V 32/16 位混编指令集，包含64个外部中断源，有4个bits可以用于配置中断优先级。M0 包含 32K 指令 cache 和 16K 数据 cache。

D0集成DVP/CSI/ H264/NPU等视频处理模块，采用平头哥 C906 480MHz 64-bit RISC-V CPU，采用 5 级流水线结构，支持 RISC-V RV64IMAFCV 指令架构，包含67个外部中断源，有 3 个 bits 可以用于配置中断优先级。D0 包含 32K 指 令 cache 和 32K 数据 cache。

BL808内部还有一个LP核，采用的是平头哥E902，主频160MHz。

### 关键特性

* 480 MHz C906 + 320MHz E907 + 160MHz E902
* 100GOPS NPU(BLAI-100)
* MJPEG and H264(Baseline/Main)
* Wi-Fi 802.11 b/g/n Wi-Fi4
* Bluetooth 5.x Dual-mode BT + BLE
* USB HS OTG

### [收录资源](https://github.com/SoCXin/BL808)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

### [选型建议](https://github.com/SoCXin)

可以预见在2023年，[BL808](https://github.com/SoCXin/BL808)将在AIoT市场掀起新一轮变革。

### [www.SoC.xin](http://www.SoC.Xin)
