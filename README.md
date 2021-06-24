<p align="center">
  <img width="200px" src="./doc/img/logo_ehoney_black.svg" alt="Ehoney" />
  <br/>
  <br/>
  <h1 align="center">Ehoney 欺骗防御系统</h1>
  <br/>
</p>


> ⭐️ Ehoney欺骗防御系统通过部署高交互高仿真蜜罐及流量代理转发，再结合自研密签及诱饵，将攻击者攻击引导到蜜罐中达到扰乱引导以及延迟攻击的效果，可以很大程度上保护业务应用以及主机的安全。⭐️   

![介绍视频](./doc/img/介绍.gif)



## 📝 特点

- **支持丰富的蜜罐类型**

1. **通用蜜罐**： SSH 蜜罐、Http蜜罐、Redis蜜罐、Telnet蜜罐、Mysql蜜罐、RDP 蜜罐
2. **IOT蜜罐**：  RTSP 蜜罐
3. **工控蜜罐**： ModBus 蜜罐



## ⛴ 环境准备

- **系统要求**: CentOS 7
- **配置要求**: 内存4G、磁盘空间10G以上

> Note: 以上的配置要求为系统运行的最优配置

<br>

## 🔧 快速部署

```shell
git clone https://github.com/seccome/Ehoney.git
cd Ehoney && chmod +x quick-start.sh && ./quick-start.sh
```

此安装过程会比较耗时、耐心等待后看到如下提示语

​			**all the services are ready and happy to use!!!**

代表安装成功。

访问http://IP:8080/decept-defense 进入系统登录页
默认账户密码
       <font color=Blue>用户名: admin</font>
       <font color=Blue>密码: 123456</font>

<br>

## 🖥️ 使用演示

![操作视频](./doc/img/操作视频.gif)

系统的详细使用文档请参考[这里](https://www.showdoc.com.cn/1432924569255366?page_id=7002138596779961)

<br>

## 🚀 效果展示

- **攻击大屏**

![攻击事件大屏](./doc/img/攻击事件大屏.png)

- **蜜罐拓扑**

![蜜罐拓扑图](./doc/img/蜜罐拓扑图.png)

- **告警列表**

![告警列表](./doc/img/告警列表.png)



## 🙏 关于 

如果大家对系统有好的建议或想法, 请[创建issue](https://github.com/seccome/Ehoney/issues/new ), 我们会及时回复并处理。

