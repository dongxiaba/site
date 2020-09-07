---
title: "如何用golang构建一个bittorrent客户端"
date: 2020-09-07T18:05:40+08:00
tags: ["golang","bittorrent","p2p"]
featured_image: ""
description: "翻译自https://blog.jse.li/posts/torrent"
---

BitTorrent是用于在Internet上下载和分发文件的协议.与传统的客户端/服务器关系不同. 在传统的客户端/服务器关系中.下载器连接到中央服务器（例如：在Netflix上观看电影或加载您正在阅读的网页). BitTorrent网络中的参与者（称为peers)之间交换下载文件的分块-这就是p2p(peer-to-peer). 我们将研究其工作原理.并建立自己的客户端.该客户端可以找到peers并在它们之间交换数据.  
![avatar](/img/5fx57tgniq.png)