# MyPresentation
This repository is used to store PowerPoint for public presentations.

## VulDeePecker: A Deep Learning-Based System for Vulnerability Detection
NDSS-2018 中华中科技大学提出的基于深度学习的漏洞挖掘系统 VulDeePecker
 
 - 使用 Code Gadget 表示应用程序应用于深度学习领域中
 - 使用 BLSTM 作为深度学习使用的神经网络
 - 使用 Theano 和 Keras 为工具框架
 - 整理 NVD 和 SARD 形成并开源应用于深度学习的应用程序数据集 

## Chainsaw: Chained Automated Workflow-based Exploit Generation
CCS-2016 针对基于 PHP 的 Web 应用程序源代码生成一系列可成功利用的攻击向量的集合

 - 源码分析使用 Pixy 与 TAPS
 - 规划求解来自 Z3 SMT 和 Z3-Str

## Understanding Linux Malware
 S&P-2018 思科针对 Linux 平台上恶意软件大规模测量的研究

 - 使用 IDA Pro 提取代码度量
 - 使用 systemtap 实现内核探针
 - 使用 KVM 和 QEMU 实现多体系架构沙盒
 - 使用 AVClass 对 VT 报告进行分类
 - 使用 Unicorn 实现脱壳

## A Lustrum of malware network communication: Evolution and insights
S&P-2017 五年时间收集了 2680 万样本的网络通信数据

 - 和美国一家大型 ISP 合作收集 50 亿条 Passive DNS 记录
 - 使用两个商业加一个学术恶意软件数据集
 - 使用 DGArchive 识别恶意软件家族

## TLS in the wild: An Internet-wide analysis of TLS-based protocols for electronic communication
NDSS-2016 构建了一个用于监测网络钓鱼工具包的沙盒，可以观测受害者与钓鱼工具包的交互方式

## PhishEye: Live Monitoring of Sandboxed Phishing Kits
CSS-2016 分析了互联网范围内基于 TLS 的通信协议安全情况

 - 使用 zmap 进行主动扫描，Bro 进行被动监控
 - 除大型邮件服务提供商外的邮件服务大多不安全
