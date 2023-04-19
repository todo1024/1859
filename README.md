# 1859
马士兵-kubernetes实战与源码剖析 | 完结
### 微:NoBug1024 


课程介绍：

说明

第1部分 目的是看k8s组件架构并解析相关源码，目前已完成80小节文档内容
第2部分 容器底层原理，这里需要会加一些docker源码解读， 小节还未编写
第3部分 k8s 重点资源源码解读，主要是核心资源的控制器源码解读， 小节还未编写
第4部分 k8s 存储对象源码解读， 小节还未编写
第5部分 k8s 网络底层原理， 小节还未编写
第6部分 深入掌握k8s Service， 小节还未编写
第7部分 k8s 编排管理， 小节还未编写
第8部分 容器安全， 小节还未编写
第9部分 K8s crd开发项目， 具体功能还没定好，但是crd开发应该是主流，小节还未编写
观察市面上k8s 开发主要分两类
1是 调k8s接口做 页面化操作，谓之弹性云平台(后端技术要求不高，前端我不会)
2是 开发crd(能够对k8s后端代码有较多的应用)，我这里选这个
〖课程目录〗:


- ├──章节1-第1章 准备工作  
- |   ├──课时1-k8s的介绍与核心对象概念-1660019847.mp4  62.75M
- |   ├──课时2-使用kubeadm 10分钟部署k8集群-1660019860.mp4  77.65M
- |   ├──课时3-k8s-上部署第一个应用程序-1660019877.mp4  76.24M
- |   ├──课时4-给应用添加service，执行扩容和滚动更新-1660019890.mp4  58.60M
- |   ├──课时5-安装Kuboard在页面上熟悉k8s集群-1660019911.mp4  173.41M
- |   └──课时6-阅读k8s源码的准备工作-1660019918.mp4  22.86M
- ├──章节10-第10章  kubelet中的cgroupManager解读  
- |   ├──课时1-10.1 cgroup-v1原理介绍和golang代码体验cgroup的cpu和memory限制-1660020416.mp4  84.69M
- |   ├──课时2-10.2 cgroup-v2原理介绍-1660020422.mp4  16.17M
- |   ├──课时3-10.3 kubelet 中的cgroupManager解析和节点qos顶级目录创建-1660020432.mp4  109.98M
- |   └──课时4-10.4 containerManager应用之创建容器cgroup目录-1660020442.mp4  106.35M
- ├──章节11-第11章  kubelet中的资源管理器cpuManager、memoryManager、deviceManager解读  
- |   ├──课时1-11.1 TopologyManager分析-1660020452.mp4  60.97M
- |   ├──课时2-11.2 TopologyManager源码解读-1660020468.mp4  205.03M
- |   ├──课时3-11.3 写goland代码体会cpuset原理-1660020479.mp4  58.51M
- |   ├──课时4-11.4 kubelet中的cpuManager解读-1660020499.mp4  157.31M
- |   ├──课时5-11.5 memoryManager原理简介-1660020507.mp4  24.09M
- |   ├──课时6-11.6 memoryManager源码阅读-1660020520.mp4  123.90M
- |   ├──课时7-11.7 device-plugins设备插件机制介绍-1660020528.mp4  24.99M
- |   └──课时8-11.8 deviceManager源码解读-1660020542.mp4  127.14M
- ├──章节12-第12章 kubelet pleg对象和containerManager总结  
- |   ├──课时1-12.1 kubelet pleg对象介绍和源码解读-1660020561.mp4  141.03M
- |   └──课时2-12.2 kubelet containerManager源码解读-1660020580.mp4  147.99M
- ├──章节13-第13章 kubelet containerRuntime和sandbox容器  
- |   ├──课时1-13.1 containerRuntime 原理简介-1660020591.mp4  42.87M
- |   ├──课时2-13.2 kubelet containerRuntime接口定义和初始化-1660020601.mp4  75.30M
- |   ├──课时3-13.3 sandbox简介和podsandbox-1660020608.mp4  18.41M
- |   └──课时4-13.4 containerRuntime创建sandbox源码阅读-1660020620.mp4  100.57M
- ├──章节14-第14章 containerRuntime创建init容器前期工作  
- |   ├──课时1-14.1 实操说明init容器的作用-1660020634.mp4  55.46M
- |   ├──课时2-14.2 创建init容器步骤1拉取镜像源码解读-1660020649.mp4  127.67M
- |   └──课时3-14.3 创建init容器步骤2create的准备工作源码解读-1660020664.mp4  129.15M
- ├──章节15-第15章 创建init和app容器的后期工作  
- |   ├──课时1-15.1 创建init容器步骤2剩余工作源码解读-1660020673.mp4  36.53M
- |   └──课时2-15.2 创建init容器步骤3 4启动容器源码解读-1660020683.mp4  72.91M
- ├──章节16-第16章 containerRuntime停止容器的流程  
- |   ├──课时1-16.1 killContainer源码解读-1660020693.mp4  52.86M
- |   └──课时2-16.2 killContainer的调用方解析-1660020702.mp4  69.55M
- ├──章节17-第17章 kubelet的GarbageCollection  
- |   ├──课时1-17.1 GarbageCollection之镜像清理源码解读-1660020714.mp4  64.63M
- |   └──课时2-17.2 GarbageCollection之容器清理源码解读-1660020725.mp4  67.36M
- ├──章节18-第18章 kubelet的syncLoop的第1大监听configCh  
- |   ├──课时1-18.1 syncLoop的configCh中的apiserver通信的流程-1660020740.mp4  102.01M
- |   ├──课时2-18.2 syncLoop的configCh中的file源码-1660020752.mp4  75.25M
- |   ├──课时3-18.3 syncLoop的configCh中的http源码-1660020759.mp4  26.15M
- |   └──课时4-18.4 syncLoop的configCh中的merge逻辑-1660020767.mp4  50.57M
- ├──章节19-第19章 kubelet的syncLoop的其余监听  
- |   ├──课时1-19.1 syncLoop的housekeepingCh流程-1660020780.mp4  98.01M
- |   ├──课时2-19.2 syncLoop的syncCh流程-1660020790.mp4  68.75M
- |   └──课时3-19.3 syncLoop监听的health-manager-1660020798.mp4  39.75M
- ├──章节2-第2章 创建pod时kubectl的执行流程和它的设计模式  
- |   ├──课时1-2.1 使用kubectl部署一个简单的nginx-pod-1660019925.mp4  14.60M
- |   ├──课时2-2.2 命令行解析工具cobra的使用-1660019938.mp4  122.80M
- |   ├──课时3-2.3 kubectl命令行设置pprof抓取火焰图-1660019946.mp4  69.63M
- |   ├──课时4-2.4 kubectl命令行设置7大命令分组-1660019954.mp4  64.99M
- |   ├──课时5-2.5 create命令执行流程-1660019962.mp4  81.22M
- |   ├──课时6-2.6 createCmd中的builder建造者设计模式-1660019968.mp4  44.26M
- |   ├──课时7-2.7 createCmd中的visitor访问者设计模式-1660019980.mp4  158.67M
- |   └──课时8-2.8 kubectl功能和对象总结-1660019986.mp4  17.41M
- ├──章节20-第20章 kubelet中内置的cadvisor  
- |   └──课时1-20.1 kubelet中内置的cadvisor-1660020824.mp4  257.07M
- ├──章节21-第21章 kubelet中内置的dockershim机制  
- |   ├──课时1-21.1 容器和namespace-1660020836.mp4  44.86M
- |   ├──课时2-21.2 容器和cgroups-1660020842.mp4  12.06M
- |   ├──课时3-21.3 容器运行时的乱战-1660020851.mp4  39.62M
- |   ├──课时4-21.4 k8s的cri接口和dockershim的去留-1660020861.mp4  39.62M
- |   └──课时5-21.5 kubelet中dockershim源码解读-1660020878.mp4  165.78M
- ├──章节22-第22章 容器底层技术之镜像原理  
- |   ├──课时1-22.1 以nginx镜像为例看OCI中的镜像规范-1660020897.mp4  132.29M
- |   └──课时2-22.2 联合文件系统简介-1660020917.mp4  136.86M
- ├──章节23-第23章 k8s job和cronjob源码解读  
- |   ├──课时1-23.1 job的基本功能-1660020928.mp4  39.40M
- |   ├──课时2-23.2 job controller源码解析之初始化工作-1660020942.mp4  106.11M
- |   ├──课时3-23.3 job controller源码解析之syncJob工作-1660020958.mp4  119.45M
- |   ├──课时4-23.4 job controller源码解析之manageJob工作-1660020972.mp4  115.29M
- |   ├──课时5-23.5 cronjob-controller同步主流程源码解析-1660020983.mp4  79.13M
- |   └──课时6-23.6 cronjob-controller同步核心syncCronJob源码解析-1660020994.mp4  63.95M
- ├──章节24-第24章 k8s deployment源码解读  
- |   ├──课时1-24.1 deployment的基本功能-1660021011.mp4  89.33M
- |   ├──课时2-24.2 deployment源码解析之初始化工作-1660021022.mp4  70.53M
- |   ├──课时3-24.3 deployment-controller源码解析之syncDeployment的准备工作-1660021032.mp4  52.65M
- |   ├──课时4-24.4 deployment-controller源码解析之删除暂停回滚-1660021047.mp4  101.91M
- |   ├──课时5-24.5 deployment-controller源码解析之扩缩容-1660021057.mp4  50.52M
- |   ├──课时6-24.6 deployment-controller源码解析之滚动更新-1660021069.mp4  75.76M
- |   └──课时7-24.7 deployment-controller源码解析之暴力新建-1660021077.mp4  47.60M
- ├──章节25-第25章 k8s ReplicaSetController源码分析  
- |   ├──课时1-25.1 ReplicaSetController源码解析之初始化工作-1660021087.mp4  41.20M
- |   └──课时2-25.2 ReplicaSetController源码解析之syncReplicaSet-1660021103.mp4  80.51M
- ├──章节26-第26章 k8s daemonSet源码分析  
- |   ├──课时1-26.1 daemonSet的常见功能-1660021117.mp4  65.50M
- |   ├──课时2-26.2 DaemonSetController源码分析之初始化工作-1660021127.mp4  55.80M
- |   ├──课时3-26.3 DaemonSetController源码分析之状态同步-1660021140.mp4  93.73M
- |   ├──课时4-26.4 DaemonSetController源码分析之创建操作-1660021151.mp4  62.63M
- |   └──课时5-26.5 DaemonSetController源码分析之滚动更新-1660021162.mp4  77.21M
- ├──章节27-第27章 k8s statefulSet源码分析  
- |   ├──课时1-27.1 statefulSet的常见功能之动态pv准备-1660021180.mp4  125.34M
- |   ├──课时2-27.2 statefulSet的常见功能新增删除扩容-1660021189.mp4  63.48M
- |   ├──课时3-27.3 StatefulSetController源码分析之初始化工作-1660021196.mp4  30.48M
- |   └──课时4-27.4 StatefulSetController源码分析之sync同步-1660021204.mp4  96.13M
- ├──章节28-第28章 Service的定义和概念  
- |   ├──课时1-28.1 4种Service概念介绍-1660021215.mp4  53.13M
- |   ├──课时2-28.2 4种service的负载均衡模式-1660021222.mp4  21.05M
- |   └──课时3-28.3 2种service的服务发现模式-1660021233.mp4  87.48M
- ├──章节29-第29章 kube-proxy iptables和ipvs模式源码解读  
- |   ├──课时1-29.1 kube-proxy 启动流程之判断代理模式初始化proxier接口-1660021244.mp4  104.39M
- |   ├──课时2-29.2 kube-proxy 启动流程之proxier运行-1660021254.mp4  83.37M
- |   ├──课时3-29.3 kube-proxy 中iptables模式的规则分析-1660021265.mp4  86.61M
- |   ├──课时4-29.4 kube-proxy 中iptables模式的syncProxyRules解析-1660021276.mp4  144.32M
- |   └──课时5-29.5 kube-proxy 中ipvs模式的syncProxyRules解析-1660021283.mp4  44.66M
- ├──章节3-第3章 apiserver中的权限相关  
- |   ├──课时1-3.1 apiserver启动主流程分析-1660019995.mp4  82.97M
- |   ├──课时2-3.2 API核心服务通用配置genericConfig的准备工作-1660020004.mp4  106.18M
- |   ├──课时3-3.3 API核心服务的Authentication认证-1660020012.mp4  91.98M
- |   ├──课时4-3.4 API核心服务的Authorization鉴权-1660020020.mp4  79.30M
- |   ├──课时5-3.5 node类型的Authorization鉴权-1660020028.mp4  95.90M
- |   ├──课时6-3.6 rbac类型的Authorization鉴权-1660020038.mp4  99.55M
- |   ├──课时7-3.7 audit审计功能说明和源码解读-1660020048.mp4  96.66M
- |   └──课时8-3.8 admission准入控制器功能和源码解读-1660020059.mp4  137.77M
- ├──章节30-第30章 k8s 网络底层原理  
- |   ├──课时1-30.1 同pod容器和容器之间的通信-1660021291.mp4  38.46M
- |   ├──课时2-30.2 pod和pod之间调用是怎么做到通信的-1660021300.mp4  62.17M
- |   ├──课时3-30.3 Pod和Service之间的通信-1660021311.mp4  83.64M
- |   ├──课时4-30.4 k8s CNI简介和kubelet中cni源码调用-1660021322.mp4  96.67M
- |   └──课时5-30.5 k8s calico plugin源码解析-1660021336.mp4  184.40M
- ├──章节31-第31章 k8s Ingress 7层路由机制和traefik源码解读  
- |   ├──课时1-31.1  Ingress安装使用-1660021348.mp4  75.53M
- |   └──课时2-31.2  traefik 源码解读-1660021359.mp4  107.39M
- ├──章节32-第32章 k8s 存储对象源码解读  
- |   ├──课时1-32.1 k8s存储管理发展历程和volume简介-1660021368.mp4  50.60M
- |   ├──课时2-32.2 pv和pvc简介静态pv和动态pv示例-1660021379.mp4  90.90M
- |   ├──课时3-32.3 pv控制器源码解读之控制器初始化-1660021388.mp4  81.12M
- |   ├──课时4-32.4 pv控制器源码解读之控制器volumeWorker处理pv增删-1660021396.mp4  76.84M
- |   ├──课时5-32.5 pv控制器源码解读之reclaimVolume回收解析-1660021408.mp4  112.03M
- |   └──课时6-32.6 pv控制器源码解读之claimWorker处理pvc-1660021419.mp4  95.26M
- ├──章节33-第33章 k8s configMap和secret解析  
- |   ├──课时1-33.1 k8s configMap简介-1660021427.mp4  38.93M
- |   ├──课时2-33.2 k8s secret简介-1660021433.mp4  38.50M
- |   └──课时3-33.3 kubelet volume-manager挂载configMap secret源码解读-1660021441.mp4  79.44M
- ├──章节34-第34章 k8s hpa扩容和Aggregator汇聚插件原理解读  
- |   ├──课时1-34.1 k8s 基于CPU的hpa扩容简介-1660021453.mp4  80.90M
- |   ├──课时2-34.2 k8s 基于MEM的hpa扩容简介-1660021462.mp4  54.19M
- |   ├──课时3-34.3 k8s hpa控制器源码解读之3种监控指标client-1660021469.mp4  50.70M
- |   ├──课时4-34.4 k8s hpa控制器源码解读之调谐过程-1660021481.mp4  139.74M
- |   └──课时5-34.5 k8s apiserver的Aggregator汇聚插件-1660021493.mp4  123.85M
- ├──章节35-第35章 基于prometheus-adaptor 的自定义指标HPA  
- |   ├──课时1-35.1 部署prometheus-adapter-1660021503.mp4  75.82M
- |   ├──课时2-35.2 golang程序统计登录的qps-1660021511.mp4  60.13M
- |   └──课时3-35.3 k8s 基于prometheus-adapter 的自定义指标扩容-1660021521.mp4  78.85M
- ├──章节36-第36章 k8s vpa扩容  
- |   ├──课时1-36.1 安装vpa 控制器并使用-1660021547.mp4  330.88M
- |   ├──课时2-36.2 vertical-pod-autoscaler源码阅读之Recnmender-1660021563.mp4  160.06M
- |   ├──课时3-36.3 vertical-pod-autoscaler源码阅读之updater-1660021571.mp4  41.86M
- |   └──课时4-36.4 vertical-pod-autoscaler源码阅读之admission-controller-1660021578.mp4  53.89M
- ├──章节37-第37章 k8s hpa和vpa依赖的metrics-server源码解读和kubelet top原理  
- |   ├──课时1-37.1 metrics-server源码解读-1660021592.mp4  136.93M
- |   └──课时2-37.2 kubelet top原理-1660021602.mp4  75.67M
- ├──章节38-第38章 k8s crd 开发  
- |   ├──课时1-38.1 crd技术介绍和自定义crd需求分析-1660021610.mp4  30.85M
- |   ├──课时2-38.2 使用kubebuilder编写crd代码-1660021620.mp4  114.26M
- |   └──课时3-38.3 部署crd到k8s中使用-1660021632.mp4  126.05M
- ├──章节39-第39章 istio上手使用和sidecar流量劫持原理解析  
- |   ├──课时1-39.1 微服务和istio准备知识-1660021640.mp4  13.13M
- |   ├──课时2-39.2 istio安装部署-1660021657.mp4  204.51M
- |   ├──课时3-39.3 istio基于身份的请求路由、故障注入、流量转移功能-1660021666.mp4  65.78M
- |   ├──课时4-39.4 istio访问外部服务-1660021676.mp4  72.06M
- |   ├──课时5-39.5 istio中的Sidecar注入讲解-1660021684.mp4  71.88M
- |   └──课时6-39.6 istio中的Sidecar流量劫持解析-1660021694.mp4  99.02M
- ├──章节4-第4章 自定义准入控制器，完成nginx sidecar的注入  
- |   ├──课时1-4.1 自定义准入控制器需求分析-1660020065.mp4  21.88M
- |   ├──课时2-4.2 检查k8s集群准入配置和其他准备工作-1660020073.mp4  73.95M
- |   ├──课时3-4.3 注入sidecar的mutatePod注入函数编写-1660020085.mp4  157.38M
- |   └──课时4-4.4 打镜像部署并运行注入sidecar验证-1660020102.mp4  202.23M
- ├──章节40-第40章 envoy基础知识  
- |   ├──课时1-40.1 envoy基础知识-1660021726.mp4  105.79M
- |   ├──课时2-40.2 envoy代理https流量-1660021733.mp4  33.66M
- |   ├──课时3-40.3 envoy基于文件的动态EDS和CDS配置-1660021742.mp4  59.28M
- |   └──课时4-40.4 envoy基于 API 的动态端点发现-1660021750.mp4  77.94M
- ├──章节41-第41章 istio组件分析  
- |   ├──课时1-41.1 istio都有哪些组件，它们是干什么的-1660021758.mp4  39.38M
- |   ├──课时2-41.2 istio xds协议知识介绍-1660021764.mp4  16.93M
- |   ├──课时3-41.3 istio-ingressgateway和istio-proxy对应的pilot-agent分析-1660021775.mp4  147.26M
- |   └──课时4-41.4 istiod pod对应的 pilot-discovery分析41.4 istiod pod对应的 pilot-discovery分析-1660021784.mp4  92.13M
- ├──章节5-第5章 API核心服务的处理流程  
- |   ├──课时1-5.1 API核心server的启动流程-1660020117.mp4  202.60M
- |   ├──课时2-5.2 scheme和RESTStorage的初始化-1660020132.mp4  131.67M
- |   ├──课时3-5.3 apiserver中Pod数据的保存-1660020142.mp4  82.83M
- |   ├──课时4-5.4 apiserver中的限流策略源码解读-1660020152.mp4  111.44M
- |   └──课时5-5.5 apiserver重要对象和功能总结-1660020157.mp4  9.37M
- ├──章节6-第6章 kube-scheduler 调度pod的流程  
- |   ├──课时1-6.1 kube-scheduler的启动流程-1660020169.mp4  151.21M
- |   ├──课时2-6.2 kube-scheduler中的leaderelection选主机制解读-1660020182.mp4  150.22M
- |   ├──课时3-6.3 k8s的事件event和kube-scheduler中的事件广播器-1660020197.mp4  168.75M
- |   ├──课时4-6.4 k8s的informer机制-1660020206.mp4  79.69M
- |   ├──课时5-6.5 kube-scheduler中的informer源码阅读-1660020219.mp4  173.98M
- |   └──课时6-6.6 kube-scheduler利用informer机制调度pod-1660020237.mp4  217.53M
- ├──章节7-第7章  kube-controller-manager控制管理中心的作用  
- |   ├──课时1-7.1 controller-manager启动主流程-1660020250.mp4  132.38M
- |   └──课时2-7.2 ReplicaSet和对应的ReplicaSetController控制器-1660020266.mp4  187.30M
- ├──章节8-第8章  kubelet节点上控制容器生命周期的管理者  
- |   ├──课时1-8.1 kubelet启动主流程-1660020277.mp4  108.90M
- |   ├──课时2-8.2 kubelet节点自注册源码分析-1660020289.mp4  146.95M
- |   ├──课时3-8.3 基于NodeStatus和lease对象的心跳机制-1660020298.mp4  81.47M
- |   ├──课时4-8.4 syncLoop响应pod创建的过程-1660020308.mp4  123.31M
- |   ├──课时5-8.5 kubelet维护pod的内存管理器podManager源码解析-1660020317.mp4  76.76M
- |   ├──课时6-8.6 volumeManager中的desiredStateOfWorld理想状态解析-1660020331.mp4  196.31M
- |   ├──课时7-8.7 volumeManager中的reconciler协调器解析-1660020344.mp4  164.13M
- |   ├──课时8-8.8 statusManager同步pod状态-1660020358.mp4  155.72M
- |   └──课时9-8.9 probeManager监控pod中容器的健康状况-1660020370.mp4  137.74M
- └──章节9-第9章 kubelet稳定性保证Eviction驱逐和oom  
- |   ├──课时1-9.1 Kubelet Eviction驱逐解读-1660020377.mp4  20.27M
- |   ├──课时2-9.2 EvictionManager源码解读-1660020391.mp4  208.59M
- |   ├──课时3-9.3 容器qos和OOMScoreAdj的取值范围-1660020397.mp4  20.68M
- |   └──课时4-9.4 oomWatcher管理器源码解读-1660020404.mp4  59.72M
- 
