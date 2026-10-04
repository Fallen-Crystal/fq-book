# wireguard

进入[wireguard](https://www.wireguard.com/install/)，下载

![](../_offline/vendor/i.postimg.cc/d0Ny2kxH/Snipaste-2019-10-04-10-49-28.png)

打开wireguard选择 `add empty tunnel`并复制`public key` 公钥键值

![](../_offline/vendor/i.postimg.cc/FR2w1Vkf/00-05.png)

进入[cryptostorm.is/wireguard](https://cryptostorm.is/wireguard)，将公钥复制到`your wireguard public key`选项，`add key`继续，并生成的配置文件

![](../_offline/vendor/i.postimg.cc/MHB0Ky1p/27-48.png)

将配置文件复制到`public key`下方配置信息框内，并删除如下不必要的字段

```
[Interface]
PrivateKey = YOUR_PRIVATE_KEY
```

![](../_offline/vendor/i.postimg.cc/BbRhmSBX/41-15.png)

点击`active`激活

![](../_offline/vendor/i.postimg.cc/65gwLTRh/50-10.png)

测试

![](../_offline/vendor/i.postimg.cc/zvz1SjPK/56-26.png)

> 参考自油管 [Siemens Tutorials](https://www.youtube.com/channel/UCmvvn2qsP77_7XUB0omMeCw/about?pbjreload=10) 关于wireguard翻墙视频