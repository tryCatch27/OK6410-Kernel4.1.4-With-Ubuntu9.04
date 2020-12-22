From url:https://bbs.elecfans.com/jishu_506283_1_1.html

Target:OK6410 + Kernel-4.1.4 + Ubuntu9.04

Step1:
    下载内核，修改板级文件，并对新内核进行配置；
Step2:
    制作SD卡启动环境；
Step3:
    下载ubuntu文件系统，并修改在解压目录修改启动设置；
Step4:
     将kernel生成的档案与文件系统关联；
Step5:
     将zImage和ubuntu放入SD中的对应分区；
Step6:
     将SD卡插入OK6410，上电，设置uboot从SD卡启动；
Step7:
     重新启动开发板。完成移植
