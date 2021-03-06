# 求职意向
### iOS开发工程师

# 基本信息

姓名：王超(chaors) 　　　  出生日期：1992-04  


工作年限：4年　　　　　　毕业院校：潍坊学院(统招本科）　

手机：13001992410　　 　 邮箱：chaors_w@yeah.net  

期望月薪：**>=16k** 　　 　 　到岗时间：随时(离职状态)

# 专业技能
- 熟练掌握Objective-C，熟悉C，了解Python、Go等编程语言；

- 了解主流常见的算法思想和数据结构

- 熟练使用各种OC框架和主流第三方库，熟练使用Xcode等相关开发工具

- 熟悉SDK开发流程，熟练主要的设计模式如MVC，单例等；

- 理解内存管理和优化，MRC/ARC相关原理

- 熟悉性能优化，Crash定位，无痕埋点原理等相关技术；

- 了解RevealUI，clang，Charles等常用工具使用

-	熟练蓝牙(BLE4.0)相关开发，有端到设备复杂蓝牙通讯/数据解析相关经验，智能硬件SDK开发

- 了解相关iOS底层技术实现原理，如RunTime/RunLoop，KVC，Category等

- 熟悉几种主要多线程开发方式，JSON/XML数据相关解析

- 了解网络相关基础(http/https)

- 熟练使用git进行代码管理；熟悉常用的加密技术，如Hash，AES，DSA，ECC等

-	熟练使用Edraw等工具对程序整体实现进行流程细化，从而把控全局掌握整体架构

- 大学英语CET-6水平，可以查阅相关英文技术文档(目前还在不断提高英语水平)
- 较强的学习能力，适应能力和总结能力；[技术博客]( https://www.jianshu.com/u/a46bd6ade353)
-	区块链技术爱好者，区块链相关原理也稍有涉猎:[相关git](https://github.com/chaors)


# 项目经历
### 项目1：AIEcgSDK(iOS端心电采集SDK）					2017.1—2018.10
主要为第三方公司提供的与我司动态心电记录仪相匹配的软件开发包，主要提供同步采集数据，12导心电波形绘制，实时心率，波形质量预判，及时生成心电图报告，心电文件上传后台等核心功能。

#### 项目职责：
框架设计，流程分析
从零到一的技术实现
为第三方提供技术支持
实时绘图效率提升

#### 主要技术：
framework静态库/SDK接口设计/UIKit/BLE4.0/AFNet二次封装/drawRect屏幕刷新/UIGraphics绘图/zip压缩/心率算法/Block/KVO/NSNotification/本地数据缓存(LRU)/服务器通讯/多线程控制传输流程/字节运算处理/流程分析(核心流程图)

## 项目2：iOS端心电回放和诊断组件(供App端直接调用) 		2017.2—2018.10
对用户端采集上传的心电文件，可以在医生端打开查看。需要适配符合心电图医学标准的各个电压定标/走纸速度组合，可以全屏显示并放大单个导联心电图，同时计算平均心率和各个心电技术指标，实现两个心电文件的同屏波形对比，手机端选择打印区域可以生成对应区域心电图等。
### 项目职责：
框架设计，技术难点攻克
全程独立开发
对app端进行技术支持
波形绘制效率提升
### 主要技术：
心电文件数据解析/心电滤波算法/UIBezierPath绘图/ScrollView联动/改进的Douglas抽吸算法/分片绘图机制/NSNotification/KVO/电压高度自适应算法/数据缓冲

## 项目3：CHBLEHelper(通用的蓝牙通讯类) 						2016.9—2018.10
为公司使用的所有蓝牙设备提供统一的蓝牙通讯类，除了一般的蓝牙通讯功能外，还要集成各个医疗设备的数据解析。输入不同的设备，最后得到的是已经解析好的设备数据供app端展示。可以解析的设备有：12导动态心电仪/血压计/血氧/心率带/血脂仪。
### 项目职责：
学习BLE4.0相关知识，全程独力开发
与硬件部门联调，并协助硬件组制定相关通讯协议
对app端进行技术支持
数据传输速率与稳定性测试/数据丢包率与长连接意外测试
协议通讯指令测试(主要针对12导动态心电仪)
### 主要技术：
BLE4.0/CoreBluetooth封装/Block/KVO/NSNotificatio/数据双缓冲技术/多线程数据解析/通讯协议规范/字节转化(位处理)/蓝牙设备绑定/接口设计/蓝牙长连接

## 项目4：康乃心(客户端App/辅助开发)							2017.10—2018.10
康乃心是一款专注心脏PCI术后康复和监测的健康服务平台，主要对用户心电图做监测，同时包括血压、血氧等其他参数监测；健康训练指导，用药提醒，图文/电话/视频咨询，随访等，旨在实现对用户健康全方位的服务。
### 项目职责：
版本需求分析，相关技术选型
辅助客户端开发者完成部分功能性代码
APP性能分析
### 主要技术：
UITableview/Cell自定制/App启动优化/App Crash定位(dSYM,UMeng第三方辅助)/数据解析优化(二级缓存LRU算法)/YYWebImage/性能优化(Instruments,hook技术)/App瘦身

## 项目5：掌上云医院(开发)/瘦瘦，孕育加(维护)					 2016.3—2016.9
云医院是一款可以提供健康咨询，健康档案，查找医生，网上预约等健康服务的App；
瘦瘦是一款为用户量身定制提供个性化瘦身方案的App;
孕育加是一款提供关于孕期，孕后，宝妈综合咨询平台的一款App。
### 项目职责：
需求分析，文档规范
应用功能开发
接手云医院V1.5版本后开发
瘦瘦维护Debug
孕育加0.5版本开发。
### 主要技术：
ZBarSDK/SDWebImage/自定制TabBar和TableViewCell，NavigationVc/富文本/EaseMobSDK/ShareSDK/AutoLayout/UIKit

## 项目6：基于AES&RSA的混合加密工具(外包私活)	  2016.7—2016.8
基于AES和RSA的混合加密工具，用于对某项目中的通讯模块进行接口和数据加密.
### 项目职责：
调研加密技术，适合的技术选型，对加密类底层进行封装，对外实现加密接口调用。
### 主要技术：
AES/RSA/接口封装/混合加密/API设计

## 项目7：基于ijkPlayer的简易直播App(个人Demo)
这是一款免费播放直播视频的App，并实现了手机端直播功能
### 项目职责：
全部功能的实现和Mac端rtmp服务器的搭建
LFLiveKit实现数据采集端的视频录制
ffmpeg实现视频推流
GPUImage实现直播中的美颜和特效
### 主要技术：
 rtmp服务器nigx/ijkPlayer集成/ffmpeg推流/GPUImage/LFLiveKit/UIKit
 
# 非iOS项目
## 项目1：[TTC公链](https://github.com/TTCECO/gttc)				 　 　 2018.11-2019.1
TTC公链致力于通过TTC平台构建基于去中心化和代币激励的社交化网络解决方案，旨在解决现有区块链方案的问题，特别是在处理大规模交易和海量数据的场景。
### 项目职责：
公链共识层需求分析、讨论；相关旧有代码，技术文档维护
Alien共识机制相关测试(signerQueue，snapShot，出块规则，主侧链运行及相关奖励分配)
持续跟进区块链技术在相关方向的技术进展，调研最新技术
### 主要技术：
Go语言/Dpos+PBFT共识/Ethereum其他模块/侧链机制/Dapp奖励机制

## 项目2：[基于Go 的区块链公链实现	](https://github.com/chaors)		 　 　 2018.6-2018.10
该简单公链参照 Bitcoin 模型，基本具备区块链全功能，主要有 BlockChain 模块，CLi 模块，BoltDB 模块，POW 模块，Tx 交易模块，UTXO 模块，Wallet 钱包模块，Server 网络同步模块，otto 模块等。虽还为想到具体的应用点，但麻雀虽小五脏俱全，已经可以作为一个公链项目的雏形。
### 项目职责：
全程独立开发
边学习边逐个添加模块功能
### 主要技术：
Hash算法/椭圆曲线加密算法/BoltDB 数据库/RSA 签名算法/P2P/otto 虚拟机

## 项目3：工业控制显示屏程序开发			 　 　 2015.3-2015.10
主要为工业控制(起重机，路桥装载机)显示屏做GUI开发，还有坦克相关控制屏程序维护。

### 项目职责：
Qt嵌入式显示屏程序开发
功能实现与基本测试，后期维护
机油，温度等重要参数监控与预警
为相关合作方(如包头一机)提供技术支持
### 主要技术：
Qt/C++/Linux/CanBus总线通信

## 项目4：基于GPS的农耕自动计亩算法	 　 　 2015.9-2016.3
主要用于农业旋耕机耕地时的作业地块的面积计算，在农机作业的过程中配套的GPS记录点位，作业完毕后按照一定的算法计算出地块面积。
### 项目职责：
嵌入式设备计亩算法初版
模拟农机作业测试并计算误差
不断改进和优化算法
协助PC端做算法移植的实现
### 主要技术：
Linux C/GPS定位点/多边形面积计算/相关算法

# 工作经历

### [北京朗势科技有限公司](https://www.ttc.eco/#/)　　　  　2018.10 – 2019.1
#### TTC项目组 | 区块链研发工程师 
1.公链共识层需求分析、讨论；相关旧有代码，技术文档维护

2.Alien共识机制相关测试(signerQueue，snapShot，出块规则，主侧链运行及相关奖励分配)

3.持续跟进区块链技术在相关方向的技术进展，调研最新技术

### [心韵恒安医疗科技有限公司](https://www.cardiocloud.cn/)　　　       2016.9 – 2018.10
#### 软件事业部  |  心电SDK开发组长
1.与硬件设备蓝牙通讯的接口设计，提供高复用的蓝牙接口包；制定和规范SDK接口

2.心电数据的解析和存储，12导心电数据实时采集，回放；心率的实时计算，心率散点图的绘制

3.心电图滤波处理，波形平滑处理；心电图基本诊断；指导后台与前端的相关心电业务

4.血压数据的采集，显示，以及语音播报；自动与标准血压库对比，生成心电诊断；血氧采集

5.心电、血压设备蓝牙模块的调试；心电采集与心电诊断SDK的设计和开发

### 东软熙康健康有限公司	　　　   　  			 	                           2016.3 – 2016.9
#### 软件研发部  |  iOS开发工程师(APP)   
1.掌上云医院APP版本迭代,维护;新增功能的研发; APP到AppStore的打包发布工作

2.UI整体布局;IM相关模块迭代和维护;需求讨论和线上Bug的解决

### [北京博创联动科技有限公司](http://www.uml-tech.com/)				                            　　　  2015.4 – 2016.3
#### 应用系统部  |  Qt开发工程师
1，嵌入式设备应用层开发，工程机械显示屏程序编写，显示屏程序安装维护与升级。主要用于工业控制，军用设备，工程机械领域的智能控制；

2.CANBUS总线通信，用于车联网的重要数据监控与预警

3.基于GPS的计亩算法研究，主要用于农业设备对作业地块的面积计算。平地计亩误差基本控制在7.5%左右，因此先后两次获得公司项目奖金共5000元 

### [中国软件ETC事业部(实习)](http://www.cssweb.com.cn)				                            　　　  2014.10 – 2015.3
#### 后台组  |  Unix C 研发
1.实习＋工作

2.日志分析工具的编写，辅助终端设备组排查故障

3.vb编写结构化代码自动生成工具，根据Excel数据生成大量项目必须的结构体

4.AFC后台服务器部分功能维护，升级；数据库sql脚本的编写

# 教育背景
#####	中软国际北京ETC	   嵌入式工程师(Linux C)	     培训	             2014.6 – 2014.10

#####	潍坊学院	 　　　   计算机科学与技术		    　　 本科	     2011.9 – 2015.6


 
