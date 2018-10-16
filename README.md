# 简介

{% hint style="warning" %}
该文档正在建设中，请勿参考！
{% endhint %}

## ![](https://img.alicdn.com/tfs/TB1e1U7vyAnBKNjSZFvXXaTKXXa-973-200.png)

AliOS Things 发布于2017年杭州云栖大会， 是 AliOS 家族旗下的、面向 IoT 领域的、高可伸缩的物联网操作系统。

GitHub 仓库地址：[https://github.com/alibaba/AliOS-Things](https://github.com/alibaba/AliOS-Things)

## 愿景

AliOS Things 致力于搭建云端一体化 IoT 基础设施，具备极致性能、极简开发、云端一体、丰富组件、安全防护等关键能力。AliOS Things 支持多种多样的设备连接到阿里云 Link，可广泛应用在智能家居、智慧城市、工业，新出行等领域。

## 特性

**极简开发**

* 基于Linux之上的轻量虚拟化环境，开发者直接在 Linux 平台上开发硬件无关的 IoT 应用和软件库，使用GDB/Valgrind/SystemTap 等 PC 平台工具诊断开发问题
* 提供 IDE，支持系统/内核行为 Trace, Mesh 组网图形化显示
* 提供 Shell 交互，支持内存踩踏、泄露、最大栈深度等各类侦测
* 提供面向组件的编译系统以及 aos-cube 工具，支持灵活组合 IoT 产品软件栈
* 提供包括存储\(掉电保护、负载均衡\)在内的各类产品级别的组件

**即插即用的连接和丰富服务**

* 支持 uMesh 即插即用网络技术，设备上电自动连网
* 通过 Alink 与阿里云计算 IoT 服务无缝连接

**细颗粒度的FOTA更新**

* 支持应用代码独立编译映像，IoT app 独立极小映像升级
* 支持映像高度压缩

**彻底全面的安全保护**

* 提供系统和芯片级别安全保护
* 支持可信运行环境\(支持 ARMV8-M Trust Zone\)
* 支持预置 ID2 根身份证和非对称密钥以及基于 ID2 的可信连接和服务

**高度优化的性能**

* 内核支持 Idle Task 成本，Ram &lt; 1K, Rom &lt; 2k，提供硬实时能力
* 提供 Yloop 事件框架以及基于此整合的核心组件，避免栈空间消耗，核心架构良好支持极小 footprint的设备

