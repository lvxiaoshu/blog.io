---
title: 日版任天堂switch如何通过电脑端v2ray访问商店
tags:switch
---
博主的switch,到货不久,发现无法连上商店,正好手上有v2ray，研究了下，发现可以通过v2ray共享http连接，步骤如下

### v2ray配置(以v2rayN为例)
默认启用http代理，
点击参数设置![Image text](1.png)
打开v2ray设置,勾选 <span color=#0099ff>允许来自局域网的连接</span>![Image text](2.png)
### switch网络设置
确保switch和电脑在同一个局域网下，
打开switch的网络设置,设置网络代理,ip是电脑的网络ip,在填上http代理端口号(v2rayN默认是10809)。
![Image text](3.png)
这个方法用来eshop加速完全够用，下载速度可观。