# CBM-Linux
Self-used scripts
## DD Debian 11
```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian 11  -pwd '<密码>' -port "<端口号>"
# -mirror "<镜像源>" = 可替换镜像源，官方镜像源列表：https://www.debian.org/mirror/list.html
# -pwd '<密码>' = 默认密码：LeitboGi0ro 或设置需要的密码
# -port "<端口号>" = 默认端口号：22 或设置自己要的端口号 (1~65535)
# -debian 11 = Debian 版本号：11 可选版本范围 7-after
# -hostname "random" = 主机名：random 或设置自己的主机名
```
