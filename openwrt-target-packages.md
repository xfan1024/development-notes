# OpenWRT目标软件包

## 系统设备实用工具

| Package Name                    | Comment                                                          |
| ------------------------------  | ---------------------------------------------------------------- |
| htop                            | 进程监视软件                                                     |
| atop                            | 系统和进程监视软件                                               |
| iftop                           | 网络流量监测工具                                                 |
| lspci                           | PCI设备信息枚举（OpenWRT目前仅提供busybox的applet）              |
| lsusb                           | USB设备信息枚举（OpenWRT目前仅提供busybox的applet）              |
| lsblk                           | 块设备信息枚举                                                   |
| fdisk                           | 磁盘分区操作软件                                                 |
| tmux                            | 终端复用器                                                       |
| ethtool                         | 网络接口配置工具                                                 |
| i2c-tools                       | i2c实用程序                                                      |
| minicom                         | 串口终端                                                         |
| openssl                         | 命令行加密解密软件                                               |

## 网络功能支持

| Package Name                    | Comment                                                          |
| ------------------------------- | ---------------------------------------------------------------- |
| openssh-sftp-server             | sftp服务器支持                                                   |
| sshtunnel                       | ssh隧道客户端支持                                                |
| ipset                           | iptables的扩展，支持ip集合匹配                                   |
| relayd(luci-proto-relay)        | 提供一种类似于桥的中继功能                                       |
| wireguard(luci-proto-wireguard) | wireguard客户端支持                                              |
| ppp-mod-pppol2tp                | l2tp客户端支持                                                   |
| ppp-mod-pptp                    | ppp客户端支持                                                    |

## 网络实用软件

| Package name                    | Comment                                                          |
| ------------------------------- | ---------------------------------------------------------------- |
| netcat                          | TCP,UDP测试工具                                                  |
| curl                            | http,ftp客户端工具                                               |
| wget                            | 下载器                                                           |
| tcpdump                         | 抓包软件                                                         |
| ipref                           | 网络质量诊断工具                                                 |
| bind-dig                        | DNS命令行实用工具                                                |

## VPN和Proxy工具

| Package name                    | Comment                                                          |
| ------------------------------- | ---------------------------------------------------------------- |
| openvpn                         | openvpn客户端、服务器软件                                        |
| xl2tpd                          | L2TP协议的服务端软件                                             |
| pptpd                           | PPTP协议的服务端软件                                             |
| shadowsocks                     | 轻量的加密隧道软件                                               |
