## 🛠️ PE启动盘制作 

- #### 准备工具
	>* 一台能正常使用的电脑
	>* 一个不小于8G的U盘
	>* U盘启动制作工具：[**优启通**](https://www.123pan.com/s/TktA-Jgvyv)
	>* 下载工具：[**迅雷**](https://www.xunlei.com/)

  ***注：以下操作会清空磁盘、U盘文件，如有重要文件请先备份再进行！***
- #### 下载系统镜像
	复制下面链接到迅雷下载
	```bash
	# win10镜像链接
	ed2k://|file|Win10_22H2_China_GGK_Chinese_Simplified_x64.iso|5687615488|937058F92F1EE4B5B4FCD1450C5AF212|/
	```
	```bash
	# win11镜像链接
	ed2k://|file|windows_11_version_22h2_updated_nov_2022_x64_dvd_2c7e96c3.iso|5673539584|EB8FF2B481BB6AFE71B2784C6485733B|/
	```
- #### 开始制作PE

	插上U盘，打开刚刚下载的优启通（下载下来的是压缩包，需要先解压），双击打开`EasyU_v3.7.exe`这个应用程序
	
	![](https://img1.imgtp.com/2022/12/14/ZadbwsS8.png)
	
	选择你要制作PE的U盘，点击`全新制作`
	
	![](https://img1.imgtp.com/2022/12/14/NHkdhxDH.png)	
	
	制作完成后，将下载好的系统镜像复制到U盘里面，至此U盘PE已经制作完成
	
	![](https://img1.imgtp.com/2022/12/14/R9JaGq2M.png)     
	
## 💾 磁盘分区
- #### 分区

	将制作好的PE U盘插到要安装系统的电脑上，开机等待进入PE系统即可，顺利进入后打开桌面上的DG分区工具
	
	![](https://img1.imgtp.com/2022/12/14/AQYnklZb.png)
	
	选中你需要安装系统的磁盘右键`转换分区表类型为GUID格式`（如果硬盘原本格式为GUID则可跳过此步骤）紧接着选择`删除所有分区`
	
	![](https://img1.imgtp.com/2022/12/14/WsPUSNLE.png)
	
	选择`是`
	
	![](https://img1.imgtp.com/2022/12/14/5Q2QQW0K.png)
	
	完成上诉步骤后点击`保存更改`
	
	![](https://img1.imgtp.com/2022/12/14/OdL5IjQr.png)
	
	选择`是`
	
	![](https://img1.imgtp.com/2022/12/14/Zk05Yk74.png)
	
	选中刚刚删除所以分区的磁盘，点击`快速分区`
	
	![](https://img1.imgtp.com/2022/12/14/9KVyW6HT.png)
	
	选择GUID，分区数目根据硬盘大小可自行决定，勾选`重建新ESP分区``创建MSR分区`这两个选项，其中ESP分区分配300MB的空间，选择`对齐分区到此扇区数的整倍速为4096扇区`，最后点击`确定`
	
	![Snipaste_2022-07-20_17-25-32.png](https://img1.imgtp.com/2022/12/14/ekN9amSH.png)
	![Snipaste_2022-07-20_17-33-37.png](https://img1.imgtp.com/2022/12/14/ZgV7Mg9N.png)
## ⚙️ PE下系统安装 

- #### 安装

	到这里，DG分区工具的动作就已经结束了。退出DG分区工具，打开桌面上的EIX系统安装工具进行系统安装了
	
	![Snipaste_2022-07-20_17-34-31.png](https://img1.imgtp.com/2022/12/14/i7RXb5Yh.png)
	
	左侧栏选中你需要安装的系统版本，右侧栏选中刚刚分好区的磁盘盘符，一般默认为C盘，如果不能确定可以再打开DG分区工具确定所在的盘符或者根据磁盘大小来确定盘符，点击`一键恢复`
	![Snipaste_2022-07-20_17-36-36.png](https://img1.imgtp.com/2022/12/14/oJL5xcS5.png)
	
	点击`确定`
	
	![Snipaste_2022-07-20_17-37-34.png](https://img1.imgtp.com/2022/12/14/LnN3eTNg.png)
	
	至此，PE下的动作已经完成，待进度条完成后重启黑屏时移除U盘即可进行系统安装了
	
	![Snipaste_2022-07-20_17-37-46.png](https://img1.imgtp.com/2022/12/14/Fw8HeAKu.png)






