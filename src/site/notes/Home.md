---
{"dg-home":true,"dg-publish":true,"permalink":"/home/","tags":["gardenEntry"],"dgPassFrontmatter":true}
---

> [!info] 事先说明 这篇基本上是流水账，原因是分享有活动。

之所以要转移NAS，是因为最近的黑群晖因为SATA线的松动导致了硬盘一直重连，最后报故障不再识别了。正好新家的弱电柜放不下当前的服务器机箱，所以物色了一个新机箱来作为家庭服务器。

![NAS转移-瀚存见方L-8盘位机箱.png](https://zytomorrow.top/attachments/NAS%E8%BD%AC%E7%A7%BB-%E7%80%9A%E5%AD%98%E8%A7%81%E6%96%B9L-8%E7%9B%98%E4%BD%8D%E6%9C%BA%E7%AE%B1.png)

![NAS转移-瀚存见方L-8盘位机箱-1.png](https://zytomorrow.top/attachments/NAS%E8%BD%AC%E7%A7%BB-%E7%80%9A%E5%AD%98%E8%A7%81%E6%96%B9L-8%E7%9B%98%E4%BD%8D%E6%9C%BA%E7%AE%B1-1.png)

先看下我的旧机箱设备,目前用的是一个塔式机箱-Thermaltake 挑战者H6, 这个机箱很大，支持10盘位，各方面都不错，只是自带的两个硬盘位是真的不好接线，其他的硬盘位需要单独买支架，还不带背板，以PVE作为底层，虚拟了`openwrt软路由`、`HA服务器`、`开发服务器`、`DOCKER`和`黑群晖`。这套服务器稳定运行了4年多了，当时加机箱和硬盘的价格大概在3000-4000之间，主要是硬盘太贵了。第一次出问题是在去年，当前的居住环境会无意识的触碰到NAS服务器，导致硬盘或者SATA线震动，黑群晖有次突然推送`硬盘重新连接次数：3`，一直到现在，这个告警我都没怎么在意，毕竟重连就重连呗。直到现在重连960次后，存储池降级了，不识别了，导致我没办法只能考虑要么修复要么尝试新系统。

![NAS转移-瀚存见方L-8盘位机箱-6.png](https://zytomorrow.top/attachments/NAS%E8%BD%AC%E7%A7%BB-%E7%80%9A%E5%AD%98%E8%A7%81%E6%96%B9L-8%E7%9B%98%E4%BD%8D%E6%9C%BA%E7%AE%B1-6.png)

![NAS转移-瀚存见方L-8盘位机箱-3.png](https://zytomorrow.top/attachments/NAS%E8%BD%AC%E7%A7%BB-%E7%80%9A%E5%AD%98%E8%A7%81%E6%96%B9L-8%E7%9B%98%E4%BD%8D%E6%9C%BA%E7%AE%B1-3.png)

最终我还是考虑了换底层，PVE对我来说还是太重了，使用起来不是很方便。结合我当前的情况：`ATX主板`、`ATX电源`，`全高PCIE设备`，`8盘位`。全网能找到的NAS