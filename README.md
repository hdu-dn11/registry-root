# Decentralized Network 11 Corporation for Assigned Names and Numbers (DN11_CANN)

## Description
root.zone 需要自己的权威根进行与文件同步（写死）

dn11_named.root 文件劫持递归服务器的根域名服务器（防止跑到公网）

dn11.zone 为TLD的权威服务器文件（需要主从同步，主TLD在172.16.7.53）