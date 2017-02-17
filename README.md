# python-apk
python 打包资料包

！！！必须安装了python,并且正确配置环境变量

1，把签名apk放在python打包文件路径下
2，android_channels.txt存放渠道名，可以添加，删除，但是文件名不要改变
3，channel.py 注意，里面包含了windows和mac两种系统的配置，所以要根据自己的环境修改
4，命令行切换到python打包文件路径下，python channel.py app-debug4j.apk
5,执行完，会生成一个res文件夹，内部还有一个zipalign文件夹
6.
