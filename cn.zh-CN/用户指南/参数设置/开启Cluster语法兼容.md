# 开启Cluster语法兼容 {#task_al4_b4z_nfb .task}

云数据库Redis版的集群实例兼容社区Cluster相关语法，允许JedisCluster等客户端使用命令访问Cluster Nodes。在开启Cluster语法兼容后，您可以将自建的Cluster集群无缝迁移到阿里云上，无须修改业务代码。

-   实例架构类型为集群版；
-   实例网络类型为VPC。

1.  登录 [Redis 管理控制台](https://kvstore.console.aliyun.com/)。 
2.  单击目标实例的**实例 ID**或者操作列的**管理**。 
3.  在实例信息页的左侧导航栏中，单击**参数设置**。 
4.  在参数列表中找到cluster\_compat\_enable，单击其操作列的**修改**。 
5.  在弹出的对话框中将值修改为1，之后单击**确定**。 

    0表示关闭此功能，1表示打开，默认为关闭。

    更多参数信息请参见[参数设置](cn.zh-CN/用户指南/管理实例/参数设置.md#)。


