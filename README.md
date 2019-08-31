# IOT_Articles_Collection
Some IOT Integration of Technical Articles

## 适合入门的资料

[伏辰实验室-物联网安全百科][1]

[绿盟 - 智能设备安全分析手册][2]

## 环境搭建

[路由器漏洞挖掘测试环境的搭建之问题总结][3]


## 固件提取&固件分析

http://www.devttys0.com/2011/06/mystery-file-system/
http://www.devttys0.com/2011/05/reverse-engineering-firmware-linksys-wag120n/

[逆向路由器固件之解包][4]

[基于 VxWorks 的嵌入式设备固件分析方法介绍][5]

[TP-Link wr886nv7-V1.1.0 路由器分析 – 固件初步分析][6]

[TP-Link wr886nv7-V1.1.0 路由器分析 - VxWorks cmd命令行获取及使用方法][7]

[物联网设备的固件分析技术][8]

[VxWorks固件逆向：WRT54Gv8][9]

[工控漏洞挖掘方法之固件逆向分析][10]

[路由固件的逆向解包及破解方法][11]

[深入分析Ewon Flexy物联网路由器（下）][12]

[D-Link DIR-850L路由器分析之获取设备shell][13]

[TP-Link wr886nv6 固件解析][14]

[Reverse Engineering VxWorks Firmware: WRT54Gv8][15]

[IoT固件逆向入门][16]

[安全小课堂第118期【IOT漏洞挖掘之路由器】][17]

[关于IoT安全我有话说][18]


### 固件调试

[如何通过 TTL 调试光猫][19]

### 信息收集

[逆向路由器固件之信息泄露][20]

## 实例漏洞分析

### 路由器

#### 命令执行漏洞
1. [重现 TP-Link SR20 本地网络远程代码执行漏洞][21]
2. 
[由一道工控路由器固件逆向题目看命令执行漏洞][22]

2. [分析Belkin SURF路由器中的多个漏洞][23]（缓冲区溢出、后门）

3. [H4lo - 路由器漏洞分析系列][24]

4. [kczwa1 - 路由器 CVE 复现][25] 

5. [360 IOT 人才培养计划][26]
https://bbs.ichunqiu.com/thread-32773-1-1.html?from=beef
6. [腾达 Tenda 路由器后门分析][27]

7. [D-Link 路由器HNAP协议系列漏洞披露（DIR-823G、DIR-878、DNS 重绑定攻击）][28]

8. [Dlink DIR 路由器HNAP登录函数的多个漏洞][29]

9. [dir-890l 命令执行漏洞分析][30]

10. [D-Link 系列路由器漏洞挖掘入门][31]

11. [TP-LINK wr-842n 等多款无线路由器（新界面2015）存在多个致命漏洞][32]

12. [实测一款IoT路由的安全性如何？从web到硬件，我们进行了全面的漏洞挖掘和分析（下）][33]


#### 拒绝服务

[TP-LINK wr-886n 拒绝服务][34]

[CVE-2018-0296 Cisco ASA 拒绝服务漏洞分析][35]

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp


#### 未授权访问

[实测绕过腾达某型号路由器后台登陆认证，获得管理权限][36]
[如何日穿自家光猫][37]

#### MikroTik

[MikroTik RouterOS][38]


### DLINK - DIR 系列 CVE

CVE-2016-6563
CVE-2019-8312

### UPNP 相关漏洞

[P2P 网络核心技术：UPnP 和 SSDP 协议][39]

http://www.360doc.com/content/14/1009/17/13468863_415575489.shtml

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=upnp

[D-Link DIR-615 XSS Via the UPnP Protocol][40]

### SMB

[路由器抓包分析之 SMB 篇][41]

### SNMP

[多种设备基于 SNMP 协议的敏感信息泄露漏洞数据分析报告][42]

## 摄像头安全

[以某家用摄像头测评入手谈物联网智能家居安全][43]

[vivetok 摄像头远程栈溢出漏洞分析][44]

[智能摄像头安全分析及案例参考][45]


## 门锁安全

[硬件安全|智能门锁安全研究方法总结][46]

## 嵌入式设备固件逆向

[嵌入式逆向工程入门：STM32F103C8T6 上 的 FreeRTOS & Libopencm3][47]

## 其他智能设备

https://www.exploitee.rs/index.php/FireFU_Exploit

[网络设备漏洞分析技术研究（KCON2016议题）][48]


## 整合/总结性资料

https://github.com/V33RU/IoTSecurity101
https://xz.aliyun.com/t/2278
[伏宸安全实验室-知乎专栏][49]

[物联网（IOT）安全测试经验总结][50]

[绿盟 - 智能设备安全分析手册][51]

[OWASP TOP10 物联网漏洞一览][52]

## 漏洞挖掘思路/技巧

> 智能硬件的攻击面也主要在 协议 这一块， 比如协议数据的加密问题， 协议的权限问题，认证机制以及对数据的处理问题（堆栈溢出）

https://www.cnblogs.com/hac425/p/9674758.html

[D-Link DIR-850L路由器分析之获取设备shell][53]

[对嵌入式设备的逆向分析与漏洞利用：软件栈（第一部分）][54]

[看雪2018峰会回顾_智能设备漏洞挖掘中几个突破点(内有十种固件提取方法和首次公开uboot提取固件方法)][55]

[路由器0day漏洞挖掘实战](https://www.anquanke.com/post/id/180714)

浅谈路由器漏洞挖掘（科普文）


## 固件逆向工具使用

[固件逆向分析过程中的工具和技巧（上）][56]

[固件逆向分析过程中的工具和技巧（下）][57]

[mips 漏洞利用框架][58]


## 大佬的博客

[devttys0][59]
[giantbranch][60]
https://github.com/xinali/articles
[银河安全实验室][61]
[cq][62]
[hac425][63]
[secwiki 路由器漏洞相关资料][64]
https://github.com/leonW7?tab=repositories
[ray-cp][65]

伏宸安全实验室

## fuzz

[基于 unicorn 的单个函数模拟执行和 fuzzer 实现][66]

[基于Unicorn和LibFuzzer的模拟执行fuzzing][67]

[American Fuzzy Lop/AFL使用/][68]

[IoT设备固件分析之网络协议fuzz][69]

[M4x - afl-fuzz技术初探][70]

[初探BooFuzz][71]


## CTF 题目

[Real World Finals 2018 Router][72]




## 国外技术文章

[afl-unicorn: Fuzzing Arbitrary Binary Code][73]

http://www.routerpwn.com/


## 嵌入式基础知识
uboot

uimage

https://www.jianshu.com/p/01e5dd7c979a

## 文件系统

1. https://elinux.org/File_Systems

2. [linux 与嵌入式系统][74]


## 相关命令

解压 lzma 格式压缩数据：

```
lzma -kdc A200.lzma > A200
lzmadec -kd fwr2.lzma>fwr22
```

## 路由器固件下载

[TOTOLINK][75]
[FAST][76]


## 事件报道

[4G无线路由曝致命漏洞，攻击者可执行任意代码][77]


  [1]: https://iot-security.wiki
  [2]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [3]: https://xz.aliyun.com/t/3826
  [4]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E8%A7%A3%E5%8C%85/
  [5]: https://paper.seebug.org/771/
  [6]: https://www.secpulse.com/archives/75635.html
  [7]: https://mp.weixin.qq.com/s/6q3zAaS4jV_Mw3qvgtngBw
  [8]: https://www.cnblogs.com/ssooking/articles/6144577.html
  [9]: https://www.anquanke.com/post/id/176481
  [10]: https://paper.seebug.org/613/
  [11]: https://blog.csdn.net/leekwen/article/details/53635462
  [12]: https://www.anquanke.com/post/id/180864
  [13]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [14]: https://cq674350529.github.io/2018/09/19/TP-Link-wr886v6-%E5%9B%BA%E4%BB%B6%E8%A7%A3%E6%9E%90/
  [15]: http://www.devttys0.com/2011/07/reverse-engineering-vxworks-firmware-wrt54gv8/
  [16]: http://zeroyu.xyz/2019/08/15/How_to_start_IoT_Reverse/
  [17]: https://www.secpulse.com/archives/81577.html
  [18]: https://www.freebuf.com/articles/ics-articles/210776.html
  [19]: https://paper.seebug.org/506/
  [20]: http://xdxd.love/2015/08/24/%E9%80%86%E5%90%91%E8%B7%AF%E7%94%B1%E5%99%A8%E5%9B%BA%E4%BB%B6%E4%B9%8B%E4%BA%8C/
  [21]: https://paper.seebug.org/879/
  [22]: https://www.anquanke.com/post/id/183202
  [23]: https://www.anquanke.com/post/id/183326
  [24]: https://www.anquanke.com/search?s=%E8%B7%AF%E7%94%B1%E5%99%A8%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98
  [25]: https://www.freebuf.com/author/kczwa1
  [26]: https://mp.weixin.qq.com/s?__biz=MjM5NjM2NDU0Ng==&mid=2450189577&idx=1&sn=ad2f8f7089f9c67ba6e6676e1cb933a2&chksm=b11425648663ac7214afcacf625f4e1f58647ff90dc83aea5764a10c2b55463b20ba0d592848&token=1945049632&lang=zh_CN&scene=21#wechat_redirect
  [27]: https://www.freebuf.com/articles/terminal/14425.html
  [28]: https://www.heibai.org/post/1395.html
  [29]: https://www.anquanke.com/post/id/84912
  [30]: http://www.devttys0.com/2015/04/hacking-the-d-link-dir-890l/
  [31]: https://www.cnblogs.com/HacTF/p/8052279.html
  [32]: https://www.secpulse.com/archives/35760.html
  [33]: https://mp.weixin.qq.com/s/p_lQQ_X4up004LCpNHyrnw
  [34]: https://github.com/PAGalaxyLab/VulInfo/blob/master/TP-Link/WR886N/inetd_task_dos_13/README.md
  [35]: https://cq674350529.github.io/2019/03/01/CVE-2018-0296-Cisco-ASA-%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/
  [36]: https://mrxn.net/jswz/tenda-authentic-bypass.html/comment-page-2
  [37]: https://www.anquanke.com/post/id/183998
  [38]: https://www.anquanke.com/post/id/183451
  [39]: https://www.jianshu.com/p/e41aa1428df3
  [40]: https://github.com/reevesrs24/CVE/blob/master/D-Link_DIR-615/xss_UPnP/dlink_dir615_xss_upnp.md
  [41]: https://www.freebuf.com/news/193340.html
  [42]: https://paper.seebug.org/795/
  [43]: https://www.freebuf.com/articles/terminal/207584.html
  [44]: https://www.anquanke.com/post/id/185336
  [45]: https://www.anquanke.com/post/id/178795
  [46]: https://nosec.org/home/detail/2760.html
  [47]: https://bbs.pediy.com/thread-247140.htm
  [48]: https://www.freebuf.com/articles/system/114741.html
  [49]: https://zhuanlan.zhihu.com/future-sec
  [50]: http://www.polaris-lab.com/index.php/archives/48/
  [51]: https://book.yunzhan365.com/tkgd/lzkp/mobile/index.html
  [52]: https://xz.aliyun.com/t/2278
  [53]: https://cq674350529.github.io/2019/03/18/D-Link-DIR-850L%E8%B7%AF%E7%94%B1%E5%99%A8%E5%88%86%E6%9E%90%E4%B9%8B%E8%8E%B7%E5%8F%96%E8%AE%BE%E5%A4%87shell/
  [54]: https://www.anquanke.com/post/id/95055
  [55]: https://bbs.pediy.com/thread-230095.htm
  [56]: https://mp.weixin.qq.com/s?__biz=MzI0MDY1MDU4MQ==&mid=2247493390&idx=2&sn=94582aa41410f53b608ec803c1fb8203&chksm=e9153734de62be22558307ba47f949345c2ed9dd445d215d9786f45e556394f151b8558f3cf1&scene=21#wechat_redirect
  [57]: https://www.chainnews.com/articles/550133689280.htm
  [58]: https://github.com/zcutlip/bowcaster
  [59]: http://www.devttys0.com/blog/
  [60]: http://www.giantbranch.cn
  [61]: http://galaxylab.com.cn
  [62]: https://cq674350529.github.io/categories/IoT/
  [63]: http://www.cnblogs.com/hac425/
  [64]: https://sec-wiki.com/news/search?wd=%E8%B7%AF%E7%94%B1%E5%99%A8
  [65]: https://ray-cp.github.io/
  [66]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8E-unicorn-%E7%9A%84%E5%8D%95%E4%B8%AA%E5%87%BD%E6%95%B0%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8C%E5%92%8C-fuzzer-%E5%AE%9E%E7%8E%B0/
  [67]: http://galaxylab.com.cn/%E5%9F%BA%E4%BA%8Eunicorn%E5%92%8Clibfuzzer%E7%9A%84%E6%A8%A1%E6%8B%9F%E6%89%A7%E8%A1%8Cfuzzing/
  [68]: http://galaxylab.com.cn/afl%E4%BD%BF%E7%94%A8101/
  [69]: https://medium.com/hackernoon/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf
  [70]: https://www.cnblogs.com/WangAoBo/p/8280352.html
  [71]: https://xz.aliyun.com/t/5155
  [72]: https://www.jianshu.com/p/77293121030e
  [73]: https://books.google.com.hk/books?id=6mOIToQVmO8C&pg=PA12&lpg=PA12&dq=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&source=bl&ots=uW-tX2dsbb&sig=ACfU3U0Tc8aNc0riddaXeiE3JcPjb3kLDA&hl=zh-CN&sa=X&redir_esc=y#v=onepage&q=vxworks%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F&f=false
  [74]: https://mp.weixin.qq.com/s/utcyVK41-iIzQUPeT5Zq9g6%E7%B3%BB%E7%BB%9F&f=false
  [75]: http://www.totolink.cn/index.php/Download/list/121.html
  [76]: https://service.fastcom.com.cn/download-list.html#0
  [77]: https://service.fastcom.com.cn/download-list.html#0
