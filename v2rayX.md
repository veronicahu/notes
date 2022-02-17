V2rayX

一、服务器配置

1. 购买服务器（腾讯云 轻量应用服务器）

2. 安装镜像 Ubuntu

3. 重置root和ubuntu密码

4. SSL登录

   ![image-20220217110637853](/v2rayX.assets/image-20220217110637853.png)

   主机连接成功后

   `su root`

   `root password`

   <img src="v2rayX.assets/image-20220217110835891.png" alt="image-20220217110835891" style="zoom:50%;" />

5. `bash <(curl -L https://raw.githubusercontent.com/v2fly/fhs-install-v2ray/master/install-release.sh)`

   一直回车即可

6. 得到v2ray配置信息

   <img src="v2rayX.assets/image-20220217111140360.png" alt="image-20220217111140360" style="zoom:50%;" />

7. 打开服务器防火墙

<img src="v2rayX.assets/image-20220217111802625.png" alt="image-20220217111802625" style="zoom:50%;" />

二、mac 配置

1. 安装v2rayx

   `brew install --cask v2rayx`

2. 配置v2rayx

   <img src="v2rayX.assets/image-20220217111609212.png" alt="image-20220217111609212" style="zoom:50%;" />

3. 开启v2rayx，试试吧

三、可能遇到的问题

1. 开启后，网络不通：

   是防火墙的问题，添加防火墙规则即可。
