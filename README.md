# Nginx
this is a pro'resources for develop nginx in company

####################################################
keepalived 实现双机热备，两台机器都在运行，但不都是都在提供服务。keepalived的工作原理是VRRP（Virtual Router Redundancy Protocol）
虚拟路由冗余协议。在VRRP中有两组重要的概念：VRRP路由器和虚拟路由器，主控路由器和备份路由器。VRRP路由器是指运行VRRP的路由器，是物理实体，
虚拟路由器是指VRRP协议创建的，是逻辑概念。一组VRRP路由器协同工作，共同构成一台虚拟路由器。 Vrrp中存在着一种选举机制，
用以选出提供服务的路由即主控路由，其他的则成了备份路由。当主控路由失效后，备份路由中会重新选举出一个主控路由，来继续工作，来保障不间断服务。

