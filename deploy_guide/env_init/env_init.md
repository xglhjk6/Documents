# EayunStack环境初始化

在EayunStack环境部署完成后，需要连接到Fuel节点，对环境进行初始化，便于后续环境维护。

> ###### 注意
> 初始化操作会在环境中所有节点生成节点列表及节点角色配置文件。

```
[fuel]$ eayunstack init
[ INFO  ] Generate node-list file ...
[ INFO  ] Copy node-list file to all nodes ...
[ INFO  ]    To node 172.16.100.11 ...
[ INFO  ]    To node 172.16.100.4 ...
[ INFO  ]    To node 172.16.100.10 ...
[ INFO  ]    To node 172.16.100.9 ...
[ INFO  ]    To node 172.16.100.6 ...
[ INFO  ]    To node 172.16.100.7 ...
[ INFO  ]    To node 172.16.100.8 ...
[ INFO  ]    To node 172.16.100.5 ...
[ INFO  ] Generate node-role file for fuel node ...
[ INFO  ] Generate node-role file for openstack node ...
[ INFO  ]    To node 172.16.100.11 ...
[ INFO  ]    To node 172.16.100.4 ...
[ INFO  ]    To node 172.16.100.10 ...
[ INFO  ]    To node 172.16.100.9 ...
[ INFO  ]    To node 172.16.100.6 ...
[ INFO  ]    To node 172.16.100.7 ...
[ INFO  ]    To node 172.16.100.8 ...
[ INFO  ]    To node 172.16.100.5 ...
```