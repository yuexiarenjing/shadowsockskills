# shadowsockskills
    
    根据自己的发行版安装 python-pip
    > ubuntu, debian, mint
    sudo apt-get install python-pip
    > fedora, centos
    sudo yum install python-pip
    > arch
    sudo pacman -S python-pip
    升级 pip
    >执行
    sudo pip install --upgrade pip
    用 pip 安装 shadowsocks
    sudo pip install shadowsocks
    使用 sslocal 命令运行 shadowsocks
    例：
    sslocal -s sg01-22.ssv4.net -p 22222 -b 127.0.0.1 -l 1080 -k password -m aes-256-cfb
    解释:
    > -s 后接想要用的服务器地址
    > -p 是服务器端口
    > -b 是监听地址，一般是127.0.0.1不要改
    > -l 是本地监听端口，可以自己选，一般是1080，或者1000-9999之间自己选一个
    > -k 是 shadowsocks 连接密码
    > -m 是加密方式， 我们统一都是 aes-256-cfb， 不要改
    浏览器插件配置请参见 http://ttt.tt/150
    
    about:config
