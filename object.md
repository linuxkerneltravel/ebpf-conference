# ebpfConference

#### 介绍
首届中国eBPF大会项目征集。

#### 项目题目


#### 简要描述
对项目给予简要描述，包括但不限于以下内容：

- 背景是什么
- 解决了什么问题
- 特色是什么
- 效果是什么样子的

你也可以敞开你的思维，进行更有趣的描述，如果你能制作2-3分钟的视频预告片，将会震撼人心。



#### 作者简介
XXXX




*************************************************
## 已登记演讲题目/项目

#### Pixie:开源云原生应用可观测平台
#### 简要描述
 Pixie 是 Kubernetes 应用程序的开源可观察性工具。使用 Pixie 查看集群的高级状态（服务地图、集群资源、应用程序流量），还可以深入查看更详细的视图（pod 状态、火焰图、单个全身应用程序请求）。

官网：https://pixielabs.ai/


#### 作者简介
 赵亚雄，2019年4月加入PixieLabs，作为Founding Engineer负责产品研发。曾在Google Borg、Network Infrastructure团队担任Tech Lead (TL)、Tech Lead Manager (TLM)，也是Amazon Kinesis创始团队成员。


*************************************************
####  eBPF小工具开发-精准计算CPU利用率
#### 简要描述
 内核的CPUIdle状态的选择初衷是为了节约能耗，但不恰当的选择却有可能造成功耗的浪费，使用eBPF可以对CPUIdle的状态选择算法做出一个合理的衡量标准，适用于其算法优化。
CPU频率的变化总是受到CPU利用率的影响，使用eBPF可以将kprobe与perf进行有效的结合，轻易得到CPU在不同频率下的CPU利用率以及受CPU利用率影响的频率变换信息。


详细内容参考公众号文章：https://mp.weixin.qq.com/s/df3GHVR9oq8AUl2qL-rNlA

#### 作者简介
张玉哲，陈莉君老师研究生团队研二学生。

*************************************************
####  eBPF小工具开发-打印内核栈调用关系
#### 简要描述
eBPF提供了STACK_TRACE类型的Map，可以轻易打印出内核中的函数调用关系，对于内核学习以及debug异常有很大的意义。

详细内容参考公众号文章最后一部分：https://mp.weixin.qq.com/s/df3GHVR9oq8AUl2qL-rNlA

#### 作者简介
张玉哲，陈莉君老师研究生团队研二学生。


*************************************************
#### surftrace工具简介  
#### 简要描述
 surftrace是在ftrace和libbpf基础上封装的一系列工具集，用于trace内核信息，当前发行版主要包含 surftrace、surfGuide、pylcc三大个工具。
链接： https://github.com/aliyun/surftrace
#### 作者简介
阿里巴巴 OSS团队 

*************************************************
#### embedshim简介  
#### 简要描述
 Embedshim provide task runtime implementation with pidfd and eBPF sched_process_exit tracepoint to manage deamonless container with low overhead.
链接：https://github.com/fuweid/embedshim
#### 作者简介
傅伟, 华为云容器技术专家，CNCF containerD 项目核心 Committer


*************************************************
#### DatenLord简介  
#### 简要描述
 DatenLord, Computing Defined Storage, an application-orientated, cloud-native distributed storage system.
链接: https://github.com/datenlord/datenlord

#### 作者简介
DatenLord团队


*************************************************
####  eCapture：无需CA证书抓https网络明文通讯
#### 简要描述
eCapture是一款基于eBPF技术实现的用户态数据捕获工具。不需要CA证书，即可捕获https/tls的通讯明文。
  
链接:  https://github.com/ehids/ecapture

#### 作者简介
CFC4N, 美团

 