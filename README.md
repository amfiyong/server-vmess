# SERVER-VMESS
> 服务端版本请使用 [xflash-panda/v2board](https://github.com/xflash-panda/v2board), 不要使用原版

## 主要特性
- 永久免费，并且完整开源
- 专属节点后端，只支持 [xflash-panda/v2board](https://github.com/xflash-panda/v2board) 面板
- 无需配置文件，和面板完美集成
- 更好的性能，更低的资源占用，减少大量无效数据传输
- 更简单的实现方式
- 陆续会有新特性支持

## 安装
**手动安装**
1. go >= 1.16.0
2. 依次运行
```
git clone https://github.com/xflash-panda/server-vmess.git
cd server-vmess/cmd/server
go build -o server-trojan -ldflags "-s -w"
chmod +x server-vmess
./server-vmess --api xxx --token xxx --node xxx
```
##  Thanks
* [Project X](https://github.com/XTLS/)
* [XrayR](https://github.com/XrayR-project/XrayR)
