ssr-python
一个Shell脚本，集成SSR多用户管理，流量限制，加密更改等基本操作。是一个基于ShadowsocksR官方的mujson的辅助脚本。方便用户操作，并且支持快速构建SSR服务环境。

系统支持
Ubuntu 14
Ubuntu 16
Debian 7
Debian 8
CentOS 6
CentOS 7

功能
全自动无人值守安装，服务端部署只需一条命令，您和SSR都是如此的优雅：）
一键开启、关闭SSR服务
添加、删除、修改用户端口、密码和连接数限制
支持傻瓜式用户添加,小白也可以用
自由限制用户端口流量使用及端口网速
自动修改防火墙规则
自助修改SSR加密方式、协议、混淆等参数
自动统计，方便查询每个用户端口的流量使用情况
自动安装Libsodium库以支持Chacha20等加密方式
支持一键构建ss-panel-V3-mod,前端后端自动对接，无需额外操作（仅开发版可用）
傻瓜式的BBR、锐速、LotServer一键构建（有风险，仅开发版可用）
可自定义的服务器巡检，故障自动重启服务，确保链接稳定有效
可对配置进行备份、还原，迁移服务器只需在新服务器上还原配置，无需重复设置
支持IP黑名单功能，可通过端口查询，直接加入黑名单，禁止该IP访问服务器的所有服务
允许针对不同用户限制帐号有效期，到期自动删除帐号
一键修改DNS

安装
wget -q -N --no-check-certificate https://raw.githubusercontent.com/steamsv/SSR-Bash-Python/master/install.sh && bash install.sh

卸载
wget -q -N --no-check-certificate https://raw.githubusercontent.com/steamsv/SSR-Bash-Python/master/install.sh && bash install.sh uninstall
