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


### 固件加密

[某智能设备固件解密][27]

### 固件修改

[固件修改及编译记录][28]


### 固件调试

[如何通过 TTL 调试光猫][29]

### 信息收集

[逆向路由器固件之信息泄露][30]
[逆向路由器固件之敏感信息泄露 Part2][31]
[tenda 某路由器信息泄露查找][32]


## 实例漏洞分析

### 路由器

#### 命令执行漏洞
1. [重现 TP-Link SR20 本地网络远程代码执行漏洞][33]
2. 
[由一道工控路由器固件逆向题目看命令执行漏洞][34]

2. [分析Belkin SURF路由器中的多个漏洞][35]（缓冲区溢出、后门）

3. [H4lo - 路由器漏洞分析系列][36]

4. [kczwa1 - 路由器 CVE 复现][37] 

5. [360 IOT 人才培养计划][38]
https://bbs.ichunqiu.com/thread-32773-1-1.html?from=beef
6. [腾达 Tenda 路由器后门分析][39]

7. [D-Link 路由器HNAP协议系列漏洞披露（DIR-823G、DIR-878、DNS 重绑定攻击）][40]

8. [Dlink DIR 路由器HNAP登录函数的多个漏洞][41]

9. [dir-890l 命令执行漏洞分析][42]

10. [D-Link 系列路由器漏洞挖掘入门][43]

11. [TP-LINK wr-842n 等多款无线路由器（新界面2015）存在多个致命漏洞][44]

12. [实测一款IoT路由的安全性如何？从web到硬件，我们进行了全面的漏洞挖掘和分析（下）][45]
13. [Some vulnerability in ASUS routers][46]

14. [TP-LINK WR941N路由器研究][47]

15. [华硕路由器9999端口远程命令执行研究报告 V1][48]

16. [分析多款D-Link路由器中的未授权RCE漏洞][49]

17. [腾达AC15路由器上的远程代码(CVE-2018-5767)执行演练][50]

18. [你用它上網，我用它進你內網! 中華電信數據機遠端代碼執行漏洞][51]

19. [必虎路由器大量高危漏洞分析][52]

20. [D-Link DIR-859的RCE漏洞（CVE-2019–17621）][53]


#### 拒绝服务

[TP-LINK wr-886n 拒绝服务][54]

[CVE-2018-0296 Cisco ASA 拒绝服务漏洞分析][55]

[CVE-2019-1663 Cisco 的多个低端设备的堆栈缓冲区溢出漏洞分析][56]

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[tplink wr940 缓冲区溢出][57]



#### 未授权访问

[实测绕过腾达某型号路由器后台登陆认证，获得管理权限][58]

[如何日穿自家光猫][59]

[D-Link多型号路由器存在任意文件下载漏洞（CVE-2018-10822）][60]

[某些型号的Comba和D-Link路由器存在管理员密码泄露漏洞][61]


#### MikroTik

[MikroTik RouterOS][62]


### DLINK - DIR 系列 CVE

CVE-2016-6563
CVE-2019-8312

### UPNP 相关漏洞

[P2P 网络核心技术：UPnP 和 SSDP 协议][63]

http://www.360doc.com/content/14/1009/17/13468863_415575489.shtml

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[D-Link DIR-615 XSS Via the UPnP Protocol][64]

### SMB

[路由器抓包分析之 SMB 篇][65]

### SNMP

[多种设备基于 SNMP 协议的敏感信息泄露漏洞数据分析报告][66]

## 摄像头安全

[以某家用摄像头测评入手谈物联网智能家居安全][67]

[vivetok 摄像头远程栈溢出漏洞分析][68]

[智能摄像头安全分析及案例参考][69]

[绕过某摄像头校验机制软刷固件][70]

[IT_Security_Research_WirelessIP_camera_family][71]

[一款摄像头的安全测试-1][72]

[一款摄像头的安全测试-2][73]

[IT Security Research by Pierre][74]

[亚马逊Blink智能摄像头曝出劫持漏洞][75]
- **响应包存在 root 命令注入**

![image.png-136kB][76]

[智能摄像头安全分析及案例参考][77]

## 门锁安全

[硬件安全|智能门锁安全研究方法总结][78]

## 智能音箱安全

[物联网安全系列之远程破解Google Home][79]


## 嵌入式设备固件逆向

[嵌入式逆向工程入门：STM32F103C8T6 上 的 FreeRTOS & Libopencm3][80]
[嵌入式设备硬件 PCB 级逆向][81]
[渗透低性能智能设备的关键技术-固件提取][82]


## 其他智能设备/工控设备

https://www.exploitee.rs/index.php/FireFU_Exploit

[网络设备漏洞分析技术研究（KCON2016议题）][83]

[2018年 KCon 议题解读 | 智能家居安全——身份劫持][84]

[如何PWN掉西门子工控设备][85]

[破解微软智能手环][86]

[指纹锁的硬件逆向工程][87]

[攻击案例 -- 数字密码锁 - 手把手DIY，教你强攻嵌入式设备那些黑科技][88]


## 整合/总结性资料

https://github.com/V33RU/IoTSecurity101
https://xz.aliyun.com/t/2278
[伏宸安全实验室-知乎专栏][89]

[物联网（IOT）安全测试经验总结][90]

[绿盟 - 智能设备安全分析手册][91]

[OWASP TOP10 物联网漏洞一览][92]

[secwiki - 设备安全][93]

## 漏洞挖掘思路/技巧

> 智能硬件的攻击面也主要在 协议 这一块， 比如协议数据的加密问题， 协议的权限问题，认证机制以及对数据的处理问题（堆栈溢出）

https://www.cnblogs.com/hac425/p/9674758.html

[D-Link DIR-850L路由器分析之获取设备shell][94]

[对嵌入式设备的逆向分析与漏洞利用：软件栈（第一部分）][95]

[看雪2018峰会回顾_智能设备漏洞挖掘中几个突破点(内有十种固件提取方法和首次公开uboot提取固件方法)][96]

[路由器0day漏洞挖掘实战](https://www.anquanke.com/post/id/180714)

浅谈路由器漏洞挖掘（科普文）


## 固件逆向工具使用

[固件逆向分析过程中的工具和技巧（上）][97]

[固件逆向分析过程中的工具和技巧（下）][98]

[mips 漏洞利用框架][99]


## IOT 大佬的博客

[devttys0][100]
[giantbranch][101]
https://github.com/xinali/articles
[银河安全实验室][102]
[cq][103]
[hac425][104]
[secwiki 路由器漏洞相关资料][105]
https://github.com/leonW7?tab=repositories
[ray-cp][106]
[jayway0day][107]

伏宸安全实验室

## fuzz && unicorn

[基于 unicorn 的单个函数模拟执行和 fuzzer 实现][108]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][109]

[American Fuzzy Lop/AFL使用/][110]

[IoT设备固件分析之网络协议fuzz][111]

[M4x - afl-fuzz技术初探][112]

[初探BooFuzz][113]

https://www.cnblogs.com/studyskill/category/1028655.html

[初探Windows Fuzzing神器----Winafl][114]

[fuzz实战之libfuzzer][115]

https://github.com/Dor1s/libfuzzer-workshop/tree/master/lessons

[Cotopaxi：使用指定IoT网络协议对IoT设备进行安全测试][116]

### unicorn 加载 ELF 文件

[Unicorn 在 Android 的应用][117]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][118]


[IOTFUZZER：通过基于应用程序的模糊测试发现物联网中的内存损坏][119]

- 相关视频：https://www.youtube.com/watch?v=Ys2FBmdbdIw

## 固件加密

https://www.docin.com/p-882254908.html

[四个字节的安全 ：一次固件加密算法的逆向分析][120]


## CTF 题目

[Real World Finals 2018 Router][121]

[0ctf2019 Final embedded_heap题解][122]


## 国外技术文章

[afl-unicorn: Fuzzing Arbitrary Binary Code][123]

http://www.routerpwn.com/

https://firmwaresecurity.com/

[路由器分析之硬件拆卸][124]

https://blog.3or.de/



## 嵌入式基础知识
uboot

uimage

https://www.jianshu.com/p/01e5dd7c979a

## 文件系统

1. https://elinux.org/File_Systems

2. [linux 与嵌入式系统][125]


## 相关命令

解压 lzma 格式压缩数据：

```
lzma -kdc A200.lzma > A200
lzmadec -kd fwr2.lzma>fwr22
```

### jffs2 文件系统的处理

https://blog.51cto.com/axlrose/1317610

## 路由器固件下载

[TOTOLINK][126]
http://www.totolink.net/
[FAST][127]
[极路由/hiwifi][128]
[D-LINK][129]
[TP-LINK][130]
[MERCURY][131]
[Tenda][132]
[磊科][133]
[维盟][134]
http://www.wayos.com:8081/download/
[艾泰][135]
[锐捷路由器][136]
[飞鱼星][137]
[newifi][138]
[b-link][139]
[华硕][140]
[腾达][141]
[拓实][142]
[netis][143]


## 事件报道

[4G无线路由曝致命漏洞，攻击者可执行任意代码][144]
[破解了十款路由器之后，我们有话要说][145]
[数数那些坑你的路由器漏洞][146]
[腾讯安全团队新发现：智能音箱摇身一变成间谍][147]
[大量Ruckus路由器出现漏洞，易受黑客攻击][148]



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
  [27]: https://5alt.me/2017/08/%E6%9F%90%E6%99%BA%E8%83%BD%E8%AE%BE%E5%A4%87%E5%9B%BA%E4%BB%B6%E8%A7%A3%E5%AF%86/
  [28]: https://xz.aliyun.com/t/6053
  [29]: https://paper.seebug.org/506/
  [30]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E4%BA%8C/
  [31]: https://www.freebuf.com/articles/terminal/76481.html
  [32]: https://blog.csdn.net/qq_27446553/article/details/79125129
  [33]: https://paper.seebug.org/879/
  [34]: https://www.anquanke.com/post/id/183202
  [35]: https://www.anquanke.com/post/id/183326
  [36]: https://www.anquanke.com/search?s=%E8%B7%AF%E7%94%B1%E5%99%A8%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98
  [37]: https://www.freebuf.com/author/kczwa1
  [38]: https://mp.weixin.qq.com/s?__biz=MjM5NjM2NDU0Ng==&mid=2450189577&idx=1&sn=ad2f8f7089f9c67ba6e6676e1cb933a2&chksm=b11425648663ac7214afcacf625f4e1f58647ff90dc83aea5764a10c2b55463b20ba0d592848&token=1945049632&lang=zh_CN&scene=21#wechat_redirect
  [39]: https://www.freebuf.com/articles/terminal/14425.html
  [40]: https://www.heibai.org/post/1395.html
  [41]: https://www.anquanke.com/post/id/84912
  [42]: http://www.devttys0.com/2015/04/hacking-the-d-link-dir-890l/
  [43]: https://www.cnblogs.com/HacTF/p/8052279.html
  [44]: https://www.secpulse.com/archives/35760.html
  [45]: https://mp.weixin.qq.com/s/p_lQQ_X4up004LCpNHyrnw
  [46]: https://www.securityartwork.es/2018/01/25/some-vulnerability-in-asus-routers/
  [47]: https://paper.seebug.org/448/
  [48]: https://blog.knownsec.com/2015/01/report-of-asua-router-9999-port-remote-command-execution-v1/
  [49]: https://www.anquanke.com/post/id/187923
  [50]: https://bbs.pediy.com/thread-225671.htm
  [51]: https://blog.orange.tw/2019/11/HiNet-GPON-Modem-RCE.html?nsukey=Z%2bR9JgOkzUjLo8kbR45klrA5HZVClqg%2bg27Fyo6HW0z%2bAXWeGL38o75v6cFXTVLUeBaTpMVhhszEphXPakYx%2b3ZBRsHBRBp4x17HzOp9oB2K/XvK9iSBOLXDe/gKVn4T%2b8MDkZVzEDHgILZPfe6WXMbcpe20UQlKs8ajTpNynCo=
  [52]: https://www.cnblogs.com/k1two2/p/5808839.html
  [53]: https://nosec.org/home/detail/3772.html
  [54]: https://github.com/PAGalaxyLab/VulInfo/blob/master/TP-Link/WR886N/inetd_task_dos_13/README.md
  [55]: https://cq674350529.github.io/2019/03/01/CVE-2018-0296-Cisco-ASA-%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  [56]: https://paper.seebug.org/1039/
  [57]: https://securityintelligence.com/buffer-overflow-vulnerability-in-tp-link-routers-can-allow-remote-attackers-to-take-control/
  [58]: https://mrxn.net/jswz/tenda-authentic-bypass.html/comment-page-2
  [59]: https://www.anquanke.com/post/id/183998
  [60]: https://nosec.org/home/detail/1913.html
  [61]: https://nosec.org/home/detail/2949.html
  [62]: https://www.anquanke.com/post/id/183451
  [63]: https://www.jianshu.com/p/e41aa1428df3
  [64]: https://github.com/reevesrs24/CVE/blob/master/D-Link_DIR-615/xss_UPnP/dlink_dir615_xss_upnp.md
  [65]: https://www.freebuf.com/news/193340.html
  [66]: https://paper.seebug.org/795/
  [67]: https://www.freebuf.com/articles/terminal/207584.html
  [68]: https://www.anquanke.com/post/id/185336
  [69]: https://www.anquanke.com/post/id/178795
  [70]: http://invicsfate.cc/2018/10/09/%E7%BB%95%E8%BF%87%E6%9F%90%E6%91%84%E5%83%8F%E5%A4%B4%E6%A0%A1%E9%AA%8C%E6%9C%BA%E5%88%B6%E8%BD%AF%E5%88%B7%E5%9B%BA%E4%BB%B6/
  [71]: https://github.com/eloygn/IT_Security_Research_WirelessIP_camera_family
  [72]: https://mp.weixin.qq.com/s/mY3I60dcXQHxof79NvOAFw
  [73]: https://www.pentestpartners.com/security-blog/hacking-the-aldi-ip-cctv-camera-part-2/
  [74]: https://pierrekim.github.io/blog/2017-03-08-camera-goahead-0day.html
  [75]: https://www.freebuf.com/column/222661.html
  [76]: http://static.zybuluo.com/H4l0/gzrod4v52vfltfxzlg6bx29m/image.png
  [77]: https://www.freebuf.com/articles/terminal/203311.html
  [78]: https://nosec.org/home/detail/2760.html
  [79]: https://mp.weixin.qq.com/s/4kO3pU_tCDZmgj2CkROzMg
  [80]: https://bbs.pediy.com/thread-247140.htm
  [81]: https://zhuanlan.zhihu.com/p/28294785
  [82]: http://blog.nsfocus.net/firmware-extraction/
  [83]: https://www.freebuf.com/articles/system/114741.html
  [84]: https://xz.aliyun.com/t/2664
  [85]: https://www.freebuf.com/articles/network/213897.html
  [86]: http://drops.xmd5.com/static/drops/wireless-15139.html
  [87]: https://mp.weixin.qq.com/s/D8Q9jgk4TodLPf4GoqTfGg
  [88]: http://39.elecfans.com/20170804537214_3.html
  [89]: https://zhuanlan.zhihu.com/future-sec
  [90]: http://www.polaris-lab.com/index.php/archives/48/
  [91]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [92]: https://xz.aliyun.com/t/2278
  [93]: https://www.sec-wiki.com/news/index/tag/device/
  [94]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [95]: https://www.anquanke.com/post/id/95055
  [96]: https://bbs.pediy.com/thread-230095.htm
  [97]: https://mp.weixin.qq.com/s?__biz=MzI0MDY1MDU4MQ==&mid=2247493390&idx=2&sn=94582aa41410f53b608ec803c1fb8203&chksm=e9153734de62be22558307ba47f949345c2ed9dd445d215d9786f45e556394f151b8558f3cf1&scene=21#wechat_redirect
  [98]: https://www.chainnews.com/articles/550133689280.htm
  [99]: https://github.com/zcutlip/bowcaster
  [100]: http://www.devttys0.com/blog/
  [101]: http://www.giantbranch.cn
  [102]: http://galaxylab.com.cn
  [103]: https://cq674350529.github.io/categories/IoT/
  [104]: http://www.cnblogs.com/hac425/
  [105]: https://sec-wiki.com/news/search?wd=%E8%B7%AF%E7%94%B1%E5%99%A8
  [106]: https://ray-cp.github.io/
  [107]: https://www.cnblogs.com/jayway0day/
  [108]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8E-unicorn-%E7%9A%84%E5%8D%95%E4%B8%AA%E5%87%BD%E6%95%B0%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8C%E5%92%8C-fuzzer-%E5%AE%9E%E7%8E%B0/
  [109]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [110]: http://galaxylab.com.cn/afl%E4%BD%BF%E7%94%A8101/
  [111]: https://medium.com/hackernoon/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf
  [112]: https://www.cnblogs.com/WangAoBo/p/8280352.html
  [113]: https://xz.aliyun.com/t/5155
  [114]: https://www.tuicool.com/articles/j2eqym6
  [115]: https://www.secpulse.com/archives/71898.html
  [116]: https://www.freebuf.com/sectool/213347.html
  [117]: https://bbs.pediy.com/thread-253868.htm
  [118]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [119]: https://www.ics-cert.org.cn/portal/page/133/cf6ae40284a9445098bc4876eaa701b1.html
  [120]: https://cloud.tencent.com/developer/article/1005700
  [121]: https://www.jianshu.com/p/77293121030e
  [122]: https://e3pem.github.io/2019/08/26/0ctf-2019/embedded_heap/
  [123]: https://books.google.com.hk/books?id=6mOIToQVmO8C&pg=PA12&lpg=PA12&dq=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&source=bl&ots=uW-tX2dsbb&sig=ACfU3U0Tc8aNc0riddaXeiE3JcPjb3kLDA&hl=zh-CN&sa=X&redir_esc=y#v=onepage&q=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&f=false
  [124]: https://wrongbaud.github.io/router-teardown/?nsukey=/KEjloh%2bbczobN%2bEikQIFSrIO5FNmTQtFzGV7FrN6YNrvYQS%2bkO4fywtTv/q1sEax7raeB39N9XOi3/WoKSVnubD5g6HwnCZmStBFDzStFK64j0fUo0KToypAbXs2Wu3KVIqvvCjFS0PmO5UepBb9ntN7By04QxMDcrPQFheOCeHoM8j7bb0RMQYopkVYnqE5yui/ho8htfYOTn0LfHZdw==
  [125]: https://mp.weixin.qq.com/s/utcyVK41-iIzQUPeT5Zq9g6%E7%B3%BB%E7%BB%9F&f=false
  [126]: http://www.totolink.cn/index.php/Download/list/121.html
  [127]: https://service.fastcom.com.cn/download-list.html#0
  [128]: https://app.hiwifi.com/dstore.php?m=download&a=info
  [129]: ftp://ftp2.dlink.com/PRODUCTS
  [130]: https://service.tp-link.com.cn/download?classtip=software&p=1&o=0
  [131]: https://service.mercurycom.com.cn/download-list.html
  [132]: https://www.tenda.com.cn/download/cata-11.html
  [133]: http://www.netcoretec.com/download.html
  [134]: http://www.wayos.com/download/luyougujian.html
  [135]: https://www.utt.com.cn/downloadcenter.php
  [136]: http://www.ruijie.com.cn/fw/rj/
  [137]: http://www.adslr.com/companyfile/2/
  [138]: http://www.newifi.com/download.shtml
  [139]: http://www.b-link.net.cn/download.php?CateId=11
  [140]: https://www.asus.com.cn/support/Download-Center/
  [141]: https://www.tenda.com.cn/download/cata-11.html
  [142]: http://www.tuoshi.cn/download.asp
  [143]: http://www.netis-systems.com/Suppory/de_details/id/1/de/50.html
  [144]: https://service.fastcom.com.cn/download-list.html#0
  [145]: https://zhuanlan.zhihu.com/p/27312102
  [146]: http://newpaper.dahe.cn/dhb/html/2015-03/27/content_1240435.htm?div=-1
  [147]: https://baijiahao.baidu.com/s?id=1608672836032406833&wfr=spider&for=pc
  [148]: https://www.t00ls.net/articles-54495.html
