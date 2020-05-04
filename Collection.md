# IOT 安全实战资料收集整合

标签（空格分隔）： 学习资料

---

## 适合入门的资料

[海特实验室 IOT WIKI][1]

[伏辰实验室-物联网安全百科][2]

[绿盟 - 智能设备安全分析手册][3]

[物联网安全从入门到入坑][4]

## 环境搭建

[路由器漏洞挖掘测试环境的搭建之问题总结][5]


## 固件提取&固件分析

http://www.devttys0.com/2011/06/mystery-file-system/
http://www.devttys0.com/2011/05/reverse-engineering-firmware-linksys-wag120n/

[逆向路由器固件之解包][6]

[基于 VxWorks 的嵌入式设备固件分析方法介绍][7]

[TP-Link wr886nv7-V1.1.0 路由器分析 – 固件初步分析][8]

[TP-Link wr886nv7-V1.1.0 路由器分析 - VxWorks cmd命令行获取及使用方法][9]
https://www.secpulse.com/archives/75636.html

[物联网设备的固件分析技术][10]

[VxWorks固件逆向：WRT54Gv8][11]

[工控漏洞挖掘方法之固件逆向分析][12]

[路由固件的逆向解包及破解方法][13]

[深入分析Ewon Flexy物联网路由器（下）][14]

[D-Link DIR-850L路由器分析之获取设备shell][15]

[TP-Link wr886nv6 固件解析][16]

[Reverse Engineering VxWorks Firmware: WRT54Gv8][17]

[IoT固件逆向入门][18]

[安全小课堂第118期【IOT漏洞挖掘之路由器】][19]

[关于IoT安全我有话说][20]

[智能路由器安全特性分析][21]

[Reversing D-Link’s WPS Pin Algorithm][22]

[D-Link DIR-816 A2路由器安全研究分享][23]

[路由器固件安全分析技术（一）][24]

[极路由安全设计架构分析][25]
https://www.freebuf.com/articles/terminal/76046.html

[binwalk提取固件失败][26]

[U-boot详解：板子上电时都干了些什么][27]

[IOT物理安全-固件提取基础(1)][28]

[IoT固件提取以及固件分析的workshop资料–Jett][29]

[固件分析之GoAhead框架ASP文件提取][30]


### 固件加密

[某智能设备固件解密][31]
[如何处理加密路由器固件][32]


### 固件修改

[固件修改及编译记录][33]


### 固件调试

[如何通过 TTL 调试光猫][34]

### 信息收集

[逆向路由器固件之信息泄露][35]
[逆向路由器固件之敏感信息泄露 Part2][36]
[tenda 某路由器信息泄露查找][37]


## 实例漏洞分析

### 路由器

#### 命令执行漏洞
1. [重现 TP-Link SR20 本地网络远程代码执行漏洞][38]
2. 
[由一道工控路由器固件逆向题目看命令执行漏洞][39]

2. [分析Belkin SURF路由器中的多个漏洞][40]（缓冲区溢出、后门）

3. [H4lo - 路由器漏洞分析系列][41]

4. [kczwa1 - 路由器 CVE 复现][42] 

5. [360 IOT 人才培养计划][43]
https://bbs.ichunqiu.com/thread-32773-1-1.html?from=beef
6. [腾达 Tenda 路由器后门分析][44]

7. [D-Link 路由器HNAP协议系列漏洞披露（DIR-823G、DIR-878、DNS 重绑定攻击）][45]

8. [Dlink DIR 路由器HNAP登录函数的多个漏洞][46]

9. [dir-890l 命令执行漏洞分析][47]

10. [D-Link 系列路由器漏洞挖掘入门][48]

11. [TP-LINK wr-842n 等多款无线路由器（新界面2015）存在多个致命漏洞][49]

12. [实测一款IoT路由的安全性如何？从web到硬件，我们进行了全面的漏洞挖掘和分析（下）][50]
13. [Some vulnerability in ASUS routers][51]

14. [TP-LINK WR941N路由器研究][52]

15. [华硕路由器9999端口远程命令执行研究报告 V1][53]

16. [分析多款D-Link路由器中的未授权RCE漏洞][54]

17. [腾达AC15路由器上的远程代码(CVE-2018-5767)执行演练][55]

18. [你用它上網，我用它進你內網! 中華電信數據機遠端代碼執行漏洞][56]

19. [必虎路由器大量高危漏洞分析][57]

20. [D-Link DIR-859的RCE漏洞（CVE-2019–17621）][58]

    [D-Link DIR-859 RCE漏洞（CVE-2019-17621）分析复现][59]

21. [D-Link DIR-878 路由器存在漏洞两枚][60]

22. [DLINK DIR-859 ssdpcgi 命令注入][61]

[Pulse Secure SSL VPN远程代码执行漏洞利用与分析][62]

[TP-Link Archer A7命令注入漏洞分析][63]

[D-Link DSL-2640B多个漏洞分析][64]

https://www.pentestpartners.com/security-blog/pwning-cctv-cameras/

#### 拒绝服务&栈溢出

[TP-LINK wr-886n 拒绝服务][65]

[CVE-2018-0296 Cisco ASA 拒绝服务漏洞分析][66]

[CVE-2019-1663 Cisco 的多个低端设备的堆栈缓冲区溢出漏洞分析][67]

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[tplink wr940 缓冲区溢出][68]


[dir-842 rev.c 栈溢出][69]


[Asuswrt RT-AC68U 华硕路由器文件删除漏洞 && 栈溢出][70]

[ASUSWRT Stack Overflow in wanduck.c][71]

[ASUSWRT - Multiple Vulnerabilities][72]

[Netgear R6400 upnp栈溢出漏洞分析][73]

[openfind mail2000 栈溢出漏洞分析&利用][74]

[CVE-2020-3119 Cisco CDP 协议栈溢出漏洞分析][75]


#### 未授权访问/认证绕过

[实测绕过腾达某型号路由器后台登陆认证，获得管理权限][76]

[如何日穿自家光猫][77]

[D-Link多型号路由器存在任意文件下载漏洞（CVE-2018-10822）][78]

[某些型号的Comba和D-Link路由器存在管理员密码泄露漏洞][79]

[ZXHN H108N Router Web-Shell and Secrets][80]

[Dlink Shareport Web Access Authentication Bypass][81]

[CVE-2020-9544: DLink DSL-2640B un-authenticated firmware upgrade][82]

#### 信息泄露

[影响 NETGEAR 路由器的 0-Day：KCodes NetUSB 两个安全漏洞披露（CVE-2019-5016/5017）][83]


#### MikroTik

[MikroTik RouterOS][84]


### DLINK - DIR 系列 CVE

CVE-2016-6563
CVE-2019-8312

### UPNP 相关漏洞

[P2P 网络核心技术：UPnP 和 SSDP 协议][85]

http://www.360doc.com/content/14/1009/17/13468863_415575489.shtml

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[D-Link DIR-615 XSS Via the UPnP Protocol][86]

[UPnP 安全（二）：UPnP 协议具体流程][87]

[D-Link DIR-859 —未经身份验证的RCE(CVE-2019–17621)][88]



### SMB

[路由器抓包分析之 SMB 篇][89]

### SNMP

[多种设备基于 SNMP 协议的敏感信息泄露漏洞数据分析报告][90]

## 摄像头安全

[以某家用摄像头测评入手谈物联网智能家居安全][91]

[vivetok 摄像头远程栈溢出漏洞分析][92]

[智能摄像头安全分析及案例参考][93]

[绕过某摄像头校验机制软刷固件][94]

[IT_Security_Research_WirelessIP_camera_family][95]

[一款摄像头的安全测试-1][96]

[一款摄像头的安全测试-2][97]

[IT Security Research by Pierre][98]

[亚马逊Blink智能摄像头曝出劫持漏洞][99]
- **响应包存在 root 命令注入**

![image.png-136kB][100]

[智能摄像头安全分析及案例参考][101]

[海思芯片摄像头后后门、硬编码、栈溢出][102]
https://ssd-disclosure.com/archives/3025

[Qemu复现雄迈摄像头固件漏洞][103]
[Full disclosure: 0day vulnerability (backdoor) in firmware for Xiaongmai-based DVRs, NVRs and IP cameras][104]
https://www.cnblogs.com/mmseh/p/6537924.html

[pwning-cctv-cameras][105]

[AVTECH DVR设置无需用户登录的命令执行漏洞][106]

[JAWS/1.0 漏洞复现（摄像头）][107]


## 门锁安全

[硬件安全|智能门锁安全研究方法总结][108]

## 智能音箱安全

[物联网安全系列之远程破解Google Home][109]


## 嵌入式设备固件逆向

[嵌入式逆向工程入门：STM32F103C8T6 上 的 FreeRTOS & Libopencm3][110]
[嵌入式设备硬件 PCB 级逆向][111]
[渗透低性能智能设备的关键技术-固件提取][112]


## 其他智能设备/工控设备

https://www.exploitee.rs/index.php/FireFU_Exploit

[网络设备漏洞分析技术研究（KCON2016议题）][113]

[2018年 KCon 议题解读 | 智能家居安全——身份劫持][114]

[如何PWN掉西门子工控设备][115]

[破解微软智能手环][116]

[指纹锁的硬件逆向工程][117]

[攻击案例 -- 数字密码锁 - 手把手DIY，教你强攻嵌入式设备那些黑科技][118]

[分析逆向通信HACK升降桌后感想][119]

## 无线电安全

[Wi-Fi Protected Network and Wi-Fi Protected Network 2 Information Disclosure Vulnerability][120]


## 整合/总结性资料

https://github.com/V33RU/IoTSecurity101
https://xz.aliyun.com/t/2278
[伏宸安全实验室-知乎专栏][121]

[物联网（IOT）安全测试经验总结][122]

[绿盟 - 智能设备安全分析手册][123]

[OWASP TOP10 物联网漏洞一览][124]

[secwiki - 设备安全][125]

## 漏洞挖掘思路/技巧

> 智能硬件的攻击面也主要在 协议 这一块， 比如协议数据的加密问题， 协议的权限问题，认证机制以及对数据的处理问题（堆栈溢出）

https://www.cnblogs.com/hac425/p/9674758.html

[D-Link DIR-850L路由器分析之获取设备shell][126]

[对嵌入式设备的逆向分析与漏洞利用：软件栈（第一部分）][127]

[看雪2018峰会回顾_智能设备漏洞挖掘中几个突破点(内有十种固件提取方法和首次公开uboot提取固件方法)][128]

[路由器0day漏洞挖掘实战](https://www.anquanke.com/post/id/180714)

浅谈路由器漏洞挖掘（科普文）


## 相关工具使用

[固件逆向分析过程中的工具和技巧（上）][129]

[固件逆向分析过程中的工具和技巧（下）][130]

[mips 漏洞利用框架][131]

[Miranda][132]

## IOT 安全开发

[假如你的灯被入侵了][133]


## IOT 大牛博客

[devttys0][134]
[giantbranch][135]
https://github.com/xinali/articles
[银河安全实验室][136]
[cq][137]
[hac425][138]
[secwiki 路由器漏洞相关资料][139]
https://github.com/leonW7?tab=repositories
[ray-cp][140]
[jayway0day][141]
https://wzt.ac.cn/2020/01/10/firmadyne2/
http://www.gandalf.site/
[jalalsela][142]
[伏宸安全实验室][143]
http://www.atomsec.org/

## fuzz && unicorn

[基于 unicorn 的单个函数模拟执行和 fuzzer 实现][144]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][145]

[American Fuzzy Lop/AFL使用/][146]

[IoT设备固件分析之网络协议fuzz][147]

[M4x - afl-fuzz技术初探][148]

[初探BooFuzz][149]

https://www.cnblogs.com/studyskill/category/1028655.html

[初探Windows Fuzzing神器----Winafl][150]

[fuzz实战之libfuzzer][151]

https://github.com/Dor1s/libfuzzer-workshop/tree/master/lessons

[Cotopaxi：使用指定IoT网络协议对IoT设备进行安全测试][152]

[Unicorn 在 Android 的应用][153]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][154]


[IOTFUZZER：通过基于应用程序的模糊测试发现物联网中的内存损坏][155]

- 相关视频：https://www.youtube.com/watch?v=Ys2FBmdbdIw

[FIRM-AFL: High-Throughput Greybox Fuzzing of IoT Firmware via Augmented Process Emulation][156]

[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware][157]

[利用Marvell Avastar Wi-Fi中的漏洞远程控制设备：从零知识入门到RCE漏洞挖掘利用（下）][158]

[IoT 设备网络协议模糊测试工具boofuzz实战][159]

[提高AFL qemu模式性能][160]


## IOT 安全视频教学

[边界IOT漏洞挖掘精要][161]
[家用路由器漏洞挖掘入门][162]
[物联网设备漏洞挖掘思路与技巧][163]
[ChaMd5安全团队 带你入坑物联网安全][164]
[2020-2-29-知世-公开课-路由器PWN][165]
[「突围」联合线上技术直播沙龙完整录屏丨漏洞银行直播回顾 - 2020.2.26 - AIOT 安全][166]

## 固件加密

https://www.docin.com/p-882254908.html

[四个字节的安全 ：一次固件加密算法的逆向分析][167]


## CTF 题目

[Real World Finals 2018 Router][168]

[0ctf2019 Final embedded_heap题解][169]


## 国外技术文章

[afl-unicorn: Fuzzing Arbitrary Binary Code][170]

http://www.routerpwn.com/

https://firmwaresecurity.com/

[路由器分析之硬件拆卸][171]

https://blog.3or.de/

## 会议 paper



## 嵌入式基础知识
uboot

uimage

https://www.jianshu.com/p/01e5dd7c979a

## 文件系统

1. https://elinux.org/File_Systems

2. [linux 与嵌入式系统][172]


## 相关命令

解压 lzma 格式压缩数据：

```
lzma -kdc A200.lzma > A200
lzmadec -kd fwr2.lzma>fwr22
```

### jffs2 文件系统的处理

https://blog.51cto.com/axlrose/1317610

## 国内 or 国外路由器固件下载

[TOTOLINK][173]
http://www.totolink.net/
[FAST][174]
[极路由/hiwifi][175]
[D-LINK][176]
[TP-LINK][177]
[MERCURY][178]
[Tenda][179]
[磊科][180]
[维盟][181]
http://www.wayos.com:8081/download/
[艾泰][182]
[锐捷路由器][183]
[飞鱼星][184]
[newifi][185]
[b-link][186]
[华硕][187]
[腾达][188]
[拓实][189]
[netis][190]
[华硕][191]
[draytek][192]
[grandstream][193]
http://www.grandstream.com/support/firmware/

[linksys][194]
[ruckuswireless][195]



## 摄像头固件

[tp-link][196]
[杭州-雄迈][197]
[avtech][198]
https://drivers.softpedia.com/get/network-ip-surveillance-baby-camera/AVTECH/AVTECH-AVH0801-NVR-Firmware-1012.shtml
https://support.wdc.com/downloads.aspx?lang=cn#firmware


## 事件报道

[4G无线路由曝致命漏洞，攻击者可执行任意代码][199]
[破解了十款路由器之后，我们有话要说][200]
[数数那些坑你的路由器漏洞][201]
[腾讯安全团队新发现：智能音箱摇身一变成间谍][202]
[大量Ruckus路由器出现漏洞，易受黑客攻击][203]
[启明星辰ADLab：某摄像头产品漏洞分析及解决方案][204]
[华为海思芯片又有后门？外国研究员刚提出指控，就被打脸了][205]



  [79 https://service.fastcom.com.cn/downloa## 标题 ##d-list.html#0


  [1]: https://dassecurity-labs.github.io/HatLab_IOT_Wiki/
  [2]: https://iot-security.wiki
  [3]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [4]: https://paper.seebug.org/1045/
  [5]: https://xz.aliyun.com/t/3826
  [6]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E8%A7%A3%E5%8C%85/
  [7]: https://paper.seebug.org/771/
  [8]: https://www.secpulse.com/archives/75635.html
  [9]: https://mp.weixin.qq.com/s/6q3zAaS4jV_Mw3qvgtngBw
  [10]: https://www.cnblogs.com/ssooking/articles/6144577.html
  [11]: https://www.anquanke.com/post/id/176481
  [12]: https://paper.seebug.org/613/
  [13]: https://blog.csdn.net/leekwen/article/details/53635462
  [14]: https://www.anquanke.com/post/id/180864
  [15]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [16]: https://cq674350529.github.io/2018/09/19/TP-Link-wr886v6-%E5%9B%BA%E4%BB%B6%E8%A7%A3%E6%9E%90/
  [17]: http://www.devttys0.com/2011/07/reverse-engineering-vxworks-firmware-wrt54gv8/
  [18]: http://zeroyu.xyz/2019/08/15/How_to_start_IoT_Reverse/
  [19]: https://www.secpulse.com/archives/81577.html
  [20]: https://www.freebuf.com/articles/ics-articles/210776.html
  [21]: https://security.tencent.com/index.php/blog/msg/91
  [22]: http://www.devttys0.com/2014/10/reversing-d-links-wps-pin-algorithm/
  [23]: https://mp.weixin.qq.com/s/rT53P9EW4xLFV9JLbnLroQ
  [24]: https://www.cnblogs.com/k1two2/p/7072709.html
  [25]: https://www.freebuf.com/articles/terminal/75524.html
  [26]: https://mp.weixin.qq.com/s/E9h0lT184wBiDyojuWx1CA
  [27]: https://mp.weixin.qq.com/s/Sxi9fQ_Jtj5xC5gm-nr5WQ
  [28]: https://mp.weixin.qq.com/s/l73iLAayzajs4HQgnnIpYg
  [29]: https://github.com/C00kie-/workshop-materials
  [30]: http://blog.nsfocus.net/0320-goahead-asp/
  [31]: https://5alt.me/2017/08/%E6%9F%90%E6%99%BA%E8%83%BD%E8%AE%BE%E5%A4%87%E5%9B%BA%E4%BB%B6%E8%A7%A3%E5%AF%86/
  [32]: https://www.anquanke.com/post/id/198311
  [33]: https://xz.aliyun.com/t/6053
  [34]: https://paper.seebug.org/506/
  [35]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E4%BA%8C/
  [36]: https://www.freebuf.com/articles/terminal/76481.html
  [37]: https://blog.csdn.net/qq_27446553/article/details/79125129
  [38]: https://paper.seebug.org/879/
  [39]: https://www.anquanke.com/post/id/183202
  [40]: https://www.anquanke.com/post/id/183326
  [41]: https://www.anquanke.com/search?s=%E8%B7%AF%E7%94%B1%E5%99%A8%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98
  [42]: https://www.freebuf.com/author/kczwa1
  [43]: https://mp.weixin.qq.com/s?__biz=MjM5NjM2NDU0Ng==&mid=2450189577&idx=1&sn=ad2f8f7089f9c67ba6e6676e1cb933a2&chksm=b11425648663ac7214afcacf625f4e1f58647ff90dc83aea5764a10c2b55463b20ba0d592848&token=1945049632&lang=zh_CN&scene=21#wechat_redirect
  [44]: https://www.freebuf.com/articles/terminal/14425.html
  [45]: https://www.heibai.org/post/1395.html
  [46]: https://www.anquanke.com/post/id/84912
  [47]: http://www.devttys0.com/2015/04/hacking-the-d-link-dir-890l/
  [48]: https://www.cnblogs.com/HacTF/p/8052279.html
  [49]: https://www.secpulse.com/archives/35760.html
  [50]: https://mp.weixin.qq.com/s/p_lQQ_X4up004LCpNHyrnw
  [51]: https://www.securityartwork.es/2018/01/25/some-vulnerability-in-asus-routers/
  [52]: https://paper.seebug.org/448/
  [53]: https://blog.knownsec.com/2015/01/report-of-asua-router-9999-port-remote-command-execution-v1/
  [54]: https://www.anquanke.com/post/id/187923
  [55]: https://bbs.pediy.com/thread-225671.htm
  [56]: https://blog.orange.tw/2019/11/HiNet-GPON-Modem-RCE.html?nsukey=Z%2bR9JgOkzUjLo8kbR45klrA5HZVClqg%2bg27Fyo6HW0z%2bAXWeGL38o75v6cFXTVLUeBaTpMVhhszEphXPakYx%2b3ZBRsHBRBp4x17HzOp9oB2K/XvK9iSBOLXDe/gKVn4T%2b8MDkZVzEDHgILZPfe6WXMbcpe20UQlKs8ajTpNynCo=
  [57]: https://www.cnblogs.com/k1two2/p/5808839.html
  [58]: https://nosec.org/home/detail/3772.html
  [59]: https://mp.weixin.qq.com/s/TzFepaBpYnMbZ8Mep4IXwA
  [60]: https://wzt.ac.cn/2019/09/18/D-Link_BUG/
  [61]: https://medium.com/@s1kr10s/d-link-dir-859-unauthenticated-rce-en-ssdpcgi-http-st-cve-2019-20215-es-6ec205f5cf
  [62]: https://www.anquanke.com/post/id/185773#h2-11
  [63]: https://www.anquanke.com/post/id/202671
  [64]: https://www.anquanke.com/post/id/202213
  [65]: https://github.com/PAGalaxyLab/VulInfo/blob/master/TP-Link/WR886N/inetd_task_dos_13/README.md
  [66]: https://cq674350529.github.io/2019/03/01/CVE-2018-0296-Cisco-ASA-%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  [67]: https://paper.seebug.org/1039/
  [68]: https://securityintelligence.com/buffer-overflow-vulnerability-in-tp-link-routers-can-allow-remote-attackers-to-take-control/
  [69]: https://ctrsec.io/index.php/2020/02/12/cve-2020-8962-d-link-dir-842-stack-based-buffer-overflow/
  [70]: https://www.cnblogs.com/iamstudy/articles/Asuswrt_RT-AC68U_CVE-2018-6636_Detail.html
  [71]: https://starlabs.sg/advisories/18-20336/
  [72]: https://bierbaumer.net/security/asuswrt/#session-stealing
  [73]: https://mp.weixin.qq.com/s/R2V6LWyD2RqLkXHIRUlZKg
  [74]: https://devco.re/blog/2019/12/23/how-binary-dog-survives-in-web-world/
  [75]: https://www.anquanke.com/post/id/202054#h2-0
  [76]: https://mrxn.net/jswz/tenda-authentic-bypass.html/comment-page-2
  [77]: https://www.anquanke.com/post/id/183998
  [78]: https://nosec.org/home/detail/1913.html
  [79]: https://nosec.org/home/detail/2949.html
  [80]: https://jalalsela.com/zxhn-h108n-router-web-shell-secrets/
  [81]: https://cyberloginit.com/2019/09/10/dlink-shareport-web-access-authentication-bypass.html
  [82]: https://ktln2.org/2020/03/05/cve-2020-9544/
  [83]: https://www.chainnews.com/articles/042047440649.htm
  [84]: https://www.anquanke.com/post/id/183451
  [85]: https://www.jianshu.com/p/e41aa1428df3
  [86]: https://github.com/reevesrs24/CVE/blob/master/D-Link_DIR-615/xss_UPnP/dlink_dir615_xss_upnp.md
  [87]: https://www.attacker.cc/index.php/archives/113/
  [88]: https://xz.aliyun.com/t/7039
  [89]: https://www.freebuf.com/news/193340.html
  [90]: https://paper.seebug.org/795/
  [91]: https://www.freebuf.com/articles/terminal/207584.html
  [92]: https://www.anquanke.com/post/id/185336
  [93]: https://www.anquanke.com/post/id/178795
  [94]: http://invicsfate.cc/2018/10/09/%E7%BB%95%E8%BF%87%E6%9F%90%E6%91%84%E5%83%8F%E5%A4%B4%E6%A0%A1%E9%AA%8C%E6%9C%BA%E5%88%B6%E8%BD%AF%E5%88%B7%E5%9B%BA%E4%BB%B6/
  [95]: https://github.com/eloygn/IT_Security_Research_WirelessIP_camera_family
  [96]: https://mp.weixin.qq.com/s/mY3I60dcXQHxof79NvOAFw
  [97]: https://www.pentestpartners.com/security-blog/hacking-the-aldi-ip-cctv-camera-part-2/
  [98]: https://pierrekim.github.io/blog/2017-03-08-camera-goahead-0day.html
  [99]: https://www.freebuf.com/column/222661.html
  [100]: http://static.zybuluo.com/H4l0/gzrod4v52vfltfxzlg6bx29m/image.png
  [101]: https://www.freebuf.com/articles/terminal/203311.html
  [102]: https://github.com/H4lo/pwn-hisilicon-dvr
  [103]: https://nosec.org/home/detail/4213.html
  [104]: https://habr.com/en/post/486856/
  [105]: https://www.pentestpartners.com/security-blog/pwning-cctv-cameras/
  [106]: https://www.seebug.org/vuldb/ssvid-92493
  [107]: https://www.lstazl.com/1252-2/
  [108]: https://nosec.org/home/detail/2760.html
  [109]: https://mp.weixin.qq.com/s/4kO3pU_tCDZmgj2CkROzMg
  [110]: https://bbs.pediy.com/thread-247140.htm
  [111]: https://zhuanlan.zhihu.com/p/28294785
  [112]: http://blog.nsfocus.net/firmware-extraction/
  [113]: https://www.freebuf.com/articles/system/114741.html
  [114]: https://xz.aliyun.com/t/2664
  [115]: https://www.freebuf.com/articles/network/213897.html
  [116]: http://drops.xmd5.com/static/drops/wireless-15139.html
  [117]: https://mp.weixin.qq.com/s/D8Q9jgk4TodLPf4GoqTfGg
  [118]: http://39.elecfans.com/20170804537214_3.html
  [119]: https://mp.weixin.qq.com/s/d8qi8F-M3g857LwZJff-_g
  [120]: https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20200226-wi-fi-info-disclosure
  [121]: https://zhuanlan.zhihu.com/future-sec
  [122]: http://www.polaris-lab.com/index.php/archives/48/
  [123]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [124]: https://xz.aliyun.com/t/2278
  [125]: https://www.sec-wiki.com/news/index/tag/device/
  [126]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [127]: https://www.anquanke.com/post/id/95055
  [128]: https://bbs.pediy.com/thread-230095.htm
  [129]: https://mp.weixin.qq.com/s?__biz=MzI0MDY1MDU4MQ==&mid=2247493390&idx=2&sn=94582aa41410f53b608ec803c1fb8203&chksm=e9153734de62be22558307ba47f949345c2ed9dd445d215d9786f45e556394f151b8558f3cf1&scene=21#wechat_redirect
  [130]: https://www.chainnews.com/articles/550133689280.htm
  [131]: https://github.com/zcutlip/bowcaster
  [132]: https://tools.kali.org/information-gathering/miranda
  [133]: https://mp.weixin.qq.com/s/O1sJv5IBGJVZCbPGqUNHjw
  [134]: http://www.devttys0.com/blog/
  [135]: http://www.giantbranch.cn
  [136]: http://galaxylab.com.cn
  [137]: https://cq674350529.github.io/categories/IoT/
  [138]: http://www.cnblogs.com/hac425/
  [139]: https://sec-wiki.com/news/search?wd=%E8%B7%AF%E7%94%B1%E5%99%A8
  [140]: https://ray-cp.github.io/
  [141]: https://www.cnblogs.com/jayway0day/
  [142]: https://jalalsela.com/
  [143]: https://iot-security.wiki
  [144]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8E-unicorn-%E7%9A%84%E5%8D%95%E4%B8%AA%E5%87%BD%E6%95%B0%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8C%E5%92%8C-fuzzer-%E5%AE%9E%E7%8E%B0/
  [145]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [146]: http://galaxylab.com.cn/afl%E4%BD%BF%E7%94%A8101/
  [147]: https://medium.com/hackernoon/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf
  [148]: https://www.cnblogs.com/WangAoBo/p/8280352.html
  [149]: https://xz.aliyun.com/t/5155
  [150]: https://www.tuicool.com/articles/j2eqym6
  [151]: https://www.secpulse.com/archives/71898.html
  [152]: https://www.freebuf.com/sectool/213347.html
  [153]: https://bbs.pediy.com/thread-253868.htm
  [154]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [155]: https://www.ics-cert.org.cn/portal/page/133/cf6ae40284a9445098bc4876eaa701b1.html
  [156]: https://www.usenix.org/conference/usenixsecurity19/presentation/zheng
  [157]: https://firmianay.github.io/2018/06/14/firmalice.html
  [158]: https://www.anquanke.com/post/id/170078
  [159]: https://blog.csdn.net/song_lee/article/details/104334096
  [160]: https://xz.aliyun.com/t/2805
  [161]: https://www.bugbank.cn/live/view.html?id=112706
  [162]: https://www.bugbank.cn/live/view.html?id=112432
  [163]: https://live.freebuf.com/detail/9c82bef60253479f3df1c0f2c802cebf
  [164]: https://mp.weixin.qq.com/s/ZojMGy_4e3Uvlsu5dnGWPA
  [165]: https://www.bilibili.com/video/BV1PE411E7Sz?from=search&seid=14546198786268353402
  [166]: https://www.bilibili.com/video/BV1CE411s7YX?from=search&seid=14546198786268353402
  [167]: https://cloud.tencent.com/developer/article/1005700
  [168]: https://www.jianshu.com/p/77293121030e
  [169]: https://e3pem.github.io/2019/08/26/0ctf-2019/embedded_heap/
  [170]: https://books.google.com.hk/books?id=6mOIToQVmO8C&pg=PA12&lpg=PA12&dq=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&source=bl&ots=uW-tX2dsbb&sig=ACfU3U0Tc8aNc0riddaXeiE3JcPjb3kLDA&hl=zh-CN&sa=X&redir_esc=y#v=onepage&q=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&f=false
  [171]: https://wrongbaud.github.io/router-teardown/?nsukey=/KEjloh%2bbczobN%2bEikQIFSrIO5FNmTQtFzGV7FrN6YNrvYQS%2bkO4fywtTv/q1sEax7raeB39N9XOi3/WoKSVnubD5g6HwnCZmStBFDzStFK64j0fUo0KToypAbXs2Wu3KVIqvvCjFS0PmO5UepBb9ntN7By04QxMDcrPQFheOCeHoM8j7bb0RMQYopkVYnqE5yui/ho8htfYOTn0LfHZdw==
  [172]: https://mp.weixin.qq.com/s/utcyVK41-iIzQUPeT5Zq9g6%E7%B3%BB%E7%BB%9F&f=false
  [173]: http://www.totolink.cn/index.php/Download/list/121.html
  [174]: https://service.fastcom.com.cn/download-list.html#0
  [175]: https://app.hiwifi.com/dstore.php?m=download&a=info
  [176]: ftp://ftp2.dlink.com/PRODUCTS
  [177]: https://service.tp-link.com.cn/download?classtip=software&p=1&o=0
  [178]: https://service.mercurycom.com.cn/download-list.html
  [179]: https://www.tenda.com.cn/download/cata-11.html
  [180]: http://www.netcoretec.com/download.html
  [181]: http://www.wayos.com/download/luyougujian.html
  [182]: https://www.utt.com.cn/downloadcenter.php
  [183]: http://www.ruijie.com.cn/fw/rj/
  [184]: http://www.adslr.com/companyfile/2/
  [185]: http://www.newifi.com/download.shtml
  [186]: http://www.b-link.net.cn/download.php?CateId=11
  [187]: https://www.asus.com.cn/support/Download-Center/
  [188]: https://www.tenda.com.cn/download/cata-11.html
  [189]: http://www.tuoshi.cn/download.asp
  [190]: http://www.netis-systems.com/Suppory/de_details/id/1/de/50.html
  [191]: https://www.asus.com.cn/Networking/RTAC68U/HelpDesk_BIOS/
  [192]: https://www.draytek.com.tw/ftp/
  [193]: http://www.grandstream.cn/Xiazai.aspx?TypeId=65
  [194]: https://www.linksys.com/us/support-article/?articleNum=114663
  [195]: https://support.ruckuswireless.com/software?direction=desc&sort=updated_at
  [196]: https://security.tp-link.com.cn/service/download?classtip=2&p=1&o=0
  [197]: https://www.xiongmaitech.com/service/down/13
  [198]: https://avtech.com/support/
  [199]: https://service.fastcom.com.cn/download-list.html#0
  [200]: https://zhuanlan.zhihu.com/p/27312102
  [201]: http://newpaper.dahe.cn/dhb/html/2015-03/27/content_1240435.htm?div=-1
  [202]: https://baijiahao.baidu.com/s?id=1608672836032406833&wfr=spider&for=pc
  [203]: https://www.t00ls.net/articles-54495.html
  [204]: https://mp.weixin.qq.com/s/E0pEAADV7kMrpTIYqjip0g
  [205]: https://www.leiphone.com/news/202002/oSS5YNySfUC4ptfy.html
