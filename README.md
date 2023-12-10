# CBM-Linux

Self-used scripts

## DD Debian 

### 修改参数

```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian <7-12>  -pwd '<密码>' -port "<端口号>" -hostname "<主机名>"
```
> **可添加参数**
>
> -debian <7-12> = 设置 Debian 版本：7-12
>
> -pwd '<密码>' = 设置 root 密码
> 
> -port "<端口号>" = 设置端口号：(1~65535)
> 
> -hostname "<主机名>" = 设置主机名
> 
> -mirror "<镜像源>" = 替换镜像源，官方镜像源列表：https://www.debian.org/mirror/list.html

### 默认参数

> 默认密码：LeitboGi0ro
>
> 默认端口号：22 或安装前系统默认端口号

#### Debian 8 64位

```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian 8  -pwd '<密码>'
```

#### Debian 9 64位

```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian 9  -pwd '<密码>'
```

#### Debian 10 64位

```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian 10  -pwd '<密码>'
```

#### Debian 11 64位

```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian 11  -pwd '<密码>'
```

#### Debian 12 64位

```sh
wget --no-check-certificate -qO InstallNET.sh 'https://raw.githubusercontent.com/ShenDoyle/CBM-Linux/ef530fe3efbecf122f6712e2d02021680a2a30fb/Scripts/InstallNET.sh' && chmod a+x InstallNET.sh && bash InstallNET.sh -debian 12  -pwd '<密码>'
```
