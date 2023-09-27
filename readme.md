1. 执行下面命令安装
   
```apt-get install build-essential autoconf automake libpcre3-dev libevent-dev pkg-config zlib1g-dev libssl-dev```

2. 拷贝当前 zip 文件到容器，执行 unzip 去解压

3. 执行下面命令
```
$ autoreconf -ivf
$ ./configure
$ make
$ make install
```

4. 执行 ```memtier_benchmark -h``` 命令
