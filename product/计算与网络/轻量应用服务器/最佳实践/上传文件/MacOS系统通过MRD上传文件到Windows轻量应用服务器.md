## 操作场景
Microsoft Remote Desktop（以下简称 MRD） 是微软推出的适用于 Mac 机器的远程桌面应用程序， 本文档介绍 Mac 机器通过 MRD 快速上传文件至 Windows Server 2012 R2 操作系统的腾讯云轻量应用服务器。 

## 前提条件
- 本地计算机已下载并安装 MRD，您可前往 [Microsoft Remote Desktop for Mac Beta](https://install.appcenter.ms/orgs/rdmacios-k2vy/apps/microsoft-remote-desktop-for-mac/distribution_groups/all-users-of-microsoft-remote-desktop-for-mac) 进行下载安装。
- MRD 支持 Mac OS 10.10 及以上版本，请确保使用支持的操作系统。
- 已获取登录轻量应用服务器的管理员帐户及密码。
	- Windows 轻量应用服务器默认管理员帐户为 Administrator。
	- 如果您忘记了登录密码，请 [重置密码](https://cloud.tencent.com/document/product/1207/44575)。

## 操作步骤
### 获取公网 IP
登录 [轻量应用服务器控制台](https://console.cloud.tencent.com/lighthouse/instance/index)，在“服务器”页面中获取需上传文件轻量应用服务器的公网 IP。

### 上传文件
1. 启动 MRD，并单击 **Add Desktop**。如下图所示：
![](https://main.qcloudimg.com/raw/e69528d10e9a17dfa26119a090766c49.png)
2. 在弹出的 “Add Desktop” 窗口中，按以下步骤选择需上传的文件夹并创建连接。如下图所示：
![](https://main.qcloudimg.com/raw/fc241ce8e4744bde57476ea823fcef72.png)
  1. 在 “PC name” 处输入已获取的轻量应用服务器公网 IP。
  2. 单击 **Folders** 切换到选择文件夹列表。
  3. 单击左下角的<img src="https://main.qcloudimg.com/raw/89e7a3ff040849307cd1eb8bd878a2db.png" style="margin:-3px 0px">，并在弹出窗口中选择需上传的文件夹。
  4. 完成选择后，可查看需上传文件夹列表，并单击 **Add** 确认创建。
  5. 其余选项保持默认设置，完成创建连接。
即可在窗口中查看已成功创建的连接。如下图所示：
![](https://main.qcloudimg.com/raw/1c0eff28aa68a7f02e8f295917bb603b.png)
4. 双击打开新创建的连接，并在弹出的窗口中根据提示，输入轻量应用服务器的帐号和密码，单击 **Continue**。
5. 在弹出的窗口中单击 **Continue** 确认连接。如下图所示：
![](https://main.qcloudimg.com/raw/61b3d9566365183fcc1d92c2f6bc2e7b.png)
成功连接后将打开 Windows 轻量应用服务器界面。如下图所示：
![](https://main.qcloudimg.com/raw/5a524210acd13624af7263b6de3aea54.png)
7. 选择左下角的 <img src="https://main.qcloudimg.com/raw/87d894e564b7e837d9f478298cf2e292.png" style="margin:-3px 0px"> > **这台电脑**，即可看到已共享的文件夹。如下图所示：
![](https://main.qcloudimg.com/raw/b6a9fc9ef75131fab3549533187d24e3.png)
8. 双击打开共享文件夹，并将需要上传的本地文件复制到 Windows 轻量应用服务器的其他硬盘中，即完成文件上传操作。
例如，将文件夹中的 A 文件复制到 Windows 轻量应用服务器的 C: 盘中。

### 下载文件
如需将 Windows 轻量应用服务器中的文件下载至本地计算机，也可以参照上传文件的操作，将所需文件从 Windows 轻量应用服务器中复制到共享文件夹中，即可完成文件下载操作。


