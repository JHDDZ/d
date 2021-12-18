项目地址：https://github.com/maintell/webBenchmark （来自：https://hostloc.com/thread-692122-1-1.html）


## 怎样编译适合你的环境架构的二进制程序？


首先安装Git和Golang


CentOS：`yum install git golang`

Debian/Ubuntu：`apt install git golang`

Termux：`pkg install git golang`

然后

```
git clone https://github.com/maintell/webBenchmark.git
cd webBenchmark
go build
```

国内鸡：

```
export GOPROXY=https://goproxy.io
git clone https://ghproxy.com/github.com/maintell/webBenchmark.git
cd webBenchmark
go build
```


## 提供几个已经编译好的


架构：Arm64+Linux

快速运行

```
wget -qO webBenchmark https://cdn.jsdelivr.net/gh/JHDDZ/d@main/webBenchmark_linux_arm64
chmod +x webBenchmark
./webBenchmark -c 32 -s http://example.link
```

注意替换下载链接

---

架构：Arm64+Android
可在Termux下运行

快速运行

```
wget -qO webBenchmark https://cdn.jsdelivr.net/gh/JHDDZ/d@main/webBenchmark_android_arm64
chmod +x webBenchmark
./webBenchmark -c 32 -s http://example.link
```

注意替换下载链接

