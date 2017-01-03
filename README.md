# ShareDevice

一个轻量级的安卓设备共享程序.
特点:

1.最少的环境依赖

2.即开即用,多平台支持(windows ,mac , linux).

3.支持一人操作,多人观看的行为模式


如果您喜欢这个项目请 star 这个项目  [源码地址](https://github.com/sunshine4me/ShareDevice)

![image](https://raw.githubusercontent.com/sunshine4me/ShareDevicePublish/win10-x64/index.png)

![image](https://raw.githubusercontent.com/sunshine4me/ShareDevicePublish/win10-x64/help.gif)

## windows 使用说明

1.下载相应的执行软本.
![image](https://raw.githubusercontent.com/sunshine4me/ShareDevicePublish/win10-x64/download.png)



2.运行 ShareDevice.exe

**如果是win7的话 需要先安装c++支持库 ,在下载的文件中有 "vc_redist.x64.exe" 这个文件.**

**如果发生 Failed to load the dll from [C:\Program Files\dotnet\host\fxr\1.0.1\hostfxr.dll] 错误,  请安装系统补丁 https://support.microsoft.com/en-us/kb/2533623**


3.在浏览器中通过 http://电脑IP:5020 进行访问.


## mac 使用说明
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

![image](https://raw.githubusercontent.com/sunshine4me/ShareDevicePublish/win10-x64/download.png)


4.对执行文件赋权限
```
chmod 777 ShareDevice
```
5.运行程序
```
./ShareDevice
```
6.在浏览器中通过 http://IP地址:5020 进行访问.
