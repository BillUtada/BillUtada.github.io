---
title: "简历"
permalink: /aboutcn/
---

---
# 个人信息

 - 赵威 (William Zhao) / 男 
 - 南京邮电大学软件工程 大三在读 

---
# 工作经历

## Nvidia
### Graphic Tools Dev

## Red Hat
### Quality Engineer
参与Redhat旗舰产品Red Hat Enterprise Linux (RHEL)的测试开发工作，负责订阅(Entitlement)功能的测试框架开发与维护，涉及产品有开源项目virt-who与Red Hat Subscription Manager (RHSM)。框架底层使用paramiko实现虚拟化测试。同时也参与了两个产品具体的测试用例(testcase)开发与整理发送自动化测试报告。

该测试框架最大的难点有两个
 1. 测试环境异常多变复杂，用户的hypervisor产品有近10种选择，并且部署平台不统一
 2. 每天都会有上千条用户报的千奇百怪的user case，要及时发现其中有效的，并实现为testcase

对于第一点，我们通过paramiko完成与unix-like的通信，对于windows平台通过socket，手动开启监听端口从而实现linux与windows的交互。对于多种hypervisor产品，我们在jenkins里进行了分类处理，通过docker同时运行多个job实现虚拟化测试，快速得到测试结果，这也是最令我满意的实现细节。
对于第二点，我使用正则模块编写了过滤器，能有效准确发现有效case，进而交给维护testcase的同事们处理，这样工作负担就少了很多。

初次接触大公司的测试流程与测试细节，得到了方方面面的收获。得益于对python与linux的深刻理解，我迅速学习新的相关知识，初到公司一周便上手了测试框架的开发和维护工作，作为实习生，至今更是成为了该框架的主要维护者。

## 完美世界 (Mobile Game UI Programmer) 
负责手游UI部分，在Unity中实现基于NGUI的栈结构UI框架、实现部分gameplay框架与游戏脚本。
作为一名热爱游戏者，带着对游戏的热情让我不断努力与进步。这个项目工作两个月时，策划突然要大改UI，前面一段时间的工作基本全部要重新来过。我尽最大努力，复用了很多代码，让工作量从计划的减少至少一半。
这是我的第一份工作，我投入了很多热情和经历，但也让我认识到品质一般的游戏和无止尽的加班绝不是中国游戏的未来。

---
# Skills
- Linux，丰富的Linux经验
- 深刻理解Python，nose，unittest模块，丰富的testcase开发经验
- 理解Shell与Shell (bash)编程
- 理解软件测试，虚拟化测试，自动化测试流程，有发送测试报告经验
- 熟悉Jenkins等常用自动化CI测试平台，熟悉JJB等工具
- 具有开发自动化测试框架的能力
- 精通git，精通gerrit等代码审查工具，熟悉svn
- 熟悉github page的web jekyll框架
- 流畅阅读英文技术文档，熟悉英文工作环境，托福96
- 理解常用算法与数据结构
- 熟悉C/C++
- 了解图形学基本渲染算法
- 了解Mysql / C# / Java / html / css
- 熟悉Openstack环境，熟悉微信公众号等开放平台

---
# 竞赛/会议经历
- MCM/ICM美国大学生数学建模竞赛一等奖 (M奖)
- ACM国际大学生程序设计竞赛上海区域赛铜奖
- Siggraph Asia 2016 (澳门) 学生志愿者
- Siggraph Asia 2017 (曼谷) 学生志愿者
- 蓝桥杯全国软件和信息技术专业人才大赛C/C++组全国二等奖
- 蓝桥杯全国软件和信息技术专业人才大赛C/C++组江苏省一等奖
- 南京邮电大学ACM程序设计竞赛一等奖 (第二名)
- 甲骨文杯全国Java程序设计大赛华东赛区三等奖

---
# Open Source

## 项目
- [virt-who](https://github.com/candlepin/virt-who): 检测并报告hypervisor状态的工具
 - [leetcode-python-solution](https://github.com/BillUtada/leetcode-python-solution): leetcode的python题解
 - 基于QT和微信，在Windows桌面实现类似B站弹幕效果 (支持高并发)
 - 使用Unity复刻游戏: *Pretentious Game*

## 技术文章
- [绘制直线的光栅化算法](https://zhuanlan.zhihu.com/p/20213658)
- [浅谈 C++ 中的 const 和 constexpr](https://zhuanlan.zhihu.com/p/20206577)

---
# 联系方式
- 赵威 (William Zhao)
  - william.zhao.programmer@gmail.com
  - 17625909218

