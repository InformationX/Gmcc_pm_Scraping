获取移动物业管理平台，某些特定信息的爬虫，为移动某地市代维内部使用。
使用selenium来做自动化登陆和页面浏览，基于chrome插件的实现
校验码问题，目前的解决办法为人工手动输入
模态框的数据获取问题：目前的解决办法为，将该模态框显示的内容的连接重新分析出来，
然后再重新打开，打开的页面就是这个模态框的页面代码，这时再获取里面的代码和内容，

将收集后的数据，汇总，过滤掉非该地市的内容，统计出不同意的信息，
最后将内容写入一个Excel文件中，该文件定义了文件的title，逐行写入信息。

本脚本在某些国产的所谓的安全软件，会报安全问题，因为其在频繁的操作。
