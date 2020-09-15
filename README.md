# mysql
使用set语句set password=password(“新密码”)
卸载完全，删除所有数据,先关闭跟MySql所有有关的进程,进入命令行(cmd)中输入taskkill /f /im mysqld-nt.exe然后找到MySql的根目录删除即可
登陆mysql，一般命令格式为：mysql> set password for 用户名@localhost = password('新密码');
