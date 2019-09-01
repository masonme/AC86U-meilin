# 华硕RT-AC86U86U86U：刷官改/梅林改版系统和挂载虚拟内存教程

------

### 步骤一、固件下载

- 【梅林改版】：基于梅林固件修改，添加软件中心，有更多的功能和 bug 修复。
- 【官改】：基于官方固件修改，添加软件中心，ROG 红色界面，支持 AiMesh，更新较快。
 ```
 好用程度差别不大，稳定性也基本无差，选哪个固件基于个人喜好。固件作者：sadog
 ```
- 【梅林改版】[384.13_1 下载](https://github.com/masonvip/AC86U-meilin/blob/master/file/RT-AC86U_384.13_1_cferom_ubi-koolshare.w)
- 【官改】[384_45717 下载](https://github.com/masonvip/AC86U-meilin/blob/master/file/RT-AC86U_384_45717_koolshare_cferom_ubi-0627.w)



------

### 步骤二、升级固件

`注：以梅林改版为例，请使用 Chrome 浏览器进行操作。`

* 路由器连接电脑，网页端进入路由器后台；
* 点选【系统管理】-【固件升级】，选择下载好 ```.w``` 后缀的固件上传。

![01](https://github.com/masonvip/AC86U-meilin/blob/master/picture/01.png?raw=true)

* 约 3 分钟即可完成。

![01 升级](https://github.com/masonvip/AC86U-meilin/blob/master/picture/01%20%E5%8D%87%E7%BA%A7%E4%B8%89%E5%88%86%E9%92%9F.png?raw=true)

- 完成后连接网络，可以看到左下角出现【软件中心】。

![02](https://github.com/masonvip/AC86U-meilin/blob/master/picture/02.png?raw=true)

---

### 步骤三、安装科学上网插件

* 科学上网插件下载：[shadowsocks.tar.gz](https://github.com/masonvip/chajian/blob/master/flie01/shadowsocks.tar.gz)
* 进入【软件中心】-【离线安装】，选择下载好的文件（后缀名为`.gz`）上传安装。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/03.png?raw=true)

* 安装成功后回到【软件中心】，即可看到科学上网工具。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/04.png?raw=true)

* 点选【科学上网】，添加上网方式，如：`SS`  `SSR` `V2Ray`。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/05.png?raw=true)

* 订阅机场：点选【更新管理】，把链接粘贴到下图②处，然后保存并订阅。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/06.png?raw=true)

------

### 安装虚拟内存

随着固件升级越来越完善，如安装插件不多无需挂载虚拟内存，此步骤可省略；当然也可以选择安装，步骤如下：
* 进入【软件中心】-【未安装】里找到【虚拟内存】并安装。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/07.png?raw=true)

* 先将 U盘格式为 ext4 格式。方法：[U盘如何格式化为 ext3 ext4 格式](https://www.jianshu.com/p/85039ac096c3)
* 将 U盘插到背面 USB（2.0 或 3.0 接口均可）上，进入【软件中心】-【虚拟内存】，会显示 U盘信息。
`如不显示说明 U 盘格式不对，请重新格式化。`
* 虚拟内存大小选择 512 MB 或 1 GB 均可，点选【创建虚拟内存】即可挂载成功。

![](https://github.com/masonvip/AC86U-meilin/blob/master/picture/08.png?raw=true)

### 体验：

- 华硕路由器刷机非常简单，直接上传新固件即可完成。
- 现阶段千元内的路由器，不论颜值还是性能都非常优秀。

声明：刷机的朋友认真请阅读本文，带来的风险请自行承担！

友情链接：[AC86U开启SSH，重置软件中心更换皮肤]([https://github.com/masonvip/AC86U-pifu/blob/master/README.md](https://github.com/masonvip/AC86U-pifu/blob/master/README.md))

---
[![Telegram](https://rawcdn.githack.com/masonvip/masonvip.github.io/7fa770686f715c1d67b1544a6dc92d0bc24855c2/file01/Telegram.svg)](https://t.me/MasonClub)
[![简书](https://rawcdn.githack.com/masonvip/masonvip.github.io/7fa770686f715c1d67b1544a6dc92d0bc24855c2/file01/简书.svg)](https://www.jianshu.com/u/76be8479a4ae)
[![支付宝](https://rawcdn.githack.com/masonvip/masonvip.github.io/18ae48780713dafb6da43fb13fd869429e648d37/file01/支付宝.svg)](https://github.com/masonvip/masonvip.github.io/blob/master/file01/%E6%94%AF%E4%BB%98%E5%AE%9D.JPG?raw=true)
[![](https://rawcdn.githack.com/masonvip/masonvip.github.io/6f7f84c40b1e1ef79292707e4151017017aa09ed/file01/微信捐赠.svg)](https://github.com/masonvip/masonvip.github.io/blob/master/file01/%E5%BE%AE%E4%BF%A1%E6%94%B6%E6%AC%BE%E4%BA%8C%E7%BB%B4%E7%A0%81.JPG?raw=true)
