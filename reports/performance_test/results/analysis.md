# 测试分析

## 云主机性能测试分析

### 云主机存储

根据云主机存储的测试结果，Ceph 存储的 IOPS 比较低，出现低于 Eqlx 的情况。

在队列深度较小的情况下，Ceph 盘的利用率已经很高(超过 95%)，因此，当队列深度增加时，IOPS 变化不大。

> 根据测试结果，**Ceph 存储性能需要调优**。

### 云主机网络

由于云主机网络性能受其他因素影响较大，需要继续测试。