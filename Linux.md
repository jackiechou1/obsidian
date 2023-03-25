	Linux下 is not in the sudoers file 解决方法
	#切换到root
	su
	#编辑配置文件
	vim /etc/sudoers


```
Linux系统下，不小心按了ctrl+z命令后，退出了当前进程的执行界面，程序没有结束，只是被挂起了。

通过ps命令可以查看进程信息，这里不做详细介绍，可通过jobs命令查看被挂起的进程号

#jobs 

通过fg命令可以恢复进程到前台执行、bg命令恢复进程到后台执行。
```