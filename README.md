# airbug
Airbug(空气洞),一个长期开放用于收集漏洞poc以及详情的学习平台,用于打发闲暇的无聊时光。  

所有POC文件按照一定格式编写，且支持python3.x，为了方便操作，Airbug平台所有网络访问需要使用[黑客们使用的http底层网络库 - hack-requests](https://github.com/boy-hack/hack-requests)引擎编写。  

- 因为使用了`hack-requests`，需要安装 `pip3 install HackRequests`
## Poc文件格式
POC内容用`poc(arg,**kwargs)`函数封装，不关注其他细节。