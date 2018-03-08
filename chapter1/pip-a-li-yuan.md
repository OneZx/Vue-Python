> windows

- 在文件夹窗口输入 ` %APPDATA%`

![](/assets/appdata.png)

- 在跳转的文件夹下新建pip文件夹

![](/assets/roaming.png)

- 然后再pip文件夹中新建`pip.ini`,写入配置

![](/assets/pipin.png)

```
[global]

timeout = 60

index-url = http://mirrors.aliyun.com/pypi/simple/

trusted-host = mirrors.aliyun.com 
```

> 安装的时候

- pip install