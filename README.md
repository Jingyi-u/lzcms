# lzcms

项目地址：
https://gitee.com/phplaozhang/LzCMS-LaoZhangBoKeXiTong

搭建完成后，进入后台管理，在管理员信息页面添加头像，并且抓包
![image](https://github.com/user-attachments/assets/5c3352b9-b743-4278-9b7e-21ca12043abb)

修改后缀为php,添加php代码：<?php phpinfo();?>，可以看到保存路径
![image](https://github.com/user-attachments/assets/fe383798-812a-4bdd-b87a-3eb33bd703d7)

存在文件上传漏洞，攻击者可执行任意代码获取服务器权限
![image](https://github.com/user-attachments/assets/a38e5f7f-ea4a-4c8b-9071-78dde64d8480)
