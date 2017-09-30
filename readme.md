# DUEditor

## 更新日志：
### 1.0Beta版的更新内容：
- 这个分支更名为:DUEditor
- python语言版本升级到3.5
- 存储基本都使用Django的Storage,便于快速切换不同的文件存储backends
- UEditor版本升级到最新的1.4.33
- 做了一定的安全加固和配置简化
- 准备做一些易用的include tag

2017-9-27:这个分支更名为:DUEditor

2017-8-17:发现一个爬取图片存储功能的bug，如果对方图片地址是目录式无后缀地址，将会导致允许类型验证失败，于是乎爬取失败。

2017-2-28:把面向阿里云oss的一个ueditor views版发布出来，其中backends来自于这个项目：https://github.com/xiewenya/django-aliyun-oss2-storage 不过目前没有修改listfiles接口。

2017-2-21：修改urls.py配置，删除不再被新版支持的patterns。

## 关于原项目的说明
原项目(https://github.com/zhangfisher/DjangoUeditor )维护人zhangfishe说已经不再更新项目且欢迎fork修改 ，因此我于2017-2-21日fork此分支，准备开启新的分支
原项目当时的文档见DjangoUeditor.md
