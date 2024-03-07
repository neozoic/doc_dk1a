## 系统镜像烧写

DK-1A支持从EMMC引导启动和从SD卡引导启动。

### SD卡引导启动模式

#### 准备工作

- SD卡烧录工具**balenaEtcher** ，点击[此处]( https://etcher.balena.io/)下载并安装；

- 更新镜像文件，下载地址[PPOSv1.1.1](https://pp-os.bj.bcebos.com/vs680/system/dk1a-generic-1.1.1-system.zip) ，MD5：9a10b1008185d05e8c604781d84f9fcb ，并解压。

#### Step1

将SD卡插入电脑，并打开balenaEtcher；  

#### Step2

在balenaEtcher界面中选择“从文件烧录”，并在对话框中选择解压后以.img尾缀的镜像文件；

#### Step3

点击“选择目标磁盘”按钮，选择SD卡所在盘符；

#### Step4

点击“现在烧录！”按钮，开始烧录；

#### Step5

待烧录完成后，将SD卡从电脑中拔出，并插入到DK-1A的MicroSD卡槽中，即可正常开机启动；
