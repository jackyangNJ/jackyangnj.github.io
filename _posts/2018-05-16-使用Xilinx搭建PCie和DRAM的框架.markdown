---
layout: post
title:  "NetFPGA-SUME源码解读"
date:   2018-04-17 0:0:7 +0800
categories: jekyll update
---

### introduction
本帖主要介绍NetFPGA-SUME源码的代码结构，以及如何修改建立自己的工程。
![NetFPGA-SUME][fig-netfpga_sume]

----

### 代码树

```verilog
reg[1:0]  a;
if (isAwesome){
  a <= 0;
}
```

[fig-netfpga_sume]: /assets/img/netfpga_sume.png
[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
