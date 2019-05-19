# [extHUB](https://github.com/Qful/extHUB) 
[![sites](Qful/qitas.png)](http://www.Qful.net)
####  qitas@qitas.cn
### [extHUB简介](https://github.com/Qful/extHUB) 

[extHUB](https://github.com/Qful/extHUB) 是Qful项目中外置板卡工程，通过extHUB可以级联调用多台PC设备及相关的资源，和[intHUB](https://github.com/Qful/intHUB) 定位不同互为补充，同时也是几大计算设备的强力支持。

extHUB将各种输入输出进行汇集，可以服务一台主机，也可以服务多台主机，但设备偏向服务多台主机设备，形成资源的互补和增强。

extHUB的一个应用场景是在外设资源有限，例如显示器和键鼠，在一个用户需要通过一套输入输出环境操作多台设备的场合，需要一个更有针对性的DEMUX HUB设备，通过快捷智能的切换完成资源的复用。

设备的形态可以是传统的HUB形态，也可以被外部的各种设备集成在内部，实现更多途径的指令切换，所以本仓库用于设计相应的核心单元，完成核心的控制和输入输出管理，更方便的被各种网络整合为一部分，也方便接入各种智能化的管理网络。

板卡核心功能：

* KVM管理
* 路由器
* 物联网关

实现的策略包括：

* 集成ETH和USB转换设备，通过USB接入到PC端，从而满足一根网线连接多个设备，并且这多个设备的网络可管理
* 集成无线收发器件辅助相应的射频信号处理

### [工程目录](https://github.com/Qful)

* [文档](docs/)
* [资源](src/)
* [KVM](KVM/)
* [IOTHub](IOTHub/)

### [Q资源](https://github.com/Qful)

* [Q软件](https://github.com/OS-Q)
* [Q硬件](https://github.com/sochub)
* [Q智慧](https://github.com/tfzoo)
* [Q品质](https://github.com/qitas)

### www.Qful.net