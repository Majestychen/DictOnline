在线英英词典说明文档:

功能描述:
       1.在线注册       
       2.在线登录验证   
       3.单词在线翻译    
       4.历史记录查询    
       5.退出
项目分析:
    整体难度一般,最主要的是各个功能模块的划分以及有机组合.导入数据表遇到特殊字符的解决方式.以及历史记录查询的实现细节.
    一共用了两张表,user,dict分别记录用户名,密码 以及 单词跟翻译.
    客户端链接服务端后出现功能选择界面,分别是: 注册,登录,退出!
    首先进行注册,注册完后返回登录界面,输入用户名跟密码登录,之后便可以进行
单词在线翻译,登陆后任意时刻输入(-1)退出,(?)历史记录查询.
    历史记录放在本地客户端所在的目录,设置为隐藏文件.且不同用户分别用不同文件保存历史记录,登录后输入(?)可访问.