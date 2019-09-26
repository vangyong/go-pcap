# 镜像制作步骤：

## 准备工作
* go get github.com/google/gopacket
* rpm -ivh  libpcap

* mkdir -p $GOPATH/src/golang.org/x/
* cd $GOPATH/src/golang.org/x/
* git clone https://github.com/golang/net.git net
* go install net
* git clone https://github.com/golang/sys.git sys
* go install sys


## 编译
* go build device_util.go
* go build realtime_util.go
  