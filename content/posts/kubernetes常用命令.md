---
title: "Kubernetes常用命令"
date: 2019-05-28T14:02:07+08:00
disqus: false
description: ""
tags: [kubernetes]
---

#### 节点开启调度
```bash
kubectl taint nodes 172.16.119.109 node-role.kubernetes.io/controlplane:NoSchedule-
```




