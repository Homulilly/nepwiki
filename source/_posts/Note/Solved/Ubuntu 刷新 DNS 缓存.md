---
title: Ubuntu 刷新 DNS 缓存
date: 2019-12-16 06:50:24
tags:
categories:
---

1. 使用 systemd
    ```
    # 清除缓存
    sudo systemd-resolve --flush-caches
    ```
    
    ```
    # 查看缓存大小
    sudo systemd-resolve --statistics
    ```

2. 使用 dns-clean
    ```
    使用systemd-resolve刷新DNS-Cache
    ```

