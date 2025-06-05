## 一：优选IP应用

CF官方优选80系端口：80、8080、8880、2052、2082、2086、2095

CF官方优选443系端口：443、2053、2083、2087、2096、8443

如果你没有天天最高速度或者选择国家的需求，使用默认的CF官方IP或者域名即可，不必更换

推荐好记的懒人专属CF官方IP如下，支持13个标准端口切换，称之为"冲在最前的不死IP"

104.16.0.0 

104.17.0.0 

104.18.0.0 

104.19.0.0 

104.20.0.0 

104.21.0.0 

104.22.0.0 

104.24.0.0 

104.25.0.0 

104.26.0.0 

104.27.0.0 

172.66.0.0

172.67.0.0

162.159.0.0

2606:4700::0 需IPV6环境

通过配置变量修改，可使用他人分享的IP或者域名，也可以自行本地优选，相关优选应用与脚本可参考视频教程

本地电脑端优选项目推荐（可在上面代码区直接下载）：

1、CDN优选域名V23.8.18 (电脑win64)

2、CF优选反代IP (电脑版，带测速)

3、CF优选官方IP (电脑版、可选择部分国家)

4、CF优选官方IP (美、亚、欧三地区无交互电脑版！强烈推荐！点击[视频教程](https://youtu.be/6kKIzObEZ2c))

5、CF优选官方IP (电脑版，带测速)

注意：多个CF节点在客户端使用负载均衡或者自动选择时，建议所有应用的节点都为同一个国家地区，以避免不同国家之间的IP乱跳现象

---------------------------------

## 二：客户端推荐

#### 启用分片(Fragment)功能的好处：无视域名被墙TLS阻断，从而让workers等被墙的域名支持TLS节点
#### 提示：未被墙TLS阻断的自定义域名或pages域名无需开启分片就可使用TLS节点
 
目前支持该功能的平台客户端如下（点击名称即跳转到官方下载地址）

1、安卓Android：[v2rayNG](https://github.com/2dust/v2rayNG/tags)、[Nekobox](https://github.com/starifly/NekoBoxForAndroid/releases)、[Karing](https://github.com/KaringX/karing/tags)、v2box

2、电脑Windows：[v2rayN](https://github.com/2dust/v2rayN/tags)、[Hiddify](https://github.com/hiddify/hiddify-next/tags)、[Karing](https://github.com/KaringX/karing/tags)

3、苹果Ios：Karing、Hiddify Proxy & VPN、Shadowrocket(小火箭)、Streisand、v2box

4、软路由：passwall、ssr-plus、homeproxy

注意：其他平台客户端未开启分片功能情况下，workers域的6个443系TLS节点是不可用的

注意：Shadowrocket(小火箭)、v2box、v2rayn、v2rayng客户端对trojan+ws有强制开启TLS问题，造成trojan+ws不通。且clash订阅没有trojan+ws节点。特此说明

关于客户端使用问题，请看[CF vless/trojan永久免费节点教程（六）：节点不能用，问题出在哪？多平台免费客户端设置指南及避坑说明](https://youtu.be/8E0l0nQWLxs)

---------------------------------
