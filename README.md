### openshift4 使用与运维手册

刚开始写，平台基本使用和运维内容都会有。基于4.4 同样适用其他 4.x 差异不大。

---

目录
* 集群安装与配置管理
  * [4.7 在线安装 DHCP方式](./cluster_install_and_managerment/openshift4.7-install-online-DHCP.md)
  * [4.3 离线部署 DHCP方式](https://github.com/cai11745/k8s-ocp-yaml/blob/master/ocp4/2020-02-25-openshift4.3-install-offline-dhcp.md)
  * [4.4 在线部署 静态IP(支持all-in-one单点)](https://github.com/cai11745/k8s-ocp-yaml/blob/master/ocp4/2020-02-25-openshift4.4-install-online-staticIP-allinone.md)
  * [离线升级4.5->4.6](./cluster_install_and_managerment/offline-upgrade-4.5-to-4.6.md)
  * [AWS公有云安装openshift4](./cluster_install_and_managerment/openshift4-install-on-aws.md)
  * [添加worker node](./cluster_install_and_managerment/add-worker-node.md)


* 权限与认证
  * [访问web控制台](./user_permissions/web-console.md.md)
  * [使用HTPasswd方式管理用户](./user_permissions/使用HTPasswd方式管理用户.md)
  * [移除kubeadmin默认管理员](./user_permissions/remove-kubeadmin.md)

* 存储管理
  * [nfs-provisioner提供storageclass动态存储](./storage/nfs-provisioner提供storageclass动态存储.md)

* 日志与监控
  * [日志系统EFK安装与配置](./logging_and_monitoring/日志系统EFK安装与配置.md)

* 镜像仓库
  * [安装内部image_registry及存储持久化](./image_registry/安装内部image_registry及存储持久化.md)
  * [使用Samples-Operator更新ImageStream](./image_registry/使用Samples-Operator更新ImageStream.md)

* 应用商店
  * [搭建私有helm仓库及图形管理界面](./application_store/搭建私有helm仓库及图形管理界面.md)
  * [离线部署operatorhub并批量导入](./application_store/离线部署operatorhub并批量导入operator.md)

* ServiceMesh
  * [ServiceMesh简介与安装](./ServiceMesh/ServiceMesh简介与istio安装.md)

* DevOps
  * [Pipeline(Tekton)简介与场景示例](./DevOps/openshift-pipeline-Tekton简介与场景示例.md)

* 资源管理--未就绪

* 应用管理--未就绪


有问题可以联系我或者github提issue，欢迎共同完善。  


**扫一扫，关注微信公众号，不迷路，实时分享容器平台技术。或者直接搜 老菜**

<div align="center"><img width="300" height="300" src="./images/gongzhonghao.jpeg"/></div>
