# IOT 安全实战资料收集整合

标签（空格分隔）： 学习资料

---

## 适合入门的资料

[伏辰实验室-物联网安全百科][1]

[绿盟 - 智能设备安全分析手册][2]

[物联网安全从入门到入坑][3]

## 环境搭建

[路由器漏洞挖掘测试环境的搭建之问题总结][4]


## 固件提取&固件分析

http://www.devttys0.com/2011/06/mystery-file-system/
http://www.devttys0.com/2011/05/reverse-engineering-firmware-linksys-wag120n/

[逆向路由器固件之解包][5]

[基于 VxWorks 的嵌入式设备固件分析方法介绍][6]

[TP-Link wr886nv7-V1.1.0 路由器分析 – 固件初步分析][7]

[TP-Link wr886nv7-V1.1.0 路由器分析 - VxWorks cmd命令行获取及使用方法][8]

[物联网设备的固件分析技术][9]

[VxWorks固件逆向：WRT54Gv8][10]

[工控漏洞挖掘方法之固件逆向分析][11]

[路由固件的逆向解包及破解方法][12]

[深入分析Ewon Flexy物联网路由器（下）][13]

[D-Link DIR-850L路由器分析之获取设备shell][14]

[TP-Link wr886nv6 固件解析][15]

[Reverse Engineering VxWorks Firmware: WRT54Gv8][16]

[IoT固件逆向入门][17]

[安全小课堂第118期【IOT漏洞挖掘之路由器】][18]

[关于IoT安全我有话说][19]

[智能路由器安全特性分析][20]

[Reversing D-Link’s WPS Pin Algorithm][21]

[D-Link DIR-816 A2路由器安全研究分享][22]

[路由器固件安全分析技术（一）][23]

[极路由安全设计架构分析][24]
https://www.freebuf.com/articles/terminal/76046.html

[binwalk提取固件失败][25]

[U-boot详解：板子上电时都干了些什么][26]

[IOT物理安全-固件提取基础(1)][27]

[IoT固件提取以及固件分析的workshop资料–Jett][28]


### 固件加密

[某智能设备固件解密][29]
[如何处理加密路由器固件][30]


### 固件修改

[固件修改及编译记录][31]


### 固件调试

[如何通过 TTL 调试光猫][32]

### 信息收集

[逆向路由器固件之信息泄露][33]
[逆向路由器固件之敏感信息泄露 Part2][34]
[tenda 某路由器信息泄露查找][35]


## 实例漏洞分析

### 路由器

#### 命令执行漏洞
1. [重现 TP-Link SR20 本地网络远程代码执行漏洞][36]
2. 
[由一道工控路由器固件逆向题目看命令执行漏洞][37]

2. [分析Belkin SURF路由器中的多个漏洞][38]（缓冲区溢出、后门）

3. [H4lo - 路由器漏洞分析系列][39]

4. [kczwa1 - 路由器 CVE 复现][40] 

5. [360 IOT 人才培养计划][41]
https://bbs.ichunqiu.com/thread-32773-1-1.html?from=beef
6. [腾达 Tenda 路由器后门分析][42]

7. [D-Link 路由器HNAP协议系列漏洞披露（DIR-823G、DIR-878、DNS 重绑定攻击）][43]

8. [Dlink DIR 路由器HNAP登录函数的多个漏洞][44]

9. [dir-890l 命令执行漏洞分析][45]

10. [D-Link 系列路由器漏洞挖掘入门][46]

11. [TP-LINK wr-842n 等多款无线路由器（新界面2015）存在多个致命漏洞][47]

12. [实测一款IoT路由的安全性如何？从web到硬件，我们进行了全面的漏洞挖掘和分析（下）][48]
13. [Some vulnerability in ASUS routers][49]

14. [TP-LINK WR941N路由器研究][50]

15. [华硕路由器9999端口远程命令执行研究报告 V1][51]

16. [分析多款D-Link路由器中的未授权RCE漏洞][52]

17. [腾达AC15路由器上的远程代码(CVE-2018-5767)执行演练][53]

18. [你用它上網，我用它進你內網! 中華電信數據機遠端代碼執行漏洞][54]

19. [必虎路由器大量高危漏洞分析][55]

20. [D-Link DIR-859的RCE漏洞（CVE-2019–17621）][56]

    [D-Link DIR-859 RCE漏洞（CVE-2019-17621）分析复现][57]

21. [D-Link DIR-878 路由器存在漏洞两枚][58]

22. [DLINK DIR-859 ssdpcgi 命令注入][59]

#### 拒绝服务

[TP-LINK wr-886n 拒绝服务][60]

[CVE-2018-0296 Cisco ASA 拒绝服务漏洞分析][61]

[CVE-2019-1663 Cisco 的多个低端设备的堆栈缓冲区溢出漏洞分析][62]

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[tplink wr940 缓冲区溢出][63]



#### 未授权访问

[实测绕过腾达某型号路由器后台登陆认证，获得管理权限][64]

[如何日穿自家光猫][65]

[D-Link多型号路由器存在任意文件下载漏洞（CVE-2018-10822）][66]

[某些型号的Comba和D-Link路由器存在管理员密码泄露漏洞][67]

[ZXHN H108N Router Web-Shell and Secrets][68]

[Dlink Shareport Web Access Authentication Bypass][69]

#### 信息泄露

[影响 NETGEAR 路由器的 0-Day：KCodes NetUSB 两个安全漏洞披露（CVE-2019-5016/5017）][70]


#### MikroTik

[MikroTik RouterOS][71]


### DLINK - DIR 系列 CVE

CVE-2016-6563
CVE-2019-8312

### UPNP 相关漏洞

[P2P 网络核心技术：UPnP 和 SSDP 协议][72]

http://www.360doc.com/content/14/1009/17/13468863_415575489.shtml

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[D-Link DIR-615 XSS Via the UPnP Protocol][73]

[UPnP 安全（二）：UPnP 协议具体流程][74]

[D-Link DIR-859 —未经身份验证的RCE(CVE-2019–17621)][75]



### SMB

[路由器抓包分析之 SMB 篇][76]

### SNMP

[多种设备基于 SNMP 协议的敏感信息泄露漏洞数据分析报告][77]

## 摄像头安全

[以某家用摄像头测评入手谈物联网智能家居安全][78]

[vivetok 摄像头远程栈溢出漏洞分析][79]

[智能摄像头安全分析及案例参考][80]

[绕过某摄像头校验机制软刷固件][81]

[IT_Security_Research_WirelessIP_camera_family][82]

[一款摄像头的安全测试-1][83]

[一款摄像头的安全测试-2][84]

[IT Security Research by Pierre][85]

[亚马逊Blink智能摄像头曝出劫持漏洞][86]
- **响应包存在 root 命令注入**

![image.png-136kB][87]

[智能摄像头安全分析及案例参考][88]

## 门锁安全

[硬件安全|智能门锁安全研究方法总结][89]

## 智能音箱安全

[物联网安全系列之远程破解Google Home][90]


## 嵌入式设备固件逆向

[嵌入式逆向工程入门：STM32F103C8T6 上 的 FreeRTOS & Libopencm3][91]
[嵌入式设备硬件 PCB 级逆向][92]
[渗透低性能智能设备的关键技术-固件提取][93]


## 其他智能设备/工控设备

https://www.exploitee.rs/index.php/FireFU_Exploit

[网络设备漏洞分析技术研究（KCON2016议题）][94]

[2018年 KCon 议题解读 | 智能家居安全——身份劫持][95]

[如何PWN掉西门子工控设备][96]

[破解微软智能手环][97]

[指纹锁的硬件逆向工程][98]

[攻击案例 -- 数字密码锁 - 手把手DIY，教你强攻嵌入式设备那些黑科技][99]

[分析逆向通信HACK升降桌后感想][100]



## 整合/总结性资料

https://github.com/V33RU/IoTSecurity101
https://xz.aliyun.com/t/2278
[伏宸安全实验室-知乎专栏][101]

[物联网（IOT）安全测试经验总结][102]

[绿盟 - 智能设备安全分析手册][103]

[OWASP TOP10 物联网漏洞一览][104]

[secwiki - 设备安全][105]

## 漏洞挖掘思路/技巧

> 智能硬件的攻击面也主要在 协议 这一块， 比如协议数据的加密问题， 协议的权限问题，认证机制以及对数据的处理问题（堆栈溢出）

https://www.cnblogs.com/hac425/p/9674758.html

[D-Link DIR-850L路由器分析之获取设备shell][106]

[对嵌入式设备的逆向分析与漏洞利用：软件栈（第一部分）][107]

[看雪2018峰会回顾_智能设备漏洞挖掘中几个突破点(内有十种固件提取方法和首次公开uboot提取固件方法)][108]

[路由器0day漏洞挖掘实战](https://www.anquanke.com/post/id/180714)

浅谈路由器漏洞挖掘（科普文）


## 固件逆向工具使用

[固件逆向分析过程中的工具和技巧（上）][109]

[固件逆向分析过程中的工具和技巧（下）][110]

[mips 漏洞利用框架][111]

## IOT 安全开发

[假如你的灯被入侵了][112]


## IOT 大佬的博客

[devttys0][113]
[giantbranch][114]
https://github.com/xinali/articles
[银河安全实验室][115]
[cq][116]
[hac425][117]
[secwiki 路由器漏洞相关资料][118]
https://github.com/leonW7?tab=repositories
[ray-cp][119]
[jayway0day][120]
https://wzt.ac.cn/2020/01/10/firmadyne2/
http://www.gandalf.site/
[jalalsela][121]


伏宸安全实验室

## fuzz && unicorn

[基于 unicorn 的单个函数模拟执行和 fuzzer 实现][122]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][123]

[American Fuzzy Lop/AFL使用/][124]

[IoT设备固件分析之网络协议fuzz][125]

[M4x - afl-fuzz技术初探][126]

[初探BooFuzz][127]

https://www.cnblogs.com/studyskill/category/1028655.html

[初探Windows Fuzzing神器----Winafl][128]

[fuzz实战之libfuzzer][129]

https://github.com/Dor1s/libfuzzer-workshop/tree/master/lessons

[Cotopaxi：使用指定IoT网络协议对IoT设备进行安全测试][130]

[Unicorn 在 Android 的应用][131]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][132]


[IOTFUZZER：通过基于应用程序的模糊测试发现物联网中的内存损坏][133]

- 相关视频：https://www.youtube.com/watch?v=Ys2FBmdbdIw

[FIRM-AFL: High-Throughput Greybox Fuzzing of IoT Firmware via Augmented Process Emulation][134]

[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware][135]


## IOT 安全视频教学

[边界IOT漏洞挖掘精要][136]
[家用路由器漏洞挖掘入门][137]
[物联网设备漏洞挖掘思路与技巧][138]
[ChaMd5安全团队 带你入坑物联网安全][139]


## 固件加密

https://www.docin.com/p-882254908.html

[四个字节的安全 ：一次固件加密算法的逆向分析][140]


## CTF 题目

[Real World Finals 2018 Router][141]

[0ctf2019 Final embedded_heap题解][142]


## 国外技术文章

[afl-unicorn: Fuzzing Arbitrary Binary Code][143]

http://www.routerpwn.com/

https://firmwaresecurity.com/

[路由器分析之硬件拆卸][144]

https://blog.3or.de/



## 嵌入式基础知识
uboot

uimage

https://www.jianshu.com/p/01e5dd7c979a

## 文件系统

1. https://elinux.org/File_Systems

2. [linux 与嵌入式系统][145]


## 相关命令

解压 lzma 格式压缩数据：

```
lzma -kdc A200.lzma > A200
lzmadec -kd fwr2.lzma>fwr22
```

### jffs2 文件系统的处理

https://blog.51cto.com/axlrose/1317610

## 国内 or 国外路由器固件下载

[TOTOLINK][146]
http://www.totolink.net/
[FAST][147]
[极路由/hiwifi][148]
[D-LINK][149]
[TP-LINK][150]
[MERCURY][151]
[Tenda][152]
[磊科][153]
[维盟][154]
http://www.wayos.com:8081/download/
[艾泰][155]
[锐捷路由器][156]
[飞鱼星][157]
[newifi][158]
[b-link][159]
[华硕][160]
[腾达][161]
[拓实][162]
[netis][163]

## 摄像头固件

[tp-link][164]

## 事件报道

[4G无线路由曝致命漏洞，攻击者可执行任意代码][165]
[破解了十款路由器之后，我们有话要说][166]
[数数那些坑你的路由器漏洞][167]
[腾讯安全团队新发现：智能音箱摇身一变成间谍][168]
[大量Ruckus路由器出现漏洞，易受黑客攻击][169]
[启明星辰ADLab：某摄像头产品漏洞分析及解决方案][170]



  [79 https://service.fastcom.com.cn/downloa## 标题 ##d-list.html#0


  [1]: https://iot-security.wiki
  [2]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [3]: https://paper.seebug.org/1045/
  [4]: https://xz.aliyun.com/t/3826
  [5]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E8%A7%A3%E5%8C%85/
  [6]: https://paper.seebug.org/771/
  [7]: https://www.secpulse.com/archives/75635.html
  [8]: https://mp.weixin.qq.com/s/6q3zAaS4jV_Mw3qvgtngBw
  [9]: https://www.cnblogs.com/ssooking/articles/6144577.html
  [10]: https://www.anquanke.com/post/id/176481
  [11]: https://paper.seebug.org/613/
  [12]: https://blog.csdn.net/leekwen/article/details/53635462
  [13]: https://www.anquanke.com/post/id/180864
  [14]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [15]: https://cq674350529.github.io/2018/09/19/TP-Link-wr886v6-%E5%9B%BA%E4%BB%B6%E8%A7%A3%E6%9E%90/
  [16]: http://www.devttys0.com/2011/07/reverse-engineering-vxworks-firmware-wrt54gv8/
  [17]: http://zeroyu.xyz/2019/08/15/How_to_start_IoT_Reverse/
  [18]: https://www.secpulse.com/archives/81577.html
  [19]: https://www.freebuf.com/articles/ics-articles/210776.html
  [20]: https://security.tencent.com/index.php/blog/msg/91
  [21]: http://www.devttys0.com/2014/10/reversing-d-links-wps-pin-algorithm/
  [22]: https://mp.weixin.qq.com/s/rT53P9EW4xLFV9JLbnLroQ
  [23]: https://www.cnblogs.com/k1two2/p/7072709.html
  [24]: https://www.freebuf.com/articles/terminal/75524.html
  [25]: https://mp.weixin.qq.com/s/E9h0lT184wBiDyojuWx1CA
  [26]: https://mp.weixin.qq.com/s/Sxi9fQ_Jtj5xC5gm-nr5WQ
  [27]: https://mp.weixin.qq.com/s/l73iLAayzajs4HQgnnIpYg
  [28]: https://github.com/C00kie-/workshop-materials
  [29]: https://5alt.me/2017/08/%E6%9F%90%E6%99%BA%E8%83%BD%E8%AE%BE%E5%A4%87%E5%9B%BA%E4%BB%B6%E8%A7%A3%E5%AF%86/
  [30]: https://www.anquanke.com/post/id/198311
  [31]: https://xz.aliyun.com/t/6053
  [32]: https://paper.seebug.org/506/
  [33]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E4%BA%8C/
  [34]: https://www.freebuf.com/articles/terminal/76481.html
  [35]: https://blog.csdn.net/qq_27446553/article/details/79125129
  [36]: https://paper.seebug.org/879/
  [37]: https://www.anquanke.com/post/id/183202
  [38]: https://www.anquanke.com/post/id/183326
  [39]: https://www.anquanke.com/search?s=%E8%B7%AF%E7%94%B1%E5%99%A8%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98
  [40]: https://www.freebuf.com/author/kczwa1
  [41]: https://mp.weixin.qq.com/s?__biz=MjM5NjM2NDU0Ng==&mid=2450189577&idx=1&sn=ad2f8f7089f9c67ba6e6676e1cb933a2&chksm=b11425648663ac7214afcacf625f4e1f58647ff90dc83aea5764a10c2b55463b20ba0d592848&token=1945049632&lang=zh_CN&scene=21#wechat_redirect
  [42]: https://www.freebuf.com/articles/terminal/14425.html
  [43]: https://www.heibai.org/post/1395.html
  [44]: https://www.anquanke.com/post/id/84912
  [45]: http://www.devttys0.com/2015/04/hacking-the-d-link-dir-890l/
  [46]: https://www.cnblogs.com/HacTF/p/8052279.html
  [47]: https://www.secpulse.com/archives/35760.html
  [48]: https://mp.weixin.qq.com/s/p_lQQ_X4up004LCpNHyrnw
  [49]: https://www.securityartwork.es/2018/01/25/some-vulnerability-in-asus-routers/
  [50]: https://paper.seebug.org/448/
  [51]: https://blog.knownsec.com/2015/01/report-of-asua-router-9999-port-remote-command-execution-v1/
  [52]: https://www.anquanke.com/post/id/187923
  [53]: https://bbs.pediy.com/thread-225671.htm
  [54]: https://blog.orange.tw/2019/11/HiNet-GPON-Modem-RCE.html?nsukey=Z%2bR9JgOkzUjLo8kbR45klrA5HZVClqg%2bg27Fyo6HW0z%2bAXWeGL38o75v6cFXTVLUeBaTpMVhhszEphXPakYx%2b3ZBRsHBRBp4x17HzOp9oB2K/XvK9iSBOLXDe/gKVn4T%2b8MDkZVzEDHgILZPfe6WXMbcpe20UQlKs8ajTpNynCo=
  [55]: https://www.cnblogs.com/k1two2/p/5808839.html
  [56]: https://nosec.org/home/detail/3772.html
  [57]: https://mp.weixin.qq.com/s/TzFepaBpYnMbZ8Mep4IXwA
  [58]: https://wzt.ac.cn/2019/09/18/D-Link_BUG/
  [59]: https://medium.com/@s1kr10s/d-link-dir-859-unauthenticated-rce-en-ssdpcgi-http-st-cve-2019-20215-es-6ec205f5cf
  [60]: https://github.com/PAGalaxyLab/VulInfo/blob/master/TP-Link/WR886N/inetd_task_dos_13/README.md
  [61]: https://cq674350529.github.io/2019/03/01/CVE-2018-0296-Cisco-ASA-%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  [62]: https://paper.seebug.org/1039/
  [63]: https://securityintelligence.com/buffer-overflow-vulnerability-in-tp-link-routers-can-allow-remote-attackers-to-take-control/
  [64]: https://mrxn.net/jswz/tenda-authentic-bypass.html/comment-page-2
  [65]: https://www.anquanke.com/post/id/183998
  [66]: https://nosec.org/home/detail/1913.html
  [67]: https://nosec.org/home/detail/2949.html
  [68]: https://jalalsela.com/zxhn-h108n-router-web-shell-secrets/
  [69]: https://cyberloginit.com/2019/09/10/dlink-shareport-web-access-authentication-bypass.html
  [70]: https://www.chainnews.com/articles/042047440649.htm
  [71]: https://www.anquanke.com/post/id/183451
  [72]: https://www.jianshu.com/p/e41aa1428df3
  [73]: https://github.com/reevesrs24/CVE/blob/master/D-Link_DIR-615/xss_UPnP/dlink_dir615_xss_upnp.md
  [74]: https://www.attacker.cc/index.php/archives/113/
  [75]: https://xz.aliyun.com/t/7039
  [76]: https://www.freebuf.com/news/193340.html
  [77]: https://paper.seebug.org/795/
  [78]: https://www.freebuf.com/articles/terminal/207584.html
  [79]: https://www.anquanke.com/post/id/185336
  [80]: https://www.anquanke.com/post/id/178795
  [81]: http://invicsfate.cc/2018/10/09/%E7%BB%95%E8%BF%87%E6%9F%90%E6%91%84%E5%83%8F%E5%A4%B4%E6%A0%A1%E9%AA%8C%E6%9C%BA%E5%88%B6%E8%BD%AF%E5%88%B7%E5%9B%BA%E4%BB%B6/
  [82]: https://github.com/eloygn/IT_Security_Research_WirelessIP_camera_family
  [83]: https://mp.weixin.qq.com/s/mY3I60dcXQHxof79NvOAFw
  [84]: https://www.pentestpartners.com/security-blog/hacking-the-aldi-ip-cctv-camera-part-2/
  [85]: https://pierrekim.github.io/blog/2017-03-08-camera-goahead-0day.html
  [86]: https://www.freebuf.com/column/222661.html
  [87]: http://static.zybuluo.com/H4l0/gzrod4v52vfltfxzlg6bx29m/image.png
  [88]: https://www.freebuf.com/articles/terminal/203311.html
  [89]: https://nosec.org/home/detail/2760.html
  [90]: https://mp.weixin.qq.com/s/4kO3pU_tCDZmgj2CkROzMg
  [91]: https://bbs.pediy.com/thread-247140.htm
  [92]: https://zhuanlan.zhihu.com/p/28294785
  [93]: http://blog.nsfocus.net/firmware-extraction/
  [94]: https://www.freebuf.com/articles/system/114741.html
  [95]: https://xz.aliyun.com/t/2664
  [96]: https://www.freebuf.com/articles/network/213897.html
  [97]: http://drops.xmd5.com/static/drops/wireless-15139.html
  [98]: https://mp.weixin.qq.com/s/D8Q9jgk4TodLPf4GoqTfGg
  [99]: http://39.elecfans.com/20170804537214_3.html
  [100]: https://mp.weixin.qq.com/s/d8qi8F-M3g857LwZJff-_g
  [101]: https://zhuanlan.zhihu.com/future-sec
  [102]: http://www.polaris-lab.com/index.php/archives/48/
  [103]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [104]: https://xz.aliyun.com/t/2278
  [105]: https://www.sec-wiki.com/news/index/tag/device/
  [106]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [107]: https://www.anquanke.com/post/id/95055
  [108]: https://bbs.pediy.com/thread-230095.htm
  [109]: https://mp.weixin.qq.com/s?__biz=MzI0MDY1MDU4MQ==&mid=2247493390&idx=2&sn=94582aa41410f53b608ec803c1fb8203&chksm=e9153734de62be22558307ba47f949345c2ed9dd445d215d9786f45e556394f151b8558f3cf1&scene=21#wechat_redirect
  [110]: https://www.chainnews.com/articles/550133689280.htm
  [111]: https://github.com/zcutlip/bowcaster
  [112]: https://mp.weixin.qq.com/s/O1sJv5IBGJVZCbPGqUNHjw
  [113]: http://www.devttys0.com/blog/
  [114]: http://www.giantbranch.cn
  [115]: http://galaxylab.com.cn
  [116]: https://cq674350529.github.io/categories/IoT/
  [117]: http://www.cnblogs.com/hac425/
  [118]: https://sec-wiki.com/news/search?wd=%E8%B7%AF%E7%94%B1%E5%99%A8
  [119]: https://ray-cp.github.io/
  [120]: https://www.cnblogs.com/jayway0day/
  [121]: https://jalalsela.com/
  [122]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8E-unicorn-%E7%9A%84%E5%8D%95%E4%B8%AA%E5%87%BD%E6%95%B0%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8C%E5%92%8C-fuzzer-%E5%AE%9E%E7%8E%B0/
  [123]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [124]: http://galaxylab.com.cn/afl%E4%BD%BF%E7%94%A8101/
  [125]: https://medium.com/hackernoon/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf
  [126]: https://www.cnblogs.com/WangAoBo/p/8280352.html
  [127]: https://xz.aliyun.com/t/5155
  [128]: https://www.tuicool.com/articles/j2eqym6
  [129]: https://www.secpulse.com/archives/71898.html
  [130]: https://www.freebuf.com/sectool/213347.html
  [131]: https://bbs.pediy.com/thread-253868.htm
  [132]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [133]: https://www.ics-cert.org.cn/portal/page/133/cf6ae40284a9445098bc4876eaa701b1.html
  [134]: https://www.usenix.org/conference/usenixsecurity19/presentation/zheng
  [135]: https://firmianay.github.io/2018/06/14/firmalice.html
  [136]: https://www.bugbank.cn/live/view.html?id=112706
  [137]: https://www.bugbank.cn/live/view.html?id=112432
  [138]: https://live.freebuf.com/detail/9c82bef60253479f3df1c0f2c802cebf
  [139]: https://mp.weixin.qq.com/s/ZojMGy_4e3Uvlsu5dnGWPA
  [140]: https://cloud.tencent.com/developer/article/1005700
  [141]: https://www.jianshu.com/p/77293121030e
  [142]: https://e3pem.github.io/2019/08/26/0ctf-2019/embedded_heap/
  [143]: https://books.google.com.hk/books?id=6mOIToQVmO8C&pg=PA12&lpg=PA12&dq=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&source=bl&ots=uW-tX2dsbb&sig=ACfU3U0Tc8aNc0riddaXeiE3JcPjb3kLDA&hl=zh-CN&sa=X&redir_esc=y#v=onepage&q=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&f=false
  [144]: https://wrongbaud.github.io/router-teardown/?nsukey=/KEjloh%2bbczobN%2bEikQIFSrIO5FNmTQtFzGV7FrN6YNrvYQS%2bkO4fywtTv/q1sEax7raeB39N9XOi3/WoKSVnubD5g6HwnCZmStBFDzStFK64j0fUo0KToypAbXs2Wu3KVIqvvCjFS0PmO5UepBb9ntN7By04QxMDcrPQFheOCeHoM8j7bb0RMQYopkVYnqE5yui/ho8htfYOTn0LfHZdw==
  [145]: https://mp.weixin.qq.com/s/utcyVK41-iIzQUPeT5Zq9g6%E7%B3%BB%E7%BB%9F&f=false
  [146]: http://www.totolink.cn/index.php/Download/list/121.html
  [147]: https://service.fastcom.com.cn/download-list.html#0
  [148]: https://app.hiwifi.com/dstore.php?m=download&a=info
  [149]: ftp://ftp2.dlink.com/PRODUCTS
  [150]: https://service.tp-link.com.cn/download?classtip=software&p=1&o=0
  [151]: https://service.mercurycom.com.cn/download-list.html
  [152]: https://www.tenda.com.cn/download/cata-11.html
  [153]: http://www.netcoretec.com/download.html
  [154]: http://www.wayos.com/download/luyougujian.html
  [155]: https://www.utt.com.cn/downloadcenter.php
  [156]: http://www.ruijie.com.cn/fw/rj/
  [157]: http://www.adslr.com/companyfile/2/
  [158]: http://www.newifi.com/download.shtml
  [159]: http://www.b-link.net.cn/download.php?CateId=11
  [160]: https://www.asus.com.cn/support/Download-Center/
  [161]: https://www.tenda.com.cn/download/cata-11.html
  [162]: http://www.tuoshi.cn/download.asp
  [163]: http://www.netis-systems.com/Suppory/de_details/id/1/de/50.html
  [164]: https://security.tp-link.com.cn/service/download?classtip=2&p=1&o=0
  [165]: https://service.fastcom.com.cn/download-list.html#0
  [166]: https://zhuanlan.zhihu.com/p/27312102
  [167]: http://newpaper.dahe.cn/dhb/html/2015-03/27/content_1240435.htm?div=-1
  [168]: https://baijiahao.baidu.com/s?id=1608672836032406833&wfr=spider&for=pc
  [169]: https://www.t00ls.net/articles-54495.html
  [170]: https://mp.weixin.qq.com/s/E0pEAADV7kMrpTIYqjip0g
