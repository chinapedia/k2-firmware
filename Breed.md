斐讯K2新版 22.6.511.69 刷Breed

* 登录 http://192.168.2.1 
* 高级设置 -> 系统设置 -> 自动升级 -> 自定义升级时间 -> 开启。之后就是按照[a大的方法](http://www.iytc.net/wordpress/?p=1624)操作了。

点选时间中的右侧下拉分钟选择框，鼠标箭头（手势）放在05上，点击鼠标右键，在Firefox或傲游浏览器“审查元素”（傲游浏览器先按“F12”按键打开审查页面后再点击定时重启）：

双击"05"，改为你要执行的命令：

改为：

 05 | /usr/sbin/telnetd -l /bin/login.sh

在定时重启路由器页面上重新选择05之后（这里要注意，一定要重选，并且重选后可以看到05后面自己输入的字符）：

然后保存 就可以开启telnet 用breed助手刷breed了

参考：
* https://www.right.com.cn/forum/thread-325258-1-1.html
* http://www.iytc.net/wordpress/?p=1624