---
title: "供Wii mini安装的d2xl cIOS （实验性功能）"
---

{% include toc title="Table of Contents" %}

这个教程将告诉你如何安装由Leseratte制作的d2xl Wii mini cIOS (自定义 IOS)。 如果你想使用USB Loader加载游戏，你就需要这个。 有一些自制软件使用cIOS会运作的更好。

![d2x cIOS Installer](/images/cIOS.png)

这个教程只为Wii mini用户而设计。 如果你使用的是Wii，请前往[这个教程](cios)。
{: .notice--warning}

如果你在本教程中需要任何帮助，请加入[Wii Mini破解 Discord群组](https://discord.gg/6ryxnkS)（推荐）
{: .notice--info}

这个d2x cIOS installer原先是为WiiU的vWii系统而开发的，由DaveBaol制作，自定义cIOS是由Laseratte为Wii mini设计的。 原下载地址可在[这里](https://wii.leseratte10.de/d2xl-cIOS/)找到。 Leseratte的Github主页可在[这里](https://github.com/Leseratte10/d2xl-cios)找到。 请注意，这个cIOS依然是实验性的，即使没有关于功能的错误反馈。
{: .notice--info}

#### 你需要的是

* 一台Wii mini，带有HBC。
* 一个U盘
* Leseratte的 [d2xl cIOS Installer](/assets/files/d2xl_wii_mini_cIOS_installer_v1_beta2.zip)

#### 步骤

##### 第一章 - 下载

1. 解压d2xl cIOS Installer到U盘里的`apps`文件夹。
1. 把你的U盘插入Wii，在HBC里进入d2xl cIOS Installer。

##### 第二章 - 安装

1. 按下继续，然后按照以下设置设定：
    ```
    Select cIOS: d2xl-v1-beta2
    Select cIOS base: 57
    Select cIOS slot: 249
    ```
在注释下记下版本号(`IOS57-64-`的结尾一般是 `v31776`或`v31775`)
1. 当设定完毕，按下A来安装。 当安装完成后，退出installer。
   - 如果安装失败提醒 `TMD version mismatch` ，在`Select cIOS base` 选项按下十字键的左键或右键，直到版本号和你刚刚尝试安装的版本号不同。 数字57将不会改变。


##### 开启以太网
如果你希望通过以太网（光纤）在Wii mini上使用Wiimmfi，你需要运行[Ethernet Enabler Homebrew](/assets/files/Wii_Mini_Ethernet_Enable.zip)，由Fullmetal5制作。 要运行它，只需要卸载它到U盘中的`apps`文件夹里，在HBC里启动它。

Wii 和 Wii mini 主机仅与使用 AX88772 芯片的网络适配器工作。 请在购买之前检查该产品是否兼容。 已知这个Ugreen的产品兼容 [淘宝(China Mainland)](https://m.tb.cn/h.fOy9RJe?sm=c1379f?tk=2dfz23UWroC)
{: .notice--info}

请不要在Wii mini尝试去安装只供Wii使用的iOS和系统菜单。 这样做会使你的Wii mini砖机。
{: .notice--warning}

你现在可以以使用一些自制工具例如[USB Loader GX](usbloadergx)和[WiiFlow](wiiflow)。
{: .notice--info}

[继续 网站导览](site-navigation) 我们有许多你可能喜欢的其他教程。
{: .notice--info}
