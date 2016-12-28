# ShareDevicePublish
一个轻量级的安卓设备共享程序,无需安装任何运行环境,双击运行启动. 支持 windows ,mac , linux 多个平台.


[源码地址](https://github.com/sunshine4me/ShareDevice)


![image](https://raw.githubusercontent.com/sunshine4me/ShareDevicePublish/win10-x64/help.gif)
## windows 使用说明
1.下载相应的执行软本.

2.运行 ShareDriver.exe

3.在浏览器中通过 http://IP地址:5020 进行访问.


## mac/linux 使用说明

1. 安装homeBrew
```
curl -LsSf http://github.com/mxcl/homebrew/tarball/master | sudo tar xvz -C/usr/local --strip 1
```

2. 安装openssl
```
brew install openssl
ln -s /usr/local/opt/openssl/lib/libcrypto.1.0.0.dylib /usr/local/lib/
ln -s /usr/local/opt/openssl/lib/libssl.1.0.0.dylib /usr/local/lib/
```


3.下载相应的执行软本

4.对执行文件赋权限
```
chmod 777 ShareDriver
```
5.运行程序
```
./ShareDriver
```
6.在浏览器中通过 http://IP地址:5020 进行访问.


![image](https://raw.githubusercontent.com/sunshine4me/ShareDevicePublish/win10-x64/download.png)
