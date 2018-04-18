---
layout: post
title:  "NetFPGA-SUME资源对比"
date:   2018-04-17 0:0:7 +0800
categories: jekyll update
---

### introduction
本帖主要介绍NetFPGA-SUME板上资源介绍。

NetFPGA-SUME开发板FPGA芯片型号xc7vx690tffg1761-3。

----

### 芯片资源
我们将NetFPGA-SUME的芯片[xc7vx690t][virtex_resource] 与 [XCKU060][ultrascale_resource] 做对比。

|  芯片型号 | Logic cells | CLB Flip-Flops | DSP slices | Max. Distributed RAM (Kb) | BRAM(kb) |
|:---------:|:-----------:|----------------|:----------:|---------------------------|----------|
| XC7VX690T |    693120   | 866400         |    3600    | 10888                     | 52920    |
|  XCKU060  |    726000   | 663360         |    2760    | 9180                      | 38000    |

### Memory
主要包括DRAM和SRAM：
* Two 4GB DDR3 SODIMMs (MT8KTF51264Hz- 1G9E1)
  * 64 bit wide buses clocked at 850 MHz (1700 mbps)
* Three 72Mbit QDRII+ SRAMs (CY7C25652KV18-500BZXC)
  * 36 bit wide buses clocked at 500 MHz (1000 mbps)


[virtex_resource]: https://www.xilinx.com/support/documentation/selection-guides/7-series-product-selection-guide.pdf#V7
[ultrascale_resource]: https://www.xilinx.com/support/documentation/selection-guides/ultrascale-fpga-product-selection-guide.pdf#KU

[fig-netfpga_sume]: /assets/img/netfpga_sume.png
