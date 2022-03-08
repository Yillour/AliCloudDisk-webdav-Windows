# AliCloudDisk-webdav-Windows

在Windows实现阿里云盘的webdav服务并挂载

aliyundrive-webdav.exe为另一个开源项目编译文件，[项目地址](https://github.com/messense/aliyundrive-webdav)

start.bat为启动程序bat，使用需将<Your refresh-token> 改为你在浏览器登录后获取的token
  
由于单靠bat文件需要命令窗口一直践行才能保持webdav开启状态，因此增加了一个vbs来屏蔽命令窗口，可以直接双击vbs文件实现程序后台运行。
  
 在vbs文件内需要将D:\Programs\aliyundrive-webdav\start.bat改为你的文件存放地址
  
 推荐将vbs文件放在系统的启动文件夹，以实现开机自启动，后台占用并不高。

