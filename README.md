openvpn-build-helper
====================

openvpn官方提供了适用于各个系统下的openvpn封装工具：[openvpn-build](https://github.com/OpenVPN/openvpn-build)

对于Windows下面的封装，提供了nsi脚本。但是缺乏一些相关变量和一些预编译的二进制文件。

为了方便各位重新编译openvpn或者需要封装特定配置文件到安装程序中，所以建了这个项目……果然是很没技术含量的说。

##所以我到底干了什么？
0.从openvpn build同步过来的脚本加了必要的一些config，从openvpn.net提供的安装文件解包出二进制文件。然后添加了自己的配置文件和README。

1.如果openvpn build上游更新就合并过来。

2.如果openvpn二进制文件更新同样合并到pre-bin。