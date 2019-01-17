# Server-Settings For Windows
## 1.命令行代码
下载免费版XShell: https://www.netsarang.com/zh/free-for-home-school/

安装之后点击左上角 **文件 -> 新建**

点击**连接**

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/XShellHost.png" width='400'/>

在**名称**可以随意输入

**主机**输入从管理员处拿到的IP

**端口号**除特别情况（会另行知会）都是22

点击**用户身份验证**

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/XShellUserPasswd.png" width='400'/>

**用户名**输入从管理员处拿到的用户名

**密码**输入从管理员处拿到的密码

## 2.配置自己的服务器环境

**使用网络**
在自己的电脑上使用编辑器打开**FUDAN.py**

<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/Fudan.png" width='400'/>

在18，19行的**你的学号**和**你的密码**处输入自己的复旦学号和密码。

使用WinSCP将Fudan.py文件上传到服务器自己的文件夹*/home/你的账户*下。

使用XShell链接到服务器。运行如下代码:
```
python2 FUDAN.py
```

等三十秒钟之后，使用**Ctrl+C**停止程序。

使用如下代码来检查是否连接到网络:

```
ping www.baidu.com
```
如果出现下面的情况，说明你已经成功连接到网络（否则请联系管理员）。使用**Ctrl+C**停止程序。
<img src="https://github.com/LibertFan/Server-Settings/blob/master/img/FudanSuccess.png" width='200'/>


下载最新版的Anaconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/

```
bash AnacondaXXXX.sh
```
在安装的最后一步是否要把anaconda下的python作为自己的默认python，选择yes。

这一步操作会将anaconda下的python路径添加到**/home/你的账户/.bahsrc**下。



## 3.

## 4.
