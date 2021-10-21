# Ansible-application

#### 介绍
基于ansible自身模块应用
- 交换机自动化管理场景；
- Windows Server补丁自动更新场景；

##交换机自动化场景说明
此脚本支持思科、华为通用型交换机设备。

- 1、普通接口的重启
- 2、普通接口改绑定MAC接口
- 3、普通接口改绑定多个MAC的接口
- 4、绑定MAC的接口转普口接口
- 5、绑定MAC的接口更改绑定的MAC


##Windows Server补丁自动更新场景说明

- 1、检测winrm状态
- 2、配置wsus地址和策略
- 3、检测WSUS服务连接是否正常
- 4、获取待更新补丁清单
- 5、下载补丁
- 6、安装补丁
- 7、获取补丁安装结果


![更新补丁服务器准备](https://images.gitee.com/uploads/images/2021/1021/151240_8d7ca406_9861276.png "屏幕截图.png")
![更新补丁部分截图](https://images.gitee.com/uploads/images/2021/1021/150437_aa121d5d_9861276.png "屏幕截图.png")


