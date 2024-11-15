### 自用AX6一键编译脚本
IMM官方项目没有NSS加速，要编译没有nss加速的是首选！

LEDE显示有nss，但是测试WIFI有问题，内网中上传速度特别慢。

开源驱动支持NSS的项目，都是在官方openwrt上集成了很多大佬的IPQ驱动。

以下两个项目是支持大分区，而且带NSS加速！

1、LiBwrt：https://github.com/LiBwrt-op/openwrt-6.x.git build-AX6-IPQ脚本【该项目近期发现nss加速启动不了】
2、VIKINGYFY： https://github.com/VIKINGYFY/immortalwrt.git build-AX6-NSS脚本【该项目nss加速满血，500m科学跑满cpu占用个位数!】


高通OPENWRT其他大佬项目：

下面的这些项目带nss加速，但是只支持官方的分区！

https://github.com/JiaY-shi/openwrt.git

https://github.com/qosmio/openwrt-ipq.git

https://github.com/King-Of-Knights/openwrt-6.x.git
![微信截图_20241111142204](https://github.com/user-attachments/assets/ae453a7e-aa5b-4355-9ca8-7bb192664fb6)
![微信截图_20241111142223](https://github.com/user-attachments/assets/24657fcb-89b0-411f-b159-d5754f648502)
