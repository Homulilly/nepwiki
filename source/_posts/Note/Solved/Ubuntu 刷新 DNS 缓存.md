---
title: Ubuntu 刷新 DNS 缓存
date: 2019-12-16 06:50:24
tags:
categories:
---

1. 使用 systemd
    ```bash 
    # 清除缓存
    sudo systemd-resolve --flush-caches
    
    # 查看 DNS 缓存大小
    sudo systemd-resolve --statistics
    ```

2. 使用 dns-clean
    ```bash
    sudo /etc/init.d/dns-clean start
    ```

