# Javase
Javase基础程序


Maven的Settings.xml中的repository需要配置一些内网地址，可以参考同事机器上的配置。

启动类为：com.chinaway.trailer_gto_server.TrailerApplication，运行时需要在VM OPTION参数中加上如下参数：

-Dapp.id=trailer_gto_server -Dapollo.meta=http://172.16.1.88:8080 -Dapollo.cacheDir=/opt/data/trailer_gto_server_apollo_cache -Denv=DEV

项目所有配置均在Apollo配置中心，可登录：test.apollo.chinawayltd.com，搜索 trailer_gto_server 找到。
