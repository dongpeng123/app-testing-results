#系统测试流程
1、制作ISO到U盘
$ dd if=android.iso of=/dev/sdd

2、安装或U盘启动（物理机）

3、安装好系统后设置-应用兼容性-打开可兼容使用arm库的应用 (必须，否则第三方应用好多不可用)

4、安装第三方应用 ，可通过U盘安装，也可通过脚本。
  方法1）U盘：直接单击即可安装
  方法2）脚本安装。
       A）git clone git://192.168.0.185/openthos-apps 至本地工作机-内含APK包及脚本文件
       B）阅读openthos-apps 下的readme文件，修改好PATH后执行脚本 即可安装测试所需第三方包
  
5、测试系统（包含如下几个模块）



