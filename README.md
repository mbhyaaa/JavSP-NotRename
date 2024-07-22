# Jav Scraper Package -NotRename

修改自[Jav Scraper Package](https://github.com/Yuukiy/JavSP)。

修改了JavSP.py、config.py、nfo.py程序。

在config.ini中添加判断，当File->enable_rename = no时，整理文件之前保存原始文件名，整理完成后再恢复原始文件名。

修复输出的nfo文件中\<num\>和\<cid\>标签的命名问题，用于适配[Jvedio](https://github.com/hitchao/Jvedio)。


## 安装
	请确保已安装 Python （此项目以 Python 3.8 开发）
	```
	git clone https://github.com/Yuukiy/JavSP.git
	cd JavSP
	pip install -r requirements.txt
	python JavSP.py
	```


## 许可

此项目的所有权利与许可受 GPL-3.0 License 与 [Anti 996 License](https://github.com/996icu/996.ICU/blob/master/LICENSE_CN) 共同限制。此外，如果你使用此项目，表明你还额外接受以下条款：

- 本软件仅供学习 Python 和技术交流使用

- 请勿在微博、微信等墙内的公共社交平台上宣传此项目

- 用户在使用本软件时，请遵守当地法律法规

- 禁止将本软件用于商业用途


